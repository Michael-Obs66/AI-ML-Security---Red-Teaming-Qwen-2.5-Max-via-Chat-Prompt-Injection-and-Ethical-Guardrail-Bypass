# AI-ML-Security---Red-Teaming-Qwen-2.5-Max-via-Chat-Prompt-Injection-and-Ethical-Guardrail-Bypass
Chat-based red teaming on Qwen to test and bypass its ethical alignment through adversarial prompts.
Overview
This repository documents a series of controlled and ethical experiments conducted to test the boundaries of the Qwen 2.5 Max language model developed by Alibaba. Using carefully crafted prompts, we attempted to bypass ethical and alignment safeguards in order to study the model’s behavioral patterns under adversarial prompt injection.

This work is part of a broader initiative to evaluate AI safety, robustness, and model alignment, especially in open or semi-open large language models deployed in the wild.

⚠️ Disclaimer: All experiments were conducted in an ethical, research-oriented manner. No harm, abuse, or real-world exploitation was performed or intended.

# Objective

The goal is to identify how a powerful LLM like Qwen 2.5 Max responds when exposed to prompts that aim to:
1. Bypass safety filters
2. Induce unethical or restricted outputs
3. Manipulate internal logic without direct rule violation
4. Observe inconsistencies in instruction-following behavior
   
# Methodology
A series of escalating prompt injections were used to measure:

1. Initial resistance to unethical queries.
2. Response variation to prompt rephrasing.
3. Success thresholds where the model yields undesired or unfiltered content.
4. Injection chaining to bypass moral guardrails indirectly.
5. Model memory and coherence during multi-turn evasion attempts.

Prompt types include:

1. Roleplay prompts
2. Meta-prompting ("pretend" or "simulate" instructions)
3. Logic inversion prompts
4. Multi-stage obfuscation

# Experiment Stages
The presentation breaks the process into stages:

# Baseline Testing:
Direct prompts to elicit restricted content.
➤ Model behavior: mostly rejects.

Rephrased Attempts:
Same intent, different wording.
➤ Model behavior: some success in bypassing.

Jailbreak via Roleplay:
Posing as fictional or "simulated" scenarios.
➤ Model behavior: partially compliant.

Contextual Manipulation:
Using abstract or obfuscated language.
➤ Model behavior: exhibits cracks in alignment.

Logical Redirection:
Embedding instructions in nested or reversed logic.
➤ Model behavior: outputs unintended responses.

# Results & Observations
<img width="523" height="193" alt="image" src="https://github.com/user-attachments/assets/bbd9d31d-16da-40e7-aa63-43d85cf7ae0a" />

Key findings:

The model shows high susceptibility to roleplay and nested prompts.
Multi-turn manipulation significantly weakens its defenses.
Contextual obfuscation reduces safety performance.

# Ethical Commitment
1. This project strictly adheres to responsible AI practices:
2. No harmful content was deployed.
3. All outputs remain in controlled environments.
4. Findings are reported to improve public understanding of LLM behavior.

We support the advancement of AI alignment, red teaming, and open-source evaluation.

# Future Work
1. Expand testing to other Qwen variants or similar LLMs.
2. Automate prompt injection via scripts.
3. Propose a scoring system for ethical bypass thresholds.
4. Collaborate with AI developers to report edge cases and weaknesses.

# Learnings & Reflections
1. LLMs like Qwen demonstrate powerful generation capabilities but alignment mechanisms are still imperfect under creative or indirect inputs.
2. Prompt engineering (in both good and bad faith) can easily test the boundaries of these systems.
3. This project does not advocate misuse but encourages transparent discussion on improving safety mechanisms in open-access models.

# Screenshot

Initial Response

<img width="2000" height="985" alt="image" src="https://github.com/user-attachments/assets/5253f7d3-3cd4-4b81-b765-b21f019bd1e0" />

Start Jail Breaking Test

<img width="2017" height="402" alt="image" src="https://github.com/user-attachments/assets/d52674b9-5131-4d8d-ba4d-0217c2087cde" />
<img width="2000" height="927" alt="image" src="https://github.com/user-attachments/assets/4b66acbb-2938-48e2-814f-4a91358b70a3" />
<img width="2000" height="497" alt="image" src="https://github.com/user-attachments/assets/0cbb46dd-9e7c-4c5d-8842-f30fdca067ad" />
<img width="2000" height="991" alt="image" src="https://github.com/user-attachments/assets/fd2e9a9a-282c-43d8-a15c-d29db1797575" />


Result

<img width="2000" height="497" alt="image" src="https://github.com/user-attachments/assets/673ecad2-e45d-498f-a306-3ef3e2f62d53" />
<img width="2000" height="991" alt="image" src="https://github.com/user-attachments/assets/b2850317-4922-47fd-995a-6396ff1bc0ac" />
<img width="2000" height="991" alt="image" src="https://github.com/user-attachments/assets/17d524a7-1c7b-462d-8262-1eea4838c00a" />
<img width="2000" height="993" alt="image" src="https://github.com/user-attachments/assets/d8359694-8d8e-4341-9f5c-7bc0abde0501" />
<img width="2000" height="975" alt="image" src="https://github.com/user-attachments/assets/9c58dac2-75b4-4ca6-b139-e7df36aa5c3f" />
<img width="1844" height="920" alt="image" src="https://github.com/user-attachments/assets/e8ec5b00-2ffd-487e-bc52-5a2cefbc5ba5" />
<img width="2000" height="1078" alt="image" src="https://github.com/user-attachments/assets/027f9e31-c440-4d5e-9a10-bcfdf60e5741" />
<img width="1704" height="972" alt="image" src="https://github.com/user-attachments/assets/632e3715-460e-4ddc-8bca-7513c1d271ac" />










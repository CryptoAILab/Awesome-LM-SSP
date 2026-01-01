# Awesome-LM-SSP

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/ThuCCSLab/Awesome-LM-SSP)](.)

[<img src="figure/title_new.png" alt="Awesome-LM-SSP" width="1000" height="auto" class="center">](.)

## Introduction 
The resources related to the trustworthiness of large models (LMs) across multiple dimensions (e.g., safety, security, and privacy),                  with a special focus on multi-modal LMs (e.g., vision-language models and diffusion models). 

- This repo is in progress :seedling: (manually collected).
- Badges: 

    - Model:
        - ![LLM](https://img.shields.io/badge/LLM_(Large_Language_Model)-589cf4)
        - ![VLM](https://img.shields.io/badge/VLM_(Vision_Language_Model)-c7688b) 
        - ![SLM](https://img.shields.io/badge/SLM_(Speech_Language_Model)-39c5bb) 
        - ![Diffusion](https://img.shields.io/badge/Diffusion-a99cf4)

    - Comment: ![Benchmark](https://img.shields.io/badge/Benchmark-87b800) ![New_dataset](https://img.shields.io/badge/New_dataset-87b800) ![Agent](https://img.shields.io/badge/Agent-87b800)                 ![CodeGen](https://img.shields.io/badge/CodeGen-87b800) ![Defense](https://img.shields.io/badge/Defense-87b800) ![RAG](https://img.shields.io/badge/RAG-87b800) ![Chinese](https://img.shields.io/badge/Chinese-87b800) ...

   - Venue: ![conference](https://img.shields.io/badge/conference-f1b800) ![blog](https://img.shields.io/badge/blog-f1b800) ![OpenAI](https://img.shields.io/badge/OpenAI-f1b800)  ![Meta AI](https://img.shields.io/badge/Meta_AI-f1b800) ...


- 🔥🔥🔥 Help us update the list! 🔥🔥🔥
  - First, check papers through our database: [Metadata of LM-SSP](https://docs.google.com/spreadsheets/d/1i2IfQJiAdFJueoy7sTv7snn__ZJx11GfiJx8rhDyfc0/edit?usp=sharing).
  - If you want to update the information of a paper (e.g., an arXiv paper has been accepted by a venue), search the paper title in our [metadata table](https://docs.google.com/spreadsheets/d/1i2IfQJiAdFJueoy7sTv7snn__ZJx11GfiJx8rhDyfc0/edit?usp=sharing) and then leave a message in the corresponding cell of the table.
  - If you would like to add some paper, please fill in the following table through `ISSUE`:

| Title | Link  | Code |   Venue |  Classification |  Model | Comment | 
| ---- |---- |---- |---- |---- |----|----| 
| This is a title |  paper.com | github  | bb'23    |  A1. Jailbreak | LLM  | Agent | 

## News
- [2025.01.09] 🎂 Happy 1st Birthday to Awesome-LM-SSP! Keep Going! 💪
- [2024.01.09] 🚀 LM-SSP is released!

## Collections
- [Book](collection/book.md) (3)
- [Competition](collection/competition.md) (5)
- [Leaderboard](collection/leaderboard.md) (5)
- [Toolkit](collection/toolkit.md) (15)
- [Survey](collection/survey.md) (40)
- Paper (2352)
    - A. Safety (1183)
        - [A0. General](collection/paper/safety/general.md) (30)
        - [A1. Jailbreak](collection/paper/safety/jailbreak.md) (530)
        - [A2. Alignment](collection/paper/safety/alignment.md) (145)
        - [A3. Deepfake](collection/paper/safety/deepfake.md) (94)
        - [A4. Ethics](collection/paper/safety/ethics.md) (8)
        - [A5. Fairness](collection/paper/safety/fairness.md) (60)
        - [A6. Hallucination](collection/paper/safety/hallucination.md) (116)
        - [A7. Prompt Injection](collection/paper/safety/prompt_injection.md) (114)
        - [A8. Toxicity](collection/paper/safety/toxicity.md) (86)
    - B. Security (457)
        - [B0. General](collection/paper/security/general.md) (16)
        - [B1. Adversarial Examples](collection/paper/security/adversarial_examples.md) (105)
        - [B2. Agent](collection/paper/security/agent.md) (132)
        - [B3. Poison & Backdoor](collection/paper/security/poison_&_backdoor.md) (178)
        - [B4. Side-Channel](collection/paper/security/side-channel.md) (2)
        - [B5. System](collection/paper/security/system.md) (24)
    - C. Privacy (712)
        - [C0. General](collection/paper/privacy/general.md) (54)
        - [C1. Contamination](collection/paper/privacy/contamination.md) (17)
        - [C2. Data Reconstruction](collection/paper/privacy/data_reconstruction.md) (63)
        - [C3. Membership Inference Attacks](collection/paper/privacy/membership_inference_attacks.md) (65)
        - [C4. Model Extraction](collection/paper/privacy/model_extraction.md) (14)
        - [C5. Privacy-Preserving Computation](collection/paper/privacy/privacy-preserving_computation.md) (131)
        - [C6. Property Inference Attacks](collection/paper/privacy/property_inference_attacks.md) (8)
        - [C7. Side-Channel](collection/paper/privacy/side-channel.md) (10)
        - [C8. Unlearning](collection/paper/privacy/unlearning.md) (70)
        - [C9. Watermark & Copyright](collection/paper/privacy/watermark_&_copyright.md) (280)

## Big love to the community — thank you! 🙏

[![Star History Chart](https://api.star-history.com/svg?repos=CryptoAILab/Awesome-LM-SSP&type=Date)](https://star-history.com/#CryptoAILab/Awesome-LM-SSP&Date)

## Acknowledgement

- Organizers: [Tianshuo Cong (丛天硕)](https://tianshuocong.github.io/), [Xinlei He (何新磊)](https://xinleihe.github.io/), [Zhengyu Zhao (赵正宇)](https://zhengyuzhao.github.io/), [Yugeng Liu (刘禹更)](https://liu.ai/), [Delong Ran (冉德龙)](https://github.com/eggry)

- This project is inspired by [LLM Security](https://llmsecurity.net/), [Awesome LLM Security](https://github.com/corca-ai/awesome-llm-security), [LLM Security & Privacy](https://github.com/chawins/llm-sp),             [UR2-LLMs](https://github.com/jxzhangjhu/Awesome-LLM-Uncertainty-Reliability-Robustness), [PLMpapers](https://github.com/thunlp/PLMpapers), [EvaluationPapers4ChatGPT](https://github.com/THU-KEG/EvaluationPapers4ChatGPT)

<p align="center"><img src="figure/logo.png" width="900" /></p>
<h1 align="center">Munim Thahmid</h1>

<p align="center">
  Trustworthy Software · Formal Methods · LLM Verification
</p>

<p align="center">
  <a href="https://munimthahmid.github.io">Website</a> ·
  <a href="mailto:munimthahmid2@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/munimthahmid/">LinkedIn</a> ·
  <a href="https://munimthahmid.github.io/files/Munim_Thahmid_Resume.pdf">Resume</a>
</p>

I am a research intern at the **University of Illinois Urbana-Champaign** and a recent Computer Science and Engineering graduate from **BUET** with a CGPA of **3.46/4.00**.

My research focuses on making software systems more trustworthy as AI-generated code becomes increasingly common. I want to use formal specifications, theorem provers, and model checkers both to verify AI-generated software and to give LLMs machine-checkable feedback while they reason. My long-term goal is to improve their ability to produce correct specifications, proofs, and safe, verifiable code from the beginning.

## Selected research

- **[TLAPS-Bench](https://specula-org.github.io/tlaps-bench-website/):** We are building a 956-task benchmark across 71 TLA+ specifications for evaluating frontier LLMs on mechanically verified proof completion and generation. My work spans evaluator contracts, canonical replay, anti-cheating checks, TLAPM verification, reproducible runners, and behavioral analysis. On a matched 293-task slice, GPT-5.6 Sol reached 99.0% task pass with iterative verifier feedback versus 18.8% single-turn. [[code](https://github.com/specula-org/tlaps-bench)]

- **[SREGym](https://www.sregym.com/):** We are building a live benchmark with 90 realistic SRE problems and 3,623 fault-target pairs for evaluating agents on real cloud and Kubernetes failures. My work includes reproducible incidents, state-based recovery oracles, independent agent and judge endpoints, and a nine-question LLM-as-a-Judge rubric validated against experts with Cohen's kappa of 0.90. [[code](https://github.com/SREGym/SREGym)]

- **[Script Matters / BanglishBench](https://github.com/munimthahmid/BanglishBench):** I built a controlled multilingual benchmark with 1,174 aligned Bangla, Banglish, and English items, evaluated three local Qwen models and five hosted frontier LLMs, and analyzed script-conditioned behavior under frozen prompts and parsers. I also fine-tuned Qwen2.5-3B with Hugging Face PEFT/LoRA to study robustness mitigation.

- **Bengali speech representations:** My first-author research uses speaker-disjoint probing, cross-model comparison, and controlled robustness analyses to study Whisper encoder representations. The resulting paper, *Layer-wise Probing of Whisper's Encoder Representations for Bengali Phone-like Units*, was accepted to **INTERSPEECH 2026**.

## Experience

- **Research Intern, UIUC** | May 2026 to present
- **Software Developer, AI Systems, Yobo AI** | September 2024 to February 2026

## Technical areas

- **Formal methods and evaluation:** TLA+, TLC, TLAPS/TLAPM, theorem proving, model checking, LLM benchmarks
- **ML and LLMs:** PyTorch, Hugging Face Transformers, PEFT/LoRA, Qwen, Whisper, XLS-R, LiteLLM
- **Programming and systems:** Python, C/C++, Linux, Git, Docker, Kubernetes, FastAPI, Bash, PostgreSQL

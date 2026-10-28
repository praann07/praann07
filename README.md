# Mamidala Som Praneeth Babu

Third-year B.Tech (AI) student at Amrita Vishwa Vidyapeetham, Coimbatore.
I work on understanding and editing what language models know, on image deblurring, and on local-first AI that runs on one laptop GPU.

- **Interpretability:** cross-lingual causal tracing and rank-1 editing in Llama-3.2-3B and Gemma-2-2B ([babel-effect](https://github.com/praann07/babel-effect), paper draft in preparation).
- **Computer vision:** WaveFusion-Net, a dual-branch spatial-wavelet deblurring network (9.48M parameters), IEEE NIGERCON 2026 ([code](https://github.com/praann07/wavefusion-net-nigercon2026)).
- **Shipped product:** Coast, a peer-to-peer ride-matching Android app built with React Native, Expo and Supabase ([coastapp.in](https://coastapp.in/)).

## Open-source contributions

| Project | Change | Status |
|---|---|---|
| [microsoft/PyRIT](https://github.com/microsoft/PyRIT/pull/3154) | Add a request timeout to remote dataset downloads | Merged |
| [NVIDIA/NeMo-Agent-Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2443) | Stop logging the expanded config when `--override` is used, which could expose secrets | Merged |
| [mozilla-ai/otari](https://github.com/mozilla-ai/otari/pull/2648) | `guardrails validate` warns when a `when_changed` glob matches no file | In review |
| [SylphAI-Inc/AdalFlow](https://github.com/SylphAI-Inc/AdalFlow/pull/511) | Make `append_to_jsonl` safe across threads | Open |
| [arc53/DocsGPT](https://github.com/arc53/DocsGPT/pull/3062) | Read markdown, rst and csv files as UTF-8 | Open |

## Selected projects

| Project | What it is | Result |
|---|---|---|
| [babel-effect](https://github.com/praann07/babel-effect) | Do LLMs store facts in language-specific circuits? Pre-registered hypotheses, 1059 claims in a verifiable manifest | English-Spanish causal-profile alignment above the shuffled null (z = 4.0 Llama, 4.8 Gemma) |
| [WaveFusion-Net](https://github.com/praann07/wavefusion-net-nigercon2026) | Spatial-wavelet fusion for blind image deblurring | 9.48M parameters, SHA256 split-leakage checks |
| [Knee OA grading](https://github.com/praann07/knee-oa-kl-grading-resnet-scratch) | ResNet ensemble trained from scratch, with Grad-CAM | 65.7% accuracy, kappa 0.813 |
| [Multi-Scale Attention U-Net](https://github.com/praann07/Multi-Scale-Attention-Enhanced-U-Net-for-Image-Deblurring-with-Composite-Loss-Functions) | Image deblurring with CBAM attention and a Charbonnier + FFT loss | 28.1 dB PSNR, 0.815 SSIM on GoPro |
| [HospiCall-AI](https://github.com/praann07/HospiCall-AI) | Hospital voice receptionist: Whisper, Llama 3.1 and TTS, fully local | Demo flow in the README |
| [liftgain-tracker](https://github.com/praann07/liftgain-tracker) | Workout and nutrition tracking on PostgreSQL: 3NF schema, PR-detection trigger, window-function views | FastAPI backend, React Native app |
| [signum-job-intelligence](https://github.com/praann07/signum-job-intelligence) | Job-market skill tracker on TimescaleDB with a custom Redis bitmap index | Real data sources, no synthetic data |

## Stack

Python, PyTorch, TransformerLens, FastAPI, Ollama, React Native, Expo, TypeScript, PostgreSQL, Supabase.

## Contact

[LinkedIn](https://www.linkedin.com/in/som-praneeth-babu-mamidala-788441216/)

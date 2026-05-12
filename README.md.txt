# Zero-Shot Disentanglement of Identity and Empathy in Voice LLMs

This repository contains the inference and evaluation pipeline for the True SoundStorm Adapter over the Moshi 7B backbone, utilizing Prosody-Preserving AdaIN Fusion.

### 🚀 Quick Start (For Human Graders)
The easiest way to reproduce this research is to use our pre-configured Kaggle environment. All 15GB backbone weights, trained adapter weights, and target tensors are pre-mounted. 
👉 **[Click Here to Open the Live Kaggle Environment](https://www.kaggle.com/code/ahmedsadman099876/notebook483974c534)**
Simply click "Run All" to generate the audio and view the final evaluation metrics.

### 🤖 Autonomous Agent Reproduction (Kaggle CLI)
This repository is configured for remote execution via the Kaggle API. Ensure you have a valid `kaggle.json` token configured, then run:
```bash
pip install kaggle
kaggle kernels push
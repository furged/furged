# Hey, I'm Anushka 

> Machine Learning Engineer exploring the edge between classical ML and deep neural architectures

I build systems that predict when other models fail, approximate PDEs with neural surrogates, and occasionally automate my coffee routine with Python scripts

## What I'm Deep In Right Now

**Neural Surrogate Modeling for PDEs**  
Replacing expensive numerical solvers with CNN-based rollout models and Fourier Neural Operators. The goal? Resolution-invariant mappings that don't accumulate catastrophic errors over time. Currently debugging why my FNO learns the low-frequency modes perfectly but completely ignores high-frequency turbulence

**Meta-Model for Transformer Failures**  
Ever wonder when your transformer is confidently wrong? I built a meta-classifier that predicts DistilBERT failures by analyzing cross-model disagreement patterns. Trained on 67K sentiment samples with <5% failure rate — turns out confidence scores lie, but when VADER and TF-IDF disagree with your transformer, something's probably broken.

Key insight: High confidence ≠ correctness. Disagreement signals are gold for reliability engineering.

## Tech Arsenal

**Core Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**ML/DL Stack**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**Tools & Platforms**  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Areas I Geek Out Over

**Model Reliability & Uncertainty Quantification**  
When your production model says 95% confidence but is completely hallucinating — that's the problem I'm trying to solve. Working with confidence calibration, out-of-distribution detection, and meta-learning approaches to know when not to trust your neural network.

**Physics-Informed ML**  
Why train on millions of samples when you can bake physical laws directly into your loss function? Exploring PINNs, neural operators, and surrogate modeling for scientific computing.

**Imbalanced Learning**  
Real-world data is messy. Fraud detection, anomaly detection, failure prediction — all have <5% positive class. Standard accuracy metrics are useless. I live in the world of ROC-AUC, PR curves, and class weights.

## GitHub Activity

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=furged&theme=tokyonight&hide_border=true)

## Recent Experiments

**Meta-Model for Transformer Failure Prediction** | [Code](https://github.com/furged/meta-model-failure-prediction)  
- TF-IDF baseline: 84.4% accuracy, 0.93 ROC-AUC, 0.946 PR-AUC on 67K samples
- Meta-features: cross-model disagreement, confidence magnitudes, prediction entropy
- Class-weighted logistic regression for severe imbalance (<5% failures)
- **Key finding**: Confidence alone sucks at predicting failures. Disagreement beats everything.

**Neural PDE Surrogate** | Ongoing [Repo](https://github.com/furged/neural-surrogate)  
- CNN multi-step rollout for spatiotemporal dynamics
- Fourier Neural Operator for resolution-invariant learning
- Synthetic data pipeline from numerical solvers
- Evaluation: rollout stability, error accumulation, generalization across resolutions

**Connect Four Engine** | [Code](https://github.com/furged/Connect-four-game)  
- 6×7 NumPy board with 4-directional win detection
- Event-driven Pygame rendering at 60 FPS
- Because sometimes you just need to build a game to remember why you liked programming in the first place

**Pong** | [Code](https://github.com/furged/Pong-game)  
- Real-time physics at 100 FPS
- Collision detection, scoring system
- My first project. Nostalgia code I refuse to delete.

## What I'm Learning

- **Advanced CNN Architectures** — Going beyond vanilla convnets into residual connections, attention mechanisms
- **Fourier Neural Operators** — Operator learning in frequency space for PDEs
- **Uncertainty Quantification** — Bayesian neural networks, ensemble methods, conformal prediction
- **Production ML** — Model serving, monitoring, A/B testing (turns out research code ≠ production code, who knew?)

## 2026 Goals

- [ ] Publish neural surrogate work (targeting ML4PS workshop)
- [ ] Master Fourier Neural Operators and operator learning
- [ ] Learn Rust (because why not add pain to my life)

## Let's Talk About

- Why your high-accuracy model might be terrible
- Class imbalance nightmares
- When to use transformers vs classical ML (hint: not always transformers)
- Physics-informed neural networks
- Coffee automation scripts
- Literally any ML failure story — I collect them

## Reach Me (Please)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](your-linkedin-url)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anushkashakyacs@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/furged)

---

*"In ML, 99% accuracy on imbalanced data just means your model learned to say 'no' really well."*

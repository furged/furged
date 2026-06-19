# 🕷️ Anushka

> *"With great model accuracy comes great responsibility... to check your test set distribution."*

Machine Learning engineer who spends more time debugging data leaks than actually training models. Currently fighting with Fourier Neural Operators and questioning why I thought PDEs would be fun.

---

## What I'm Actually Working On

### 🔬 Neural Surrogate Modeling for PDEs
**Status**: Currently losing sleep over spectral bias

I'm building CNN-based surrogates that approximate expensive numerical solvers. The FNO learns low frequencies beautifully, but high-frequency turbulence? It just... ignores it. Like it's not even there.

**The mess I'm dealing with right now**:
- My rollout model accumulates error like compound interest
- Resolution invariance works in theory, fails in practice
- I've spent 3 days debugging a shape mismatch that was a single transposed dimension

[Repo →](https://github.com/furged/neural-surrogate)

### 🎯 Meta-Model for Transformer Failures
**Status**: Successfully predicting when my model is lying to me

Built a meta-classifier that predicts DistilBERT failures by looking at disagreement patterns between models. Turns out when VADER (sentiment) and TF-IDF disagree with your transformer, your transformer is probably wrong. 

**The actual numbers**:
- 0.93 ROC-AUC on failure prediction
- Tried 15 different feature combinations
- The simplest model (logistic regression) beat everything
- Confidence scores are useless for failure detection

[Repo →](https://github.com/furged/meta-model-failure-prediction)

### 🎮 The "I Missed This" Projects
- **Connect Four**: 6×7 board, 60 FPS rendering, 4-directional detection. Sometimes you just need to build something that works.
- **Pong**: My first project. 100 FPS, collision detection. I keep it for the nostalgia.

---

## The Tech Stack

**I live in**: PyTorch, NumPy, scikit-learn
**I tolerate**: TensorFlow (when I have to)
**I'm learning**: Rust (slowly, painfully)
**My terminal**: Linux, always

---

## Things I Actually Think About

**Model reliability** - When your model says 95% confidence but is hallucinating, *that's* the problem. I work on confidence calibration, OOD detection, and knowing when not to trust your neural network.

**Physics-informed ML** - Baking physical laws into loss functions because I'm too lazy/lazy to generate more training data.

**Imbalanced learning** - Real data is messy. Fraud, anomalies, failures - all <5% positive. I've learned that accuracy is a lie and PR-AUC is your real friend.

---

## 2026

- [ ] Stop my neural surrogate from catastrophically failing after 10 timesteps
- [ ] Actually learn Rust (not just install it and feel good about myself)
- [ ] Write about ML failures (I have so many stories)
- [ ] Build something that isn't ML related

---

## The Part Where I Sound Like a Normal Person

When I'm not wrestling with PyTorch, I'm:
- Reading ML papers and immediately forgetting the math
- Playing chess badly
- Trying to automate my coffee routine (still haven't)
- Actually watching Spiderman

## Talk to Me About

- Your worst model failure (I'll share mine)
- Why your 99% accuracy model is probably terrible
- Neural operators, UQ, or literally any ML paper you're excited about
- Things you've built that have nothing to do with ML

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](your-linkedin)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:anushkashakyacs@gmail.com)

---

*"I don't have imposter syndrome, I have 'my model is overfitting' syndrome."*

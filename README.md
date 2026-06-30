<h1 align="center">Hi, I'm Beshoy Gamal Wahba 👋</h1>

<h3 align="center">AI/ML Engineer in the making — currently open to work 🟢</h3>

<p align="center">
  I build machine learning and deep learning projects from the ground up — not just calling libraries, but understanding what's happening underneath. Currently exploring computer vision, NLP, and multimodal AI systems.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bishoy-gamal/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

### 🚀 What I'm working on

- 🧠 **Deep Learning from scratch** — built a DNN with no TensorFlow/PyTorch shortcuts to truly understand backpropagation and optimization
- 🐱🐶 **Computer Vision** — CNN-based image classifiers (cats vs. dogs and beyond)
- 💳 **Applied ML** — fraud detection models on real-world style datasets
- 🗣️ **Multimodal AI** — contributing to an offline AI avatar system combining Whisper, Aya, XTTS, and Wav2Lip for real-time voice-cloned video generation
- 📊 **Signal Processing** — MATLAB-based audio signal processing tools

---

### 🛠️ Tech Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,matlab,jupyter,javascript,git,github" />
</p>

---

### 📌 Featured Projects

| Project | Description |
|---|---|
| 🧠 [**DNN-Model_From_Scratch**](https://github.com/BeshoGamal4040/DNN-Model_From_Scratch) | A deep neural network built from raw math — no TensorFlow/PyTorch shortcuts — trained on Fashion-MNIST |
| 🐱🐶 [**CNN_Binary_Classifier_CatsVsDogs**](https://github.com/BeshoGamal4040/CNN_Binary_Classifier_CatsVsDogs) | CNN built with TensorFlow/Keras to classify cats vs. dogs |
| 💳 [**Credit_Card_Fraud_Detection_Model**](https://github.com/BeshoGamal4040/Credit_Card_Fraud_Detection_Model) | ML model for detecting fraudulent credit card transactions |
| 🗣️ [**EchoMe_Project**](https://github.com/BeshoGamal4040/EchoMe_Project) | Offline multimodal AI avatar system — Whisper + Aya + XTTS + Wav2Lip |
| 🐍 [**Python-AI-Learning**](https://github.com/BeshoGamal4040/Python-AI-Learning) | Python exercises and assignments completed while learning the language |
| 🎚️ [**matlab-Audio-Signal-Processing-APP**](https://github.com/BeshoGamal4040/matlab-Audio-Signal-Processing-APP) | MATLAB app for audio signal processing |

---

### 📊 GitHub Stats

<p align="center">
  <img src="./github-metrics.svg" alt="GitHub Stats" />
</p>

> Stats above are generated automatically once a day by a GitHub Actions workflow in this repo (see setup steps below) — no third-party server required, so they won't break if an external service goes down.

<details>
<summary>⚙️ One-time setup for the auto-updating stats (click to expand)</summary>

In your `BeshoGamal4040/BeshoGamal4040` repo:

1. Create a **classic** Personal Access Token: go to [github.com/settings/tokens/new](https://github.com/settings/tokens/new), give it the `repo` and `read:user` scopes, no expiration if you don't mind renewing later.
2. In your repo, go to **Settings → Secrets and variables → Actions → New repository secret**, name it `METRICS_TOKEN`, and paste the token as the value. (The action needs a personal token, not the default `GITHUB_TOKEN`, because it has to read data outside this one repo.)
3. Create a file at `.github/workflows/metrics.yml` with:

```yaml
name: Metrics
on:
  schedule:
    - cron: '0 0 * * *'   # runs once a day
  workflow_dispatch:        # lets you trigger it manually too

jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          filename: github-metrics.svg
          token: ${{ secrets.METRICS_TOKEN }}
          base: header, activity, community, repositories, metadata
          plugin_languages: yes
```

Commit that file, then go to the **Actions** tab and click **Run workflow** to trigger it the first time.

That run commits a fresh `github-metrics.svg` straight into your repo — which is the image referenced above. Because the file lives in your own repo instead of being fetched from someone else's server, it can't silently go down the way the Vercel-hosted cards did.

</details>

---

### 🤝 Let's Connect

<p align="center">
  I'm actively looking for opportunities in <b>Machine Learning / AI Engineering</b>.<br/>
  Feel free to reach out on <a href="https://www.linkedin.com/in/bishoy-gamal/">LinkedIn</a> — always happy to talk about AI, projects, or potential roles.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BeshoGamal4040&style=flat-square&color=blue" alt="Profile views"/>
</p>
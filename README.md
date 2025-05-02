# GAN-Stability
<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/emadef1/GAN-Stability/tree/main">
    <img src="Figure/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h1 align="center">GAN-Stability</h1>

  <p align="center">
    Towards Robust Stability Prediction in Smart Grids: GAN-based Approach under Data Constraints and Adversarial Challenges
    <br />
    <a href="https://arxiv.org/abs/2501.16490"><strong>Papaer Available»</strong></a>
    <br />
    <br />
    <a href="https://www.dei.unipd.it/persona/1373bd29c9ef0140e39d53ec9add14d2">Emad Efatinasab</a>
    ·
    <a href="https://www.math.unipd.it/~abrighen/">Alessandro Brighente</a>
    .
    <a href="https://donadelden.github.io/">Denis Donadel</a>
    ·
    <a href="https://www.math.unipd.it/~conti/">Mauro Conti</a>
    .
    <a href="https://www.dei.unipd.it/persona/95DDDDA0C518D43822ADC0338BD38073">Mirco Rampazzo</a>
  </p>
</div>

## 🗣️ Citation

Please, cite this work when referring to GAN-Stability.

```
@misc{efatinasab2025robuststabilitypredictionsmart,
      title={Towards Robust Stability Prediction in Smart Grids: GAN-based Approach under Data Constraints and Adversarial Challenges}, 
      author={Emad Efatinasab and Alessandro Brighente and Denis Donadel and Mauro Conti and Mirco Rampazzo},
      year={2025},
      eprint={2501.16490},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2501.16490}, 
}

```
<div id="abstract"></div>

## 🧩 Abstract

Smart grids are crucial for meeting rising energy demands driven by global population growth and urbanization. By integrating renewable energy sources, they enhance efficiency, reliability, and sustainability. However, ensuring their availability and security requires advanced operational control and safety measures. 
While Artificial Intelligence and Machine Learning can assist in assessing grid stability, challenges such as data scarcity and cybersecurity threats, particularly adversarial attacks, remain.
Data scarcity is a major issue, as obtaining real-world instances of grid instability requires significant expertise, resources, and time. Yet, these instances are critical for testing new research advancements and security mitigations.
This paper introduces a novel framework for detecting instability in smart grids using only stable data. It employs a Generative Adversarial Network (GAN) where the generator is designed not to produce near-realistic data but instead to generate Out-Of-Distribution (OOD) samples with respect to the stable class. These OOD samples represent unstable behavior, anomalies, or disturbances that deviate from the stable data distribution. By training exclusively on stable data and exposing the discriminator to OOD samples, our framework learns a robust decision boundary to distinguish stable conditions from any  unstable behavior, without requiring unstable data during training. Furthermore, we incorporate an adversarial training layer to enhance resilience against attacks.
Evaluated on a real-world dataset, our solution achieves up to 98.1\% accuracy in predicting grid stability and 98.9\% in detecting adversarial attacks. Implemented on a single-board computer, it enables real-time decision-making with an average response time of under 7ms.
<p align="right"><a href="#top">(back to top)</a></p>
<div id="usage"></div>

## ⚙️ Usage

To execute the attacks or to deploy the FaultGuard framework, start by cloning the repository:

```bash
git clone https://github.com/emadef1/GAN-based-Stability-prediction.git
cd GAN-based-Stability-prediction
```
<sup>NOTE: if you're accessing this data from the anonymized repository, the above command might not work..</sup>

Then, install the required Python packages by running:

```bash
pip install -r requirements.txt
```

<p align="right"><a href="#top">(back to top)</a></p>
<div id="models"></div>

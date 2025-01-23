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
    <a href="https://github.com/emadef1/GAN-Stability/tree/main"><strong>Paper in progress »</strong></a>
    <br />
    <br />
    <a href="">Anonymous Authors</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary><strong>Table of Contents</strong></summary>
  <ol>
    <li>
      <a href="#abstract">Abstract</a>
    </li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li>
      <a href="#models">Models</a>
    </li>
    <li>
      <a href="#baseline">Baseline</a>
    </li>
    <li>
      <a href="#attacks">Attacks</a>
    </li>
  </ol>
</details>

<div id="abstract"></div>

## 🧩 Abstract

Smart grids are critical for addressing the growing energy demand due to global population growth and urbanization. They enhance efficiency, reliability, and sustainability by integrating renewable energy. Ensuring their availability and safety requires advanced operational control and safety measures. Researchers employ AI and machine learning to assess grid stability, but challenges like the lack of datasets and cybersecurity threats, including adversarial attacks, persist. In particular, data scarcity is a key issue: obtaining grid instability instances is tough due to the need for significant expertise, resources, and time. However, they are essential to test novel research advancements and security mitigations.
In this paper, we introduce a novel framework to detect instability in smart grids by employing only stable data. It relies on a Generative Adversarial Network (GAN) where the generator is trained to create instability data that are used along with stable data to train the discriminator. Moreover, we include a new adversarial training layer to improve robustness against adversarial attacks. Our solution, tested on a dataset composed of real-world stable and unstable samples, achieve accuracy up to 97.5\% in predicting grid stability and up to 98.9\% in detecting adversarial attacks. Moreover, we implemented our model in a single-board computer demonstrating efficient real-time decision-making with an average response time of less than 7ms. Our solution improves prediction accuracy and resilience while addressing data scarcity in smart grid management.
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

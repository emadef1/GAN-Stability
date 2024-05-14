# GAN-Stability
<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/emadef1/GAN-Stability/tree/main">
    <img src="Figures/logo.png" alt="Logo" width="150" height="150">
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

The rapid growth of the global population and economy, along with increasing urbanization, is expected to drive a surge in energy demand. Integrating renewable energy sources poses challenges, notably in adapting conventional grids to handle bidirectional energy flows and accommodating "prosumers" in energy distribution networks. Smart grids offer a transformative solution, leveraging advanced technologies to improve the efficiency, reliability, and sustainability of electrical grids. This paper examines the role of smart grids in integrating renewables, optimizing energy distribution, and tackling challenges in the evolving energy landscape. It also explores the importance of accurately predicting renewable energy generation for maintaining stable power system operation, emphasizing the role of machine learning and artificial intelligence in developing stability prediction systems for smart grids. Despite significant progress, challenges such as data scarcity and cybersecurity vulnerabilities persist, necessitating innovative solutions to ensure the resilience of smart grid infrastructure. This paper introduces a pioneering framework utilizing a Generative Adversarial Network (GAN) model to predict smart grid stability, addressing the challenge of limited data accessibility. By utilizing only stable instances from available datasets, our approach reflects real-world constraints where instability data may be scarce. Incorporating a novel adversarial training layer, our model achieves up to 0.975 accuracy in stability prediction, even without instability instances in training data. Demonstrating robustness against state-of-the-art whitebox adversarial attacks with up to 0.973 accuracy when classifying these attacks as instance of instability, our framework eliminates the need for an additional Anomaly Detection System (ADS). This represents a significant advancement in stability prediction, ensuring high accuracy and resilience while mitigating data scarcity challenges in smart grid management.
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

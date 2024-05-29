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

Smart grids are essential for meeting the increasing energy demand driven by global population growth, economic expansion, and urbanization. By leveraging advanced technologies, smart grids enhance grid efficiency, reliability, and sustainability. They facilitate seamless integration of renewables and optimize energy distribution, making them central to modernizing the energy sector. Therefore, ensuring the availability of smart grids is crucial, requiring comprehensive control over operations and robust safety measures. Researchers have developed diverse approaches to assess smart grid stability and ensure safe operations, with artificial intelligence and machine learning being prominent methods for precise stability forecasting. Despite notable advancements, persistent challenges include data scarcity, referring to the difficulty in acquiring instances of grid instability. This issue demands significant reliance on human expertise, substantial resources, and extensive time, deliberately inducing instability in a real-world smart grid for data collection. Furthermore, cybersecurity vulnerabilities such as adversarial attacks continue to pose significant challenges.
This paper introduces a pioneering framework utilizing a Generative Adversarial Network (GAN) model to to detect instability in smart grid only leveraging stable data. To achieve this, we utilize the generator component of our GAN to create diverse instances of instability, which are then used alongside stable data to train the discriminator.  Unlike other architectures and models used in literature, our model offers distinct advantages of being able to be trained on just one label (stable) and generating synthetic data that could be interpreted as potential real-world instances of grid instability. By utilizing only stable instances from available datasets, our approach reflects real-world scenario where instability data may be in practice scarce and unlabeled. Incorporating a novel adversarial training layer for enhancing robustness against adversarial attacks, our model achieves up to 0.975 accuracy in stability prediction, even without instability instances in training data. Our framework eliminates the need for an additional Anomaly Detection System (ADS) demonstrating robustness against state-of-the-art adversarial attacks in whitebox and greybox scenarios with up to 0.973 accuracy when classifying these attacks as instance of instability. This represents a significant advancement in stability prediction, ensuring high accuracy and resilience while mitigating data scarcity challenges in smart grid management.
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

<h1 align="center">
  Taking Over the Stock Market: </br>
  Adversarial Perturbations Against Algorithmic Traders
</h1>

<h3 align="center">
  <a href="https://arxiv.org/abs/2010.09246">
    Paper
  </a>
  <span> | </span>
  <a href="https://github.com/nehemya/Algo-Trade-Adversarial-Examples">
    Code
  </a>
  <span> | </span>
  <a href="https://www.kaggle.com/nickdl/snp-500-intraday-data">
    Data
  </a>
</h3>

<p align="center">
  Crafting a targeted universal adversarial perturbation against the alpha model of an algorithmic trading system.
</p>

<p align="center">
  <img width=80% src="https://github.com/nehemya/Algo-Trade-Adversarial-Examples/blob/main/git_logo.jpeg">
</p>

## About the Project
This repository contains the code for the ECML PKDD 2021 manuscript [Taking Over the Stock Market: Adversarial Perturbations Against Algorithmic Traders](https://arxiv.org/abs/2010.09246). Our study presents a realistic scenario in which an attacker influences algorithmic trading systems using adversarial learning techniques to manipulate the input data stream in real-time.
The attacker creates a targeted universal adversarial perturbation (TUAP) that is agnostic to the target model and time of use, which remains imperceptible when added to the input stream.

Our code reads and processes the data from the [S&P 500 Intraday](https://www.kaggle.com/nickdl/snp-500-intraday-data) dataset and divides it into a set for training the alpha models, a set for crafting TUAPs, and six test sets to evaluate the attack. The training set is used to train three alpha models. Then, we use the TUAP set to craft a universal adversarial perturbation that can fool the target alpha models and evaluate the perturbations' performance.  Finally, we also explore various mitigation methods. Additional information is available in the paper. 

## Citation
```
@article{nehemya2020bots,
  title={When Bots Take Over the Stock Market: Evasion Attacks Against Algorithmic Traders},
  author={Nehemya, Elior and Mathov, Yael and Shabtai, Asaf and Elovici, Yuval},
  journal={arXiv preprint arXiv:2010.09246},
  year={2020}
}
```

## Acknowledgments
The logo was created using [Lorenzo's image from Pexels](https://www.pexels.com/photo/turned-on-monitor-displaying-frequency-graph-241544/).


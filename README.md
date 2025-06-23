# USElection-CoIA-TheWebConf25

This repository accompanies our paper presented at **The Web Conference 2025**:

**"Exposing Cross-Platform Coordinated Inauthentic Activity in the Run-Up to the 2024 US Election"**

## 📄 Citation

If you find this work useful, please consider citing our paper:

```bibtex
@inproceedings{10.1145/3696410.3714698,
author = {Cinus, Federico and Minici, Marco and Luceri, Luca and Ferrara, Emilio},
title = {Exposing Cross-Platform Coordinated Inauthentic Activity in the Run-Up to the 2024 U.S. Election},
year = {2025},
isbn = {9798400712746},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3696410.3714698},
doi = {10.1145/3696410.3714698},
abstract = {Coordinated information operations remain a persistent challenge on social media, despite platform efforts to curb them. While previous research has primarily focused on identifying these operations within individual platforms, this study shows that coordination frequently transcends platform boundaries. Leveraging newly collected data of online conversations related to the 2024 U.S. Election across 𝕏 (formerly, Twitter), Facebook, and Telegram, we construct similarity networks to detect coordinated communities exhibiting suspicious sharing behaviors within and across platforms. Proposing an advanced coordination detection model, we reveal evidence of potential foreign interference, with Russian-affiliated media being systematically promoted across Telegram and 𝕏. Our analysis also uncovers substantial intra- and cross-platform coordinated inauthentic activity, driving the spread of highly partisan, low-credibility, and conspiratorial content. These findings highlight the urgent need for regulatory measures that extend beyond individual platforms to effectively address the growing challenge of cross-platform coordinated influence campaigns.},
booktitle = {Proceedings of the ACM on Web Conference 2025},
pages = {541–559},
numpages = {19},
keywords = {coordinated inauthentic behavior, information operations},
location = {Sydney NSW, Australia},
series = {WWW '25}
}
```

## 📊 Notebooks

The Jupyter notebooks in this repository are named after each corresponding **plot** in the paper, making it easy to trace and reproduce the figures.

🔗 [https://github.com/mminici/USElection-CoIA-TheWebConf25/tree/main/notebooks](#)

## 📁 Data

All datasets used in the paper will be made available soon (Google Drive link to follow).

In the meantime, please refer to the following for updated versions of the datasets:

	•	Ashwin Balasubramanian, Vito Zou, Hitesh Narayana, Christina You, Luca Luceri, and Emilio Ferrara A public dataset tracking social media discourse about the 2024 US presidential election on Twitter/X. arXiv preprint arXiv:2411.00376 (2024).

	•	Leonardo Blas, Luca Luceri, and Emilio Ferrara Unearthing a Billion Telegram Posts about the 2024 US Presidential Election: Development of a Public Dataset. arXiv preprint arXiv:2410.23638 (2024).

## 🛠️ Dependencies

To ensure compatibility and reproducibility, we used the following library versions:
```
cuml==24.08.00
matplotlib==3.10.1
nltk==3.9.1
numpy==2.2.4
pandas==2.2.2
polars==1.6.0
pyarrow==19.0.1
rapids==24.08.00
torch==2.6.0
transformers==4.50.0
```


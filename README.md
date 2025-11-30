# GRATEv2: Computational Tools for Real-time Analysis of High-throughput High-resolution TEM (HRTEM) Images of Conjugated Polymers

This is the repository that contains source code for the project website.

## Abstract

Automated analysis of high-resolution transmission electron microscopy (HRTEM) images is increasingly essential for advancing research in organic electronics, where precise characterization of lamellar, one-dimensional crystalline domains in conjugated polymers governs device performance. This paper introduces an open-source computational framework—GRATEv2 (GRaph-based Analysis of TEM, Version 2)—designed for near-real-time analysis of semi-crystalline, polymeric microstructures; its capabilities are illustrated on poly[N-9′-heptadecanyl-2,7-carbazole-alt-5,5-(4′,7′-di-2-thienyl-2′,1′,3′-benzothiadiazole)] (PCDTBT), a benchmark material in organic photovoltaics. GRATEv2 employs fast, automated image processing algorithms, enabling rapid extraction of structural features like d-spacing, orientation, and crystal shape metrics. Bayesian optimization rapidly identifies the parameters (that are traditionally user-defined) in the approach, reducing the need for manual parameter tuning and thus enhancing reproducibility and usability. Additionally, GRATEv2 is compatible with high-performance computing (HPC) environments, allowing for efficient, large-scale data processing at near real-time speeds. A unique feature of GRATEv2 is a Wasserstein distance-based stopping criterion, which optimizes data collection by determining when further sampling no longer adds statistically significant information. This capability optimizes the amount of time the TEM facility is used while ensuring data adequacy for in-depth analysis. Open-source and tested on a substantial PCDTBT dataset, this tool offers a powerful, robust, and accessible solution for high-throughput material characterization in organic electronics.

## Key Features

- **Automated HRTEM image analysis** for conjugated polymers
- **Bayesian optimization** for parameter tuning
- **Real-time structural feature extraction** (d-spacing, orientation, crystal shape)
- **HPC compatibility** for large-scale data processing
- **Wasserstein distance-based stopping criterion** for optimal data collection
- **Open-source framework** for reproducible research

## Links

- [Paper (Materials Advances)](https://pubs.rsc.org/en/content/articlehtml/2025/ma/d5ma00409h)
- [arXiv Preprint](https://arxiv.org/abs/2411.03474)
- [Code Repository](https://github.com/baskargroup/GRATEv2)

## Citation

If you find this work useful for your research, please cite:

```bibtex
@article{gamdha2025gratev2,
  title={GRATEv2: computational tools for real-time analysis of high-throughput high-resolution TEM (HRTEM) images of conjugated polymers},
  author={Gamdha, Dhruv and Fair, Ryan and Krishnamurthy, Adarsh and Gomez, Enrique D and Ganapathysubramanian, Baskar},
  journal={Materials Advances},
  volume={6},
  number={19},
  pages={6820--6842},
  year={2025},
  publisher={Royal Society of Chemistry}
}
```

## Website License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
# CausalRanking
The `CausalRanking` repository contains code for a network diffusion based framework to identify significant causal anomalies and rank them. The method implemented here is described in [this paper](https://dl.acm.org/doi/pdf/10.1145/2939672.2939765).

## Citation

If you find the code in this respository useful for your research, please cite our paper:
```
@inproceedings{cheng2016ranking,
  title={Ranking causal anomalies via temporal and dynamical analysis on vanishing correlations},
  author={Cheng, Wei and Zhang, Kai and Chen, Haifeng and Jiang, Guofei and Chen, Zhengzhang and Wang, Wei},
  booktitle={Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining},
  pages={805--814},
  year={2016}
}
```

## Other information

- The baseline methods are also included, such as LBP and gRank, mRank.

- The code to calculate pair-wise correlations are included in ranking(sytheticdata).

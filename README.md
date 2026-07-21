# eXtreme Deep Factorization Machine

```bash
# INSTALL DEPENDENCIES
conda env create -f env/environment.yaml
conda activate ctr
```

- pkgs:
    - factorization machine based ctr prediction experiment library [`repo`](https://github.com/jayarnim/pkg-ctr)

- dataset:
    - kaggle display advertising dataset [`link`](https://ailab.criteo.com/ressources/)

        | | origin | sampling |
        |---|---:|---:|
        | total | $45,840,617$ | $1,000,000$ |
        | click | $11,745,438$ | $256,223$ |
        | non-click | $34,095,179$ | $743,777$ |
        | ratio | $1:2.9$ | $1:2.9$ |
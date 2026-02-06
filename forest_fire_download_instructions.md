# Forest Fire Project

The dataset for this project is images, so it is too large to store a copy of in this repo.
Instead, you will need to download the data yourself from Kaggle (remember - this is one of the challenging projects!).
Luckily, Kaggle has an easy way to download datasets - a package called kagglehub.
You will need to install kagglehub first by running `pip install kagglehub` in a terminal.

Then run the following code from a Jupyter notebook or Python terminal:

```
import kagglehub

# Download latest version
path = kagglehub.dataset_download("obulisainaren/forest-fire-c4")

print("Path to dataset files:", path)
```

If you want to inspect the data before downloading it, check it out on Kaggle:
https://www.kaggle.com/datasets/obulisainaren/forest-fire-c4 
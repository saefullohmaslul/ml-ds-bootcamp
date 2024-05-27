# Learn NumPy, Pandas, Matplotlib, Sci-kit Learn

## How to use this notebook

So first you can create env based on `environment.yml` file and make prefix as `env`. 

```bash
conda env create -f environment.yml --prefix ./env
```

Then you can activate the environment.
```bash
conda activate ./env
```

Then you can open the notebook.
```bash
jupyter notebook
```

## Installing Other Libraries

You can install other libraries using `pip` or `conda` in the same environment.

```bash
conda install -c conda-forge matplotlib
```

```bash
pip install matplotlib
```

## Re-export the environment

If you install any other libraries, you can re-export the environment using the following command.

```bash
conda env export | grep -v "^prefix: " > environment.yml
```

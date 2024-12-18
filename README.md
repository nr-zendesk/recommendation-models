# recommendation-models
Repository containing different implementation of several recommendation system models.

## Downloading the datasets
To download a dataset, run the following commands on your linux machine ( tested in aws instances):

```
wget https://files.grouplens.org/datasets/movielens/ml-100k.zip
```

```
unzip ml-100k.zip
```

The first command downloads the movielense 100k dataset zip from the hosting platform.  
The second command unzips it into a folder called `ml-100k`.

The structure I am using is storing the `ml-100k` folder inside a folder called `data`, with the `data` folder being placed in the root of the repository.

To get additional larger versions of the `movielense` dataset replace the `mk-100k` byt its variations, *e.g* `ml-20m, ml-1m, ...`
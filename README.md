## Getting Started

### Step 1
Download the Yelp dataset from [here](https://www.kaggle.com/c/yelp-recruiting/data?yelp_training_set.tgz#_=_)

Place the `.tgz` file within this repo's `data` folder

### Step 2
`cd` into the `data` folder and run `tar -xvzf /path/to/yelpfile.tgz`

### Step 3
From the command line, make sure you are still within your `data` folder, run `python convert.py`.

This should covert the `.json` files to `.csv` files, which are easier to deal with for `pandas`

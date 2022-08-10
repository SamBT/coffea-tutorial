# coffea-tutorial
A short tutorial for the coffea HEP data analysis framework

# Setup
You'll need to create a conda environment with coffea installed + some other helpful packages. I've provided a setup YAML file for this, so just run
```
conda env create -f coffea.yml
```
If this doesn't work, try visiting the [coffea website](https://coffeateam.github.io/coffea/installation.html) for installation instructions.

Please download the root files from [here](https://cornell.box.com/s/tbo7mo6oqgvwv840c53nh6chl5tfdxs4) and put them in the `samples` directory.

# Tutorials
All the tutorial content is in the Jupyter notebooks. There are also a bunch of good tutorials on the [coffea website](https://coffeateam.github.io/coffea/examples.html) and a no-install-required set of [tutorial notebooks on binder](https://mybinder.org/v2/gh/CoffeaTeam/coffea/master?filepath=binder/).

Much of the information covered here is analysis-specific and pertains to the coffea framework I've built for the [iDMe analysis](https://github.com/SamBT/iDMe).

To run the tutorials, activate the conda environment and run jupyter:
```
conda activate coffea
jupyter [notebook/lab]
```
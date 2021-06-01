# t-SNE dimensionality reduction and visualization
This repository demonstrates reduction of tensorflow extracted 256-dimensionsal elemental embeddings using t-SNE and PCA.

# Package Requirements
* [scikit-learn](https://scikit-learn.org/stable/install.html)
* numpy
* seaborn
* matplotlib

# Usage
Follow the `tsne.ipynb` demo

# Data
* `sites_from_cifs.csv`: contains atomic site indices, structures IDs, atomic site types from all structures
* `Ba_*_only.csv`: contains site energies, atomic site class (chalcogens, halogens, tetrels, pnictogens), structure IDs of all structures containing Ba atoms
* `embeddings.npy`: numpy array containing tensorflow extracted elemental embeddings
* `train.csv.gz`: contains training set structure IDs

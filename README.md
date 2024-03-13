# Network Anomaly Detection

This project attempts the network anomaly detection task on the ["KDD Cup 1999"](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html) benchmark dataset. The unsupervised learning algorithms K-Means, spectral clustering and DBSCAN were used to attempt this problem, after applying some feature engineering and dimensionality reduction strategies on the data. Manually-implemented metrics (precision, recall, f1-score and conditional entropy) were used to assess the quality of the aforementioned learning algorithms

This project was developed as part of the course Pattern Recognition in the Spring 2023 semester at the Faculty of Engineering, Alexandria University, under the Computer and Communications Engineering department, supervised by Dr. Marwan Torki.

## Steps

1- Download KDD Cup 1999 dataset and understand its format.

2- Implement the K-Means clustering algorithm, and try different values for K.

3- Implement the spectral clustering algorithm, and apply for k = 23.

4- Manually implement the evaluation metrics (precision, recall, f1 score and conditional entropy), and use them to compare between the results for k-means and spectral clustering.

5- Implement the DBSCAN algorithm, and evaluate it using the previously mentioned metrics.

## Prerequisites

This project was developed in the following environment:

- Jupyter Notebook
- Miniconda
- Python 3.11.5

## Installing

1- Clone the repository to your local machine:

```bash
git clone https://github.com/MohEsmail143/network-anomaly-detection.git
```

2- Open Jupyter notebook.

3- Check out the the Jupyter notebook `network-anomaly-detection.ipynb`.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

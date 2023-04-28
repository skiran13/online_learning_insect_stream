# Online Learning on Insect Data Stream

In this project we use 3 data streams with different data drifts. One of the streams have abrubt changes, the other has incremental changes and the last one has gradual changes. Scikit multiflow is used to perform online learning and find out the performance of the model with all the 3 different data streams. The detailed report can be found in the [document](./CSI5155%20Machine%20Learning%20Assignment%204.pdf).

## Requirements

To run this project, you will need:

- Python 3
- PyTorch
- Scikit-learn
- Pandas
- Scikit Multiflow

You can install the required dependencies by running:

```bash
pip install scikit-learn pandas scikit-multiflow
```

## Getting Started

The Project is organized as follow:
```
├── abrubt ht sliding window.txt
├── Abrubt.txt
├── Gradual.txt
├── Gradual1.txt
├── Hoeffding_Tree_Classifier_Abrupt.txt
├── Hoeffding_Tree_Classifier_Gradual.txt
├── Incremental.txt
├── Incremental1.txt
├── INSECTS-abrupt_balanced_norm.txt
├── INSECTS-abrupt_balanced_norm.csv
├── INSECTS-gradual_balanced_norm.txt
├── INSECTS-gradual_balanced_norm.csv
├── INSECTS-incremental_balanced_norm.csv
├── INSECTS-incremental_balanced_norm.txt
├── main.ipynb
├── op.txt
├── README.md
```

The file `main.ipynb` contains all the code for training different models and the output graphs.
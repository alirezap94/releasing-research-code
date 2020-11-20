>📋  README.md file for code accompanying the paper

# My Paper Title

This repository is the official implementation of paper [A Complex Systems Approach To Feature Extraction for Chaotic Behavior Recognition]. 

## Requirements

This code is written in Jupyter NoteBook. To install the requirements in the corresponding environmnet, run this command in Anaconda Powershell Prompt:

```setup
conda install numpy matplotlib jupyter scipy sklearn
```

## Dataset and Feature extraction 

All the data could be generated using the following notebook, 

```train
\Generating Time-Series.ipynb
```
However as it is a time consuming process, final features are provided in 
```
\Lorenz_System_Features.csv
```
>📋  In the code, a propotion of 80 percent of this dataset is utilized as train data and the rest is for test. 

## Classification 

Three different machines of SVM, KNN and Random Forest with tuned hyper-parameters are trained in the following notebook

```
\Classification.ipynb
```


## Results

The best model achieves the following performance as:

| Model name  |  Precision | Recall  |  F1 |
|:-:|:-:|:-:|:-:|
|SVM       | 0.82  | 0.77  | 0.78|
| Random Forest      |  .092 | 0.92  |0.92 |
| KNN    | 0.86  | 0.85  | 0.85|




## Contributing

>📋  Any modification, adaption and th use of this source code must be credited by citing the original paper

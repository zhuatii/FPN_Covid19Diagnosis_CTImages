# Deep Learning based detection of COVID-19 presence using lung CT images

To be able to condense and replicate the ResNet with Feature Pyramid Neteork (FPN) architeture proposed by Rahimzadeh et el. [paper](https://www.sciencedirect.com/science/article/pii/S1746809421001853?via%3Dihub). The paper has an accompanying github repository with code in Keras : [code](https://github.com/mr7495/COVID-CT-Code). The model implemented is in PyTorch with ResNet18 as the feature extraction backbone and with 2 layers in the FPN. The dataset used is a smaller one providxed by the authors in kaggle : [here](https://www.kaggle.com/datasets/mohammadrahimzadeh/covidctset-a-large-covid19-ct-scans-dataset).

Trained model for two data folds are given in the files : [Fold1](FPNFold1) and [Fold2](FPNFold2).

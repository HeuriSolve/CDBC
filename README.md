# CDBC
Configuration/Diagnosis Benchmark in Choco

Knowledge base and datasets as configuration or diagnosis problems:

## 1- Knowledge Bases:
We have implemented Bike2, PC and Camera configuration problems in CSP using choco library in Java. 
Bike2 and PC knowledge bases are generated based on the configuration benchmarks of IT-University of Copenhagen (https://www.itu.dk/research/cla/externals/clib/). 
Camera problem is generated by us based on real digital camera online markets.

## 2- Real Users Datasets:

### 2.1 - CameraKB_DiagnosisDataset:
In order to evaluate the success rate of the prediction quality of a diagnosis algorithm, we applied a user study with 264 students.  Users select values for the 10 different camera parameters (resolution, display size, etc.). Besides, users select 3 most important (weighted) parameters as w1=the first most important parameter, w2=the second most important parameter, w3=the third most important parameter. For these inconsistent user constraints, no product can be found in the product catalog. Then users need to select an available camera from the product catalog in the user study.  We use selected product ID to compare with the result of a diagnosis algorithm to evaluate its prediction quality.

### 2.2 - CameraKB_ConfigurationDataset:
We have converted the user requirements in CameraKB_DiagnosisDataset into consistent requirement sets.  Using this dataset, we can evaluate the prediction accuracy of a configuration system.

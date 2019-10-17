![alt text](Data/header.png)

<center> <h1> An End-to-end Deep Learning Model for CyTOF data <h1> </center>
<center>Zicheng Hu, Ph.D.</center><br/>
<center>Research Scientist</center><br/>
<center>ImmPort Team</center><br/>
<center>The Unversity of California, San Francisco</center><br/><br/>

### Introduction
This GitHub repository contains a tutorial for creating deep learning models tailored to CyTOF data. We will apply the model to diagnose latent cytomegalovirus (CMV) infection. We will also use a decision tree-based method to identify cell subsets that are associated with the CMV infection. 

### Install dependencies
Create conda environment with dependencies for the tutorial: 

```conda create --name CyTOF_DL --file requirements.txt```

### Main tutorial
Navigate into the tutorial folder. Run the main tutorial [DeepLearning_CyTOF.ipynb](https://github.com/hzc363/DeepLearningCyTOF/blob/master/DeepLearning_CyTOF.ipynb):

```jupyter notebook DeepLearning_CyTOF.ipynb```

### CyTOF data processing
Please see the script in [FCS_to_Array folder](https://github.com/hzc363/DeepLearningCyTOF/tree/master/FCS_to_Array) for detailed preprocessing steps of the CyTOF data. 

### More information
For more background information of deep learning and its use in cytometry data, see the [slides](https://github.com/hzc363/DeepLearningCyTOF/blob/master/FOCIS_deeplearning.pdf) of the FOCIS 2019 workshop. 
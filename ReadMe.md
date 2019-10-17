![alt text](Data/header.png)

<center> <h1> An End-to-end Deep Learning Model for CyTOF data <h1> </center>
<center>Zicheng Hu, Ph.D.</center><br/>
<center>Research Scientist</center><br/>
<center>ImmPort Team</center><br/>
<center>The Unversity of California, San Francisco</center><br/><br/>

### Introduction
This GitHub repository contains a tutorial for creating deep learning models tailored to CyTOF data. We will apply the model to diagnose latent cytomegalovirus (CMV) infection. We will also use a decision tree-based method to identify cell subsets that are associated with the CMV infection. 

<hr>

### Install dependencies
Navigate into the tutorial folder. Create conda environment with dependencies for the tutorial. Install time takes around 5 mins.  

```conda create --name CyTOF_DL --file requirements.txt```

<hr>

### Main tutorial
Activate the conda environment.

```conda activate CyTOF_DL```

Run the main tutorial [DeepLearning_CyTOF.ipynb](https://github.com/hzc363/DeepLearningCyTOF/blob/master/DeepLearning_CyTOF.ipynb). It takes around 40 mins to run in a laptop with 2.5 GHz GPU (Intel Core i7) and 16 GB Memory. 

```jupyter notebook DeepLearning_CyTOF.ipynb```

<hr>

### CyTOF data processing
Please see the script in [FCS_to_Array folder](https://github.com/hzc363/DeepLearningCyTOF/tree/master/FCS_to_Array) for detailed preprocessing steps of the CyTOF data. 

<hr>

### More information
For more background information of deep learning and its use in cytometry data, see the [slides](https://github.com/hzc363/DeepLearningCyTOF/blob/master/FOCIS_deeplearning.pdf) of the FOCIS 2019 workshop. 

<hr>

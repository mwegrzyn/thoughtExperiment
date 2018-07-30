# Thought experiment: decoding cognitive processes from the fMRI data of one individual  

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1323666.svg)](https://doi.org/10.5281/zenodo.1323666)  

Martin Wegrzyn, Joana Aust, Larissa Barnstorf, Magdalena Gippert, Mareike Harms, Antonia Hautum, Shanna Heidel, Friederike Herold, Sarah M. Hommel, Anna-Katharina Knigge, Dominik Neu, Diana Peters, Marius Schaefer, Julia Schneider, Ria Vormbrock, Sabrina M. Zimmer, Friedrich G. Woermann & Kirsten Labudda

### Abstract
Cognitive processes, such as the generation of language, can be mapped onto the brain using fMRI. These maps can in turn be used for decoding the respective processes from the brain activation patterns. Given individual variations in brain anatomy and organization, analyzes on the level of the single person are important to improve our understanding of how cognitive processes correspond to patterns of brain activity. They also allow to advance clinical applications of fMRI, because in the clinical setting making diagnoses for single cases is imperative. 
In the present study, we used mental imagery tasks to investigate language production, motor functions, visuo-spatial memory, face processing, and resting-state activity in a single person. Analysis methods were based on similarity metrics, including correlations between training and test data, as well as correlations with maps from the NeuroSynth meta-analysis. The goal was to make accurate predictions regarding the cognitive domain (e.g. language) and the specific content (e.g. animal names) of single 30-second blocks. Four teams used the dataset, each blinded regarding the true labels of the test data. 
Results showed that the similarity metrics allowed to reach the highest degrees of accuracy when predicting the cognitive domain of a block. Overall, 23 of the 25 test blocks could be correctly predicted by three of the four teams. Excluding the unspecific rest condition, up to 10 out of 20 blocks could be successfully decoded regarding their specific content.
The study showed how the information contained in a single fMRI session and in each of its single blocks can allow to draw inferences about the cognitive processes an individual engaged in. Simple methods like correlations between blocks of fMRI data can serve as highly reliable approaches for cognitive decoding. We discuss the implications of our results in the context of clinical fMRI applications, with a focus on how decoding can support functional localization.


### Requirements

Data analysis was performed with Python 2.7 [www.python.org](http://www.python.org) using mainly numpy, scipy, pandas, scikit-learn, nilearn, matplotlib, seaborn and jupyter.

To run all the scipts, you can create a virtual environment, by first installing virtualenv


```shell
pip install virtualenv
```
Then you can create a virtual environment in the folder into which you cloned this repository

```shell
virtualenv venv
```

and then install all modules using pip and the requirements file provided in this repository


```shell
venv/bin/pip install -r requirements.txt
```


### Contact

For questions or comments please write to [martin.wegrzyn@uni-bielefeld.de](mailto:martin.wegrzyn@uni-bielefeld.de)

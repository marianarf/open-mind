# Open Mind
## An effort to show the world how accessible can Neuroscience experiments can be, and their datasets

Researchers across the rapidly developing fields of data science, machine learning, artificial intelligence are increasingly attuned to the wider social responsibilities raised by emerging technologies and their applications. These responsibilities are especially acute for technologies such as BCI and consumer EEG, which now allow data to be collected and organised with unprecedented ease. Open source frameworks for machine learning – which do not require substantial prior expertise – and the increasing availability of easy-to-use SDKs further accelerate these trends, permitting rapid prototyping and at-scale deployment. To optimise the balance between rapid development and social responsibility, publishing data with open and rigorous standards is emerging as a critical practice.

## Contents of this repository

### basal_anxiety_sleep_analysis.ipynb

The core experiment of the talk, were I (Mariana) captured data of a (subjectively) basal anxiogenic state (that is to say: evening, regular-day conditions) and compare it to a high anxiety period followed by sleep. Data is loaded from the data captured using [Mind Monitor program](https://mind-monitor.com/), analyzed both numerically and graphically, then to find interesting patterns that seem to follow the conclusions pointed out by [Pascalis et al. (2019)](https://www.sciencedirect.com/science/article/abs/pii/S0191886919307354).

This experiment was done using a [MUSE 2](https://choosemuse.com/muse-2/) headband, using Mind Monitor to capture information, with a data standard that was documented here following the Google Transit File Specification open data schema ([link in spanish](https://drive.google.com/open?id=1QzpmsojnnR2AkqqFXoCVqMAsCo54R9RhzmUjVa0fEFk)).

### load_experiment_data.ipynb

A small notebook that loads the experiment data, organized by folders.

### example_load_file.ipynb

A small notebook that loads and plots EEG data.

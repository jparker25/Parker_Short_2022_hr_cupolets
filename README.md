# Cupolets in a Chaotic Neuron Model, Parker & Short, 2022.

This repository contains all the necessary information and data to reconstruct figures from [Cupolets in a Chaotic Neuron Model](http://arxiv.org/abs/2204.13066). This paper has been updated and accepted for publication in Chaos. We will update the link to the paper upon publication.

The majority, if not all, code sould be commented and documented. However, for any questions or issues contact the owner of this repository.

### Getting Started
Python 3.9.13 was used in a virtual environment for all analysis and figures in this paper. Please refer to [Creation of Virtual Environments](https://docs.python.org/3/library/venv.html) on how to use a virtual environment.

Once the virtual environment has been created, install the required packages in `requirements.txt`:
```
$ pip install -r requirements.txt
```
### Generating Paper Figures
The repository directory `paper_data` contains the necessary files for generation of several figures from the paper. Particularly, these are figures 5, 6, 7, 8, 9, and 11. The remaining figures require data that are too large to fit in the repository. Please contact John Parker at john.parker@unh.edu for access to this data.

### Running the main code
The script `run.py` can act as a single input for generating cupolets. For options and commands please use 
```
$ python run.py -h
```


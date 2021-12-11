# PSECNN
Detection of polypharmacy side effects by integrating multiple data sources and convolutional neural networks
# Decagon: Representation Learning on Multimodal Graphs

#### Author: [Mahdi Babaei] ( mahdi.babaei@qom.ac.ir)
#### Author: [Amir Lakizadeh] ( lakizadeh@qom.ac.ir)

## Overview

This repository contains code necessary to run the PSECNN algorithm. PSECNN is a method for predicting possible polypharmacy side effects.
  
## Usage: Polypharmacy

We construct a multilabel multiclass classification model of five different drug features and 
polypharmacy side effects, which are represented as drug-drug interactions.

### Running the code

Run the code with flowing command:

    $ python main.py
    

## Requirements

PSECNN is tested to work under Python 2 and Python 3. 

Recent versions of Tensorflow, sklearn, networkx, numpy, and scipy are required. All the required packages can be installed using the following command:

    $ pip install -r requirements.txt

## License

PSECNN is licensed under the University of Qom.

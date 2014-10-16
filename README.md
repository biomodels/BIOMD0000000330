# BIOMD0000000330: Larsen2004_CalciumSpiking

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000330.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000330.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000330 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** On the encoding and decoding of calcium signals in hepatocytes **   
Ann Zahle Larsen, Lars Folke Olsen and Ursula Kummera _Biophysical
Chemistry_Volume 107, Issue 1, 1 January 2004, Pages 83-99
[14871603](http://www.ncbi.nlm.nih.gov/pubmed/14871603),  
**Abstract:**   
Many different agonists use calcium as a second messenger. Despite intensive
research in intracellular calcium signalling it is an unsolved riddle how the
different types of information represented by the different agonists, is
encoded using the universal carrier calcium. It is also still not clear how
the information encoded is decoded again into the intracellular specific
information at the site of enzymes and genes. After the discovery of calcium
oscillations, one likely mechanism is that information is encoded in the
frequency, amplitude and waveform of the oscillations. This hypothesis has
received some experimental support. However, the mechanism of decoding of
oscillatory signals is still not known. Here, we study a mechanistic model of
calcium oscillations, which is able to reproduce both spiking and bursting
calcium oscillations. We use the model to study the decoding of calcium
signals on the basis of co-operativity of calcium binding to various proteins.
We show that this co-operativity offers a simple way to decode different
calcium dynamics into different enzyme activities.

**Note:**

This model corresponds to the 5 variable receptor-operated model, as described
by Larsen et al., 2004. This model is a modified version of the model
described in Kummer 2000
(PMID:[10968983](http://www.ncbi.nlm.nih.gov/pubmed/10968983))



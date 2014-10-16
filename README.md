# BIOMD0000000509: MODEL1401200001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000509.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000509.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000509 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Barrack2014 - Calcium/cell cycle coupling - Rs dependent ATP release

This model is designed based on the hypothesis that cytoplasmic calcium
accelerates entry into S phase of the cell cycle and/or acts to recruit
otherwise quiescents cells onto the cell cycle. The model describes the ATP
mediated calcium-cell cycle coupling via Rs (retinoblastoma tumour suppressor
protein bound to the E2F transcription factor) in a single radial glial cell.

This model is described in the article:

[Modelling the coupling between intracellular calcium release and the cell
cycle during cortical brain
development.](http://identifiers.org/pubmed/24434742)

Barrack DS, Thul R, Owen MR.

J Theor Biol. 2014 Jan 13;347C:17-32.

Abstract:

Most neocortical neurons formed during embryonic brain development arise from
radial glial cells which communicate, in part, via ATP mediated calcium
signals. Although the intercellular signalling mechanisms that regulate radial
glia proliferation are not well understood, it has recently been demonstrated
that ATP dependent intracellular calcium release leads to an increase of
nearly 100% in overall cellular proliferation. It has been hypothesised that
cytoplasmic calcium accelerates entry into S phase of the cell cycle and/or
acts to recruit otherwise quiescent cells onto the cell cycle. In this paper
we study this cell cycle acceleration and recruitment by forming a
differential equation model for ATP mediated calcium-cell cycle coupling via
Cyclin D in a single radial glial cell. Bifurcation analysis and numerical
simulations suggest that the cell cycle period depends only weakly on
cytoplasmic calcium. Therefore, the accelerative impact of calcium on the cell
cycle can only account for a small fraction of the large increase in
proliferation observed experimentally. Crucially however, our bifurcation
analysis reveals that stable fixed point and stable limit cycle solutions can
coexist, and that calcium dependent Cyclin D dynamics extend the oscillatory
region to lower Cyclin D synthesis rates, thus rendering cells more
susceptible to cycling. This supports the hypothesis that cycling glial cells
recruit quiescent cells (in G0 phase) onto the cell cycle, via a calcium
signalling mechanism, and that this may be the primary means by which calcium
augments proliferation rates at the population scale. Numerical simulations of
two coupled cells demonstrate that such a scenario is indeed feasible.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000509](http://identifiers.org/biomodels.db/BIOMD0000000509) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.



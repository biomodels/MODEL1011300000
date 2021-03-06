# MODEL1011300000: Kim2010_VvuMBEL943_V_vulnificus

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1011300000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1011300000.git@20140916`

## Usage

Importing the model package.

`import MODEL1011300000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is a model of the genome scale reconstruction of the Vibrio vulnificus
metabolic network, VvuMBEL943, described in the article:  
**Integrative genome-scale metabolic analysis of Vibrio vulnificus for drug targeting and discovery**   
Hyun Uk Kim, Soo Young Kim, Haeyoung Jeong, Tae Yong Kim, Jae Jong Kim, Hyon E
Choy, Kyu Yang Yi, Joon Haeng Rhee, and Sang Yup Lee. _Molecular Systems
Biology_ 7:460 Jan 2011 doi:
[10.1038/msb.2010.115](http://dx.doi.org/10.1038/msb.2010.115)

Abstract:  
Although the genomes of many microbial pathogens have been studied to help
identify effective drug targets and novel drugs, such efforts have not yet
reached full fruition. In this study, we report a systems biological approach
that efficiently utilizes genomic information for drug targeting and
discovery, and apply this approach to the opportunistic pathogen Vibrio
vulnificus CMCP6. First, we partially re-sequenced and fully re-annotated the
V. vulnificus CMCP6 genome, and accordingly reconstructed its genome-scale
metabolic network, VvuMBEL943. The validated network model was employed to
systematically predict drug targets using the concept of metabolite
essentiality, along with additional filtering criteria. Target genes encoding
enzymes that interact with the five essential metabolites finally selected
were experimentally validated. These five essential metabolites are critical
to the survival of the cell, and hence were used to guide the cost-effective
selection of chemical analogs, which were then screened for antimicrobial
activity in a whole-cell assay. This approach is expected to help fill the
existing gap between genomics and drug discovery.

This metabolic network model has been thoroughly validated by the authors.
VvuMBEL943 is a stoichiometric model that contains the metabolic information
of the microbial pathogen, Vibrio vulnificus CMCP6, at genome-scale. The SBML
version was generated by Hyun Uk Kim using MetaFluxNet.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



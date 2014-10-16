# MODEL9088169066: testid

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL9088169066.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL9088169066.git@20140916`

## Usage

Importing the model package.

`import MODEL9088169066 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes
This model is taken from the <a href = "http://www.ncbi.nlm.nih.gov/entrez/que
ry.fcgi?cmd=retrieve&db=pubmed&list_uids=7559438&dopt=Abstract">Peer-reviewed
publication>Husam M. Abu-Soud et al. Biochemistry 1999, 38, 12446-12451. This
model shows kinetic binding of NMArginine to neuronal nitric oxide synthase.
Model shows the substrate (NM-Arginine) binding to nNOS in a two-step
reversible fashion. First there is rapid binding equilibrium between Im-nNOS
and NM-Arginine to form an intermediate that contains bound imidazole and NM-
arginine. This is followed by a slower conformational change in the Im-enzyme-
substrate complex that is associated with release of bound imidazole and
generation of a modified enzyme-substrate complex which is detected due to
spectral change. Rates approximated based on data in Table 2. The rates for
first reaction are not exact since only Kd known and appropriate graphs do not
exist for matching the profile.

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



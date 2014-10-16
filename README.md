# BIOMD0000000068: Curien2003_MetThr_synthesis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000068.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000068.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000068 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A kinetic model of the branch-point between the methionine and threonine biosynthesis pathways in Arabidopsis thaliana.**   
Curien G, Ravanel S, Dumas R _Eur. J. Biochem._ 2003 Dec; Volume: 270 (Issue:
23 )]:4615-27 [14622248](http://www.ncbi.nlm.nih.gov/pubmed/14622248) ,  
**Abstract:**   
This work proposes a model of the metabolic branch-point between the
methionine and threonine biosynthesis pathways in Arabidopsis thaliana which
involves kinetic competition for phosphohomoserine between the allosteric
enzyme threonine synthase and the two-substrate enzyme cystathionine gamma-
synthase. Threonine synthase is activated by S-adenosylmethionine and
inhibited by AMP. Cystathionine gamma-synthase condenses phosphohomoserine to
cysteine via a ping-pong mechanism. Reactions are irreversible and inhibited
by inorganic phosphate. The modelling procedure included an examination of the
kinetic links, the determination of the operating conditions in chloroplasts
and the establishment of a computer model using the enzyme rate equations. To
test the model, the branch-point was reconstituted with purified enzymes. The
computer model showed a partial agreement with the in vitro results. The model
was subsequently improved and was then found consistent with flux partition in
vitro and in vivo. Under near physiological conditions, S-adenosylmethionine,
but not AMP, modulates the partition of a steady-state flux of
phosphohomoserine. The computer model indicates a high sensitivity of
cystathionine flux to enzyme and S-adenosylmethionine concentrations.
Cystathionine flux is sensitive to modulation of threonine flux whereas the
reverse is not true. The cystathionine gamma-synthase kinetic mechanism
favours a low sensitivity of the fluxes to cysteine. Though sensitivity to
inorganic phosphate is low, its concentration conditions the dynamics of the
system. Threonine synthase and cystathionine gamma-synthase display similar
kinetic efficiencies in the metabolic context considered and are first-order
for the phosphohomoserine substrate. Under these conditions outflows are
coordinated.

  

** [SBML](http://www.sbml.org/) level 2 code generated for the JWS Online project by Jacky Snoep using [PySCeS](http://pysces.sourceforge.net/)   
Run this model online at
[http://jjj.biochem.sun.ac.za](http://jjj.biochem.sun.ac.za/)  
To cite JWS Online please refer to: Olivier, B.G. and Snoep, J.L. (2004) [Web-
based modelling using JWS
Online](http://bioinformatics.oupjournals.org/cgi/content/abstract/20/13/2143)
, Bioinformatics, 20:2143-2144 **

_Biomodels Curation_ The model simulates the flux for TS and CGS under
conditions given in Table 2 and reproduces the dotted lines given in Table 3
of the paper. There is a typo in the equation for the apparent specificity
constant for Phser, Kts (equation13). This was changed after communication
with the authors to be: Kts =
5.9E-4+6.2E-2*pow(AdoMet,2.9)/(pow(32,2.9)+pow(AdoMet,2.9)). The model was
successfully tested on Jarnac and Copasi. Due to a suggestion from Pedro
Mendez the parameter AdoMet, TS and CGS where made constant species.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



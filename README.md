# BIOMD0000000243: Neumann2010_CD95Stimulation_NFkB_Apoptosis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000243.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000243.git@20140916`


# Model Notes


This is the reduced model (model 8) described in: **Dynamics within the CD95
death-inducing signaling complex decide life and death of cells.**  
Leo Neumann, Carina Pforr, Joel Beaudouin, Alexander Golks, Peter H. Krammer,
Inna N. Lavrik and Roland Eils (German Cancer Research Center (DKFZ),
<http://www.dkfz.de> ); _Mol Sys Biol_ 2010; **6** :352. doi:
[10.1038/msb.2010.6](http://dx.doi.org/10.1038/msb.2010.6) ;

**Abstract:**   
This study explores the dilemma in cellular signaling that triggering of CD95
(Fas/APO-1) in some situations results in cell death and in others leads to
the activation of NF-κB. We established an integrated kinetic mathematical
model for CD95-mediated apoptotic and NF-κB signaling. Systematic model
reduction resulted in a surprisingly simple model well approximating
experimentally observed dynamics. The model postulates a new link between
c-FLIP L cleavage in the death-inducing signaling complex (DISC) and the NF-κB
pathway. We validated experimentally that CD95 stimulation resulted in an
interaction of p43-FLIP with the IKK complex followed by its activation.
Furthermore, we showed that the apoptotic and NF-κB pathways diverge already
at the DISC. Model and experimental analysis of DISC formation showed that a
subtle balance of c-FLIP L and procaspase-8 determines life/death decisions in
a nonlinear manner. We present an integrated model describing the complex
dynamics of CD95-mediated apoptosis and NF-κB signaling.

The original was taken from the MSB article supplementary material site [msb20
106-s2.xml](http://www.nature.com/msb/journal/v6/n1/suppinfo/msb20106_S1.html)
. All the species ids were changed since the model was not a valid SBML with
its original ids - Lukas.

Notes added to the species [L] (the initial concentration of Anti-CD95),
regarding changes to be made in the initial concentration of [L], to obtain
figure 5D.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)



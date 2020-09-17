# An Estimation of Text Loss of Old Norse Legendary Sagas
## A case study based on The Atlantis of Middle Dutch Chivalric Epics: An estimation of the text loss using methods from ecodiversity [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3701587.svg)](https://zenodo.org/record/3701587)

This repository contains the data and code for a preliminary study of loss of medieval legendary saga works and witnesses of both extant and loss works. It is based on forthcoming paper on manuscript and text loss of the medieval legendary saga corpus. It utilizes the methods adapted from the Chao ecodiversity model and applied to Middle Dutch romances published in:

> Mike Kestemont and Folgert Karsdorp, "Het Atlantis van de Middelnederlandse ridderepiek. Een schatting van het tekstverlies met methodes uit de ecodiversiteit". *Spiegel der letteren* (2020).

## Data

`FASNL_SurvivingMSS_mdvl`: This spreadsheet contains the data used for the present study. It is in the same format as the original, with first column bearing names of works and the second bearing shelfmarks of manuscripts bearing each work. The corpus of works and the manuscripts in which they survive come from the <a href="http://fasnl.ku.dk/">'Stories for All Time' project website</a>. A copy of the same file is here as `mnl` for testing with the Jupyter Notebook using the script developed by Mike Kestemont. The accompanying `FASNL_SurvivingMSS_mdvl` spreadsheet was an attempt to use the model for a much larger corpus. This does not seem to work and requires further examination.

`mnl.old.xlsx`: This spreadsheet contains the data of the original study. It contains a tabular overview of the surviving texts and text carriers that are conventionally identified as belonging to the text variety ("genre") of Middle Dutch chivalric epics. Each row represents an individual text carrier. The first column lists the titles of the texts; the right column describes the sources in which they survive. Inclusion and identification of individual texts were based on the repertory by Kienhorst:

> H. Kienhorst, De handschriften van de Middelnederlandse ridderepiek. Een codicologische beschrijving. 2 dln. Deventer, 1988.

## Code
`analysis.ipynb`: This stand-alone Python notebook implements and discusses all the code that was used to generate the numbers and figures given in the main paper. The notebook assumes that you are running Python version 3.6 (or higher). All dependencies can be installed via pip, for instance, from the file `requirements.txt` in the repository.

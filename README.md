# Ancient Artifacts
> Identifying lithic microdebitage in soil samples

Analyzing lithic microdebitage (<4mm debris produced in the creation of stone tools) can reveal ancient stone manufacturing sites to provide insight into past cultural activity.  In this work, we build models to identify microdebitage particles from soil samples collected from a Mayan village.  These models are then used to characterize the soil composition to reveal ancient stoneknapping sites in Nacimiento, Guatemala.

# Quick navigation
[Background](#background)  
[Scope](#scope)  
[Data](#data)  
[Models](#models)  
[Timeline](#timeline)  
[Logistics](#project-logistics)  
[Resources](#resources)  
[Contact Info](#contact-info)  

# Background  

The analysis of lithic microdebitage can illuminate ancient stone tool manufacturing practices to provide insight into past cultural activity.  In his dissertation, Dr. Markus Eberl studied the small Mayan site of Nacimiento in the Petexbatun region of Guatemala to investigate how a substantial change in regional political power affected the inhabitants and the local community.  One aspect of investigating the cultural dynamics in the region during the 7th and 8th centuries is to understand the the public structures and daily community interactions.

The purpose of this project is to identify the location of ancient stone tool manufacturing areas within this village.  The locations of these manufacturing areas may be uncovered by analyzing the soil composition.  Although ancient stoneknappers (people who made stone tools) often cleared large and sharp debris from their area of work, lithic microdebitage - that is, particles < 4mm or 1/6th of an inch - would be very difficult to remove from their workspace.  Thus, evidence of lithic microdebitage in the soil can inform the location of these ancient stoneknapping sites and the methods used to create the stone tools.  Soil samples from 50 locations within the village were collected for analysis.

Samples of microdebitage obtained from current stoneknappers provides a set of examplars to compare with the particles of the soil samples.  In order to characterize these samples, a particle analyzer can be used, which provides 40 measurements about each particle contained within the sample.  From this, the profiles of the soil samples can be computed to identify likely stoneknapping sites.

[Johnson and Eberl, et.al.](https://www.tandfonline.com/doi/full/10.1080/01977261.2020.1860351) provides the current work towards these efforts in using dynamic image analysis to discern microdebitage in soil samples.  More about the motivating work studying Nacimiento can be found [here](nsf.gov/awardsearch/showAward?AWD_ID=0514563).

# Scope

The motivating goal of this work is to identify the location(s) of ancient stone tool manufacturing sites given 50 soil samples from the Maya site of Nacimiento and 30-50 stoneknapping microdebitage exemplar samples.  To achieve this result, this project will focus on generating a model or algorithm to characterize the composition of soil samples by identifying particles which are likely microdebitage.  The model may then be used to calculate the percentage composition of the entire soil sample which is microdebitage, enabling the ability to identify which households likely hosted stoneknapping work.  A secondary objective is to establish a workflow for the management of data, although this will proceed in parallel with the modeling and characterization efforts.

# Data

Data management is expected to be an challenge and a workflow should be established to enable expeditious usage of the data.  Currently, there are 50 soil samples from the Mayan village of interest.  The goal is to identify the composition of these soil samples, and the contained particles will be characterized by the PartAn 3D particle analyzer.  The particle analyzer measures 40 variables for every particle, and there are approximately ~500,000 particles in every sample.  The training data contains 30-50 collected and labelled microdebitage samples collected from modern stoneknappers, and represents the stages of specific work.

## Data security

No issues

## Counts

This is currently **TBD** for this project, and will reflect the expected distribution of microdebitage within soil.

# Models

The generated model will produce probabilities of particles being lithic microdebitage given their descriptors from the particle analyzer.

# Timeline

The particle analyzer is expected to arrive and the workstation setup by the end of February.  Based on the ability to obtain particle descriptors from the analyzer around this time, the targeted end date for the project is the end of the semester before May 10th.  Some days of flexibility may be necessary to accomodate particularly rigorous student exam schedules.

The deliverables of the project are models, code repository, and sample predictions.  The expectation is that the model will be ready for comparative validation on new samples.

# Project logistics

**Sprint planning**: Mondays from 1-2pm  at [Zoom link here.](https://vanderbilt.zoom.us/j/98991315219?pwd=YkhaaVdmcWFoblFEN3JLeTlaR1d2UT09&from=addon)  
**Coder's meeting**: TBD  at [Zoom link here](https://vanderbilt.zoom.us/j/98991315219?pwd=YkhaaVdmcWFoblFEN3JLeTlaR1d2UT09&from=addon)  
**Demos**: Fridays at 2-3pm at [Zoom link here](https://vanderbilt.zoom.us/j/93451251344?pwd=UzVMbEdpYS83K2o1bk9QSEd4NldzQT09&from=addon)  
**Data location**:  TBD  
**Slack channel**:  `ancient-artifacts` on Data Science TIP Slack Workspace 

# Resources

* **R Basics**: [RStudio Primers](https://rstudio.cloud/learn/primers/)
* **Data Science with R and Tidyverse**: [R for Data Science, Hadley Wickham](https://r4ds.had.co.nz/)
* **Git tutorials**: [Simple Guide](https://rogerdudler.github.io/git-guide/), [Learn Git Branching](https://learngitbranching.js.org/?locale=en_US)

# Contact info

Markus Eberl, Ph.D.  Associate Professor of Anthropology  
markus.eberl@vanderbilt.edu

Jesse Spencer-Smith, Ph.D.  Chief Data Scientist, DSI  
jesse.spencer-smith@vanderbilt.edu

Charreau Bell, Ph.D.  Senior Data Scientist, DSI  
charreau.s.bell@vanderbilt.edu

Umang Chaudhry  Data Scientist, Vanderbilt DSI  
umang.chaudhry@vanderbilt.edu

Phyllis Johnson, M.A. Graduate student  
phyllis.s.johnson@vanderbilt.edu   

Amy Rieth, Undergraduate student  
amy.e.rieth@Vanderbilt.Edu

Mark Raj, Undergraduate student  
mark.j.raj@vanderbilt.edu

Amanda Sarubbi, Undergraduate student  
amanda.sarubbi@vanderbilt.edu

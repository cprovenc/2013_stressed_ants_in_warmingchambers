# 2013_stressed_ants_in_warmingchambers

###Author: Curtis A. Provencher and Andrew D. Nguyen   

**Date initiated:**   2016-03-29    
**Last Date modified:**  2016-04-20

Funding source:   National Science Foundation, Division of Environmental Biology (1136644)       

# Table of contents
1. [Project Overview](#id-section1)
2. [Objectives and Hypotheses](#id-section2)
3. [Repository Layout](#id-section3)
4. [Materials and Methods](#id-section4)

<div id='id-section1'/>
##Project Overview
This is an National Science Foundation supported project aiming to understand how climate change will impact critical species that perform key ecosystem services. 

<div id='id-section2'/>
##Objecives and Hypotheses
In this study, we assess the potential impacts of experimental warming in wild populations of the ant genus <i>Aphaenogaster</i> from a southern (Duke Forest, NC) and northern (Harvard Forest, MA) site near their range boundaries. Using Hsps as a proxy for sub lethal stress, we will determine the extent simulated warming between a northern and southern site imposes costs on foraging ant workers.
<div id='id-section3'/>
##Repository Layout
  1. **2013_stress_in_nature_manuscript/** : folder for manuscript documents   
  2. **Data/** : All of the raw data generated and includes manipulated or manually parsed data.    
    * **qPCR_Plate_Layouts/** : organization of how samples were ran on each plate   
    * **qPCR_Raw_data_sheets/** : excel spreadsheets of the raw data generated from qpcr machine (SteponePlus)   
    * **Sequencing/** : sequenced amplicons from qpcr reactions   
    * cdna_synthesis_template.xlsx : excel spreadsheet for caculating cDNA synthesis reactions (RNA-cDNA)
    * 20160211_prelim_normfinder.txt and normfinder_prelim.csv : preliminary normfinder data lay out (we opted for a different approch to find the most stable gene )    
    * 2015_warming_prelim.csv : preliminary dataset   
    * RNA_cDNA_Maps.xlsx : plate layout of how RNA was converted to cDNA   
    * 20160222_anbe_sequencing_pog_aph_83_70_40.xls : sequencing layout for hsc70-4 h2, hsp83, and hsp40   
  3. **Results/** : Has preliminary results so far; pdf output of scripts
    * **Figures/** : saved figures by date 
    * 20150824_stressed_ants.pdf : analysis pdf from the Script_Analyses folder (most digestable view of data, metadata, and analyses)    
  4. **Scripts_Analyses/** : I use [R](https://www.r-project.org/) and [Rstudio](https://www.rstudio.com/) for data analysis and data visualization and convert ([knit](http://yihui.name/knitr/)) these analyses into pdfs(see results). 


<div id='id-section4'/>
##Materials and methods

Please [click here](https://github.com/adnguyen/Dissertation_temperature_adaptation_ants/blob/master/ANBE_protocols.md) for lab protocols and reagents. 

# Seedling_Disease
All files related to the seedling experiment testing the protective effects of Syncom vs pathogen in tomato seedlings and any potential timing effects of arrival done in the Koskella Lab.

## Where the Project Stands

By the end of the project, there were no significant statistics I could confirm using my data and no clear trends. When generating the figures, the trends across datasets seemed to change and be variable when looking at a single treatment. 

If anyone moves forward with this work, I fully recommend tinkering with the experimental design and getting comfortable with seedling techniques. In my mind, something about inoculating the bacteria across 3 different days is not allowing them to "establish" on the cotyledon leaves properly. There's no proof or evidence behind that feeling though so I'd be happy to find that it was something else. Additionally, the seedling methods were easy to pick up but there was a lot of variability. The seeds/seedlings are very fragile and it felt like 50/50 whether or not they sprouted successfully.

For Koskella Lab members, message me on slack or find my email  there to chat more. For anyone else, please contact the lab PI, Britt Koskella to chat more. 

## File Descriptions & Uses

### Seedling_Data_Processing.Rmd

Master R markdown file was used when drafting my code, running stat tests, generating figures, and more. With no prior experience in coding (any language) I learned what I needed this year from my mxntor, lab mates, and the internet. Any respectful tips, suggestions, edits, etc. are more than welcome. 

(24.08.13 Would like to redo this code to shorten it and make it more efficient at some point)

### Seedling_Disease_Scores.xlsx

Master excel sheet that contains all raw disease scores and CFU counts per g or mL. Sheets are labeled according to the seedling set they belong to. Notes or differences in each set are listed below.

- **Set 1:** First run through, protocol tester. Moved Rescue disease scores two days ahead to have _Psudomonas syringae pv. tomato DC3000_ (DC) match _in silica_. Initial inoculation of Full Synthetic Community (FSC) & DC <<0.002 OD<sub>600</sub> to due human error.
- **Set 2:** Second run, improve potential stats. Initial inoculation of FSC & DC <<0.002 OD<sub>600</sub> to due human error.
- **Set 3:** Third run, improve potential stats. Initial inoculation of FSC & DC <<0.002 OD<sub>600</sub> to due human error. First set where I homogenized and plated seedlings on rifampicin KBHA plates to quantify ending DC.
- **Set 4:** Fourth run, corrected initial seedling inoculation to 0.002 OD<sub>600</sub>. Additionally tested an initial FSC inoculation of 0.002 & 0.02 OD<sub>600</sub> to see if any differences in the amount of disease protection. Homogenized and plated seedlings.
- **Set 5:** Final run. Additionally tested _Psudomonas syringae pv. tomato PT23_ (PT) to see if any differences in the amount of disease protection between DC & PT. Only homogenized and plated DC seedlings on rifampicin plates because cloranfenicol did not come in time for PT seedlings.

### _data.csv & _CFU.csv Files

Raw csv files from the excel sheet made to import data to Rstudio. 

### LEI_Meeting_Poster.pdf

Poster I made for a fellowship I was involved with for the seedling project (My first real poster lmao). Made right after the third set of seedlings were homogenized.

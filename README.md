# LLM_NP_Synthesis_data




## Pre-trained LLM for nanomaterials data extraction
This repository consist all the data necessary for traiing LLM to be used for generating NP synthesis methods. 

Aim of the project is to train the model for extracting information about nanomaterials synthesis and characterization from published papers. 

What to do:
1. Select papers for extraction to <a href=" https://docs.google.com/spreadsheets/d/1ovGaANnqE0F8TRF7cGP3Q3uQ2mowjwkl7Li6WYviFIc/edit?usp=sharing">data table</a>
The dataset is supposed to be balanced by type field
2. create a folder with ID and create input and output JSONs
3. For input copy blocks of synthesis and characterization
4. Form output based on <a href="1/output.json">example json</a> file using rules:
   - precursors, additives, and seeds could be of different lengths depending on paper conditions
   - concentration(mM) or mass(g) of precursors, additives, and seeds going from method
   - if there's no value in the paper left field empty
   - concentrations need to be in mM
   - sizes in nm
   - volume in ml
   - mass in g
5. fill in fields in the table.
6. push new files to this git repo


Well done!

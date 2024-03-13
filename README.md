validation of model eos3b5e
This model gives the classification of hERG blockers and nonblockers

TASK 1
going through the models provided, i chose eos3b5e
I created this repository for all files
I fecth and downloaded the model following the procedure in the ersilia gitbook
I ran predictions on a sample smiles strings to ensure it works properly
I downloaded a data set from CHEMBL, on chembl, I search compounds, then selected small molecules, preclinical
i downloaded as a csv file and uploaded to google colab
i created a notebook in R which contains my code and analysis and can be found in "ersilia" of this repo
I downloaded the input.csv file, ran predictions on it and saved results in output.csv

Repository Ogranization
'/notebooks' contains all colab notebooks used
'/data' contains all the datasets
'/data/input' contains all inputs
'/data/output' contains all outputs generated
'/figues' contains all figues generated
'/requirements.txt' contains all requirements

Identifiers
EOS model ID: eos30gr
Slug: deepherg

Characteristics
Input: Compound
Input Shape: Single
Task: Classification
Output: Probability
Output Type: Float
Output Shape: Single
Interpretation: Probability of hERG blockade. The training dataset used a threshold of 80% inhibition to define hERG blockers.

References
Publication
Source Code
Ersilia contributor: azycn
Ersilia model URLs
GitHub
AWS S3
DockerHub (AMD64, ARM64)
Citation
If you use this model, please cite the original authors of the model and the Ersilia Model Hub.

License
This package is licensed under a GPL-3.0 license. The model contained within this package is licensed under a None license.

Notice: Ersilia grants access to these models 'as is' provided by the original authors, please refer to the original code repository and/or publication if you use the model in your research.

About Us
The Ersilia Open Source Initiative is a Non Profit Organization (1192266) with the mission is to equip labs, universities and clinics in LMIC with AI/ML tools for infectious disease research.

Help us achieve our mission!

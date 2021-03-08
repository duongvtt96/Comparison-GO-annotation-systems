Protein function prediction which is a crucial part of genome annotation has been witnessed a drastic
development, due to recent high-throughput sequencing technologies. Among available databases storing
protein function terms, Gene Ontology (GO) is the most outstanding and ubiquitous resource utilized
to describe functional properties. Meanwhile, deep learning, a fast-evolving discipline in data-driven
approach, is performing its impressive potential in classifying GO terms for amino acid sequences.
Therefore, we would like to present a review of computational GO annotation methods for protein, from
conventional to deep learning approach. Among reviewed tools, we select some suitable predictors and
conduct a mini comparison to compare their performance in a worldwide challenge based manner. Finally,
we discuss remaining major challenges and emphasize future directions for protein function prediction
with GO.


Description
This repository provides relevant information about the comparison made between selected GO classifiers.


Dataset used in this comparison: final benchmark CAFA3, can be found in the link below:
https://figshare.com/articles/dataset/Supplementary_data/8135393/3

GO annotation systems used in this comparison:
PFP: 
https://kiharalab.org/web/pfp.php
PANNZER2:
http://ekhidna2.biocenter.helsinki.fi/sanspanz/
DeepGOPlus package (kindly follow the requirements to run the package properly):
https://github.com/bio-ontology-research-group/deepgoplus

Evaluation tool provided by CAFA3:
https://github.com/ashleyzhou972/CAFA_assessment_tool/tree/v1.0-beta


Folders in this repo:
1. raw_prediction: contains raw output after running GO classifiers
2. processed_prediction: transform data to the same format for the evaluation step
3. evaluation_results: contains scores after running evaluation tool
4. go.OBO: GO database used for evaluation in the version of 08 December 2020.

Note: 
CAFA3 assessment tool produces scores of F_max, precision, recall in LK, NK type. We add scores of AUPR calculated from precision, recall and All (NK+LK) type.






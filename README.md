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





Dataset used in this comparison (final benchmark CAFA3) can be found in the link below:
https://figshare.com/articles/dataset/Supplementary_data/8135393/3

GO annotation systems used in this comparison:
1. INGA  
https://inga.bio.unipd.it/
2. DeepGOPlus   
https://github.com/bio-ontology-research-group/deepgoplus

Evaluation tool provided by CAFA3:
https://github.com/ashleyzhou972/CAFA_assessment_tool/tree/v1.0-beta


Folders/File in this repository:  
1. raw_prediction: contains raw output after running GO classifiers  
2. processed_prediction: raw output transformed to the same format for the evaluation step  
3. evaluation_result: contains scores after running evaluation tool

Note: 
1. In the evaluation results, we added scores of AUPR; Precision, Recall at threshold of F_max, and also computed for All (NK+LK) protein type.
2. Raw predictions of INGA is provided at: https://inga.bio.unipd.it/documentation/cafa
3. Raw predictions of DeepGOPlus received the same scores compared to the performance presented in their paper (when running evaluate_deepgoplus.py file).
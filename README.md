# What is TaxoRef?
Taxoref is a methodology for Taxonomy Refinement via word embeddings. In order to select the best embedding for the refinement task, several vector models are generted and evaluated on the basis of their ability to represent taxonomic similarity relations.
TaxoRef has been implemented in the following article:
"TaxoRef: Embeddings Evaluation for AI-drivenTaxonomy Refinement" - ECML 2021

Plese cite TaxoRef as:
Malandri, L., Mercorio, F., Mezzanzanica, M., & Nobani, N. TaxoRef: Embeddings Evaluation for AI-driven Taxonomy Refinement. Joint European Conference on Machine Learning and Knowledge Discovery in Databases (2021).

```
@inproceedings{malandri2021taxoref,
  title={TaxoRef: Embeddings Evaluation for AI-drivenTaxonomy Refinement},
  author={Malandri, Lorenzo and Mercorio, Fabio and Mezzanzanica, Mario and Nobani, Navid},
  booktitle={Joint European Conference on Machine Learning and Knowledge Discovery in Databases},
  year={2021},
  organization={Springer}
}
```

# TaxoRef for Labour Market

TaxoRef is a general tool that can be apllied to any taxonomy. The only pre-requisite is having a text corpus to train word embeddings.
In our case, it has been used in the Labour Market domain to propose a refinement of the European Skills, Competences, Qualifications and Occupations (ESCO) taxonomy, training the embeddings on a corpus of 2.2M+ Online Job Vacancies (OJVs) related to the ICT market and collected in UK in 2018.

# The TaxoRef framework

![image](https://user-images.githubusercontent.com/86835945/131684169-a9a69fd2-588c-4d65-83df-3bdbe8d181b0.png)

# Quick start

The notebook TaxoRef.ipynb contains the code, complete and commented.

The embedding generation and selection phase, thorougly described in the article, is not included, because it can be built with any pair corpus-taxonomy following the description in the paper.

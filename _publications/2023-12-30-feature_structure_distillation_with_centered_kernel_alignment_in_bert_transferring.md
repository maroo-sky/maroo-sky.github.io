---
title: "Feature structure distillation with Centered Kernel Alignment in BERT transferring"
collection: publications
category: manuscripts
permalink: /publication/2023-12-30-feature_structure_distillation_with_centered_kernel_alignment_in_bert_transferring
excerpt: How to transfer the feature structure from teacher to student model?
date: 2023-12-30
venue: 'Expert Systems with Applications'
citation: '@article{JUNG2023120980,
title = {Feature structure distillation with Centered Kernel Alignment in BERT transferring},
journal = {Expert Systems with Applications},
volume = {234},
pages = {120980},
year = {2023},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2023.120980},
url = {https://www.sciencedirect.com/science/article/pii/S0957417423014823},
author = {Hee-Jun Jung and Doyeon Kim and Seung-Hoon Na and Kangil Kim},
keywords = {Knowledge distillation, BERT, Centered Kernel Alignment, Natural language processing},
abstract = {Knowledge distillation is an approach to transfer information on representations from a teacher to a student by reducing their difference. A challenge of this approach is to reduce the flexibility of the student’s representations inducing inaccurate learning of the teacher’s knowledge. To resolve the problems, we propose a novel method feature structure distillation that elaborates information on structures of features into three types for transferring, and implements them based on Centered Kernel Analysis. In particular, the global local-inter structure is proposed to transfer the structure beyond the mini-batch. In detail, the method first divides the feature information into three structures: intra-feature, local inter-feature, and global inter-feature structures to subdivide the structure and transfer the diversity of the structure. Then, we adopt CKA which shows a more accurate similarity metric compared to other metrics between two different models or representations on different spaces. In particular, a memory-augmented transfer method with clustering is implemented for the global structures. The methods are empirically analyzed on the nine tasks for language understanding of the GLUE dataset with Bidirectional Encoder Representations from Transformers (BERT), which is a representative neural language model. In the results, the proposed methods effectively transfer the three types of structures and improves performance compared to state-of-the-art distillation methods: (i.e.) ours achieve 66.61% accuracy compared to the baseline (65.55%) in the RTE dataset. Indeed, the code for the methods is available at https://github.com/maroo-sky/FSD.}
}'
slidesurl: 'https://github.com/maroo-sky/FSD'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0957417423014823'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.

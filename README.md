# xnli_extension

## Abstract
Multilingual transfer learning can benefit both high- and low-resource languages, but the source of these improvements is not well understood.
Canonical Correlation Analysis (CCA) of the internal representations of a pretrained, multilingual BERT model reveals that the model partitions representations for each language rather than using a common, shared, interlingual space.
This effect is magnified at deeper layers, suggesting that the model does not progressively abstract semantic content while disregarding languages.
Hierarchical clustering based on the CCA similarity scores between languages reveals a tree structure that mirrors the phylogenetic trees hand-designed by linguists.
The subword tokenization employed by BERT provides a stronger bias towards such structure than character- and word-level tokenizations.
We release a subset of the MultiNLI/XNLI dataset translated into an additional 14 languages in this repository to assist further research into multilingual representations.

## Citation
```
@article{singhMultiLingTokBias2019,
title={{BERT is Not an Interlingua and the Bias of Tokenization}},
author={Singh, Jasdeep and McCann, Bryan and Xiong, Caiming and Socher, Richard},
journal={The Workshop on Deep Learning for Low-Resource NLP at EMNLP 2019},
year={2019}
}
```

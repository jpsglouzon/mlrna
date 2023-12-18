# Machine Learning and RNA
Lists of models and tools based on Machine Learning to solve problems related to RNA structure prediction, representation, classification, and many more

**Table of contents**
1. [RNA secondary structures prediction](https://github.com/jpsglouzon/mlrna/edit/main/README.md#rna-secondary-structures-prediction)
2. [RNA representation](https://github.com/jpsglouzon/mlrna/edit/main/README.md#rna-representation)
3. [RNA classification Example](https://github.com/jpsglouzon/mlrna/edit/main/README.md#rna-representation)
4. [RNA clustering](https://github.com/jpsglouzon/mlrna/edit/main/README.md#deep-learning-approaches)
5. [RNA therapeutics and diagnostics](https://github.com/jpsglouzon/mlrna/edit/main/README.md#rna-representation)
6. [Tools and webservers](https://github.com/jpsglouzon/mlrna#tools)

## RNA secondary structures prediction

### Deep Learning approaches
- [Sequence similarity governs generalizability of de novo deep learning models for RNA secondary structure prediction](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011047): "...Model generalizability, i.e., the performance gap between the seen and unseen sets, degrades rapidly as the sequence similarity decreases....  Generalizability thus poses a major hurdle for deploying de novo DL models in practice and various pathways for future advances are discussed."
- [Automatic recognition of complementary strands: Lessons regarding machine learning abilities in RNA folding](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011047): "...We observed that low-capacity models are better suited for learning with mislabelled training examples, while large capacities improve the ability to generalize to structurally dissimilar data. Given a more complex task like RNA folding, it comes as no surprise that the scarcity of usable examples hurdles the applicability of machine learning techniques to this field."
- [Machine learning for RNA 2D structure prediction benchmarked on experimental data](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbad153/7140288):"...We show that DL-based algorithms (such as SPOT-RNA and UFold) can outperform SL and traditional methods if the data distribution is similar in the training and testing set. However, when predicting 2D structures for new RNA families, the advantage of DL is no longer clear, and its performance is inferior or equal to that of SL and non-ML methods."

## RNA representation
- [Informative RNA base embedding for RNA structural alignment and clustering by deep representation learning](https://academic.oup.com/nargab/article/4/1/lqac012/6534363): '...we adopt a pre-training algorithm for the effective embedding of RNA bases to acquire semantically rich representations...' (Application to clustering tasks)
- [An efficient graph kernel method for non-coding RNA functional prediction](https://academic.oup.com/bioinformatics/article/33/17/2642/3798629): '...We employ a flexible graph encoding to preserve multiple structural hypotheses and exploit recent advances in representation and model induction to scale to large data volumes...'
- [The super-n-motifs model: a novel alignment-free approach for representing and comparing RNA secondary structures](https://academic.oup.com/bioinformatics/article/33/8/1169/2907822): '...we propose the super-n-motifs model based on a latent analysis of enhanced motifs comprising not only basic motifs but also adjacency relations. The super-n-motifs model computes a vector representation of secondary structures as linear combinations of these motifs. ...'

## RNA classification
- [Comparison and benchmark of deep learning methods for non-coding RNA classification](https://www.biorxiv.org/content/10.1101/2023.11.24.568536v2.abstract): '...We propose a comparison of the different approaches and of non-coding RNA datasets proposed in the state-of-the-art. Then, we perform experiments to fairly evaluate the performance of various tools for non-coding RNA classification on two popular datasets. With regard to these results, we assess the relevance of the different architectural choices and provide recommendations to consider in future methods. ...'

## RNA clustering


## RNA therapeutics and diagnostics
### Therapeutics
- [Tailor made: the art of therapeutic mRNA design](https://www.nature.com/articles/s41573-023-00827-x): '...A key feature of mRNA medicines is their high degree of designability, although the design choices involved are complex...  In this Review, we describe the principles that underlie the physical stability and biological activity of mRNA and emphasize their relevance to the myriad considerations that factor into therapeutic mRNA design ...' (Moderna Research)
- [The Limitless Future of RNA Therapeutics](https://www.frontiersin.org/articles/10.3389/fbioe.2021.628137/full?fbclid=IwAR1hf9aSKPggBAqooXTy7HHsEQQpOCNvQ-frY_gTkX5eVpdiYR1bqUc02eU): '...RNA therapeutics comprise a rapidly expanding category of drugs that will change the standard of care for many diseases and actualize personalized medicine. These drugs are cost-effective, relatively simple to manufacture, and can target previously undruggable pathways. It is a disruptive therapeutic technology, as small biotech startups, as well as academic groups, can rapidly develop new and personalized RNA constructs... we discuss general concepts of different classes of RNA-based therapeutics, including antisense oligonucleotides, aptamers, small interfering RNAs, microRNAs, and messenger RNA... we provide an overview of the RNA-based therapies that are currently being evaluated in clinical trials or have already received regulatory approval...'
- [Therapeutic siRNA: state of the art](https://www.nature.com/articles/s41392-020-0207-x):  '...the evolution of siRNA chemical modifications and their biomedical performance are comprehensively reviewed. All clinically explored and commercialized siRNA delivery platforms, including the GalNAc (N-acetylgalactosamine)–siRNA conjugate, and their fundamental design principles are thoroughly discussed...' 
- [The current landscape of nucleic acid therapeutics](https://www.nature.com/articles/s41565-021-00898-0): '...nucleic acid therapeutics can achieve long-lasting or even curative effects via gene inhibition, addition, replacement or editing. Their clinical translation, however, depends on delivery technologies that improve stability, facilitate internalization and increase target affinity. We review four platform technologies that have enabled the clinical translation of nucleic acid therapeutics: antisense oligonucleotides, ligand-modified small interfering RNA conjugates, lipid nanoparticles and adeno-associated virus vectors...' 




## Tools and webservers 
- [e-RNA: a collection of web-servers for the prediction and visualisation of RNA secondary structure and their functional features](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkad296/7143234): e-RNA is a collection of web-servers for the prediction and visualisation of RNA secondary structures and their functional features, including in particular RNA–RNA interactions

  

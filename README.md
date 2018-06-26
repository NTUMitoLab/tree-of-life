# Sequences of Hominidae(大猿)

## Family of Hominidae

[WikiRef](https://en.wikipedia.org/wiki/Hominidae)

1. Homo sapiens (humans)
2. Pan paniscus (bonobos)
3. Pan troglodytes (chimpanzees)
4. Gorilla beringei (eastern gorillas)
5. Gorilla gorilla (western gorillas)

Others are extinct.

## Analyzing ribosomal RNA sequences (epic fail!)

### ARB project

[Website](https://www.arb-silva.de/)

RAM consumption exploded (>20GB) while loading the big database XD.

## Tools and databases to analyze protein sequences

1. [Phylogeny.fr](http://www.phylogeny.fr/). For the Non-Specialist.
    - [PMC ref1](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2447785/)
    - [PMC ref2](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2821324/)
2. [NCBI gene database](https://www.ncbi.nlm.nih.gov/gene?Db=gene)
3. [Uniprot](https://www.uniprot.org)

### Phylogeny.fr usage

Go to `Phylogeny analysis` section in the homepage

- "One Click" ([Beginner](http://www.phylogeny.fr/simple_phylogeny.cgi)) :
    Paste your set of sequences and let the software make decisions on your behalf (Each step is optimized for your data).
- "Advanced" ([Literally](http://www.phylogeny.fr/advanced.cgi)) :
    Manually set parameters for the various steps.
- "A la Carte" ([Old driver](http://www.phylogeny.fr/alacarte.cgi)) :
    Create your own phylogeny workflow using more programs available.

### Introduction to methods used in Phylogeny.fr pipeline

- [MUSCLE](http://www.drive5.com/muscle/muscle.html) : Multiple sequence comparison by log-expectation
- [PhyML](http://www.atgc-montpellier.fr/phyml/usersguide.php?type=command): Generate phylogenetic trees by maximum likelihood method
- [TreeDyn](http://www.treedyn.org/): Visualization of phylogenetic trees
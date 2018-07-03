# Sequences of Hominidae (大猿)

## Family of Hominidae

[WikiRef](https://en.wikipedia.org/wiki/Hominidae)

1. Homo sapiens (humans)
2. Pan paniscus (bonobos)
3. Pan troglodytes (chimpanzees)
4. Gorilla beringei (eastern gorillas)
5. Gorilla gorilla (western gorillas)
6. Pongo pygmaeus (Bornean orangutan)
7. Pongo tapanuliensis (Tapanuli orangutan)
8. Pongo abelii (Sumatran orangutan)

We choose 1, 2, 3, 5, and 6 since the data are of better qualities

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


## References

1. Dereeper A., Audic S., Claverie J.M., Blanc G. BLAST-EXPLORER helps you building datasets for phylogenetic analysis. BMC Evol Biol. 2010 Jan 12;10:8. (PubMed)
2. Dereeper A.*, Guignon V.*, Blanc G., Audic S., Buffet S., Chevenet F., Dufayard J.F., Guindon S., Lefort V., Lescot M., Claverie J.M., Gascuel O. Phylogeny.fr: robust phylogenetic analysis for the non-specialist. Nucleic Acids Res. 2008 Jul 1;36(Web Server issue):W465-9. Epub 2008 Apr 19. (PubMed) *: joint first authors
3. Edgar RC. MUSCLE: multiple sequence alignment with high accuracy and high throughput. Nucleic Acids Res. 2004, Mar 19;32(5):1792-7. (PubMed)
4. Castresana J. Selection of conserved blocks from multiple alignments for their use in phylogenetic analysis. Mol Biol Evol. 2000, Apr;17(4):540-52. (PubMed)
5. Guindon S., Gascuel O. A simple, fast, and accurate algorithm to estimate large phylogenies by maximum likelihood. Syst Biol. 2003, Oct;52(5):696-704. (PubMed)
6. Anisimova M., Gascuel O. Approximate likelihood ratio test for branchs: A fast, accurate and powerful alternative. Syst Biol. 2006, Aug;55(4):539-52. (PubMed)
7. Chevenet F., Brun C., Banuls AL., Jacq B., Chisten R. TreeDyn: towards dynamic graphics and annotations for analyses of trees. BMC Bioinformatics. 2006, Oct 10;7:439. (PubMed)

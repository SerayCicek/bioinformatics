# bioinformatics
Bioinformatics and Computational Biology Topics, DBs, Challenges, etc.

## Links

- [Open Bioinformatics Foundation GSoC](http://obf.github.io/GSoC/ideas/)
- Graph theory: [chemlambda](https://github.com/chorasimilarity/chemlambda-gui/blob/gh-pages/dynamic/README.md)

## The Cycle

1. data -> interpreation via "tool"
2. tool -> interpret
3. self -> tool
4. go back to 1.

## Criteria

- submitting code/plots to **github** before the presentation
- code inputs and outputs
- explanation related to interpretation of results
- references
- innovation

## Workshops

- R (Bioconductor)
- Python
- bionode/R - [Tutorial](https://github.com/thejmazz/js-bioinformatics-exercise)

## Databases

- ENSEMBL
- NCBI
- UniProt, Pfam
- RNACentral, rfam
- SGD, other species specific DBs
- ontology DBs, FANTOM, GO
- microarray DBs
- RNASeq
- SWISS Model
- STRING, IntAct, MARA

## Undeveloped Ideas

- "data modeling", SQL relations
- "FBA"
- "structure analysis" (+ ramachandran plots)
- "PPI"

## Web Tools

- EMBOSS explorer

## Challenges

### [5] finding secondary structure of RNA

CSC373 6.5

### [1~3] multiple sequence alignment

[Tutorial here](https://github.com/thejmazz/js-bioinformatics-exercise)

- (cancer) cell lines
- similar proteins across species
- domain, family

### [3] expression analysis with GEO2R

Link to BCH441 assignment

### [4] mass spec -> protein

Protein Mass spectrometry is application of mass spectrometry to proteins. Mass spectrometry is a technique that sorts ions according to their mass and gives exact chemical composition of a sample. Mass spectrum is a plot representing an intensity vs mass to charge ratio (m/z).  Peaks found on a protein mass spectrum can used to identify aminoacid residues present. This challenge focusses on obtaining information (structure, chemical composition) of a protein by utilizing mass spectrum given by designing a computational tool. You can use following mass spectrum data from a to C to develop your tool and identify the given examples.

Lınks
- A: https://db.systemsbiology.net/sbeams/cgi/PeptideAtlas/PASS_View?identifier=PASS00096 (MS data is located under data_mzXML)
- B: https://db.systemsbiology.net/sbeams/cgi/PeptideAtlas/PASS_View?identifier=PASS00011 (MS data are the mzXML files, not the excel files)
- C: https://db.systemsbiology.net/sbeams/cgi/PeptideAtlas/PASS_View?identifier=PASS00091 (MS data in the mzXML_Part# folders)

### [3] Phylogenetic Tree

## A -> B Tools

Simple, one step tools, that can be used together in an analysis pipeline.

- BLAST
- PSI-BLAST (iterative though)
- bowtie
- tophat2
- ~

## Visualization Tools

- phylip
- d3
- plotly
- cytoscape.js
- R's `plot()`



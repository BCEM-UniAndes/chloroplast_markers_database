# chloroplast_markers_database

The database included in this repository was used in our study in process of publication as:

**"Taxonomical evaluation of plants genetic markers by Bayesian Classifier"**

*by 

This database contains plant sequences of six chloroplastic markers (trnL, rpoB, rbcL, matK, psbA-trnH and psbK). 
Hereby, we provide a Greengenes-like databases derived from NCBI data for scientists who want to use these resources in their own research. 

Sequences were downloaded from Genbank on September of 2018. The fasta file was modified to include every species' respective taxonomy (donwloaded and linked from NCBI Taxonomy). The taxonomy was included in each fasta header in the respective order: 
>, ID, Taxonomy. 

The taxonomy annotation is: p__(phylum),c__(class),o__(order),f__(family),g__(genus),s__(species). 

This database includes a balanced number of sequences per species. Two different datasets were generated for each molecular marker: 
* The first one with species having a minimum of 2 sequences and a maximum of 20 sequences per species (directory: "2_20_DB"),
* and the second one having a minimum of 5 sequences and a maximum of 20 sequences per species (directory: "5_20_DB"). 

In both cases, species that had more than 20 sequences were randomly subsampled to 20 sequences. The 5-20 dataset was generated in order to evaluate the performance of every marker on general classification, on the other hand, 2-20 dataset was generated to determine dataset bias in marker classification.

We hope this material is useful for you.

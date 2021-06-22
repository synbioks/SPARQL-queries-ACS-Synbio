# SPARQL Queries ACS Synthetic Biology
  This is a repository with a set of sparql queries to answer questions posed in an ACS Synthetic Biology Paper titled: The Synthetic Biology Knowledge System
  Queries should be run in the [sparql interface of synbioks.org](https://synbioks.org/sparql).

  Each query comes as a template where variables are indicated as <variable> and as an example query (fully functional). The different queries are described bellow.
  
## SPARQL Basics
  Any line starting with ```#``` in SPARQL is a comment meaning it will not do anything but describes the code or can be removed to add an additional feature.
  Any urls must be surrounded by ```<``` and ```>``` e.g. ```<https://synbioks.org/public/MoClo_Yeast_Toolkit_Dueber_Lab/KanR/1>```
  For more information on SPARQL see the SPARQL 1.1 [W3 Overview](https://www.w3.org/TR/2013/REC-sparql11-overview-20130321/). 

## Papers by Keyword
  Example queries:
   - What are some papers about metabolic engineering?
   - What are some papers about yeast?
   - What are some papers about S. cerevisiae?
  
  The [example file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/papers_by_keyword_example.sparql) and the [template file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/papers_by_keyword_template.sparql). Remember to copy the PREFIX section too and to remove the prefilled PREFIX lines in the synbioks sparql interface.
  
## Papers by Part Use
  Example query:
   - Which papers use the KanR kanamycin resistance sequence?
  
  The [example file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/papers_by_part_use_example.sparql) and the [template file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/tree/main). Remember to copy the PREFIX section too and to remove the prefilled PREFIX lines in the synbioks sparql interface.
  
## Papers with Multiple Filters
   Example query:
   - Which papers have keyword yeast or S. cerevisiae?
   - Which papers about metabollic engineering use S. cerevisiae?
   - Which papers using KanR kanamycin resistance also use S. cerevisiae?
  
  The [example file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/papers_with_multiple_filters_example.sparql) and the [template file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/papers_with_multiple_filters_template.sparql). Remember to copy the PREFIX section too and to remove the prefilled PREFIX lines in the synbioks sparql interface.
  
## Parts used in a Paper
   Example query:
   - What are all the parts used in 'Genetic Engineering of Bee Gut Microbiome Bacteria with a Toolkit for Modular Assembly of Broad-Host-Range Plasmids'?
   - What are all the parts used in https://pubs.acs.org/doi/10.1021/acssynbio.7b00399?
  
  The [example file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/parts_used_in_a_paper_example.sparql) and the [template file](https://github.com/synbioks/SPARQL-queries-ACS-Synbio/blob/main/parts_used_in_a_paper_template.sparql). Remember to copy the PREFIX section too and to remove the prefilled PREFIX lines in the synbioks sparql interface.

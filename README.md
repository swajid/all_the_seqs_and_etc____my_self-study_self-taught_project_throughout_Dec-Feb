# all_the_seqs_and_etc

```

A Work in Progress
These are notes for myself

->> Super Rough Draft <<-
(Organizing what I know, new stuff etc.)

** very very rough draft, trying to organize a lot of information **

1. Choose a sequencing/profiling method
2. Add branch to tree

Probe, Unknown Sample
├── DNA                                         
│    ├── single cell
│    ├── bulk
│	   │    ├── molecular resolution
│	   │    │   └── 
│    ├── blot
│    │   └── southern blot
│    ├── array
├── RNA
│    ├── molecular resolution
│    │   └── RNA-seq
│    ├── blot
│    │   └── northern blot
├── Protein
│    ├── molecular resolution
│    │   └── ChIP-seq
│    │   └── CLIP-seq
│    ├── blot
│    │   └── western blot

Profiling
├── Regulatory Activity
│    ├── molecular base resolution
│    │   └── ATAC-seq
│    ├── chemical marking
│    │   └── MeRIP-Seq
├── Spatial Transcriptomics
│    ├── molecular resolution
│    ├── visualization via fluorophores
│    │   └── 
├── RNA Structure Profile
│    ├── molecular resolution
│    │   └── 
├── Genotyping
├── Gene Expression Profiling

Interactions/Analysis (Data Analysis / Methods)
├── Gene Enrichment
├── Interactome
│    ├── RNA-RNA
│    ├── RNA-Protein
├── 

Statistical Methods / Models
├── Gene Enrichment
├── Nanopore Basecalling



```


table ideas

name / input / output ? / special equipment / figures / best use cases 

advantages / limitations / application

data generated from sequencer per method in GB/TB/PB

method's avg disk space or memory used for analysis

method's recommended aligner or workflow and etc.

some of my own drawings

* ~ a commit a day, in the evening

[XYZeq](https://advances.sciencemag.org/content/7/17/eabg4755?intcmp=trendmd-adv)

[DART-seq](https://www.researchsquare.com/article/nprot-7063/v1)
* Droplet Assisted RNA Targeting by single cell sequencing

original RNA seq paper

original ChIP seq paper

etc


## all the aggregators/pipelines/workflows for bio/chem/synbio/informatics
### subcategories [`API`, `imagenet`, `wordnet`]

| Project Type | Year   | Github | _Paper_ / Article | Funding | Notes |
| ------------ | ------ |------ | ----- | ------- | ----- |
| Workflow | 2021 |[`PyKale`](https://github.com/pykale/pykale)|[_PyKale: Knowledge-Aware Machine Learning from Multiple Sources in Python_](https://arxiv.org/pdf/2106.09756.pdf) | ["Developing a machine learning tool to improve prognostic and treatment response assessment on cardiac MRI data"](https://grantnav.threesixtygiving.org/grant/360G-Wellcome-215799_Z_19_Z)| <details> _see paper subheadings_ "3.1 Green machine learning" , "6.2 Limitations and future development" </details> |
| Aggregator | 2020 | | [Seven Bridges Selected to Build Cancer Data Aggregator ...](https://www.sevenbridges.com/seven-bridges-to-build-cancer-data-aggregator-for-the-nci/) | [NCI Center for Cancer Data Harmonization (CCDH)](https://datascience.cancer.gov/data-commons/center-cancer-data-harmonization-ccdh) | |
| Aggregator, API | 20** | [`openFDA`](https://github.com/FDA/openfda)| [OpenFDA (API) Data Dictionary](https://open.fda.gov/data/datadictionary) | [FDA](https://open.fda.gov/about/) | <details> luigi, Elasticsearch [etc.](https://github.com/FDA/openfda#contents) </details> |
| Aggregator, imagenet | 20** | | [Medical ImageNet](https://aimi.stanford.edu/research/medical-imagenet) | | |
| Cell Counting | 2021 | - | [_Deep Learning and Transfer Learning for Automatic Cell Counting in Microscope Images of Human Cancer Cell Lines_](https://www.mdpi.com/2076-3417/11/11/4912) | - | compare and contrast / benchmark type of paper |

<!-- this isn't the "secret paper" very different but similar-ish and really great achievement, some ideas on what I'm thinking about -->


## other, what I'm reading/read
`& problems`

* 8/25-28/21 Introduction to Algorithms, Ch 29, "Linear Programming"
  * 29.2 "Formulating problems as linear programs"

9/2-9/7
* A Review Paper: [Potential roles of N6-methyladenosine (m6A) in immune cells](https://pubmed.ncbi.nlm.nih.gov/34103054/) + other related papers <!-- Note: I've never taken anatomy and physiology or immunology, so the bigger picture is new to me -->

10/20-11/5: 
Reading/Taking Notes on: [Software Estimation: Demystifying the Black Art](https://www.goodreads.com/book/show/93891.Software_Estimation) <!-- my copy was printed in 2011 (Copyright 2006) -->
* Tip #1 - "Distinguish between estimates, targets and commitments"
* Tip #115 - "Attack the problem, not the people" - (said by also my dad, for so many years) <!-- my addendum: well, there are still times when the problems are soley because of a person. -->

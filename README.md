# IR-datasets
Search/Retrieval datasets with relevance judgments


- [ ] [CLEFeHealth](https://github.com/CLEFeHealth) with [task descriptions](https://sites.google.com/site/clefehealth/tasks) and [paper](http://doras.dcu.ie/20122/1/SIGIR1013ws_paper12_cameraReady.pdf)
  - [2018](https://sites.google.com/view/clef-ehealth-2018/task-3-consumer-health-search?authuser=0): [**Common crawl** dataset](https://sites.google.com/view/clef-ehealth-2018/task-3-consumer-health-search?authuser=0#h.p_BVbszFZoWcNY)
  - 2016: **ClueWeb 12 B13** will be used this year. If your organization does not have access to this dataset, you can still participate in our task by accessing the infrastructure kindly provided by Microsoft Azure. Nevertheless, every participant should have a licence to use ClueWeb: it is free of charge. This licence can be obtained after filling up and signing every page of the ClueWeb organizational agreement and sending it to lupu@ifs.tuwien.ac.at. Your Azure account will be created only after we receive a confirmation that the license has been obtained.
  - 2013-2015: The data set for task 3 consists of a set of **medical-related documents**, provided by the Khresmoi project. This collection contains documents covering a broad set of medical topics, and does not contain any patient information. The documents in the collection come from **several online sources**, including the Health On the Net organization certified websites, as well as well-known medical sites and databases (e.g. Genetics Home Reference, ClinicalTrial.gov, Diagnosia), covering a broad range of health topics, targeted at both the general public and healthcare professionals. Web pages in the corpus are predominantly medical and health-related websites.


- [ ] [TREC 2017 Precision Medicine Track](http://www.trec-cds.org/2017.html) with [Relevance Judgments](https://trec.nist.gov/data/precmed2017.html)

  Participants of the track will be challenged with retrieving (1) **biomedical articles, in the form of article abstracts** (largely from MEDLINE/PubMed), addressing relevant treatments for the given patient, and (2) clinical trials (from ClinicalTrials.gov), addressing relevant clinical trials for which the patient is eligible. The first set of results represents the retrieval of existing knowledge in the scientific literature, while the second represents the potential for connecting patients with experimental treatments if existing treatments have been ineffective.

  **Scientific Abstracts**: A January 2017 snapshot of PubMed abstracts is used for the scientific abstracts. Additionally, abstracts obtained from AACR and ASCO proceedings are included in this category (these are more targeted toward cancer therapy, and likely to include precision medicine studies not in PubMed). These are only available as TXT files, and the file name (without extension) should be used as the ID in the submission files.

- [ ] [TREC 2016 Clinical Decision Support Track](http://www.trec-cds.org/2016.html) and paper:[Overview of the TREC 2016 Clinical Decision Support Track](https://trec.nist.gov/pubs/trec25/papers/Overview-CL.pdf)

  Participants of the track will be challenged with retrieving full-text biomedical articles that answer questions related to several types of clinical information needs for a given EHR note. Each topic will consist of a note and one of three generic clinical question types, such as "What is the patient's diagnosis?" Retrieved articles will be judged relevant if they provide information of the specified type that is pertinent to the given patient. The evaluation of submissions will follow standard TREC evaluation procedures.

  **Documents**: The target document collection for the track is the Open Access Subset of **PubMed** Central (PMC). PMC is an online digital database of freely available full-text biomedical literature. Because documents are constantly being added to PMC, to ensure the consistency of the collection, for the 2016 task we obtained a snapshot of the open access subset on March 28, 2016 (Note this is an updated collection from last year's track), which contained a 1.25 million articles.


- [ ] [TREC Novelty Tracks](https://trec.nist.gov/data/novelty.html): locate relevant AND new information within a set of documents relevant to a TREC topic. Necessary to purchase **AQUAINT** document collection.
- [ ]  [TREC difficult queries track](https://trec.nist.gov/data/t14_robust.html) Necessary to purchase **AQUAINT** document collection.
- [ ] [TREC-9 Filtering Track](https://trec.nist.gov/data/t9_filtering.html) The **OHSUMED** test collection is a set of 348,566 references from **MEDLINE**, the on-line medical information database, consisting of **titles and/or abstracts** from 270 medical journals over a five-year period (1987-1991). The available fields are title, abstract, MeSH indexing terms, author, source, and publication type.
- [ ] [LETOR from Microsoft](https://www.microsoft.com/en-us/research/project/letor-learning-rank-information-retrieval/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fum%2Fbeijing%2Fprojects%2Fletor%2F) "a package of benchmark data sets for research on LEarning TO Rank. This data set contains standard features, relevance judgments, data partitioning, evaluation tools, and several baselines, for the **OHSUMED** data collection and the **'.gov'** data collection." 
- [ ] [TREC Total Recall track 2015,2016](https://plg.uwaterloo.ca/~gvcormac/total-recall/) Lengthy data acquisition process. [Sample dataset](https://github.com/hical/sample-dataset) Have to sign and email forms to *possibly* get the data or access the Web server

  Participants in the Total Recall Track will investigate tools and strategies to find, given a topic and a collection of documents, with as little human effort as possible, as nearly all of the relevant documents as possible.

  Given a simple topic description – like those typically used for ad-hoc and Web search – identify the documents in a corpus, one at a time, such that, as nearly as possible, all relevant documents are identified before all non-relevant documents. Immediately after each document is identified, its ground- truth relevance or non-relevance is disclosed.

- [ ] [Reuters Corpus Volume I (RCV1)](http://scikit-learn.org/0.19/datasets/rcv1.html) and [TREC 2010 Legal Track](https://trec.nist.gov/data/legal10.html) used in [Active Search for High Recall: a Non-Stationary Extension of Thompson Sampling](https://arxiv.org/abs/1712.09550)


# Software

- [Open sourced system for High-Recall retrieval with a nice interface](https://hical.github.io) Commercial use - GNU General Public License v3.0

# Other datasets 
- [ ]  [Pubmed data](ftp://ftp.ncbi.nlm.nih.gov/pubmed/updatefiles/README.txt) and [Daily update files](ftp://ftp.ncbi.nlm.nih.gov/pubmed/updatefiles) sign as Guest
- [ ] [arxiv data](https://arxiv.org/help/bulk_data)

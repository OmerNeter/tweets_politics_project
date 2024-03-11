# Tweets_Politics_Project
This repository includes all code and links to data sets used in the study "“Signals of Propaganda” - Detecting and Estimating Political Influences in Information Cascades in Social Networks".
The article presents a method to distinguish between political (biased) and non-political (disasters) information cascades on Twitter (now X).  

There are 3 main directories, where the code is locaded as an ipython code in each directory with code and one directory with images. Also olded versions of the project are found in "_old-files" and .ipynb_checkpoints". 
1. **Hashtag analysis. (named hashtags).**
  1.1 distribution of counts of hashtags
  1.2 slopes on log-log scale
  1.3 PLMSE computation.
   
2. **Users analysis (named network).**
   2.1 distribution of counts of users
   2.2 slopes on log-log scale ( we came into conclusion that the users are NOT distributed by a power law, but it is some type of long tail.
   2.3 PLMSE computation.

3. **Network analysis (named network)**
The excel table named Network_datasets in the main root directory includes links to all datasets used in the work.
The data from which we constructed the networks was downloaded from 2 different sources.
   3.1 csv files see (Kaggle, see link in code)
   3.2 jsonl files see (Zubiaga, A. (2018). A longitudinal assessment of the persistence of twitter datasets. Journal of the Association for Information Science and Technology, 69(8), 974-984.)

4. **images** - images produced during the project, not all images are included in the article.

5. All data sources and their links are found in the file named "DataSources.xlsx" in column "J".
   The data sets were first downloaded manually to a local machine, then processed by the ipython code give in each directory.
   Due to data size, we cannot upload all datasets to the git.
   We uploaded datasets when it was posibe, and in each case (hashtags, users, networks) we added at least one dataset so that it can be run with the code and also added the links to the additional datasets. 
   
6. File named "Fig4 A-D.xlsx" includes the data points to produce image 4, which show the separatation values of the two types of cascades (political vs. disasters). In this excell file, one tab includes the Users analysis (sub figures A,B) and the second tab the Hashtags analysis, (sub-figures C, D).
   
7. *** the .ipynb_checkpoints folders are old code, which were not deleted, but generally include code and images that were not the last version used in the manuscript. Also the "old-files" include backup and older versions of the project.

8. The code was produce by Omer Neter while Alon Sela suggested the directions and methods as well as supervised.

[![DOI](https://zenodo.org/badge/386157510.svg)](https://zenodo.org/doi/10.5281/zenodo.10805273)
   

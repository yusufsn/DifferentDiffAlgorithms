# Research Artifact: How Different Are Different diff Algorithms in Git?

[https://github.com/yusufsn/DifferentDiffAlgorithms](https://github.com/yusufsn/DifferentDiffAlgorithms)

This is a research artifact for the paper **How Different Are Different diff Algorithms in Git? Use --histogram for Code Changes**. This artifact is a repository consisting of (a) SZZ implementation; code for investigating the disagreement level of `diff` outputs produced by two `diff` algorithms: Myers and Histogram using SZZ (i.e. an approach to identify bug-introducing changes); and (b) dataset including (i) 468,311 files associated with the information of commit identity number, parent commit identity number, filepath, and project name (RQ1); (ii) 14,883 files including the information of filepath, candidate of bug-fixing commit identity number, parent commit identity number and project name (RQ2); and (iii) all 21,590 files with the information of project name, filename, filepath, commit identity number, parent commit identity number, and the number of different identified code changes (RQ3). 


## Contents
* `SZZ` - SZZ implementation. The installation and the operation procedure can be found [here](https://github.com/yusufsn/DifferentDiffAlgorithms/blob/master/SZZ/INSTALL.md)
* `dataset` - a directory of the dataset
  * `52_collected_papers.csv` - 52 collected papers used in our systematic mapping study (.csv format)
  * `468311_RQ1_all_CI-Java_targeted_files.csv.zip` - RQ1: all collected files from 14 CI-Java projects for Metrics comparison (.zip format)
  * `14883_RQ2_all_apache_targeted_files.csv` - RQ2: all collected files from the extracted bug-fixing commit candidates in 10 Apache Java projects for SZZ result comparison (.csv format)
  * `21590_RQ3_files_having_different_changes_of_all_projects.csv` - RQ3: all collected files that have different code changes from all targeted projects in RQ1 and RQ2 (.csv format)
* `README.md` - this file

## Authors
* [Yusuf Sulistyo Nugroho](https://yusufsn.github.io/)
* [Hideaki Hata](https://hideakihata.github.io/)
* Kenichi Matsumoto

## Related Paper
* Published version in Journal of [Empirical Software Engineering](https://link.springer.com/article/10.1007/s10664-019-09772-z)
* Preprint version in [ArXiv](https://arxiv.org/abs/1902.02467)

## MIT License for code
Our SZZ implementation is licensed under the [MIT License](LICENSE.md).

## CC0 1.0 Universal for dataset
CC0 [summary](https://creativecommons.org/publicdomain/zero/1.0/) and [legal text](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

Our dataset are published on the public domain, so that anyone may freely build upon, enhance and reuse the dataset for any purposes without restriction under copyright or database law.

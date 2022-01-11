## Lexical Semantic Change: Models, Data and Evaluation


Lexical Semantic Change (LSC) is a phenomenon associated with the diachronic evolution of the meanings of a word. 
In historical linguistics, it is a well-known problem, which is recently gaining momentum also in the Natural Language Processing (NLP) and Computational Lingustics (CL) communities, thanks to the availability of both large diachronic corpora and evaluation benchmarks.

This tutorial will present an overview of the current approaches, problems and challenges in this research field. The tutorial will consist of two parts. First, we will provide an introduction to Lexical Semantic Change and to the available resources (corpora and data sets) for the study of meanings in diachrony. We will highlight issues in the creation and use of diachronic corpora, as well as different procedure for the annotation of data. In the second part, we will introduce the current state-of-the-art approaches for the automatic detection of LSC and we will provide an hands-on section on available systems and tools.


## Outline


### Introduction


### Data

#### Diachronic resources

- Diachronic Corpora (e.g. The New York Times Annotated Corpus [1], Corpus of Contemporary American English [2], L'Unità corpus [3])

- Other resources

  - Co-occurrence matrices (e.g. Dukweb [4])

  - Ngrams (e.g. Google Ngrams)

  - Lexicographic resources 

- Annotation of Lexical Semantic Changes


### Models

#### Alignment Models

- Post-alignment models (e.g. OP [5], Canonical Analysis [15])

- Jointly alignment models (e.g. TRI [6], TWEC [7], TR [8], DWE [9], DBE [10])

#### Other Models

- Frequency-based models

- Contextualized models

- Word Sense Induction

- Grammatical and syntax approaches


### Evaluation

#### Tasks

- Binary task (e.g. Semeval 2020 Task 1 Subtask 1 [11], DIACR-Ita [12])

- Graded task (e.g. Semeval 2020 Task 1 Subtask 2 [11], RushiftEval [13])

- Temporal Analogies [9]

- Lexical Semantic Change Discovery [14]

#### Results

- Baselines

- State-of-the-art approaches


## References

[1]    E. Sandhaus, “The new york times annotated corpus,” Linguist. Data Consort. Phila., vol. 6, no. 12, p. e26752, 2008.

[2]    R. Alatrash, D. Schlechtweg, J. Kuhn, and S. S. im Walde, “CCOHA: Clean Corpus of Historical American English,” in Proceedings of The 12th Language Resources and Evaluation Conference, 2020, pp. 6958–6966.

[3]    P. Basile, A. Caputo, T. Caselli, P. Cassotti, and R. Varvara, “A Diachronic Italian Corpus based on ‘L’Unità,’” in Proceedings of the Seventh Italian Conference on Computational Linguistics, CLiC-it 2020, Bologna, Italy, March 1-3, 2021, 2020, vol. 2769. [Online]. Available: http://ceur-ws.org/Vol-2769/paper\_44.pdf

[4]    A. Tsakalidis, P. Basile, M. Bazzi, M. Cucuringu, and B. McGillivray, “DUKweb, diachronic word representations from the UK Web Archive corpus,” Sci. Data, vol. 8, no. 1, pp. 1–12, 2021.

[5]    W. L. Hamilton, J. Leskovec, and D. Jurafsky, “Diachronie word embeddings reveal statistical laws of semantic change,” in 54th Annual Meeting of the Association for Computational Linguistics, ACL 2016 - Long Papers, May 2016, vol. 3, pp. 1489–1501. [Online]. Available: http://arxiv.org/abs/1605.09096

[6]    P. Basile, A. Caputo, and G. Semeraro, “Analysing word meaning over time by exploiting temporal random indexing,” 2014.

[7]    V. D. Carlo, F. Bianchi, and M. Palmonari, “Training Temporal Word Embeddings with a Compass,” in The Thirty-Third AAAI Conference on Artificial Intelligence, AAAI 2019, The Thirty-First Innovative Applications of Artificial Intelligence Conference, IAAI 2019, The Ninth AAAI Symposium on Educational Advances in Artificial Intelligence, EAAI, Honolulu, Hawaii,USA, Jan. 2019, pp. 6326–6334. doi: 10.1609/aaai.v33i01.33016326.

[8]    H. Dubossarsky, S. Hengchen, N. Tahmasebi, and D. Schlechtweg, “Time-Out: Temporal Referencing for Robust Modeling of Lexical Semantic Change,” in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 2019, pp. 457–470.

[9]    Z. Yao, Y. Sun, W. Ding, N. Rao, and H. Xiong, “Dynamic word embeddings for evolving semantic discovery,” in WSDM 2018 - Proceedings of the 11th ACM International Conference on Web Search and Data Mining, Feb. 2018, vol. 2018-Febua, pp. 673–681. doi: 10.1145/3159652.3159703.

[10]    M. R. Rudolph and D. M. Blei, “Dynamic Embeddings for Language Evolution,” in Proceedings of the 2018 World Wide Web Conference on World Wide Web, WWW 2018, Lyon, France, April 23-27, 2018, 2018, pp. 1003–1011. doi: 10.1145/3178876.3185999.

[11]    D. Schlechtweg, B. McGillivray, S. Hengchen, H. Dubossarsky, and N. Tahmasebi, “SemEval-2020 Task 1: Unsupervised Lexical Semantic Change Detection,” in Proceedings of the Fourteenth Workshop on Semantic Evaluation, SemEval@COLING 2020, Barcelona (online), December 12-13, 2020, 2020, pp. 1–23. [Online]. Available: https://www.aclweb.org/anthology/2020.semeval-1.1/

[12]    P. Basile, A. Caputo, T. Caselli, P. Cassotti, and R. Varvara, “DIACR-Ita @ EVALITA2020: Overview of the EVALITA2020 Diachronic Lexical Semantics (DIACR-Ita) Task,” in Proceedings of the Seventh Evaluation Campaign of Natural Language Processing and Speech Tools for Italian. Final Workshop (EVALITA 2020), Online event, December 17th, 2020, 2020, vol. 2765. [Online]. Available: http://ceur-ws.org/Vol-2765/paper158.pdf

[13]    A. Kutuzov, L. Pivovarova, and others, “RuShiftEval: a shared task on semantic shift detection for Russian,” 2021.

[14]    S. Kurtyigit, M. Park, D. Schlechtweg, J. Kuhn, and S. Schulte im Walde, “Lexical Semantic Change Discovery,” in Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), Online, Aug. 2021, pp. 6985–6998. doi: 10.18653/v1/2021.acl-long.543.

[15]    O. Pražák, P. Přibáň, S. Taylor, and J. Sido, “UWB at SemEval-2020 Task 1: Lexical Semantic Change Detection,” in Proceedings of the Fourteenth Workshop on Semantic Evaluation, 2020, pp. 246–254.

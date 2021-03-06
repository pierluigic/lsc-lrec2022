## Lexical Semantic Change: Models, Data and Evaluation


Lexical Semantic Change (LSC) is a phenomenon associated with the diachronic evolution of the meanings of a word. 
In historical linguistics, it is a well-known problem, which is recently gaining momentum also in the Natural Language Processing (NLP) and Computational Lingustics (CL) communities, thanks to the availability of both large diachronic corpora and evaluation benchmarks.

This tutorial will present an overview of the current approaches, problems and challenges in this research field. The tutorial will consist of two parts. First, we will provide an introduction to Lexical Semantic Change and to the available resources (corpora and data sets) for the study of meanings in diachrony. We will highlight issues in the creation and use of diachronic corpora, as well as different procedure for the annotation of data. In the second part, we will introduce the current state-of-the-art approaches for the automatic detection of LSC and we will provide an hands-on section on available systems and tools.

Registration is open [https://lrec2022.lrec-conf.org/en/registration/](https://lrec2022.lrec-conf.org/en/registration/)

The schedule is available here [https://lrec2022.lrec-conf.org/en/workshops-and-tutorials/ws-tut-schedule/](https://lrec2022.lrec-conf.org/en/workshops-and-tutorials/ws-tut-schedule/)

___

## Speakers
[Pierpaolo Basile](http://www.di.uniba.it/~swap/index.php?n=Membri.Basile), University of Bari, Italy

[Annalina Caputo](https://annalina.github.io/), Dublin City University, Ireland

Pierluigi Cassotti, University of Bari, Italy

[Rossella Varvara](https://www3.unifr.ch/directory/en/people/343639/d1f2e), Universit√© de Fribourg, Switzerland

___

## Slides

- [Introduction](https://github.com/pierluigic/lsc-lrec2022/blob/gh-pages/LSC%20Tutorial%20-%20LREC%202022%20-%20Introduction.pdf)
- [Data](https://github.com/pierluigic/lsc-lrec2022/blob/gh-pages/LSC%20Tutorial%20-%20LREC%202022%20-%20Data.pdf)
- [Models](https://github.com/pierluigic/lsc-lrec2022/blob/gh-pages/LSC%20Tutorial%20-%20LREC%202022%20-%20Models.pdf)
- [Evaluation](https://github.com/pierluigic/lsc-lrec2022/blob/gh-pages/LSC%20Tutorial%20-%20LREC%202022%20-%20Evaluation.pdf)

___

## Outline

### [09:00-09:15] **Introduction** 


### [09:15-10:00] **Data**

#### Diachronic resources

- Diachronic Corpora (e.g. The New York Times Annotated Corpus [1], Corpus of Contemporary American English [2], L'Unit√† corpus [3])

- Other resources

  - Co-occurrence matrices (e.g. Dukweb [4])

  - Ngrams (e.g. Google Ngrams)

  - Lexicographic resources 

#### Annotation of Lexical Semantic Changes


### [10:00-10:30] **Models Part I**

#### Background concepts

- PPMI matrix factorization
- Word2Vec Skip-gram with Negative Sampling (SGNS)
- BERT-based models

#### Alignment Models

- Post-alignment models (e.g. Orthogonal Procrustes [5])

- Jointly alignment models (e.g. Temporal Random Indexing (TRI) [6], Temporal Word Embedding with a Compass (TWEC) [7], Temporal Referencing (TR) [8], Dynamic Word Embedding (DWE) [9], 
Dynamic Bernoulli Embedding (DBE) [10])


### [10:30-11:45] Break  


### [11:00-11:45] **Models Part II**


#### Contextualized Models

- TempoBERT
- Temporal Attention
- Deep Mistake
- Gloss Reader


#### Other Models

- Local Neighborhood measure
- Word Sense Induction
- Grammatical Features


### [11:45-12:15] **Evaluation** 

#### Tasks

- Binary task (e.g. Semeval 2020 Task 1 Subtask 1 [11], DIACR-Ita [12])

- Graded task (e.g. Semeval 2020 Task 1 Subtask 2 [11], RushiftEval [13])

- Temporal Analogies [9]

- Lexical Semantic Change Discovery [14]

#### Results

- Baselines

- State-of-the-art approaches

### [12:15-13:00] **Hands-on**

- Word2Vec Skip-grams with Negative Sampling (SGNS) and Orthogonal Procrustes (OP) ([Colab Notebook](https://colab.research.google.com/drive/1pnA1VX8YDDQu-6jayUTy3z9AQesEUmYs?usp=sharing))

- BERT for Lexical Semantic Change ([Colab Notebook](https://colab.research.google.com/drive/1aQZkX1YQki5W7aXCec0lu_3rZhlkw7u8?usp=sharing))

___


## References

[1]    E. Sandhaus, ‚ÄúThe new york times annotated corpus,‚ÄĚ Linguist. Data Consort. Phila., vol. 6, no. 12, p. e26752, 2008.

[2]    R. Alatrash, D. Schlechtweg, J. Kuhn, and S. S. im Walde, ‚ÄúCCOHA: Clean Corpus of Historical American English,‚ÄĚ in Proceedings of The 12th Language Resources and Evaluation Conference, 2020, pp. 6958‚Äď6966.

[3]    P. Basile, A. Caputo, T. Caselli, P. Cassotti, and R. Varvara, ‚ÄúA Diachronic Italian Corpus based on ‚ÄėL‚ÄôUnit√†,‚Äô‚ÄĚ in Proceedings of the Seventh Italian Conference on Computational Linguistics, CLiC-it 2020, Bologna, Italy, March 1-3, 2021, 2020, vol. 2769. [Online]. Available: http://ceur-ws.org/Vol-2769/paper\_44.pdf

[4]    A. Tsakalidis, P. Basile, M. Bazzi, M. Cucuringu, and B. McGillivray, ‚ÄúDUKweb, diachronic word representations from the UK Web Archive corpus,‚ÄĚ Sci. Data, vol. 8, no. 1, pp. 1‚Äď12, 2021.

[5]    W. L. Hamilton, J. Leskovec, and D. Jurafsky, ‚ÄúDiachronie word embeddings reveal statistical laws of semantic change,‚ÄĚ in 54th Annual Meeting of the Association for Computational Linguistics, ACL 2016 - Long Papers, May 2016, vol. 3, pp. 1489‚Äď1501. [Online]. Available: http://arxiv.org/abs/1605.09096

[6]    P. Basile, A. Caputo, and G. Semeraro, ‚ÄúAnalysing word meaning over time by exploiting temporal random indexing,‚ÄĚ In The First Italian Conference on Computational Linguistics CLiC-it 2014 (p. 38-42). 

[7]    V. D. Carlo, F. Bianchi, and M. Palmonari, ‚ÄúTraining Temporal Word Embeddings with a Compass,‚ÄĚ in The Thirty-Third AAAI Conference on Artificial Intelligence, AAAI 2019, The Thirty-First Innovative Applications of Artificial Intelligence Conference, IAAI 2019, The Ninth AAAI Symposium on Educational Advances in Artificial Intelligence, EAAI, Honolulu, Hawaii,USA, Jan. 2019, pp. 6326‚Äď6334. doi: 10.1609/aaai.v33i01.33016326.

[8]    H. Dubossarsky, S. Hengchen, N. Tahmasebi, and D. Schlechtweg, ‚ÄúTime-Out: Temporal Referencing for Robust Modeling of Lexical Semantic Change,‚ÄĚ in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 2019, pp. 457‚Äď470.

[9]    Z. Yao, Y. Sun, W. Ding, N. Rao, and H. Xiong, ‚ÄúDynamic word embeddings for evolving semantic discovery,‚ÄĚ in WSDM 2018 - Proceedings of the 11th ACM International Conference on Web Search and Data Mining, Feb. 2018, vol. 2018-Febua, pp. 673‚Äď681. doi: 10.1145/3159652.3159703.

[10]    M. R. Rudolph and D. M. Blei, ‚ÄúDynamic Embeddings for Language Evolution,‚ÄĚ in Proceedings of the 2018 World Wide Web Conference on World Wide Web, WWW 2018, Lyon, France, April 23-27, 2018, 2018, pp. 1003‚Äď1011. doi: 10.1145/3178876.3185999.

[11]    D. Schlechtweg, B. McGillivray, S. Hengchen, H. Dubossarsky, and N. Tahmasebi, ‚ÄúSemEval-2020 Task 1: Unsupervised Lexical Semantic Change Detection,‚ÄĚ in Proceedings of the Fourteenth Workshop on Semantic Evaluation, SemEval@COLING 2020, Barcelona (online), December 12-13, 2020, 2020, pp. 1‚Äď23. [Online]. Available: https://www.aclweb.org/anthology/2020.semeval-1.1/

[12]    P. Basile, A. Caputo, T. Caselli, P. Cassotti, and R. Varvara, ‚ÄúDIACR-Ita @ EVALITA2020: Overview of the EVALITA2020 Diachronic Lexical Semantics (DIACR-Ita) Task,‚ÄĚ in Proceedings of the Seventh Evaluation Campaign of Natural Language Processing and Speech Tools for Italian. Final Workshop (EVALITA 2020), Online event, December 17th, 2020, 2020, vol. 2765. [Online]. Available: http://ceur-ws.org/Vol-2765/paper158.pdf

[13]    A. Kutuzov, L. Pivovarova, and others, ‚ÄúRuShiftEval: a shared task on semantic shift detection for Russian,‚ÄĚ  In Computational linguistics and intellectual technologies: Papers from the annual conference Dialogue. Redkollegija sbornika.

[14]    S. Kurtyigit, M. Park, D. Schlechtweg, J. Kuhn, and S. Schulte im Walde, ‚ÄúLexical Semantic Change Discovery,‚ÄĚ in Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), Online, Aug. 2021, pp. 6985‚Äď6998. doi: 10.18653/v1/2021.acl-long.543.

[15]    O. PraŇĺ√°k, P. PŇôib√°Ňą, S. Taylor, and J. Sido, ‚ÄúUWB at SemEval-2020 Task 1: Lexical Semantic Change Detection,‚ÄĚ in Proceedings of the Fourteenth Workshop on Semantic Evaluation, 2020, pp. 246‚Äď254.

# Awesome-Word-Embeddings
This is a monolingual and cross-lingual word representation reading list maintained by muyeby!

* [Monolingual word embeddings](#monolingual_word_embeddings)
    * [Tutorials](#mwe_tutorials)
    
* [Cross-lingual word embeddings](#cross-lingual_word_embeddings)
    * [Tutorials](#clwe_tutorials)
    * [Supervised models](#clwe_su)
    * [Semi-supervised models](#clwe_semi)
    * [Unsupervised models](#clwe_un)
    
<h2 id="Monolingual word embeddings">Monolingual word embeddings</h2>
<h3 id="mwe_tutorials">Tutorials</h3>
<h2 id="Cross-lingual word embeddings">Cross-lingual word embeddings</h2>

<h3 id="clwe_tutorials">Tutorials</h3>

* Sebastian Ruder, Ivan Vulić, and Anders Søgaard. 2017. [A Survey Of Cross-lingual Word Embedding Models](https://arxiv.org/pdf/1706.04902.pdf). *arxiv:1706.04902*. [[BibTeX](https://dblp.uni-trier.de/rec/bibtex/journals/corr/Ruder17)]
* Ivan Vuli¢, Anders Søgaard, Manaal Faruqui. 2017. [Cross-Lingual Word Representations: Induction and Evaluation](http://people.ds.cam.ac.uk/iv250/tutorial/xlingrep-tutorial.pdf). In *Proceedings of EMNLP 2017*.
* Anders Søgaard, Sebastian Ruder, and Ivan Vulić. 2018. [On the Limitations of Unsupervised Bilingual Dictionary Induction](http://aclweb.org/anthology/P18-1072). In *Proceedings of ACL 2018*. [[BibTeX](https://aclanthology.info/papers/P18-1072/p18-1072.bib)]
<h3 id="clwe_su">Supervised models</h3>

* Tomas Mikolov, Quoc V. Le, and Ilya Sutskever. 2013. [Exploiting Similarities among Languages for Machine Translation](https://arxiv.org/pdf/1309.4168.pdf). *arxiv:1309.4168*. [[BibTeX](https://dblp.uni-trier.de/rec/bibtex/journals/corr/MikolovLS13)]
* Manaal Faruqui and Chris Dyer. 2014 [Improving vector space word representations
using multilingual correlation](http://aclweb.org/anthology/E14-1049). In *Proceedings of EACL 2014*. [[BibTeX](https://aclanthology.info/papers/E14-1049/e14-1049.bib)] [[Code](https://github.com/mfaruqui/crosslingual-cca)]
* Georgiana Dinu, Angeliki Lazaridou, and Marco Baroni. 2015. [Improving Zero-shot Learning by Mitigating the Hubness Problem](https://arxiv.org/pdf/1412.6568.pdf). In *Proceedings of ICLR 2015*. [[BibTeX](https://dblp.uni-trier.de/rec/bibtex/journals/corr/DinuB14)] 
* Chao Xing, Dong Wang, Chao Liu, Yiye Lin. 2015. [Normalized word embedding and orthogonal transform for bilingual word translation](http://aclweb.org/anthology/N15-11040). In *Proceedings of NAACL 2015*. [[BibTeX](https://aclanthology.info/papers/N15-1104/n15-1104.bib)]
* Meng Zhang, Yang Liu, Huanbo Luan, Maosong Sun, Tatsuya Izuha, and Jie Hao. 2016. [Building Earth Mover's Distance on Bilingual Word Embeddings for Machine Translation](http://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/12227/12035). In *Proceedings of AAAI 2016*. [[BibTeX](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/rt/captureCite/12227/0/BibtexCitationPlugin)]
* Meng Zhang, Yang Liu, Huanbo Luan, Yiqun Liu, and Maosong Sun. 2016. [Inducing Bilingual Lexica From Non-Parallel Data With Earth Mover's Distance Regularization](http://aclweb.org/anthology/C16-1300). In *Proceedings of COLING 2016*. [[BibTeX](https://aclanthology.info/papers/C16-1300/c16-1300.bib)]
* Ivan Vulić and Anna Korhonen. [On the Role of Seed Lexicons in Learning Bilingual Word Embeddings](http://www.aclweb.org/anthology/P16-1024). In *Proceedings of ACL 2016*. [[BibTeX](https://aclanthology.info/papers/P16-1024/p16-1024.bib)]
* Ann Irvine and Chris Callison-Burch. 2017. [A Comprehensive Analysis of Bilingual Lexicon Induction](http://aclweb.org/anthology/J17-2001). *Computational Linguistics*. [[BibTeX](https://aclanthology.info/papers/J17-2001/j17-2001.bib)]
* Geert Heyman, Ivan Vulić, and Marie-Francine Moens. 2017. [Bilingual Lexicon Induction by Learning to Combine Word-Level and Character-Level Representations](http://aclweb.org/anthology/E17-1102). In *Proceedings of EACL 2017*. [[BibTeX](https://aclanthology.info/papers/E17-1102/e17-1102.bib)]
* Ndapa Nakashole. 2018. [NORMA: Neighborhood Sensitive Maps for Multilingual Word Embeddings](http://aclweb.org/anthology/D18-1047). In *Proceedings of EMNLP 2018*. [[BibTeX](https://aclanthology.info/papers/D18-1047/d18-1047.bib)]
* Yerai Doval, Jose Camacho-Collados, Luis Espinosa Anke, and Steven Schockaert. 2018. [Improving Cross-Lingual Word Embeddings by Meeting in the Middle](http://aclweb.org/anthology/D18-1027). In *Proceedings of EMNLP 2018*. [[BibTeX](https://aclanthology.info/papers/D18-1027/d18-1027.bib)]

<h3 id="clwe_semi">Semi-supervised models</h3>

* Meng Zhang, Haoruo Peng, Yang Liu, Huanbo Luan, and Maosong Sun. [Bilingual Lexicon Induction from Non-Parallel Data with Minimal Supervision](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14682/14264). In *Proceedings of AAAI 2017*. [[BibTeX](https://aaai.org/ocs/index.php/AAAI/AAAI17/rt/captureCite/14682/0/BibtexCitationPlugin)] [[Code](http://nlp.csai.tsinghua.edu.cn/~zm/EmbeddingMatching/)]
* Mikel Artetxe, Gorka Labaka, and Eneko Agirre. 2017. [Learning Bilingual Word Embeddings with (Almost) No Bilingual Data](http://aclweb.org/anthology/P17-1042). In *Proceedings of ACL 2017*. [[BibTeX](https://aclanthology.info/papers/P17-1042/p17-1042.bib)]
[[Code](https://github.com/artetxem/vecmap)]
<h3 id="clwe_un">Unsupervised models</h3>

* Meng Zhang, Yang Liu, Huanbo Luan, and Maosong Sun. 2017. [Adversarial Training for Unsupervised Bilingual Lexicon Induction](http://aclweb.org/anthology/P17-1179). In *Proceedings of ACL 2017*. [[BibTeX](https://aclanthology.info/papers/P17-1179/p17-1179)] [[Code](http://nlp.csai.tsinghua.edu.cn/~zm/UBiLexAT/)]
* Bradley Hauer, Garrett Nicolai, and Grzegorz Kondrak. 2017. [Bootstrapping Unsupervised Bilingual Lexicon Induction](http://aclweb.org/anthology/E17-2098). In *Proceedings of EACL 2017*. [[BibTeX](https://aclanthology.info/papers/E17-2098/e17-2098.bib)]
* Yunsu Kim, Julian Schamper, and Hermann Ney. 2017. [Unsupervised Training for Large Vocabulary Translation Using Sparse Lexicon and Word Classes](http://aclweb.org/anthology/E17-2103). In *Proceedings of EACL 2017*. [[BibTeX](https://aclanthology.info/papers/E17-2103/e17-2103.bib)]
* Derry Tanti Wijaya, Brendan Callahan, John Hewitt, Jie Gao, Xiao Ling, Marianna Apidianaki, and Chris Callison-Burch. 2017. [Learning Translations via Matrix Completion](http://aclweb.org/anthology/D17-1152). In *Proceedings of EMNLP 2017*. [[BibTeX](https://aclanthology.info/papers/D17-1152/d17-1152.bib)]
* Meng Zhang, Yang Liu, Huanbo Luan, and Maosong Sun. 2017. [Earth Mover's Distance Minimization for Unsupervised Bilingual Lexicon Induction](http://aclweb.org/anthology/D17-1207). In *Proceedings of EMNLP 2017*. [[BibTeX](https://aclanthology.info/papers/D17-1207/d17-1207.bib)] [[Code](http://nlp.csai.tsinghua.edu.cn/~zm/UBiLexEMD/)]
* Ndapandula Nakashole and Raphael Flauger. 2017. [Knowledge Distillation for Bilingual Dictionary Induction](http://aclweb.org/anthology/D17-1264). In *Proceedings of EMNLP 2017*. [[BibTeX](https://aclanthology.info/papers/D17-1264/d17-1264.bib)]
* Guillaume Lample, Alexis Conneau, Marc'Aurelio Ranzato, Ludovic Denoyer, and Hervé Jégou. 2018. [Word Translation without Parallel Data](https://openreview.net/pdf?id=H196sainb). In *Proceedings of ICLR 2018*. [[BibTeX](https://openreview.net/forum?id=H196sainb)] [[Code](https://github.com/facebookresearch/MUSE)]
* Fabienne Braune, Viktor Hangya, Tobias Eder, and Alexander Fraser. 2018. [Evaluating Bilingual Word Embeddings on the Long Tail](http://aclweb.org/anthology/N18-2030). In *Proceedings of NAACL 2018*. [[BibTeX](https://aclanthology.info/papers/N18-2030/n18-2030.bib)]
* Ndapa Nakashole and Raphael Flauger. 2018. [Characterizing Departures from Linearity in Word Translation](http://aclweb.org/anthology/P18-2036). In *Proceedings of ACL 2018*. [[BibTeX](https://aclanthology.info/papers/P18-2036/p18-2036)]
* Mikel Artetxe, Gorka Labaka, and Eneko Agirre. 2018. [A Robust Self-learning Method for Fully Unsupervised Cross-lingual Mappings of Word Embeddings](http://aclweb.org/anthology/P18-1073). In *Proceedings of ACL 2018*. [[BibTeX](https://aclanthology.info/papers/P18-1073/p18-1073.bib)] [[Code](https://github.com/artetxem/vecmap)]
* Parker Riley and Daniel Gildea. 2018. [Orthographic Features for Bilingual Lexicon Induction](http://aclweb.org/anthology/P18-2062). In *Proceedings of ACL 2018*. [[BibTeX](https://aclanthology.info/papers/P18-2062/p18-2062.bib)]
* Amir Hazem and Emmanuel Morin. 2018. [Leveraging Meta-Embeddings for Bilingual Lexicon Extraction from Specialized Comparable Corpora](http://aclweb.org/anthology/C18-1080). In *Proceedings of COLING 2018*. [[BibTeX](https://aclanthology.info/papers/C18-1080/c18-1080.bib)]
* Xilun Chen and Claire Cardie. 2018. [Unsupervised Multilingual Word Embeddings](http://aclweb.org/anthology/D18-1024). In *Proceedings of EMNLP 2018*. [[BibTeX](https://aclanthology.info/papers/D18-1024/d18-1024.bib)]
* Sebastian Ruder, Ryan Cotterell, Yova Kementchedjhieva, and Anders Søgaard. 2018. [A Discriminative Latent-Variable Model for Bilingual Lexicon Induction](http://aclweb.org/anthology/D18-1042). In *Proceedings of EMNLP 2018*. [[BibTeX](https://aclanthology.info/papers/D18-1042/d18-1042.bib)]
* Zi-Yi Dou, Zhi-Hao Zhou, and Shujian Huang. 2018. [Unsupervised Bilingual Lexicon Induction via Latent Variable Models](http://aclweb.org/anthology/D18-1062). In *Proceedings of EMNLP 2018*. [[BibTeX](https://aclanthology.info/papers/D18-1062/d18-1062.bib)]
* Armand Joulin, Piotr Bojanowski, Tomas Mikolov, Hervé Jégou, and Edouard Grave. 2018. [Loss in Translation: Learning Bilingual Word Mapping with a Retrieval Criterion](http://aclweb.org/anthology/D18-1330). In *Proceedings of EMNLP 2018*. [[BibTeX](https://aclanthology.info/papers/D18-1330/d18-1330.bib)]

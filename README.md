# FieldedSDM
**UPDATE:** FSDM was included in Galago 3.9 release [under contrib module](https://sourceforge.net/p/lemur/galago/ci/default/tree/contrib/src/main/java/org/lemurproject/galago/contrib/retrieval/traversal/FieldedSequentialDependenceTraversal.java).

Fielded Sequential Dependence Model is a retrieval model for effective search of structured documents. It is a generalization of  [Sequential Dependence Model (SDM)](http://www-dev.ccs.neu.edu/home/yzsun/classes/2014Spring_CS7280/Papers/Probabilistic_Models/A%20Markov%20Random%20Field%20Model%20for%20Term%20Dependencies.pdf) by Metzler and Croft, and [Mixture of Language Models (MLM)](http://www.cs.cmu.edu/~callan/Papers/sigir03-pto.pdf) by Ogilvie and Callan.

All experiments were performed on a [test collection for entity search in DBpedia](http://krisztianbalog.com/resources/sigir-2013-dbpedia/) using [Galago](http://sourceforge.net/p/lemur/galago/ci/default/tree/).
The model is implemented in Java as a Galago traversal. Yet, we provide an implementation of MLM. You can find both implementations in `galago` directory.
Please see [documentation](http://sourceforge.net/p/lemur/wiki/Galago%20Traversals/#implementing-your-own-traversal)
to understand how to configure Galago to use them. Or [ask the authors](mailto:nikita.zhiltsov@gmail.com) if you experience some issues.

We provide retrieval results of our models and baselines we used in the paper in `runs` directory.

Please see our [presentation](https://github.com/teanalab/FieldedSDM/blob/master/fsdm-presentation.pdf) and [paper](http://dl.acm.org/authorize.cfm?key=N90326) if you want to understand how models works in more detail.

## Authors
- [Nikita Zhiltsov](https://github.com/nzhiltsov) *Kazan Federal University*, [*Textocat*](http://textocat.com/)
- [Alexander Kotov](http://www.cs.wayne.edu/kotov/) *Wayne State University*
- [Fedor Nikolaev](https://github.com/fedorn) *Wayne State University*

## Acknowledgment
This project was partially funded by the [Kazan Federal University](http://kpfu.ru/eng).

## License
Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0

## Citation
Please cite the following paper if you use our code or ideas in your work:

N. Zhiltsov, A. Kotov, and F. Nikolaev. *Fielded Sequential Dependence Model for Ad-Hoc Entity Retrieval in the Web of Data*  (ACM SIGIR, 2015).

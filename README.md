# Multilingual Knowledge Graph Embeddings for Cross-lingual Knowledge Alignment

This repository includes the code of MTransE var4 (see paper), links to the data sets, and pretrained models.

A more recent tensorflow implementation is available at this repository: https://github.com/muhaochen/MTransE-tf , which takes in entity-level seed alignment.
## Install
Make sure your local environment has the following installed:

    Python >= 2.7.6
    pip
    
Install the dependents using:

    ./install.sh

## Run the experiments
Please first download the data sets:

http://yellowstone.cs.ucla.edu/~muhao/MTransE/data.zip

and pretrained models

http://yellowstone.cs.ucla.edu/~muhao/MTransE/models.zip

Unpack these two folders to the local clone of the repository.

To run the experiments on WK3l (wikipedia graphs), use:

    ./run_wk3l.sh
To run the experiments on CN3l (conceptNet), use:

    ./run_cn3l.sh
You may also train your own models on these two data sets using:

    ./train_models.sh

## Reference
Please refer to our paper. 
Muhao Chen, Yingtao Tian, Mohan Yang, Carlo Zaniolo. Multilingual Knowledge Graph Embeddings for Cross-lingual Knowledge Alignment. In *Proceedings of the 26th International Joint Conference on Artificial Intelligence (IJCAI)*, 2017

    @inproceedings{chen2017multigraph,
        title={Multilingual Knowledge Graph Embeddings for Cross-lingual Knowledge Alignment},
        author={Chen, Muhao and Tian, Yingtao and Yang, Mohan and Zaniolo, Carlo},
        booktitle={Proceedings of the 26th International Joint Conference on Artificial Intelligence (IJCAI)},
        year={2017}
    }

## Links
The following links point to some recent follow-ups of this work.

Sun, Zequn, Wei Hu, and Chengkai Li. [Cross-lingual entity alignment via joint attribute-preserving embedding.](https://iswc2017.semanticweb.org/wp-content/uploads/papers/MainProceedings/188.pdf) International Semantic Web Conference. Springer, Cham, 2017.  
Zhu, Hao, et al. [Iterative entity alignment via joint knowledge embeddings.](https://www.researchgate.net/profile/Hao_Zhu31/publication/318830326_Iterative_Entity_Alignment_via_Joint_Knowledge_Embeddings/links/598afe10aca27243585a115e/Iterative-Entity-Alignment-via-Joint-Knowledge-Embeddings.pdf), IJCAI, 2017.  
Yeo, Jinyoung, et al. [Machine-Translated Knowledge Transfer for Commonsense Causal Reasoning.](https://pdfs.semanticscholar.org/d065/0236b8cd7a693691eb479614d31a394b0c9b.pdf) AAAI. 2018.  
Chen, Muhao, et al. [Co-training Embeddings of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment.](http://www.ijcai.org/proceedings/2018/0556.pdf), IJCAI, 2018.  
Sun, Zequn, et al. [Bootstrapping Entity Alignment with Knowledge Graph Embedding.](https://www.ijcai.org/proceedings/2018/0611.pdf) IJCAI. 2018.  
Otani, Naoki, et al. Cross-lingual Knowledge Projection Using Machine Translation and Target-side Knowledge Base Completion. COLING, 2018.
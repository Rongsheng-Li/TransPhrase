# TransPhrase
Since there are few Chinese phrase-level evaluation tasks, we have constructed an evaluation data set called a synonymous-unrelated phrase task (SU). For details on the construction and use of this data set, see our paper. If your work uses our data set, please cite our paper.
@article{LI2020114387,
title = "TransPhrase: A New Method for generating phrase embedding from word embedding in Chinese",
journal = "Expert Systems with Applications",
pages = "114387",
year = "2020",
issn = "0957-4174",
doi = "https://doi.org/10.1016/j.eswa.2020.114387",
url = "http://www.sciencedirect.com/science/article/pii/S0957417420310605",
author = "Rongsheng Li and Shaobin Huang and Xiangke Mao and Jie He and Linshan Shen",
keywords = "phrase embedding, word embedding, composition method, neural network",
abstract = "Currently, there are two main methods of learning phrase embedding: the distribution method and the composition method. The distribution method treats a phrase as an entirety and learns phrase embedding based on the context of the phrase. Its disadvantage is that it completely ignores the semantics of the component words of the phrase and the data sparseness problem. The composition method calculates the phrase embedding from the embedding of component words. The existing composition methods fail to represent the semantics of phrases well. Because of the above problems, we take Chinese, for example, and propose a new composition method to generate phrase embedding from the component word embedding, named TransPhrase. It is a neural network that can use LSTM to learn the order information of component words, use the attention mechanism to learn the important information of component words, and use a fully connected network to learn the semantic information of component words, and finally predict phrase embedding. It can solve the data sparseness problem and properly and fully represent the semantics of phrases. Our evaluation of three Chinese phrase-level semantic tasks shows that the comprehensive performance of TransPhrase's phrase representation is better than the composition method, the distribution method, and the pre-trained language model."
}

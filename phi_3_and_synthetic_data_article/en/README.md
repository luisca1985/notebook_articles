# Synthetic Data: Behind the Impressive Performance of Phi-3

## Abstract
The recent article "Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone" presents significant findings on the use of synthetic data in training language models. The Phi-3-mini model, with a fraction of the size of models like GPT-3.5, achieves comparable performance thanks to innovations in the training dataset. These results challenge the preconceived notion about synthetic data and its impact on model performance.

This article explores the implications of these findings, from reducing model size to the impact synthetic data could have on the future development of the language model industry. The results of Phi-3 open up new possibilities for creating more efficient and accessible models, and highlight the importance of training data quality in advancing artificial intelligence.

## Introduction

The recent article "Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone" presents surprising and encouraging findings in the field of language models. Researchers managed to create a highly capable language model, called Phi-3-mini, that rivals much larger models like GPT-3.5, but with the advantage of being small enough to run locally on a mobile phone. This achievement is entirely attributed to innovations in the dataset used for training, which consists of an expanded version of the one used for the previous model, Phi-2, composed of heavily filtered web data and synthetic data.

## Reducing model size and improving performance

One of the most notable aspects of the study is the ability to significantly reduce the size of the model without compromising its performance. Phi-3-mini, with only 3.8 billion parameters, achieves results comparable to much larger models like GPT-3.5, which has around 175 billion parameters. This drastic reduction in model size is achieved through the use of optimized training data, specifically highly filtered web data and synthetic data generated by larger language models.

The results are impressive. Phi-3-mini achieves 69% on the MMLU test and 8.38 on MT-bench, metrics that measure the model's reasoning ability and overall performance. These scores are comparable to those obtained by significantly larger models, such as Mixtral 8x7B and GPT-3.5, demonstrating that a small model can achieve performance similar to larger models when trained with high-quality data.

## The power of synthetic data

Traditionally, there has been some resistance to working with synthetic data in training language models, due to concerns that it could increase bias and even negatively affect performance. However, the results presented in this article challenge that notion and demonstrate that synthetic data, when properly generated and filtered, can significantly improve the performance of a small model, allowing it to achieve results comparable to larger models.

One of the advantages of using synthetic data is that it is easier to collect and variations can be generated to cover a wide range of scenarios. This allows models to be trained with diverse and representative data, which in turn improves their generalization and robustness.

## Hypotheses about the improvements

To better understand how synthetic data contributes to improving the performance of small models, several hypotheses can be proposed based on established concepts in machine learning and information theory.

One possible explanation is that a giant language model can generate synthetic data that captures the most relevant outputs and provides the greatest amount of differentiated information. By training a smaller model with this optimized data, performance equivalent to the larger model can be achieved. This concept is not entirely new and has been used in techniques such as model distillation, where a smaller model is trained to imitate the behavior of a larger model.

Another hypothesis is based on the principle of dimensionality reduction, similar to techniques such as Principal Component Analysis (PCA). Although PCA and other related techniques are not directly applicable to language models due to their nonlinear and high-dimensional nature, the underlying principles can be applied through the generation of synthetic data. By generating data that captures the most relevant and distinctive features, an effect similar to dimensionality reduction can be achieved, allowing a smaller model to learn more efficiently.

Moreover, from the perspective of information theory, it is known that richer and more structured information can lead to better learning results. Synthetic data generated by a large model can provide denser and more meaningful information, allowing a smaller model to learn more effectively.

In this way, it can be argued that synthetic data generated by large models acts as a form of "positive overfitting," allowing a smaller model to replicate the behavior of the large model using fewer parameters. By training the small model with the most probable and representative data from the large model, similar performance can be achieved with a fraction of the size.

## The future of the language model industry

The findings presented in the Phi-3 article make us think of a possible paradigm shift in the language model industry. Instead of focusing solely on creating ever larger and more powerful models, we are likely to see a two-pronged approach.

On the one hand, leading technology companies will continue to develop giant models, which have already surpassed trillions of parameters. These models will be trained with massive amounts of data and will have increasingly impressive capabilities. However, due to their enormous size and computational requirements, these giant models will be primarily operated by a small number of companies with sufficient resources to do so.

On the other hand, it is expected that these giant models will be increasingly used to generate high-quality synthetic data, which in turn will be used to train smaller and more efficient models. These small models, like Phi-3-mini, will have performance comparable to giant models, but will be much more accessible and able to run on local devices.

In this sense, the industry will be divided into two main fronts. The first will focus on creating the best possible giant models, with the goal of minimizing bias, maximizing performance and diversity, and offering the best features. However, these models will not be directly used to provide services to end users. Instead, their main purpose will be to generate the highest quality synthetic data to feed smaller models.

The second front of the industry will be dedicated to optimizing small models and generating the best possible synthetic data. The goal will be to create increasingly smaller and more efficient models that maintain the performance of large models. Companies will strive to find the optimal balance between model size and the quality of synthetic data used for training.

## Application in ICL and RAG

Although the results of Phi-3 are exciting, the reality is that most companies do not have the capacity to develop their own language models, not even the smallest ones. Instead, many companies are adopting approaches such as In-Context Learning (ICL) and Retrieval Augmented Generation (RAG) to leverage existing language models.

In ICL and RAG, company data or texts are used to create embeddings that are stored as vectors. Then, a retrieval of the most relevant vectors is performed to construct a context window or prompt that is provided to a pre-trained language model. The model generates responses based on the information provided in the context window.

However, just as in training small models, the quality of the data used in ICL is crucial. Much of the data generated by companies can be irrelevant, redundant, or not very diverse, which limits the effectiveness of the model.

The findings of the Phi-3 article can shed light on how to improve ICL and RAG processes. One possibility is to generate synthetic data as a source for RAG, using a language model to create data that has the same desirable qualities used to train high-performance small models. This could include generating relevant metadata, applying filters to select the most meaningful information, and obtaining greater diversity of information through re-ranking techniques.

By generating high-quality synthetic data to feed ICL and RAG models, companies can significantly improve the effectiveness of these approaches. The information generated by a language model could provide added value that is not easily found in the original manually created documentation.

## Conclusion

The results presented in the article "Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone" have significant implications for the language model industry and machine learning in general. They demonstrate that the generation of high-quality synthetic data can enable the creation of small models with performance comparable to larger models, opening up new possibilities for efficiency and accessibility.

These findings also challenge the preconceived notion that synthetic data is inherently problematic and should be avoided. Instead, they suggest that when properly generated and filtered, synthetic data can be a valuable resource for improving model performance, regardless of size.

For companies that do not have the capacity to develop their own language models, these findings offer a valuable lesson. Instead of relying solely on models provided by third parties, companies can and should invest in generating high-quality synthetic data to feed their ICL and RAG processes. By doing so, they can achieve superior performance and more relevant results, even with smaller models.

Ultimately, the results of the Phi-3 article remind us that the future of artificial intelligence is not just about creating ever larger and more powerful models. It's also about being smart and strategic about the data we use to train and feed these models. By embracing the potential of synthetic data and applying the principles of filtering, diversity, and relevance at all levels of the machine learning process, we can unlock new levels of efficiency and performance.

## References

- [Abdin, M., Jacobs, S. A., Awan, A. A., Aneja, J., Awadallah, A., Awadalla, H., ... Zhou, X. (2024). *Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone*. arXiv preprint arXiv:2404.14219.](https://arxiv.org/abs/2404.14219)

- [Wang, Y., Kordi, Y., Mishra, S., Liu, A., Smith, N. A., Khashabi, D., & Hajishirzi, H. (2023). *Self-Instruct: Aligning Language Models with Self-Generated Instructions*. arXiv preprint arXiv:2212.10560.](https://arxiv.org/abs/2212.10560)
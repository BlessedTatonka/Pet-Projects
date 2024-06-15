# bge-m3 model for english and russian

This is a tokenizer shrinked version of [BAAI/bge-m3](https://huggingface.co/BAAI/bge-m3).

The current model has only English and Russian tokens left in the vocabulary.
Thus, the vocabulary is 21% of the original, and number of parameters in the whole model is 63.3% of the original, without any loss in the quality of English and Russian embeddings.
<!--- Describe your model here -->

## Specs 

Other bge-m3 models are also shrinked.

| Model name                |
|---------------------------|
| [bge-m3-retromae_en_ru](https://huggingface.co/TatonkaHF/bge-m3-retromae_en_ru)     |
| [bge-m3-unsupervised_en_ru](https://huggingface.co/TatonkaHF/bge-m3-unsupervised_en_ru) |
| [bge-m3_en_ru](https://huggingface.co/TatonkaHF/bge-m3_en_ru)              |

## Reference:

Jianlv Chen, Shitao Xiao, Peitian Zhang, Kun Luo, Defu Lian, Zheng Liu. [BGE M3-Embedding: Multi-Lingual, Multi-Functionality, Multi-Granularity Text Embeddings Through Self-Knowledge Distillation](https://arxiv.org/abs/2402.03216).

Inspired by [LaBSE-en-ru](https://huggingface.co/cointegrated/LaBSE-en-ru) and [https://discuss.huggingface.co/t/tokenizer-shrinking-recipes/8564/1](https://discuss.huggingface.co/t/tokenizer-shrinking-recipes/8564/1).

License: [mit](https://huggingface.co/datasets/choosealicense/licenses/blob/main/markdown/mit.md)

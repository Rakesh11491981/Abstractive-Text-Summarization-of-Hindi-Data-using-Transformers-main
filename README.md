# Abstractive-Text-Summarization-of-Hindi-Data-using-Transformers-main
Abstractive-Text-Summarization-of-Hindi-Data-using-Transformers-main

Our approach utilizes a transformer encoder-decoder model to generate human-like headline summaries from Hindi news articles. The model is trained on the "Hindi Text Short Summarization Corpus" dataset, which consists of approximately 0.3 million news articles. You can access this dataset on Kaggle at https://www.kaggle.com/datasets/disisbig/hindi-text-short-summarization-corpus.

To enhance the model's performance, we employ FastText pre-trained word embeddings provided by Facebook. These embeddings are trained on Hindi Wikipedia and news articles, and you can find them at https://fasttext.cc/docs/en/crawl-vectors.html. The pre-trained embedding weights are used to initialize the vectors before being passed to the transformer encoder and decoder modules.

If you intend to train the model from scratch using the entire dataset, please ensure that you download the data and embeddings files from the mentioned links. Keep in mind that due to the large size of the data, a minimum of 16 GB RAM and a GPU with Tensor cores and a bandwidth of 300+ gb/s are required. However, for experimental purposes, you can train the model on smaller subsets of the data.

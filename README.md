# Resnet Embedding Extractor

Small and easily modifiable [notebook](https://nbviewer.jupyter.org/github/dinarior/resnet_embeddings_extractor/blob/master/extract_embeddings.ipynb) to extract embeddings from pre trained resnet50.

The notebook extract embeddings from `CIFAR100`, using a pretrained resnet50.

For the pretrained model we use https://github.com/facebookresearch/swav , thus the embeddings are learned unsupervised on imagenet. You can easily swap it for other models of your choosing.

If you do use `SWAV`, make sure you [cite](https://arxiv.org/pdf/2006.09882.pdf) them properly.

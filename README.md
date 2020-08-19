# Resnet Embedding Extractor

Small and easily modifiable notebook to extract embeddings from pre trained resnet50.

The notebook extract embeddings from `CIFAR100`, using a pretrained resnet50.

For the pretrained model we use https://github.com/facebookresearch/swav , thus the embeddings are learned unsupervised. You can easily swap it for other models of your choosing.

If you do use `SWAV`, make sure you [cite](https://arxiv.org/pdf/2006.09882.pdf) them properly.

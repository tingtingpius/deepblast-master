# DeepBLAST 

DeepBLAST is a neural-network based alignment algorithm that can estimate structural alignments. And it can generate structural alignments that are nearly identical to state-of-the-art structural alignment algorithms.

# Installation

具体版本如下：
pip install deepblast
numpy
scipy
pandas
torch>=1.4
scikit-learn
numba
pytorch-lightning==1.8.5
matplotlib
pillow
biopython>=1.78,<2.0
transformers
sentencepiece
tensorboard

# Downloading pretrained models and data

预训练模型网址：(https://users.flatironinstitute.org/jmorton/public_www/deepblast-public-data/checkpoints/deepblast-l8.ckpt).

用于预训练的TM-align结构性对齐：
- [Training data](https://users.flatironinstitute.org/jmorton/public_www/deepblast-public-data/train_matched.txt)
- [Validation data](https://users.flatironinstitute.org/jmorton/public_www/deepblast-public-data/valid.txt)
- [Testing data](https://users.flatironinstitute.org/jmorton/public_www/deepblast-public-data/test.txt)


可以从(http://prodata.swmed.edu/malisam/) 和(http://prodata.swmed.edu/malidup/) 中下载更多数据集


# transformer

From-scratch PyTorch implementation of transformer from "Attention is All You Need."

## Requirements

Python 3.11

A GPU is recommended for training.

## Install

```
python3.11 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Train

Place training data in `data/`. The text in all files in this directory will be used for training.

To train, run

```
python train.py
```

By default, this will save the trained model at `models/model.pt`.

For a list of all options, run

```
python train.py --help
```

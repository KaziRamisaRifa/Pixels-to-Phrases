# Pixels to Phrases
Encoder CNN is used with a language‑generating decoder RNN to generate a fitting natural‑language caption from the image. SpaCy tokenization is utilized for splitting strings into individual words and mapped to corresponding index values.

## Requirements: 
- PyTorch
- Torchvision
- Spacy
- Tensorboard
- PIL
- TQDM

## Training
To train on the Flickr8k dataset, you will need to download [Flickr8k](https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb) and keep it inside the folder `data/`. The data directory tree will look like this:

```
data/
    flickr8k/
        images/
        captions.txt
```

## Pre-Train Checkpoints
- Pre-trained models are available in [checkpoint](https://drive.google.com/file/d/1gL8__Y4Pm5CQbU87N3hhTkmQU9eY8xWQ/view?usp=sharing). The checkpoint directory tree will look like this:

```
checkpoint/
    model_checkpoint.pth.tar
```

## Commands 

The pixels to Phrases pipeline is trained using
```
python train.py
```
The pixels-to-phrases pipeline is evaluated using
```
python test.py
```

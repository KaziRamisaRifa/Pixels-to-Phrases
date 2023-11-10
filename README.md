## Pixels-to-Phrases

#### Requirements: `Pytorch, Torch Vision, Spacy, Tensorboard, PIL, TQDM`

To train on Flickr8k dataset, you will need to download [Flickr8k](https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb) and keep it inside the folder `data/`. The data directory tree will look like this:

```
data/
    flickr8k/
        images/
        captions.txt
```

Pre-trained models are available in [checkpoint](https://drive.google.com/file/d/1gL8__Y4Pm5CQbU87N3hhTkmQU9eY8xWQ/view?usp=sharing). The checkpoint directory tree will look like this:

```
checkpoint/
    model_checkpoint.pth.tar
```


Pixels to Phrases pipeline is trained using
```python
python python train.py
```

Pixels to Phrases pipeline is evaluated using
```python
python python test.py
```


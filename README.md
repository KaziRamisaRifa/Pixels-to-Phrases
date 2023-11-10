## Pixels-to-Phrases

#### Requirements: `Pytorch, Torch Vision, Spacy, Tensorboard, PIL, TQDM`

python -m spacy download en
Download the dataset: [link](https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb)
Downloaded it into ./data

- Set images folder, captions.txt inside a folder Flickr8k.
- train.py: For training the CNN model.
- model.py: creating the encoderCNN, decoderRNN model and combine them together into one model. 
- get_loader.py: Loading the data, creating vocabulary for training, testing and evluation.
- utils.py: Load model, save model, printing few test cases to evaluate the model.


#### Usage: For Training Start running the training script with `python train.py` 

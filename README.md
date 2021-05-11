# CaptionGenerationAI
CS419 Caption Generation ML Model

# Contents
Model/
1) ExtractFeatures --- Code to use the pre-trained VGG16 model to extract the features from the Flickr8k image dataset.
2) TextPreprocessing --- Code to preprocess the descriptions and store the map of images to captions in 'descriptions.txt'.
3) Model ---  Contains the Model architecture to train and store the best model obtained in 20 epochs.
4) EvaluateModel --- Code to evaluate the BLEU score on the Flickr8k test dataset.
5) CaptionGeneration --- Code to generate the captions of a given image.

Misc/
1) 'descriptions.txt' --- Contains the image to description map.
2) tokenizer.pkl --- Contains the encoded token values of the vocabulary obtained from the Flickr8k training dataset.

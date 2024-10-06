# NLP_2024_Final_Project
NLP 2024 Final Project: Scientific Sentence Extraction with a Small LLM (OpenELM Models)

## Extraction Methodology from an Abstract
EX:
  The reliability of self-labeled data is an important issue when the data are regarded as ground-truth for training and testing learning-based models. 
  This paper addresses the issue of false-alarm hashtags in the self-labeled data for irony detection. 
  `We analyze the ambiguity of hashtag usages and propose a novel neural network-based model, which incorporates linguistic information from different aspects, to disambiguate the usage of three hashtags that are widely used to collect the training data for irony detection. 
  Furthermore, we apply our model to prune the self-labeled training data. `
  Experimental results show that the irony detection model trained on the less but cleaner training instances outperforms the models trained on all data.

## Strategies
  - Hyper-parameter tuning
  - Training the model
  - Prompting
  - Preprocessing
  - Post-processing

## Restrictions
  - Your system can be performed on the free version of Google Colab
  - The backbone model should be chosen from the Apple OpenELM family
  - No access to outside resources during the inference stage

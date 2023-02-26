# Abstractive Text Summarization

This repository contains code and resources for Abstractive Text Summarization using Deep Learning models. The goal of this project is to summarize large amounts of textual data into a concise, easy-to-read summary that captures the essence of the original text.

## Introduction

The basic idea behind abstractive text summarization is to be able to extract a short subset of the most important information from a large set and present it in a human-readable format. As the amount of textual data on the internet grows, automatic text summarization methods have the potential to be very useful because more useful information can be read in a shorter amount of time. This repository contains a PyTorch implementation of an abstractive text summarization model.

## Dataset

The Amazon Reviews Dataset is used for training and evaluation. This dataset contains product reviews and ratings from Amazon, along with metadata such as product category and reviewer information. The dataset can be downloaded from the following link: https://s3.amazonaws.com/amazon-reviews-pds/readme.html

## Model Architecture

The model architecture used for this project is a Seq2Seq model with an attention mechanism. The encoder is a bidirectional LSTM and the decoder is a unidirectional LSTM with attention.

## Getting Started

To get started, clone this repository:

```bash
git clone https://github.com/username/Abstractive-Text-Summarization.git
```

```bash
cd Abstractive-Text-Summarization
```
Next, install the required packages:

```bash
pip install -r requirements.txt
```

## Training

To train the model, run the following command:

``` bash
python train.py
```

By default, the model will train for 100 epochs. To change this, modify the num_epochs parameter in config.py.

## Inference

To generate summaries for new text, run the following command:

``` bash
python infer.py --text "Insert text to be summarized here."
```

## Results

The performance of the model is evaluated using ROUGE metrics. The following table shows the ROUGE scores for the model on the test set:

|ROUGE-1 | ROUGE-2	| ROUGE-L
|-----|------|---
|0.45 | 0.28 | 0.41

## Contributing

Contributions are welcome! Please create an issue or submit a pull request if you would like to contribute to this project.


## That's all folks!
Feel free to mail me for any doubts/query 
:email: abhi.yalamaddi@gmail.com


Feel free to **file a new issue** with a respective title and description on the the [Abstractive Text Summarization](https://github.com/hipstermartin/Abstractive-Text-Summarization/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! 

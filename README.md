# Machine Learning Projects Repository

This repository contains three machine learning projects developed for different purposes.

## Second Hand Car Price Prediction using Linear Regression

This project focuses on predicting the current price of second-hand cars based on various parameters. The model takes eight input features: **years**, **km**, **rating**, **condition**, **economy**, **top speed**, **horsepower (hp)**, and **torque**. Using **linear regression** techniques, it estimates the **price** of a car, aiding buyers and sellers in making informed decisions.

## Malaria Detection using Convolutional Neural Network

This project implements **Convolutional Neural Networks (CNNs)** for the detection of malaria in **blood cell images**. Trained on a dataset comprising nearly **24,000 images** labeled as **'parasitized'** or **'unparasitized'**, the CNN analyzes cell images, extracting features through **convolutional**, **normalization**, and **pooling layers**. The extracted features are then flattened and fed into **dense layers** for **classification**, ultimately determining whether a cell is parasitized or not.

## Next Word Predictor using Bidirectional LSTM

This project develops a next word prediction model using a **news dataset**. By employing **Bidirectional Long Short-Term Memory (LSTM)** layers, the model predicts the next word in a sequence of words provided as input. This involves **tokenizing** the text data, mapping tokens to **indices**, and using these indices to train the **LSTM model**. The aim is to accurately predict subsequent words in a given text context.

## Lip Reader using Convolutional Neural Network and LSTM

This project develops a **lip-reading** model that predicts **words**, **letters**, **numbers**, or entire **sentences** spoken in a video. The preprocessing steps include extracting frames from the video at a consistent rate, cropping the **mouth region**, and normalizing **pixel values** to ensure consistent input. The model architecture integrates **CNN layers** for extracting **spatial features** from the frames, **LSTM layers** for capturing **temporal dependencies** across the sequence of frames, and **dense layers** for the final **classification** of the spoken content. This combination of techniques enables the model to analyze both visual and temporal aspects of the video effectively and make accurate predictions.

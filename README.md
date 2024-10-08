CFD ML Research Project: Predicting Shallow Water Perturbations

Overview

This project focuses on using a Convolutional Autoencoder with Long Short-Term Memory (LSTM) networks in the latent space to predict perturbations in shallow water simulations. By leveraging advanced machine learning techniques, we aim to enhance the understanding and forecasting of fluid dynamics in shallow water environments.

Table of Contents

	•	Introduction
	•	Project Structure
	•	Data Generation
	•	Model Architecture
	•	Installation
	•	Usage
	•	Results
	•	Contributing
	•	License

Introduction

The goal of this research project is to develop a predictive model for shallow water perturbations using LSTM networks. The model is designed to operate in a latent space derived from simulations of shallow water flows, enabling more efficient and accurate predictions of dynamic changes.


Data Generation

The dataset for this project was created by simulating shallow water flows using Computational Fluid Dynamics (CFD) techniques. The generated data consists of various perturbations that the LSTM model will learn to predict.

Model Architecture

The CAE-LSTM model is implemented in the shallow_code.py file. Key features of the architecture include:

	•	Input Layer: Accepts input data from the latent space after encoding.
	•	LSTM Layers: Stacked LSTM layers to capture temporal dependencies in the data.
	•	Output Layer: Produces predictions for shallow water perturbations and feeds it to the decoder of the CAE.
 



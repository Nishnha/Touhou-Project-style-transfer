# Touhou-Project-style-transfer
A Deep LSTM variational autoencoder trained on 100+ hours of Touhou Project music.... don't ask why.

## Getting started

## Windows:
1. Clone this project in a folder and navigate to it with a terminal.
2. Install the latest python 3 (with chocolatey, `choco install python`).
3. Open a terminal to install virtualenv `pip install virtualenv` and create an environment `virtualenv env`.
4. Activate the environment `source env\Scripts\activate` and install the project requirements `pip install -r requirements.txt`.

## Training data
This project was trained on over 100+ hours of Touhou Project music. The music was converted to 16bit WAV and fed the discrete fourier transform into the the variable autoencoder. Our training data is available in `/data`.

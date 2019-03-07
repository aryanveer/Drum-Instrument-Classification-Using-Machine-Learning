# Drum Instrument Classification Using Machine Learning

1. The main focus of this project is on classification of various Drum sub instruments: Bass Drum, Snare Drum, Toms and Cymbal. The initial input is the audio recordings of the various sub parts of the Drum Kit in WAV file format. 

2. The audio recordings are self-prepared by recording instruments using proper recording equipment in a soundproofed room so as to minimize noise interference. Feature Extraction is then performed on these audio recordings and various features are extracted and are recorded in a tabular format, having rows for each entry and columns for various features. 

3. One of the columns is the Class of the instrument to which it belongs. It is simply an integer mapped to an instrument (making the use of Label Encoder).

**Data Collection**

The initial dataset consists of self-recorded audio files in WAV format. The audio recordings then are parsed and converted into a list and various features are extracted from the same. Individual samples of drum instruments were recorded using a condenser microphone, an audio interface and Logic Pro X (Digital Audio Workstation).


**Feature Extraction**

The Wav audio files have a sampling rate of 22.05 KHz, that means in one second of time there are 22050 samples in an audio list created, similarly for a duration of 2 seconds there will be a total of 44100 samples in an audio list parsed. This means that we have 160 various parsed audio lists, each of which has 44100 numbers in them. The list of each audio is then used to extract the various possible features from them, which includes: 
1. Zero Crossing Rates
2. Spectral Centroid 
3. RMS Energies

**Classification Techniques**

We worked using various classifiers including K Nearest Neighbors, Random Forests and Naive Bayes. Further tuning of the hyper parameters was done accordingly so as to increase the accuracy score.

<img src="https://github.com/aryanveer/Drum-Instrument-Classification-Using-Machine-Learning/blob/master/output.png?raw=true"
     style="float: left; margin-right: 10px;" />
     


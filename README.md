# AI-Music
## Acknowledgments
The Maestro dataset's developers and the Google Magenta team's work are expanded upon by the AI-Music-Generator project.  This project would not have been possible without their efforts in creating and curating the dataset.
## Project Overview:
With the use of  LSTM-based neural network to learn musical patterns from a collection of MIDI files and generate new sequences in the style of classical piano music.
Key Concepts:
- MIDI Parsing with music21
- Sequence generation for time series (notes/chords)
- Multi-layer LSTM model with dropout regularization
- Generation of new music and conversion to playable .mid files

## Quick Access
Open in Google Colab - https://colab.research.google.com/drive/1k5aZEuG50VDdsuT33zfebFFIxWtUozCV?usp=sharing

## Model Architecture
- 3 stacked LSTM layers (512 units each)
- Dropout (0.3) for regularization]
- Dense layer to map to output vocabulary
- Softmax activation to predict next note/chord

## What is MIDI?
MIDI stands for Musical Instrument Digital Interface, and is the code computers use to read and write music. You can play MIDI files with many applications. 

![AABA_L6_10](https://github.com/user-attachments/assets/e7b19cac-5828-46fd-ab6b-e0fe4fe794b9)

The written-out music looks much more complicated than what the fingers actually do - isn't that the trouble with written-out music! Actually written-out music helps us to train our model, it has two components note and chord.

## Usage
To use this project, follow these steps:

- Open the project notebook in Google Colab.
- Follow the instructions provided in the notebook to configure any necessary settings or parameters.
- Run the code cells in sequential order to execute the project.
- Examine the output and listen to the music.


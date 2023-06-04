# BrainHack-TIL-AI-2023

BrainHack TIL-23 Hackathon Challenge Description:

This repository contains the project files for the Advanced OD & ReID qualifier and Advanced Automatic Speech Recognition qualifier:
1. [ASR-NLP](https://github.com/J0JIng/BrainHack-TIL-AI-2023/tree/main/ASR-NLP)
2. [Computer_vision](https://github.com/J0JIng/BrainHack-TIL-AI-2023/tree/main/Computer_vision)

---

### Challenge Synopsis

You are tasked with security management of a high level conference between foreign delegates held at
“Crown Renaissance Resort”. 

You have received reports that a terrorist organisation is planning to kidnap Mr.
Dastan, the President of United AI, who chairs the conference. 

The intelligence team has also managed to
retrieve pictures of the kidnapper, also known as “White Stinger”.

Your task is to prepare for a search-and-rescue mission in the event that Mr. Dastan is kidnapped. To
achieve this, two models are needed:

● Computer vision models that are able to detect and identify (1) Mr. Dastan, and (2) White Stinger.

● Automatic speech recognition model to interpret your intelligence team’s communications about the
whereabouts of Mr. Dastan

---

## OD & ReID

xxxxxxxx



## Automatic Speech Recognition

Building the model with adaption of deepspeech2 , raw audio data from .wav file will be transformed into a melspectrogram.
The melspectrograms are then inputted into CNN and RNN layers to generate predictions about the words that are spoken in the audio data. 
The number of classes is 28 ( 26 alphabets in caps + SPACE + blanks ). Text transformed by encoding the characters and decoding the integers corresponding to the characters. Finally, GreedyDecoder decodes the logits into characters to form the final transciption. 






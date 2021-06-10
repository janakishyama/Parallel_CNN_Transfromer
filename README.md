# Parallel_CNN_Transfromer

## Audio - Emotion classification - RAVDESS

Project Details: Audio - Emotion classification

Language : Python

DL Library: Pytorch - GPU

Dataset : https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio

Datafolder : working_directory/archive/Actor_No/filename.wav

Model Save: working_directory/models

Data citation : "The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)" by Livingstone & Russo is licensed under CC BY-NA-SC 4.0.


                        
### Implementation Details:
___________________________________________________________

Step-1: Descriptive Analysis

Step-2: Base CNN model

Step-3: Hybrid CNN-Transformer model

Step-5: Emotion Classification for Strong intensity

Step-6: Emotion Classification for Normal intensity


Labels are extracted from loaded audio files and save it as a CSV file - data.csv

Also audio intensities - Strong and Normal extracted and saved in two seperate csv file for deep learning implementation

Strong Intensity : data_strong.csv

Normal Intensity : data_normal.csv

List of complete papers, blogs, git repositories refered for implementation and model design is listed in this document.
                        
## Data Description
____________________________________________________________________________
                        
This portion of the RAVDESS contains 1440 files: 60 trials per actor x 24 actors = 1440. The RAVDESS contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech emotions includes calm, happy, sad, angry, fearful, surprise, and disgust expressions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.

File naming convention

Each of the 1440 files has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 03-01-06-01-02-01-12.wav). These identifiers define the stimulus characteristics:

Filename identifiers

Modality (01 = full-AV, 02 = video-only, 03 = audio-only).

Vocal channel (01 = speech, 02 = song).

Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).

Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.

Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").

Repetition (01 = 1st repetition, 02 = 2nd repetition).

Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).



## References 
_____________________________________________________________________________________

https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7

Dataset : https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio

https://medium.com/swlh/can-we-make-machines-understand-human-emotions-69d5d9f6ea3c

https://link.springer.com/article/10.1007/s12559-019-09667-7

https://towardsdatascience.com/using-cnns-and-rnns-for-music-genre-recognition-2435fb2ed6af

https://github.com/IliaZenkov/transformer-cnn-emotion-recognition/blob/main/notebooks/Parallel_is_All_You_Want.ipynb

https://towardsdatascience.com/deep-learning-on-dataframes-with-pytorch-66b21be54ef6

https://adventuresinmachinelearning.com/convolutional-neural-networks-tutorial-in-pytorch/

https://towardsdatascience.com/pytorch-layer-dimensions-what-sizes-should-they-be-and-why-4265a41e01fd

https://www.assemblyai.com/blog/end-to-end-speech-recognition-pytorch

http://www.speech.cs.cmu.edu/15-492/slides/03_mfcc.pdf

http://pytolearn.csd.auth.gr/b4-pandas/40/moddfcols.html

https://www.analyticsvidhya.com/blog/2019/10/building-image-classification-models-cnn-pytorch/

https://pytorch.org/audio/stable/index.html

https://pytorch.org/docs/stable/index.html

https://pytorch.org/vision/stable/index.html

https://librosa.org/doc/latest/index.html

https://arxiv.org/abs/1706.03762


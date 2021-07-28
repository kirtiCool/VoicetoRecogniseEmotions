# VoicetoRecogniseEmotions

Objective:

![image](https://user-images.githubusercontent.com/87946026/127307657-7e74b6a8-7414-43aa-9c4b-5b2e779aec27.png)


Download the imports


Data Source:

![image](https://user-images.githubusercontent.com/87946026/127307605-7fd044a9-bf80-4da7-bb1e-b99d5b50ecc6.png)


Load the data
Analysis part involves:-The audio files names are 03-01-01-01-01-01-01
Using our emotions dictionary, this number is turned into an emotion, and our function checks whether this emotion is in our list of observed_emotions;
if not, it continues to the next file. It makes a call to extract_feature and stores what is returned in ‘feature’. Then, it appends the feature to x and the emotion to y.
So, the list x holds the features and y holds the emotions. We call the function train_test_split with these, the test size, and a random state value, and return that.

Calculate accuracy for train and test sets.
Accuracy formula :- 
![image](https://user-images.githubusercontent.com/87946026/127307337-1759a7f9-36d5-4dc6-91e1-ff56b3a3fe93.png)

Application:
![image](https://user-images.githubusercontent.com/87946026/127307407-f2d18605-198f-4f8b-8de8-6e42a3be01fe.png)


Conclusion:
In this study its’s an attempt to detect underlying emotions in recorded speech by analyzing the acoustic features of the audio data of recordings. It’s all about -how we can leverage machine learning to obtain the underlying emotion from speech audio data and some insights on the human expression of emotion through voice. 


Future:
![image](https://user-images.githubusercontent.com/87946026/127307467-af91762d-ade8-42ea-a879-598d079d661b.png)

Referances:
Documents:-
Librosa – https://librosa.org/librosa/tutorial.html 
MFCC - http://practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/
Data Sources:-
RAVDESS: https://zenodo.org/record/1188976#.XvbvZudS_IU
SAVEE: http://kahlan.eps.surrey.ac.uk/savee/Download.html
TESS: https://tspace.library.utoronto.ca/handle/1807/24487
Literature :-
Ittichaichareon, C. (2012). Speech recognition using MFCC. … Conference on Computer …, 135–138. https://doi.org/10.13140/RG.2.1.2598.3208



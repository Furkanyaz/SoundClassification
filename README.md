# SoundClassification
Sound classification continues to take more and more place in our lives day by day. Algorithms that classify sounds work in the background of many products we use in our daily lives. Examples of these are virtual assistants, text-to-speech applications, smart home security systems (Environmental Sound Classification). It has a wide range of uses, from Speech recognition to Classifying Song Genre(like Spotify). The more machine learning algorithms with high accuracy rates are developed in different areas, the easier our lives will be in the future.

Here, I will share with you 3 different machine learning models that I developed for a product. This product can classify 6 different cat sounds and tell you what your cat is doing even when you are not with your cat.

This study was done to distinguish cat sounds, but you can use this algorithm to classify sounds in the area you want. Here's what you need to do: First of all, you should create a sound library for the subject you are working on. When creating your sound library, make sure that the length of the sounds does not exceed 4 seconds. This is important for your model to perform well. I can recommend Audacity to cut your sounds into small pieces. (You can download it here https://www.audacityteam.org/download/) While breaking the sounds into small parts, listen to each sound one by one and make sure you have enough time window variety. After creating your sound library, you need to create an excel file and enter the extensions (path), class and class labels of the sounds. Thus, you will have taken the first step for classification. After this point, we need to convert the sounds into audio, that is, obtain the electronic representations of the sound and reveal the features of these reprasantations. I used librosa to get the electronic representations of the sound and MFCC (Mel-Frequency Cepstral Coefficients) to extract the features of the audios. Of all the methods I've tried for the feature extraciton, MFCC has given the best results by far. Now you have a matrix of all sounds and a class that matrix belongs to. The last thing to do from here is to set up the model. 
The models I use are:

- CNN with 99% accuracy
- ANN with 98% accuracy
- CatBoost with 96% accuracy
 
You can find the details in the codes above.

If you have anything to ask, you can reach me here (ffurkanyaz@gmail.com)

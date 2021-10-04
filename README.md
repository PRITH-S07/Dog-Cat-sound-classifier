# Dog-Cat-sound-classifier

The link to the dataset used here is: <br>
https://drive.google.com/drive/folders/1B0rT7vSXAHTOjtail5sKbGd8YGnIopYo?usp=sharing<br>
<p>
Here, I have used the WavFileHelper() function to give us information about the number of channels, sample rate and bit depth of the audio files present.<br>Then,
I have used the librosa library to extract features from the audio which generates an mfcc from time series audio data.<br>Then, the data and labels are converted into numpy arrays
and the labels are encoded. This follows a 20% split in the data.<br>Then, a CNN has been trained to deal with the extracted features and the respective output.
<br>After training, it is seen that the best performing model has a 100% training accuracy and a 91.07% test accuracy.<br>
A few examples of the predicted outputs are included in my code as well.
</p>

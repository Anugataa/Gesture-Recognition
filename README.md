# Gesture-Recognition
A home electronics company which manufactures state of the art smart televisions wants us to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

We are going to build a 3D Conv model that will be able to predict the 5 gestures correctly. We would also be performing a few experiments on models with different augmentation, number of frames, normalization, batch size, drop out etc. We would also see models with Conv2D+LSTM and transfer learning techniques.

Each gesture corresponds to a specific command:

Gesture		Meaning
Thumbs Up		- Increase the volume.
Thumbs Down	-	Decrease the volume.
Left Swipe	-	'Jump' backwards 10 seconds.
Right Swipe	- 'Jump' forward 10 seconds.
Stop	- Pause the movie.

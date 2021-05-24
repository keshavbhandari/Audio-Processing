# Audio Processing Projects

 1. **Pitch Detection with Spice** - This example project detects pitch of an audio based melody and then transcribes it into piano midi format.
 2. **Sound Classification with YAMNet** - Loads prebuilt Tensorflow YAMNet model from Google Hub and performs inference on any short audio recording. Model output has 521 labels such as dog barking, gunshot, laughter, etc.
 3. **Transfer Learning with YAMNet** - Loads prebuilt Tensorflow YAMNet model from Google Hub for inference. Builds a new model using the YAMNet embeddings to classify cat and dog sounds. Evaluate and export the model.
 4. **Voice Command Recognition** - This example builds a basic speech recognition network that recognizes ten different words. Although real speech and audio recognition systems are much more complex, but like MNIST for images, this gives a basic understanding of the techniques involved. The model classifies a one second audio clip as "down", "go", "left", "no", "right", "stop", "up" and "yes".
 5. **Speaker Recognition** - This example demonstrates how to create a model to classify speakers from the frequency domain representation of speech recordings, obtained via Fast Fourier Transform (FFT).
	 - Prepare a dataset of speech samples from different speakers, with the speaker as label.
   	 - Add background noise to these samples to augment our data.
     - Take the FFT of these samples.
     - Train a 1D convnet to predict the correct speaker given a noisy FFT speech sample.

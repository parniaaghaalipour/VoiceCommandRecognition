# VoiceCommandRecognition

This project is a python-based application for voice command recognition. The application trains on the Google Speech Commands data set and uses Convolutional Neural Network (CNN) for recognising specific voice commands. The CNN model is designed using Keras, a high-level neural networks API, capable of running on top of TensorFlow. The goal of this project is to introduce a simple and efficient way of integrating voice command functionalities into various systems and devices.



## Voice Command Recognition Application

This application trains on the widely-used Google Speech Commands dataset, using a Convolutional Neural Network (CNN) model implemented in Keras. The project is perfect for beginners in AI and speech recognition, and can be easily integrated into a variety of projects.

### Prerequisites

Ensure you have the following installed on your PC:

- Python 3.6 or above
- Tensorflow 2.0
- Keras
- Librosa
- Matplotlib
- Sklearn 
- Numpy

You can install the prerequisites via pip:

```
pip install tensorflow keras librosa matplotlib sklearn numpy
```

### Installation 

1. Clone the repository to your local machine:

```
git clone https://github.com/yourusername/voice-command-recognition.git
```

2. Navigate to the project directory:

```
cd voice-command-recognition
```

### Dataset Preparation

The Google Speech Commands dataset can be downloaded from [here](http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz) (1.2GB).

After downloading, you can extract the dataset into the project folder and rename it to 'dataset'.

### Training the model

You can train the model with the train.py script. Run the following command:

```
python train.py
```

This will train the CNN model on the Google Speech Commands dataset.

### Testing the model

After training, you can use the test.py script to test the model with your own voice commands:

```
python test.py /path_to_your_audio_file
```

Please ensure the audio file you are testing with is in .wav format.

### Contribution

Contributions are always welcome. If you see something that could be improved, open a pull request. Issues are also welcome.

### License

This project is licensed under the MIT License. Please see the [LICENSE.md](LICENSE.md) for more details.

### Contact

If you encounter any issues, feel free to contact me via Github. 

---

Enjoy using the Voice Command Recognition Application!

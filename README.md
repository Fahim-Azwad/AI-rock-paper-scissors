# A Python AI Rock-Paper-Scissors Game 
--------------------------------------
[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/DAVFoundation/captain-n3m0/blob/master/LICENSE)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

## Project Summary
Play the infamous Rock-Paper-Scissors game with neural network trained AI.

## About The Project
The pytho project showcases a simple game bulid through AI image processing and nural network. At it's core lies an image catagorizer, which segrigates images based on hand gesture into one of rock, paper or scissors. We are going to use a pre-trained convolutional neural network called SqueezNet and utilize its outer layer. We will retrain the outer layer to recoginze our classifiactions. It scans the hand gestures first and then plays its turns based on how it has been trained. 

## How To Run The App
1. Clone the repo and cd into the project directory.
```sh
$ git clone https://github.com/Fahim-Azwad/AI-rock-paper-scissors.git
$ cd rock-paper-scissors
```

2. Install the dependencies
```sh
$ pip install -r requirements.txt
```

3. Rock, Paper, Scissors and None(For blank images where the user may not gitve any gestures) hand signs has to be transcripted init.
In this example, we gather 200 images for the "rock" gesture.
```sh
$ python3 gather_images.py rock 200
```

4. You can train the model through this command in the Terminal.
```sh
$ python3 train.py
```

5. Put the model through some image tests.
```sh
$ python3 test.py <path_to_test_image>
```

6. Start enjoying the game!
```sh
$ python3 play.py
```

## Tech Stack
* Python 3
* Visual Studio Code
* Keras
* Tensorflow
* OpenCV
* Bash Terminal

## Contributing
Fee free to add suggestions or make any pull request. Also this is a replicated project.

## License
The contents of this repository is licensed under a [MIT License](https://opensource.org/licenses/MIT)

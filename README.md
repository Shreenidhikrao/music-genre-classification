# music-genre-classification

This is a project for music genre classification. The project contains a Jupyter notebook file, `music_genre.ipynb`, and a Python script, `music_genre.py`.

## Prerequisites

Before running the project, you need to have the following libraries installed:

- `python_speech_features`
- `scipy`

You can install the libraries by running the following commands:

!pip install python_speech_features
!pip install scipy


## Usage

To use the project, follow these steps:

1. Run the cells individually from the file `music_genre.ipynb`.
2. A dumpfile `mydataset.dat` is created when we run all the cells.
3. Open the file `music_genre.py` and mention the path of the music file with `.wav` extension in the respective position.
4. Open the terminal and run `music_genre.py` file using the command `python3 music_genre.py` to get the output.

The project allows you to classify music into different genres using audio features. To classify a music file, provide the path of the file in the `music_genre.py` file and run the file. The output will be the predicted genre of the music file.


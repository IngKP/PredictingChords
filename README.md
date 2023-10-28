# PredictingChords
The documents consisted of 3 main jupyter notebook file:
1. [Annotate_chords](#annotate_chords)
2. [Matching_only](#matching_only)
3. [Train_Test](#train_test)

## [Annotate_chords](Annotate_chords.ipynb)

The file is created to `create label` for training and testing purpose. The label process is direct `from filename` where there are 3 cases of chord patterns follow by chords played, bpm of the song and the song name. the label is in the format `start(s); end(s); chord('char')`

## [Matching_only](Matching_only.ipynb)

This file is created to test the capability of `matching the data with a binary template` of each chord and determine chord play at the given moment by similarity between the data and the template. 

## [Train_Test](Train_Test.ipynb)

This file is designated to use support vector machine to help classifying chords played at any time frame given similarity matrix from `Matching_only.ipynb` 

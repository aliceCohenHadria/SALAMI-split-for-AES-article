# SALAMI-split-for-AES-article

We give here our split (train, val and test set) for the AES article of 2017, Music Structure Boundaries Estimation Using Multiple Self-Similarity Matrices as Input Depth of Convolutional Neural Networks.
SALAMI contains 1048 music tracks of various music genres (including popular, classical, jazz or world music) annotated in music structure at different temporal scales and by two different annotators.

We have at access to 732 of the audio files of SALAMI.
We split our 732 audio tracks into 400 tracks for training, 100 for validation and 232 for testing. 
The splitting has been to ensure that the same artist does not appear both in the training and testing set.

We provide three lists (`idSALAMITrain`, `idSALAMIVAL`, `idSALAMITest`) of id of SALAMI (called `SONG_ID`), defined in the `metada.csv` file of SALAMI database.




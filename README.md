## Datasets supported

a. [Bentham](http://www.transcriptorium.eu/~tsdata/)

b. [IAM](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database)

c. [Rimes](http://www.a2ialab.com/doku.php?id=rimes_database:start)

d. [Saint Gall](https://fki.tic.heia-fr.ch/databases/saint-gall-database)

e. [Washington](https://fki.tic.heia-fr.ch/databases/washington-database)

## Requirements

- Python 3.x
- OpenCV 4.x
- editdistance
- TensorFlow 2.x

## Command line arguments

- `--source`: dataset/model name (bentham, iam, rimes, saintgall, washington)
- `--arch`: network to be used (puigcerver, bluche, flor)
- `--transform`: transform dataset to the HDF5 file
- `--cv2`: visualize sample from transformed dataset
- `--kaldi_assets`: save all assets for use with kaldi
- `--image`: predict a single image with the source parameter
- `--train`: train model using the source argument
- `--test`: evaluate and predict model using the source argument
- `--norm_accentuation`: discard accentuation marks in the evaluation
- `--norm_punctuation`: discard punctuation marks in the evaluation
- `--epochs`: number of epochs
- `--batch_size`: number of the size of each batch

# STF4J Test Models

This project contains several prebuilt TensorFlow models that are used to test
the STF4J (Simplified TensorFlow for Java) project.

For STF4J testing, CIFAR-10 data and MNIST data should be downloaded and extracted
to the `cifar10_data` and `mnist_data` directories. More information about
this can be found in the README.md files in these directories.

For Higgs Boosted Trees testing, the Higgs data does not need to be downloaded
since the HiggsBoostedTreesTest class contains the data used for predictions.

Most STF4J testing utilizes the basic SavedModels in the `simple_saved_models`
directory.

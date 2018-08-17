# STF4J Test Models

This project contains several prebuilt TensorFlow models that are used to test
the STF4J (Simplified TensorFlow for Java) project.

For STF4J testing, CIFAR-10 data and MNIST data should be downloaded and extracted
to the `cifar10_data` and `mnist_data` directories. More information about
this can be found in the README.md files in these directories.

For Higgs Boosted Trees testing, the Higgs data does not need to be downloaded
since the HiggsBoostedTreesTest class contains the data used for predictions.

The `image_data` directory can be used for image predictions. If `dog.jpg` and
`cat.jpg` files are placed in this directory, they will be used by CIFAR10Test
for image predictions. If these image files are not present, the relevant tests
will be skipped.

Most STF4J testing utilizes the basic SavedModels in the `simple_saved_models`
directory.

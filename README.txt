The dataset consists of 78200 training images and 13800 test images.
58000 have been used for training and 19550 have been used for validation.
The data set is saved as a numpy zip called dataset.npz.

Use:

    dataset = np.load( "dataset.npz" )

    X_train = dataset[ "arr_0" ]
    X_test = dataset[ "arr_1" ]
    y_train = dataset[ "arr_2" ]
    y_test = dataset[ "arr_3" ]


to load the datasets.

Find the original dataset at:
https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset

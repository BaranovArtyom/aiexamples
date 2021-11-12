### Tensorflow example

Some sample codes showing the usage of Tensorflow

#### Code description

* saved_model

  The example illustrates the saving and loading of the SavedModel format model.

  * save_model.py-save a simple handwriting recognition model to ./model in the current directory
  * load_model.py-Load the model saved in save_model.py under ./model and make predictions.
  * export_logdir.py-read the model and export the logdir required by TensorBoard
  * connect_model.py-connect two Tensorflow models to form a new model and save
  * test_connect_model.py-test the new model of connect_model.py

* mnist

  Sample code for handwritten digit recognition.

  * hwdigits.py-Use linear regression model to realize handwritten digit recognition
  * cnn_mnist.py-Use convolutional neural network to realize handwritten digit recognition
  * mlp_minist.py-Use multi-layer fully connected network to realize handwritten digit recognition

* autoencoder

  The realization of the self-encoder.
  
* object_detection

  Sample code for target detection.
 

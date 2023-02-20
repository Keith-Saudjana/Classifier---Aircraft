# Classifier---Aircraft
A classifier model trained to detect and classify various aircraft models.

The classifier model is a simple 2d Convolutional neural network which utilizes transfer learning of the ResNet50 model. The method of training includes exclusively training the non-transferred model for a certain number of epochs and then training it together with some layers of the transferred model. 

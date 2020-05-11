# Neural-Style-Transfer
The 'arbitrary_style_transfer' notebook contains code that utitilizes Tensorflow Hub's magenta model code,
which has pretrained weights for the neural style transfer. The inital code shared by The TensorFlow Authors 
(found here https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/style_transfer.ipynb#scrollTo=aDyGj8DmXCJI )
did not include an implementation to run multiple transfers at once or support local image use, so I added those
functionalities. The notebook also shows many examples of the results of the neural style transfer. The style
transfer runs so fast that I thought it may be useful to make a function that can iterate through several content 
and style images at once. 

The 'results' zip contains images of the various output images of the neural style transfer.

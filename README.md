# Download the model :
  Refer app.py  (line no.32-34)
  from keras.applications.resnet50 import ResNet50
  model = ResNet50(weights='imagenet')
  model.save('model.keras')

# Create Upload folder
   This folder will store images which are given as input

# To run flask App : 
  python app.py

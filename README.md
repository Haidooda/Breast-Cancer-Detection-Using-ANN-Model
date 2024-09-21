# Breast-Cancer-Detection-Using-ANN-Model
This a Breast Cancer Detection using ANN( Artificial Neural Network Model) to classify whether it's Benign or Malignant:
• Developed artificial neural network model to classify Breast Cancer whether it's Benign or Malignant. 
• Implemented 4  Fully connected layers using Dense Layer in Neural network :
  -  Input layer with 16 neuron unit, input dimentions 30 which represents features and a relu activation Function.
  -  2 Hidden layers with 16 neurons at each one  and a relu activation function.
  -  Output layer with 1 neuron unit and  and a Sigmoid activation Function as it's binary classification model.
• Dropout 10 % of fully connected neurons in input and 2 hidden layers to prevent overfitting. 
• Compiled Model with Adam Optimizer,binary crossentropy loss function.
• Trained model with validation size 20 % and test size 10 %, number of epochs=150 and batch_size=50 which represnts number of training examples to traind in each epoche.
• Applied Early Stopping Technique to stop when the model accuaracy don't improve for 5 epochs to prevent overfitting.
# What I have come into through this project :
• Model performed Early Stopping at epoche 54  with keeping the best weights which was at epoche 49.
• ANN Model has achieved a 100 % Validation Accuracy and 95 % Testing Accuracy.  
• Model doesn't suffer from Overfitting  as Trainning Accuracy is 98.25 % and Testing Accuracy is 95 %.
# Notice: Link of dataset is inside the notebook.

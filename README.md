# Hand-geature-recognition
The process of hand gesture recognition involves capturing the movement and position of the hand and fingers using cameras .
Hand gesture recognision helps to detect the alphabet according to the symbols that we show by our hand.
After running the program ,camera of our system is switched on and if we place our hand infront of camera it captures the movement and symbol of our hand and displays the respective alphabet.
The result will be keep on changing until the movement of hand is stopped.
We used CNN(Convolutional Neural Network) as algorithm from teachable machine.
Teachable machines train the data with CNN and provides model and then model is imported into the code.
Hand gesture recognition is a field of computer science that deals with the interpretation and understanding of hand movements and postures.
 It involves using computer vision and machine learning techniques to recognize and classify different hand gestures in real-time.
Hand gesture recognition has various applications in fields such as human-computer interaction, gaming, virtual and augmented reality, robotics, and sign language recognition. 
In human-computer interaction, hand gesture recognition can provide natural way of interacting with computers.
Overall, hand gesture recognition is an exciting and rapidly evolving field that has the potential to transform the way we interact with technology and the world around us.

dataCollection.py is ued to collect the data of images of each alphabet.
data is given to teachable machines and it gave keras_model.h5 and that can be used to test the hand geatures every where

# How to run
# method-1
directly download the zip file and run the test.py then you get real time hand gesture recognition.
# method-2
put all the files in single folder (model.py,dataCollection.py, keras_model.h5, labels.txt,test.py)
then open the folder as a package and run test.py code.


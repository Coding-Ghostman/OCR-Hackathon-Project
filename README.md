# OCR-Hackathon-Project

Optical character Recognition system is a system that converts the text into machine-coded format. This helps in keeping the handwritten documents or typewritten documents in a digital form which is safer and more organized. It generally satisfies the needs for the digital preservation of the historic data, law documents, and other important text-based forms.

The project we are working on is an image classification recognition system, in which the input will be given in the form of an image which consists of handwritten or type-based text. This system will be using the CNN (Convolutional Neural Network) a type of neural network dealing with pictures (static and moving). It’s the latest form of techniques introduced to make the character recognition system more efficient, easy to process and free to use.

Our recognition system is an offline based system i.e., We will be building a model and we will integrate the model with an android app. In this app, the camera feature will take the photo of the text, the input image will be given to the model and the model will give its output. The model will classify the text through the neural nets installed in it and give the output in the form of the digital text which will be given in the text field in the app.

CNN is the most advanced and most efficient way to perform this task, cuz other methods which were used previously are good but outdated and not really efficient compared to the CNN.

The Complex part of the whole project is the training of the model which will take a lot of time, space and processing power. To counter this part, we will be using the Azure cloud services which provide GPU for rent which will solve the time and the processing power requirement. Azure services give free 1 month for the new sign ups and we will make use of this free thingy.

The last part which is left out will be the APP building. We will use Android Studio and JAVA to build this app. We will keep the UI simple and fast.

	
# DATASET
https://drive.google.com/drive/folders/1ej6_QqP7dgLZDZFjhkF87oYw-pGsHYxb?usp=sharing <br>
Download the files given in the link for the dataset files. I have distributed and organized the pictures according to classes and for alphabets each class has 4000 pictures and for digits each class has 10000 files. 
While splittling the data, we will do a 70 : 30 split for Training and testing dataset resectively.

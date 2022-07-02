MULTI-FACE RECOGNITION OF PARTIAL FACES
By
Swathi A (185002109)
Nandana S (185002065)

Abstract :
Face recognition is a method of identifying or verifying the identity of an individual using their face. In many scenarios, it is quite likely that the captured face image is not a holistic face. The solution to this problem would be a Partial Face Recognition (PFR) system, where the partial facial areas of the person could be used to extract information that could be used for recognition. This project proposes a way of dividing the facial regions into fewer unique features that can be used to identify individuals. The applications of this project include masked face recognition and attendance systems. In this project, a custom dataset containing 423 images was created and then extended using the following augmentation techniques: Rotation Range, Shear Range, Zoom Range, Horizontal Flip, Brightness Range. After augmentation, the dataset was increased to 2202 images. Various deep learning models, like VGGFace, ResNet50, AlexNet, FaceNet and a custom-made CNN model, were used to train this dataset. After analysing and fine-tuning the models to train our data, FaceNet model produced the highest accuracy of 97.7% in the training set and 85.5% in the validation set. The trained model was then applied to detect multiple partial faces in the test images.

How to Run :

1) For Partial Face Recognition :
	- Open the Retina Face Detection file.
	- Specify the dataset file path to detect the faces.
	- Run the Face Recognition scripts and save the models.
	- Load the best Face Recognition model (FaceNet in our case) to recognise the faces.
	- Run the script to recognise the faces and print the output images.


    
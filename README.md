# Face-Recognition
A Face Recognition project in Python that you can use for various other projects and service providers. 
This project is based on face_recognition library in Python. You have to install it first.You can refer the link below for the same:
https://github.com/ageitgey/face_recognition

There are two files FR Part1 & FR Part2:
In FR Part 1 we create two face encodings reg_face_encodings and str_face_encoding from the available images and save them in .dat files.
FR Part 1 needs to be run only once.

FR Part 2 is the execution file.

When FR Part 2 is executed, the camera live feed window appears(it might take some time based on PC performance)

r is pressed on keyboard to start recognition and then the result is displayed.
If, the user is a registered user it will recognise him and take action further.

If, the user is a new user, he will be provided with the service once and then his photo will be captured and automatically trained and stored as a defaulter if he asks for the service again without registration.

If, the user is not a registered user and has already used the free service once, he then will be labelled a defaulter and will not be provided with any service.

q is pressed to quit!

All improvements and corrections are Welcome!

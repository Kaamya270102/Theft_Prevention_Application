A theft prevention system is made with the help of AI ( Artificial Intelligence ) and CNN ( Convolution Neural Network ). It’s main aim is to help an individual or a group of family members to get notified about the intrusion in the house or their property. 
This system recognize the family members ( at least 1 ) as innocent and anyone apart from them ( the recognized faces ) as intruder. Also, once an intruder is identified, the system triggers an email with the picture captured.

Rules Followed :
      Use a webcam as a security camera
      The moment any family member come in front of the camera, it recognize them as an innocent
      The moment someone else comes into the frame (not family), it should capture the picture and notify the user through email with a picture captured
      
Focused Points :
      Training of a model to recognize known faces (At least one)
      Defining a function to differentiate known face (innocent) to an intruder
      Setup any SMTP service (Gmail, etc) for sending e-mail.
      Using Haar cascades to recognize a human and/or a face

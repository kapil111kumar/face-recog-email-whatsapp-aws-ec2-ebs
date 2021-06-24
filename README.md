# face-recog-email-whatsapp-aws-ec2-ebs
This is a code for face recognition for two users(face). My face and younger brother's face. 
I have used LBPH(Local Binary Patterns Histogram) and Haarcascade classifier.
When it will predict it as my face: It will send a message through WhatsApp and will send an email regarding this.
When it will predict it as my younger brother's face: It will create an AWS EC2 instance and EBS volume, EBS volume will be attached to it.

## Pre-requistes
libraries/modules: pywhatkit, time, numpt, boto3, opencv-contrib-python, smtplib.

## main.py
1. All the required libraries imported
2. Model is being trained for both faces
3. Train Model for my face
4. Running Our Facial Recognition and creating function for detecting face

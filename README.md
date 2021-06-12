# Learn Boto3
This repository deals with basics of AWS S3, ML/AI based AWS Rekognition & Comprehend & SNS services.
The purpose is to build an automated system for the local NGO to help them identify the issues in the neighbourhoud. 

Any user can upload an image (let's say pile of garbage) then using AWS Rekognition the object will be identified and NGO will be informed via SNS. 

## Prerequisite
An AWS User which will have the below permissions:
    * AWS S3 Full Access
    * AWS SNS Full Access
    * AWS REKOGNITION Full Access
    * AWS COMPREHEND Full Access

## Installation 
''' bash
pip install boto3
pip install pandas
'''



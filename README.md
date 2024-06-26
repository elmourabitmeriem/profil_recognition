# profil_recognition
This project aims to implement a profile recognition model. The main objective is to develop a system capable of scanning an identification document, extracting specific information such as name, surname, gender, and date of birth . Additionally, the model should also extract the person's image from the ID card and compare it in real-time with the person present, thereby ensuring instant identity verification.

## The project contains 2 files.

# Information extraction 

![alt text](image.png)

This schema primarily utilizes a first step involving acquiring data from an ID card, processing it to enrich the existing dataset. Next, it trains the model to determine the position of each specific element on the card. Finally, this model is applied to each new card to extract and retrieve the necessary information.

# Image extarction 

Extraction of the image from the card followed by real-time comparison.

![alt text](image-1.png)
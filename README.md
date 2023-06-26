# Handwritten_to_speech_GCP


The goal of our application is to take in 
handwritten text images written by students and to 
give out the text and convert this into speech in any 
language the evaluator prefers. Natural Language 
processing is also done on this text to identify entities 
and other features.
A custom dataset which has sentences classified 
into 3 labels ( Physics , Chemistry , Biology) is taken 
and trained using AutoML . The text identified from 
the image is given to this model which finally classifies 
it to the appropriate subject.
PAGE 1


#### Pretrained APIs used
###### • Cloud Vision 
To identify the Text present in the Image.
###### • Text to speech
To convert the text we obtained from the image to an audio file.
###### • Translate
To translate the text we obtained to any language chosen.
###### • Natural language
To analyze the text read.

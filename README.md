# Urban Semantics

## intro

As computer vision technology advances, this research aims to develop a model that processes unspecific user prompts and delivers customized, 
quantitative analysis for urban mapping. 

The model will streamline a process that accepts user prompts and locations to automatically collect street views along with several layers 
of maps, then return predictions and confidence heatmaps for users to explore the city. 

Utilizing zero-shot object detection, the model is not constrained by a predefined list of keywords but instead understands the correlation
between general texts and images. This capability enables the analysis to be fully scalable and real-time, without a limited scope. It can 
analyze aspects such as building types, user groups, or even the emotional ambiance of a location.

## Setup

The script was previously developed inside Google Colab. Please follow the instructions within the file step by step, and all the necessary 
libraries and datasets will be installed along the way. It is also suggested to run the script on your Colab since the ML models might take 
some time to set up for the first time.

## What's Next

Based on the prototype, I am currently improving the data collection mechanism from the Google Maps API, aiming to better fine-tune the NLTK 
for improved segmentation results. Additionally, I am seeking new models to cross the language barrier and operate the pipeline in cities that 
do not use English as their primary language. 

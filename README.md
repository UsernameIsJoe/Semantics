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

The script was previously developed insdie Google Colab, please follow the instructions within the file step by step and all the neccesary 
libraries and datasets will be installed along the way. It is also suggsted to runthe script on your Colab sinc the ML models might take som
time to set up for the first time.

## What's Next

Based on the protorype, I am currently improving the data collection mechanism from Google Maps API, aiming to better fine-tune the NLTK for
Better segmentation results. Also, I am seeking new models to cross the language barrier and operate the pipeline in cities that do not use Eng
as their primary language. 

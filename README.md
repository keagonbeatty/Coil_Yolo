# Hairpin/Return Bend Quality Check Program

## Description of Project
This project is a takeoff point for creating an application for quality checking the hairpin patterns of fin and tube heat exchangers in a production enviroment.

## Usage
This project serves as an extremely basic understanding of a larger project for quality checking the hairpin patterns and return bend pattern of custom made 
fin and tube heat exchangers. Within the industry of custom made fin and tube heat exchangers, one problem with mass scale production of such custom
nature is the issue of incorrectly circuiting heat exchangers. Incorrect circuiting if caught in production before expansion can result in increased labor, however it 
mitigates the downstream effects such as spoiled material, increased post expansion labor, and customer dis-satisfaction. This project aims to mitigate the risk involved with 
custom production of fin and tube heat exchangers and increase profit margins on such operations.

## Getting Started
To get started with this project I recommend the use of Visual Studio Code to interface with Jupyter Notebooks within the project itself.

## Training Model from scratch
In order to train a model from scratch you will need to do the following:
* Install Label Studio to create a dataset
* Export that Dataset in the YOLOv8 OBB format
* Sort the dataset into multiple directories to correctly train, test, and validate your model
* Create a YAML file to assist in this training effort.

I have created a script that will do everything but labelling the data for you. This script is called "Training_From_Scratch.ipynb" and it will assist you through the while process. To download Label Studio and get started with labelling datasets run `pip install label-studio`



# Disease Classificaion

A neural network model to classify a disease from given symptoms.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Django==2.0.1
mysqlclient==1.3.12
nltk==3.2.5
numpy==1.14.2
pytz==2017.3
six==1.11.0
```

## Deployment

After clonging the project and installing all the deppendecies, Open the command prompt and go to the project folder. Run the following command
```
python manage.py runserver
```
## Description

After running the command, the model will start training and show the delta value after every 10000 iterations. we can observe the value decresing gradually.


<img src="images/Disease-catagorization-1.JPG" >

By openning the web browser and navigating to the server we will be greeted by the following page.

<img src="images/Disease-catagorization-2.JPG" >

If we enter some syptoms it will identfy the disese with probable accuraccy as following.

<img src="images/Disease-catagorization-3.JPG" >

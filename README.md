# Deployed cat VS dog classifier. Flask and TensorFlow Serving with Docker

### About course

The project was made within the course "Deploy Models with TensorFlow Serving and Flask" 


*Description of course*:

This course runs on Coursera's hands-on project platform called Rhyme. 
On Rhyme, you do projects in a hands-on manner in your browser. 
You will get instant access to pre-configured cloud desktops containing 
all of the software and data you need for the project. 
Everything is already set up directly in your Internet browser so 
you can just focus on learning. For this project, 
you’ll get instant access to a cloud desktop with 
(e.g. Python, Jupyter, and Tensorflow) pre-installed. 
[LINK](https://www.coursera.org/projects/deploy-models-tensorflow-serving-flask).


### Created roject

![main page](https://github.com/OleksandrKosovan/deployed-cat-dog-classifier/blob/master/image_examples/main-page.png?raw=true)

![cat page](https://github.com/OleksandrKosovan/deployed-cat-dog-classifier/blob/master/image_examples/cat-page.png?raw=true)

![dog page](https://github.com/OleksandrKosovan/deployed-cat-dog-classifier/blob/master/image_examples/dog-page.png?raw=true)


### How to run

Install requirements: 

`pip install -r requirements.txt`

Run TensorFlow Serving with Docker:

`sudo docker run -p 8502:8501 --name=pets -v "/home/example/pets/:/models/pets/1" -e MODEL_NAME=pets tensorflow/serving`

See tutorial [here](https://github.com/OleksandrKosovan/deployed-cat-dog-classifier/blob/master/tutorial/instructions.pdf).
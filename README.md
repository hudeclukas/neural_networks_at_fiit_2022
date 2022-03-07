# Neural Networks @ FIIT

This repository contains supporting materials for the subject __Neural Networks__ (@ FIIT STU).

It is a very important repository, you will find here the assignments prepared for you, for the first 4 weeks of the semester.

## Course Information
- __Weekly tasks [7+3 pts]:__ First 3 weeks (after this one), you will work on the same tasks for better understanding of how neural networks work.
- __Projects [4+1 pts, 11+2 pts, 15+2 pts]:__ You will work in pairs on 3 deep learning project with gradually increasing difficulty throughout the entire semester. You will present your progress during the consultations, which are marked so you will be scored continuously and for the final presentations of your solutions.
- _8 pts for activity on courses and theoretical preparation from the lecture_ 
  - (the nature of questions and problems on courses may be similar to the ones in midterm and exam)
- __Midterm [15 pts]:__ This is gonna be fun
- __Exam [40 pts]__ This is gonna be a nightmare \
(No worries, not for you, for me to create them... even after previous year 🤦‍♂️)

You'll find out more during the firs lecture - you are encouraged to ask any questions regarding the course.
### Feedback
- If you find any inconvenience or errors in the notebooks, just let us know (or make a pull request)...
- Any recommendations to the subject + topics = let us know...

### Python
We use _Python 3.7_+ compatible code in these notebooks, however it may work with older versions.
We assume that you have seen Python code before. If you have not, Week 1 is a quick dive-in course that may help.
You should learn the basics as soon as possible (e.g. [W3Schools tutorial](https://www.w3schools.com/python/default.asp)).

##  Week 1
This is a warm-up week and for some of you the __lecture is after your seminar__, so we'll take it easy on you. 
All you have to do is to prepare your computing environment. 
If you have never worked with Python, this is a good chance for you to start - you'll be using it a lot during this semester (or not, if you prefer C++).
We have prepared a few simple tasks that you can find in the directory "week_1" - Jupyter Notebook.
If you know all of that already, well ...then, congratulations ;)

But still... the attendance of the seminars is mandatory.

Regards, L.

## Week 2
All hands on board!

This week, you are going to implement a simple multilayer perceptron with its feed forward function.
In the notebook, there are already prepared base classes and structures. 
Finish all the forward functions and run the visualization/print cells.
Follow the instructions in the notebook.

Of course - you don't have to do it before the seminar... 
As stated during the lecture and seminars, this is your work for the upcoming week's seminars.
Also - don't forget to refresh your memory about matrix operations and perceptron's architecture.

Good luck,

Regards, L.

## Week 3
Buckle up! 👍

After successful feed forward, the only logical step is to implement backward feed.
To make the task easier, we have implemented all feed forward functions for you according to the lecture with very similar variables naming. 
Apply chain rule and implement backward propagation for your network. 
The backward pass also requires the computation and derivation of loss function. 
... So remember the tears of years past of your studies and derive, multiply matrices (with correct operation) and transpose if necessary.

GLHF

Regards, L,P,I

PS: Hopefully I+P double check repaired all possible discrepancies

## Week 4

The time we all have been waiting for is here! (seriously, me too)

Let's do some training magic 🧙‍♂️

On this week's task, you will finally make your network able to train and to optimize its parameters. All is prepared, you just have to finish the algorithms of 3 optimizers (and do some tracking and visualizations).

Regards, L.

### Training is not all it takes!
We all started at debugging our systems with lines of text into textual output... 
Sure, it can help, but when you are training neural network for hours with new output every few seconds, the data can scale up to few thousands, and you ... we all are lazy to go manually through so many lines.
Thankfully, we don't have to!! because... Visualization comes to help 📈📉📊.

Maybe, few of you have the pleasure to know [**Tensorboard**](https://www.tensorflow.org/tensorboard), 
which is a nice graphical interface for visualizing any data aggregated during training, most usually graphs with losses.
Graphical visualizations help us greatly with identifying when(+where) the training went wrong.

However, time brought us multiple different visualization and tracking toolkits. 
 - [ML Flow](https://mlflow.org/)
 - [Kubeflow](https://www.kubeflow.org/)
 - our favorite [**WandB**](https://wandb.ai/)

There is a folder named [__wandb__](https://github.com/vgg-fiit/neural_networks_at_fiit_2022/tree/main/wandb) containing a jupyter notebook, that you might see helpful for your future work with WandB. 
Take a careful look into it, it is not that difficult. 

Oh, and I recommend you to create your free account.

...because - it is mandatory to track your trainings using **WandB** to present your progress on your semestral Assignments.

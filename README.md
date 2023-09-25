# streaming-04-multiple-consumers

> Use RabbitMQ to distribute tasks to multiple workers

One process will create task messages. Multiple worker processes will share the work. 


## Before You Begin

1. Fork this starter repo into your GitHub.
1. Clone your repo down to your machine.
1. View / Command Palette - then Python: Select Interpreter
1. Select your conda environment. 

## Read

1. Read the [RabbitMQ Tutorial - Work Queues](https://www.rabbitmq.com/tutorials/tutorial-two-python.html)
1. Read the code and comments in this repo.

## RabbitMQ Admin 

RabbitMQ comes with an admin panel. When you run the task emitter, reply y to open it. 

(Python makes it easy to open a web page - see the code to learn how.)

## Execute the Producer

1. Run emitter_of_tasks.py (say y to monitor RabbitMQ queues)

Explore the RabbitMQ website.

## Execute a Consumer / Worker

1. Run listening_worker.py

Will it terminate on its own? How do you know? 

## Ready for Work

1. Use your emitter_of_tasks to produce more task messages.

## Start Another Listening Worker 

1. Use your listening_worker.py script to launch a second worker. 

Follow the tutorial. 
Add multiple tasks (e.g. First message, Second message, etc.)
How are tasks distributed? 
Monitor the windows with at least two workers. 
Which worker gets which tasks?


## Reference

- [RabbitMQ Tutorial - Work Queues](https://www.rabbitmq.com/tutorials/tutorial-two-python.html)


## Screenshot
![Alt text](Images/Capture1.JPG)![Alt text](Images/Capture2.JPG)![Alt text](Images/Capture3.JPG)![Alt text](Images/Capture4.JPG)![Alt text](Images/Capture5.JPG)![Alt text](Images/Capture6.JPG)![Alt text](Images/Capture8.JPG)![Alt text](Images/Capture9.JPG)![Alt text](Images/Capture10.JPG)![Alt text](Images/Capture11.JPG)![Alt text](Images/Capture12.JPG)![Alt text](Images/Capture13.JPG)![Alt text](Images/Capture14.JPG)![Alt text](Images/Capture15.JPG)

See a running example with at least 3 concurrent process windows here:
![Alt text](<Images/3 terminal.png>)![Alt text](<Images/all tasks.png>)
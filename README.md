<h1 align="center">Training Udacity's Self Driving Car Simulator</h1>

<div align= "center"> <h4>Training a Deep Learning neural network that would allow a car to drive itself in a self-driving car simulator.</h4>
  <img src="https://github.com/stuti2403/Training-Self-Driving-Car-Simulator/blob/main/image.jpeg"/>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## :innocent: About the Project
Training a self-driving car using a Convolutional Neural Network. The open source Self-Driving car simulator provided by Udacity's nano degree program has been used in this project. Using this simulator, the neural network is first trained using training mode of the simulator. After training, the simulator is run in autonomous mode to view the car driving itself on the track.

## :warning: TechStack/framework used

- [OpenCV](https://opencv.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [Udacity-Self-Driving-Car-Simulator](https://github.com/udacity/self-driving-car-sim)
- <!-- - [MobileNetV2](https://arxiv.org/abs/1801.04381) -->


## How to Install the simulator
To install Udacity's Self Driving Car Simulator, follow the steps given in the following link:
https://kikaben.com/introduction-to-udacity-self-driving-car-simulator/

## Working
## Training the model:
To train the convolutional neural network, run the file named trainingSimulation.py. Then, open the simulator and run it the training mode. Collect data by pressing record button followed by pressing space bar on the keyboard to store screenshots of the current car position. Doing this also stores the car's data in a csv file such as steering angle, speed and throttle. 

## Testing :
The video given below shows the car driving itself in the autonomous mode on the simulator after the model has been trained. This output is seen by running the file testsimulation.py followed by running the simulator in autonomous mode.





https://user-images.githubusercontent.com/72308729/227167010-bad69e22-adf5-49c9-9832-94443094c1d3.mp4






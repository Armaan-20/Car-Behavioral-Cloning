# Car-Behavioral-Cloning
This project is about self driving cars.
I have used the Udacity self driving car simulator for replicating the environment in which the car drives. 
The training data is itself created by taking real time images from the track while the car is driving in the simulator.
During this process a corresponding .csv file is created which records the steering angles, speed, throttle values, etc.
The Image dataset is preprocessed by various data augmentation techniques like flipping the images, changing the brightness, cropping and adding shadows,etc.
The Nvidia modified model is used here to train the dataset.

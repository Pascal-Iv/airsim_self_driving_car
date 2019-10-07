# Airsim: Self-driving Car
I built a convolutional neural network (CNN) for autonomous driving in a simple virtual environment. 
The virtual environment is Airsim, an open-source simulation environment for cars and drones.
I created training data by manually driving in Airsim, while recording images taken by the front camera and the current steering angle.
The CNN was trained to predict the appropriate steering angle for a given image of the front camera.
It learned to assess its location on the street and how to react accordingly.
The driving speed was not learned, I just hardcoded it.

You can download my cooked data here:
https://drive.google.com/drive/folders/1KhPBuFM6znu6giGoha1bPmfbEGiH-IPR?usp=sharing

Or you can directly download my neural network model to run the car:
https://drive.google.com/file/d/1-gho_TuLx7ku1phH8Ba2CFlyKNqaOe63/view?usp=sharing

To test the driving, you also need to download the Airsim Coastline environment from:
https://github.com/Microsoft/AirSim/releases/tag/v1.2.1


Just start the environment, adapt the PATH variables in the test_model script and run it, e.g. in a Jupyter Notebook.





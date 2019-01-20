## Let's play with machine learning!

So I wanted to play with my RPI3, my new Intel Neural Compute Stick 2 (NCS2), a camera, some servos and Python.

Step 1: get a RPI ready:
- Set up Raspbian
  - headless setup [link](https://medium.com/coinmonks/run-raspberry-pi-in-a-true-headless-state-cfb3431667de)
- Get the camera to work
  - together with a servo turret [link](https://learn.sparkfun.com/tutorials/setting-up-the-pi-zero-wireless-pan-tilt-camera)
  - Don't forget to enable the camera and update the firmware using raspi-config
  - probably would work also using [this](https://projects.raspberrypi.org/en/projects/getting-started-with-picamera)
- Install OpenVINO
  - Install OpenVINO [link](https://software.intel.com/articles/OpenVINO-Install-RaspberryPI)
  - Only the inference works on the RPI in Jan 2019. Make sure to download the distribution linked in the above instructions

Step 2: Train a model
- a local computer to practice
- an AWS image to do the real training
Step 3:
- Run it again on the device and do some actions


# experiment 1
1) Let's use an already trained model on my computer (face detection)
2) See how to convert it to OpenVINO
3) Run it on the RPI

# experiment 2
1) Let's try to train a new model

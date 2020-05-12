# CVC---Sign-Language-Translator
In college there is a computer vision compition (CVC), we provided an idea for our project which is a translator for arabic letters (some of them)for deaf and mute poeple . 

We developed a machine learning model (we tried many models) to detect 6 arabic characters(ب ت ث س م ك).

## Team name: Space cowboy
## Team members 
  - Abanoub Salib
  - Abanoub Michael
  - Rita Ehab
  - Reham Ashraf
  - Menna Allah Mohamed

## Our Workflow
  1) We made a dataset by ourselves but then we found a dataset that can help us as ML model need large dataset.
  2) Image processing is done for captured stream of photos by detecting the hand on image whetether the user appear or not in image and 
    background removal to ease the task for the model.
  3) ML model is trained by those (more than one model is made actually) and tried to reach an acceptable level of accuracy.
  4) Desktop application is developed and GUI is made to be user friendly interface.
  
## Libraries we used:  
- tensorflow
- OpenCV v4.2.0
- numpy
- Tkinter
- PIL

## Software assumptions
A few assumptions have been made:
1. The camera is supposed to be static.
2. The camera has no automatic regulations, such as auto-focus etc.
3. The user is not moving in the frame (eg: he sits at his desk in front of the camera).
4. There are no particular constraints on the color of the background, but it should be approximately static (no moving objects/strong changes of illumination in the background).

## Usage
This software has been developed on google colab, executed by jupyter notebook as Webcam can only be accessed locally. 

### Software Usage
After configuring your webcam you can close the window. You'll now have two windows. To use the program perform this sequence of actions:
1. Without showing your hand in the frame, press the `B` key on your keyboard. It will start the process of background removal.
2. Move your hand so that it completely covers the two purple rectagles shown in the window called `output`. Press the `S` key on your keyboard. This will sample the color of your skin and start the process of hand detection.
3. When you want to close the program press the `esc` key on your keyboard.

                   

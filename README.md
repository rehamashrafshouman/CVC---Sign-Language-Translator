# CVC---Sign-Language-Translator
In college there is a computer vision compition (CVC), we provided an idea for our project which is a translator for arabic letters (some of them)for deaf and mute poeple. 

We developed a machine learning model (we tried many models) to detect 6 arabic characters(ب ت ث س م ك). Due to limitaions of time and GPU, the model was trained on 6 letters only.

## Team name: Space cowboy
## Team members 
  - Abanoub Salib :ML 
  - Abanoub Michael:GUI
  - Rita Ehab:Image processing
  - Reham Ashraf :Image processing
  - Menna Allah Mohamed: GUI

The whole team did the integration part and collected the dataset.
For demo click [here](https://youtu.be/DT6lTy0NkSU)

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
1. Click on `Open Camera` button.
2. Move your hand slightly close to camera. Gesture will be translated at once and diplayed in left window.
3. If the predicted letter is what you desire press `a` on your keyboard to add it to your word.
4. If not desired letter added you can delete last letter by pressing on `l`.
5. You can copy word to clip board by pressing on button `copy to clip board` so you can paste it in whatever you want.
6. If you want to clear word press on `c`.
7. To add a new word to sentence press `space`.
8. To quit from camera press `q` .




                   

According to WHO, 39 million peoples are estimated as blind worldwide. They are suffering immense hardships in their daily life.

The affected ones have been using the traditional white cane for many years which although being effective, still has a lot of disadvantages. Another way is, having a pet animal such as a dog, but it is really expensive.

# So, the aim of the project ,"Third Eye", is to develop a cheap and more efficient way to help visually impaired to navigate with greater comfort, speed and confidence.

# The product consists of:
# - The Smart Cap: 
Smart Cap helps the user navigate through traffic safely and confidently by reading out traffic signboards to them and instructs them accordingly, which is recorded in real-time by the camera fixed on the cap.
# - The Smart Glove:
Smart Gloves facilitate the user to detect obstacles in their proximity and alert them by vibrating. The Ultrasonic sensors keep a constant watch for the user to walk around safely.
# - The Smart Body Module:
The Smart Body Module consists of 4 modules that the user fixes at the designated area, i.e. , 
- 2 on the shoulders (to detect obstacles for the upper body)
- 2 on the knees (to detect obstacles for the lower body)
This ensures complete protection from obstacles for the user.

# Traffic-Signs-Detection
SIGNS_LOOKUP = {
        (1, 0, 0, 1): 'Turn Right', # turnRight
        (0, 0, 1, 1): 'Turn Left', # turnLeft
        (0, 1, 0, 1): 'Move Straight', # moveStraight
        (1, 0, 1, 1): 'Turn Back', # turnBack
    }
    
    
    
The sign_lookup matrix is defined to distinguish between ahead, back, left and right showing traffic signals. The algorithm can be used to define other traffic signs also. Video is captured using a webcam and output window is generated after initial code run. Test it on the sample images. currently works on these four signs, you can add up more sign matrices and also define functions for traffic signals.

For more info, refer:
https://prezi.com/view/9tYFxcu3rtrAP1AzDkTc/
    
    Compiled on Python 3.6.2

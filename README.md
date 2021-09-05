# Get_Fit_HackJNU

Demo Video: https://youtu.be/2Fya_Rl5664

In pandemic, most of us are just sitting in front of the computer and getting fatter & unhealthy day by day. People are getting serious about their health during the pandemic but they are not motivated enough to go to gym or yoga classes.
Exercising is boring and tiresome for beginners so they quit.
So we want to solve the problem with <strong>Stay Fit</strong>.

It has guided Gym workout as well as yoga with help of ML. Anyone can access it from anywhere. Now exercising will be a fun part of life.

It has guided Gym workout as well as yoga with help of ML. Anyone can access it from anywhere. Now exercising will be a fun part of life.
We have utilized Posenet model and mediapipe pose api for keypoints extraction of body parts and after getting these keypoints, firstly for Gym part we are calculating angle between different body parts and accordingly giving instruction to user to perfrom that gym exercise and maintain the count of reps. For Yoga part we are extracting the keypoints using posenet, we have trained an artificial neural network using ml5.js to correctly classify the yoga poses and if the detected pose is correct then we are maintaing the timer accordingly the yoga pose performed.  

To run Gym app independently:

  `clone the repo and go into Gym_app folder`
  
  `Install the needed dependencies using pip install -r requirements.txt`
  
  `Run python app.py`

How to run the Frontend of the app:

To run the react app (main dashboard website):

  `cd Frontend`

  `yarn install`

  `yarn build`

The optimized build will be present in the `build` folder. You can then deploy this folder.


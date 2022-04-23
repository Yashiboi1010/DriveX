# DriveX

Creators: Fnu Yash, Aniket Gupta

Purpose/Functionality: Uses camera to analyze face and determine drowsiness levels.  If the user is found drowsy, they will be alerted to wake up and stop driving.

PREREQUISITES:
Python 3.7.9
  1. pip install opencv-python
  2. pip install pygame
  3. pip install scipy
  4. pip install cmake
  5. Download all the C++ Redistributable files: https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170
  6. Download Visual Studio 2022: https://visualstudio.microsoft.com/downloads - and install all C++ tools
  7. pip install dlib

FILES:
  EARCalculator.py: Used to calculate user's average EAR
  alarm_tone.mp3: Alarm file
  earinfo.txt: List of all users and their EARs
  main.py: Main file to run the app
  shape_predictor_68_face_landmarks.dat: Face landmarking tool used to landmark the face.
  
NOTES:
  1. EAR: What the app uses to calculate drowsiness levels - to calculate, use EARCalculator.py to determine your average EAR
  2. When using the app for the first time make sure to change the path in EARCalculator.py and main.py to your respective path.

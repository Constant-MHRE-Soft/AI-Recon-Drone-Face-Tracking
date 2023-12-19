# A.I. Recon Drone Face Follow and Surveillance.
This is a rather simplistic approach to be able to launch your Tello drone & have it track your face. 
This approach has been tested & proven to work with the DJI Tello Drone.

Tested with Python 3.7, but it also may be compatible with other versions.


## Install
```
pip install -r requirements.txt
```

## Usage
```
  -h, --help            ** = required
  -d DISTANCE, --distance DISTANCE
                        use -d to change the distance of the drone. Range 0-6
                        (default: 3)
  -sx SAFTEY_X, --saftey_x SAFTEY_X
                        use -sx to change the saftey bound on the x axis .
                        Range 0-480 (default: 100)
  -sy SAFTEY_Y, --saftey_y SAFTEY_Y
                        use -sy to change the saftey bound on the y axis .
                        Range 0-360 (default: 55)
  -os OVERRIDE_SPEED, --override_speed OVERRIDE_SPEED
                        use -os to change override speed. Range 0-3 (default:
                        1)
  -ss, --save_session   add the -ss flag to save your session as an image
                        sequence in the Sessions folder (default: False)
  -D, --debug           add the -D flag to enable debug mode. Everything works
                        the same, but no commands will be sent to the drone
                        (default: False)
```

## Controls
- Esc: Quit Application
- T: Takeoff
- L: To Land

##### AI Mode
- 0: Set Drone distance to 0
- 1: Set Drone distance to 1
- 2: Set Drone distance to 2
- 3: Set Drone distance to 3
- 4: Set Drone distance to 4
- 5: Set Drone distance to 5
- 6: Set Drone distance to 6

##### Override Mode or Surveillance mood
- Backspace: Enable / Disable Override mode
- W/S: Fly Forward/Back
- A/D: Pan Left/Right
- Q/E: Fly Up/Down
- Z/C: Fly Left/Right
- 1: Set Drone speed to 1
- 2: Set Drone speed to 2
- 3: Set Drone speed to 3

## Demonstration of AI Recon Drone's Face Tracking feature
https://www.youtube.com/watch?v=oYa4MbPf860


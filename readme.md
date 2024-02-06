# Instruction to run the code

* Install the required dependencies
```cmd
  sudo pip install scipy math matplotlib pillow opencv-python quaternions
```

1. ADDING PATH TO SAVE DJI RAW FRAMES 
    
    In wrapper.py add drone images path at line 22 and 24.For eg.
    ```python
    
      images_directory_1 = '/home/pear/AerialRobotics/Aerial/HW4/pytorch-spynet/images/frames_raw_images'

      images_directory_2 = '/home/pear/AerialRobotics/Aerial/HW4/pytorch-spynet/images/frames_opticalflow'
    ```


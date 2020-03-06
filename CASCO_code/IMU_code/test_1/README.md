# test_1 
test_1 is the code to simply read out the data from the IMU sensor. if you plug into the correct pins, you should
see the output of the data. the one thing off will be the YAW. the reason for this is becuase this IMU doesnt have a
magotometer. This IMU is 6-dof (gyroscope and accelerometer). Maybe in the future we can expand to a 9-dof depending if
we need that, but for the current status, the chnages in the pitch and roll can be used to sense if the user is using the 
helmet or not.

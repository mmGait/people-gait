# Human gait in ‘mmWave’ eyes

  We collect a total of 30 hours of gait data from 95 volunteers. The data set contains two types of walking trajectories includes fixed route and free route, wherein up to 5 volunteers walk at the same time. For fixed route, each volunteer walked back and forth on the fixed route 25 times, lasting about 5 minutes; For free route, each volunteers walked freely in the test scenario for about 10 minutes.

# Name rules.
  The file # people-gait/room1/4/fixed_route/77Ghz_device/xx_xx_xx_xx.csv means the data collect from the device with the mmWave frequency band of 77 to 81Ghz. There are 4 co-existing people walking on the fixed route in the scene1.
  The file # people-gait/room2/3/free_rout/60Ghz_device/xx_xx_xx.csv means the data collect from the device with the mmWave frequency band of 60 to 64Ghz. There are 3 co-existing people walking freely in the scene2.

![image](https://github.com/mmGait/people-gait/blob/master/people.jpeg)

 # Volunteers.
  There are 45 male volunteers and 50 female volunteers. The age of the volunteers is between 19 and 27. More than half of the volunteers are aged 20 and 21(college students in our university). The height of the volunteers is between 150cm and 185 cm, and more than two-thirds of the total population in the range of 160 cm to 180 cm. The weight distribution of the volunteers is between 41kg and 115kg. More than half of the volunteers weigh between 50 and 65 kg.

 # Data composition. 
  The number of volunteers in the dataset is shown in Table 1. For example, the number 25 in row 3vol-sim and scene2 fixed route column means there are 25 volunteers took part in an experiment where a volunteer walks with another two volunteers on fixed route in scene2.
  
 # Data format. 
  The .csv file is a sequence of poind cloud collect from mulity co-existing walking people. Point cloud contains several points. Each line in the file records a point, and each column represents an attribute of the point. The meaning of each column in the document is as follows:
  Frame \#: Frame number of the point cloud where the point is located. 
  \# Obj: The number of points in the point cloud where the point is located.
  X: The position of the point in X dimension, m
  Y: The position of the point in Y dimension, m
  Z: The position of the point in Z dimension, m
  Doppler：Radial velocity of the point, m/s
  Intensity：Peak Value (relates to the strength of the detection)
  y, m, d, h, m, s；Time to get the point.

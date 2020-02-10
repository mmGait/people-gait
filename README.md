# people-gait

  We collect a total of 30 hours of data from 95 volunteers5. The data set contains two types of walking trajectories in cludes fixed route and free route where is up to 5 volunteers walking at the same time. For fixed route, volunteers walked back and forth on the fixed route 25 times, collected about 5 minutes; free route collected about 10 minutes.
  
The file # people-gait/611/4/guding/1443/xx_xx_xx_xx_1443_mid_guding.csv means the data collect from the device IWR 1443 there are co-existing 4 people walking on the fixed route at the room 631.
The file # people-gait/611/4/ziyou/1443/xx_xx_xx_xx_1443_mid_guding.csv means the data collect from the device IWR 1443 there are co-existing 4 people walking on the free route at the room 631.

![image](https://github.com/mmGait/people-gait/blob/master/people.jpeg)
 # Volunteers.
  We collect mmGait from 95 recruit volunteers. mmGait contains 45 male volunteers and 50 female volunteers. The age of the volunteers is between 19 and 27. More than half of the volunteers are aged 20 and 21. The height of the volunteers is between 150cm and 185 cm. With more than two-thirds of the total population in the range of 160 cm to 180 cm. The weight distribution of the volunteers is between 41kg and 115kg. More than half of the volunteers weigh between 50 and 65 kilograms.

 # Data composition. 
  The number of volunteers in the dataset is shown in Table 1. For example,The number 25 in row 3vol-sim and scene2 fixed route column means there are 25 volunteers took part in an experiment where volunteers need to walk with other two volunteers on fixed route in scene2.
  ![image](https://github.com/mmGait/people-gait/blob/master/point.jpg)
 # Data format. 
  The data collected by our sensors are very sparse, as shown in Fig. 2. That is because the human body acts as a reflector rather than a scatter. At any point in time, our sensor can capture only a subset of the radio frequency reflections off the human body. Fig. 2 confirms two facts. Firstly, as the number of volunteers walking increases simultaneously, the number of points in the point cloud increases. However, the increase in the number of points becomes smaller. Secondly, as the number of volunteers walking increases simultaneously, the number of points for a volunteer in the point cloud decreases. This is because, first, he output capacity of the sensor is limited. As the number of points in the point cloud increases, the sensor only could output the points with higher confidence. What’s more, asthe number of points in the point cloud increases, the probability of a volunteer occluded by other volunteers is increasing. For example, when five people are walking, the sensors could only detect three people most of the time. Hence as the number of people increases, the increase in the number of points becomes smaller and there will be fewer points on each person. The two sensors work at the same time can effectively increase the density of point cloud and effectively reduce the occlusion of volunteers.

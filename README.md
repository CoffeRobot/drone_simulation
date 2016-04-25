# drone_simulation

Additional files to work with drones in gazebo and ros. 

# Contents

- [Setup](#markdown-header-setup)
- [Models](#markdown-header-models)
- [Launch](#markdown-header-launch)
- [World](#markdown-header-world)


## Setup

Most of the files included in this package are modification of the packages provided by Erle Robotics. These are additional files to help building a more complex simulating environment. To setup your simulating environment please follow the guide written by [Erle Robotics](https://erlerobotics.com/docs/Simulation/Configuring_your_environment.html).

## Models

Various Aruco markers are included in the folder using the original model create by Erle Robotics. 

```
git clone https://github.com/CoffeRobot/drone_simulation.git
mv models/* ~/.gazebo/models
```

## Launch

Launch files should be move to the launch folder of the ardupilot_sitl_gazebo_plugin in the ros workspace used for simulation.

## World

World files should be move to the worlds folder of the ardupilot_sitl_gazebo_plugin in the ros workspace used for simulation.
# Need for Speed
This is the capstone project repo for the Udacity Self-Driving Car Nanodegree: Programming a Real Self-Driving Car. For more information about the project, see the project introduction [here](https://classroom.udacity.com/nanodegrees/nd013/parts/6047fe34-d93c-4f50-8336-b70ef10cb4b2/modules/e1a23b06-329a-4684-a717-ad476f0d8dff/lessons/462c933d-9f24-42d3-8bdc-a08a5fc866e4/concepts/5ab4b122-83e6-436d-850f-9f4d26627fd9).

Need for Speed is comprised of the following engineers:

* Kiarie Ndegwa (kiarie.ndegwa@gmail.com) 
* Joseph Zhou (zhouqi.joseph@gmail.com)
* Pramod BM (pmb@nvidia.com)
* Sidharth Varier (sidvarier@gmail.com)
* Mike Rzucidlo (mfrstatements@yahoo.com)

To build the environment needed to run the code in this repo, you should follow the instructions in the [original Udacity project instructions](https://github.com/udacity/CarND-Capstone).

# Building and running the project
You can find the light classification [model](https://drive.google.com/open?id=1zgwV5fsgDHjXK9b8VZwyg0DkvvAWgFZ1) in this link.

To use it in the simulator you must:
* Download and extract model.tar.gz
* You should find frozen_inference_graph.pb after extaction
* Copy ```frozen_inference_graph.pb into ros/src/tl_detector/light_classification/sim_model``` into your local repo

Once set up you need to go to the folder labeled ```NFS-Capstone/ros``` and type in the following and build commands:
* ```catkin_make```
* ```devel/setup.sh```
* ```roslaunch launch/styx.launch```
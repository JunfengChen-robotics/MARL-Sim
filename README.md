# MultiRoboLearn
<!-- omit in toc -->
 
**This is an unified framework which can by used by researcher multi-agent reinforcement learning in robot learning for multi-robot system.**

``MultiRoboLearn`` build an open-source framework for multi-robot systems. This framework builds a unified setup of simulation and real-world applications. It aims to provide standard, easy-to-use simulated scenarios that can also be easily deployed to real-world multi-robot environments. Also, the framework provides researchers with a benchmark system for comparing the performance of different reinforcement learning algorithms. 

![](https://github.com/JunfengChen-robotics/MultiRoboLearn/blob/main/gif/sac.gif) 

**Test mode in both simulation and real world for multi-sac algorithm**


![](https://github.com/JunfengChen-robotics/MultiRoboLearn/blob/main/gif/dqn.gif)

**Test mode in both simulation and real world for multi-dqn algorithm**

# Main Features
- It mainly focus on multi-robot system. It provides the community with an open-source framework for MADRL simulations and their corresponding deployment on real robots. 
- It can be used in continous and discrete action space
- It herits [OpenAI Gym](https://gym.openai.com) interface for all the the environments, easily matching different kinds of algorithms
- It has been successfully deployed to train two kinds of MADRL algorithms to solve two different tasks in simulation as well as real-world tasks without any further training in  the real world

**Warning:** This framework is ongoing developing,  and thus some changes might slight changes occur. Please don't mind modification!

# Requirements

Our experimental platform can be well installed on both Ubuntu 16.04 and 18.04, in the future, our framework will support higher veirsion of Ubuntu. At the same time, this framework is tested in Python2.7 and Python3.5(higher Python3 versions are supported). 


Our framework has some packages and libraries as follows:
- **ROS**(Kinetic @ Melodic). For melodic version, we also bulid some dependencies:  **ros-melodic-pid **, ** ros-melodic-joy **
-  **Python2.7** &  **Python3.6 **
-  **Gym
-  **Virtualenv** (Due to ROS only supports Python2.x, however, multiagent reinforcement learning algorithms must be trained in Python3.x, so we build virtual environment.): so we need to build some dependencies:  **python-pip **, numpy, python-catkin-tools, python3-dev, python3-pip, python3-yaml. rospkg, catkin_pkg, geometry, geometry2, empy. 
-   **Tensorflow **
-   **Pytorch
-   **Keras
-   **Pandas


# 



# Liscence 
MIT

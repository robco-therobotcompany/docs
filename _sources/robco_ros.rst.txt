Robco ROS Integration
=====================

The Robco ROS integration (``robco_ros``) provides an interface between Robco
robots and the Robot Operating System (ROS).

Installation
------------

The Robco ROS integration requires ``librobcomm`` to communicate with the robot.
First please, install ``librobcomm`` according to the instructions in its
documentation: :ref:`librobcomm-install`

Then, clone the
`robco-ros repository <https://github.com/robco-therobotcompany/robco-ros>`_
into your catkin workspace and install its dependencies using ``rosdep``::

    cd ~/catkin_ws && rosdep install --from-paths src --ignore-src -r -y

Finally, build the package as usual::

    cd ~/catkin_ws && catkin_make


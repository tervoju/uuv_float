
http://wiki.ros.org/catkin/Tutorials/create_a_workspace

also look

http://wiki.ros.org/catkin/Tutorials/using_a_workspace

workspace creation

1) create a dir for workspace and src in that
2) catkin_make in workspace folder
    catkin_init_workspace vs. catkin_ma
        seems to be similar. only that catkin_init_workspace is run in src folder, catkin_make in workspace folder

3) command source devel/setup.bash
4) create packages
    visual studio code with ros plugin crtl+shift+p + ROS:create catkin package
    or from command line

    pub/sub publishers and subscribers

    service sort of rest service

    src
        -

    package
        - launch
        - urdf xacro file describing robot 
        - worlds

5) launch
    roslaunch simfloat_1001 world.launch


UAV
https://uuvsimulator.github.io/packages/uuv_simulator/docs/tutorials/create_new_vehicle/
https://github.com/uuvsimulator/uuv_simulator/issues/385


https://github.com/uuvsimulator/rexrov2/blob/master/rexrov2_description/urdf/rexrov2_base.xacro

http://www.irs.uji.es/uwsim/gallery

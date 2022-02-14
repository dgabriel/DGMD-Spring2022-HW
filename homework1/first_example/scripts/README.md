# Homework 1: First Example

Indented and tested versions of the Python files for homework 1.  
This content more or less copied from the slides originally created and maintained by Jose Luis Ramirez Herran ALM.  All credit belongs to that author, and all problems introduced are of my creation.  There are certainly mistakes and bad ideas in these files; feel free to fork and suggest improvements.  

To run this homework locally, follow these steps:

1. Properly install ROS1 (see http://ros.wiki.org; step-by-step instructions are out of scope for this README)
2. in ~/catkin_ws run ```catkin_create_pkg first_example std_msgs rospy roscpp```
3. copy the files from this repo into ~/catkin_ws/src/first_example/scripts
4. make the executable ```chmod +x *.py```
5. OPTIONAL (you don't *have* to add this to bashrc, it just makes it easier to run the bots)
      ```bash
         echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc
         source ~/.bashrc
         ```
7. run (I love debug because it will show you compile errors) ```catkin_make -DCMAKE_BUILD_TYPE=Debug```
8. run ```roscore```
9. Open a second terminal window and run ```rosrun first_example command_node.py```
10. Open a third terminal window and run ```rosrun first_example drive_node.py```

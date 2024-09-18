# hw1_introduction
ROS- Homework Assignment1
## Overview:
This is Implemented by Harsh Panara - hp475@cornell.edu


`![The title of your image](imageName.png)`.
## Deliverables
Answer are in hw1_introduction/writeup/README.md.
<ol>
<li> Define in your own words what a node, topic, publisher, and subscriber are and how they relate to each other.</li>
1.	Node: A node is basically a process which is responsible for performing computation in Robot Operating System. Each node is responsible and designed for some specific tasks which involves like collecting data from sensors, motors or some data processing. They communicate with each other by passing messages over topics. Nodes communicate indirectly through topics by using the publisher-subscriber model. Multiple nodes can publish to and subscribe from the same topic allowing for scalable and modular communication.
  
2. Topic: Topic is communication channel which is being used by nodes to exchange some messages. It acts like a “message bus” where nodes can either send or receive information as well. Topics are having specific naming conventions and messages sent to that named topic are available to all nodes which are interested in that topic.

3.	Publisher: Publisher is a node that sends the message to a specific topic and Robot operating system communicates with Publisher subscriber communication. Publisher creates a stream of data that other nodes can even subscribe to. Example – A sensor node might publish data from a camera or a LiDAR sensor to a topic. 

4. Subscriber: Subscriber is similar to publisher but they are the node that receives messages from a topic. It listens to data being published on a specified topic and processes that information. Example – A node controlling a robot arm might subscribe to topic like position coordinates and updates.

<li> What is the purpose of a launch file? </li>

<li> Include your RViz screenshot showing the car. </li>

<li> Include your runtime_comparison.png figure for the different norm implementations. </li>

<li> Include the locations.png and norms.png figures for the plan figure_8.txt. Make sure the plots contain labelled axes and a title. </li>

<li> Include the locations.png and norms.png figures for the plan crown.txt. Make sure the plots contain labelled axes and a title. </li>

<li> Optional for undergrad, mandatory for graduate: Include your own plan file, any code you wrote to generate it, and the resulting locations.png figure. </li>
</ol>

### Submission 
hw1_introduction is submitted on Gradescope.

### Reference Images
More images are in the hw1_introduction/src/writeup directory.
Below are some more reference Images which were taken while doing the assignment.
`![The title of your image](imageName.png)`.

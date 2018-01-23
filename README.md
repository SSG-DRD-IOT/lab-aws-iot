[AWS Alliance Workshop](https://github.com/SSG-DRD-IOT/Alliance-AWS-Workshop) > [AWS IoT Lab](lab-aws-iot.md)

# AWS IoT Lab

This lab will walk you through connecting your Up2 Board to AWS IoT. In this lab you will configure a device in AWS IoT, send some test data, and finally send sensor data gathered at the edge up to AWS IoT. 

### Prerequisites
You will need to have completed the following steps:
*	Setup UP2 board
*	Connect UP2 board to Arduino Create 
*	Complete the [Sensors and Actuators](https://ssg-drd-iot.github.io/toc-sensors)

## Configure AWS IoT
The first step is to configure AWS IoT to recieve incomming data from your UP2 board. Please follow the [AWS IoT tutorial](https://docs.aws.amazon.com/iot/latest/developerguide/iot-console-signin.html) up to the **Configure Your Device** step.

## Configure Pub/Sub Example 

Now that you have configured AWS IoT lets configure the AWS Pub/Sub example in Arduino Create and start sending and reciveing data. 

[Arduino Create AWS Pub/Sub](https://ssg-drd-iot.github.io/lab-arduino-create-aws-pub-sub)

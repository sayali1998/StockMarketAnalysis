# StockMarketAnalysis
Analysing Stock Market Data using Kafka <br />
<br />
This a project that I am developing for learning purposes. I have used this youtube video for reference :  [Stock Market Real-time Data Analysis using Kafka](https://www.youtube.com/watch?v=KerNf0NANMo)

---
<br />

# Steps in the project

- [Setting up EC2 Instance](#setting-up-EC2-Instance)    
- [Downloading Kafka on EC2 Instance](#downloading-Kafka-on-EC2-Instance)
- [Starting Zookeeper and Kafka server on local machine](#starting-Zookeeper-and-Kafka-server-on-local-machine)
- [Creating topic on Kafka server](#creating-topic-on-Kafka-server)
- [Creating producer and consumer on our server](#creating-producer-and-consumer-on-our-server)
- [Writing python code for Kafka producer and consumer in python on Jupyter Notebook](#writing-python-code-for-Kafka-producer-and-consumer-in-python-on-Jupyter-Notebook)
- [Simulating realtime data using a dataset](#simulating-realtime-data-using-a-dataset)
- [Setting up S3 Bucket](#setting-up-S3-Bucket)
- [Setting up Glue crawler](#setting-up-Glue-crawler)
- [Quering our data using AWS Athena](#quering-our-data-using-AWS-Athena)

### Setting up EC2 Instance

First, [Create an AWS Account](https://portal.aws.amazon.com/billing/signup?nc2=h_ct&src=header_signup&redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start/email) and activate it, which will take approximately 24 hours.

Steps to follow after activation:
1. On AWS Console, search for EC2
2. Go to the EC2 dashboard, then click on **Instances(running)** tab and the go to **Launch Instance**
3. Create a instance name for this project.
4. As you scroll down, you will find a box of key-pair(login), click on **Create a new key-pair**
    - Create a unique name for this key-pair
    - Choose RSA 
    - Create a key pair
<br />
> **Important:** Save the key-pair properly in a folder

5. Keep all the other settings to default, and then Launch Instance.

You can find the instance on the EC2 Dashboard under the Instances(running) tab.


### Downloading Kafka on EC2 Instance
### Starting Zookeeper and Kafka server on local machine
### Creating topic on Kafka server
### Creating producer and consumer on our server
### Writing python code for Kafka producer and consumer in python on Juoyter Notebook
### Simulating realtime data using a dataset
### Setting up S3 Bucket
### Setting up Glue crawler
### Quering our data using AWS Athena

Credits : Darshil Parmar [Stock Market Project](https://www.youtube.com/watch?v=KerNf0NANMo)



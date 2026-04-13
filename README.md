# web-server-architecture-using-EC2

A scalable web server deployed using EC2 with security groups and public access configuration with cpu monitoring and amazon EventBridge 

This project demonstrates how to deploy and manage a cloud server using AWS EC2. 
It includes setting up a web server, configuring security, monitoring with CloudWatch, 
and automating instance start/stop using EventBridge to optimize cost.

# Features 
1. using EC2 for serverless virtual machines
2. using public configuration with http and ssl security groups
3. using cloud watch to monitor resources
4. using eventbridge fr scheduling automation over the resoure (EC2)



# Tech Stack 
AWS EC2 
linux ubuntu 
security group 
HTTP protocol 


# problem statmenet 
Many users launch cloud servers but fail to manage costs, monitor performance, 
or automate routine tasks. This project solves that by creating a system that 
is accessible, monitored, and automated.

# services used 
- AWS EC2 (Virtual Server)
- Security Groups (Firewall)
- Apache (Web Server)
- AWS CloudWatch (Monitoring)
- SNS (Notifications)
- EventBridge (Automation)

# steps performed 
1. Launched EC2 instance (Amazon Linux)
2. Configured Security Groups (SSH, HTTP)
3. Connected via SSH
4. Installed and started Apache server
5. Deployed a basic web page
6. Set up CloudWatch alarm for CPU utilization
7. Configured SNS for email alerts
8. Created EventBridge rules to automate start/stop

# key learnings 
- Understanding of cloud infrastructure setup
- Importance of security groups and access control
- Monitoring system behavior using CloudWatch
- Automating cloud operations to reduce manual effort and cost


# future improvements
- Add HTTPS using SSL certificate
- Use domain instead of public IP
- Implement load balancing


<img width="940" height="447" alt="image" src="https://github.com/user-attachments/assets/9263a1ae-c5c7-42dd-830c-0e80e2ad64fc" />
figure shows the ec2 created


<img width="940" height="449" alt="image" src="https://github.com/user-attachments/assets/e89974f7-6902-4282-8d1d-a8597d41066d" />
connecting to the server 

<img width="940" height="451" alt="image" src="https://github.com/user-attachments/assets/d1ad7bc1-3ccd-4d2a-a0a4-ce6f80004eff" />
opening the workplace of the server 

<img width="940" height="447" alt="image" src="https://github.com/user-attachments/assets/8bbd873f-d1d3-4270-a2c3-c29810d552d6" />
cloudwatch configuration for cpu utilisation 

<img width="940" height="454" alt="image" src="https://github.com/user-attachments/assets/10b96cfe-3b3f-4795-8503-9ca30aa30371" />
sns configuration for threshhold 

<img width="940" height="446" alt="image" src="https://github.com/user-attachments/assets/2c20dd5f-b792-4c30-a645-b8a912e6e4be" />
amazon EventBridge to automate ec2 

<img width="940" height="446" alt="image" src="https://github.com/user-attachments/assets/284f1796-2122-42d0-adad-27bc80ac6695" />
scheduling the resource over the defined time 

<img width="940" height="445" alt="image" src="https://github.com/user-attachments/assets/98b7483b-e645-480e-b9c6-77d6402c702d" />
what measures to look after 


<img width="940" height="452" alt="image" src="https://github.com/user-attachments/assets/43088051-b294-48b6-95e8-604b56410511" />
scheduled priview


<img width="940" height="497" alt="image" src="https://github.com/user-attachments/assets/0c03b9ab-2285-465b-a806-f1292d5d24aa" />
shows the public ip being used 


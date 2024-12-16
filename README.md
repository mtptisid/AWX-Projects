# Ansible projects

# EC2 Instance Creation Playbook

This project contains an Ansible playbook that automates the creation of an EC2 instance on Amazon Web Services (AWS). It allows users to define parameters such as region, instance type, image ID, key name, security group, and tags, and then creates a new EC2 instance with these settings.

The playbook also retrieves and prints the public IP address of the newly created instance.

## Prerequisites

To use this playbook, you'll need the following:

- **Ansible**: Ansible is used to automate the EC2 instance creation process. You can install it with the following command:
  
  ```bash
  sudo apt-get install ansible
  ```

## Variables

The following variables should be defined in your playbook or provided via command-line arguments:
	•	ec2_region: The AWS region where the EC2 instance will be created (e.g., us-west-2).
	•	ec2_instance_type: The type of EC2 instance (e.g., t2.micro, m5.large).
	•	ec2_image_id: The AMI ID to use for creating the instance (e.g., ami-0abcdef1234567890).
	•	ec2_key_name: The name of your SSH key pair to access the instance (e.g., my-ec2-key).
	•	ec2_security_group: The security group to associate with the EC2 instance (e.g., my-security-group).
	•	ec2_instance_name: The name of the EC2 instance, which will be used as a tag (e.g., MyInstance).

## Screenshots

![Image 29-07-24 at 8 38 AM](https://github.com/user-attachments/assets/260ed3b9-c5eb-4876-8053-0b6623560bbd)

I have created a various jobs for AWS.

- ## Get_Instance_details
  This job will get all the instance details from selected rezion.
  
  run the the job by selecting the rezion

  <img width="1440" alt="Screenshot 2024-07-29 at 9 48 24 PM" src="https://github.com/user-attachments/assets/0ca08adb-4e3c-4ecf-b7ad-16830b5639be">

Launch the job after selecting the rezion.
  
<img width="1440" alt="Screenshot 2024-07-29 at 9 48 34 PM" src="https://github.com/user-attachments/assets/9fff48a5-14f0-47be-ab9d-b1b4b505005c">

you will get the details of all the listed VM's

<img width="1440" alt="Screenshot 2024-07-29 at 9 50 33 PM" src="https://github.com/user-attachments/assets/6b509d03-1a63-483b-8b73-afe9f78a0dc2">


  <img width="1440" alt="Screenshot 2024-07-29 at 9 53 31 PM" src="https://github.com/user-attachments/assets/be6d6938-beb5-4b72-9219-401550120dde">

  
<img width="1440" alt="Screenshot 2024-07-29 at 9 53 49 PM" src="https://github.com/user-attachments/assets/c93db9f4-d04a-4399-b0b1-7fd6d3af2f62">


<img width="1440" alt="Screenshot 2024-07-29 at 9 56 02 PM" src="https://github.com/user-attachments/assets/f023589b-bd68-4bc6-b78c-4a4df116f26c">



<img width="1440" alt="Screenshot 2024-07-29 at 9 56 09 PM" src="https://github.com/user-attachments/assets/dba4c680-15a1-4adb-9083-b4e4afb33798">


- ## Run_command_on_ec2_instance
  
  This job will run a command on ec2 instance.

<img width="1440" alt="Screenshot 2024-07-29 at 10 01 13 PM" src="https://github.com/user-attachments/assets/9fad4be0-bf22-4183-9dc0-4a1bd63596b7">



<img width="1440" alt="Screenshot 2024-07-29 at 10 01 20 PM" src="https://github.com/user-attachments/assets/952b153f-3dff-492f-b300-74b06a9648df">



<img width="1440" alt="Screenshot 2024-07-29 at 10 01 02 PM" src="https://github.com/user-attachments/assets/6c766d48-b96b-40a2-a27e-61360b36c496">


  


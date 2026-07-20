# Apache-httpd--demo-project

This project demonstrates how to deploy a simple static website using the Apache Web Server on an AWS EC2 instance.

This project includes a few milestones to help you gain hands-on experience.

Milestone 1: Deploy the Static Website on an EC2 Instance
Step 1: Launch an Ubuntu EC2 Instance
Step 2: Connect to the EC2 instance using SSH
Step 3: Update Packages and Install Apache
        sudo apt update
        sudo apt install apache2 -y
Step 4: Clone the git hub repository to your EC2 instance:
Step 5: Deploy the Website Files
          Copy the application files to Apache's default web root directory:
          sudo cp -r * /var/www/html/
          Apache serves web content from /var/www/html by default.
Step 6: Start and Verify Apache Service
          sudo systemctl start apache2
          sudo systemctl status apache2
Step 7: Access the Application -> Open a web browser and navigate to:
          http://<EC2-Public-IP>

If the deployment is successful, the static website will be displayed.

<img width="872" height="428" alt="Screenshot 2026-07-20 175047" src="https://github.com/user-attachments/assets/06f9e80c-1193-403f-923e-67f3a5066983" />

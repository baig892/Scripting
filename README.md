# Apache Installation Script with Custom HTML Page

This repository contains a Bash script to install Apache on an Amazon EC2 instance Amazon Linux and configure it to serve a custom HTML page. When the script is executed, it will install Apache, create a directory to store the HTML file, and serve a simple webpage on the EC2 instance's public IP.

## Requirements

- An Amazon EC2 instance (Amazon Linux 2 or compatible).
- An active internet connection to download packages.
- Proper security group settings to allow HTTP traffic (port 80).

## Installation

### Step 1: Clone the Repository

First, clone the repository to your EC2 instance:

```bash
git clone https://github.com/baig892/Scripting.git
cd Scripting




## Step 2: Run the Bash Script
Execute the installation script to install Apache and set up the custom HTML page:

bash
Copy
Edit
chmod +x install_apache_amazon.sh
./install_apache_amazon.sh

This will:

Install Apache (httpd).

Create a custom directory for serving the HTML file.

Move the index.html file to the Apache directory.

Set the correct permissions for the files.

Start the Apache service and enable it to start on boot.

Display the EC2 public IP where the webpage can be accessed.


## Step 3: Access the Webpage
Once the script has completed, open a web browser and go to your EC2 instance’s public IP address:

cpp
Copy
Edit
http://<your-ec2-public-ip>





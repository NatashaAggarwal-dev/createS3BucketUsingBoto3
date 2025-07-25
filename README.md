 🚀 AWS S3 Bucket Creator & File Uploader using Python (Boto3)

This project demonstrates how to **create an AWS S3 bucket** and **upload a local backup file** to it using Python’s Boto3 SDK — all inside a Jupyter Notebook!

## 📁 Project Overview
This script allows you to:

- 🔗 Connect to AWS S3 using Boto3  
- 🪣 Create a new S3 bucket in a specified region (`us-east-2`)  
- ⬆️ Upload a local file to the created bucket  
- 📂 Display all buckets available in your AWS account  

## 🛠️ Technologies Used

- 🐍 Python 3.x  
- ☁️ AWS S3  
- 🔧 Boto3 (AWS SDK for Python)  
- 📒 Jupyter Notebook  


## ✅ Prerequisites

### 1️⃣ AWS CLI Configuration (Recommended)

Ensure that the AWS CLI is configured on your machine:
aws configure

You’ll be prompted to enter:
AWS Access Key ID
AWS Secret Access Key
Default region name (e.g., us-east-2)
Default output format (e.g., json)

The credentials will be stored in:
~/.aws/credentials
~/.aws/config

✅ Jupyter and Boto3 will automatically use these credentials.

2️⃣ Install Dependencies
Install boto3 if you haven’t already:

pip install boto3

🚀 How to Use the Script
Clone or copy this repository.
Replace the file_path in the script with the path to your actual backup file.
Replace bucket_name with a unique bucket name (S3 bucket names must be globally unique).
Run the script inside your Jupyter Notebook.


🙌 Acknowledgments
Special thanks to:
Vimal Daga Sir — for inspiring deep learning in cloud technologiJibran Sir & Didlip Sir — for clearly explaining AWS & Boto3 concepts

🔐 Important Note
Make sure your IAM user has permissions to:
Create S3 buckets
Upload objects
List buckets

📬 Contact
For any issues or suggestions, feel free to reach out!

⭐️ If you find this helpful, consider giving a star to the repo!


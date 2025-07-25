# 🚀 Create an S3 Bucket Using Python and Boto3

This project demonstrates how to **create an AWS S3 bucket programmatically** using Python's Boto3 SDK inside a Jupyter Notebook.

## 📁 Project Overview

This script helps you:
- Connect to AWS S3 with Boto3
- Create an S3 bucket in a specific region (`us-east-2`)
- Handle region-based configuration issues
- Display all existing S3 buckets in your account

## 🛠️ Technologies Used

- 🐍 Python 3.x  
- ☁️ AWS S3  
- 🔧 Boto3 (AWS SDK for Python)  
- 📒 Jupyter Notebook

## ✅ Prerequisites

✅ 1. Run aws configure (recommended)( AWS account with programmatic access (Access key & Secret key)
This sets up credentials in a config file that boto3 automatically uses.

Open Anaconda Prompt, Git Bash, or CMD, then run:

aws configure
You'll be prompted to enter:
AWS Access Key ID:     <Your Access Key>
AWS Secret Access Key: <Your Secret Key>
Default region name:   us-east-2
Default output format: json
This stores your credentials in:

~/.aws/credentials

~/.aws/config

🧠 Jupyter Notebook will read these files automatically.

✅ 2. AWS CLI configured locally OR credentials set using environment variables or config file
✅ 3-`boto3` installed:
  (pip install boto3)

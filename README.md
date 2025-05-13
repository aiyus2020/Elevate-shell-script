# AWS Shell Script Automation – Mini Project

## 📝 What I Understand About the Requirement

This project is designed to help me apply key shell scripting concepts in a practical way by automating AWS tasks. The goal is to create a script that sets up EC2 instances and S3 buckets while using important shell scripting techniques.

Based on the requirement, I understand that the script should demonstrate the following five key areas:

1. **Functions** – Break down the script into modular, reusable parts for tasks like creating EC2 instances and S3 buckets.
2. **Arrays** – Use arrays to store and track the resources created (e.g., instance IDs and bucket names).
3. **Environment Variables** – Use variables to store sensitive data like AWS credentials or region for better security and flexibility.
4. **Command Line Arguments** – Allow users to input instance types or bucket names dynamically when running the script.
5. **Error Handling** – Add mechanisms to handle and respond to errors (e.g., if AWS services fail) so the script doesn’t crash unexpectedly.

The purpose of this phase is to confirm that I understand what is expected before moving into full implementation.

---

## 🧩 What the Script Does

The shell script:
- Accepts command line arguments for EC2 instance type and S3 bucket name.
- Creates an EC2 instance using AWS CLI.
- Creates an S3 bucket in the specified AWS region.
- Tracks created resources using arrays.
- Uses environment variables for AWS profile and region.
- Implements error handling to catch and respond to failures gracefully.

---

## 🚀 How to Run the Script

```bash
chmod +x setup_aws.sh
./setup_aws.sh --instance-type t2.micro --bucket-name my-unique-bucket-name-123

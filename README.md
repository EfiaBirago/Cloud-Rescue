Cloud Rescue Squad: Portfolio Recovery Mission

This project simulates a real-world cloud rescue scenario, where a startup’s portfolio website had to be rebuilt and redeployed using AWS and MongoDB technologies — all within the free tiers.

Objective

Recreate and deploy a secure, scalable, and fully cloud-hosted static website, with a simulated backend using MongoDB Atlas. The aim was to practice:

Cloud resource management with IAM

Static website hosting with Amazon S3

Secure deployment workflows using Amplify

Cloud-based data simulation using MongoDB Atlas

Tools & Services Used

Tool/Service	                 Purpose
AWS IAM	                    Created a secure user with MFA
Amazon S3	                Hosted the static site
AWS Amplify	                Deployment method
MongoDB Atlas	            Simulated backend storage
MongoDB Compass         	Connected to Atlas cluster
draw.io	                    Designed system architecture diagram
 
Key Steps

IAM & Security Setup

Created a dedicated IAM user

Enabled Multi-Factor Authentication (MFA)

Static Website Hosting with S3

Created and configured an S3 bucket

Uploaded a basic index.html

Enabled public access (via bucket policy)

Deployed website on AWS Amplify

MongoDB Atlas (Simulated Backend)

Created a Free Tier cluster

Simulated a contact form submissions database

Connected to MongoDB Compass for schema visualization

Architecture
Refer to the Architecture.png file for the full architecture diagram.

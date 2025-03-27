# 🌐 Static Portfolio Website Deployed on AWS S3 & Route 53

## 🚀 Overview  
This repository contains the configuration and deployment details for my **static portfolio website**, hosted on **Amazon S3** and managed with **Route 53**.  

## 🏗️ Architecture  
- **Amazon S3** – Used for static website hosting  
- **Route 53** – DNS management for a custom domain  
- **CloudFront (Optional)** – CDN for improved performance and security  
- **AWS Certificate Manager (ACM)** – For HTTPS with SSL/TLS  

## 🔧 Deployment Steps  
### 1️⃣ **Create an S3 Bucket**  
- Enable **Static Website Hosting**  
- Set permissions to allow public access (if required)  
- Upload the website files (HTML, CSS, JS, etc.)  

### 2️⃣ **Configure Route 53**  
- Register a domain or use an existing one  
- Create an **A record (Alias)** pointing to the S3 bucket or CloudFront distribution  

### 3️⃣ **Enable HTTPS (Optional but Recommended)**  
- Use **AWS Certificate Manager (ACM)** to issue an SSL certificate  
- Attach it to **CloudFront** for secure access  

### 4️⃣ **Automate Deployments (Next Step)**  
- Use **GitHub Actions / AWS CodePipeline** for CI/CD  

## 🎯 Key Benefits  
✅ **Scalable & Cost-Effective** – Pay only for what you use  
✅ **Fast & Secure** – With CloudFront & HTTPS  
✅ **Custom Domain** – Managed via Route 53  

## 📢 Connect with Me  
🔗 [LinkedIn](https://www.linkedin.com/in/praveen-methraskar-067441172/)
🔗 [Portfolio Website](http://praveenmethraskar.site/)  

If you found this useful, feel free to ⭐ the repo! Happy coding! 🚀  

#AWS #S3 #Route53 #StaticWebsite #CloudComputing #DevOps

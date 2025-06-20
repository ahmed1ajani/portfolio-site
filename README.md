# portfolio-site
Secure static portfolio site (GitHub Pages + AWS security mock)
# AWS Secure Static Website Hosting (Mock Setup)

This mock project explains how to securely host a static website using AWS services.

## 🛠️ Services Used
- **S3**: to store website files (private access only)
- **CloudFront**: to serve content over HTTPS
- **Certificate Manager (ACM)**: for SSL/TLS certificates
- **Route 53**: to manage custom domain (optional)
- **IAM**: for secure access control

## 🔒 Security Best Practices
- S3 bucket is not public
- Access only via CloudFront Origin Access Identity (OAI)
- HTTPS enforced (no HTTP)
- Custom SSL certificate applied
- Logging enabled for CloudFront
- IAM policy uses least privilege principle

## 📂 Files Included
- `bucket-policy.json` – Sample S3 bucket policy
- `iam-policy.json` – Sample IAM policy for limited access
- `cloudfront-settings.txt` – CloudFront config highlights
- `architecture.png` – Architecture diagram of setup

## 🔗 Live Demo (Simulated)
Hosted on GitHub Pages here: [https://ahmed1ajani.github.io/portfolio-site/](https://ahmed1ajani.github.io/portfolio-site/)

While this is not an AWS deployment, the structure and security design reflect real-world AWS standards.


# AWS S3 Static Website Hosting with Terraform

This repository contains Terraform code to create an AWS S3 bucket and configure it to host a static website. The configuration uploads an `index.html` and `error.html` file and sets the bucket for static website hosting.

## Overview

This Terraform script does the following:

1. Creates an S3 bucket.
2. Uploads `index.html` and `error.html` to the bucket.
3. Configures the bucket to be publicly accessible for static website hosting.
4. Sets `index.html` as the homepage and `error.html` for errors.

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/terraform-s3-static-website.git
cd terraform-s3-static-website

terraform init

terraform apply

terraform output website_endpoint

terraform destroy

Resources
S3 Bucket: Stores the website files.
Website Configuration: Sets index.html as the homepage and error.html for errors.



---

### Key Points:

1. **Overview**: A concise description of the Terraform code's purpose.
2. **Setup Instructions**: Short steps to clone the repo, initialize Terraform, apply the configuration, and access the static website.
3. **Screenshots**: Placeholder links for screenshots of the S3 bucket and website endpoint in AWS Console (you should replace these with actual screenshots).
4. **License**: Simple licensing information for the repository.

The **screenshots** are placeholders in the Markdown format. You can replace them with actual images showing:
- The S3 bucket created in the AWS Console.
- The static website endpoint URL.




# Aniket Chakraborty

Cloud and DevOps engineer in Liverpool, UK. AWS Certified Solutions Architect (Associate), MSc Computer Science (University of Liverpool, 2025).

I started in quality engineering at Cognizant, where I spent a year writing automated tests in Java and JavaScript and looking after Jenkins pipelines for a large Agile programme. That work got me interested in what happens after the tests pass: how code is built, shipped and kept running. These repos are where I practise that.

Open to junior cloud, DevOps, platform and test automation roles in the UK.

## Projects

| Project | What it is | Main tools |
|---|---|---|
| [ai-document-analyser](https://github.com/aniketrick/ai-document-analyser) | Upload a document, then a queue-driven pipeline pulls out the text, removes personal data and saves the result | AWS Lambda, S3, EventBridge, SQS, Textract, Comprehend, Bedrock, Terraform |
| [gitops-kubernetes-platform](https://github.com/aniketrick/gitops-kubernetes-platform) | A local Kubernetes cluster built with one `terraform apply`, with Argo CD deploying a small API from this repo | Terraform, kind, Argo CD, Helm, nginx ingress, Docker |
| [multi-az-vpc-alb-asg](https://github.com/aniketrick/multi-az-vpc-alb-asg) | A VPC across two Availability Zones with a load balancer and an Auto Scaling Group, split into Terraform modules | AWS VPC, ALB, EC2, Auto Scaling, CloudWatch, Terraform |
| [cloud-task-manager](https://github.com/aniketrick/cloud-task-manager) | A small task app with a React front end on S3 and CloudFront and a serverless API | AWS Lambda (Node.js), API Gateway, DynamoDB, CloudFront, Terraform |
| [aniket-cloud-portfolio](https://github.com/aniketrick/aniket-cloud-portfolio) | My portfolio site, deployed by GitHub Actions on every push | React, TypeScript, GitHub Actions |

## What I'm working on next

- A Java test automation framework (Selenium, REST Assured, JUnit) that runs on every pull request
- A real deploy pipeline for cloud-task-manager, using GitHub Actions with OIDC so no AWS keys are stored
- Monitoring and alerting on the Kubernetes platform with Prometheus and Grafana

## Tools I use

AWS · Terraform · Docker · Kubernetes · Helm · Argo CD · GitHub Actions · Jenkins · Python · Java · JavaScript · Bash · SQL · Selenium

## Contact

[LinkedIn](https://www.linkedin.com/in/aniket-chakraborty07) · [Email](mailto:aniket07chakraborty@gmail.com)

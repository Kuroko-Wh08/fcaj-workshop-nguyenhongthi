---
title: "MalScanAI Internship Report"
date: 2026-05-05
weight: 1
chapter: false
---

# Internship Report – MalScanAI Project


This website documents participation in the **AWS FCAJ Bootcamp 2026**, the learning activities completed during the internship, and the deployment of the **MalScanAI** project on AWS.


<div style="text-align: center; margin: 20px 0;">
  <img src="images/avatar-thi.jpg" alt="Avatar" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>

## Student information

| Item | Information |
|---|---|
| Full name | Nguyễn Hồng Thi |
| Phone number | 0703038883 |
| E-mail | kuroko042330@gmail.com |
| University | Ho Chi Minh City University of Technology |
| Major | Information Security |
| Class | 22DATA2 |
| Internship company | Amazon Web Services Vietnam Company Limited |
| Internship position | Workforce Bootcamp – First Cloud AI Journey |
| Internship period | From May 5, 2026 to July 26, 2026 |


## Project information

- **Project name:** MalScanAI
- **Deployment platform:** Amazon ECS Fargate
- **AWS Region:** Asia Pacific (Singapore) – `ap-southeast-1`
- **Application domain:** `malscanai.sadc.io.vn`
- **Main components:** Streamlit and URL Engine

MalScanAI is packaged into two Docker containers. The Streamlit container provides the web interface and scanning functions, while the URL Engine handles URL analysis separately. The application is deployed behind Amazon CloudFront, AWS WAF, and an Application Load Balancer.

![MalScanAI architecture](/images/5-Workshop/5.2-Architecture/malscanai-architecture.jpg)

## Report sections

1. [Weekly worklog](1-Worklog/)
2. [Project proposal](2-Proposal/)
3. [Published blog posts](3-BlogsPosted/)
4. [Events participated](4-EventParticipated/)
5. [MalScanAI deployment workshop](5-Workshop/)
6. [Personal self-evaluation](6-Self-evaluation/)
7. [Sharing and feedback](7-Feedback/)

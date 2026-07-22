---
title: "Báo cáo thực tập MalScanAI"
date: 2026-05-05
weight: 1
chapter: false
---

# Báo cáo thực tập – Dự án MalScanAI

Website này được sử dụng để ghi lại quá trình tham gia **AWS FCAJ Bootcamp 2026**, các hoạt động học tập và phần triển khai dự án **MalScanAI** trên hạ tầng AWS.

## Thông tin sinh viên

| Nội dung | Thông tin |
|---|---|
| Họ và tên | Nguyễn Hồng Thi |
| Số điện thoại | 0703038883 |
| E-mail | kuroko042330@gmail.com |
| Trường | Đại học Công nghệ TP.HCM |
| Ngành | An toàn thông tin |
| Lớp | 22DATA2 |
| Công ty thực tập | Công ty TNHH Amazon Web Services Việt Nam |
| Vị trí thực tập | Workforce Bootcamp – First Cloud AI Journey |
| Thời gian thực tập | Từ ngày 05/05/2026 đến ngày 26/07/2026 |

{{% notice warning %}}
Trang này có chứa số điện thoại và địa chỉ e-mail cá nhân. Trước khi đưa website lên kho mã nguồn công khai, cần kiểm tra lại phạm vi chia sẻ các thông tin này.
{{% /notice %}}

## Thông tin dự án

- **Tên dự án:** MalScanAI
- **Nền tảng triển khai:** Amazon ECS Fargate
- **AWS Region:** Asia Pacific (Singapore) – `ap-southeast-1`
- **Tên miền ứng dụng:** `malscanai.sadc.io.vn`
- **Thành phần chính:** Streamlit và URL Engine

MalScanAI được đóng gói thành hai Docker container. Container Streamlit cung cấp giao diện web và các chức năng quét, trong khi URL Engine xử lý riêng phần phân tích URL. Ứng dụng được triển khai phía sau Amazon CloudFront, AWS WAF và Application Load Balancer.

![Kiến trúc MalScanAI](/images/5-Workshop/5.2-Architecture/malscanai-architecture.jpg)

## Nội dung báo cáo

1. [Nhật ký công việc theo tuần](1-Worklog/)
2. [Bản đề xuất dự án](2-Proposal/)
3. [Các bài blog đã đăng](3-BlogsPosted/)
4. [Các sự kiện đã tham gia](4-EventParticipated/)
5. [Workshop triển khai MalScanAI](5-Workshop/)
6. [Tự đánh giá cá nhân](6-Self-evaluation/)
7. [Chia sẻ và đóng góp ý kiến](7-Feedback/)

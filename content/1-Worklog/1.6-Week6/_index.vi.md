---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Nắm vững các kiến thức nền tảng về bảo mật AWS, mô hình Trách nhiệm chung (Shared Responsibility Model), quản lý danh tính (IAM) và xác thực người dùng qua Amazon Cognito.
* Triển khai các khung quản trị bảo mật cấp doanh nghiệp, bao gồm quản lý đa tài khoản, tập trung quyền truy cập (SSO), mã hóa dữ liệu (KMS) và giám sát tuân thủ tự động.
* Phát triển kỹ năng vận hành tự động hóa bằng kiến trúc Serverless (AWS Lambda) và quản trị tài nguyên thông qua gắn nhãn (Tagging) và kiểm soát truy cập (IAM).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Nền tảng bảo mật AWS:** <br> - Nghiên cứu mô hình Trách nhiệm chung (Shared Responsibility Model) <br> - Chuyên sâu về IAM: users, groups, policies và roles <br> - Tìm hiểu cơ chế xác thực/ủy quyền người dùng với Amazon Cognito (User Pools, Identity Pools) | 25/5/2026 | 25/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Quản trị doanh nghiệp và bảo mật:** <br> - AWS Organizations (quản lý đa tài khoản) <br> - AWS Identity Center (SSO) <br> - Quản lý khóa mã hóa AWS KMS <br> - Sử dụng AWS Security Hub để giám sát tuân thủ bảo mật | 26/5/2026 | 26/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Lab giám sát tuân thủ bảo mật:** <br> - **Module 05-Lab18:** Kích hoạt AWS Security Hub <br> - Phân tích các tiêu chuẩn tuân thủ (compliance) và các điểm yếu bảo mật <br> - Đánh giá điểm số an ninh và dọn dẹp tài nguyên sau lab | 27/5/2026 | 27/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Lab tự động hóa Serverless:** <br> - Thiết lập hạ tầng (VPC, EC2, Security Groups) <br> - Tích hợp Slack Webhooks để nhận thông báo <br> - Viết và triển khai hàm AWS Lambda để tự động hóa Start/Stop EC2 instance | 28/5/2026 | 28/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Lab quản trị tài nguyên và IAM:** <br> - Quản lý gắn nhãn (Tagging) và Resource Groups <br> - Thực hành lệnh AWS CLI với tags <br> - Cấu hình IAM chi tiết (User, Policy, Role) để phân quyền kiểm soát truy cập | 29/5/2026 | 29/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 6:

* **Thấm nhuần mô hình Trách nhiệm chung (Shared Responsibility Model)**, hiểu rõ ranh giới bảo mật giữa AWS và khách hàng để chủ động xây dựng chiến lược phòng thủ an toàn cho hệ thống.

* **Thành thạo cấu hình quản lý danh tính và quyền truy cập**, triển khai chính xác các thực thể IAM (users, groups, roles, policies) và tích hợp Amazon Cognito làm giải pháp định danh quy mô lớn cho ứng dụng.

* **Xây dựng khung quản trị bảo mật tập trung cho doanh nghiệp**, ứng dụng thành công AWS Organizations để phân tách tài khoản và sử dụng AWS Identity Center (SSO) để đồng bộ danh tính đăng nhập, giảm thiểu rủi ro bảo mật.

* **Tăng cường khả năng giám sát và mã hóa dữ liệu**, vận hành hiệu quả dịch vụ AWS KMS để bảo vệ khóa mã hóa và sử dụng AWS Security Hub làm bảng điều khiển trung tâm để theo dõi các lỗ hổng, đảm bảo hệ thống luôn tuân thủ các tiêu chuẩn an toàn.

* **Sáng tạo các quy trình vận hành tự động (Automation Workflow)**, xây dựng hệ thống serverless sử dụng AWS Lambda để tự động quản lý vòng đời EC2 instance (Start/Stop), kết hợp với thông báo real-time qua Slack giúp tối ưu hóa nhân lực vận hành.

* **Kiện toàn năng lực quản trị tài nguyên theo tiêu chuẩn (Governance)**, áp dụng chặt chẽ chính sách đặt Tag để phân loại, lọc và tổ chức hạ tầng quy mô lớn qua Resource Groups, giúp việc truy vết và quản lý tài nguyên trở nên khoa học.

* **Nâng cao kỹ năng phân quyền chi tiết (IAM Administration)**, thiết lập các IAM Policy và Role tinh chỉnh, tuân thủ nghiêm ngặt nguyên tắc đặc quyền tối thiểu (Principle of Least Privilege), đảm bảo an ninh cho toàn bộ tài nguyên phòng Lab.
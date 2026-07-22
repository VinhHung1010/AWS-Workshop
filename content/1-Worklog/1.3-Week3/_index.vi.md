---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---



### Mục tiêu tuần 3:

* Nắm vững các mô hình định tuyến nâng cao giữa các VPC (VPC Peering, Transit Gateway) và kiến trúc máy chủ ảo EC2 cốt lõi bao gồm tính năng tự động mở rộng (Auto Scaling).
* Tích lũy kinh nghiệm thực tế về triển khai chính sách bảo vệ dữ liệu (AWS Backup), tích hợp lưu trữ hỗn hợp (Storage Gateway) và các tính năng quản lý đối tượng chuyên sâu (Bảo mật S3, Versioning và Replication).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Hoàn thành các bài Lab về VPC Peering và Tự động hóa:** <br> - **Lab 02-19.02.1 đến 02-19.02.3:** Khởi tạo CloudFormation để tự động hóa hạ tầng, thiết lập Security Groups và deploy các thực thể EC2 để test mạng <br> - **Lab 02-19.03 đến 02-19.07:** Cấu hình lại NACLs, thiết lập kết nối Peering, cập nhật Route Tables, kích hoạt Cross-Peer DNS và thực hiện dọn dẹp tài nguyên | 4/5/2026 | 4/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Hoàn thành chuỗi bài Lab về AWS Transit Gateway:** <br> - **Lab 02-Lab20-01 & 02-Lab20-02:** Nghiên cứu kiến trúc Transit Gateway và chuẩn bị trước các thông số cấu hình mạng <br> - **Lab 02-Lab20-03 đến 02-Lab20-07:** Khởi tạo Transit Gateway, thiết lập các VPC Attachments & Route Tables tập trung, cập nhật bảng định tuyến của từng VPC và dọn dẹp hệ thống | 5/5/2026 | 5/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Nghiên cứu lý thuyết Dịch vụ máy chủ EC2 cốt lõi (Module 03-01-01 đến 03-01-07):** <br> - Phân tích phân loại EC2 Instance Types phù hợp với từng loại workload, cơ chế AMI/Backup/Key Pair <br> - So sánh lưu trữ bền vững (EBS) với lưu trữ tốc độ cao tạm thời (Instance Store) <br> - Tìm hiểu cơ chế tự động hóa qua User Data/Metadata và khả năng co giãn tự động của EC2 Auto Scaling Groups | 6/5/2026 | 6/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Hoàn thành bài Lab Bảo vệ dữ liệu & Chuẩn bị lưu trữ:** <br> - **Module 03-Lab13-01 đến 03-Lab13-06:** Triển khai dịch vụ AWS Backup, tạo Backup Plan tự động (thiết lập chu kỳ, retention chính sách), thực hành phục hồi kiểm tra toàn vẹn dữ liệu và xóa tài nguyên thử nghiệm <br> - **Module 03-Lab24-01.1 & 01.2:** Khởi tạo Amazon S3 Bucket và deploy máy chủ EC2 đóng vai trò Storage Gateway | 7/5/2026 | 7/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Hoàn thành bài Lab Storage Gateway & S3 Static Web Hosting:** <br> - **Module 03-Lab24-02.1 & 02.2:** Cấu hình AWS Storage Gateway và thiết lập các File Shares chia sẻ dữ liệu (SMB/NFS) <br> - **Module 03-Lab57-02.1 đến 05:** Khởi tạo các S3 bucket, tải dữ liệu lên, kích hoạt tính năng Host Website tĩnh và điều chỉnh quyền truy cập public | 8/5/2026 | 8/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 7   | **Hoàn thành bài Lab Bảo mật S3 & Quản lý nâng cao:** <br> - **Module 03-Lab57-06 đến 07.3:** Kiểm thử truy cập website, thực hành bật tính năng S3 Block Public Access để khóa toàn bộ truy cập từ ngoài và rà soát Bucket Policies <br> - **Module 03-Lab57-08 đến 11:** Kích hoạt S3 Bucket Versioning để quản lý phiên bản, điều hướng thư mục, thiết lập Replication sao chép dữ liệu chéo bucket và dọn dẹp tài nguyên | 9/5/2026 | 9/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 3:

* **Làm chủ các mô hình liên kết mạng đa VPC và điều phối dữ liệu tập trung**, có kinh nghiệm thực tế sâu sắc trong việc cấu hình kết nối ngang hàng VPC Peering và triển khai hệ thống AWS Transit Gateway đóng vai trò làm hub trung tâm để quản lý định tuyến, kết nối giữa nhiều VPC một cách bảo mật.

* **Đạt được hiểu biết vững chắc về kiến trúc tính toán máy chủ EC2 trên AWS**, biết cách lựa chọn dòng máy chủ tối ưu hiệu năng và chi phí theo từng bài toán doanh nghiệp, hiểu rõ cơ chế phục hồi hệ thống qua AMI, tự động hóa cấu hình khởi tạo qua User Data/Metadata, và thiết lập hạ tầng sẵn sàng cao với EC2 Auto Scaling Groups.

* **Triển khai thành công cơ chế bảo vệ dữ liệu tập trung**, ứng dụng giải pháp AWS Backup để thiết lập các chính sách sao lưu tự động và kiểm thử thành công quy trình khôi phục dữ liệu (restore point) nhằm đảm bảo phương án khắc phục sự cố luôn sẵn sàng.

* **Xây dựng thành thạo giải pháp lưu trữ hỗn hợp kết hợp với on-premises**, cấu hình hoàn chỉnh hệ thống AWS Storage Gateway và phân bổ các file share theo chuẩn SMB/NFS giúp đồng bộ dữ liệu cục bộ lên nền tảng đám mây một cách mượt mà.

* **Thành thạo kỹ năng quản trị dịch vụ lưu trữ đối tượng Amazon S3**, khởi tạo thành công hệ thống lưu trữ và quản lý tập tin cấu trúc, kích hoạt tính năng static website hosting và cấu hình phân quyền truy cập public chính xác cho các ứng dụng web.

* **Tối ưu hóa và thắt chặt an toàn thông tin lớp lưu trữ**, thực hành áp dụng thành công bộ chặn S3 Block Public Access và tinh chỉnh chuyên sâu các chính sách Bucket Policy để bảo vệ tài nguyên đối tượng trước các nguy cơ truy cập trái phép.

* **Triển khai các phương án dự phòng và quản lý vòng đời dữ liệu trên S3**, cấu hình thành công S3 Bucket Versioning giúp lưu trữ nhiều phiên bản của đối tượng chống lại việc vô tình sửa đổi, xóa nhầm, đồng thời cài đặt tính năng Replication tự động đồng bộ hóa chéo giữa các bucket để tăng cường tính sẵn sàng cao.

* **Duy trì tốt tư duy tối ưu chi phí vận hành đám mây**, liên tục tiến hành rà soát, dọn dẹp sạch sẽ toàn bộ tài nguyên sau mỗi bài lab thử nghiệm (bao gồm các thực thể máy chủ, nhóm bảo mật, cổng Transit Gateway, các phân vùng mạng Peering và các thùng lưu trữ) để tránh phát sinh chi phí ngoài ý muốn.
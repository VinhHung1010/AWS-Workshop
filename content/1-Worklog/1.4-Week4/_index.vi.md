---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---



### Mục tiêu tuần 4:

* Nắm vững kiến trúc tối ưu hóa lưu trữ nâng cao trên Amazon S3 (Access Points, Storage Classes, CORS) và các cơ chế di chuyển dữ liệu quy mô lớn của doanh nghiệp (Snow Family).
* Tích lũy kinh nghiệm thực tế về quản trị sao lưu tự động đa tài nguyên, quy trình di chuyển máy chủ ảo (VM) từ on-premises lên AWS và tích hợp giải pháp Hybrid Storage Gateway.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Nghiên cứu kiến trúc tối ưu hóa và lưu trữ hỗn hợp AWS:** <br> - **Module 04-02:** Phân tích giải pháp đơn giản hóa quyền truy cập qua S3 Access Points và phân loại đặc tính các dòng S3 Storage Classes (Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, các dòng Glacier) để tối ưu chi phí <br> - **Module 04-03:** Khảo sát tính năng Host Static Website trên S3, cấu hình chia sẻ tài nguyên chéo tên miền CORS, các cơ chế kiểm soát truy cập (IAM, Bucket Policies, ACLs) và tối ưu hiệu suất đọc ghi <br> - **Module 04-04:** Tìm hiểu bộ giải pháp di chuyển phần cứng Snow Family, kiến trúc Storage Gateway và dịch vụ AWS Backup | 11/5/2026 | 11/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Hoàn thành bài Lab quản lý sao lưu toàn diện với AWS Backup:** <br> - **Module 04-Lab13-02.1 & 02.2:** Khởi tạo S3 Bucket làm vùng chứa và deploy hạ tầng phục vụ kiểm thử sao lưu <br> - **Module 04-Lab13-03 đến 06:** Thiết lập Backup Plans tự động (chu kỳ, thời gian lưu trữ), cấu hình dịch vụ thông báo trạng thái Job, thực hành khôi phục dữ liệu từ điểm phục hồi để kiểm tra tính toàn vẹn và giải phóng tài nguyên hệ thống | 12/5/2026 | 12/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Hoàn thành bài Lab di chuyển máy chủ ảo (VM) từ cục bộ lên đám mây:** <br> - **Module 04-Lab14-01 & 14-02.1:** Thiết lập môi trường ảo hóa VMware Workstation và xuất tệp tin cấu hình máy chủ ảo <br> - **Module 04-Lab14-02.2 đến 02.4:** Tải các tệp tin máy ảo lên S3, sử dụng dịch vụ VM Import/Export chuyển đổi máy ảo thành một AMI tùy chỉnh và khởi chạy máy chủ EC2 thực tế từ AMI đó <br> - **Module 04-Lab14-03.1 đến 05:** Cấu hình phân quyền S3 Bucket ACL phục vụ migrate, thực hành xuất ngược một EC2 instance thành định dạng máy ảo cục bộ và tiến hành dọn dẹp hệ thống | 13/5/2026 | 13/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Thực hành chuyên sâu và củng cố quy trình di chuyển máy chủ ảo (VM Workflow):** <br> - Rà soát và tái hiện toàn bộ quy trình lab dịch chuyển hạ tầng (**Từ Module 04-Lab14-02.1 đến Module 04-Lab14-05**) <br> - Củng cố vững chắc các bước xuất máy ảo tại local, upload tệp tin ổ đĩa lên S3 bucket, biên dịch tệp tin thành AMI hoàn chỉnh, cấu hình quyền S3 bucket ACL phục vụ tiến trình dịch chuyển dữ liệu bảo mật và hủy các tài nguyên tạm thời | 14/5/2026 | 14/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Hoàn thành bài Lab tích hợp lưu trữ hỗn hợp với Storage Gateway:** <br> - **Module 04-Lab24-2.1 & 24-2.2:** Khởi tạo cấu hình AWS Storage Gateway và thiết lập các File Shares chia sẻ dữ liệu đám mây <br> - **Module 04-Lab24-2.3 & 24-3:** Thực hành mount trực tiếp các cổng chia sẻ dữ liệu đám mây về môi trường máy chủ on-premises (theo chuẩn SMB/NFS) và thực hiện dọn dẹp sạch sẽ tài nguyên bài lab | 15/5/2026 | 15/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 4:

* **Làm chủ chiến lược tối ưu hóa chi phí và quản lý phân vùng dữ liệu nâng cao trên Amazon S3**, hiểu rõ cách triển khai S3 Access Points để đơn giản hóa chính sách truy cập cho đa ứng dụng và biết cách luân chuyển dữ liệu tự động giữa các lớp S3 Storage Classes nhằm tối ưu ngân sách hạ tầng.

* **Thành thạo giải pháp bảo mật và phân phối nội dung qua lưu trữ đối tượng**, có khả năng cấu hình máy chủ web tĩnh (static website hosting) an toàn, xử lý triệt để xung đột tài nguyên chéo tên miền bằng cấu hình CORS, phối hợp đa lớp bảo mật gồm IAM Policy, Bucket Policy, ACLs và Block Public Access.

* **Tiếp thu nền tảng kiến thức về di chuyển dữ liệu quy mô lớn và lưu trữ đám mây kết hợp**, hiểu sâu về các kịch bản áp dụng dòng phần cứng AWS Snow Family (Snowcone, Snowball Edge, Snowmobile) khi băng thông mạng bị hạn chế và hiểu cách ứng dụng Storage Gateway cho các mô hình doanh nghiệp lớn.

* **Triển khai thành công hệ thống bảo vệ dữ liệu tự động và giám sát tập trung**, vận dụng AWS Backup để thiết lập lịch trình sao lưu nghiêm ngặt, cấu hình thành công dịch vụ gửi thông báo tự động (Notification Services) để kiểm soát các tác vụ và thực hiện khôi phục (restore) kiểm tra toàn vẹn hệ thống cứu hộ.

* **Thực hiện trọn vẹn quy trình dịch chuyển hạ tầng chuẩn doanh nghiệp (Cloud Migration Workflow)**, chuyển đổi thành công hệ thống máy chủ ảo từ môi trường ảo hóa cục bộ VMware Workstation lên đám mây AWS bằng dịch vụ VM Import/Export, chuyển đổi tệp tin ổ đĩa thành Amazon Machine Image (AMI) và khởi chạy máy chủ EC2 hoạt động ổn định.

* **Làm chủ quy trình kiểm soát quyền truy cập tài nguyên chéo môi trường**, cấu hình chính xác các thông số S3 Bucket ACLs phức tạp để cấp quyền cho tiến trình dịch chuyển dữ liệu máy ảo giữa hạ tầng on-premises và hạ tầng đám mây một cách an toàn.

* **Xây dựng hoàn chỉnh mô hình lưu trữ hỗn hợp (Hybrid Cloud Storage Solution)**, triển khai thành công AWS Storage Gateway đóng vai trò cầu nối dữ liệu, mount trực tiếp các ổ đĩa đám mây về máy cục bộ qua giao thức mạng SMB/NFS và xác thực khả năng đồng bộ dữ liệu song song.

* **Duy trì tốt tư duy quản trị tài nguyên và tối ưu hóa ngân sách đám mây**, thực hiện quy trình dọn dẹp môi trường (cleanup) nghiêm ngặt sau khi kết thúc thử nghiệm (xóa bỏ máy chủ EC2 test, hủy các AMI tạm, dọn dẹp các tệp tin đĩa ảo nặng trên S3 và gỡ bỏ Storage Gateway appliance) nhằm ngăn chặn việc phát sinh các chi phí ngoài ý muốn trên tài khoản AWS.
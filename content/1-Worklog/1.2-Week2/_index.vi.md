---
title: "Worklog Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---



### Mục tiêu tuần 2:

* Nắm vững các tùy chọn kết nối mạng nâng cao của AWS, tích hợp điện toán đám mây kết hợp (hybrid cloud) và các dịch vụ cân bằng tải để đảm bảo tính sẵn sàng cao.
* Tích lũy kinh nghiệm thực hành toàn diện thông qua các bài lab về xây dựng hạ tầng VPC bảo mật, định tuyến DNS hỗn hợp qua Route 53 và tự động hóa hạ tầng bằng CloudFormation.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu Site-to-Site VPN và Client-to-Site VPN để thiết lập các kết nối bảo mật <br> - Tìm hiểu AWS Direct Connect giúp cung cấp mạng riêng kết nối chuyên dụng giữa hạ tầng on-premises và AWS <br> - Học cơ chế hoạt động và phân loại Elastic Load Balancing (ELB): bao gồm Application Load Balancer (ALB - Layer 7), Network Load Balancer (NLB - Layer 4), Classic Load Balancer (CLB - Legacy) và Gateway Load Balancer (GWLB - quản lý thiết bị tường lửa bên thứ ba) | 27/4/2026 | 27/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Hoàn thành các bài Lab thuộc Module 02:** <br> - **Lab 03-01:** Giới thiệu về Amazon VPC & AWS Site-to-Site VPN <br> - **Lab 03-01.1 đến 03-01.4:** Cấu hình Subnets (Public/Private), Route Tables, Internet Gateway (IGW), và NAT Gateway <br> - **Lab 03-02.1 đến 03-02.3:** Thực hành Security Groups, Network ACLs (NACLs) và trực quan hóa hệ thống bằng VPC Resource Map | 28/4/2026 | 28/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Hoàn thành chuỗi bài Lab thiết lập hạ tầng và triển khai EC2:** <br> - **Lab 03.1 & 03.2:** Khởi tạo mạng VPC và thiết kế các dải subnet public/private (phân bổ dải CIDR) <br> - **Lab 03.3 & 03.4:** Thiết lập IGW và cấu hình Route Table điều phối luồng traffic đi ra internet <br> - **Lab 03.5 & 04.1:** Triển khai Security Groups và khởi chạy các instance EC2 nằm trong các subnet tùy chỉnh | 29/4/2026 | 29/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Hoàn thành chuỗi bài Lab kiểm thử kết nối và tự động hóa:** <br> - **Lab 03-04.2 & 03-04.3:** Kiểm tra kết nối giữa các EC2 và cấu hình NAT Gateway bảo mật cho subnet private <br> - **Lab 03-04.5:** Thiết lập kết nối từ xa an toàn qua EC2 Instance Connect Endpoint <br> - **Lab 02-10.01 đến 02-10.02.3:** Cấu hình Hybrid DNS với Route 53, khởi tạo Key Pair, deploy tự động hóa hạ tầng bằng AWS CloudFormation và tối ưu hóa Security Groups | 30/4/2026 | 30/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Hoàn thành chuỗi bài Lab Hybrid DNS Endpoints & VPC Peering:** <br> - **Lab 02-10.05 đến 02-10.05.4:** Thiết lập dịch vụ DNS, tạo Route 53 Outbound/Inbound Endpoints, cấu hình Resolver Rules và kiểm thử phân giải tên miền chéo môi trường <br> - **Lab 02-10.06:** Tiến hành dọn dẹp các tài nguyên đã tạo để tối ưu chi phí <br> - **Lab 02-15.01 & 02-19.02.1:** Thiết lập kết nối VPC Peering và tự động hóa khởi tạo bằng CloudFormation | 1/5/2026 | 1/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 2:

* **Nắm vững tư duy thiết kế kết nối hỗn hợp và điều phối lưu lượng truy cập trên AWS**, hiểu sâu về cách vận dụng Site-to-Site VPN, Client-to-Site VPN, Direct Connect cùng các giải pháp cân bằng tải (ALB, NLB, CLB, GWLB) để xây dựng hệ thống có tính sẵn sàng cao và khả năng mở rộng tốt.

* **Hoàn thành xuất sắc toàn bộ các bài thực hành từ Module 02 (Lab 03-01 đến Lab 03-02.3)**, tự tay thiết kế và cấu hình hoàn chỉnh một mô hình kiến trúc VPC tiêu chuẩn đáp ứng đầy đủ yêu cầu phân tách phân vùng mạng, định tuyến dữ liệu nội bộ và ra internet.

* **Thành thạo kỹ năng quản trị bảo mật mạng lớp sâu**, làm chủ cơ chế thiết lập bộ quy tắc tường lửa tại cấp độ thực thể (Security Groups - stateful) và cấp độ phân vùng mạng (NACLs - stateless), biết sử dụng công cụ trực quan VPC Resource Map để bao quát toàn diện sơ đồ liên kết hệ thống.

* **Nâng cao năng lực kiểm thử kết nối và quản trị truy cập từ xa an toàn**, thực hiện rà soát đường truyền mạng thông qua SSH, triển khai thành công EC2 Instance Connect Endpoint để quản trị trực tiếp các máy chủ trong mạng private mà không cần cấp phát IP public, loại bỏ hoàn toàn rủi ro lộ lọt thông tin.

* **Tiếp cận và ứng dụng thành thạo giải pháp Tự động hóa hạ tầng (IaC)**, biết cách viết và khởi chạy các template AWS CloudFormation để tự động hóa quy trình phân bổ tài nguyên hệ thống cũng như thiết lập các kết nối liên kết vùng VPC Peering một cách nhanh chóng và chính xác.

* **Xây dựng giải pháp DNS hỗn hợp (Hybrid DNS) chuyên sâu qua Amazon Route 53**, triển khai thành công các cổng phân giải Inbound/Outbound Endpoints phối hợp cùng các bộ Resolver Rules tùy chỉnh, đảm bảo hệ thống on-premises và môi trường AWS có thể phân giải tên miền qua lại lẫn nhau một cách mượt mà.

* **Hình thành tư duy tối ưu hóa chi phí vận hành đám mây**, tuân thủ nghiêm ngặt quy trình dọn dẹp và xóa bỏ tài nguyên dư thừa (Clean up Resources) sau khi hoàn thành thử nghiệm, đảm bảo tài khoản không phát sinh các chi phí ngoài ý muốn.
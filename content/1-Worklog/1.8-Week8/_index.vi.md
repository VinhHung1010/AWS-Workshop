---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---



### Mục tiêu tuần 8:

* Nắm vững các mô hình thiết kế cơ sở dữ liệu nền tảng và nâng cao trên đám mây, so sánh tải xử lý giao dịch (OLTP) và phân tích dữ liệu (OLAP) trên các nền tảng cơ sở dữ liệu quan hệ được quản trị và giải pháp bộ nhớ đệm in-memory.
* Tích lũy kinh nghiệm thực tế về chuẩn bị hạ tầng mạng biệt lập và triển khai bảo mật mô hình ứng dụng đa tầng hướng cơ sở dữ liệu (EC2-to-RDS) trên AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Hệ thống hóa kiến thức Cơ sở dữ liệu:** <br> - Xem xét các khái niệm nền tảng về cơ sở dữ liệu quan hệ (Relational) và phi quan hệ (Non-relational) <br> - Nghiên cứu sâu về khóa chính (primary keys), khóa ngoại (foreign keys), chỉ mục (indexes) và các ràng buộc dữ liệu <br> - So sánh đặc tính của hai mô hình xử lý dữ liệu OLTP và OLAP cùng kiến trúc triển khai cloud | 8/6/2026 | 8/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Nghiên cứu Hệ quản trị Cơ sở dữ liệu quan hệ AWS:** <br> - Tìm hiểu dịch vụ cơ sở dữ liệu được quản trị hoàn toàn Amazon RDS <br> - Khảo sát kiến trúc và lợi thế vượt trội về hiệu năng của Amazon Aurora <br> - Nghiên cứu cơ chế sẵn sàng cao Multi-AZ, thiết lập bản sao mở rộng vùng đọc (Read Replicas), quy trình backup và khôi phục thảm họa | 9/6/2026 | 9/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Kiến trúc Kho dữ liệu & Bộ nhớ đệm:** <br> - Tìm hiểu giải pháp kho dữ liệu đám mây Amazon Redshift phục vụ phân tích dữ liệu doanh nghiệp lớn <br> - Nghiên cứu dịch vụ bộ nhớ đệm Amazon ElastiCache (sử dụng Redis và Memcached) và các chiến lược caching giúp giảm tải xử lý, tối ưu hóa độ trễ cho cơ sở dữ liệu | 10/6/2026 | 10/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Hoàn thành bài Lab thiết lập hạ tầng mạng cho RDS:** <br> - **Module 06-Lab05-2.1 đến 2.4:** Cấu hình các thành phần mạng cần thiết cho Amazon RDS trong mạng VPC, khởi tạo các nhóm bảo mật (Security Groups) chuyên dụng cho EC2 và cơ sở dữ liệu, đồng thời phân bổ DB Subnet Groups | 11/6/2026 | 11/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Hoàn thành bài Lab triển khai Ứng dụng đa tầng và Cơ sở dữ liệu:** <br> - **Module 06-Lab05-3 đến 5:** Khởi chạy máy chủ EC2 host ứng dụng, tạo cơ sở dữ liệu Amazon RDS nằm trong dải DB Subnet Group bảo mật, mở quyền kết nối chéo tầng qua quy tắc Security Group và deploy ứng dụng mẫu <br> - **Module 06-Lab05-6 & 7:** Thực hành kiểm thử sao lưu/phục hồi (Backup & Restore) xác thực khả năng khôi phục thảm họa, tiến hành dọn dẹp và giải phóng tài nguyên | 12/6/2026 | 12/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 8:

* **Củng cố vững chắc các kiến thức nền tảng về kỹ nghệ cơ sở dữ liệu**, phân biệt rõ cấu trúc lược đồ dạng bảng quan hệ và phi quan hệ, cơ chế ràng buộc dữ liệu toàn vẹn, và các kịch bản áp dụng tối ưu cho hệ thống giao dịch thời gian thực (OLTP) so với kho dữ liệu phân tích (OLAP).

* **Đạt được tư duy lý thuyết sâu sắc về các giải pháp quản trị database trên mây**, hiểu rõ khả năng mở rộng linh hoạt của dịch vụ Amazon RDS và các kiến trúc lưu trữ/sao chép dữ liệu vượt trội của giải pháp đám mây Amazon Aurora.

* **Lĩnh hội kiến trúc lưu trữ dữ liệu lớn và giải pháp giảm thiểu độ trễ hệ thống**, nắm rõ cách thức tổ chức kho dữ liệu phân tích doanh nghiệp quy mô lớn qua Amazon Redshift và cách áp dụng tầng bộ nhớ đệm Amazon ElastiCache (Redis/Memcached) giúp giải phóng hàng loạt tác vụ truy vấn trùng lặp cho database gốc.

* **Thực hiện thiết kế phân vùng mạng biệt lập an toàn cho lớp lưu trữ**, tạo lập thành công các DB Subnet Groups phân bổ chéo các Availability Zones riêng tư, thiết lập bộ lọc quy tắc tường lửa (Security Groups) đa lớp chặt chẽ giúp ngăn chặn mọi hành vi truy cập trực tiếp trái phép từ internet vào database.

* **Triển khai thành công mô hình hạ tầng ứng dụng hướng cơ sở dữ liệu hoàn chỉnh trên AWS**, tích hợp thành thạo máy chủ web ứng dụng chạy trên Amazon EC2 kết nối mượt mà và bảo mật đến phân tầng lưu trữ dữ liệu được quản trị trên Amazon RDS.

* **Làm chủ quy trình vận hành bảo vệ an toàn thông tin dữ liệu và khôi phục thảm họa**, thực hành thành công việc tạo các bản snapshot sao lưu thủ công, rà soát tính năng tự động sao lưu của RDS, đồng thời tiến hành khôi phục (restore) toàn vẹn hệ thống để đảm bảo ứng dụng không bị mất mát dữ liệu hoặc gián đoạn hoạt động.

* **Tuân thủ xuất sắc các quy chuẩn tối ưu hóa chi phí và quản trị tài nguyên**, triển khai quy trình dọn dẹp hệ thống (cleanup) nghiêm ngặt sau khi kết thúc thử nghiệm (hủy bỏ thực thể máy chủ ứng dụng, gỡ bỏ hoàn toàn database RDS test cùng các cấu hình mạng liên quan) để bảo vệ tài khoản không phát sinh cước phí ngoài ý muốn.
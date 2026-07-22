---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---



### Mục tiêu tuần 5:

* Làm chủ quy trình triển khai hệ thống tệp tin doanh nghiệp lớn bằng Amazon FSx, tập trung vào kiến trúc sẵn sàng cao Multi-AZ, quản trị tài nguyên, co giãn dung lượng và kỹ thuật tối ưu không gian lưu trữ.
* Nâng cao năng lực chuyên sâu về phân phối nội dung toàn cầu và tối ưu hóa ứng dụng web nhờ tích hợp bảo mật giữa dịch vụ lưu trữ website tĩnh S3 và mạng lưới CDN Amazon CloudFront.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Hoàn thành các bài Lab khởi tạo và tối ưu hóa Amazon FSx:** <br> - **Module 04-Lab25-2.2 & 25-2.3:** Cấu hình và triển khai hệ thống tệp tin doanh nghiệp lớn chuẩn Multi-AZ trên cả hai tùy chọn ổ đĩa SSD và HDD <br> - **Module 04-Lab25-3 & 25-4:** Khởi tạo các phân vùng chia sẻ dữ liệu tệp tin mới và tiến hành kiểm thử, đo lường hiệu năng lưu trữ hệ thống <br> - **Module 04-Lab25-5 & 25-6:** Giám sát các chỉ số hiệu suất của hệ thống và kích hoạt tính năng Data Deduplication để chống trùng lặp dữ liệu | 18/5/2026 | 18/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Hoàn thành bài Lab quản trị nâng cao và co giãn tài nguyên FSx:** <br> - **Module 04-Lab25-7 đến 25-9:** Kích hoạt tính năng Shadow Copies phục vụ sao lưu phục hồi nhanh, quản lý các phiên làm việc của người dùng (user sessions), kiểm soát tệp tin đang mở và thiết lập hạn ngạch lưu trữ cho người dùng (user storage quotas) <br> - **Module 04-Lab25-11 đến 25-13:** Thực hành mở rộng linh hoạt băng thông thông lượng (throughput) và dung lượng bộ nhớ, sau đó tiến hành xóa bỏ môi trường để hoàn tất bài lab | 19/5/2026 | 19/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Hoàn thành chuỗi bài Lab lưu trữ Website tĩnh trên Amazon S3:** <br> - **Module 04-Lab57-2.1 & 57-2.2:** Khởi tạo các S3 Bucket chuyên dụng và tải các đối tượng dữ liệu của mã nguồn website lên hệ thống <br> - **Module 04-Lab57-3 đến 57-6:** Kích hoạt tính năng Static Website Hosting, cấu hình mở cài đặt truy cập công khai (Public Access) kết hợp phân quyền đối tượng và kiểm thử truy cập thành công website thực tế | 20/5/2026 | 20/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Hoàn thành bài Lab cấu hình mạng phân phối nội dung CloudFront & Bảo mật S3:** <br> - **Module 04-Lab57-7.1:** Thắt chặt an toàn thông tin bằng cách kích hoạt tính năng S3 Block Public Access để khóa toàn bộ truy cập công khai trực tiếp vào bucket <br> - **Module 04-Lab57-7.2 & 57-7.3:** Tạo lập và cấu hình hệ thống phân phối dữ liệu Amazon CloudFront, kiểm thử luồng đi của dữ liệu qua CDN và bật tính năng quản lý phiên bản đối tượng S3 Bucket Versioning | 21/5/2026 | 21/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Hoàn thành bài Lab cấu hình sao chép đa vùng S3 và dọn dẹp hệ thống:** <br> - **Module 04-Lab57-9 & 57-10:** Thực hiện tổ chức, điều hướng và di chuyển các đối tượng bên trong bucket, thiết lập tính năng tự động sao chép đối tượng đa vùng dữ liệu chéo (Replication Object Multi Region) <br> - **Module 04-Lab57-11:** Tiến hành giải phóng và xóa bỏ toàn bộ tài nguyên lưu trữ để tối ưu hóa tài khoản | 22/5/2026 | 22/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 5:

* **Lĩnh hội sâu sắc kiến trúc triển khai hệ thống tệp tin doanh nghiệp lớn Amazon FSx**, thực hành cấu hình thành công mô hình lưu trữ sẵn sàng cao đa vùng (Multi-AZ) trên cả phân tầng ổ đĩa hiệu năng cao SSD và phân tầng lưu trữ tối ưu chi phí HDD.

* **Làm chủ các giải pháp quản trị hiệu suất lưu trữ nâng cao**, ứng dụng thành thạo cơ chế loại bỏ dữ liệu trùng lặp (Data Deduplication) nhằm giải phóng không gian bộ nhớ ảo, đồng thời thiết lập hệ thống cảnh báo, giám sát dữ liệu thông lượng để kiểm soát tải.

* **Đạt được năng lực quản trị hệ thống lưu trữ cấp độ doanh nghiệp**, thuần thục các kỹ thuật tạo bản sao bóng (Shadow Copies) phục vụ cứu hộ dữ liệu nhanh, kiểm soát chặt chẽ phiên kết nối của người dùng, quản lý trạng thái tệp tin đang mở và phân bổ hạn ngạch dung lượng (storage quotas) hợp lý cho từng nhóm tài khoản.

* **Nâng cao kỹ năng điều phối co giãn hạ tầng linh hoạt**, thực hiện thành công các thao tác thay đổi và mở rộng quy mô thông lượng (throughput capacity) cũng như mở rộng bộ nhớ lưu trữ của FSx một cách an toàn mà không làm gián đoạn hệ thống.

* **Thành thạo quy trình triển khai hạ tầng Web-hosting trên đám mây**, làm chủ các bước thiết lập phân vùng lưu trữ tĩnh thông qua Amazon S3, cấu hình tinh chỉnh các ranh giới cấp quyền truy cập đối tượng, giúp đẩy nhanh tiến độ xuất bản ứng dụng front-end lên internet.

* **Tối ưu hóa tốc độ và thắt chặt an toàn hạ tầng bằng mạng lưới phân phối nội dung (CDN)**, tích hợp thành công Amazon CloudFront để tăng tốc độ tải trang toàn cầu cho website S3, đồng thời cô lập vùng lưu trữ gốc bằng bộ khóa bảo mật S3 Block Public Access để ngăn chặn các lỗ hổng rò rỉ dữ liệu trực tiếp.

* **Triển khai toàn vẹn các phương án dự phòng và khắc phục thảm họa lớp lưu trữ đối tượng**, vận dụng tính năng S3 Versioning để khôi phục nhanh các tập tin bị ghi đè, phối hợp cùng cơ chế cấu hình tự động đồng bộ hóa đa vùng chéo địa lý (Multi-Region Replication) nhằm đảm bảo tính sống còn cho dữ liệu hệ thống.

* **Tuân thủ xuất sắc các quy chuẩn tối ưu hóa chi phí đám mây**, thực hiện quy trình rà soát và hủy bỏ tài nguyên bài lab (clean up) một cách bài bản (xóa môi trường FSx, gỡ bỏ phân phối CloudFront CDN, làm sạch dữ liệu trong bucket) bảo vệ tài khoản không phát sinh cước phí ngoài ý muốn.
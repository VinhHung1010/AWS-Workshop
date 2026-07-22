---
title: "Worklog Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---



### Mục tiêu tuần 12:

* Làm chủ quy trình xây dựng đường ống ETL nâng cao và tự động hóa trích xuất siêu dữ liệu thông qua các công cụ chuyên sâu bao gồm AWS Glue Interactive Sessions, giao diện đồ họa GUI và AWS Glue DataBrew.
* Triển khai giải pháp xử lý dữ liệu lớn quy mô phân tán, phân tích dữ liệu luồng kết hợp và thiết lập tầng phân phối dữ liệu không máy chủ thông qua Amazon EMR, Amazon Athena và Amazon Kinesis.
* Hoàn thiện chuỗi giá trị phân tích dữ liệu cấp doanh nghiệp bằng cách xây dựng hệ thống kho dữ liệu đám mây với Amazon Redshift và các bảng báo cáo thông minh trực quan tương tác cao trên Amazon QuickSight.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Chuẩn bị Dữ liệu Trực quan & Định hình Cấu trúc:** <br> - Cấu hình công cụ AWS Glue DataBrew và khởi chạy tiến trình định hình dữ liệu (data profiling) <br> - Tiến hành làm sạch các tập dữ liệu, xử lý triệt để các giá trị bị thiếu (missing values) hoặc không nhất quán <br> - Áp dụng các bộ quy tắc chuyển đổi (transformation recipes) và kiểm thử chất lượng dữ liệu | 06/07/2026 | 06/07/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Thu thập Dữ liệu Phân tích & Quản lý Siêu dữ liệu:** <br> - Thiết lập các bước chuẩn bị cho môi trường phân tích nâng cao <br> - Thực hiện thu thập và lưu trữ đồng bộ các tập dữ liệu lớn vào các vùng chứa Amazon S3 <br> - Khởi tạo lập danh mục dữ liệu và trích xuất siêu dữ liệu tập trung bằng AWS Glue Data Catalog | 07/07/2026 | 07/07/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Xây dựng Đường ống ETL Đa phương thức:** <br> - Thực thi các tác vụ biến đổi dữ liệu ETL lập trình chuyên sâu thông qua AWS Glue Interactive Sessions <br> - Thiết kế quy trình biến đổi dữ liệu trực quan trên giao diện đồ họa (GUI) của AWS Glue Studio <br> - Phối hợp xử lý và tối ưu hóa cấu trúc tập dữ liệu bằng AWS Glue DataBrew để so sánh các giải pháp | 08/07/2026 | 08/07/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Xử lý Dữ liệu Lớn Phân tán & Phân tích Thời gian thực:** <br> - Triển khai xử lý các tập dữ liệu dung lượng lớn qua cụm Spark phân tán bằng Amazon EMR <br> - Thực thi các câu lệnh truy vấn SQL kiểm tra dữ liệu nhanh với Amazon Athena <br> - Thiết lập phân tích luồng dữ liệu thời gian thực (streaming analytics) bằng Amazon Kinesis Data Analytics | 09/07/2026 | 09/07/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Kho Dữ liệu Doanh nghiệp & Trực quan hóa Báo cáo Quản trị (BI):** <br> - Triển khai mã nguồn không máy chủ AWS Lambda đóng vai trò trung chuyển, phục vụ dữ liệu <br> - Thực hiện tải các tập dữ liệu phân tích sạch vào kho dữ liệu đám mây Amazon Redshift <br> - Thiết kế hệ thống bảng điều khiển tương tác (Interactive Dashboards) đa chiều, cải tiến bộ lọc trên Amazon QuickSight | 10/07/2026 | 10/07/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 12:

* **Làm chủ các kỹ thuật chuẩn bị dữ liệu trực quan và tối ưu hóa chất lượng dữ liệu**, vận dụng thành thạo AWS Glue DataBrew để phân tích sâu phân phối dữ liệu, phát hiện bất thường, loại bỏ các giá trị nhiễu và đóng gói thành các bộ công thức biến đổi (recipes) tái sử dụng cao.

* **Triển khai thành công quy trình thu thập dữ liệu lớn chuẩn hóa**, tổ chức phân vùng hạ tầng lưu trữ đệm tối ưu trên Amazon S3, kết hợp với cơ chế quản lý siêu dữ liệu thông minh của AWS Glue Data Catalog để định hình mô hình dữ liệu (data cataloging) cho toàn dự án.

* **Kiện toàn năng lực phát triển hệ thống ETL toàn diện**, thành thạo cả 3 phương thức xử lý dữ liệu đám mây: viết mã lệnh chuyên sâu với AWS Glue Interactive Sessions, thiết kế trực quan no-code bằng giao diện đồ họa (GUI) và tinh chỉnh luồng dữ liệu qua DataBrew.

* **Đạt được kiến thức và kỹ năng thực tế về kiến trúc tính toán phân tán (Big Data Processing)**, vận hành thành công các cụm máy chủ Amazon EMR mạnh mẽ để tính toán xử lý các tập dữ liệu quy mô lớn một cách nhanh chóng.

* **Xây dựng mô hình phân tích dữ liệu lai kết hợp (Hybrid Cloud Analytics)**, làm chủ kỹ thuật truy vấn SQL không máy chủ tốc độ cao với Amazon Athena đối với dữ liệu tĩnh, song song với việc cấu hình Amazon Kinesis Data Analytics để khai thác thông tin từ dòng dữ liệu biến động theo thời gian thực.

* **Kiến tạo tầng phục vụ dữ liệu (Data Serving Layer) linh hoạt**, ứng dụng các hàm serverless AWS Lambda để tự động hóa luồng chuyển dữ liệu, nạp (load) các tập dữ liệu đã qua xử lý nghiêm ngặt vào hệ thống kho dữ liệu đám mây hiệu năng cao Amazon Redshift.

* **Hoàn thiện giải pháp Báo cáo Quản trị Doanh nghiệp Thông minh (Business Intelligence)**, kết nối mượt mà Amazon QuickSight với các kho dữ liệu, tự tay xây dựng các bộ Interactive Dashboards nâng cao tích hợp các thành phần trực quan và bộ lọc lọc dữ liệu đa góc nhìn, hỗ trợ đắc lực cho bài toán quản trị.

* **Khẳng định năng lực chuyên sâu trong toàn bộ vòng đời Kỹ nghệ Dữ liệu (Data Engineering Lifecycle)**, hiện thực hóa xuất sắc một chuỗi giá trị hoàn chỉnh: từ khâu Thu thập (Ingestion) -> Lưu trữ (Storage) -> Biến đổi/Đồng bộ (ETL/Cataloging) -> Tính toán hiệu năng cao (EMR/Athena) -> Kho dữ liệu (Warehousing) -> Trực quan hóa (BI Dashboard).
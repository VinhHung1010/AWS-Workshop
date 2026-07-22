---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---



### Mục tiêu tuần 10:

* Thiết kế và triển khai hoàn chỉnh một đường ống phân tích dữ liệu đám mây (Data Analytics Pipeline) toàn diện, từ thu thập dữ liệu luồng, tự động hóa lập danh mục, truy vấn không máy chủ, cho đến trực quan hóa báo cáo thông minh (BI).
* Tích lũy kinh nghiệm thực tế chuyên sâu trong việc tích hợp các dịch vụ phân tích cốt lõi của AWS bao gồm Kinesis Data Firehose, AWS Glue, Amazon Athena và Amazon QuickSight vào một luồng xử lý kỹ nghệ dữ liệu thống nhất.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Xây dựng Đường ống Thu thập Dữ liệu Luồng:** <br> - Khởi tạo một Amazon S3 bucket đóng vai trò làm vùng lưu trữ dữ liệu thô đầu vào <br> - Cấu hình đường truyền phân phối dữ liệu luồng thời gian thực bằng Amazon Kinesis Data Firehose <br> - Tạo lập các tập dữ liệu mẫu (sample data) để thực hành kiểm thử và xác thực luồng truyền tải dữ liệu mượt mà vào S3 | 22/6/2026 | 22/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Tự động hóa Khám phá Cấu trúc Dữ liệu:** <br> - Tạo lập một AWS Glue Crawler để tiến hành quét (scan) toàn bộ tập dữ liệu thô đang lưu trữ tại Amazon S3 <br> - Tự động trích xuất siêu dữ liệu (metadata) và đồng bộ sơ đồ bảng vào kho lưu trữ tập trung AWS Glue Data Catalog <br> - Rà soát và kiểm tra độ chính xác của cấu trúc bảng dữ liệu do bộ quét khám phá | 23/6/2026 | 23/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Vận hành Chu trình Xử lý Dữ liệu:** <br> - Đọc hiểu, phân tích và giải thích cấu trúc mã nguồn (code logic) được áp dụng trong quy trình xử lý dữ liệu hệ thống <br> - Định hình phân vùng S3 bucket đích làm nơi lưu trữ kết quả dữ liệu sau khi xử lý <br> - Thiết lập các kết nối phiên làm việc (session connections) cần thiết cho các dịch vụ xử lý và kích hoạt luồng chạy | 24/6/2026 | 24/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Truy vấn Dữ liệu Không máy chủ (Serverless Analytics):** <br> - Cấu hình dịch vụ Amazon Athena để thiết lập liên kết dữ liệu trực tiếp với phân tầng lưu trữ S3 <br> - Thực thi các câu lệnh truy vấn SQL tiêu chuẩn trực tiếp dựa trên cấu trúc bảng được ánh xạ từ AWS Glue Data Catalog <br> - Phân tích, rà soát và kiểm tra các tập dữ liệu lớn một cách nhanh chóng mà không cần quản trị máy chủ | 25/6/2026 | 25/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Trực quan hóa Dữ liệu BI & Quản trị Vòng đời:** <br> - Thiết lập kết nối dịch vụ trực quan hóa dữ liệu thông minh Amazon QuickSight với tập dữ liệu từ Athena <br> - Thiết kế các biểu đồ hiển thị và xây dựng bảng điều khiển tương tác (Dashboards) phục vụ báo cáo doanh nghiệp <br> - Thực hiện quy trình rà soát gỡ bỏ (clean up) toàn bộ tài nguyên bài lab để tối ưu chi phí | 26/6/2026 | 26/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 10:

* **Làm chủ kiến trúc thu thập dữ liệu luồng quy mô lớn (Streaming Ingestion)**, cấu hình thành thạo dịch vụ Amazon Kinesis Data Firehose giúp tự động gom cụm, chuyển đổi và phân phối liên tục luồng dữ liệu thời gian thực vào các kho chứa Amazon S3 một cách đáng tin cậy.

* **Thành thạo giải pháp quản lý siêu dữ liệu và tự động hóa trích xuất cấu trúc (Data Cataloging)**, vận dụng chính xác công cụ AWS Glue Crawler để tự động quét qua các kho dữ liệu thô phức tạp, nhận diện định dạng tệp tin và xây dựng kho từ điển dữ liệu tập trung trên AWS Glue Data Catalog.

* **Nâng cao năng lực kiểm soát luồng mã nguồn xử lý dữ liệu**, hiểu sâu về logic vận hành của các tập lệnh xử lý, thiết lập thành công các kết nối session bảo mật kết nối chéo dịch vụ và tổ chức phân vùng lưu trữ kết quả đầu ra khoa học trên S3.

* **Triển khai thuần thục giải pháp khai thác dữ liệu không máy chủ (Serverless Data Querying)**, ứng dụng công cụ Amazon Athena để thực thi trực tiếp các câu lệnh truy vấn SQL nâng cao trên nền dữ liệu lớn lưu trữ tại S3, tối ưu tốc độ trích xuất thông tin mà không cần phân bổ tài nguyên phần cứng.

* **Xây dựng thành công giải pháp Báo cáo quản trị thông minh (Business Intelligence)**, kết nối mượt mà Amazon QuickSight vào các phân tầng dữ liệu phân tích, tự tay thiết kế các bộ đồ thị động và hệ thống báo cáo trực quan hóa chuyên nghiệp giúp hỗ trợ ra quyết định kinh doanh.

* **Kiện toàn tư duy thiết kế hệ thống dữ liệu chuẩn hóa trên AWS (Modern Data Stack)**, hiện thực hóa thành công một chuỗi giá trị dữ liệu khép kín: từ khâu Thu thập (Ingestion) -> Lưu trữ (Storage) -> Xử lý/Lập danh mục (Processing/Cataloging) -> Truy vấn (Querying) -> Trực quan hóa (Visualization).

* **Tuân thủ nghiêm ngặt quy định tối ưu hóa chi phí vận hành điện toán đám mây**, triển khai quy trình dọn dẹp hệ thống (cleanup) triệt để sau khi hoàn thành chuỗi thực hành (hủy bỏ luồng Kinesis Firehose, xóa dữ liệu Catalog, làm sạch S3 bucket và ngắt các dashboard QuickSight thử nghiệm) bảo vệ tài khoản không phát sinh cước phí ngoài ý muốn.
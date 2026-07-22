---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---



### Mục tiêu tuần 9:

* Làm chủ các chiến lược chuyển đổi và di chuyển cơ sở dữ liệu khác nền tảng (heterogeneous migration) bằng công cụ AWS Schema Conversion Tool (SCT) và AWS Database Migration Service (DMS).
* Phát triển năng lực vận hành nâng cao trong việc chuẩn bị hạ tầng nguồn (SQL Server, Oracle), điều phối tiến trình sao chép dữ liệu không máy chủ (Serverless), và chẩn đoán các kịch bản sự cố thực tế.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Kết nối Hệ thống & Cấu hình SQL Server Nguồn:** <br> - Thực hiện kết nối từ xa vào các máy chủ máy tính thông qua giao thức RDP (Remote Desktop Protocol) <br> - Khảo sát và sử dụng AWS Systems Manager Fleet Manager để quản lý hệ thống máy chủ từ xa <br> - Khởi tạo cấu hình hệ quản trị cơ sở dữ liệu Microsoft SQL Server đóng vai trò nguồn dịch chuyển (Source DB) cho dự án | 15/6/2026 | 15/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Cấu hình Cơ sở dữ liệu Oracle Nguồn:** <br> - Thiết lập kết nối thành công đến các thực thể cơ sở dữ liệu Oracle <br> - Thực hiện các bước chuẩn bị cấu hình Oracle đóng vai trò nguồn dịch chuyển dữ liệu sang AWS <br> - Tiến hành chỉnh sửa, lược bỏ các ràng buộc dữ liệu (constraints) để đáp ứng yêu cầu tương thích của tiến trình migration | 16/6/2026 | 16/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Chuyển đổi Lược đồ Lược đồ Khác nền tảng:** <br> - Thiết lập và cấu hình dịch vụ cơ sở dữ liệu đám mây Amazon Aurora MySQL đóng vai trò điểm đích (Target DB) <br> - Khởi tạo các dự án dịch chuyển (Migration Projects) trên các công cụ tự động của AWS <br> - Thực hiện biên dịch, chuyển đổi cấu trúc lược đồ dữ liệu (Schema Conversion) từ Microsoft SQL Server và Oracle sang MySQL | 17/6/2026 | 17/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Triển khai Tiến trình Sao chép Dữ liệu Serverless:** <br> - Khởi tạo các điểm kết nối đầu cuối (DMS Endpoints) và thiết lập các tác vụ di chuyển dữ liệu (Migration Tasks) <br> - Rà soát và xác thực dữ liệu được đồng bộ trung gian lưu trữ tại Amazon S3 <br> - Cấu hình và kích hoạt tiến trình di chuyển dữ liệu tự động không máy chủ AWS DMS Serverless Migration | 18/6/2026 | 18/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Giám sát Vận hành & Xử lý Sự cố Migration:** <br> - Cấu hình hệ thống tự động gửi thông báo sự kiện (Event Notifications) để theo dõi trạng thái tác vụ dịch chuyển <br> - Phân tích, rà soát hệ thống mã nhật ký (Logs) phát sinh trong quá trình đồng bộ <br> - Chẩn đoán và xử lý kịch bản lỗi: Khắc phục tình trạng quá tải bộ nhớ (Memory Pressure) và xử lý triệt để các lỗi đồng bộ ở cấp độ bảng dữ liệu (Table Errors) | 19/6/2026 | 19/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 9:

* **Thành thạo kỹ năng quản trị thực thể máy chủ đám mây từ xa**, vận dụng linh hoạt giao thức RDP truyền thống phối hợp cùng giải pháp AWS Systems Manager Fleet Manager để kiểm toán, điều khiển và thiết lập quyền truy cập an toàn vào hệ thống máy chủ.

* **Làm chủ quy trình chuẩn bị và tối ưu hóa cơ sở dữ liệu nguồn trước khi dịch chuyển**, hiểu rõ các điều kiện tiên quyết khi cấu hình các công cụ lớn (Microsoft SQL Server và Oracle), biết cách xử lý và gỡ bỏ các ràng buộc dữ liệu (constraints) để đảm bảo luồng đồng bộ không bị gián đoạn.

* **Thực hiện thành công quy trình chuyển đổi lược đồ dữ liệu chéo nền tảng phức tạp**, ứng dụng các công cụ chuyển đổi của AWS (SCT) để biên dịch toàn vẹn mã nguồn cấu trúc cơ sở dữ liệu từ các hệ thống đóng (MS SQL, Oracle) sang định dạng mã nguồn mở tối ưu (Amazon Aurora MySQL).

* **Vận hành thuần thục dịch vụ dịch chuyển dữ liệu đám mây AWS DMS**, thiết lập chính xác các cặp Endpoint (Source/Target), tạo lập tác vụ chạy Full-load/CDC và tổ chức giám sát cấu trúc tệp tin lưu trữ dữ liệu kiểm tra trung gian trên Amazon S3.

* **Triển khai thành công giải pháp dịch chuyển không máy chủ AWS DMS Serverless**, tự động hóa toàn bộ quy trình phân bổ tài nguyên tính toán (Replication Capacity Units) phù hợp với dung lượng tải thực tế mà không cần cấu hình thủ công.

* **Kiện toàn hệ thống giám sát và cảnh báo vận hành thời gian thực**, tích hợp thành công cơ chế gửi thông báo sự kiện tự động, giúp đội ngũ kỹ sư nắm bắt ngay lập tức các thay đổi về trạng thái tác vụ (Start, Stop, Fail) trong suốt vòng đời chuyển đổi.

* **Nâng cao năng lực chẩn đoán và khắc phục sự cố hệ thống lớp sâu (Advanced Troubleshooting)**, trực tiếp rà soát logs để khoanh vùng và xử lý triệt để hai kịch bản lỗi kinh điển trong môi trường sản xuất (Production): lỗi thắt nút cổ chai bộ nhớ (Memory Pressure) và lỗi đồng bộ cấu trúc bảng (Table-level Errors), tối ưu hóa hiệu năng truyền tải dữ liệu trên đám mây.
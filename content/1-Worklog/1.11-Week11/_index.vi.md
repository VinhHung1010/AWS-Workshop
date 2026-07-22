---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---



### Mục tiêu tuần 11:

* Nắm vững các kiến thức nền tảng về hệ quản trị cơ sở dữ liệu phi quan hệ NoSQL và các mô hình thiết kế nâng cao với Amazon DynamoDB, tập trung vào kiến trúc serverless quy mô toàn cầu và hệ thống hướng sự kiện (event-driven).
* Khai phá đa phương thức điều phối tài nguyên đám mây (Console, CloudShell, SDK) và xây dựng không gian phát triển mã nguồn tập trung với AWS Cloud9 phục vụ cho các đường ống kỹ nghệ dữ liệu.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Nền tảng Kỹ nghệ Cơ sở dữ liệu NoSQL:** <br> - Nghiên cứu cấu trúc kiến trúc và các khái niệm cốt lõi của Amazon DynamoDB <br> - Khởi tạo và quản lý cấu trúc các bảng dữ liệu DynamoDB <br> - Cấu hình khóa phân vùng (partition keys), phân tích các thuộc tính của bảng và thực thi các thao tác CRUD cơ bản trên giao diện Console | 29/06/2026 | 29/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Thiết kế DynamoDB Nâng cao & Kiến trúc Hướng sự kiện:** <br> - Cấu hình các phương án sao lưu và phục hồi dữ liệu (Backup & Recovery) cho DynamoDB <br> - Nghiên cứu sâu các mô hình thiết kế (Design Patterns) nâng cao cho cơ sở dữ liệu NoSQL <br> - Khảo sát kiến trúc ứng dụng serverless quy mô toàn cầu và xây dựng hệ thống hướng sự kiện kết hợp giữa DynamoDB và các dịch vụ AWS | 30/06/2026 | 30/06/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Tối ưu hóa Chi phí Cơ sở dữ liệu & Truy vấn Xác thực:** <br> - Xây dựng các bảng dữ liệu, thêm dữ liệu mẫu và thực hiện các câu lệnh truy vấn bổ sung để xác thực kết quả <br> - Nghiên cứu các chỉ số đo lường sử dụng và hệ thống giám sát chi phí AWS <br> - Cấu hình gắn thẻ tài nguyên (Tagging) phục vụ phân bổ chi phí ngân sách và dọn dẹp môi trường | 01/07/2026 | 01/07/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Điều phối Hạ tầng Qua Đa giao diện:** <br> - Sử dụng môi trường dòng lệnh trực tuyến AWS CloudShell để tương tác với hệ thống <br> - Thực hành quản lý tài nguyên và tự động hóa các dịch vụ thông qua bộ phát triển phần mềm AWS SDK <br> - So sánh, đánh giá ưu nhược điểm vận hành giữa ba phương thức: Giao diện web (Console), Dòng lệnh (CLI) và Mã nguồn (SDK) | 02/07/2026 | 02/07/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Khởi tạo Môi trường Lập trình Đám mây & Chuẩn bị Dữ liệu:** <br> - Khởi tạo môi trường lập trình tích hợp đám mây AWS Cloud9 <br> - Tiến hành tải các tập dữ liệu (datasets) phục vụ cho bài toán phân tích về không gian làm việc <br> - Thực hiện đẩy (upload) các tập dữ liệu lên Amazon S3, tạo bước đệm cho các tác vụ biến đổi dữ liệu tiếp theo | 03/07/2026 | 03/07/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 11:

* **Làm chủ hạ tầng quản trị cơ sở dữ liệu NoSQL hiệu năng cao**, tự tay thiết kế và cấu hình hoàn chỉnh các bảng dữ liệu phi quan hệ trên Amazon DynamoDB, tối ưu hóa cấu trúc khóa phân vùng (partition key) để đảm bảo tốc độ đọc ghi đạt độ trễ phần nghìn giây.

* **Xây dựng thành công các kiến trúc ứng dụng Serverless hướng sự kiện**, ứng dụng các mô hình thiết kế nâng cao của DynamoDB để tự động kích hoạt các luồng xử lý dữ liệu chéo dịch vụ đám mây một cách linh hoạt khi có biến động dữ liệu.

* **Triển khai thành thạo giải pháp bảo vệ an toàn thông tin cơ sở dữ liệu NoSQL**, cấu hình chính xác cơ chế sao lưu (Backup) và phục hồi cho DynamoDB, đảm bảo khả năng sẵn sàng cao và giảm thiểu rủi ro mất mát dữ liệu.

* **Nâng cao tư duy quản trị tài chính đám mây (FinOps) cho lớp lưu trữ**, nắm vững các kỹ thuật phân tích chỉ số sử dụng, kiểm soát cước phí phát sinh và ứng dụng chiến lược gắn nhãn (Tagging) khoa học để phân bổ chi phí database một cách minh bạch.

* **Làm chủ đa phương thức giao tiếp và quản trị tài nguyên AWS**, vận dụng thuần thục từ giao diện đồ họa Console, môi trường dòng lệnh nhanh AWS CloudShell cho đến kỹ năng viết script tự động hóa hạ tầng bằng ngôn ngữ lập trình qua AWS SDK.

* **Thiết lập thành công môi trường phát triển mã nguồn đám mây chuẩn hóa**, khởi tạo không gian IDE trực tuyến AWS Cloud9 giúp tối ưu quy trình viết code, quản lý dependencies và biên dịch các đoạn script xử lý dữ liệu ngay trên cloud.

* **Xây dựng hoàn chỉnh tầng lưu trữ đệm phục vụ kỹ nghệ dữ liệu lớn**, hiện thực hóa quy trình thu thập và đồng bộ các tập dữ liệu thô vào các thùng chứa Amazon S3, tạo dựng nền móng vững chắc cho các tác vụ chuyển đổi, làm sạch dữ liệu (Data Transformation) tiếp theo.

* **Duy trì tốt tư duy tối ưu hóa tài nguyên hệ thống**, tuân thủ nghiêm ngặt quy trình giải phóng môi trường lab (xóa bỏ các bảng DynamoDB test, gỡ cài đặt các instance Cloud9 tạm thời và làm sạch S3 buckets) ngăn chặn hoàn toàn việc phát sinh cước phí ngoài ý muốn.
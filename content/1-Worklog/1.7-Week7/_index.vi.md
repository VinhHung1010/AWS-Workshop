---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---



### Mục tiêu tuần 7:

* Nâng cao năng lực chuyên sâu về Quản trị danh tính và Truy cập nâng cao (IAM), tập trung vào cơ chế cấp quyền tạm thời, ràng buộc điều kiện đa yếu tố và chuyển đổi vai trò (Switch Role) quản trị.
* Triển khai giải pháp giám sát an ninh chuẩn hóa, mã hóa dữ liệu lưu trữ S3 với AWS KMS và phân tích lỗ hổng/hành vi hệ thống tập trung thông qua sự phối hợp giữa AWS CloudTrail và Amazon Athena.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Hoàn thành các bài Lab về Chuyển đổi Vai trò IAM và Kiểm soát Truy cập EC2:** <br> - **Module 05-Lab28-5.1 đến 5.2.5:** Thực hiện chuyển đổi vai trò (Switch Roles), khởi tạo các luồng truy cập bảo mật vào EC2, tiến hành tạo EC2 instance, chỉnh sửa thẻ gắn nhãn tài nguyên (tags) và rà soát điều kiện chính sách chính xác <br> - **Module 05-Lab28-6:** Tiến hành giải phóng và dọn dẹp các tài nguyên bài lab | 1/6/2026 | 1/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3   | **Hoàn thành bài Lab Thiết lập Chính sách Ràng buộc và Đặc quyền Tối thiểu:** <br> - **Module 05-Lab30-3 đến Lab30-5:** Xây dựng các bộ chính sách giới hạn quyền hạn (Restriction Policies), khởi tạo người dùng IAM Limited User và thực hiện các bước kiểm thử ranh giới cấp quyền chặt chẽ <br> - **Module 05-Lab30-6:** Tiến hành dọn dẹp môi trường hạ tầng thử nghiệm | 2/6/2026 | 2/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4   | **Hoàn thành chuỗi bài Lab về Mã hóa, Kiểm toán Hệ thống và Phân tích Nhật ký:** <br> - **Module 05-Lab33-2.1 đến 4.2:** Khởi tạo dịch vụ quản lý khóa AWS KMS, tạo lập S3 bucket và thực hiện tải lên các tệp tin dữ liệu được mã hóa an toàn <br> - **Module 05-Lab33-5.1 đến 5.3:** Cấu hình luồng ghi nhật ký hoạt động với AWS CloudTrail và kết nối dịch vụ Amazon Athena để truy vấn dữ liệu log nâng cao | 3/6/2026 | 3/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5   | **Hoàn thành bài Lab Chia sẻ Dữ liệu Mã hóa và Phân quyền Doanh nghiệp:** <br> - **Module 05-Lab33-6 & 33-7:** Kiểm thử quy trình chia sẻ dữ liệu mã hóa qua khóa KMS trên S3 và xóa tài nguyên <br> - **Module 05-Lab44-2 đến 4.2:** Thành lập nhóm IAM Group, tạo lập các người dùng hệ thống, rà soát phân quyền thực tế và cấu hình tính năng chuyển đổi vai trò quản trị (Admin IAM Role / Switch Role) | 4/6/2026 | 4/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 6   | **Hoàn thành bài Lab Cấu hình Ràng buộc Bối cảnh và Tối ưu hóa Khóa Xác thực:** <br> - **Module 05-Lab44-4.3.1 đến 5:** Áp dụng bộ lọc giới hạn Switch Role dựa trên địa chỉ IP nguồn và khung giờ truy cập cố định, tiến hành dọn dẹp hệ thống <br> - **Module 05-Lab48-1.1 đến 4:** Khởi tạo EC2/S3, tạo cặp Access Key, thực hành xác thực CLI bằng thông tin IAM và chứng minh tính ưu việt về bảo mật của IAM Role so với Access Key | 5/6/2026 | 5/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Kết quả đạt được tuần 7:

* **Làm chủ cơ chế ủy quyền và phân cấp truy cập an toàn bằng IAM Roles**, hiểu sâu về bản chất của việc giả lập vai trò (role assumption) và sử dụng các chứng chỉ bảo mật tạm thời (temporary credentials) để loại bỏ hoàn toàn các rủi ro lộ lọt thông tin của tài khoản gốc.

* **Nâng cao năng lực thiết kế kiến trúc bảo mật lớp sâu**, tự tay xây dựng các bộ chính sách IAM nghiêm ngặt nhằm hiện thực hóa nguyên tắc đặc quyền tối thiểu (Principle of Least Privilege) và thiết lập ranh giới phân quyền vững chắc (permission boundaries) cho người dùng giới hạn.

* **Triển khai thành công giải pháp mã hóa dữ liệu lưu trữ cấp doanh nghiệp**, vận dụng linh hoạt dịch vụ AWS Key Management Service (KMS) để bảo vệ toàn diện dữ liệu tĩnh (data-at-rest) trên Amazon S3, đồng thời cấu hình cơ chế chia sẻ tệp tin mã hóa an toàn giữa các thực thể được cấp phép.

* **Thiết lập hoàn chỉnh hệ thống kiểm toán và giám sát vận hành**, cấu hình thành công AWS CloudTrail giúp tự động ghi lại toàn bộ lịch sử thao tác API trong hệ thống, đảm bảo tính minh bạch và phục vụ cho công tác điều tra an ninh thông tin khi cần thiết.

* **Vận dụng thành thạo kỹ năng phân tích dữ liệu nhật ký hệ thống nâng cao**, sử dụng công cụ Amazon Athena để thực hiện các câu lệnh truy vấn SQL trực tiếp trên các tệp tin log của CloudTrail lưu trữ tại S3, giúp nhanh chóng phát hiện các hành vi bất thường hoặc lỗi phân quyền trong hạ tầng đám mây.

* **Kiện toàn mô hình quản lý phân quyền theo nhóm trong doanh nghiệp**, tối ưu hóa quy trình quản trị qua việc thiết lập các IAM Group, phân chia quyền hạn theo vị trí công việc, và cấu hình thành công Switch Role hỗ trợ các kỹ sư chuyển đổi sang tài khoản quản trị một cách có kiểm soát.

* **Thắt chặt an ninh hệ thống bằng các chính sách kiểm soát bối cảnh thông minh (Context-aware security)**, bổ sung các điều kiện nâng cao vào IAM Policy nhằm ngăn chặn các hành vi Switch Role nằm ngoài dải IP văn phòng được phép hoặc thực hiện sai khung giờ quy định.

* **Thuần thục kỹ năng cấu hình và tương tác hạ tầng qua giao diện dòng lệnh (AWS CLI)**, biết cách quản lý và sử dụng Access Key an toàn, đồng thời nắm rõ tư duy quản trị rủi ro để ưu tiên sử dụng IAM Instance Profile cho máy chủ EC2 thay vì lưu trữ mã khóa tĩnh lâu dài.

* **Tuân thủ xuất sắc các quy chuẩn tối ưu hóa chi phí đám mây**, thực hiện quy trình rà soát và hủy bỏ tài nguyên bài lab (clean up) một cách bài bản (xóa các máy chủ EC2 kiểm thử, dọn dẹp S3 buckets, gỡ bỏ các vai trò kiểm thử và khóa KMS dư thừa) bảo vệ tài khoản không phát sinh cước phí ngoài ý muốn.
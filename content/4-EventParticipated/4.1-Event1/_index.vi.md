---
title: "Event 1"
date: 2026-05-30
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

### [Event 1](4.1-Event1/)
&emsp;**Tên sự kiện:** Meet up 30/5

&emsp;**Thời gian:** 09:00 ngày 30/05/2026

&emsp;**Địa điểm:** Tầng 26, tòa nhà Bitexco, số 02 đường Hải Triều, phường Sài Gòn, thành phố Hồ Chí Minh

&emsp;**Vai trò trong sự kiện:** Người tham dự 




### Mục Đích Của Sự Kiện

- Chia sẻ best practices trong thiết kế ứng dụng hiện đại và tối ưu hóa hệ thống[cite: 1, 5].
- Giới thiệu phương pháp DDD, kiến trúc event-driven và các giải pháp điện toán đám mây phù hợp[cite: 1].
- Hướng dẫn lộ trình thực hành AWS an toàn, ứng dụng công cụ giả lập cục bộ và AI hỗ trợ SDLC[cite: 1, 3].
- Trang bị tư duy hệ thống (DevOps Foundations) và kỹ năng phát triển bản thân (vượt qua trì hoãn, xây dựng sự tự tin thuyết trình kỹ thuật)[cite: 2, 4, 5].

### Danh Sách Diễn Giả

- **Huỳnh An Khương, Mai Quốc Anh, Nguyễn Trần Minh Quân** - Nhóm FCAJ Challenger (Chia sẻ kinh nghiệm thực chiến Hackathon)[cite: 1].
- **Nguyễn Thị Quỳnh Như** - Thành viên FCAJ (Chuyên đề Xây dựng sự tự tin - Confidence Architecture)[cite: 2].
- **Huỳnh Thái Linh** - Thành viên FCAJ (Chuyên đề Tối ưu hóa kỹ năng AWS với Cloud Quest & Floci)[cite: 3].
- **Khắc Uy Phạm** - Sinh viên năm 3 VGU (Chuyên đề Giải mã tảng băng Trì hoãn)[cite: 4].
- **Trần Minh Quân** - Kỹ sư Hệ thống (Chuyên đề Tảng băng chìm của dự án - Nền tảng DevOps)[cite: 5].

### Nội Dung Nổi Bật

#### 1. Kinh nghiệm thực chiến từ các giải đấu Hackathon
- **Bản chất Hackathon:** Là sự kiện cường độ cao, nơi các đội phải sáng tạo giải pháp và xây dựng prototype/MVP giải quyết các bài toán thực tế trong một quỹ thời gian giới hạn nghiêm ngặt từ 24-48 giờ[cite: 1].
- **Kinh nghiệm từ thực tế qua 2 dự án thi đấu:**
  * *SynthHunter:* Hệ thống phân tích nhận diện giọng nói AI giả mạo nhằm bảo vệ an toàn thông tin và giảm thiểu rủi ro gian lận, tích hợp 3 trụ cột (Speech Dynamics, Encoder Behavior, Temporal Rhythm)[cite: 1].
  * *Vortex:* Đường ống quy trình kết nối chéo toàn bộ hành trình tuyển dụng, từ khâu sàng lọc CV tự động đến phỏng vấn mô phỏng kỹ thuật[cite: 1].
- **Bài học rút ra:** Luôn bắt đầu từ bài toán thực tế, thử nghiệm liên tục không ngừng nghỉ, tận dụng tối đa các công cụ bổ trợ và chấp nhận những khó khăn đặc thù (đau lưng, thiếu ngủ, lỗi hệ thống phút chót) như một phần của quá trình trưởng thành[cite: 1].

#### 2. Kỹ năng mềm & Xây dựng sự tự tin thuyết trình (Confidence Architecture)
- **Định nghĩa lại sự tự tin:** Không phải là cái tôi lớn hay sự hoàn hảo biết hết mọi câu trả lời, mà là sự dũng cảm dám hành động và thử nghiệm ngay cả khi đang cảm thấy sợ hãi hay lo lắng[cite: 2].
- **Cầu nối năng lực:** Kiến thức kỹ thuật chuyên môn và code giỏi chỉ là nền móng, kỹ năng giao tiếp và sự tự tin chính là chiếc cầu nối quyết định để đưa sản phẩm và năng lực của bạn ra thực tế[cite: 2].
- **Phương pháp "Hack" sự tự tin:** Vận dụng quy tắc 5 giây (5-Second Rule) để hành động trước khi não bộ kịp hoài nghi, chuẩn bị kỹ lưỡng để tạo ra sự rõ ràng (Clarity) và ăn mừng từ những chiến thắng nhỏ nhất (Small Wins) để xây dựng niềm tin vào bản thân[cite: 2].

#### 3. Lộ trình thực hành AWS & Công cụ giả lập mã nguồn mở Floci
- **Nỗi sợ của người mới học Cloud:** Thường xuyên lo lắng về cước phí phát sinh ngoài ý muốn (AWS Bill), quên xóa tài nguyên thử nghiệm sau khi dùng hoặc vượt hạn mức Free Tier[cite: 3].
- **Hệ sinh thái Floci:** Giới thiệu công cụ giả lập AWS cục bộ (Local Emulator) mã nguồn mở siêu nhẹ (khởi động chỉ 24ms, tốn vỏn vẹn 13MiB RAM nhưng hỗ trợ tới hơn 50+ dịch vụ cốt lõi như EC2, Lambda, S3, DynamoDB, SQS, API Gateway), mang lại hiệu năng vượt trội so với LocalStack bản Community miễn phí[cite: 3].
- **Lộ trình thực hành 3 giai đoạn kết hợp:** 
  * *Giai đoạn 1 (Tư duy & Kiến trúc):* Học trực quan qua các nhiệm vụ game-hóa của AWS Cloud Quest[cite: 3].
  * *Giai đoạn 2 (Code & Kiểm thử nhanh):* Viết code và test cục bộ không tốn chi phí với Floci[cite: 3].
  * *Giai đoạn 3 (Triển khai thực tế):* Deploy sản phẩm hoàn chỉnh lên môi trường AWS thật[cite: 3].

#### 4. Giải mã tâm lý trì hoãn thông qua mô hình tảng băng (The Iceberg of Procrastination)
- **Bản chất bề nổi và chiều sâu:** Sự lười biếng, lướt mạng xã hội vô định hay tắt báo thức chỉ chiếm 20-30% bề nổi. Nguyên nhân cốt lõi (70-80%) là do khó khăn trong việc quản lý cảm xúc trước áp lực, chứ không phải do kỹ năng quản lý thời gian kém[cite: 4].
- **3 lớp mặt của nỗi sợ kỹ sư thường gặp:** 
  * *Sợ không đủ năng lực (Fear of Inadequacy):* Khi đối mặt với roadmap phức tạp (Kubernetes, Terraform), não bộ tự động chọn cách đóng tab để né tránh áp lực cảm xúc[cite: 4].
  * *Sợ bị phán xét (Fear of Judgment):* Viết code xong không dám push lên GitHub hoặc không dám chia sẻ vì sợ người khác đánh giá thấp[cite: 4].
  * *Sợ thất bại (Fear of Failure):* Trì hoãn để tạo ra một cái cớ an toàn rằng "Tôi thất bại vì tôi chưa dành đủ thời gian chứ không phải tôi kém"[cite: 4].
- **Giải pháp:** Thay vì tự trách mình lười, hãy gọi tên chính xác nỗi sợ (Name Your Fear) và áp dụng Quy tắc 5 phút (chỉ cần mở máy làm việc đúng 5 phút, quán tính hành động sẽ tự dẫn dắt bạn tiếp tục)[cite: 4].

#### 5. Tư duy hệ thống và Văn hóa DevOps doanh nghiệp
- **Mô hình tảng băng trong quản lý dự án:** Các triệu chứng bề nổi như trễ deadline, bug production, cháy deal hay team burnout thực chất bắt nguồn từ các vấn đề tiềm ẩn bên dưới: Yêu cầu mơ hồ, giao tiếp kém giữa các phòng ban, quy trình thủ công và thiếu tinh thần trách nhiệm chung[cite: 5].
- **Bản chất của DevOps:** DevOps không đơn thuần là công cụ kỹ thuật (Docker, Kubernetes, CI/CD pipelines)[cite: 5]. Đó là sự kết hợp chặt chẽ giữa Con người, Quy trình và Công nghệ (People, Process, Technology). Bạn có thể tự động hóa việc triển khai nhưng không thể tự động hóa sự tin tưởng và tinh thần làm chủ (ownership)[cite: 5].
- **4 bài học cốt lõi từ DevOps:** 
  * Hợp tác phá bỏ các phân vùng cô lập (Breaking Silos) để chia sẻ trách nhiệm[cite: 5].
  * Tự động hóa quy trình (Automation) để giảm thiểu ma sát và lỗi con người[cite: 5].
  * Phản hồi nhanh (Fast Feedback) qua hệ thống giám sát và đo lường (Monitoring/Observability) để phát hiện bug sớm[cite: 5].
  * Cải tiến liên tục (Continuous Improvement) sau mỗi thất bại thông qua các buổi họp Retrospectives[cite: 5].

---

### Những Gì Học Được

#### Về Tư Duy Thiết Kế & Hệ Thống
- **Business-First Approach:** Luôn tập trung hiểu và giải quyết bài toán nghiệp vụ kinh doanh trước khi lựa chọn công nghệ[cite: 1, 4].
- **Tư duy hệ thống (System Thinking):** Tập trung đào sâu tìm nguyên nhân gốc rễ (Root Causes) thay vì chỉ đi vá các triệu chứng lỗi bề nổi[cite: 5].
- **Quy chuẩn quản trị (Governance):** Nắm rõ tầm quan trọng của việc quản lý vòng đời tài nguyên và tối ưu hóa ngân sách đám mây để tránh lãng phí.

#### Về Kiến Trúc Kỹ Thuật
- Học cách vận dụng kỹ thuật **Event Storming** để bóc tách quy trình kinh doanh và xác định biên giới dịch vụ (Bounded Contexts) cho hệ thống[cite: 1, 4].
- Nắm chắc tiêu chí phân bổ hạ tầng tính toán (Compute Spectrum) và hiểu sâu về cơ chế định tuyến dữ liệu luồng.
- Thành thạo việc xây dựng môi trường phát triển và lab cục bộ an toàn, tiết kiệm hiệu năng cao bằng việc kết hợp **Cloud Quest** và **Floci emulator**[cite: 3].

#### Về Phát Triển Bản Thân (Personal Growth)
- Hiểu rằng sự tự tin và khả năng hành động vượt qua nỗi sợ là một kỹ năng có thể rèn luyện hàng ngày thông qua các quy tắc hành động nhanh (5-Second Rule, 5-Minute Rule)[cite: 2, 4].
- Chuyển đổi tư duy từ đổ lỗi sang tư duy DevOps: Nhận trách nhiệm chung, liên tục cải tiến và học hỏi từ các thất bại của hệ thống[cite: 5].

---

### Ứng Dụng Vào Công Việc

- **Triển khai DDD và Event Storming:** Lên lịch làm việc cùng team nghiệp vụ để chuẩn hóa ngôn ngữ chung (Ubiquitous Language) và bóc tách cấu trúc dự án phần mềm hiện tại[cite: 1, 4].
- **Kiến trúc lại Microservices:** Sử dụng Bounded Contexts để tối ưu ranh giới các dịch vụ backend, thay thế dần các kết nối đồng bộ (sync calls) bằng tin nhắn bất đồng bộ qua hàng đợi (async messaging)[cite: 1].
- **Tối ưu quy trình phát triển Local:** Cấu hình Floci emulator tại máy cá nhân để làm môi trường test API, Lambda và S3 cục bộ trước khi đẩy lên AWS, giúp tăng tốc độ coding và tiết kiệm tài nguyên[cite: 3].
- **Áp dụng văn hóa DevOps & Giám sát sớm:** Thiết lập các bộ đo lường phản hồi nhanh (Fast Feedback logs) và tổ chức các buổi họp Retrospectives nghiêm túc sau mỗi chặng hoàn thành code để cải tiến hiệu suất team[cite: 5].

---

### Trải nghiệm cá nhân trong sự kiện

Tham gia workshop là một trải nghiệm toàn diện và vô cùng đắt giá, tạo ra sự thay đổi mạnh mẽ cả về nhận thức kỹ thuật lẫn kỹ năng tư duy mềm:

- **Sự truyền cảm hứng lớn từ các chuyên gia:** Được lắng nghe chia sẻ trực tiếp và đầy năng lượng từ các thành viên trong cộng đồng First Cloud AI Journey[cite: 1, 2, 3]. Các case study sinh động từ trải nghiệm Hackathon giúp các lý thuyết khô khan về kiến trúc trở nên dễ hiểu[cite: 1].
- **Tính thực tế cao:** Không chỉ dừng lại ở lý thuyết kiến trúc đám mây, sự kiện đem lại giá trị thực tiễn rất cao khi giới thiệu các công cụ nguồn mở tối ưu như Floci hay các góc nhìn khoa học để giải quyết các vấn đề thường trực của lập trình viên như áp lực thuyết trình hay tâm lý trì hoãn công việc[cite: 2, 3, 4].
- **Môi trường kết nối tuyệt vời:** Workshop tạo cơ hội giao lưu, trao đổi văn hóa DevOps, cùng chia sẻ những khó khăn thực chiến trong quá trình làm dự án, giúp củng cố tinh thần "Go Build" và học hỏi không ngừng[cite: 1, 5].

#### Một số hình ảnh khi tham gia sự kiện

*Hình ảnh được ghi lại trong workshop - check-in, các phần trình bày và cộng đồng.*

![Event 1 - Khoảnh khắc cộng đồng và workshop 1](/AWS-Workshop/images/4-Event/event1.png)

![Event 1 - Khoảnh khắc cộng đồng và workshop 2](/AWS-Workshop/images/4-Event/event2.png)

![Event 1 - Email xác nhận 1](/AWS-Workshop/images/4-Event/confirmation1.png)

![Event 1 - Email xác nhận 2](/AWS-Workshop/images/4-Event/confirmation2.png)

> **Tổng kết:** Sự kiện đã phá vỡ rào cản thông thường của một workshop công nghệ bằng cách kết hợp hoàn hảo giữa Kỹ thuật đám mây thực chiến với Nghệ thuật quản trị con người (DevOps, Sự tự tin, Vượt qua nỗi sợ Trì hoãn)[cite: 1, 2, 3, 4, 5]. Đây chính là bệ phóng tư duy quan trọng giúp tôi hoàn thiện năng lực của một Kỹ sư Điện toán đám mây toàn diện.
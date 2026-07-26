---
title: "Event 3"
date: 2026-07-25
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

### [Event 3](4.3-Event3/)
&emsp;**Tên sự kiện:** FCAJ - AGENTIC AI BUILD WEEK

&emsp;**Thời gian:** 09:00 - 12:00 ngày 25/07/2026

&emsp;**Địa điểm:** Tầng 26, tòa nhà Bitexco, số 02 đường Hải Triều, phường Sài Gòn, thành phố Hồ Chí Minh

&emsp;**Vai trò trong sự kiện:** Người tham dự 

### Mục Đích Của Sự Kiện

- Trình diễn các dự án được xây dựng trong **FCAJ Agentic AI Build Week** - phiên cộng đồng nửa ngày, nơi các đội tham gia giới thiệu sản phẩm agentic AI end-to-end trên AWS Bedrock, AgentCore và SageMaker[cite: 1, 4].
- Lan tỏa và trao đổi các pattern kiến trúc giữa các lĩnh vực AI/ML, Computer Vision, Conversational Agent và Enterprise Search platform[cite: 2, 3].
- Cung cấp sân khấu công khai để 8 đội tự kiểm chứng MVP với hội đồng gồm AWS Solution Architect, các founder startup và AI mentor[cite: 1, 4].
- Kết nối cộng đồng First Cloud AI Journey với thế hệ GenAI builder mới thông qua demo trực tiếp, thảo luận chi phí minh bạch và các phiên Q&A[cite: 1, 2, 3, 4].

### Các Đội Thi & Dự Án Tiêu Biểu

- **One Team - KFC Bot Agent** - Anh Duy, Trần Đông, Đoàn Trung, Minh Việt, Anshul Roy. Đại lý gọi món đa kênh cho phép khách hàng KFC Việt Nam đặt đồ ngay trong Zalo OA, Messenger và các kênh tương lai mà không cần chuyển app. Vận hành trên Amazon Bedrock AgentCore với các lớp Goal, Plan, Tools, Verify. Chi phí **$0.006/đơn và $88/tháng** cho 500 đơn/ngày, độ trễ 3-5s, **giảm 60% code hạ tầng** so với kiến trúc serverless truyền thống[cite: 1].
- **Plan V - SA Professional Native App** - Phạm Tiến Thuận Phát, Huỳnh Hoàng Long, Lê Minh Nghĩa, Trần Đại Vĩ, Nguyễn An. Trợ lý Solution Architect agentic giúp tiếp nhận yêu cầu BRD/PRD dạng ngôn ngữ tự nhiên, phác thảo kiến trúc hybrid-cloud, sinh sơ đồ Drawio + AWS Architecture Icons có thể chỉnh sửa và ước tính chi phí cho khu vực ap-southeast-1. Thay thế vòng lặp phác thảo thủ công bằng chat-sidebar luôn bám sát tiêu chuẩn công ty[cite: 2].
- **Signal Scout** - Lê Tấn Lực, Đỗ Hoàng Hiếu, Triệu Quốc Hào, Nguyễn Văn Duy Khiêm, Nguyễn Công Minh, Nguyễn Trần Minh Quân. Nền tảng enterprise intelligence phát hiện sớm các thay đổi chiến lược doanh nghiệp bằng cách kết hợp nhiều nguồn tín hiệu rời rạc (LangFuse trace, TinyFish scraping, Apify feed) vào các quyết định Maintain / Adapt / Accelerate có minh chứng. Xây dựng trên Value Creation & Delivery Canvas với self-service dashboard dành cho các team risk, competitive intelligence và B2B account[cite: 3].
- **Team 3KA - S.H.E.P.H.E.R.D.** - Huỳnh An Khương, Nguyễn Quốc Huy, Ngô Quang Khôi, Hoàng Lê Thanh Đức, Đặng Nguyễn Phước Lộc, Đặng Trường Hưng. Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch - stack crowd analytics thời gian thực dùng YOLO + ByteTrack trên Amazon SageMaker, kết hợp Bedrock AgentCore + Strands Operation Agent cho phép cảnh báo chủ động khi mật độ vượt ngưỡng an toàn[cite: 4].

### Điểm Nổi Bật Của Sự Kiện

#### 1. Agentic AI như khung kiến trúc chung
- **Vượt xa chatbot:** Cả 4 đội đều hội tụ về vòng lặp Agent (Goal → Plan → Tools → Act → Verify) thay vì gọi LLM đơn lẻ, lấy tool làm nguồn sự thật thay vì dựa vào bộ nhớ model[cite: 1, 2].
- **Bedrock AgentCore trở thành baseline mới:** 3/4 đội thay thế Lambda orchestration thủ công bằng các primitive của AgentCore, giảm 40-60% code hạ tầng và tập trung vào tool, prompt và UX[cite: 1, 4].
- **Grounding theo domain là yếu tố quyết định:** Mọi dự án đều ghép foundation model với dữ liệu nghiệp vụ đáng tin cậy (menu & khuyến mãi KFC, tiêu chuẩn kiến trúc AWS, báo cáo doanh nghiệp, frame camera) - model không bịa, tool quyết định cái gì là thật[cite: 1, 2, 3, 4].

#### 2. Minh bạch chi phí và độ trễ trên sân khấu
- **KFC Bot Agent:** $0.006/đơn và $88/tháng cho 500 đơn/ngày - Bedrock chiếm **75% bill**, AgentCore lo phần còn lại. Độ trễ 3-5s bao gồm cả vòng planning round-trip của LLM[cite: 1].
- **SA Professional Native App:** Xoá sổ chi phí phác thảo thủ công; thay vì 1-2 ngày kiến trúc sư ngồi vẽ sơ đồ, mọi thứ trở thành 30 phút chat lặp[cite: 2].
- **Signal Scout:** Xây hai phiên bản kiến trúc và công khai so sánh trên sân khấu - phiên bản cost-efficient giữ nguyên độ chính xác nhưng cắt một nửa monthly run-rate, thể hiện tư duy FinOps trưởng thành[cite: 3].
- **S.H.E.P.H.E.R.D.:** Inference latency của pipeline YOLO+ByteTrack là thử thách kỹ thuật cốt lõi; các đội chia sẻ công khai chiến lược frame-skip, batching và caching[cite: 4].

#### 3. Từ MVP hackathon tới sản phẩm thực tế
- **Thiết kế đa kênh:** "Design once, deploy everywhere" là nguyên tắc thiết kế chính của KFC Bot Agent - thêm kênh mới chỉ là thêm một adapter, không phải rewrite[cite: 1].
- **Diagram-as-code:** SA Professional Native App sinh sơ đồ Drawio dùng AWS Architecture Icons chính hãng và có thể chỉnh sửa, giúp kiến trúc sư tiếp tục lặp mà không bị lock-in[cite: 2].
- **Quyết định có minh chứng:** Signal Scout không bao giờ để agent hành động mà không hiển thị đoạn nguồn đằng sau mỗi khuyến nghị Maintain/Adapt/Accelerate, tạo niềm tin cho các team enterprise risk[cite: 3].
- **Vận hành là first-class citizen:** S.H.E.P.H.E.R.D. xem nhân viên vận hành là người dùng, không phải operator của thuật toán - cảnh báo có giải thích, có hành động gợi ý và gắn liền với workflow điều phối[cite: 4].

#### 4. Cảm xúc hackathon - một hành trình chung
- **Doubt → Flow → Pride:** Mọi đội đều đi qua cung cảm xúc giống nhau - đăng ký đầy ngợp, chạm đáy ở giữa đêm, rồi tự hào demo sản phẩm hoàn chỉnh[cite: 4].
- **"Nhỏ mà hoàn chỉnh" thắng "lớn mà dở dang":** Nhiều đội chủ động giới hạn MVP xuống một workflow làm tốt (một kênh Zalo, một SOP, một loại tín hiệu, một góc camera) và chính giới hạn đó đã cứu họ[cite: 1, 2, 3, 4].
- **Con người còn giá trị hơn giải thưởng:** Các đội đều nhấn mạnh mentor, AWS SA và bạn builder chính là giá trị thực sự của cuối tuần - nhiều cộng tác đã tiếp tục sau hackathon[cite: 1, 4].

---

### Bài Học Rút Ra

#### Tư duy kỹ thuật & kiến trúc
- **Tool-grounded agent là mặc định mới:** Bộ tool được định nghĩa tốt luôn thắng prompt hay. Xây tool trước, dạy model cách dùng sau[cite: 1, 2, 4].
- **Chi phí là ràng buộc thiết kế hạng nhất:** Mọi đội trên sân khấu đều có slide unit-economics ($/đơn, $/tháng, latency budget). Đó là điều phân biệt hackathon demo với sản phẩm deploy được[cite: 1, 3].
- **Vòng lặp verify chống lỗi âm thầm:** Cả KFC Bot Agent và S.H.E.P.H.E.R.D. đều thêm bước "Verify" đối chiếu plan của agent với state thật (cart thật, frame thật) trước khi hành động[cite: 1, 4].
- **Kiến trúc composable thắng monolith:** Các pattern adapter / connector / tool giúp đội ship kênh/business/capability mới mà không cần rewrite agent[cite: 1, 2].

#### Tư duy sản phẩm & người dùng
- **Bắt đầu từ mặt phẳng người dùng đã có:** Khách KFC đang ở Zalo, vậy bot phải sống trong Zalo. Đừng ép người dùng vào app của bạn[cite: 1].
- **Explainability là một feature:** Các đoạn trích dẫn bằng chứng của Signal Scout và cảnh báo có giải thích của S.H.E.P.H.E.R.D. chính là thứ tạo niềm tin cho người dùng không chuyên kỹ thuật[cite: 3, 4].
- **Giới hạn feature xuống một workflow làm tốt:** Mọi đội thắng trong showcase đều cắt feature quyết liệt để ship demo mạch lạc đúng hạn[cite: 1, 2, 3, 4].

#### Phát triển cá nhân
- **Đăng ký đã là nửa cuộc chiến:** Phần lớn lần đầu tham gia hackathon đã từng muốn bỏ cuộc trước build weekend - không ai hối hận vì đã thử[cite: 4].
- **Khó khăn là một phần của bài học:** Cả 4 đội đều minh bạch về phần giữa hỗn loạn của cuối tuần (debug đến 3h sáng, thiếu ngủ, lỡ push env file) như phần giá trị nhất của trải nghiệm[cite: 4].
- **Định nghĩa "xong" trước khi bắt đầu:** Những đội thống nhất sớm về scope một trang và câu chuyện demo ba phút thì consistent ship được - ngược lại thì không[cite: 4].

---

### Ứng Dụng Vào Công Việc

- **Áp dụng pattern tool-grounded agent cho trợ lý nội bộ:** Thay các chuỗi prompt tự do trong tra cứu SOP, phác thảo kiến trúc và xử lý đơn hàng bằng vòng lặp Goal→Plan→Tools→Act→Verify rõ ràng, theo gương SA Professional Native App và KFC Bot Agent[cite: 1, 2].
- **Thêm lớp bằng chứng cho khuyến nghị AI:** Bất kỳ khi nào AI đề xuất quyết định (Maintain/Adapt/Accelerate, điều phối nhân sự, thêm combo), UI phải hiển thị nguồn dữ liệu mà model dùng - lấy cảm hứng từ thiết kế evidence-backed của Signal Scout[cite: 3].
- **Ghép pipeline CV với agentic operations layer:** Phân tích thời gian thực đứng một mình chưa đủ; lớp tiếp theo là agent gợi ý và kích hoạt hành động downstream - pattern S.H.E.P.H.E.R.D. áp dụng trực tiếp cho security log triage và queue management[cite: 4].
- **Biến FinOps thành thói quen, không phải phần nghĩ sau:** Theo dõi $ theo workflow và theo call ngay từ ngày đầu; 4 đội làm được điều này đã bảo vệ được quyết định kiến trúc bằng số liệu, không phải cảm tính[cite: 1, 3].
- **Tổ chức "mini-hackathon" nội bộ trước dự án lớn tiếp theo:** Cơ chế 24h có scope, vai trò rõ ràng và văn hoá demo-first đã ép mọi đội ship cái mạch lạc - cùng cơ chế đó có thể reset một workstream đang trì trệ[cite: 4].

---

### Trải Nghiệm Cá Nhân Về Sự Kiện

Tham dự FCAJ Agentic AI Build Week với vai trò khán giả là một trong những sự kiện truyền cảm hứng nhất của cả kỳ thực tập:

- **Tám MVP, tám kiến trúc thật:** Mỗi đội không chỉ demo mà trình bày một agent stack hoàn chỉnh - tool, prompt, chi phí và danh sách trung thực những gì sẽ xây tiếp. Độ sâu kỹ thuật vượt nhiều launch GenAI thương mại[cite: 1, 2, 3, 4].
- **Một bức ảnh rõ ràng về nơi GenAI đang đi:** Thấy bốn vertical khác nhau (conversational commerce, architecture copilot, enterprise intel, real-time CV) hội tụ về cùng pattern Bedrock AgentCore + tool-grounded là tín hiệu mạnh cho thấy abstraction agentic-AI đã sẵn sàng cho production[cite: 1, 2, 3, 4].
- **Một cộng đồng ship thật:** Mentor, AWS SA và các bạn tham gia chia sẻ mẹo pricing, vòng lặp prompt, template hạ tầng xuyên suốt cả ngày - đúng tinh thần "con người bạn gặp còn giá trị hơn giải thưởng" mà team 3KA đã chia sẻ[cite: 4].
- **Một cái nhìn trung thực về phần giữa hỗn loạn:** Nhiều diễn giả chia sẻ phiên debug 3h sáng, lỡ push env file, "tưởng bỏ cuộc ở giờ thứ 12". Sự chân thành đó khiến thành quả cảm giác xứng đáng và bài học có thể tái sử dụng[cite: 4].

#### Hình ảnh sự kiện

*Hình ảnh ghi lại tại phiên FCAJ Agentic AI Build Week - các đội tham gia, khán phòng AWS Vietnam và khoảnh khắc cộng đồng.*

![Event 3 - FCAJ Agentic AI Build Week khai mạc và khán phòng 1](/AWS-Workshop/images/4-Event/event%203.png)

![Event 3 - FCAJ Agentic AI Build Week các đội và demo 2](/AWS-Workshop/images/4-Event/event%203%20(2).png)

![Event 3 - FCAJ Agentic AI Build Week finalists và Q&A 3](/AWS-Workshop/images/4-Event/event%203%20(3).png)

![Event 3 - Email xác nhận](/AWS-Workshop/images/4-Event/email%20xac%20nhan.png)

> **Kết luận:** FCAJ Agentic AI Build Week là minh chứng sống cho thấy agentic AI trên AWS đã vượt khỏi giai đoạn prototype. Bằng cách kết hợp Bedrock AgentCore, SageMaker và thiết kế tool-grounded, tất cả các đội tham gia đều ship sản phẩm có chi phí, độ trễ và explainability minh bạch[cite: 1, 2, 3, 4]. Sự kiện để lại cho cả cộng đồng - trong đó có tôi - một template cụ thể cho thế hệ ứng dụng cloud-native AI tiếp theo.
# 03 — Individual Reflection

Tài liệu này ghi lại phản tư cá nhân (Individual Reflection) về vai trò đóng góp trong nhóm, cách tương tác với AI trong suốt buổi lab, và những bài học rút ra sau quá trình xác định bài toán cho AI.

---

## 1. Tôi đã tham gia vào phần nào?

Dưới đây là chi tiết các hoạt động tôi đã thực hiện và đóng góp vào kết quả chung của nhóm:

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| **Scan cá nhân** | Quét rộng 12 vấn đề thực tế quanh mình qua 4 lăng kính, lọc ra Top 3 và chuẩn bị kỹ Problem Card cho case chính "Debug & Tìm Root Cause". | Đóng góp danh sách đa dạng và chuẩn bị chu đáo để pitch với nhóm. |
| **Pitch Problem Card** | Trình bày rõ ràng về nỗi đau debug code, bottleneck ở đoạn "mapping error message -> root cause", và đề xuất workflow Before/After. | Vấn đề được nhóm đánh giá cao và đưa vào Shortlist để thảo luận sâu. |
| **Challenge bài của bạn khác** | Đặt câu hỏi phản biện cho Quyền về bài Discord FAQ: liệu có thực sự cần AI hay chỉ cần rule/cấu trúc FAQ tốt là đủ? | Giúp nhóm nhận diện rõ ranh giới giữa giải pháp AI và Non-AI. |
| **Gom trùng / cluster** | Đề xuất phân chia 9 candidates thành 3 cụm chủ đề: Trích xuất thông tin, Giao tiếp/Quản lý nhóm, và Debug lỗi kỹ thuật. | Giúp nhóm có cái nhìn hệ thống và không bị rối khi thảo luận. |
| **Chọn candidate problem** | Đồng thuận chọn bài của Quyền ("Chat nhóm -> checklist") thay vì bài Debug của mình vì bài của Quyền có scope nhỏ hơn, dễ đo lường trực tiếp và thực thi nhanh trong lab. | Nhóm đạt được sự đồng thuận nhanh chóng, chuyển sang phase sau đúng timeline. |
| **Validation / research** | Tìm hiểu cách ClickUp AI và Notion AI bóc tách action items từ chat/họp để lấy ý tưởng thiết lập workflow cho nhóm. | Đưa ra bằng chứng củng cố phương án Workflow tốt hơn Agent. |
| **Workflow nhóm** | Hỗ trợ phân tách rõ ràng các bước trong Future State: bước nào dùng Rule (lọc noise), bước nào dùng AI (draft checklist), bước nào giữ lại con người (review). | Làm rõ ranh giới con người - máy móc và xây dựng được cơ chế Fallback rõ ràng. |
| **Problem Statement** | Tham gia viết và làm sắc nét các mục Boundary (giới hạn AI) và Success Metric (giảm thời gian từ 30 phút xuống < 15 phút). | Problem Statement v0/v1 của nhóm có tính khả thi và đo lường được. |
| **Rule / Workflow / Agent** | Lập luận bảo vệ phương án Workflow để tránh over-engineering của Agent và kiểm soát rủi ro tốt hơn. | Nhóm thống nhất lựa chọn giải pháp Workflow. |
| **Decision** | Cùng nhóm thảo luận ma trận câu hỏi và chốt quyết định GO với một bản Pilot nhỏ để chạy thử nghiệm trước. | Đưa ra quyết định thực tế, không bị cuốn theo mong muốn làm AI phức tạp. |

---

## 2. Bảng dùng AI trong reflection

Phản tư về cách tôi đã sử dụng AI làm trợ lý tư duy trong suốt các Phase:

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan** | Gợi ý thêm các vấn đề thực tế dựa trên vai trò sinh viên IT/AI. | Gợi ý thêm được lăng kính "API AI giá cao" và "rate limit". | Đưa ra một số ý tưởng quá vĩ mô và chung chung. | Chỉ lọc giữ lại các vấn đề có workflow rõ và mình từng gặp thật. |
| **Problem Card** | Phản biện các trường thông tin trong Problem Card. | Chỉ ra Success Metric ban đầu còn mơ hồ (viết chung chung là "nhanh hơn"). | Đề xuất giải pháp AI dạng Agent tự động quá sớm. | Sửa lại success metric thành thời gian cụ thể (60 phút xuống 15 phút) và hạ quick gut xuống Workflow. |
| **Workflow** | Chuyển đổi mô tả luồng debug thành sơ đồ text/Mermaid. | Tiết kiệm thời gian vẽ và định dạng sơ đồ. | AI gộp bước sửa code và chạy lại làm một, làm mất bottleneck thật. | Tách lại các bước để làm nổi bật bottleneck "tìm root cause". |
| **Research** | Tìm nhanh link tài liệu về tính năng AI của Slack và Discord. | Tổng hợp nhanh các nguồn tham khảo chính thức. | Có một số tuyên bố về hiệu năng không đi kèm nguồn kiểm chứng. | Tự click link để kiểm chứng thông tin và chỉ giữ lại các case study thực sự liên quan. |
| **Problem Statement** | Nhờ AI đóng vai Skeptical PM phản biện bản v0. | Phát hiện ra phần Boundary còn thiếu giới hạn quyền tự động gửi của AI. | AI cố viết lại Problem Statement theo văn phong hoa mỹ của nó. | Chỉ ghi nhận câu hỏi phản biện, tự thảo luận với nhóm để viết lại nội dung cốt lõi ngắn gọn. |
| **Rule/Workflow/Agent**| Nhờ AI phân tích rủi ro của mức Agent so với Workflow. | Làm rõ rủi ro bảo mật dữ liệu và spam nhóm chat của Agent. | Luôn khuyên chọn Agent vì độ "xịn" của nó. | Giữ vững lập trường chọn Workflow để tối ưu chi phí và kiểm soát rủi ro. |
| **Decision** | Hỏi về cách thiết kế một bản Pilot nhỏ nhất (MVP). | Gợi ý chạy bán thủ công bằng cơm trước (semi-manual prompt) rất hay. | Đề xuất viết code tự động hóa bằng API ngay. | Quyết định chỉ chạy bằng prompt trên giao diện web trước trong 2 tuần để tiết kiệm công sức. |

---

## 3. Reflection câu hỏi mở

*   **Tôi học được gì khi nghe top 3 problems của các bạn khác?**
    *   Tôi nhận ra các bạn khác gặp những vấn đề quản trị nhóm rất thực tế (như chốt checklist từ Zalo/Messenger của Quyền hay trả lời câu hỏi trùng lặp của An). Những vấn đề này tuy nhìn không "kỹ thuật" bằng debug code của tôi nhưng tần suất lặp lại cực cao và gây ức chế thực sự cho người vận hành.
*   **Nhóm có lúc nào bị solution-first không?**
    *   Có, ở giai đoạn đầu khi chọn bài "Chat nhóm -> checklist", nhóm đã lập tức bàn đến chuyện "viết chatbot Discord tự phân công". Tuy nhiên, sau khi vẽ workflow và làm validation, nhóm nhận ra rủi ro AI gán sai task rất phiền phức, nên đã kéo tư duy quay về hướng: "chỉ cần AI draft ra checklist để trưởng nhóm duyệt".
*   **Tôi có thay đổi ý kiến sau khi bị challenge không?**
    *   Có. Ban đầu tôi rất muốn nhóm chọn bài "Debug & Tìm Root Cause" của tôi vì nghĩ nó mang tính kỹ thuật cao. Nhưng sau khi Quyền challenge rằng debug có quá nhiều ngôn ngữ/thư viện và khó thu thập dữ liệu lỗi mà không bị lộ source code công ty, tôi đồng ý rằng bài đó scope quá rộng cho buổi lab và đồng thuận chuyển sang case chat nhóm.
*   **Tôi đóng góp gì thật sự vào artifact cuối?**
    *   Tôi đóng góp phần thiết lập ranh giới (Boundary) cho AI, lập luận phản biện để nhóm chọn mức Workflow thay vì Agent, và thiết kế kế hoạch Pilot chạy bán thủ công bằng prompt ở Phase 6 để nhóm có thể thực thi ngay ngày mai.
*   **Điều khó nhất khi viết Problem Statement là gì?**
    *   Khó nhất là việc định lượng Success Metric và xác định rõ Boundary. Rất dễ bị cuốn vào việc viết "giúp nhóm làm việc hiệu quả hơn" thay vì đưa ra các con số đo lường cụ thể như "giảm thời gian tổng hợp xuống dưới 15 phút" hay giới hạn "AI tuyệt đối không được tự gửi tin nhắn".
*   **Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**
    *   Tôi sẽ challenge nhóm kỹ hơn ở phần Validation (Bước 4.1). Mẫu khảo sát nhanh của nhóm mới có 7 người và 3 cuộc phỏng vấn nhanh, đa số là bạn bè quen biết nên phản hồi có thể hơi thiên vị. Nếu làm lại, tôi sẽ đề xuất nhóm lấy trực tiếp 5 chat log thật của các tuần trước để tự bóc thử xem tỷ lệ trôi tin nhắn thực tế là bao nhiêu %.

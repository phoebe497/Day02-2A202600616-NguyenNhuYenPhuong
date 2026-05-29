# 01 - Individual Problem Scan

Tài liệu này ghi lại quá trình scan rộng các vấn đề thực tế (Individual Problem Scan) và chi tiết Top 3 Problem Cards cùng workflow tương ứng của cá nhân.

---

## 1. Scan Rộng (Scan 12 Problems)

Dưới đây là danh sách 12 vấn đề thực tế được quan sát từ trải nghiệm học tập, nghiên cứu và phát triển phần mềm, áp dụng qua 4 lăng kính khác nhau để tìm ra pain-point thực sự.

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | **Tốn thời gian** | Mất nhiều thời gian Debugvì stack trace khó hiểu, docs rải rác, nhiều dependency và khó xác định nguyên nhân gốc rễ (root cause). | Student dev / Junior dev | Mất từ 30 phút đến vài giờ cho một . |
| 2 | **Tốn thời gian** | Khi nghiên cứu giải pháp kỹ thuật hoặc học AI, phải đọc nhiều paper dài để hiểu phương pháp, so sánh đóng góp và xem có ứng dụng được không. | Sinh viên AI / Developer / Researcher | Mất 30-90 phút cho mỗi paper để lọc thông tin cốt lõi. |
| 3 | **AI tốt hơn** | Đọc hiểu và lần theo luồng (tracing flow) các đoạn source code cũ, phức tạp và thiếu tài liệu hướng dẫn khi tiếp nhận task mới. | Developer mới join dự án / Junior dev | Mất 1-2 tiếng chỉ để hiểu được luồng xử lý của một module trước khi code. |
| 4 | **Lặp lại** | Cài đặt môi trường phát triển (development environment) khi clone project mới thường gặp lỗi phiên bản dependency, OS mismatch. | Student / Junior dev | Xảy ra mỗi khi bắt đầu project mới, mất trung bình 1-3 tiếng để cấu hình. |
| 5 | **Lặp lại** | Cập nhật API documentation thủ công mỗi khi thay đổi API schema hoặc endpoint trong quá trình phát triển dự án. | Backend developer | Lặp lại mỗi sprint, dễ quên hoặc cập nhật thiếu khiến frontend dev gọi sai API. |
| 6 | **Pain từ người khác** | Người kiểm duyệt (code reviewer) phải giải thích lặp đi lặp lại các lỗi cơ bản về convention, format, đặt tên biến hoặc check null cho junior devs. | Senior developer / Reviewer | Mất 20-30 phút/PR chỉ để nhắc nhở các lỗi coding style cơ bản trước khi review logic chính. |
| 7 | **Tốn thời gian** | Sinh viên mất nhiều thời gian hệ thống hóa kiến thức sau buổi học vì nội dung nằm rải rác giữa slide, ghi chú và lời giảng miệng. | Sinh viên technical subjects | Mất khoảng 1-3 giờ sau mỗi buổi học để tổng hợp lại. |
| 8 | **Pain từ người khác** | Sau seminar/workshop dài, người tham gia khó tổng hợp insight và action items từ buổi chia sẻ. | Sinh viên, người tham gia seminar | Phải ghi chú thủ công và dễ bỏ sót ý. |
| 9 | **AI tốt hơn** | Việc tìm kiếm solution cho bài toán khó cần đọc nhiều tài liệu và khó xác định thứ tự học tập hay lộ trình phù hợp. | Sinh viên IT, AI learner | Tốn nhiều giờ tìm kiếm và chọn lọc roadmap học tập phù hợp. |
| 10 | **Lặp lại** | Ghi chú và summarize tóm tắt nội dung sau mỗi buổi seminar, khóa học online diễn ra lặp lại nhiều lần. | Sinh viên, người học online | Mất 30-60 phút sau mỗi session để viết tóm tắt. |
| 11 | **Pain từ người khác** | Người dùng ChatGPT/ClauDebugthường gặp rate limit khi cần làm việc, Debughoặc nghiên cứu liên tục. | Người học AI, developer | Phải chờ quota reset gây gián đoạn workflow làm việc. |
| 12 | **Tốn thời gian** | Việc sử dụng API AI có chi phí cao khiến sinh viên khó build và duy trì các dự án cá nhân (siDebugprojects) lâu dài. | Sinh viên IT / AI | Không đủ budget để duy trì usage lâu dài. |

---

## 2. Lọc và Chọn Top 3

Từ 6 vấn đề trên, chọn ra Top 3 vấn đề có triển vọng cao nhất dựa trên mức độ cụ thể của actor, workflow và khả năng ứng dụng AI.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | **Debug & Tìm Root Cause** | Workflow rõ ràng, tần suất xảy ra cực kỳ thường xuyên (hằng ngày), impact lớn về mặt thời gian, dữ liệu input (code + log) rất sẵn có. | Chất lượng của đề xuất sửa lỗi từ AI có đủ chính xác không và có thể áp dụng được không. |
| 2 | **Screening Paper AI** | Pain rất rõ đối với người học/làm AI do số lượng paper liên quan quá nhiều, tốn nhiều thời gian đọc lướt. | Chất lượng summary có đủ chiều sâu không |
| 3 | **Đọc hiểu source code cũ khi onboarding** | Giúp giảm đáng kể thời gian onboarding và giảm tải cho senior khi phải giải thích code cũ. | Khả năng đọc hiểu toàn bộ cấu trúc thư mục lớn thay vì chỉ đọc từng file code rời rạc. |

---

## 3. Chi Tiết Top 3 Problem Cards

### PROBLEM CARD #1 - Debug & Tìm Root Cause (Case Chính)

*   **Problem 1 câu:** Developer/student mất nhiều thời gian Debug vì stack trace khó hiểu, tài liệu rải rác và khó xác định nguyên nhân gốc rễ (root cause) để sửa lỗi.
*   **Actor:** Student developer / junior developer.
*   **Thời điểm / bối cảnh:** Khi chạy thử nghiệm bị crash hoặc xảy ra lỗi logic/runtime trong quá trình phát triển phần mềm. Khi làm assignment, project cá nhân hoặc tham gia project nhóm.
*   **Current workflow (6 bước):**
    1. Chạy và nhận lỗi (error log / stack trace).
    2. Copy error message và tìm kiếm trên Google/StackOverflow.
    3. Đọc các tài liệu hướng dẫn liên quan (documentation).
    4. Lọc các câu trả lời, đối chiếu phiên bản thư viện/dependency.
    5. Thử sửa code (trial and error).
    6. Chạy lại (re-run) và kiểm tra kết quả (lặp lại nếu vẫn lỗi).
*   **Bottleneck:** Bước 2 và 3 - Phân tích stack trace để tìm ra nguyên nhân gốc rễ (mapping error message -> root cause) giữa hàng chục file dependency và tài liệu rải rác.
*   **Impact:** Mất từ 30 phút đến vài giờ cho một lỗi. Làm giảm hiệu suất viết code của dự án và gây nản lòng cho junior devs.
*   **Success metric:** Giảm thời gian trung bình xác định root cause từ 60 phút xuống dưới 15 phút.
*   **Non-AI alternative:** Tạo checklist debug các lỗi thường gặp trong team, cấu hình công cụ linter/logger chi tiết hơn, hoặc hỏi trực tiếp mentor/senior. (Hạn chế: checklist không thể bao quát hết các runtime động hoặc thư viện mới cập nhật).
*   **AI hypothesis:** AI hỗ trợ đọc hiểu stack trace kết hợp với context code xung quanh để chỉ ra nguyên nhân gốc rễ chính xác, tự động tra cứu nhanh tài liệu lỗi tương tự và đưa ra hướng dẫn sửa đổi. PM/Dev vẫn review giải pháp trước khi áp dụng.
*   **Quick gut:** `[X] Workflow` (hoặc có thể phát triển thành Agent nếu cần tương tác đa công cụ).

#### Draft Workflow cho Problem #1

```text
CURRENT STATE - Tốn khoảng 60-90 phút / 

[1 Chạy code & crash: 1'] 
→ [2 Đọc stack trace & copy error message: 4']
→ [3 Search Google/StackOverflow: 15'] 
→ [4 Đọc docs/so sánh thư viện & phiên bản: 20']  <-- Bottleneck chính
→ [5 Thử sửa code (thử & sai nhiều lần): 15'] 
→ [6 Chạy lại & kiểm tra kết quả: 5']

FUTURE STATE - Kỳ vọng giảm xuống 15 phút / 

[1 Chạy code & crash: 1'] 
→ [2 Auto-export stack trace & context code gửi tới AI: 1']  -- Tool/Script
→ [3 AI phân tích lỗi + mapping root cause + gợi ý cách sửa: 2']  -- AI Workflow Step
→ [4 Dev review nguyên nhân và áp dụng sửa code: 5']  <-- Human Boundary (Kiểm soát chất lượng)
→ [5 Dev chạy lại & kiểm tra kết quả: 6']

Fallback: AI giải thích sai hoặc ảo giác -> Dev quay về search Google/StackOverflow thủ công.
```

---

### PROBLEM CARD #2 - Screening Paper AI

*   **Problem 1 câu:** Sinh viên AI và developer mất nhiều thời gian đọc các paper dài chỉ để quyết định xem nghiên cứu đó có phù hợp với bài toán thực tế của mình hay không.
*   **Actor:** Sinh viên AI / developer / researcher.
*   **Thời điểm / bối cảnh:** Giai đoạn đầu nghiên cứu giải pháp kỹ thuật cho dự án mới hoặc làm nghiên cứu khoa học.
*   **Current workflow (6 bước):**
    1. Tìm kiếm và tải paper liên quan (arXiv, Google Scholar).
    2. Đọc abstract và intro để nắm ý tưởng chung.
    3. Đọc phần Methodology/Approach để xem cách giải quyết.
    4. Đọc phần Results/Experiments để so sánh hiệu năng.
    5. Đọc phần Contribution để tìm điểm mới (novelty).
    6. Mapping và đối chiếu xem có áp dụng được vào bài toán hiện tại không.
*   **Bottleneck:** Bước 3 và 6 - Đọc hiểu chi tiết kỹ thuật từ paper dài (thường 8-15 trang) để đối chiếu mức độ tương thích với bài toán thực tế của mình.
*   **Impact:** Mất từ 30-90 phút/paper. Nếu phải screening 15-20 paper thì mất cả tuần chỉ để lọc tài liệu.
*   **Success metric:** Giảm thời gian screening một paper từ 60 phút xuống dưới 15 phút.
*   **Non-AI alternative:** Đọc lướt (skimming) nhanh theo kỹ thuật đọc (chỉ đọc abstract, biểu đồ, kết luận) hoặc đọc blog review paper của người khác. (Hạn chế: blog review thường không cập nhật các paper mới hoặc thiếu chi tiết kỹ thuật cụ thể phù hợp với bài toán của mình).
*   **AI hypothesis:** AI hỗ trợ đọc hiểu file PDF paper, tự động tóm tắt methodology, so sánh contribution với các phương pháp cũ dưới dạng bảng cấu trúc, và phân tích độ phù hợp dựa trên mô tả bài toán hiện tại của researcher.
*   **Quick gut:** `[X] Workflow`.

#### Draft Workflow cho Problem #2

```text
CURRENT STATE - Tốn khoảng 60 phút / paper

[1 Search & tải paper: 5']
→ [2 Đọc abstract & intro: 10']
→ [3 Đọc Methodology để hiểu approach: 20']  <-- Bottleneck chính
→ [4 Đọc Contribution & Results: 10']
→ [5 Tự đối chiếu với bài toán hiện tại: 15']

FUTURE STATE - Kỳ vọng giảm xuống 12 phút / paper

[1 Tải paper lên hệ thống: 1']
→ [2 AI phân tích, tóm tắt methodology & trích xuất contribution: 2']  -- AI Workflow Step
→ [3 AI đối chiếu sự phù hợp với bài toán của user (đã input trước): 1']  -- AI Workflow Step
→ [4 User đọc bản tóm tắt + đối chiếu của AI để ra quyết định Keep/Discard: 8']  <-- Human Boundary
```

---

### PROBLEM CARD #3 - Đọc hiểu source code cũ khi onboarding

*   **Problem 1 câu:** Developer mới tiếp nhận dự án mất nhiều thời gian đọc hiểu các đoạn source code cũ, phức tạp và thiếu tài liệu hướng dẫn.
*   **Actor:** Developer mới join dự án / Junior developer.
*   **Thời điểm / bối cảnh:** Khi được giao bảo trì, sửa lỗi hoặc thêm tính năng mới trên một module code cũ của công ty.
*   **Current workflow (5 bước):**
    1. Đọc file code chính được giao.
    2. Trace ngược/xuôi các hàm được gọi (follow the call stack).
    3. Tìm kiếm documentation hoặc comment trong repo (thường rất ít hoặc out-of-date).
    4. Chạy Debug từng bước (breakpoint deging) để xem luồng dữ liệu.
    5. Hỏi đồng nghiệp (senior) phụ trách cũ để giải thích logic.
*   **Bottleneck:** Bước 2 và 4 - Tự lần theo luồng codephức tạp và suy đoán mục đích logic của tác giả cũ.
*   **Impact:** Mất 1-2 tiếng chỉ để hiểu luồng của một chức năng đơn giản, làm chậm tiến độ xử lý task.
*   **Success metric:** Giảm thời gian đọc hiểu luồng code chính của một module từ 120 phút xuống dưới 30 phút.
*   **Non-AI alternative:** Tự vẽ sơ đồ lớp (class diagram) thủ công, viết các lệnh logger in ra console để theo dõi luồng chạy. (Hạn chế: mất nhiều công sức thiết lập và khó khăn với codebase lớn).
*   **AI hypothesis:** AI phân tích cấu trúc module code liên quan, tự động giải thích sơ đồ luồng dữ liệu (flowchart) và mục đích của từng hàm bằng ngôn ngữ tự nhiên để developer nắm được nhanh chóng.
*   **Quick gut:** `[X] Workflow`.

#### Draft Workflow cho Problem #3

```text
CURRENT STATE - Tốn khoảng 120 phút / module

[1 Đọc file code chính: 15']
→ [2 Tracing call stack thủ công qua nhiều file: 45']  <-- Bottleneck chính
→ [3 Chạy Debugtừng bước để xem biến đổi dữ liệu: 40']
→ [4 Hỏi đồng nghiệp nếu hoàn toàn bế tắc: 20']

FUTURE STATE - Kỳ vọng giảm xuống 25 phút / module

[1 Chọn module code cần đọc: 1']
→ [2 AI phân tích và tự động vẽ flowchart của luồng code + giải thích logic: 4']  -- AI Workflow Step
→ [3 Developer đọc phân tích và sơ đồ của AI: 10']
→ [4 Developer đối chiếu trực tiếp với code và chạy thử nghiệm thực tế: 10']  <-- Human Boundary
```

---

## 4. Lựa Chọn Card Muốn Pitch Nhất

*   **Card tôi muốn pitch nhất:** **PROBLEM CARD #1 - Debug & Tìm Root Cause**
*   **Vì sao:**
    *   Đây là nỗi đau thường trực nhất của bất kỳ developer nào từ junior đến student, xảy ra hằng ngày, lặp đi lặp lại nhiều lần.
    *   Mức độ phù hợp với AI rất cao vì AI rất mạnh trong việc đọc hiểu log lỗi, so sánh code và tra cứu tài liệu nhanh.
    *   Workflow hiện tại có baseline thời gian cực kỳ rõ rệt (60-90 phút) và việc rút ngắn xuống 15 phút sẽ mang lại giá trị thực tiễn rất lớn, làm tăng sự hứng khởi cho người lập trình.
*   **Câu hỏi tôi muốn nhóm challenge:**
    *   *"Làm thế nào để thu thập đủ ngữ cảnh (context) của lỗi (như các file code liên quan, file cấu hình dự án, phiên bản thư viện) mà không làm rò rỉ dữ liệu nhạy cảm hoặc mã nguồn độc quyền của công ty?"*
    *   *"Làm thế nào để đo lường độ chính xác và mức độ an toàn của đề xuất sửa lỗi từ AI để tránh trường hợp AI đề xuất code chạy được nhưng gây ra lỗi bảo mật nghiêm trọng khác?"*

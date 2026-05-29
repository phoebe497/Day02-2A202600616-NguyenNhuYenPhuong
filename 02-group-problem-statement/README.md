# 02 — Group Problem Statement

Tài liệu này ghi lại toàn bộ quá trình thảo luận nhóm để chọn ra một bài toán chính (Group Convergence), thực hiện kiểm chứng nhanh (Validation), nghiên cứu giải pháp (Research), lập Problem Statement và đưa ra quyết định Go/No-Go.

---

## 1. Group Convergence

Nhóm gồm 3 học viên (Đào Duy Quyền, Yến Phương, Khánh An) cùng trình bày các đề xuất cá nhân, gom nhóm và lựa chọn vấn đề tiềm năng nhất.

### Bước 3.1 — Trình bày top 3

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Đào Duy Quyền | Tìm kiếm và trích xuất số liệu từ các file báo cáo PDF dài | Sinh viên | Tìm đúng chỗ có số liệu và xác nhận số liệu trong bảng/biểu mất nhiều thời gian, dễ bỏ sót. | Đau thật, workflow rõ, dễ đo thời gian và số lỗi trích sai. |
| 2 | Đào Duy Quyền | Sau khi chat nhóm kết thúc, trưởng nhóm mất thời gian biến các đoạn trao đổi rời rạc thành checklist việc làm rõ ràng, có owner và deadline. | Trưởng nhóm | Thông tin rải rác, nhiều đoạn chat không liên tục, task và owner dễ bị lẫn. | Rất thực tế, đầu ra rõ, nhìn là thấy có thể pitch được. |
| 3 | Đào Duy Quyền | Lớp trưởng hoặc trưởng ban phải trả lời lặp lại cùng một thông tin, quy định và lịch trình cũ trên Discord vì thành viên không tìm lại được thông báo gốc.| Lớp trưởng | Tìm lại thông tin cũ và trả lời lặp lại liên tục. | Lặp lại rõ nhưng có khả năng chỉ cần rule/FAQ là đã xử lý nhiều. |
| 4 | Yến Phương | Debug & Tìm Root Cause | Developer | Phân tích stack trace để tìm ra nguyên nhân gốc rễ (mapping error message -> root cause) giữa hàng chục file dependency và tài liệu rải rác. | Có pain thật nhưng khá nặng, cần kiểm tra scope có quá rộng không. |
| 5 | Yến Phương | Screening Paper AI | Sinh viên AI, Researcher | Đọc hiểu chi tiết kỹ thuật từ paper dài (thường 8-15 trang) để đối chiếu mức độ tương thích với bài toán thực tế của mình. | Đúng nhu cầu, AI có đất, nhưng phải thu hẹp rất kỹ để không bị lan quá rộng. |
| 6 | Yến Phương| Đọc hiểu source code cũ khi onboarding | Developer | Tự lần theo luồng code phức tạp và suy đoán mục đích logic của tác giả cũ. | Workflow rất thật, đau đều, dễ pitch nếu chốt đúng người dùng. |
| 7 | Khánh An| Học viên hỏi lại Lab Coach về những câu hỏi gần tương tự nhau | Lab Coach, học viên | Lab Coach phải đọc lại context và trả lời lặp lại nhiều câu hỏi tương tự mỗi tuần | Pain lặp lại rõ, nhưng có vẻ rule/process fix sẽ giải được phần lớn. |
| 8 | Khánh An|Debug bài làm mà chưa biết lỗi xuất phát từ chỗ nào | Học viên  | Học viên mất nhiều thời gian đọc error, search tài liệu và thử sai trước khi xác định được nguyên nhân thật sự | Đau thật với học viên |
| 9 | Khánh An | Ôn bài kiến thức từ nhiều buổi, trên nhiều nền tảng LMS, Github, bài tập thực hành | Học viên | Học viên tự chủ động ôn lại bài với lượng kiến thức khổng lồ trước mỗi buổi kiểm tra hoặc sau mỗi buổi học. | Có nhu cầu thật nhưng còn hơi chung, cần scope cụ thể hơn. |

### Bước 3.2 — Gom trùng / cluster

Nhóm tiến hành phân loại các candidate thành các cụm chủ đề chung để dễ đánh giá:

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A. Trích xuất & tổng hợp thông tin** | Candidate 1, 5, 9 | Gom thông tin/số liệu từ tài liệu dài (PDF, Paper, LMS) để phục vụ học tập, nghiên cứu. | Pain lớn về thời gian đọc hiểu và lọc thông tin. |
| **B. Tối ưu hóa giao tiếp & quản lý** | Candidate 2, 3, 7 | Biến đổi thông tin giao tiếp (chat nhóm, câu hỏi trùng lặp) thành checklist hoặc FAQ. | Lặp lại thường xuyên trong quản lý nhóm/lớp học. |
| **C. Debug & khắc phục lỗi kỹ thuật** | Candidate 4, 8 | Hỗ trợ developer và học viên tìm nguyên nhân lỗi code từ log/stack trace. | Pain rất lớn nhưng scope kỹ thuật rộng. |

### Bước 3.3 — Shortlist

Sau khi thảo luận, nhóm đã rút gọn danh sách xuống còn 3 candidate tiềm năng nhất:

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| **Sau khi chat nhóm kết thúc, trưởng nhóm mất thời gian biến các đoạn trao đổi rời rạc thành checklist việc làm rõ ràng, có owner và deadline.** | Actor khá rõ, workflow thật và rất quen thuộc, bottleneck nằm ở việc bóc action item từ thread rời rạc. Impact đo được bằng thời gian tổng hợp và số task bị quên/hỏi lại. Dễ vẽ before/after workflow và so sánh Rule / Workflow / Agent. | Cần kiểm tra xem team đã có format chốt việc sẵn chưa. Nếu đã có template tốt thì mức pain giảm, nhưng thường vẫn đủ rõ để pitch. |
| **Debug & Tìm Root Cause** | Workflow debug là workflow thật, actor developer rõ, bottleneck cụ thể ở mapping error message -> root cause giữa nhiều file dependency và tài liệu rải rác. Impact có thể đo bằng thời gian tìm nguyên nhân gốc và số vòng thử sai. Dễ so sánh Rule / Workflow / Agent. | Scope dễ bị quá rộng nếu không chốt một stack, một loại bug, hoặc một bối cảnh cụ thể. Có nguy cơ trượt sang troubleshooting chung chung. |
| **Ôn bài kiến thức từ nhiều buổi, trên nhiều nền tảng LMS, Github, bài tập thực hành** | Actor là học viên khá rõ, workflow ôn tập sau buổi học và trước kiểm tra là workflow thật, pain lặp lại và có thể đo bằng thời gian chuẩn bị bài và mức độ nhớ lại. Có thể vẽ before/after workflow nếu chốt được output ôn tập. | Còn hơi rộng vì nguồn quá nhiều (LMS, GitHub, bài tập, note), chưa rõ output cuối là summary, flashcard hay question set. Cần thu hẹp scope trước khi deep-dive. |

### Bước 3.4 — Chấm điểm để đồng thuận

Chấm điểm theo thang 1-5 nhằm thảo luận sâu và đưa ra quyết định đồng thuận cuối cùng:

| Candidate | Actor rõ | Workflow rõ | Pain có bằng chứng | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Chat nhóm -> checklist công việc** | 5 | 5 | 3 | 4 | 4 | 4 | 5 | **30** |
| **Debug & Tìm Root Cause** | 5 | 3 | 3 | 3 | 2 | 5 | 4 | **25** |
| **Ôn kiến thức đa nguồn** | 5 | 4 | 3 | 3 | 3 | 5 | 4 | **27** |

*   **Candidate nhóm chọn:** Chat nhóm -> checklist công việc
*   **Vì sao chọn:**
    *   Bài này có actor rất rõ, workflow thật và rất quen thuộc, bottleneck nằm đúng ở bước bóc action item từ thread rời rạc.
    *   Impact đo được bằng thời gian tổng hợp và số task bị bỏ sót hoặc phải hỏi lại.
    *   Scope đủ nhỏ để làm trong lab hôm nay và dễ so sánh Rule / Workflow / Agent.
*   **Vì sao không chọn các candidate còn lại:**
    *   *Debug & Root Cause:* Có pain thật nhưng scope dễ rộng quá, nếu không chốt rõ stack, kiểu bug và bối cảnh thì rất dễ trượt sang troubleshooting chung chung.
    *   *Ôn kiến thức đa nguồn:* Là nhu cầu thật nhưng hiện còn hơi rộng, chưa chốt rõ output ôn tập là summary, flashcard hay question set nên khó đi sâu ngay.
*   **Nếu có disagreement, nhóm xử lý thế nào:**
    *   Nhóm sẽ quay lại 3 tiêu chí chốt: bài nào scope nhỏ nhất, hiểu workflow thật nhất, và đo được nhanh nhất trong lab hôm nay.
    *   Nếu vẫn ngang nhau, ưu tiên bài mà cả nhóm có thể validate ngay bằng một ví dụ workflow thật.

---

## 2. Quick Validation & Research

### Bước 4.1 — Quick Validation

| Nguồn | Số người / mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| **Quick Interview** | 3 người | 2/3 người nói sau khi chat xong đều phải đọc lại thread để bóc task, owner, deadline; bước đau nhất là tổng hợp lại thành checklist. | 1 người nói nếu team có template chốt việc sẵn thì pain giảm khá nhiều. | Thu hẹp problem thành biến thread chat sau thảo luận thành checklist có owner/deadline, không ôm toàn bộ chat. |
| **Mini Poll** | 7 người | 5/7 người gặp vấn đề ít nhất mỗi tuần; phần đau nhất là task trôi và không rõ ai phụ trách. | 2/7 người đã có pinned template hoặc summary sẵn nên ít đau hơn. | Giữ hướng Workflow, thêm non-AI alternative là template + rule chốt việc. |
| **Review Thread** | 2 thread | Trong thread thật có nhiều follow-up, task bị nhắc lại, và có đoạn không rõ owner. | Chưa đủ log để kết luận rộng, cần thêm mẫu thật nếu muốn chắc hơn. | Dùng thêm 2-3 thread thật làm evidence trước khi chốt Problem Statement. |

*   **Kết luận nhanh sau validation:**
    *   Pain có thật và lặp lại. Bước đau nhất là chuyển hội thoại rời rạc thành checklist có owner/deadline.
    *   Non-AI alternative vẫn có giá trị, nên bài này hợp với Workflow hơn là Agent.
    *   Nếu làm sâu, scope nên giữ ở mức: chat nhóm -> checklist công việc, không mở rộng thành chatbot tổng quát.

### Bước 4.2 — Research giải pháp đã có

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Slack AI** | [Slack AI](https://slack.com/help/articles/25076892548883-Guide-to-AI-features-in-Slack) | Tóm tắt channel, DM, thread; search theo nội dung trong Slack. | Native ngay trong nơi chat diễn ra, rất hợp để “catch up” nhanh. | Dừng chủ yếu ở tóm tắt và tìm kiếm, chưa tự biến hội thoại thành checklist có owner/deadline. | Nếu nguồn là Slack, bước đầu tiên nên là summarize thread rồi mới chuyển sang checklist. |
| **Discord Summaries** | [Discord summaries](https://support.discord.com/hc/en-us/articles/12926016807575-In-Channel-Conversation-Summaries) | Tóm tắt các cuộc hội thoại trong channel thành topic và snippet. | Hữu ích để đọc lại cuộc trò chuyện dài. | Tính năng còn là experiment, giới hạn server, và không nhắm vào task extraction. | Nếu nhóm dùng Discord, native AI hiện nghiêng về catch-up chứ chưa phải tasking. |
| **Notion AI Meeting Notes** | [Notion AI](https://www.notion.com/help/ai-meeting-notes) | Transcribe cuộc họp, rút key points và action items. | Có sẵn luồng từ hội thoại sang action items, có citation. | Thiên về meeting transcript hơn là chat thread rời rạc; cần quyền audio/screen. | Đây là pattern tốt: AI đọc nội dung hội thoại rồi bóc ra action items, nhưng vẫn trong bối cảnh có cấu trúc. |
| **ClickUp AI** | [ClickUp AI](https://clickup.com/ai) | Lấy action items từ docs, chats, meetings và biến thành task / plan. | Có chats trong input. | Hợp nhất khi team đã làm việc trong ClickUp; vẫn cần kiểm tra lại output trước khi giao việc. | Có bằng chứng mạnh rằng bài toán này hợp với Workflow hơn là Agent. |

*   **Research Takeaway:** Không nên build một agent tự chạy toàn bộ việc phân phối task ngay. Hướng hợp lý hơn là Workflow: tự động lấy/cấu trúc dữ liệu ở các bước rõ, dùng AI để draft checklist, người dùng (trưởng nhóm) review trước khi chốt gửi.

---

## 3. Workflow & Problem Statement v0

### Bước 5.1 — Current Workflow bản nhóm

```text
CURRENT STATE — chat nhóm -> checklist công việc

+------------------------------------------------------------------+
| 1. Paste thread log                                              |
| Actor      : Trưởng nhóm / người tổng hợp                        |
| Input      : Thread chat sau khi trao đổi xong                   |
| Output     : Thread log đã gom lại                               |
| Time/freq  : 5-10 phút / mỗi lần                                 |
| Handoff    : Group chat -> người tổng hợp                        |
| Bottleneck : Thread dài, nhiều đoạn rời rạc, khó đọc lại theo    |
|              thứ tự                                              |
+------------------------------------------------------------------+
                                  |
                                  v
+------------------------------------------------------------------+
| 2. AI tạo checklist có owner và deadline                         |
| Actor      : AI hỗ trợ                                           |
| Input      : Thread log đã paste                                 |
| Output     : Draft checklist (task / owner / deadline)           |
| Time/freq  : 1-3 phút / mỗi lần                                  |
| Handoff    : Người tổng hợp -> AI                                 |
| Bottleneck : Bóc task thiếu ngữ cảnh hoặc gán owner/deadline sai |
+------------------------------------------------------------------+
                                  |
                                  v
+------------------------------------------------------------------+
| 3. Trưởng nhóm sửa nhanh                                          |
| Actor      : Trưởng nhóm                                         |
| Input      : Draft checklist từ AI                               |
| Output     : Checklist đã chỉnh đúng                              |
| Time/freq  : 5-15 phút / mỗi lần                                 |
| Handoff    : AI -> người phụ trách                                |
| Bottleneck : Phải kiểm lại task trùng, thiếu, hoặc owner lệch    |
+------------------------------------------------------------------+
                                  |
                                  v
+------------------------------------------------------------------+
| 4. Gửi bản cuối                                                  |
| Actor      : Trưởng nhóm                                         |
| Input      : Checklist cuối                                       |
| Output     : Bản chốt gửi cho cả nhóm                            |
| Time/freq  : 1-2 phút / mỗi lần                                  |
| Handoff    : Người phụ trách -> cả nhóm                           |
| Bottleneck : Nếu format chưa rõ, người nhận vẫn phải hỏi lại    |
+------------------------------------------------------------------+

Fallback: nếu chat quá rối / thiếu ngữ cảnh
+------------------------------------------------------------------+
| Dùng template thủ công                                           |
| Actor      : Trưởng nhóm                                         |
| Input      : Chat + template checklist chuẩn                     |
| Output     : Checklist thủ công                                  |
| Time/freq  : 10-20 phút / mỗi lần                                |
| Handoff    : Chat -> template -> người phụ trách -> cả nhóm      |
| Bottleneck : Tốn công điền lại nhưng ổn định hơn                 |
+------------------------------------------------------------------+
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Handoff | Bottleneck |
|---|---|---|---|---|---|---|
| **1. Paste thread log** | Trưởng nhóm / người tổng hợp | Thread chat raw | Toàn bộ nội dung trao đổi được đưa vào một chỗ | 5-10 phút / mỗi lần | Group chat -> người tổng hợp | Thread dài, nhiều đoạn rời rạc, khó đọc lại theo thứ tự |
| **2. AI tạo checklist** | AI hỗ trợ | Thread log đã paste | Draft checklist gồm task, owner, deadline, notes | 1-3 phút / mỗi lần | Người tổng hợp -> AI | AI có thể bóc task chưa chính xác hoặc thiếu ngữ cảnh |
| **3. Trưởng nhóm sửa** | Trưởng nhóm | Draft checklist từ AI | Checklist đã chỉnh đúng ý nhóm | 5-15 phút / mỗi lần | AI -> người phụ trách | Phải kiểm tra lại owner, deadline, task bị sót hoặc trùng |
| **4. Gửi bản cuối** | Trưởng nhóm | Checklist đã sửa | Bản checklist cuối gửi cho cả nhóm | 1-2 phút / mỗi lần | Người phụ trách -> cả nhóm | Nếu format chưa rõ thì người nhận vẫn phải hỏi lại |

*   **Bottleneck chính hiện tại:** Biến thread chat rối rắm thành checklist có owner/deadline chính xác.

### Bước 5.2 — Future Workflow bản nhóm

```text
FUTURE STATE — chat nhóm -> checklist công việc (Workflow tối ưu)

+------------------------------------------------------------------+
| 1. Chuẩn hóa thread theo template                                |
| Actor      : Trưởng nhóm / người tổng hợp                        |
| Type       : Rule                                                |
| Input      : Thread chat raw                                     |
| Output     : Thread đã được gắn mốc, lọc bớt noise                |
| Time/freq  : 3-5 phút / mỗi lần                                  |
| Handoff    : Group chat -> template chuẩn                        |
| Bottleneck : Thread dài, thiếu cấu trúc, nhiều đoạn lạc chủ đề   |
+------------------------------------------------------------------+
                                  |
                                  v
+------------------------------------------------------------------+
| 2. AI draft checklist                                            |
| Actor      : AI hỗ trợ                                           |
| Type       : AI / Workflow                                       |
| Input      : Thread đã chuẩn hóa                                 |
| Output     : Draft checklist (task / owner / deadline / note)    |
| Time/freq  : 1-3 phút / mỗi lần                                 |
| Handoff    : Người tổng hợp -> AI                                |
| Bottleneck : AI có thể bóc thiếu task hoặc gán owner/deadline sai|
+------------------------------------------------------------------+
                                  |
                                  v
+------------------------------------------------------------------+
| 3. Trưởng nhóm review & chốt                                     |
| Actor      : Trưởng nhóm                                         |
| Type       : Human                                               |
| Input      : Draft checklist                                     |
| Output     : Checklist cuối                                      |
| Time/freq  : 5-10 phút / mỗi lần                                |
| Handoff    : AI -> người phụ trách                               |
| Boundary   : AI không tự chốt owner/deadline cuối                |
| Bottleneck : Phải kiểm lại task trùng, thiếu, hoặc lệch ngữ cảnh |
+------------------------------------------------------------------+
                                  |
                                  v
+------------------------------------------------------------------+
| 4. Gửi checklist theo format cố định                             |
| Actor      : Trưởng nhóm                                         |
| Type       : Rule                                                |
| Input      : Checklist cuối                                      |
| Output     : Bản chốt gửi cho cả nhóm                           |
| Time/freq  : 1-2 phút / mỗi lần                                 |
| Handoff    : Người phụ trách -> cả nhóm                          |
| Bottleneck : Nếu format chưa rõ, người nhận vẫn hỏi lại         |
+------------------------------------------------------------------+

Fallback: nếu chat quá rối / thiếu ngữ cảnh -> Dùng template thủ công trước
```

*   **Before/After Impact Table:**

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| **Số bước** | 5 | 4 | Giảm một bước xử lý trung gian nhờ chuẩn hóa. |
| **Tổng thời gian** | 20-30 phút | 8-12 phút | Giảm mạnh ở đoạn đọc lại và bóc task thủ công. |
| **Số bước thủ công** | 5 | 3 | Rule/template giúp giảm bớt thao tác nặng nhọc. |
| **Bottleneck chính** | Đọc thread rời rạc và bóc action item | Review và chốt owner/deadline | Bottleneck dịch chuyển từ làm thủ công sang kiểm tra chất lượng. |
| **Risk mới** | Chậm, dễ quên task, dễ phải hỏi lại | AI bóc sai task/owner/deadline | Khắc phục bằng human review bắt buộc và fallback template. |

### Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm hoặc người tổng hợp việc sau khi cuộc thảo luận kết thúc. |
| **Workflow** | Thread chat kết thúc $\rightarrow$ đọc lại nội dung rời rạc $\rightarrow$ bóc action item $\rightarrow$ gán owner/deadline $\rightarrow$ gửi checklist cho cả nhóm. |
| **Bottleneck** | Đọc lại thread dài và rời rạc để chốt đúng task, owner và deadline. |
| **Impact** | Mỗi lần tổng hợp mất khoảng 20-30 phút, dễ bỏ sót task hoặc phải hỏi lại nhiều lần, làm chậm việc chốt đầu việc của cả nhóm. |
| **Success Metric** | Giảm thời gian tổng hợp checklist xuống dưới 10-15 phút và giảm số task bị bỏ sót / phải nhắc lại. |
| **Boundary** | AI chỉ hỗ trợ draft checklist; người thật vẫn phải review và chốt owner/deadline cuối cùng. Không để AI tự gửi bản cuối khi chưa được kiểm tra. |

---

## 4. Rule / Workflow / Agent & Decision

### Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro |
|---|---|---|---|
| **Rule** | Dùng template meeting notes + format chat cố định để mọi người tự điền. | Team nhỏ, ít thảo luận, có kỷ luật cao. | Thành viên không tuân thủ format, vẫn phải đọc thủ công. |
| **Workflow** | AI đọc thread chat raw $\rightarrow$ trích xuất Task/Owner/Deadline $\rightarrow$ tạo draft checklist $\rightarrow$ Trưởng nhóm review. | Thảo luận dài, nhiều task và nhiều người tham gia. | AI hiểu sai context chat hoặc gán sai deadline/owner. | 
| **Agent** | Agent tự theo dõi đoạn chat, tự động hỏi lại để làm rõ, tự assign task và nhắc deadline trực tiếp trong group. | Team rất lớn, nhiều giai đoạn dự án phức tạp cần tự động hóa cao. | Over-engineering, dễ spam nhóm chat, khó kiểm soát hành vi của AI. |

*   **Mức chọn:** Workflow
*   **Vì sao chọn:**
    *   Workflow xử lý tuần tự, đầu vào và đầu ra đã được cấu trúc rõ ràng.
    *   AI phát huy đúng thế mạnh về ngôn ngữ ở các bước: tóm tắt, trích xuất action items và định dạng checklist.
    *   Có human boundary rõ (trưởng nhóm bắt buộc phải review), giúp giảm thiểu rủi ro của AI.
    *   Không cần AI tự đưa ra quyết định độc lập hay tự tương tác/điều phối động với nhóm.
*   **Vì sao không chọn mức đơn giản hơn (Rule):**
    *   Rule thuần túy không thể tự động hóa phần đọc hiểu các thảo luận tự nhiên và rời rạc trong group chat.
    *   Thực tế cho thấy mọi người khó duy trì một format chat cố định khi đang thảo luận sôi nổi.

### Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm hoặc người tổng hợp việc sau khi cuộc thảo luận kết thúc. |
| **Workflow** | Dán thread chat raw $\rightarrow$ Chuẩn hóa & lọc bớt noise (Rule) $\rightarrow$ AI trích xuất task, owner, deadline (Workflow step) $\rightarrow$ Trưởng nhóm review & chốt (Human boundary) $\rightarrow$ Gửi checklist theo định dạng chuẩn. |
| **Bottleneck** | Đọc lại thread dài và rời rạc để bóc tách đúng việc cần làm, phân công đúng người (owner) và thời hạn (deadline). |
| **Impact** | Mỗi lần tổng hợp mất khoảng 20-30 phút, dễ bỏ sót task hoặc phải hỏi lại nhiều lần, làm chậm tiến độ chốt công việc của cả nhóm. |
| **Success Metric** | Giảm thời gian tổng hợp checklist xuống dưới 10-15 phút; giảm số lượng task bị bỏ sót hoặc gán sai người (giảm tỉ lệ phải hỏi lại/nhắc lại từ 4-5 lần/tuần xuống dưới 1-2 lần/tuần). |
| **Boundary** | AI không được tự động gửi checklist khi chưa có sự xác nhận của người dùng. AI không tự quyết định thời hạn (deadline) hoặc thay đổi nhân sự mà không có trong log chat. |
| **AI intervention point** | Giai đoạn trích xuất dữ liệu: Sau khi thread chat được dán vào hệ thống, AI tự động phân tích và tạo draft checklist trước khi trưởng nhóm review. |
| **Mức chọn** | **Workflow**: Kết hợp Rule (tiền xử lý input & format output), AI (draft checklist) và Human (review/edit chốt cuối). |
| **Rủi ro & người thật kiểm tra** | **Rủi ro:** AI có thể gán sai owner hoặc deadline do hiểu sai đại từ xưng hô hoặc các câu đùa/context ẩn trong chat. <br>**Người thật kiểm tra:** Trưởng nhóm (hoặc người tổng hợp) bắt buộc phải kiểm tra đối chiếu draft checklist với thread chat gốc, đặc biệt là các phần AI ghi chú là "không chắc chắn" (fallback), trước khi gửi. |

### Bước 6.3 — Final Decision

*   **Decision:** Go (với scope nhỏ)
*   **Lý do:**
    1. Bài toán có actor, workflow và bottleneck vô cùng cụ thể, lặp đi lặp lại hàng tuần.
    2. Baseline và success metric đo lường được trực tiếp bằng thời gian (phút).
    3. Rủi ro của AI được kiểm soát hoàn toàn nhờ bước Human-in-the-loop (trưởng nhóm review trước khi gửi).
    4. Không bị over-engineering so với phương án build Agent.
*   **Kế hoạch tiếp theo (Pilot nhỏ nhất):**
    *   **Mẫu thử nghiệm:** Trưởng nhóm chuẩn bị 3 đoạn chat log thực tế từ các dự án/bài tập nhóm gần nhất.
    *   **Thử nghiệm bán thủ công (Semi-manual):** Copy-paste các đoạn chat này vào ChatGPT/Claude sử dụng một prompt hệ thống được thiết kế sẵn để AI trích xuất checklist.
    *   **Đo lường:** Trưởng nhóm tự thực hiện review, ghi lại thời gian hoàn thành (mục tiêu < 10 phút) và kiểm tra xem có lỗi sai/bỏ sót nào nghiêm trọng từ AI không.
    *   **Thời gian đánh giá:** Thử nghiệm trong 2 tuần họp nhóm tiếp theo trước khi chốt giải pháp tự động hóa luồng.

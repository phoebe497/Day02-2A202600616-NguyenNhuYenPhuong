# Day 02 Lab — Worksheet

## Nguyên tắc

1. **Problem first, not AI first.** Đừng bắt đầu bằng chatbot/agent. Bắt đầu bằng actor, workflow, bottleneck, metric.
2. **Cá nhân scan rộng, nhóm hội tụ.** Mỗi người chuẩn bị nhiều candidate problems; nhóm chọn một candidate đáng đào sâu.
3. **Vẽ workflow trước khi chọn AI.** Nếu chưa thấy bước nào nghẽn, chưa được chọn Rule / Workflow / Agent.
4. **Không cần AI vẫn là kết luận tốt.** Điểm nằm ở chất lượng lập luận, không nằm ở độ "ngầu" của solution.
5. **AI hỗ trợ, không thay quyết định.** Dùng AI để hỏi ngược, phản biện, vẽ lại, research. Người học tự kiểm và tự chốt.
6. **Tự làm trước, AI sau.** Những phần thể hiện suy nghĩ cá nhân như pitch, challenge và reflection không được để AI viết thay.

## Repo nộp bài

Mỗi học viên nộp một repo cá nhân:

```text
Day02-MãHọcViên-HọVàTên/
├── README.md
├── 01-individual-problem-scan/
├── 02-group-problem-statement/
└── 03-individual-reflection/
```

File phụ như ảnh workflow, Mermaid, survey screenshot, research notes đặt cùng prefix:

```text
01-individual-problem-scan-workflow-card-1.png
02-group-problem-statement-workflow.pdf
02-group-problem-statement-research-notes.md
```

Lưu ý: `02-group-problem-statement/` là **bản nộp nhóm**. Nhóm 3-4 người làm chung một bản cuối, sau đó mỗi học viên copy bản này vào repo cá nhân của mình.

## Output cuối cùng

| Phần | Ai làm | Cần có gì |
|---|---|---|
| `01-individual-problem-scan/` | Cá nhân | 5+ problems, top 3 Problem Cards, draft workflow trước/sau cho top 3 |
| `02-group-problem-statement/` | Nhóm | Nhật ký hội tụ, kiểm chứng nhanh, research giải pháp, workflow trước/sau, Problem Statement v0/v1, Rule / Workflow / Agent, quyết định cuối |
| `03-individual-reflection/` | Cá nhân | Vai trò trong nhóm, cách dùng AI, học được gì, nếu làm lại sẽ đổi gì |

## Tiêu chí đánh giá nhanh

Chi tiết rubric nằm trong `README.md`. Bảng dưới đây giúp bạn biết phần nào đang ảnh hưởng tới điểm khi làm worksheet.

| Nhóm / cá nhân | Thành phần | Điểm |
|---|---|---:|
| Nhóm | Workflow trước/sau | 15 |
| Nhóm | Problem Statement + metric + boundary | 20 |
| Nhóm | Độ phù hợp với AI + phương án thay thế | 15 |
| Nhóm | Chất lượng quyết định Go / Not Yet / No-Go | 10 |
| Cá nhân | Scan problem + top 3 Problem Cards | 12 |
| Cá nhân | Tham gia pitch + challenge | 12 |
| Cá nhân | Reflection cá nhân | 10 |
| Cá nhân | Kiểm tra hiểu bài cá nhân | 6 |

Bonus tối đa +10 điểm:

- +3 nếu scan rộng hơn yêu cầu và vẫn cụ thể.
- +3 nếu tương tác tích cực trên Discord hoặc trong nhóm.
- +4 nếu kiểm chứng/research vượt yêu cầu và giúp nhóm sửa lại problem, metric hoặc quyết định cuối.

## Quy ước dùng AI trong lab

| Phần | Có thể dùng AI không? | Cách dùng đúng |
|---|---|---|
| Scan cá nhân | Có, sau khi tự scan trước | Hỏi thêm góc nhìn, rồi tự chọn ý nào là pain thật. |
| Problem Card | Có | Dùng AI để phản biện, không để AI tự bịa problem thay mình. |
| Pitch + challenge | Không dùng để nói/thay mình | Trình bày và phản biện bằng hiểu biết của bản thân. |
| Research | Có | Dùng AI/search để tìm nguồn, nhưng phải kiểm link và ghi rõ giả định chưa chắc. |
| Workflow | Có | Có thể dùng AI/Mermaid để vẽ lại flow, nhưng phải tự kiểm từng bước. |
| Reflection | Không dùng để viết thay | Có thể dùng AI để gợi ý câu hỏi tự soi, nhưng câu trả lời phải là trải nghiệm thật của mình. |

## Gợi ý công cụ nhanh

| Phase | Tool có thể dùng | Dùng để làm gì | Lưu ý |
|---|---|---|---|
| Phase 1 | ChatGPT / Claude / Gemini, Google, review app/forum | Gợi ý thêm problem nếu bí | Tự scan trước; bỏ ý không có trải nghiệm thật. |
| Phase 2 | ChatGPT / Claude | Phản biện Problem Card | Prompt rõ: "chỉ ra điểm yếu, đừng khen". |
| Phase 4 | Google, Perplexity, tài liệu chính thức, survey/interview nhanh | Kiểm chứng pain, tìm giải pháp đã có | Không dùng số liệu nếu không kiểm được nguồn. |
| Phase 5 | Giấy/bảng, Mermaid, Excalidraw, FigJam | Vẽ workflow trước/sau | Vẽ tay cho rõ tư duy trước, số hóa sau nếu cần nộp đẹp hơn. |
| Phase 6 | ChatGPT / Claude | Hỏi phản biện Rule / Workflow / Agent | Không để AI chốt thay. Nhóm phải tự quyết định. |
| Phase 7 | Không bắt buộc | Chỉ dùng để gợi ý câu hỏi tự soi | Không copy reflection do AI viết. |

---

# Phase 0 — Worked Example (15')

Mở `02-deliverable-example.md` để xem một bài hoàn chỉnh. Khi đọc, chú ý:

- cá nhân scan rộng như thế nào,
- top 3 Problem Cards cụ thể ra sao,
- nhóm hội tụ từ nhiều candidates về một bài như thế nào,
- research giải pháp giúp nhóm tránh nghĩ trong chân không ra sao,
- workflow trước/sau thể hiện bottleneck, boundary và phương án quay về nếu AI sai như thế nào,
- Problem Statement v0/v1 khác nhau ở đâu.

Self-check:

- [x] Tôi hiểu nhóm chỉ chọn **candidate problem**, không chọn ngay Problem Statement.
- [x] Tôi hiểu deep-dive gồm validation, research, workflow, metric, PS và AI decision.

---

# Phase 1 — Individual Scan: tìm 5+ problems (25')

## Mục tiêu

Mỗi người scan rộng ít nhất 5 problems từ trải nghiệm thật. Đây là phần phân kỳ cá nhân.

Bonus:

- 8+ problems: bonus nếu vẫn cụ thể.
- 10+ problems: bonus tốt nếu đa dạng lăng kính và có dấu hiệu thật.
- Không bonus cho list dài nhưng toàn ý chung chung.

## 4 lăng kính để scan

Một problem có thể rơi vào nhiều lăng kính. Không cần phân loại hoàn hảo ở bước này. Dùng lăng kính để mở rộng quan sát, rồi bước sau mới filter.

| Lăng kính | Câu hỏi gợi mở | Ví dụ |
|---|---|---|
| **Lặp lại** | Việc gì cứ xuất hiện đều đặn mỗi ngày/tuần/tháng?<br>Nếu phải làm thêm 10 lần nữa, phần nào tôi muốn chuẩn hóa hoặc tự động hóa?<br>Người mới vào có phải hỏi lại cùng một quy trình không? | Báo cáo tuần, nhập liệu, tổng hợp câu hỏi |
| **Tốn thời gian** | Việc gì mỗi lần làm đều nặng, dù không nhất thiết xảy ra thường xuyên?<br>Thời gian mất ở đâu: tìm thông tin, đọc hiểu, tổng hợp, chờ người khác, format, hay sửa lại?<br>Nếu giảm 50% thời gian thì có đáng kể không? | Đọc tài liệu dài, tìm quyết định cũ, review PRD |
| **AI có thể tốt hơn** | Việc gì cần hiểu ngữ cảnh, đọc/viết ngôn ngữ, phân loại, so sánh, tổng hợp hoặc gợi ý đúng lúc?<br>Nếu AI chỉ hỗ trợ một bước trong workflow, bước nào đáng hỗ trợ nhất?<br>Nếu AI sai ở bước đó thì hậu quả là gì? | Search tài liệu, gợi ý next step, tóm tắt nhiều nguồn |
| **Pain từ người khác** | Ai ngoài tôi đang bị kẹt hoặc phàn nàn lặp lại?<br>Họ thường nói câu gì, hỏi lại điều gì, hoặc bỏ sót bước nào?<br>Có dấu hiệu thật không: ticket, Slack/Discord, comment, survey, phản hồi trực tiếp? | Hỏi lại deadline, không hiểu task, support ticket lặp lại |

Cách phân biệt nhanh:

- `Lặp lại` bắt đầu từ câu hỏi: việc này xảy ra bao nhiêu lần?
- `Tốn thời gian` bắt đầu từ câu hỏi: mỗi lần làm tốn bao nhiêu công?
- Một problem vừa lặp lại vừa tốn thời gian thì càng đáng đưa vào danh sách scan.

Nếu bí, tự hỏi:

- Tuần trước tôi mất nhiều thời gian nhất vào việc gì?
- Việc gì tôi hay trì hoãn vì nhàm chán hoặc rối?
- Người khác hay hỏi tôi câu gì lặp lại?
- Có workflow nào ở trường/công ty ai cũng biết là chậm?
- Có app nào tôi dùng và thường nghĩ "giá như nó hiểu mình hơn"?

Một số điểm bắt đầu dễ quan sát:

| Bối cảnh | Có thể nhìn vào đâu? | Câu hỏi gợi mở |
|---|---|---|
| Học tập | Bài tập, tài liệu, deadline, câu hỏi lặp lại trong lớp | Phần nào làm tôi mất thời gian vì phải đọc, tổng hợp, hỏi lại hoặc đoán ý? |
| Công việc / thực tập | Báo cáo, họp, handoff, ticket, review, nhập liệu | Việc nào lặp lại đủ nhiều nhưng vẫn cần hiểu ngữ cảnh trước khi xử lý? |
| Nhóm / CLB / dự án | Phân công, theo dõi tiến độ, feedback, tổng hợp quyết định | Chỗ nào mọi người hay hiểu khác nhau hoặc bỏ sót việc cần làm? |
| Sản phẩm đang dùng | Search, onboarding, support, form, notification | Điểm nào user phải tự nối nhiều thông tin rời rạc để hoàn thành việc? |

## Ngân hàng gợi ý problem

Nếu vẫn bí ý tưởng, đọc nhanh các gợi ý dưới đây rồi quay lại trải nghiệm thật của bạn. Không copy nguyên văn; hãy viết lại theo người dùng, workflow và dấu hiệu thật mà bạn quan sát được.

| Bối cảnh | Gợi ý problem để suy nghĩ |
|---|---|
| Học tập | Tìm lại quyết định/câu trả lời cũ trong Discord; đọc tài liệu dài trước deadline; không biết bài nộp thiếu field nào; ôn tập từ nhiều nguồn rời rạc. |
| Đời sống cá nhân | Theo dõi chi tiêu rải rác nhiều app; lên kế hoạch đi lại/ăn uống cho nhóm; tổng hợp giấy tờ cá nhân; nhắc việc định kỳ nhưng hay quên context. |
| Thực tập / công việc mới | Hỏi lại quy trình onboarding; tìm người phụ trách đúng việc; viết update hằng tuần; hiểu task từ nhiều Slack/thread/tài liệu. |
| Người đi làm | Tổng hợp báo cáo tuần; chuẩn bị meeting recap; review tài liệu dài; phân loại ticket/support; tìm quyết định cũ trước khi làm tiếp. |
| Cải thiện sản phẩm đang dùng | Search kém; onboarding khó hiểu; notification không đúng lúc; form dài và dễ nhập sai; support phải hỏi lại cùng một thông tin nhiều lần. |

## Bảng scan

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Đọc paper AI 30 trang để biết thêm kiến thức | Sinh Viên | Mất 3 tiếng/bài, hay buồn ngủ, dễ sót ý chính. |
| 2 | Lặp lại | Tổng hợp tài liệu tham khảo và định dạng chuẩn IEEE cho bài nghiên cứu. | Sinh viên | Mất 1-2 tiếng cuối mỗi kỳ làm bài, dễ gõ sai dấu chấm, dấu phẩy, bị trừ điểm oan. |
| 3 | Tốn thời gian | Tìm kiếm và trích xuất số liệu từ các file báo cáo tài chính/báo cáo thị trường định dạng PDF dài hàng trăm trang. | Sinh viên làm bài tập nhóm/nghiên cứu | Mất cả buổi chiều Ctrl+F nhưng dễ bỏ sót số liệu ẩn trong các bảng biểu phức tạp. |
| 4 | Tốn thời gian | Xem lại video bài giảng dài 2-3 tiếng để tìm đúng đoạn kiến thức bị hổng trước ngày thi. | Sinh viên | Mất 30-45 phút tua đi tua lại video, gây nản và lãng phí thời gian ôn tập. |
| 5 | AI có thể tốt hơn | Tóm tắt và kết nối các cuộc thảo luận, phân công công việc rời rạc từ tin nhắn Chat nhóm (Messenger/Zalo) thành checklist nhiệm vụ rõ ràng. | Trưởng nhóm/Thành viên | Các thành viên hay quên task, trôi tin nhắn, trưởng nhóm mất 30 phút mỗi tuần để nhắc lại deadline. |
| 6 | Lặp lại | Soạn nội dung email xin gia hạn deadline, xin thực tập, hoặc hỏi bài giảng viên sao cho đúng quy chuẩn lịch sự, trang trọng. | Sinh viên | Mất 20-30 phút đắn đo từng câu chữ vì sợ viết sai đại từ hoặc thất lễ với thầy cô. |
| 7 | Pain từ người khác | Nhận phản hồi (Feedback) chung chung từ giảng viên/mentor và không biết phải sửa bài từ bước nào cho đúng ý. | Sinh viên làm đồ án | Phải đoán ý thầy cô, sửa đi sửa lại 2-3 lần vẫn không đạt, áp lực trước giờ nộp. |
| 8 | Pain từ người khác | Thành viên CLB/Ban cán sự lớp liên tục hỏi lại các thông tin, quy định, lịch trình cũ đã được ghim hoặc thông báo trên Discord. | Trưởng ban/Lớp trưởng | Phải gõ lại câu trả lời hoặc tìm link gửi lại 4-5 lần/tuần, gây tốn thời gian và ức chế. |
| 9 | AI có thể tốt hơn | Kiểm tra lỗi logic, sự nhất quán về luận điểm và văn phong học thuật giữa các phần do các thành viên khác nhau viết trong một bài tiểu luận nhóm. | Người tổng hợp bài nhóm | Bài nộp bị râu ông nọ cắm cằm bà kia, mất 1 tiếng để sửa giọng văn đồng nhất. |
| 10 | Tốn thời gian | Chuyển đổi các ghi chú thô viết nguệch ngoạc trên lớp thành một sơ đồ tư duy hoặc hệ thống bài học có cấu trúc để học vẹt. | Sinh viên | Mất 1 tiếng/môn để hệ thống lại, dẫn đến lười và chuyển sang học tủ. |



---

# Phase 2 — Top 3 Problem Cards + draft workflow (35')

## Mục tiêu

Từ 5+ problems, mỗi người chọn top 3 để chuẩn bị share với nhóm. Mỗi top problem cần có:

- Problem Card.
- Draft current workflow.
- Draft future workflow.
- Lý do vì sao bài này có impact.

## Chọn top 3

Tiêu chí chọn:

- Actor rõ.
- Workflow hiện tại có thể vẽ được.
- Bottleneck cụ thể.
- Impact có thể đo hoặc ước lượng.
- Có thể so sánh No AI / Rule / Workflow / Agent.
- Không quá rộng cho một buổi lab.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tìm kiếm và trích xuất số liệu từ các file báo cáo PDF dài | vì mất cả buổi để Ctrl+F, dễ bỏ sót số liệu trong bảng biểu và có metric khá rõ | Chưa chắc nên giải ở mức search, OCR hay trích xuất tự động; cần kiểm tra PDF có text hay chỉ là ảnh scan |
| 2 | Tóm tắt và kết nối các cuộc thảo luận trong chat nhóm thành checklist nhiệm vụ rõ ràng | Tin nhắn trôi, task dễ bị quên, đầu ra tự nhiên là checklist nên workflow rất rõ | Chưa chắc vấn đề chính là tóm tắt hay phân công; có thể chỉ cần template + action item rule là đủ |
| 3 | Thành viên CLB/Ban cán sự lớp liên tục hỏi lại các thông tin, quy định, lịch trình cũ trên Discord | Đây là pain lặp lại, có dấu hiệu thật, và có thể đo số lần hỏi lại mỗi tuần | Chưa chắc đây đủ lớn để thành bài lab; cần xác nhận tần suất và source of truth, vì giải pháp có thể chỉ là FAQ/pinned post |

## Problem Card template
### Problem1

```text
Problem Card #1: Người làm bài nghiên cứu mất nhiều thời gian để tìm và trích đúng số liệu từ các báo cáo PDF dài, đặc biệt ở bảng biểu và đoạn có nhiều con số.

Actor: Sinh viên làm bài tập nhóm hoặc nghiên cứu.

Thời điểm / bối cảnh: Khi phải đọc 1-3 báo cáo PDF dài hàng chục hoặc hàng trăm trang để lấy số liệu trước deadline.

Current workflow 3-7 bước:
1. Mở PDF báo cáo
2. Dùng mục lục hoặc Ctrl+F theo keyword
3. Nhảy qua các trang để soi bảng, biểu đồ, số liệu
4. Ghi lại số liệu kèm trang nguồn
5. Kiểm tra lại để tránh trích sai

Bottleneck: Tìm đúng chỗ có số liệu và xác nhận số liệu trong bảng/biểu mất nhiều thời gian, dễ bỏ sót.

Impact: Có thể mất nửa buổi đến cả buổi chiều cho một lần research; nếu trích sai thì phải sửa lại.

Success metric: Giảm thời gian tìm/trích từ khoảng 2-3 giờ xuống dưới 1 giờ, và giảm số số liệu phải sửa lại.

Non-AI alternative: OCR + search tốt hơn + checklist trích nguồn, nếu tài liệu ổn định thì rule/script có thể hỗ trợ.

AI hypothesis: AI đọc PDF, định vị trang/bảng có số liệu, trích candidate numbers kèm nguồn; người dùng vẫn kiểm lại trước khi dùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow cho problem #1


```text
+----------------------+
| 1. Upload PDF        |
+----------------------+
           |
           v
+--------------------------------------+
| 2. AI/OCR xác định vùng có số liệu   |
+--------------------------------------+
           |
           v
+--------------------------------------------------+
| 3. Trích candidate numbers + source snippet      |
+--------------------------------------------------+
           |
           v
        +-------------------+
        | AI đủ tự tin?     |
        +-------------------+
           | Yes         | No
           v             v
+------------------+   +------------------------------+
| 4. Người dùng    |   | Fallback: Search thủ công    |
|    verify        |   +------------------------------+
+------------------+                 |
           |                         |
           v                         |
+------------------+                 |
| 5. Copy vào bài  |<----------------+
+------------------+
```

### Problem2

```text
Problem Card #2: Sau khi chat nhóm kết thúc, trưởng nhóm mất thời gian biến các đoạn trao đổi rời rạc thành checklist việc làm rõ ràng, có owner và deadline.

Actor: Trưởng nhóm.

Thời điểm / bối cảnh: Sau cuộc họp hoặc khi trao đổi nhiều trên Messenger/Zalo, trước lúc phân công việc.

Current workflow 3-7 bước:
1. Đọc lại thread chat
2. Lọc ra quyết định, việc cần làm, deadline
3. Xác định ai làm gì
4. Viết lại checklist / summary theo format dễ theo dõi
5. Gửi lại cho cả nhóm và follow-up

Bottleneck: Thông tin rải rác, nhiều đoạn chat không liên tục, task và owner dễ bị lẫn.

Impact: Dễ quên task, phải nhắc lại nhiều lần, và mất khoảng 20-30 phút sau mỗi buổi để chốt việc.

Success metric: Giảm thời gian tổng hợp sau cuộc họp từ khoảng 30 phút xuống dưới 10-15 phút, và giảm số task bị quên hoặc phải nhắc lại.

Non-AI alternative: Template meeting notes + action-item checklist + pin message + rule rõ về owner/deadline.

AI hypothesis: AI tóm tắt thread, bóc tách decision,action,deadline, rồi trưởng nhóm review trước khi gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow cho problem #2


```text
+---------------------------+
| 1. Paste thread log       |
+---------------------------+
                |
                v
+--------------------------------------------------+
| 2. AI tạo checklist có owner và deadline         |
+--------------------------------------------------+
                |
                v
+----------------------------------+
| 3. Trưởng nhóm sửa nhanh         |
+----------------------------------+
                |
                v
+---------------------------+
| 4. Gửi bản cuối           |
+---------------------------+

Fallback:
Nếu chat quá rối
        |
        v
+----------------------------------+
| Dùng template thủ công           |
+----------------------------------+
        |
        v
+---------------------------+
| Tiếp tục workflow         |
+---------------------------+
```
### Problem3

```text
Problem Card #3: Lớp trưởng hoặc trưởng ban phải trả lời lặp lại cùng một thông tin, quy định và lịch trình cũ trên Discord vì thành viên không tìm lại được thông báo gốc.

Actor: Lớp trưởng hoặc trưởng ban phụ trách

Thời điểm / bối cảnh: Khi thành viên hỏi lại sau khi thông báo đã được ghim hoặc đăng từ trước.

Current workflow 3-7 bước:
1. Đăng thông báo hoặc ghim thông tin
2. Thành viên hỏi lại trong chat
3. Trưởng ban tìm lại message hoặc link cũ
4. Copy lại thông tin hoặc trả lời thủ công
5. Lặp lại nhiều lần trong tuần

Bottleneck: Tìm lại thông tin cũ và trả lời lặp lại liên tục.

Impact: Tốn thời gian, làm đứt mạch công việc, gây bực và làm chậm phản hồi cho các việc mới.

Success metric: Giảm số câu hỏi lặp lại cùng một thông tin từ khoảng 4-5 lần/tuần xuống 1-2 lần/tuần, và giảm thời gian trả lời lại.

Non-AI alternative: FAQ, pinned post, tổ chức lại channel, message template, hoặc bot trả lời câu hỏi cố định.

AI hypothesis: AI tạo FAQ từ thông báo cũ và hỗ trợ tìm đúng message hoặc trả lời ngắn gọn cho câu hỏi lặp lại; không thay người quyết định nội dung mới.

Quick gut:
[x] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow cho problem #3


```text
+--------------------------------------+
| 1. Có một source of truth rõ ràng    |
+--------------------------------------+
                  |
                  v
+--------------------------------------------------+
| 2. Auto-generated FAQ hoặc pinned summary        |
+--------------------------------------------------+
                  |
                  v
+--------------------------------------+
| 3. Thành viên tìm trước khi hỏi      |
+--------------------------------------+
                  |
                  v
        +---------------------------+
        | Bot trả lời được?         |
        +---------------------------+
             | Yes             | No
             v                 v
     +----------------+   +----------------------------------+
     | Có câu trả lời |   | 4. Ping người phụ trách          |
     +----------------+   +----------------------------------+

Fallback:
Nếu là câu hỏi mới hoặc ngoại lệ
                  |
                  v
+--------------------------------------+
| Xử lý thủ công                       |
+--------------------------------------+
```
## Chọn card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
Card #2: Tóm tắt và kết nối các cuộc thảo luận trong chat nhóm thành checklist nhiệm vụ rõ ràng
```

Vì sao:

```text
Đây là workflow hằng ngày/hằng tuần rất dễ thấy. Bottleneck là đọc lại thread rối và bóc action item. Metric dễ dàng đo bằng thời gian tổng hợp và các task bị hỏi lại
```

Câu hỏi tôi muốn nhóm challenge:

```text
Theo mọi người, pain này thật sự nằm ở việc thread chat quá rối, hay nằm ở chỗ team chưa có format chốt owner/deadline ngay từ đầu?
```


# Phase 3 — Group Convergence: từ 9-12 candidates về 1 (30')

## Mục tiêu

Nhóm 3-4 người sẽ có khoảng 9-12 candidate problems. Không vote ngay. Đi qua 4 bước hội tụ:

```text
Trình bày top 3
→ gom trùng / cluster
→ shortlist
→ chấm nhanh + đồng thuận chọn 1 candidate problem
```

Nhóm lúc này **chỉ chọn candidate problem**, chưa viết Problem Statement hoàn chỉnh.

Đây là phase **tự pitch và tự challenge**. Không dùng AI để viết lời pitch, đặt câu hỏi thay mình, hoặc quyết định thay nhóm. Nếu muốn dùng AI để tóm tắt notes, chỉ làm sau khi nhóm đã thảo luận xong phần chính.

## Bước 3.1 — Trình bày top 3

Mỗi người trình bày 3 candidates, mỗi candidate 1-2 phút:

- problem là gì,
- người gặp vấn đề là ai,
- workflow hiện tại nghẽn ở đâu,
- draft workflow tương lai thay đổi gì,
- vì sao bài này có tác động đáng kể.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Đào Duy Quyền | Tìm kiếm và trích xuất số liệu từ các file báo cáo PDF dài | Sinh viên | Tìm đúng chỗ có số liệu và xác nhận số liệu trong bảng/biểu mất nhiều thời gian, dễ bỏ sót. | Đau thật, workflow rõ, dễ đo thời gian và số lỗi trích sai. |
| 2 | Đào Duy Quyền | Sau khi chat nhóm kết thúc, trưởng nhóm mất thời gian biến các đoạn trao đổi rời rạc thành checklist việc làm rõ ràng, có owner và deadline. | Trưởng nhóm | Thông tin rải rác, nhiều đoạn chat không liên tục, task và owner dễ bị lẫn. | Rất thực tế, đầu ra rõ, nhìn là thấy có thể pitch được. |
| 3 | Đào Duy Quyền | Lớp trưởng hoặc trưởng ban phải trả lời lặp lại cùng một thông tin, quy định và lịch trình cũ trên Discord vì thành viên không tìm lại được thông báo gốc.| Lớp trưởng | Tìm lại thông tin cũ và trả lời lặp lại liên tục. | Lặp lại rõ nhưng có khả năng chỉ cần rule/FAQ là đã xử lý nhiều. |
| 4 | Yến Phương | Debug Bug & Tìm Root Cause | Developer | Phân tích stack trace để tìm ra nguyên nhân gốc rễ (mapping error message -> root cause) giữa hàng chục file dependency và tài liệu rải rác. | Có pain thật nhưng khá nặng, cần kiểm tra scope có quá rộng không. |
| 5 | Yến Phương | Screening Paper AI | Sinh viên AI, Researcher | Đọc hiểu chi tiết kỹ thuật từ paper dài (thường 8-15 trang) để đối chiếu mức độ tương thích với bài toán thực tế của mình. | Đúng nhu cầu, AI có đất, nhưng phải thu hẹp rất kỹ để không bị lan quá rộng. |
| 6 | Yến Phương| Đọc hiểu source code cũ khi onboarding | Developer | Tự lần theo luồng code phức tạp và suy đoán mục đích logic của tác giả cũ. | Workflow rất thật, đau đều, dễ pitch nếu chốt đúng người dùng. |
| 7 | Khánh An| Học viên hỏi lại Lab Coach về những câu hỏi gần tương tự nhau | Lab Coach, học viên | Lab Coach phải đọc lại context và trả lời lặp lại nhiều câu hỏi tương tự mỗi tuần | Pain lặp lại rõ, nhưng có vẻ rule/process fix sẽ giải được phần lớn. |
| 8 | Khánh An|Debug bài làm mà chưa biết lỗi xuất phát từ chỗ nào | Học viên  | Học viên mất nhiều thời gian đọc error, search tài liệu và thử sai trước khi xác định được nguyên nhân thật sự | Đau thật với học viên |
| 9 | Khánh An | Ôn bài kiến thức từ nhiều buổi, trên nhiều nền tảng LMS, Github, bài tập thực hành | Học viên | Học viên tự chủ động ôn lại bài với lượng kiến thức khổng lồ trước mỗi buổi kiểm tra hoặc sau mỗi buổi học. | Có nhu cầu thật nhưng còn hơi chung, cần scope cụ thể hơn. |


## Bước 3.2 — Gom trùng / cluster

### Không trùng

## Bước 3.3 — Shortlist


| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Sau khi chat nhóm kết thúc, trưởng nhóm mất thời gian biến các đoạn trao đổi rời rạc thành checklist việc làm rõ ràng, có owner và deadline. | Actor khá rõ, workflow thật và rất quen thuộc, bottleneck nằm ở việc bóc action item từ thread rời rạc. Impact đo được bằng thời gian tổng hợp và số task bị quên/hỏi lại. Dễ vẽ before/after workflow và so sánh Rule / Workflow / Agent. | Cần kiểm tra xem team đã có format chốt việc sẵn chưa. Nếu đã có template tốt thì mức pain giảm, nhưng thường vẫn đủ rõ để pitch. |
| Debug Bug & Tìm Root Cause| Workflow debug là workflow thật, actor developer rõ, bottleneck cụ thể ở mapping error message -> root cause giữa nhiều file dependency và tài liệu rải rác. Impact có thể đo bằng thời gian tìm nguyên nhân gốc và số vòng thử sai. Dễ so sánh Rule / Workflow / Agent. | Scope dễ bị quá rộng nếu không chốt một stack, một loại bug, hoặc một bối cảnh cụ thể. Có nguy cơ trượt sang troubleshooting chung chung. |
| Ôn bài kiến thức từ nhiều buổi, trên nhiều nền tảng LMS, Github, bài tập thực hành | Actor là học viên khá rõ, workflow ôn tập sau buổi học và trước kiểm tra là workflow thật, pain lặp lại và có thể đo bằng thời gian chuẩn bị bài và mức độ nhớ lại. Có thể vẽ before/after workflow nếu chốt được output ôn tập. | Còn hơi rộng vì nguồn quá nhiều (LMS, GitHub, bài tập, note), chưa rõ output cuối là summary, flashcard hay question set. Cần thu hẹp scope trước khi deep-dive. |

## Bước 3.4 — Score để đồng thuận

Chấm 1-5. Điểm không cần tuyệt đối; mục tiêu là ép nhóm nói rõ lý do.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Chat nhóm -> checklist công việc | 5 | 5 | 3 | 4 | 4 | 4 | 5 | 30 |
| Debug & Tìm Root Cause | 5 | 3 | 3 | 3 | 2 | 5 | 4 | 25 |
| Ôn kiến thức đa nguồn | 5 | 4 | 3 | 3 | 3 | 5 | 4 | 27 |

Candidate nhóm chọn: **Chat nhóm -> checklist công việc**


Vì sao chọn:
- Bài này có actor rất rõ, workflow thật và rất quen thuộc, bottleneck nằm đúng ở bước bóc action item từ thread rời rạc. 
- Impact đo được bằng thời gian tổng hợp và số task bị bỏ sót hoặc phải hỏi lại. 
- Scope đủ nhỏ để làm trong lab hôm nay và dễ so sánh Rule / Workflow / Agent.


Vì sao không chọn các candidate còn lại:
- Debug & Root Cause có pain thật nhưng scope dễ rộng quá, nếu không chốt rõ stack, kiểu bug và bối cảnh thì rất dễ trượt sang troubleshooting chung chung. 
- Ôn bài từ nhiều nguồn là nhu cầu thật nhưng hiện còn hơi rộng, chưa chốt rõ output ôn tập là summary, flashcard hay question set nên khó đi sâu ngay.

Nếu có disagreement, nhóm xử lý thế nào:

- Nhóm sẽ quay lại 3 tiêu chí chốt: bài nào scope nhỏ nhất, hiểu workflow thật nhất, và đo được nhanh nhất trong lab hôm nay. 
- Nếu vẫn ngang nhau, ưu tiên bài mà cả nhóm có thể validate ngay bằng một ví dụ workflow thật.


---

# Phase 4 — Quick Validation + Research giải pháp (30')



## Bước 4.1 — Quick validation

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quick interview | 3 | 2/3 người nói sau khi chat xong đều phải đọc lại thread để bóc task, owner, deadline; bước đau nhất là tổng hợp lại thành checklist. | 1 người nói nếu team có template chốt việc sẵn thì pain giảm khá nhiều. | Thu hẹp problem thành biến thread chat sau thảo luận thành checklist có owner/deadline, không ôm toàn bộ chat. |
| Mini poll | 7 | 5/7 người gặp vấn đề ít nhất mỗi tuần; phần đau nhất là task trôi và không rõ ai phụ trách. | 2/7 người đã có pinned template hoặc summary sẵn nên ít đau hơn. | Giữ hướng Workflow, thêm non-AI alternative là template + rule chốt việc |
| Review thread| 2 thread | Trong thread thật có nhiều follow-up, task bị nhắc lại, và có đoạn không rõ owner.| Chưa đủ log để kết luận rộng, cần thêm mẫu thật nếu muốn chắc hơn.| Dùng thêm 2-3 thread thật làm evidence trước khi chốt Problem Statement.|

**Kết luận nhanh**

- Pain có thật và lặp lại.
- Bước đau nhất là chuyển hội thoại rời rạc thành checklist có owner/deadline.
- Non-AI alternative vẫn có giá trị, nên bài này hợp với Workflow hơn là Agent.
- Nếu làm sâu, scope nên giữ ở mức: chat nhóm -> checklist công việc, không mở rộng thành chatbot tổng quát.

## Bước 4.2 — Research giải pháp đã có


| Nguồn / tool / case  | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|
|[SlackAI](https://slack.com/help/articles/25076892548883-Guide-to-AI-features-in-Slack) | Tóm tắt channel, DM, thread; search theo nội dung trong Slack | Native ngay trong nơi chat diễn ra, rất hợp để “catch up” nhanh | Dừng chủ yếu ở tóm tắt và tìm kiếm, chưa tự biến hội thoại thành checklist có owner/deadline |Nếu nguồn là Slack, bước đầu tiên nên là summarize thread rồi mới chuyển sang checklist | 
|[Discord In-Channel Conversation Summaries](https://support.discord.com/hc/en-us/articles/12926016807575-In-Channel-Conversation-Summaries) | Tóm tắt các cuộc hội thoại trong channel thành topic và snippet | Hữu ích để đọc lại cuộc trò chuyện dài | Tính năng còn là experiment, giới hạn server, và không nhắm vào task extraction | Nếu nhóm dùng Discord, native AI hiện nghiêng về catch-up chứ chưa phải tasking | 
|[Notion AI Meeting Notes](https://www.notion.com/help/ai-meeting-notes) | Transcribe cuộc họp, rút key points và action items | Có sẵn luồng từ hội thoại sang action items, có citation | Thiên về meeting transcript hơn là chat thread rời rạc; cần quyền audio/screen | Đây là pattern tốt: AI đọc nội dung hội thoại rồi bóc ra action items, nhưng vẫn trong bối cảnh có cấu trúc | 
|[CLickUp AI](https://clickup.com/ai) | Lấy action items từ docs, chats, meetings và biến thành task / plan| Có chats trong input | Hợp nhất khi team đã làm việc trong ClickUp; vẫn cần kiểm tra lại output trước khi giao việc | Có bằng chứng mạnh rằng bài toán này hợp với Workflow hơn là Agent|


---

# Phase 5 — Workflow + Problem Statement (45')

## Bước 5.1 — Current workflow bản nhóm

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
| 1. Paste thread log | Trưởng nhóm / người tổng hợp | Thread chat sau khi trao đổi xong | Toàn bộ nội dung trao đổi được đưa vào một chỗ | 5-10 phút / mỗi cuộc trao đổi | Từ group chat sang người tổng hợp | Thread dài, nhiều đoạn rời rạc, khó đọc lại theo thứ tự |
| 2. AI tạo checklist có owner và deadline | AI hỗ trợ | Thread log đã paste | Draft checklist gồm task, owner, deadline, notes | 1-3 phút / mỗi lần tổng hợp | Từ người tổng hợp sang AI | AI có thể bóc task chưa chính xác hoặc thiếu ngữ cảnh |
| 3. Trưởng nhóm sửa nhanh | Trưởng nhóm | Draft checklist từ AI | Checklist đã chỉnh đúng ý nhóm | 5-15 phút / mỗi lần | Từ AI sang người phụ trách | Phải kiểm tra lại owner, deadline, task bị sót hoặc trùng |
| 4. Gửi bản cuối | Trưởng nhóm / người tổng hợp | Checklist đã sửa | Bản checklist cuối gửi cho cả nhóm | 1-2 phút / mỗi lần | Từ người phụ trách sang cả nhóm | Nếu format chưa rõ thì người nhận vẫn phải hỏi lại |



Bottleneck chính:

```text
biến thread chat rối thành checklist có owner/deadline đúng.
```

## Bước 5.2 — Future workflow bản nhóm

Dán workflow hoặc link file:

```text
FUTURE STATE — chat nhóm -> checklist công việc

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

Fallback: nếu chat quá rối / thiếu ngữ cảnh
        |
        v
+------------------------------------------------------------------+
| Dùng template thủ công trước                                     |
| Actor      : Trưởng nhóm                                         |
| Type       : Rule / manual                                       |
| Input      : Chat + template checklist                           |
| Output     : Checklist thủ công                                  |
| Time/freq  : 10-20 phút / mỗi lần                               |
| Handoff    : Chat -> template -> người phụ trách                 |
| Bottleneck : Tốn công nhưng ổn định hơn                          |
+------------------------------------------------------------------+
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 4 | Giảm một bước xử lý trung gian |
| Tổng thời gian | 20-30 phút | 8-12 phút | Giảm mạnh ở đoạn đọc lại và bóc task |
| Số bước thủ công | 5 | 3 | Rule/template giúp giảm thao tác nặng |
| Bottleneck chính | Đọc thread rời rạc và bóc action item | Review và chốt owner/deadline | Bottleneck chuyển sang kiểm tra chất lượng |
| Risk mới | Chậm, dễ quên task, dễ phải hỏi lại | AI bóc sai task/owner/deadline, cần người review | Nếu chat quá rối thì phải fallback sang template thủ công |

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm hoặc người tổng hợp sau khi cuộc thảo luận kết thúc. |
| **Workflow** | Thread chat kết thúc -> đọc lại nội dung rời rạc -> bóc action item -> gán owner/deadline -> gửi checklist cho cả nhóm. |
| **Bottleneck** | Đọc lại thread dài và rời rạc để chốt đúng task, owner và deadline. |
| **Impact** | Mỗi lần tổng hợp mất khoảng 20-30 phút, dễ bỏ sót task hoặc phải hỏi lại nhiều lần, làm chậm việc chốt đầu việc của cả nhóm. |
| **Success Metric** | Giảm thời gian tổng hợp checklist xuống dưới 10-15 phút và giảm số task bị bỏ sót / phải nhắc lại. |
| **Boundary** | AI chỉ hỗ trợ draft checklist; người thật vẫn phải review và chốt owner/deadline cuối cùng. Không để AI tự gửi bản cuối khi chưa được kiểm tra. |


# Phase 6 — Rule / Workflow / Agent + Decision (25')

## Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Dùng template meeting notes + format chat cố định | Team nhỏ, ít discussion | Người dùng không follow format, vẫn phải đọc thủ công | |
| **Workflow** | AI đọc thread chat $\rightarrow$ extract Task/owner/deadline $\rightarrow$ tạo draft checklist | Discussion dài, nhiều task và nhiều người tham gia | AI hiểu sai context hoặc assign sai owner | ✓ |
| **Agent** | AI tự follow-up, nhắc deadline, tự phân công việc | Team lớn, workflow phức tạp nhiều giai đoạn | Over-engineering, khó kiểm soát | |


**Mức chọn:** Workflow

**Vì sao chọn:**
- Workflow xử lý khá tuần tự và rõ ràng.
- AI chủ yếu hỗ trợ:
    - summarize
    - extract action items
    - format checklist
- Có human boundary rõ:
    - trưởng nhóm review trước khi gửi.
- Không cần AI tự ra quyết định hoặc tự điều phối nhóm.

**Vì sao không chọn mức đơn giản hơn:**
- Rule có thể giảm một phần pain nhưng không giải quyết được:
    - chat rời rạc
    - context phân tán
    - discussion không theo format
- Người dùng thường không duy trì format chat cố định trong thời gian dài.

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | Rule / Workflow / Agent |
| **Rủi ro & người thật kiểm tra** | |

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | | |
| Baseline và success metric đã đo được chưa? | | |
| Có data/input đủ dùng chưa? | | |
| Nếu AI sai, hậu quả có chấp nhận được không? | | |
| Có người review/owner vận hành không? | | |
| Có cách non-AI đơn giản hơn không? | | |

Decision:

```text
[Go / Not Yet / No-Go]
```

Lý do:

```text

```

Nếu Go, pilot nhỏ nhất là:

```text

```

Nếu Not Yet, cần validate gì trước:

```text

```

Nếu No-Go, nên làm gì thay AI:

```text

```

---

# Phase 7 — Individual Reflection (15')

Reflection không chỉ là "tôi dùng AI thế nào". Bạn cần phản tư về vai trò của mình trong nhóm.

Reflection là phần cá nhân. Không dùng AI để viết thay câu trả lời. Nếu dùng AI, chỉ dùng để gợi ý câu hỏi tự soi hoặc kiểm xem mình còn bỏ sót ý nào.

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | | |
| Pitch Problem Card | | |
| Challenge bài của bạn khác | | |
| Gom trùng / cluster | | |
| Chọn candidate problem | | |
| Validation / research | | |
| Workflow nhóm | | |
| Problem Statement | | |
| Rule / Workflow / Agent | | |
| Decision | | |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | | | | |
| Problem Card | | | | |
| Workflow | | | | |
| Research | | | | |
| Problem Statement | | | | |
| Rule / Workflow / Agent | | | | |
| Decision | | | | |

## Reflection câu hỏi mở

- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first không?
- Tôi có thay đổi ý kiến sau khi bị challenge không?
- Tôi đóng góp gì thật sự vào artifact cuối?
- Điều khó nhất khi viết Problem Statement là gì?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

Reflection:

```text

```

## Tự kiểm cuối bài

- [ ] [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [ ] [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm.
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [ ] [15đ nhóm] Nhóm có workflow trước/sau.
- [ ] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [ ] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [ ] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [ ] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [ ] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

*Day 02 Lab — Worksheet*

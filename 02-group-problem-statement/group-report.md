# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|---:|---|---|---|
| 1 | Trần Văn Thi | 2A202601548 | Nhóm trưởng |
| 2 | Vũ Thế Lực | 2A202602008 | Thành viên |
| 3 | Đinh Quốc Việt | 2A202601891 | Thành viên |
| 4 | Vũ Thanh Phương | 2A202601854 | Thành viên |
| 5 | Nguyễn Hoàng Thảo Tiên | 2A202601650 | Thành viên |
| 6 | Nguyễn Duy Hưng | 2A202601702 | Thành viên |
| 7 | Trần Bảo Phúc | 2A202601148 | Thành viên |
| 8 | Nguyễn Trung Long | 2A202601514 | Thành viên |
| 9 | Ngô Văn Linh | 2A202601929 | Thành viên |
| 10 | Hoàng Tuấn Hưng | 2A202601911 | Thành viên |
| 11 | Ngô Hoàng Phú | 2A202601244 | Thành viên |
| 12 | Nghiêm Quốc Huy | 2A202601923 | Thành viên |
| 13 | Nguyễn Xuân Kiên | 2A202601398 | Thành viên |

## 02 — Group Problem Statement

## Group convergence

3 nhóm tổng với 4-5 người trên một nhóm nhỏ, mỗi nhóm share top 4. Tổng cộng khoảng 12-13 candidates.

| Cluster | Candidate examples | Pattern chung |
|---|---|---|
| Hỗ trợ sinh viên / hỏi đáp lặp lại | Câu hỏi về setup, yêu cầu bài tập, deadline, lỗi thường gặp | Số lượng trợ giảng ít so với sinh viên; nhiều câu hỏi trùng nhau khiến trợ giảng mất khoảng 1–3 giờ để tổng hợp và trả lời lặp lại |
| Tổng hợp công việc | Tổng hợp task từ Jira, Discord, bài học lý thuyết, Lab; lọc deadline; to-do hằng ngày | Thu thập thông tin từ nhiều nguồn, tổng hợp thành một danh sách công việc và ưu tiên để người dùng theo dõi, tránh bỏ sót deadline |
| Workflow | Tài liệu kĩ thuật lỗi thời | Viết code xong phải nhớ sửa doc, phải tìm tất cả chỗ liên quan để sửa |
| Learning Material Retrieval | MSTeam, Messenger, Studocu, Google Drive | Tài liệu phân tán ở nhiều nguồn, phải tìm kiếm và tổng hợp thủ công trước khi học |
| Báo cáo / tổng hợp tiến độ | Tổng hợp commit history từ Git, gom task Trello/Jira, tổng hợp update tin nhắn nhóm làm Weekly Report | Gom dữ liệu thô rải rác từ nhiều công cụ (Git, Trello, Zalo/Discord) rồi tổng hợp thành báo cáo tiến độ ngắn gọn, mạch lạc; giảm thời gian xử lý thủ công và tránh bỏ sót công việc |
| Hỗ trợ người bán xe / Tổng hợp thông tin | Người dùng phải dắt xe qua nhiều cửa hàng để định giá trước, mỗi cửa hàng báo giá khác nhau | Phải tổng hợp thông tin để kiểm định giá xe |
| Tổng hợp / chuẩn hóa tài liệu | Format technical documentation, business report | Cả team mất khoảng 40–60 phút mỗi tài liệu để tổng hợp, chuẩn hóa cấu trúc và định dạng trước khi chia sẻ |
| Lọc deadline / tổng hợp thông báo học tập | Lọc deadline bài tập & thông báo học tập bị rải rác trên nhiều kênh (Mail trường, LMS, Group Zalo lớp) / Gom deadline và thông báo rải rác từ nhiều app về 1 nơi duy nhất | Thông tin học tập bị phân tán qua nhiều kênh, người học phải tự lọc deadline và thông báo quan trọng để tránh bỏ sót |
| Tổng hợp thông tin | Khó theo dõi tiến độ và đầu việc trên nhiều nền tảng | Phải kiểm tra GitHub, Discord và Portal; có nguy cơ bỏ sót deadline |
| Quản lý vận hành | Học viên nghỉ buổi đầu chưa có nhóm, sinh viên vào sau cần ghép bàn, rà soát nhóm đang thiếu/thừa người | Cấu trúc phân bổ cứng nhắc từ đầu không tự thích ứng khi có biến động nhân sự; mất thời gian rà soát thủ công, xử lý ngoại lệ và làm gián đoạn nhịp các nhóm đang hoạt động để người mới bắt nhịp |

## Shortlist và score

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Lọc deadline bài tập & thông báo học tập đa kênh | 5 | 5 | 5 | 5 | 5 | 5 | 5 | 35 |
| Tổng hợp tiến độ Git/task thành báo cáo nhóm hằng tuần | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| Check thông báo công việc từ nhiều nguồn | 4 | 4 | 4 | 4 | 5 | 4 | 4 | 29 |

Nhóm chọn: **Lọc deadline bài tập & thông báo học tập đa kênh**.

Vì sao chọn:

- Actor rõ: học viên/sinh viên phải tự theo dõi deadline và thông báo học tập.
- Workflow rõ: kiểm tra Mail trường, LMS, group Zalo lớp rồi tự lọc thông tin quan trọng.
- Có pain dễ thấy: thông báo bị rải rác, dễ bỏ sót deadline hoặc cập nhật quan trọng.
- Impact đo được: số kênh phải check mỗi ngày, thời gian kiểm tra thông báo, số lần quên/trễ deadline.
- Có thể làm trong lab vì scope vừa đủ, không cần tích hợp hệ thống thật ngay từ đầu.
- Có thể so sánh Rule / Workflow / Agent rõ: rule để lọc keyword deadline, workflow để gom và ưu tiên thông báo, agent nếu muốn tự nhắc và hỏi lại người học.

Vì sao không chọn các bài khác:

- Tổng hợp tiến độ Git/task thành báo cáo nhóm hằng tuần: workflow rất rõ và điểm cao, nhưng actor hẹp hơn, chủ yếu phù hợp với trưởng nhóm hoặc team làm project có dùng Git đều đặn.
- Check thông báo công việc từ nhiều nguồn: pain khá giống bài được chọn nhưng scope rộng và mơ hồ hơn; “công việc” có thể kéo sang nhiều domain khác nhau nên khó chốt workflow trong thời gian lab.

## Quick validation

Nhóm hỏi nhanh 4 học viên quen biết.

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quick interview | 4 | 4/4 học viên cho biết mỗi ngày đều phải mở nhiều nền tảng (Discord, Jira, LMS, Mail) để kiểm tra task và deadline; 3/4 từng bỏ sót ít nhất một thông báo quan trọng | 1 người sử dụng Google Calendar và tự tạo checklist nên ít bị quên deadline | Thu hẹp problem: tập trung vào tự động tổng hợp deadline và thông báo từ nhiều nguồn, thay vì chỉ nhắc lịch |
| Mini poll trong nhóm | 8 | 6/8 học viên cho biết mất khoảng 10–20 phút/ngày để kiểm tra nhiều nguồn thông tin; 5/8 mong muốn có một dashboard hoặc chatbot tổng hợp task | 2 người cho rằng số lượng thông báo không nhiều, chỉ cần tự kiểm tra là đủ | Bổ sung non-AI alternative: sử dụng Google Calendar hoặc Notion để quản lý task, nhưng vẫn cần cập nhật thủ công từ nhiều nguồn |

Insight sau validation:

```text
Pain thật không nằm ở việc "lấy số" đơn thuần. Pain nằm ở đoạn biến nhiều nguồn rời rạc thành narrative đủ rõ cho người khác ra quyết định.
```
## Research giải pháp

Nhóm tìm các hướng đã có sẵn, không giả định phải tự build từ đầu.


| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Classroom Assignment / Due date | [Google Classroom Help](https://support.google.com/edu/classroom/answer/6020265?co=GENIE.Platform%3DDesktop&hl=en) | Cho giáo viên tạo assignment, gắn due date, due time | Deadline được cấu trúc rõ nếu lớp dùng Classroom đều | Không gom được Mail trường, LMS khác, Zalo lớp; phụ thuộc giảng viên nhập đúng | Nếu data đã structured thì rule/calendar là đủ cho một phần |
| Canvas / LMS due date | [Canvas Community](https://community.instructure.com/en/kb/articles/648211-order-of-precedence-and-due-dates-for-assignments-and-modules) | Quản lý due date theo assignment/module | Tốt cho deadline nằm trong LMS | Chỉ giải quyết trong một hệ LMS; sinh viên vẫn phải check kênh ngoài | LMS không phải “single source of truth” nếu lớp còn dùng Mail/Zalo |
| Google Calendar / Tasks reminder | [Google Calendar Help](https://support.google.com/calendar/) | Lưu deadline thành event/task và nhắc trước hạn | Dễ dùng, non-AI, phù hợp nhắc deadline | Sinh viên vẫn phải tự đọc thông báo và tự nhập deadline | Calendar là output tốt, nhưng không giải quyết bước lọc thông tin ban đầu |
| Zapier Gmail + Google Calendar | [Zapier Gmail Calendar](https://zapier.com/apps/gmail/integrations/google-calendar) | Tạo calendar event từ email matching keyword | Tốt cho automation rule-based, ví dụ email có chữ “deadline”, “due”, “submission” | Không xử lý tốt Zalo/private group; keyword dễ miss hoặc bắt nhầm | Rule có thể dùng để bắt tín hiệu rõ, nhưng cần người kiểm tra |
| Zapier Google Calendar automation | [Zapier Calendar Automation](https://zapier.com/blog/automate-google-calendar-with-zapier/) | Tự động nhắc lịch, gửi notification, sync calendar | Hợp với workflow thông báo/nhắc hạn | Không hiểu ngữ cảnh học tập sâu; vẫn cần setup nguồn dữ liệu | Workflow tốt hơn agent full tự chạy: gom, lọc, nhắc, rồi người học xác nhận |

Research takeaway:

```text
Không nên build một agent tự đọc mọi kênh và tự quyết định deadline ngay từ đầu. Hướng hợp lý hơn là Workflow: gom thông báo từ các nguồn có thể truy cập, dùng rule/AI để lọc candidate deadline, sau đó học viên xác nhận trước khi đưa vào calendar hoặc checklist.
```

## Workflow before/after


File nhóm nộp kèm:

```text
02-A5-problem-statement-workflow.pdf
```

Nội dung workflow:

```text
CURRENT STATE — 6 bước, khoảng 35 phút/ngày hoặc mỗi đợt có nhiều deadline

[1 Check Mail trường: 7']
→ [2 Check LMS/Classroom: 8']
→ [3 Check group Zalo lớp: 8']
→ [4 Đọc lại message/thông báo để lọc deadline: 7']  <-- bottleneck
→ [5 Tự ghi deadline vào note/calendar: 3']
→ [6 Nhờ bạn xác nhận nếu không chắc: 2']

FUTURE STATE — 5 bước, khoảng 10-12 phút

[1 Gom thông báo từ Mail/LMS/Zalo paste thủ công: 3']  -- Workflow input
→ [2 Rule lọc keyword deadline/bài tập/thông báo: 1']  -- Rule
→ [3 AI tóm tắt candidate deadline + mức độ quan trọng: 1']  -- Workflow step
→ [4 Học viên xác nhận/sửa deadline: 4']  -- Human boundary
→ [5 Đưa vào checklist/calendar + nhắc hạn: 1-3']

Fallback:
AI lọc sai hoặc thiếu context → học viên bỏ candidate đó và tự nhập deadline thủ công.

Bottleneck mới:
Học viên review/xác nhận. Đây là bottleneck chấp nhận được vì deadline sai có thể làm nộp bài trễ.
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Tổng thời gian check thông báo | 30-35 phút | 10-12 phút | Target chính |
| Số kênh phải tự mở | 3+ | 1 màn hình tổng hợp | Mail, LMS, Zalo |
| Bước thủ công | 6/6 | 2/5 | Vẫn cần paste/check và xác nhận |
| Bottleneck chính | Lọc thông báo quan trọng | Review deadline candidate | Human boundary |
| Risk mới | Bỏ sót do con người | AI lọc sai hoặc hiểu nhầm deadline | Cần confirm trước khi lưu |

## Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Học viên/sinh viên phải theo dõi deadline bài tập và thông báo học tập từ nhiều kênh. |
| **Workflow** | Mỗi ngày hoặc trước buổi học, học viên check Mail trường, LMS/Classroom, group Zalo lớp, đọc lại thông báo, tự lọc deadline, rồi ghi vào note/calendar. |
| **Bottleneck** | Bước lọc thông báo quan trọng mất khoảng 15-20 phút vì thông tin bị rải rác và nhiều tin không liên quan. |
| **Impact** | Học viên mất khoảng 30-35 phút mỗi lần rà soát; có nguy cơ bỏ sót deadline, nộp trễ hoặc phải hỏi lại bạn cùng lớp. |
| **Success Metric** | Giảm thời gian rà soát xuống còn 10-12 phút; giảm số lần bỏ sót/trễ deadline; học viên vẫn xác nhận trước khi lưu. |
| **Boundary** | Không tự truy cập tài khoản riêng nếu chưa có quyền; không tự kết luận deadline khi thông tin mơ hồ; không tự gửi/nộp bài thay học viên. |

## Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Keyword filter: deadline, due, nộp bài, assignment, quiz, submission | Đủ nếu thông báo có format rõ và nguồn ổn định | Dễ bắt nhầm hoặc bỏ sót thông báo viết khác cách | Dùng một phần |
| **Workflow** | Gom thông báo → lọc candidate → AI tóm tắt deadline → học viên xác nhận → lưu checklist/calendar | Hợp vì quy trình tuyến tính, AI chỉ hỗ trợ bước đọc/lọc/tóm tắt | AI hiểu sai ngày, môn học hoặc mức độ quan trọng | Chọn |
| **Agent** | Agent tự đọc nhiều kênh, tự phân loại, tự nhắc, tự hỏi lại khi thiếu thông tin | Chỉ cần nếu có quyền truy cập nhiều app và cần chạy nền liên tục | Quá rộng, nhiều permission/privacy risk, khó làm trong lab | Chưa chọn |

Mức chọn:

```text
Workflow.
```

Vì sao:

- Rule đủ cho keyword rõ nhưng không đủ khi thông báo viết tự do.
- AI hữu ích ở bước tóm tắt và phân loại deadline.
- Học viên vẫn review nên giảm rủi ro deadline sai.
- Chưa cần agent vì lab chỉ cần chứng minh workflow nhỏ, không cần tự động chạy nền toàn bộ.


## Problem Statement v1


| Field | Nội dung |
|---|---|
| **Actor** | Học viên/sinh viên phải tự theo dõi deadline và thông báo học tập từ Mail trường, LMS/Classroom và group Zalo lớp. |
| **Workflow** | Check Mail → check LMS/Classroom → check Zalo → lọc thông báo liên quan deadline → ghi vào checklist/calendar → tự nhắc trước hạn. |
| **Bottleneck** | Lọc deadline từ nhiều nguồn mất khoảng 15-20 phút và dễ bỏ sót khi thông báo bị trôi hoặc viết không thống nhất. |
| **Impact** | Tổng thời gian rà soát khoảng 30-35 phút/lần; bỏ sót deadline có thể dẫn đến nộp trễ hoặc phải hỏi lại bạn/giảng viên. |
| **Success Metric** | Giảm thời gian rà soát xuống 10-12 phút; danh sách deadline candidate đạt mức học viên thấy tin cậy sau khi review; giảm số lần hỏi lại deadline trong nhóm. |
| **Boundary** | AI không tự nộp bài, không tự quyết định deadline mơ hồ, không truy cập kênh riêng nếu chưa được cấp quyền. |
| **AI intervention point** | Sau khi thông báo từ các nguồn được gom lại, trước bước học viên tự lọc và ghi deadline. |
| **Mức chọn** | Workflow: rule lọc keyword, AI tóm tắt candidate deadline, học viên xác nhận, rồi lưu vào checklist/calendar. |
| **Rủi ro & người thật kiểm tra** | Risk: hiểu sai ngày, nhầm môn, bỏ sót thông báo, lấy nhầm tin cũ. Người thật review: học viên phải xác nhận deadline trước khi lưu hoặc nhắc hạn. |


## Final decision

Decision:

```text
Go với scope nhỏ.
```

Pilot nhỏ nhất:

- Dùng thông báo mẫu trong 1-2 tuần gần nhất từ Mail trường, LMS/Classroom và group Zalo.
- Học viên paste thủ công các thông báo vào một prompt/template.
- Workflow trả ra bảng gồm: môn học, deadline, việc cần làm, nguồn, mức độ chắc chắn.
- Học viên đo thời gian review và số deadline bị sai/thiếu.
- Nếu ổn, bước sau mới đưa deadline đã xác nhận vào calendar/checklist.

Exit / rollback:

- Nếu AI bỏ sót deadline quan trọng trong 2 lần test liên tiếp, hạ xuống rule + checklist thủ công.
- Nếu AI thường xuyên nhầm ngày/môn học, chỉ dùng để tóm tắt thông báo, không dùng để tạo deadline.
- Nếu nguồn Zalo không thể export/paste ổn định, pilot chỉ dùng Mail + LMS trước.

Decision rationale:

- Problem rõ, actor rõ, workflow rõ.
- Có non-AI alternative: calendar chung, pinned message, checklist deadline.
- AI nằm ở một bước cụ thể: lọc và tóm tắt candidate deadline.


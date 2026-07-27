## Scan

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi ngày phải tổng hợp công việc từ các nguồn như bài học lý thuyết, bài lab, công việc được thông báo trên Jira, Discord | Học viên | Mất khoảng 90 phút/tuần |
| 2 | Tốn thời gian |  | Học viên | Lặp lại mỗi tuần |
| 3 | Tốn thời gian | Phải đọc tài liệu học tập quá dài | Học viên | 60 phút/bản |
| 4 | Lặp lại | Phải viết /daily trên Discord hằng ngày, nếu quên sẽ mất điểm | Học viên | 30 phút/tuần |
| 5 | Pain từ người khác | Học viên phải hỏi lại Lab Coach khi thông báo không rõ ràng thông tin | Học viên | Đôi khi thông tin cung cấp khá mơ hồ |
| 6 | AI có thể tốt hơn | Việc phải trả lời những câu hỏi lặp đi lặp từ nhiều học viên | Lab Coach | 5-10/lần trả lời |
| 7 | AI có thể tốt hơn | Lịch học không được nhắc nhở khiến học viên quên | Học viên | Trễ giờ học/ Quên lịch học |
| 8 | Lặp lại | Học viên phải viết báo cáo hàng tuần/ hàng ngày cho team và Lab Coach | Học viên | Hay bị trễ deadline/ Tốn 60 phút/tuần |


## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Job Summary | Pain lớn nhất của học viên, xảy ra hằng ngày, tốn nhiều thời gian và dễ bỏ sót deadline. AI có thể tự động tổng hợp, phân loại và nhắc việc. | Khó tích hợp đầy đủ dữ liệu từ nhiều nền tảng và đồng bộ theo thời gian thực. |
| 2 | Read Documments | Hầu hết học viên đều gặp, AI có thể tóm tắt nội dung, trích ý chính và tạo checklist giúp tiết kiệm nhiều thời gian. | Cần đảm bảo AI không bỏ sót kiến thức quan trọng hoặc tóm tắt sai ý. |
| 3 | Daily/Weekly Report | Công việc lặp lại hằng ngày/hằng tuần, tốn thời gian và dễ trễ deadline. AI có thể tự động tạo báo cáo từ công việc đã thực hiện | Cần đánh giá chất lượng báo cáo do AI sinh và khả năng phản ánh đúng tiến độ thực tế. |

## Problem Card #1 — Job Summary

**Problem 1 câu:**  
Mỗi ngày học viên phải mất khoảng 15–20 phút kiểm tra Discord, Jira và tài liệu học để tổng hợp các công việc cần làm, dễ bỏ sót deadline hoặc thông báo quan trọng.

**Actor:**  
Học viên tham gia chương trình AI20K, phải theo dõi nhiều nguồn thông tin mỗi ngày.

**Thời điểm / bối cảnh:**  
Đầu mỗi ngày học hoặc sau khi có nhiều thông báo mới trên Discord/Jira.

**Current workflow:**

```text
1. Mở Discord đọc thông báo mới
2. Kiểm tra Jira xem có task mới hay thay đổi
3. Mở LMS/Google Drive xem bài học và Lab
4. Ghi lại các công việc cần làm
5. Sắp xếp theo mức độ ưu tiên
6. Tự nhớ deadline hoặc đặt nhắc lịch
```

**Bottleneck:**  
Thông tin nằm ở nhiều nền tảng khác nhau nên học viên phải tự tổng hợp, rất dễ bỏ sót task hoặc deadline.

**Impact:**  
Khoảng 90 phút/tuần cho mỗi học viên. Việc bỏ sót thông báo có thể dẫn đến nộp bài muộn hoặc chậm tiến độ.

**Success metric:**  
Giảm thời gian tổng hợp công việc xuống dưới 5 phút/ngày và giảm số lần học viên bỏ sót deadline.

**Non-AI alternative:**  
Tự tạo checklist hoặc sử dụng Google Calendar để ghi nhớ công việc, nhưng vẫn phải cập nhật thủ công từ nhiều nguồn.

**AI hypothesis:**  
AI tự động thu thập thông tin từ Discord, Jira và tài liệu học, sau đó tạo danh sách công việc, ưu tiên và nhắc deadline.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 20 phút/ngày

[1 Đọc Discord: 7']
→ [2 Kiểm tra Jira: 5']
→ [3 Xem bài học/Lab: 5']
→ [4 Tổng hợp task: 3']
```

### Draft future workflow

```text
FUTURE STATE — 3 phút/ngày

[1 AI đồng bộ dữ liệu: 1']
→ [2 AI tạo To-do + Deadline: <1']
→ [3 Học viên review và bắt đầu làm: 2']

Fallback: AI thiếu task → học viên kiểm tra thủ công.
```

## Problem Card #2 — Read Document

**Problem 1 câu:**  
Học viên phải dành khoảng 60 phút để đọc mỗi tài liệu học tập dài trước khi bắt đầu Lab, khiến việc tiếp thu kiến thức và hoàn thành bài tập bị chậm.

**Actor:**  
Học viên cần đọc tài liệu lý thuyết trước khi thực hiện Lab hoặc Assignment.

**Thời điểm / bối cảnh:**  
Trước mỗi buổi học hoặc khi bắt đầu một module mới.

**Current workflow:**

```text
1. Mở tài liệu học
2. Đọc toàn bộ nội dung
3. Highlight ý quan trọng
4. Ghi chú lại
5. Quay lại tìm thông tin khi làm Lab
```

**Bottleneck:**  
Tài liệu dài, nhiều nội dung không cần thiết cho bài Lab nên học viên mất nhiều thời gian tìm ý chính.

**Impact:**  
Khoảng 60 phút cho mỗi tài liệu. Nếu học nhiều module, tổng thời gian đọc rất lớn và làm chậm tiến độ học.

**Success metric:**  
Giảm thời gian đọc xuống dưới 15 phút nhưng vẫn đảm bảo học viên hoàn thành Lab với chất lượng tương đương.

**Non-AI alternative:**  
Đọc mục lục hoặc ghi chú của các học viên khóa trước, nhưng chất lượng không đồng đều và dễ thiếu thông tin.

**AI hypothesis:**  
AI tóm tắt tài liệu, trích xuất ý chính, tạo checklist và các bước cần thực hiện trước khi làm Lab.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 60 phút

[1 Đọc tài liệu: 40']
→ [2 Highlight: 10']
→ [3 Ghi chú: 10']
```

### Draft future workflow

```text
FUTURE STATE — 15 phút

[1 AI tóm tắt tài liệu: <1']
→ [2 Học viên đọc summary: 8']
→ [3 AI tạo checklist + Q&A: 2']
→ [4 Học viên bắt đầu Lab: 5']

Fallback: Summary thiếu ý → mở tài liệu gốc.
```

## Problem Card #3 — Daily/Weekly Report

**Problem 1 câu:**  
Học viên phải viết Daily Report trên Discord và Weekly Report cho Lab Coach mỗi tuần, mất nhiều thời gian và dễ quên hoặc nộp trễ.

**Actor:**  
Học viên cần cập nhật tiến độ cho Team và Lab Coach.

**Thời điểm / bối cảnh:**  
Cuối ngày làm việc và cuối mỗi tuần.

**Current workflow:**

```text
1. Nhớ lại các công việc đã làm
2. Mở Jira/Git/ghi chú
3. Tổng hợp tiến độ
4. Viết Daily hoặc Weekly Report
5. Kiểm tra lại nội dung
6. Gửi lên Discord
```

**Bottleneck:**  
Học viên phải nhớ lại toàn bộ công việc trong ngày hoặc tuần nên mất thời gian và dễ thiếu nội dung quan trọng.

**Impact:**  
Khoảng 60 phút/tuần cho mỗi học viên. Báo cáo trễ hoặc thiếu thông tin khiến Lab Coach khó theo dõi tiến độ.

**Success metric:**  
Giảm thời gian viết báo cáo xuống dưới 10 phút và giảm số lần nộp trễ.

**Non-AI alternative:**  
Sử dụng template báo cáo hoặc checklist, nhưng học viên vẫn phải tự tổng hợp nội dung.

**AI hypothesis:**  
AI tự động lấy dữ liệu từ Jira, Git hoặc lịch sử công việc để tạo bản nháp Daily/Weekly Report, học viên chỉ cần chỉnh sửa trước khi gửi.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 60 phút/tuần

[1 Xem lại công việc: 15']
→ [2 Tổng hợp nội dung: 20']
→ [3 Viết báo cáo: 20']  <-- bottleneck
→ [4 Review + Gửi: 5']
```

### Draft future workflow

```text
FUTURE STATE — 10 phút

[1 AI thu thập tiến độ: 2']
→ [2 AI draft báo cáo: 1']
→ [3 Học viên review + chỉnh sửa: 5']  <-- human boundary
→ [4 Gửi Discord: 2']

Fallback: AI draft chưa đúng → học viên chỉnh sửa hoặc viết lại một phần.
```
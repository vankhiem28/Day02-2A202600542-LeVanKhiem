# 01 — Individual Problem Scan

## Bối cảnh scan

Tôi scan các vấn đề từ đời sống học tập cá nhân và các app tôi dùng hằng ngày: Discord/chat lớp, Calendar, to-do app, Google Drive, tài liệu học, note cá nhân và các file bài tập. Mục tiêu là tìm problem có actor rõ, workflow vẽ được, bottleneck cụ thể và có thể đo bằng thời gian/tần suất.

## Scan rộng

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI có thể tốt hơn | Tìm lại câu trả lời cũ trong Discord hoặc chat lớp khi cần làm bài | Học viên cần xem lại hướng dẫn, deadline hoặc câu trả lời của giảng viên | Mỗi lần tìm mất khoảng 10-20 phút vì phải nhớ keyword và đọc nhiều đoạn chat |
| 2 | Lặp lại / Tốn thời gian | Theo dõi deadline rải rác nhiều nơi như LMS, Discord, Calendar, note cá nhân | Học viên có nhiều bài/lab cùng lúc | Xảy ra hầu như mỗi tuần; có lúc phải mở 3-4 app để chắc bài nào sắp đến hạn |
| 3 | Tốn thời gian | Đọc tài liệu dài trước khi làm bài nhưng không biết phần nào quan trọng nhất | Học viên chuẩn bị làm lab hoặc assignment | Một tài liệu 10-20 trang có thể mất 30-45 phút để đọc và lọc ý |
| 4 | Pain từ người khác / AI có thể tốt hơn | Không biết bài nộp còn thiếu field nào trước deadline | Học viên nộp bài theo rubric/checklist | Trước khi nộp thường phải so lại README, worksheet và file làm bài trong 15-25 phút |
| 5 | Tốn thời gian | Tổng hợp ghi chú từ nhiều nguồn: slide, note cá nhân, chat, tài liệu chính thức | Học viên muốn ôn lại hoặc viết bài nộp | Ghi chú bị rời rạc, mỗi lần tổng hợp mất khoảng 30 phút |
| 6 | Tốn thời gian / Lặp lại | Ôn tập từ slide, note và bài tập cũ nhưng khó biết phần nào mình chưa chắc | Học viên chuẩn bị kiểm tra hoặc hỏi đáp nhanh | Mất 45-60 phút để tự rà lại, nhưng vẫn dễ bỏ sót lỗ hổng kiến thức |
| 7 | Lặp lại | Quản lý task cá nhân giữa Calendar, to-do app và tin nhắn nhóm | Học viên vừa học vừa làm việc nhóm | Mỗi ngày mất 5-10 phút rà lại; task dễ bị rơi nếu chỉ nằm trong chat |
| 8 | Tốn thời gian / AI có thể tốt hơn | Tóm tắt video hoặc bài giảng dài để lấy ý chính | Học viên xem lại bài giảng sau buổi học | Video 30-60 phút khó tua đúng đoạn; mất nhiều thời gian nếu chỉ cần vài ý chính |
| 9 | Pain từ người khác | Chia việc nhóm và theo dõi ai đang làm phần nào trong bài nhóm | Thành viên nhóm làm assignment/lab chung | Hay phải hỏi lại trong chat; dễ trùng việc hoặc chờ nhau nếu không có owner rõ |
| 10 | Tốn thời gian / Lặp lại | Tìm file, link hoặc tài liệu cũ nằm rải rác trong Drive, Discord, browser bookmark | Học viên cần dùng lại tài liệu đã được gửi trước đó | Mỗi lần tìm mất 5-15 phút; keyword không nhớ chính xác thì phải hỏi lại bạn khác |

## Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Theo dõi deadline rải rác nhiều app | Workflow rõ, xảy ra thường xuyên, impact dễ đo bằng thời gian và số deadline bị bỏ sót | Cần xác nhận số app và tần suất trễ/nhầm deadline thật trong vài tuần gần đây |
| 2 | Tìm lại câu trả lời/tài liệu cũ trong Discord hoặc chat lớp | Pain rất quen, có actor rõ, AI/search có thể hỗ trợ một bước cụ thể | Cần biết dữ liệu chat có được truy cập/tìm kiếm hợp lệ không |
| 3 | Kiểm tra bài nộp có thiếu yêu cầu nào trước deadline | Gắn trực tiếp với rubric, dễ vẽ workflow trước/sau, boundary human review rõ | Chất lượng checklist tự động phụ thuộc vào độ rõ của yêu cầu trong README/worksheet |

---

# Problem Card #1 — Theo dõi deadline rải rác nhiều app

**Problem 1 câu:**  
Học viên mất thời gian và dễ bỏ sót deadline vì thông tin bài nộp nằm rải rác trong LMS, Discord, Calendar, note cá nhân và file hướng dẫn.

**Actor:**  
Học viên đang tham gia nhiều buổi lab/assignment trong cùng tuần.

**Thời điểm / bối cảnh:**  
Cuối ngày hoặc trước mỗi buổi học, khi cần kiểm tra bài nào sắp đến hạn và cần chuẩn bị gì.

**Current workflow:**

```text
1. Mở Discord/chat lớp để xem thông báo mới
2. Mở LMS hoặc README để kiểm tra yêu cầu bài
3. Mở Calendar để xem deadline đã được lưu chưa
4. Mở note/to-do app để so lại task cá nhân
5. Tự tổng hợp deadline và việc cần làm
6. Cập nhật lại Calendar/to-do nếu thiếu
```

**Bottleneck:**  
Bước 5 — tự tổng hợp deadline và việc cần làm từ nhiều nguồn, mất khoảng 15-20 phút/lần và dễ sót thông tin.

**Impact:**  
Nếu kiểm tra 3 lần/tuần, tổng thời gian khoảng 45-60 phút/tuần. Khi sót deadline, bài nộp dễ bị làm gấp hoặc thiếu field.

**Success metric:**  
Giảm thời gian rà deadline từ 15-20 phút/lần xuống dưới 5 phút/lần, và không bỏ sót deadline/bài cần nộp trong tuần.

**Non-AI alternative:**  
Dùng một checklist cố định hoặc Calendar rule: mọi deadline phải được nhập ngay khi có thông báo. Cách này đơn giản nhưng vẫn phụ thuộc vào việc tự nhớ cập nhật.

**AI hypothesis:**  
AI hỗ trợ đọc/tóm tắt thông báo và file hướng dẫn được cung cấp, sau đó đề xuất danh sách deadline/task. Học viên vẫn kiểm tra lại trước khi thêm vào Calendar.

**Quick gut:**  
Workflow.

## Draft current workflow

```text
CURRENT STATE — khoảng 20 phút/lần

[Mở Discord/chat: 5']
→ [Mở LMS/README: 5']
→ [Mở Calendar: 3']
→ [Mở note/to-do: 3']
→ [Tự tổng hợp deadline/task: 4']  <-- bottleneck
→ [Cập nhật lại Calendar/to-do: 2']
```

## Draft future workflow

```text
FUTURE STATE — khoảng 5 phút/lần

[Paste/link thông báo + yêu cầu bài: 1']
→ [Workflow trích deadline/task: 1']
→ [AI tóm tắt việc cần làm: 1']
→ [Học viên kiểm tra lại: 2']  <-- human boundary
→ [Thêm vào Calendar/to-do nếu đúng: 1']

Fallback: Nếu AI hiểu sai deadline hoặc thiếu context, học viên quay lại đọc nguồn gốc và cập nhật thủ công.
```

---

# Problem Card #2 — Tìm lại câu trả lời/tài liệu cũ trong Discord hoặc chat lớp

**Problem 1 câu:**  
Khi làm bài, học viên mất nhiều thời gian tìm lại câu trả lời hoặc tài liệu cũ trong Discord/chat lớp vì keyword không nhớ chính xác và thông tin nằm trong nhiều thread.

**Actor:**  
Học viên cần xem lại hướng dẫn, ví dụ, link tài liệu hoặc câu trả lời của giảng viên/bạn học.

**Thời điểm / bối cảnh:**  
Khi đang làm bài và gặp câu hỏi như "nộp file nào?", "rubric nằm đâu?", "giảng viên có nói gì về phần này chưa?"

**Current workflow:**

```text
1. Nhớ lại keyword liên quan
2. Search trong Discord/chat
3. Mở từng kết quả hoặc thread
4. Đọc lại đoạn trước/sau để hiểu context
5. Copy link hoặc ghi chú lại câu trả lời đúng
6. Nếu không tìm được thì hỏi lại nhóm/lớp
```

**Bottleneck:**  
Bước 3-4 — phải mở nhiều kết quả và đọc context thủ công, mất khoảng 10-20 phút/lần.

**Impact:**  
Tốn thời gian khi đang làm bài, dễ hỏi lại câu đã được trả lời, làm gián đoạn nhóm/lớp.

**Success metric:**  
Giảm thời gian tìm câu trả lời từ 10-20 phút xuống dưới 3 phút cho các câu hỏi đã từng được trả lời.

**Non-AI alternative:**  
Tạo FAQ hoặc ghim các câu trả lời quan trọng. Cách này tốt với câu hỏi lặp lại, nhưng cần người duy trì và dễ thiếu các case mới.

**AI hypothesis:**  
AI/search hỗ trợ truy xuất và tóm tắt các đoạn chat/tài liệu liên quan, kèm link nguồn để học viên tự kiểm.

**Quick gut:**  
Workflow.

## Draft current workflow

```text
CURRENT STATE — khoảng 15 phút/lần

[Nghĩ keyword: 2']
→ [Search trong chat: 3']
→ [Mở nhiều kết quả: 4']
→ [Đọc context: 5']  <-- bottleneck
→ [Ghi lại câu trả lời/link: 1']
→ [Hỏi lại nếu không tìm được: tùy trường hợp]
```

## Draft future workflow

```text
FUTURE STATE — khoảng 3 phút/lần

[Nhập câu hỏi tự nhiên: 30s]
→ [Search lấy đoạn liên quan: 30s]
→ [AI tóm tắt câu trả lời + nguồn: 1']
→ [Học viên mở link kiểm lại: 1']  <-- human boundary

Fallback: Nếu nguồn không rõ hoặc câu trả lời mâu thuẫn, hỏi lại giảng viên/nhóm.
```

---

# Problem Card #3 — Kiểm tra bài nộp có thiếu yêu cầu nào trước deadline

**Problem 1 câu:**  
Trước khi nộp bài, học viên phải tự đối chiếu README, worksheet, rubric và file làm bài nên dễ thiếu field hoặc nhầm yêu cầu.

**Actor:**  
Học viên chuẩn bị nộp assignment/lab.

**Thời điểm / bối cảnh:**  
1-2 giờ trước deadline, khi đã có bản nháp bài làm và cần kiểm tra lần cuối.

**Current workflow:**

```text
1. Mở README để đọc tiêu chí nộp
2. Mở worksheet để xem checklist chi tiết
3. Mở file bài làm cá nhân
4. Tự so từng yêu cầu với nội dung đã viết
5. Sửa phần thiếu hoặc ghi chú phần chưa chắc
6. Nộp bài
```

**Bottleneck:**  
Bước 4 — tự so từng yêu cầu với bài làm, mất khoảng 15-25 phút và dễ bỏ sót các field nhỏ.

**Impact:**  
Bài nộp có thể mất điểm vì thiếu phần không khó nhưng bị quên, ví dụ thiếu metric, boundary, hoặc workflow after.

**Success metric:**  
Giảm thời gian kiểm tra từ 15-25 phút xuống dưới 7 phút, và phát hiện được các phần thiếu quan trọng trước khi nộp.

**Non-AI alternative:**  
Dùng checklist thủ công copy từ worksheet. Cách này đáng làm trước, nhưng vẫn cần người tự đọc và tick từng mục.

**AI hypothesis:**  
AI hỗ trợ đọc rubric/checklist và bài nháp, sau đó chỉ ra phần nào còn thiếu hoặc mơ hồ. Học viên tự quyết định sửa gì và chịu trách nhiệm nội dung cuối.

**Quick gut:**  
Workflow.

## Draft current workflow

```text
CURRENT STATE — khoảng 25 phút/lần

[Mở README/rubric: 5']
→ [Mở worksheet/checklist: 5']
→ [Mở bài làm: 2']
→ [So từng yêu cầu: 10']  <-- bottleneck
→ [Sửa phần thiếu: 3'+]
→ [Nộp bài]
```

## Draft future workflow

```text
FUTURE STATE — khoảng 7 phút/lần

[Chuẩn bị rubric + bài nháp: 1']
→ [Workflow tạo checklist yêu cầu: 1']
→ [AI so bài nháp với checklist: 2']
→ [Học viên kiểm lại các cảnh báo: 3']  <-- human boundary
→ [Sửa và nộp]

Fallback: Nếu AI đánh giá sai hoặc yêu cầu mơ hồ, học viên quay lại README/worksheet và tự kiểm thủ công.
```

---

## Card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
Theo dõi deadline rải rác nhiều app.
```

Vì sao:

```text
Problem này xảy ra thường xuyên, có workflow rõ, có thể đo bằng thời gian rà deadline mỗi lần và số deadline/task bị bỏ sót. Scope cũng vừa với lab vì không cần agent tự làm toàn bộ việc học, chỉ cần một workflow gom nguồn thông tin, trích deadline/task, rồi để học viên kiểm lại.
```

Câu hỏi tôi muốn nhóm challenge:

```text
Liệu problem này chỉ cần checklist/Calendar discipline là đủ chưa, hay thật sự cần AI hỗ trợ đọc/tóm tắt thông báo và yêu cầu bài từ nhiều nguồn?
```

## Ghi chú dùng AI ở phase cá nhân

Tôi có thể dùng AI để gợi ý thêm góc nhìn và phản biện Problem Card, nhưng không để AI tự bịa trải nghiệm. Những số liệu thời gian trong bài là ước lượng từ trải nghiệm cá nhân và nên được thay bằng số thật hơn nếu tôi có log cụ thể.

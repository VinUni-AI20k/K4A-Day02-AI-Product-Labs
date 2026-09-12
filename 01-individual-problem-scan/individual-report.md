# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Phạm Minh Hiếu
- Mã học viên: 2A202602919
- Vai trò / bối cảnh: Intern Product Manager tại tập đoàn lớn, team product 5-10 người
- Công việc hằng tuần:
  - Tổng hợp weekly report từ nhiều nguồn (Jira, Sheets, Slack) gửi cho PM Lead và quản lý
  - Dự họp cross-team 3-4 buổi/tuần, ghi meeting notes
  - Hỗ trợ viết và cập nhật user story / requirement trên Jira
  - Tổng hợp feedback từ user research và stakeholder vào tài liệu chung
  - Đọc và học quy trình nội bộ, tài liệu onboarding công ty

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Mỗi thứ Sáu tổng hợp weekly report từ Jira, Google Sheets, Slack rồi viết narrative gửi PM Lead | Intern PM (tôi), PM Lead chờ báo cáo | Mất 60-80 phút/tuần; bấm giờ 3 tuần liên tiếp: 65', 75', 70'. Thường xuyên nộp trễ 1-2 tiếng so với deadline 5pm |
| 2 | Tốn thời gian | Sau mỗi buổi họp cross-team (60'), phải ghi lại meeting notes từ trí nhớ + ghi chú rời | Intern PM, team member cần đọc lại | Mất 20-30 phút/buổi; 3-4 buổi/tuần = 60-120 phút/tuần chỉ để ghi notes. 2/4 buổi tuần trước bị quên ghi → không ai nhớ action item |
| 3 | Lặp lại | Mỗi sáng thứ Hai cập nhật status của 15-20 task trên Jira bằng cách hỏi từng người qua Slack | Intern PM, 5-6 dev/designer bị hỏi | Mất 25-35 phút mỗi thứ Hai; 3/6 người trả lời muộn nên phải nhắc lại. Tuần trước mất 40 phút vì 2 người không online |
| 4 | Pain từ người khác | Designer và dev hay hỏi lại requirement vì user story trên Jira viết chưa đủ rõ ngữ cảnh | Designer (2 người), Dev (3 người), Intern PM phải giải thích lại | 4-5 lần hỏi lại/tuần qua Slack; có ticket bị block 1 ngày vì hiểu sai acceptance criteria. Thread Slack trung bình 8-12 tin nhắn qua lại mỗi lần |
| 5 | Tốn thời gian + AI có thể tốt hơn | Tổng hợp feedback user research từ 5-8 bản ghi phỏng vấn (Google Docs) vào 1 bảng tổng hợp | PM Lead, Intern PM, Design team | Mỗi đợt research mất 2-3 tiếng đọc + gom; làm 2 lần/tháng. Lần gần nhất bỏ sót 3 insight quan trọng vì đọc nhanh |
| 6 | Tốn thời gian | Đọc tài liệu quy trình nội bộ (SOP, policy) dài 20-40 trang để hiểu cách làm việc ở công ty mới | Intern PM (tôi), các intern mới khác | Mất 2-3 tiếng/tài liệu; đọc xong vẫn phải hỏi lại mentor 3-4 câu vì tài liệu viết chung chung. 3 intern cùng đợt cũng gặp tình trạng giống nhau |
| 7 | Lặp lại + Pain từ người khác | PM Lead hay hỏi "sprint này velocity thế nào" hoặc "task X đang ở đâu" mà thông tin đã có trên Jira nhưng dashboard khó đọc | PM Lead, Intern PM phải tra lại | 3-4 lần/tuần bị hỏi; mỗi lần mất 5-10 phút mở Jira, filter, screenshot rồi trả lời trên Slack |
| 8 | AI có thể tốt hơn | Khi viết user story mới, phải đọc lại 10-15 story cũ liên quan để đảm bảo không trùng lặp và nhất quán format | Intern PM, PM Lead review | Mất 15-25 phút/story mới; viết 3-4 story/tuần. PM Lead từng reject 1 story vì trùng logic với story cũ mà tôi không biết |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi là Intern PM ở tập đoàn lớn, công việc hàng tuần gồm viết report, dự họp, quản lý Jira. Tôi đã scan 5 problems. Gợi ý thêm theo 4 lăng kính."
- Ý dùng được: AI gợi ý thêm problem về viết user story trùng lặp (problem #8) — đúng pain thật vì tuần trước bị reject story.
- Ý bỏ vì không phải pain thật: AI gợi ý "xây chatbot trả lời FAQ nội bộ" — quá rộng, không phải workflow tôi gặp hàng ngày. Cũng bỏ ý "tự động hóa CI/CD" vì đó là việc của DevOps, không phải PM.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp weekly report từ Jira, Sheets, Slack rồi viết narrative | Workflow rõ 6-7 bước, bottleneck ở bước viết narrative, có baseline thời gian (60-80'/tuần), impact đo được | Narrative "đủ tốt" đo bằng gì? PM Lead có chấp nhận AI draft không? |
| 2 | Ghi meeting notes sau họp cross-team | Lặp lại 3-4 lần/tuần, mất 60-120'/tuần, có bằng chứng rõ (2/4 buổi bị quên ghi) | Bot ghi âm có được phép dùng trong họp công ty không? Data nhạy cảm? |
| 3 | User story viết chưa rõ → designer/dev hỏi lại | Pain từ nhiều người (5 người bị ảnh hưởng), có số liệu (4-5 lần hỏi lại/tuần, 1 ticket bị block), có thể so sánh Rule/Workflow | "Đủ rõ" định nghĩa thế nào? Checklist có giải được không hay cần AI hiểu context? |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tổng hợp weekly report

```text
Problem 1 câu:
Mỗi thứ Sáu Intern PM mất 60-80 phút tổng hợp weekly report từ 3 nguồn (Jira, Sheets, Slack), trong đó bước viết narrative tốn 25-30 phút và hay bị trễ deadline.

Actor:
Intern PM chịu trách nhiệm gửi weekly report cho PM Lead trước 5pm thứ Sáu.

Thời điểm / bối cảnh:
Thứ Sáu hằng tuần, trước buổi leadership review đầu tuần sau. Team product 5-10 người tại tập đoàn lớn.

Current workflow 3-7 bước:
1. Mở Jira, filter sprint hiện tại, export danh sách task + status (10')
2. Mở Google Sheets, lấy metrics KPI tuần (conversion, bug count, ...) (10')
3. Đọc lại Slack channel team + thread quan trọng trong tuần (15')
4. Copy tất cả vào Google Docs, sắp xếp theo mục (10')
5. Viết narrative: highlight, risk, blocker, next action (25-30') ← bottleneck
6. Tự review format, sửa lỗi chính tả, check số liệu (10')
7. Gửi email cho PM Lead + CC stakeholders (5')

Bottleneck:
Bước 5 — viết narrative. Phải tự biến raw data thành insight: tuần này tốt hay xấu, risk gì, cần escalate không. Hay bị blank page 5-10 phút đầu, rồi viết lại 2-3 lần vì chưa đủ rõ.

Impact:
60-80 phút/tuần cho 1 Intern PM. Báo cáo trễ 1-2 tiếng (3/4 tuần gần nhất) → PM Lead không có thông tin kịp chuẩn bị leadership review. Nếu 2 PM cùng gửi trễ → quản lý thiếu bối cảnh sprint.

Success metric:
Giảm tổng thời gian từ 60-80 phút xuống dưới 25 phút; không tăng số lần PM Lead hỏi lại hoặc yêu cầu sửa report (hiện tại 0-1 lần/tuần).

Non-AI alternative:
Template cố định + Jira dashboard tự động + checklist narrative có thể giảm effort format và lấy số, nhưng không giải quyết phần viết narrative tuỳ theo context mỗi tuần.

AI hypothesis:
AI đọc data từ 3 nguồn đã gom, draft narrative có cấu trúc (highlight, risk, action). Intern PM review, sửa, rồi gửi. AI không tự gửi report.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 60-80 phút

[1 Export Jira: 10'] → [2 Lấy metrics Sheets: 10'] → [3 Đọc Slack recap: 15'] → [4 Gom vào Docs: 10'] → [5 Viết narrative: 25-30']  <-- bottleneck → [6 Review + format: 10'] → [7 Gửi email: 5']

FUTURE STATE — 20 phút

[1 Script auto-pull Jira + Sheets: 2' — Rule] → [2 AI tổng hợp + highlight Slack: 2' — AI] → [3 AI draft narrative: 2' — AI] → [4 PM review + edit narrative: 12' — human boundary] → [5 PM gửi: 2']

Fallback: AI draft narrative tệ hoặc sai số → PM bỏ draft, tự viết lại từ data đã gom (vẫn tiết kiệm 20 phút so với workflow cũ nhờ auto-pull).
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Ghi meeting notes sau họp cross-team

```text
Problem 1 câu:
Sau mỗi buổi họp cross-team 60 phút, Intern PM mất thêm 20-30 phút ghi lại meeting notes từ trí nhớ, và 2/4 buổi tuần trước bị quên ghi dẫn đến mất action items.

Actor:
Intern PM ghi notes cho team; team member cần đọc lại quyết định và action items.

Thời điểm / bối cảnh:
Sau mỗi buổi họp cross-team (3-4 lần/tuần, mỗi buổi 60'). Họp qua Google Meet, team 5-10 người.

Current workflow 3-7 bước:
1. Dự họp, vừa nghe vừa ghi chú rời trên Notion/giấy (60')
2. Sau họp, mở ghi chú + cố nhớ lại nội dung (5')
3. Viết meeting notes có cấu trúc: quyết định, action items, ai làm gì (15-20')
4. Đăng notes lên Slack channel team (3')
5. Nếu có action item → tạo task trên Jira thủ công (5-10')

Bottleneck:
Bước 3 — viết notes có cấu trúc. Ghi chú rời thường thiếu sót, phải nhớ lại, hay bỏ sót quyết định nhỏ. Nếu không viết ngay sau họp → quên 30-50% nội dung.

Impact:
60-120 phút/tuần (3-4 buổi × 20-30'/buổi). 2/4 buổi tuần trước không có notes → team không rõ ai chịu action item gì → 2 task bị delay vì không ai nhận.

Success metric:
100% buổi họp có notes trong 10 phút sau khi kết thúc (hiện tại ~50%). Giảm thời gian ghi notes từ 20-30'/buổi xuống dưới 5'/buổi. Giảm số action item bị rơi xuống 0/tuần.

Non-AI alternative:
Phân công luân phiên ghi notes + template meeting notes cố định. Giảm effort nhưng vẫn phụ thuộc người ghi nhớ đúng.

AI hypothesis:
Bot tự ghi transcript họp → AI trích xuất quyết định + action items + owner → người xác nhận trong 2-3 phút.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 20-30 phút/buổi

[1 Dự họp + ghi chú rời: 60'] → [2 Nhớ lại nội dung: 5'] → [3 Viết notes có cấu trúc: 15-20']  <-- bottleneck → [4 Đăng Slack: 3'] → [5 Tạo task Jira: 5-10']

FUTURE STATE — 5 phút/buổi

[1 Bot ghi transcript tự động: 0' — Rule] → [2 AI trích xuất quyết định + action items: 0' — AI] → [3 PM xác nhận + sửa: 3' — human boundary] → [4 Auto-post lên Slack: 0' — Rule] → [5 PM tạo task Jira từ list: 2']

Fallback: Bot không join được họp (họp nhạy cảm, lỗi kỹ thuật) → quay về cách cũ: PM ghi tay + template.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — User story viết chưa rõ → designer/dev hỏi lại

```text
Problem 1 câu:
User story trên Jira thiếu ngữ cảnh và acceptance criteria rõ, dẫn đến designer và dev hỏi lại 4-5 lần/tuần, có ticket bị block 1 ngày vì hiểu sai yêu cầu.

Actor:
Intern PM viết user story; 2 designer + 3 dev đọc và thực hiện.

Thời điểm / bối cảnh:
Khi viết user story mới (3-4 story/tuần) và khi dev/designer bắt đầu implement. Team product 5-10 người, tập đoàn lớn.

Current workflow 3-7 bước:
1. PM nhận yêu cầu từ PM Lead hoặc stakeholder (qua họp/Slack)
2. PM đọc lại 10-15 story cũ liên quan để check trùng lặp và nhất quán (15-25')
3. PM viết user story trên Jira: title, description, acceptance criteria (20-30')
4. PM tự review một lần (5')
5. Assign cho dev/designer
6. Dev/designer đọc → hỏi lại qua Slack khi chưa hiểu (8-12 tin nhắn/lần)
7. PM giải thích lại, đôi khi sửa story (10-15'/lần hỏi lại)

Bottleneck:
Bước 3 + 6 — PM viết story thiếu context (vì chưa quen domain + format chưa nhất quán), rồi dev/designer phải hỏi lại → vòng lặp clarification.

Impact:
4-5 lần hỏi lại/tuần × 10-15'/lần = 40-75 phút/tuần chỉ cho clarification. 1 ticket bị block 1 ngày tuần trước. Dev bực vì phải đợi → giảm trust với PM.

Success metric:
Giảm số lần hỏi lại từ 4-5/tuần xuống 1-2/tuần. Giảm số ticket bị block do hiểu sai xuống 0/sprint. Dev/designer confirm story đủ rõ để bắt đầu ngay.

Non-AI alternative:
Checklist bắt buộc trước khi assign (có user persona, có acceptance criteria, có edge case) + template user story chuẩn. Có thể giải được 60-70% lỗi format.

AI hypothesis:
AI review user story trước khi assign: check thiếu field, so sánh với story cũ để phát hiện trùng lặp / mâu thuẫn, gợi ý acceptance criteria còn thiếu. PM vẫn quyết định cuối.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 35-55 phút/story (tính cả clarification)

[1 Nhận yêu cầu: 5'] → [2 Đọc story cũ: 15-25'] → [3 Viết story: 20-30'] → [4 Tự review: 5'] → [5 Assign] → [6 Dev/designer hỏi lại: 10-15'/lần × 1-2 lần]  <-- bottleneck

FUTURE STATE — 25-30 phút/story

[1 Nhận yêu cầu: 5'] → [2 AI scan story cũ + suggest format: 3' — AI/Rule] → [3 Viết story + AI gợi ý AC thiếu: 15-20' — AI hỗ trợ] → [4 Checklist auto-check trước assign: 1' — Rule] → [5 Assign] → [6 Hỏi lại giảm: 0-5']  <-- human boundary

Fallback: AI gợi ý sai hoặc không relevant → PM bỏ qua suggestion, dùng checklist thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Tổng hợp weekly report
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow viết weekly report có 7 bước rõ ràng, bottleneck nằm ở bước viết narrative (25-30 phút). Tổng mất 60-80 phút/tuần và 3/4 tuần gần nhất bị trễ deadline. Bài này có baseline thời gian cụ thể (bấm giờ 3 tuần: 65', 75', 70'), có thể so sánh rõ Rule/Workflow/Agent, và future workflow giảm xuống ~20 phút với PM vẫn giữ quyền review trước khi gửi.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Narrative "đủ tốt" đo bằng gì? Nếu PM Lead thấy narrative do AI draft nhạt hơn viết tay thì sao?
2. Template + dashboard có đủ giải bài này không — có thật sự cần AI hay chỉ cần chuẩn hoá format?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Metric "giảm thời gian" rõ nhưng chưa có metric cho chất lượng narrative. Nếu AI draft nhạt, PM vẫn phải viết lại → thời gian không giảm bao nhiêu.
- Tôi sửa gì: Thêm metric phụ: "số lần PM Lead yêu cầu sửa report không tăng so với baseline (0-1 lần/tuần)". Thêm exit criteria: nếu PM phải viết lại >70% draft trong 2 tuần liên tiếp → hạ về template + dashboard.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge

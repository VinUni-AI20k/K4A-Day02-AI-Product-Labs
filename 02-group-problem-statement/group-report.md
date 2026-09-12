# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   |           |             |                                                               |
| 2   |           |             |                                                               |
| 3   |           |             |                                                               |
| 4   |           |             |                                                               |

**Candidate problem nhóm chọn (1 câu):**
Giao tiếp hai chiều giữa người sử dụng ngôn ngữ ký hiệu và người nghe thông thường trong các tình huống đời sống hằng ngày (mua sắm, quầy dịch vụ, y tế), giúp xóa bỏ rào cản thông tin và giảm thời gian chờ trao đổi qua giấy bút thủ công.



## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 |Quân |Tổng hợp Task phân tán từ Mentor/PM |Mentor/PM |Pain thật và tần suất cao |dải nhiều nền tảng |
| 2 |Quân |Tự động hóa giải bài tập và chấm sửa lỗi |HSSV |Pain thật và tần suất cao |khả thi |
| 3 |Quân |Học tiếng Anh bằng AI |HSSV |Nhiều người đau và market lớn |khả thi |
| 4 |Việt Anh |Tốn thời gian tạo ticket |BA/Tester/Dev |Mất 2-3 phút cho 1 ticket và hay miss cấu trúc |phụ thuộc vào doanh nghiệp |
| 5 |Việt Anh |Dev và Tester hỏi BA về các requirement |Dev/Tester ↔ BA |Dev và Tester thường xuyên hỏi lại BA về requirements cũng như test case/ticket/bug... |phụ thuộc vào doanh nghiệp |
| 6 |Việt Anh |Tốn time testing ứng dụng |BA/Tester/Dev |1 test case mất 1-10 phút |phụ thuộc vào doanh nghiệp |
| 7 |Nam |Mua sắm trực tuyến phải mở nhiều sàn/shop để so sánh giá, mã giảm giá và phí ship cuối cùng |User phổ thông |Khó khăn kỹ thuật khi crawl giá và voucher động trên các app di động |khó khăn kỹ thuật |
| 8 |Nam |Giao tiếp giữa người sử dụng ngôn ngữ ký hiệu và người không biết ngôn ngữ ký hiệu |User phổ thông |Khó khăn kỹ thuật |khó khăn kỹ thuật |
| 9 |Nam |Cần đổi tên hàng loạt file tài liệu/ảnh bài tập nộp theo một quy tắc chung nhưng phải làm thủ công từng file | User phổ thông|Người dùng phổ thông có thể ngại dùng dòng lệnh (script) và chỉ cần công cụ Rule đơn giản thay vì AI |khó khăn về bảo mật |
| 10 |Phương |Tổng hợp lại note từ slide + video bài giảng sau mỗi buổi học |HSSV |Chưa chắc bottleneck có phải luôn nằm ở bước đối chiếu hay đôi khi ở bước viết lại — cần bấm giờ tách riêng từng bước để xác nhận |dài nhiều nền tảng |
| 11 |Phương |Đọc & dịch tài liệu chuyên ngành tiếng Anh |HSSV |Chưa chắc bottleneck nằm ở "dịch nghĩa" hay ở "hiểu thuật ngữ chuyên ngành" — hai bước này có thể cần giải pháp khác nhau |khó khăn về pháp lý |
| 12 |Phương |Viết lại (paraphrase) đoạn văn/báo cáo để tránh trùng lặp khi qua Turnitin |HSSV |tần suất gặp phải đủ cao để impact tổng thể lớn — chỉ 2-3 báo cáo/kỳ, cần cân nhắc so với 2 bài trên |dài nhiều nền tảng |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Hỗ trợ giao tiếp & Khả năng tiếp cận (Accessibility) | #8 (Nam), #3 (Quân), #11 (Phương) | Phá bỏ rào cản ngôn ngữ và phương thức biểu đạt hai chiều (ngôn ngữ ký hiệu ↔ chữ/giọng nói, tiếng Anh ↔ tiếng Việt) trong đời sống và học tập | Có tác động xã hội (social impact) sâu sắc; ứng dụng thị giác máy tính và AI đa phương thức |
| B. Quy trình phần mềm & Quản trị Task | #1 (Quân), #4 (Việt Anh), #5 (Việt Anh), #6 (Việt Anh) | Handoff thông tin kỹ thuật giữa các vai trò (PM ↔ BA ↔ Dev ↔ Tester); dữ liệu phân tán hoặc thao tác nhập liệu thủ công lặp lại | Quy trình chuẩn hóa cao trong doanh nghiệp IT, dễ đo lường thời gian |
| C. Học tập & Hỗ trợ học liệu HSSV | #2 (Quân), #10 (Phương), #12 (Phương) | Tiếp nhận và xử lý khối lượng kiến thức lớn (ngoại ngữ, bài tập, slide/video dài, báo cáo) | Tệp user đông, pain quen thuộc nhưng nhiều bài có phạm vi quá rộng |
| D. Tiện ích thao tác dữ liệu cá nhân | #7 (Nam), #9 (Nam) | Thao tác thủ công lặp đi lặp lại trên nhiều nền tảng mua sắm hoặc nhiều tệp tin | Bài #9 giải được bằng Rule đơn giản (script), bài #7 gặp cơ chế chống crawl của sàn TMĐT |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#8 — Giao tiếp giữa người dùng ngôn ngữ ký hiệu và người không biết** (Nam) | 1. Ý nghĩa nhân văn và tác động xã hội (social impact) cực lớn cho cộng đồng người khiếm thính.<br>2. Workflow hai chiều rõ rệt: Ký hiệu qua Camera → AI dịch thành chữ/tiếng nói; và Giọng nói người nghe → AI hiển thị chữ/hình ảnh ký hiệu.<br>3. Giải quyết điểm nghẽn thực tế: thay thế viết giấy/gõ chữ chậm chạp (mất 3-5 phút/lần) tại quầy thanh toán, bệnh viện, dịch vụ công. | Cần giới hạn tập cử chỉ thông dụng (scope) để đảm bảo khả năng nhận diện hình ảnh trong thời gian lab. |
| **#4 — Tốn thời gian tạo ticket testing / bug** (Việt Anh) | 1. Actor (Tester/BA) và workflow tạo ticket cực kỳ chuẩn xác, lặp lại hằng ngày (10-15 ticket/ngày).<br>2. Bottleneck rõ ràng: bước viết Steps to reproduce và format Expected vs Actual.<br>3. Rất khả thi để làm trong lab 1 ngày. | Phạm vi nội bộ team IT hẹp, giá trị truyền cảm hứng và tác động xã hội không cao bằng bài toán trợ năng. |
| **#10 — Tổng hợp note từ slide + video sau buổi học** (Phương) | 1. Nhu cầu ôn thi thật sự sau các buổi học dài 2-3 tiếng của sinh viên.<br>2. Phát huy đúng thế mạnh của AI trong tóm tắt văn bản và nội dung học tập. | Kỹ thuật đa phương thức (audio tiếng Việt + video 2-3 tiếng) quá nặng cho 1 ngày lab; khó thống nhất metric đo chất lượng ghi chú. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#8. Cầu nối ngôn ngữ ký hiệu** | 5 | 5 | 5 | 5 | 4 | 5 | 4 | **33** |
| **#4. Tạo ticket bug / test** | 5 | 5 | 4 | 5 | 5 | 4 | 4 | **32** |
| **#10. Note từ slide + video** | 4 | 4 | 4 | 3 | 3 | 4 | 4 | **26** |

*Ghi chú lý do chấm điểm:*
- **#8 (33đ):** Đạt điểm 5 ở Actor rõ (Người khiếm thính ↔ Người nghe bình thường tại quầy dịch vụ/cửa hàng), Workflow hai chiều rõ rệt, Pain có bằng chứng thực tế bức thiết, Impact đo lường được (rút ngắn thời gian từ 3-5 phút viết tay xuống còn 15-30 giây). Điểm 4 ở "Làm trong lab" vì nhóm sẽ giới hạn scope vào kịch bản cụ thể (quầy mua sắm/thanh toán) với bộ cử chỉ cơ bản để đảm bảo khả thi.
- **#4 (32đ):** Điểm rất cao về tính khả thi trong lab và quy trình, nhưng mức độ bức thiết và tác động xã hội (pain/impact) chỉ gói gọn trong team phần mềm nội bộ.
- **#10 (26đ):** Bị điểm 3 ở "Impact đo được" (chất lượng note khó lượng hóa) và "Làm trong lab" (xử lý video/audio 2 tiếng vượt quá scope 1 ngày lab).

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Giao tiếp hai chiều giữa người sử dụng ngôn ngữ ký hiệu và người không biết ngôn ngữ ký hiệu (Candidate #8 - Nam)
```

**Vì sao chọn (4-5 câu):**

```text
1. Đây là bài toán mang giá trị nhân văn và tác động xã hội (social impact) vượt trội, trực tiếp tháo gỡ rào cản cô lập của cộng đồng người khiếm thính khi hòa nhập xã hội.
2. Nỗi đau (pain) và sự nghẽn (bottleneck) có bằng chứng thực tế sâu sắc: mỗi lượt giao tiếp cơ bản (mua hàng, hỏi đường, thủ tục quầy dịch vụ) hiện phải dùng giấy bút hoặc gõ điện thoại rất chậm chạp (mất 3-5 phút/lượt), gây e ngại và dễ hiểu lầm.
3. Metric thành công đo lường định lượng rõ ràng: rút ngắn thời gian một lượt trao đổi từ 3-5 phút xuống dưới 30 giây, nâng tỷ lệ hiểu đúng thông điệp giữa hai bên lên trên 90%.
4. Là bài toán kinh điển để ứng dụng tư duy AI Product: kết hợp thị giác máy tính nhận diện cử chỉ (Computer Vision/MediaPipe) và mô hình ngôn ngữ (LLM) để xâu chuỗi từ khóa thành câu hội thoại tự nhiên hai chiều.
5. Đề tài tạo cảm hứng mạnh mẽ cho toàn đội ngũ, giúp sản phẩm có tính đột phá, khác biệt và nổi bật rõ rệt trong buổi báo cáo Day 02.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- #4 (Tạo ticket bug / test): Mặc dù quy trình rất chuẩn mực và quen thuộc với dân IT, nhưng đề tài chỉ phục vụ nhóm người dùng nội bộ doanh nghiệp hẹp, thiếu đi sự bứt phá và giá trị phụng sự cộng đồng sâu sắc như bài toán ngôn ngữ ký hiệu.
- #10 (Tổng hợp note từ slide + video): Việc xử lý đa phương thức (video/audio bài giảng 2-3 tiếng tiếng Việt kết hợp slide bài giảng) vượt quá phạm vi hạ tầng của lab; ngoài ra tiêu chí "ghi chú hay/đầy đủ" mang tính cảm tính, rất khó định lượng metric thành công.
- Các candidate khác (giải bài tập, học tiếng Anh, so sánh giá TMĐT, rename file...): Hoặc có phạm vi quá rộng và đã bị độc chiếm bởi các sản phẩm lớn (Duolingo, Elsa), hoặc là bài toán chỉ cần Rule/script đơn giản chứ không khai thác đúng giá trị của AI Product.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
- Lo ngại ban đầu: Quân và Việt Anh lo ngại kỹ thuật nhận diện ngôn ngữ ký hiệu (Sign Language Recognition) bằng thị giác máy tính quá phức tạp để xây dựng trọn vẹn trong một ngày lab, đồng thời nhóm chưa có ai thành thạo ngôn ngữ ký hiệu.
- Nhóm chốt cách giải quyết:
  1. Khoanh vùng phạm vi (scoping) thật chặt: Tập trung vào ngữ cảnh "Giao tiếp cơ bản tại quầy thanh toán / cửa hàng tiện lợi" với khoảng 8-12 cử chỉ thông dụng nhất (chào hỏi, hỏi giá tiền, quét mã chuyển khoản, tiền mặt, cảm ơn, cần trợ giúp).
  2. Tập trung vào tư duy Workflow Product: Dùng mô hình nhận diện điểm mốc bàn tay/cử chỉ bắt các từ khóa (keywords), sau đó dùng LLM để ghép thành câu thoại lịch sự đầy đủ hai chiều và phát âm thanh/hiển thị màn hình, kết hợp cơ chế xác nhận của người dùng (human boundary).
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | | | | |
| Survey / poll | | | | |
| Log / ticket / review (nếu có) | | | | |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text

```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text

```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 ...: __' - ai làm] → [2 ...: __'] → [3 ...: __'] → [4 ... bottleneck: __'] → ...
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |

**Bottleneck chính (2-3 câu):**

```text

```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 ...: __' - máy] → [2 AI ...: __'] → [3 ... review: __' - boundary] → [4 ... gửi]

Fallback: ...
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | | | |
| Số bước | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Risk mới | | | |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** | |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ:
- Tôi sửa gì:

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao:
- Độ phức tạp: [ ] Thấp (1-2 bước) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao:

**Bài toán nhóm nằm ở ô nào:**

```text

```

**Vì sao (2-3 câu):**

```text

```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
5. Có hạ được từ Agent → Workflow → Rule không?

**Mức chọn:**

```text
[Rule / Workflow / Agent]
```

**Vì sao chọn (3-4 câu):**

```text

```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text

```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** (làm / không làm) | |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | | |
| Baseline + metric đo được chưa? | | |
| Data/input đủ dùng chưa? | | |
| AI sai, hậu quả chấp nhận được không? | | |
| Có người review/owner không? | | |
| Có cách non-AI đơn giản hơn không? | | |

**Decision:**

```text
[Go / Not Yet / No-Go]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text

```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text

```

**Nếu Not Yet — cần validate gì trước:**

```text

```

**Nếu No-Go — làm gì thay AI:**

```text

```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text

```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Đỗ Lê Việt Anh |             | Workflow / Validation                                         |
| 2   | Nguyễn Phương Nam |             | Facilitator / Problem Owner                                   |
| 3   | Đỗ Anh Quân |             | Technical Research & Architecture                             |
| 4   | Phương     |             | Writer / Synthesizer                                          |

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
| Interview | 3 người (1 thu ngân Circle K, 1 thân nhân người khiếm thính, 1 sinh viên khiếm thính qua phiên dịch) | - Quote 1: *"Mỗi lần gặp khách khiếm thính vào mua đồ, em với bạn ấy phải đưa điện thoại qua lại gõ chữ hoặc chỉ chỏ vào quầy, vừa mất thời gian (khoảng 3-4 phút) vừa nhiều lúc hiểu nhầm loại thuốc lá hay topping trà sữa, khách sau phải đứng chờ rất sốt ruột."* (Thu ngân)<br>- Quote 2: *"Bố mình dùng ngôn ngữ ký hiệu rất nhanh, nhưng ra ngoài chợ hay trạm y tế thì gần như bị cô lập, phải viết ra sổ tay mang theo, chữ viết tay nhiều khi vội người ta đọc không ra."* (Thân nhân)<br>- Quote 3: *"Tôi chỉ mong có app quay tay tôi làm dấu rồi đọc to ra tiếng cho người bán hàng hiểu tôi muốn mua gì, và họ nói gì thì hiện chữ lên để tôi đọc ngay."* (Người khiếm thính) | *"Nếu ứng dụng nhận diện sai cử chỉ mà tự động phát âm thanh lung tung thì sẽ gây hiểu lầm tai hại, người ta thà gõ chữ trên app ghi chú cho an toàn."* | Không cố làm phiên dịch tự động hoàn toàn; bắt buộc phải có **màn hình xác nhận (review boundary)** để người khiếm thính gật đầu trước khi phát âm thanh ra loa; đồng thời thu hẹp bài toán vào kịch bản thiết yếu tại quầy dịch vụ/mua sắm. |
| Survey / poll | 15 người (nhân viên thu ngân bán lẻ, quán cà phê và sinh viên) | - 13/15 người từng gặp tình huống lúng túng khi giao tiếp với người khiếm thính.<br>- 100% người được hỏi xác nhận việc viết giấy/gõ chữ mất từ 2-4 phút/lượt và làm gián đoạn hàng chờ.<br>- 14/15 người sẵn sàng sử dụng ứng dụng hỗ trợ dịch hai chiều trực quan nếu có sẵn trên điện thoại hoặc máy tính bảng tại quầy. | 3 người lo ngại nếu camera quét không nhạy trong điều kiện ánh sáng yếu hoặc người khiếm thính làm ký hiệu quá nhanh thì app sẽ bị đơ. | Tích hợp chế độ "Phím tắt nhanh" (Quick Buttons) với các câu thông dụng tại quầy để làm fallback ngay khi camera gặp khó khăn. |
| Log / ticket / review (nếu có) | 20+ review trên Google Play của các app từ điển ký hiệu (Hand Talk, SignLanguage) | Nhiều người khiếm thính và người học phản ánh: các app hiện tại chỉ là từ điển tra cứu 1 chiều tĩnh hoặc nhân vật 3D mô phỏng, hoàn toàn thiếu tính năng nhận diện cử chỉ thực tế qua camera để nói thay họ ngoài đời. | Một số review cho rằng ngôn ngữ ký hiệu giữa miền Bắc và miền Nam có từ khác nhau nên dịch dễ bị lệch nghĩa. | Giới hạn tập cử chỉ của sản phẩm vào các cử chỉ thanh toán/mua sắm cơ bản mang tính quy chuẩn toàn quốc (chào hỏi, hỏi giá, chuyển khoản, tiền mặt, cảm ơn). |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không chỉ là rào cản ngôn ngữ đơn thuần, mà là sự bất đối xứng thời gian và áp lực tâm lý tại nơi công cộng: người khiếm thính e ngại vì làm phiền người khác, còn người nghe bối rối vì không hiểu. Điểm nghẽn nghiêm trọng nhất là việc chuyển kênh giao tiếp sang gõ chữ thủ công gây đứt gãy tương tác và kéo dài thời gian giao dịch gấp 5-7 lần.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Google MediaPipe Gesture Recognizer** | https://ai.google.dev/edge/mediapipe/solutions/vision/gesture_recognizer | Nhận diện 21 điểm mốc bàn tay (hand landmarks) và phân loại cử chỉ theo thời gian thực trực tiếp trên thiết bị (Edge AI) | Chạy cực nhanh (<50ms), chạy trên browser/mobile, bảo mật cao vì không cần gửi stream video lên cloud, mã nguồn mở miễn phí | Chỉ nhận diện các cử chỉ tĩnh hoặc chuyển động ngắn đơn lập; không tự hiểu ngữ pháp để nối thành câu hoàn chỉnh | Dùng MediaPipe làm tầng trích xuất từ khóa cử chỉ (Keyword Extractor), sau đó đưa từ khóa vào LLM để hoàn thiện ngữ cảnh |
| **SignAll Kiosk** | https://www.signall.com/ | Hệ thống dịch tự động ngôn ngữ ký hiệu ASL hai chiều đặt tại quầy giao dịch bệnh viện, trường học ở Mỹ | Độ chính xác cao, nhận diện được cử chỉ phức tạp và biểu cảm khuôn mặt nhờ hệ thống đa camera | Chi phí phần cứng cực đắt (hàng chục nghìn USD), cồng kềnh, chỉ hỗ trợ ASL (Mỹ), không thể ứng dụng rộng rãi ở Việt Nam | Cần giải pháp gọn nhẹ hoàn toàn bằng phần mềm (Software-only) chạy trên smartphone/tablet phổ thông |
| **Hand Talk App** | https://www.handtalk.me/ | Dịch văn bản/giọng nói của người nghe sang ngôn ngữ ký hiệu thông qua hình đại diện 3D (Avatar) | Trực quan, giao diện thân thiện, rất tốt cho chiều giao tiếp: Người nghe → Người khiếm thính | Hoàn toàn chưa giải quyết được chiều ngược lại bằng camera (Ký hiệu → Giọng nói), buộc người khiếm thính vẫn phải gõ chữ | Phải ưu tiên tối đa việc giải quyết chiều nghẽn nhất: Ký hiệu của người khiếm thính → Giọng nói/Văn bản người nghe hiểu được |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên cố gắng train một mô hình End-to-End từ video raw ra toàn bộ câu văn tiếng Việt vì thiếu tập dữ liệu lớn và độ trễ cao. Giải pháp tối ưu là mô hình lai (Hybrid Workflow): Dùng Computer Vision nhẹ (MediaPipe) để nhận diện các cử chỉ/từ khóa then chốt trên thiết bị, sau đó dùng LLM để bổ sung ngữ cảnh quầy dịch vụ và sinh câu hoàn chỉnh lịch sự, kết hợp STT/TTS hai chiều có con người kiểm soát.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png`

```text
CURRENT STATE — ~225 giây (~3.7 phút)

[1 Khách ra ký hiệu muốn mua đồ: 15'' - Khách] 
→ [2 Thu ngân bối rối, lắc đầu không hiểu: 15'' - Thu ngân] 
→ [3 Khách mở smartphone, tìm app Note/Ghi chú: 30'' - Khách] 
→ [4 Khách gõ chữ giải thích món đồ/nhu cầu: 60'' - Khách]  <-- bottleneck
→ [5 Đưa màn hình điện thoại cho thu ngân đọc: 20'' - Handoff] 
→ [6 Thu ngân nói lại giá tiền & hỏi thêm, khách không nghe được: 20'' - Thu ngân] 
→ [7 Thu ngân gõ lại vào điện thoại giải thích: 45'' - Thu ngân]  <-- bottleneck
→ [8 Khách gật đầu và thanh toán: 20'' - Khách & Thu ngân]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Khách khiếm thính | Nhu cầu mua hàng | Cử chỉ ngôn ngữ ký hiệu | 15 giây | Bắt đầu giao tiếp |
| 2 | Thu ngân | Cử chỉ tay của khách | Lắc đầu / bối rối | 15 giây | Handoff thất bại do rào cản ngôn ngữ |
| 3 | Khách khiếm thính | Điện thoại thông minh | Ứng dụng ghi chú (Note) | 30 giây | Chuyển đổi kênh giao tiếp thủ công |
| 4 | Khách khiếm thính | Bàn phím ảo trên điện thoại | Dòng chữ mô tả món đồ cần mua | 60 giây | **Bottleneck chính:** gõ chữ chậm trên điện thoại |
| 5 | Khách ↔ Thu ngân | Màn hình điện thoại | Thu ngân đọc hiểu câu chữ | 20 giây | Handoff vật lý qua lại |
| 6 | Thu ngân | Giọng nói | Âm thanh báo giá/hỏi thêm | 20 giây | Thất bại vì khách không nghe được |
| 7 | Thu ngân | Bàn phím điện thoại | Dòng chữ trả lời giá tiền/hướng dẫn | 45 giây | **Bottleneck phụ:** gõ câu trả lời qua lại |
| 8 | Khách & Thu ngân | Tiền mặt / Mã QR ngân hàng | Hóa đơn & món hàng | 20 giây | Hoàn tất giao dịch |

**Bottleneck chính (2-3 câu):**

```text
Bước 4 và bước 7 là hai điểm nghẽn nghiêm trọng nhất. Cả hai bên bị ép phải chuyển từ luồng giao tiếp tương tác tự nhiên sang gõ văn bản thủ công qua lại trên một màn hình điện thoại nhỏ. Tốc độ gõ chữ chậm, vốn từ ngữ pháp viết tiếng Việt của người khiếm thính có sự khác biệt nhất định với cấu trúc ký hiệu, gây tâm lý ngượng ngùng, mệt mỏi và làm ùn tắc toàn bộ hàng chờ tại quầy.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — ~25 giây

[1 Khách làm cử chỉ ký hiệu trước camera: 5'' - Người] 
→ [2 MediaPipe trích xuất landmark & nhận diện từ khóa: 1'' - Rule / Edge AI] 
→ [3 LLM ghép từ khóa thành câu hội thoại lịch sự theo ngữ cảnh: 2'' - AI] 
→ [4 Màn hình hiển thị câu dự thảo, khách bấm xác nhận OK: 3'' - Human boundary] 
→ [5 Hệ thống phát loa đọc câu thoại hoàn chỉnh cho thu ngân: 2'' - Rule / TTS] 
→ [6 Thu ngân bấm mic nói trả lời, AI chuyển thành chữ to: 4'' - AI / STT] 
→ [7 Khách đọc chữ & thanh toán hoàn tất: 8'' - Người]

Fallback: Nếu camera không nhận diện được cử chỉ (độ tin cậy < 70%) hoặc điều kiện ánh sáng kém, màn hình lập tức hiển thị bảng "Phím tắt nhanh" (Quick Buttons: "Hỏi giá", "Quét QR", "Tiền mặt", "Lấy hóa đơn", "Mang về") để khách chạm chọn trong 1 giây.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | ~225 giây (~3.7 phút) | ~25 giây | Bấm giờ từ lúc khách tiếp cận quầy đến khi nhận hàng/hóa đơn |
| Số bước | 8 bước đứt đoạn | 5 bước liền mạch | Đếm các điểm chạm tương tác trong quy trình |
| Số bước thủ công | 6 bước gõ chữ/đưa máy | 1 bước bấm xác nhận (hoặc chạm phím tắt) | Đếm số lần người dùng phải thao tác bàn phím thủ công |
| Bottleneck chính | Gõ chữ văn bản chậm chạp trên điện thoại | Đã giải quyết triệt để nhờ nhận diện cử chỉ + LLM + STT | Đo thời gian xử lý dịch thuật (< 3 giây) |
| Risk mới | Nhận diện sai cử chỉ; tạp âm quầy thanh toán làm nhiễu STT | Tỷ lệ nhận diện sai < 10%; có nút xác nhận và fallback | Đo tỷ lệ khách phải dùng nút fallback / số lần thu ngân phải nói lại |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người khiếm thính (sử dụng ngôn ngữ ký hiệu) và nhân viên thu ngân/phục vụ tại các quầy dịch vụ bán lẻ (cửa hàng tiện lợi, quán ăn/cà phê, nhà thuốc). |
| **Workflow** | Khách tiếp cận quầy thanh toán → Làm cử chỉ ký hiệu → Nhân viên không hiểu → Hai bên lúng túng chuyển sang dùng điện thoại gõ chữ qua lại từng câu → Đọc hiểu và thanh toán. |
| **Bottleneck** | Bước chuyển đổi sang gõ chữ/ghi chú thủ công qua lại mất 2-3 phút, khiến giao tiếp bị đứt gãy, gây áp lực tâm lý cho người khiếm thính và ùn tắc hàng chờ của cửa hàng. |
| **Impact** | Người khiếm thính cảm thấy tự ti và ngần ngại hòa nhập đời sống hàng ngày; nhân viên thu ngân áp lực vì phục vụ chậm giờ cao điểm; cửa hàng giảm hiệu suất phục vụ và trải nghiệm khách hàng. |
| **Success Metric** | Giảm tổng thời gian giao dịch tại quầy từ ~3.7 phút xuống dưới 30 giây; đạt tỷ lệ hiểu đúng thông điệp hai chiều ngay lần đầu >90%. |
| **Boundary** | Chỉ tập trung vào giao tiếp thiết yếu tại quầy dịch vụ bán lẻ (hỏi mua hàng, thanh toán, xác nhận số lượng/tiền, mang về); không làm phiên dịch hội thoại pháp lý, hội nghị hay y tế chuyên sâu. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Khái niệm "ngôn ngữ ký hiệu" quá rộng và có sự khác biệt từ vựng giữa các vùng miền; chưa xác định rõ cơ chế bảo vệ nếu AI dịch sai ý muốn của người khiếm thính trước mặt người nghe.
- Tôi sửa gì: Giới hạn tập cử chỉ vào bộ từ khóa chuẩn hóa cho kịch bản mua sắm/thanh toán phổ thông; thiết lập bắt buộc **bước xác nhận thị giác (visual human boundary)** trên màn hình trước khi máy phát âm thanh ra loa.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Ngôn ngữ ký hiệu diễn đạt ý niệm bằng các từ khóa cử chỉ không theo trật tự ngữ pháp văn nói; nhân viên thu ngân cũng trả lời bằng nhiều khẩu ngữ tự nhiên phong phú, đòi hỏi AI phải hiểu ngữ cảnh mềm dẻo.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Quy trình tích hợp đa phương thức nối tiếp nhau: Camera video stream → Hand Landmarks (MediaPipe) → Nhận diện cử chỉ → LLM sinh câu tự nhiên → TTS phát âm thanh → Micro thu âm giọng nói → STT hiển thị chữ to.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô Mơ hồ cao + Phức tạp cao (Complex & Ambiguous Workflow)
```

**Vì sao (2-3 câu):**

```text
Dữ liệu đầu vào và đầu ra đều ở dạng phi cấu trúc (video cử chỉ bàn tay thời gian thực và âm thanh giọng nói ngoài đời thực). Một cử chỉ tay có thể mang nhiều sắc thái biểu đạt tùy vào ngữ cảnh mua sắm, và giọng nói của thu ngân rất đa dạng. Hệ thống quy tắc tĩnh (Rule-based) hoàn toàn không thể bao quát được sự linh hoạt này.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Bảng nút bấm cảm ứng tĩnh (Quick Buttons: Chuyển khoản, Tiền mặt, Lấy hóa đơn) và hiển thị từ điển ký hiệu tra cứu tĩnh 1-1 | Khi chỉ có 3-4 nhu cầu cố định, không có tình huống phát sinh | Cực kỳ cứng nhắc; không xử lý được câu nói tự do của thu ngân; người khiếm thính muốn hỏi món ngoài danh mục thì chịu | **Có (dùng làm Fallback)** khi camera nhận diện thất bại hoặc ánh sáng kém |
| **Workflow** | Pipeline đa tầng có cấu trúc: MediaPipe bắt landmark cử chỉ → LLM ghép thành câu lịch sự theo ngữ cảnh → Màn hình review xác nhận → TTS phát loa; Chiều ngược lại STT chuyển giọng nói thành chữ to | Đủ cho 95% tình huống giao tiếp mua sắm/thanh toán có quy trình chuẩn | Độ trễ mạng khi gọi LLM/TTS; nhận diện sai cử chỉ nếu góc quay camera bị lệch | **CHỌN (Cốt lõi toàn bộ hệ thống)** |
| **Agent** | AI tự quan sát camera, tự phân tích hành vi khách, tự động lập kế hoạch và gọi API quầy POS để trừ tiền ví/thẻ ngân hàng mà không cần khách bấm xác nhận | Khi muốn tự động hóa hoàn toàn không người phục vụ (kiosk vô nhân) | Nguy cơ ảo giác (hallucination) nghiêm trọng; tự ý xác nhận sai số tiền thanh toán gây tổn thất tài chính và rắc rối pháp lý | **KHÔNG CHỌN** (quá rủi ro cho giao dịch tiền tệ) |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? Không, vì ngôn ngữ ký hiệu có sự biến thiên lớn về góc độ bàn tay, và giọng nói phản hồi của nhân viên rất đa dạng không thể bắt theo từ khóa cố định.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Có rẽ nhánh rõ ràng theo 2 chiều (Ký hiệu → Giọng nói và Giọng nói → Văn bản) và rẽ nhánh sang fallback khi độ tin cậy < 70%.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Hoàn toàn không. Quy trình giao tiếp tại quầy thanh toán có các bước tuyến tính xác định; việc để Agent tự lập kế hoạch sẽ làm tăng rủi ro sai sót và chi phí xử lý không cần thiết.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Khách khiếm thính là người phát hiện đầu tiên khi nhìn câu dự thảo trên màn hình trước khi bấm xác nhận; sửa trong 1-2 giây bằng cách làm lại cử chỉ hoặc chạm nút Quick Button.
5. Có hạ được từ Agent → Workflow → Rule không? Có, hạ từ Agent xuống Workflow giúp hệ thống an toàn và kiểm soát được; đồng thời có sẵn tầng Rule (Quick Buttons) làm lưới bảo vệ cuối cùng.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Workflow cho phép kết hợp sức mạnh của các mô hình AI chuyên biệt (MediaPipe cho thị giác máy tính, LLM cho ngôn ngữ, Whisper cho âm thanh) theo một chuỗi bước được kiểm soát chặt chẽ. Hệ thống đảm bảo tính tất định cao, độ trễ thấp (< 3 giây) và luôn có con người kiểm duyệt (Human-in-the-loop) ở bước xác nhận trước khi phát âm thanh. Điều này mang lại sự an toàn và tin cậy tuyệt đối cho cả khách hàng lẫn nhân viên thu ngân.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Mức Rule đơn thuần (bảng nút bấm hay từ điển tra cứu) không thể tạo ra cuộc đối thoại tự nhiên, buộc người dùng phải tìm kiếm trong danh mục hàng chục nút bấm rất mất thời gian và hoàn toàn thất bại ở chiều người nghe nói tự do. Rule chỉ phù hợp để làm phương án dự phòng (fallback) khi mạng gặp sự cố.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người khiếm thính (sử dụng ngôn ngữ ký hiệu) và nhân viên thu ngân/phục vụ tại các quầy thanh toán dịch vụ bán lẻ (cửa hàng tiện lợi, quán ăn/cà phê, nhà thuốc). |
| **Workflow** | Khách tiếp cận quầy → Làm cử chỉ ký hiệu trước camera → AI nhận diện & hiển thị câu dự thảo trên màn hình → Khách bấm xác nhận → Loa phát âm thanh cho thu ngân → Thu ngân nói trả lời → AI chuyển thành chữ to cho khách đọc → Thanh toán hoàn tất. |
| **Bottleneck** | Bước gõ chữ/ghi chú thủ công qua lại trên điện thoại mất 2-3 phút, khiến giao tiếp bị đứt gãy, gây áp lực tâm lý cho người khiếm thính và làm ùn tắc hàng chờ tại quầy. |
| **Impact** | Tiết kiệm ~3 phút cho mỗi lượt giao dịch (giảm từ ~3.7 phút xuống ~25 giây); xóa bỏ sự mặc cảm của người khiếm thính; giảm 80% áp lực tắc quầy cho nhân viên thu ngân trong giờ cao điểm. |
| **Success Metric** | Thời gian hoàn tất lượt hỏi-đáp thanh toán < 30 giây; độ chính xác nhận diện cử chỉ và chuyển đổi giọng nói > 90%; tỷ lệ giao dịch thành công không cần chuyển sang gõ tay > 85%. |
| **Boundary** (làm / không làm) | **LÀM:** Nhận diện 10-15 cử chỉ mua sắm thiết yếu; sinh câu giao tiếp lịch sự theo ngữ cảnh quầy; chuyển đổi giọng nói ↔ văn bản hai chiều; hỗ trợ bảng phím tắt fallback 1 chạm.<br>**KHÔNG LÀM:** Không dịch toàn bộ từ điển ngôn ngữ ký hiệu đời sống tổng quát; không làm phiên dịch pháp lý/y tế chuyên sâu; không tự động gọi API tài khoản ngân hàng để trừ tiền. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp sau khi khách ra cử chỉ (bước 1) để dịch thành câu thoại trước khi thu ngân tiếp nhận; và can thiệp sau khi thu ngân nói (bước 5) để dịch thành văn bản trước khi khách xác nhận thanh toán. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow** — Vì kết hợp nhiều mô hình AI đa tầng (Vision + LLM + Speech) theo một quy trình kiểm soát chặt chẽ có con người duyệt, đảm bảo an toàn và không cần Agent tự trị. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI nhận diện sai cử chỉ hoặc sinh câu sai ý định thanh toán. Khách khiếm thính trực tiếp kiểm tra bằng mắt trên màn hình xác nhận trong 3 giây trước khi bấm nút cho phép phát loa. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Người khiếm thính ↔ Thu ngân tại quầy bán lẻ; luồng 5 bước hai chiều được định nghĩa chi tiết. |
| Baseline + metric đo được chưa? | **Yes** | Baseline 225 giây (~3.7 phút) giảm xuống kỳ vọng < 30 giây; đo bằng bấm giờ thực tế trên từng giao dịch. |
| Data/input đủ dùng chưa? | **Yes** | Dùng webcam/camera điện thoại thông thường; dataset MediaPipe Hand Landmarks có sẵn, kết hợp prompt ngữ cảnh quầy dịch vụ. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Có màn hình review boundary ngăn chặn phát âm thanh sai; có bảng phím tắt fallback ngay lập tức. |
| Có người review/owner không? | **Yes** | Khách khiếm thính là người kiểm duyệt nội dung trước khi phát âm thanh ra ngoài. |
| Có cách non-AI đơn giản hơn không? | **No** | Cách non-AI hiện tại (viết giấy, gõ phím ảo) chính là điểm nghẽn gây chậm chạp và khó khăn nhất. |

**Decision:**

```text
Go (với phạm vi Pilot tại quầy thanh toán cửa hàng tiện lợi)
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
1. Bài toán giải quyết nỗi đau thực tế sâu sắc và mang tính nhân văn cao, đã được kiểm chứng qua phỏng vấn người thật (thu ngân và người khiếm thính).
2. Điểm nghẽn và metric thời gian đo lường cực kỳ định lượng: giảm từ 225 giây xuống dưới 25 giây cho mỗi lượt giao dịch.
3. Kiến trúc kỹ thuật dạng Hybrid Workflow (MediaPipe + LLM + TTS/STT) hoàn toàn khả thi để xây dựng prototype chạy được ngay trong ngày lab.
4. Thiết kế human boundary và fallback tầng Rule đảm bảo an toàn tuyệt đối, loại trừ hoàn toàn rủi ro ảo giác AI trong giao dịch tiền tệ.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
1. Data & Thiết bị: 1 laptop có webcam và 1 micro gắn ngoài, đặt mô phỏng quầy thanh toán; tập cử chỉ gồm 8 cử chỉ cốt lõi (Chào hỏi, Hỏi giá, Chuyển khoản, Tiền mặt, Cảm ơn, Mang về, Cần túi, Lấy hóa đơn).
2. Chạy thử: Thực hiện 30 lượt giao dịch thử nghiệm với 10 tình huống mua hàng giả định giữa các thành viên và sinh viên tình nguyện.
3. Đo 3 số: (1) Thời gian trung bình 1 lượt giao dịch (mục tiêu < 30s), (2) Độ chính xác nhận diện từ khóa cử chỉ (mục tiêu > 90%), (3) Tỷ lệ phải bấm nút fallback chuyển sang phím tắt (mục tiêu < 15%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã quyết định Go)
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì nhóm đã quyết định Go)
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nếu trong quá trình thử nghiệm thực tế gặp điều kiện ánh sáng quá tối làm độ chính xác nhận diện cử chỉ của camera giảm xuống dưới 60%, hoặc độ trễ mạng khiến LLM phản hồi > 5 giây, hệ thống lập tức tự động chuyển giao diện sang màn hình "Bảng giao tiếp nhanh 1 chạm" (Rule-based Quick Communication Board) để khách và thu ngân chạm chọn biểu tượng mà không cần chờ AI.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do


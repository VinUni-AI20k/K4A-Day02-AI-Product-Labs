# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Thế Khang | 2A202602964 | Facilitator / Workflow Mapping                                |
| 2   | Đặng Quốc Hiệp   | 2A202602755 | Workflow / Process Analysis                                   |
| 3   | Nguyễn Khánh Sơn | 2A202602388 | Problem Owner / Solution Pitcher                              |
| 4   | Ngô Xuân Hoàng   | 2A202602597 | Research / Domain Expert                                      |
| 5   | Bùi Thị Thu Uyên | 2A202602613 | Quick Validation / Customer Evidence                          |
| 6   | Nguyễn Việt Dũng | 2A202602812 | Synthesis / Scoring & Quality Assurance                      |

**Candidate problem nhóm chọn (1 câu):**

Người tham gia cuộc họp dự án (Developer / PM / Sinh viên làm đồ án) mất 15–20 phút sau mỗi buổi họp 45–60 phút để tự nhớ lại nội dung và viết meeting notes thủ công, thường xuyên bỏ sót 20–30% quyết định kỹ thuật và action items quan trọng do thiếu ngữ cảnh dự án.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Ngô Xuân Hoàng | Hổng kiến thức nền tảng môn Toán lớp 12 nhưng không biết hổng ở chuyên đề nào, ôn thi lan man không cải thiện điểm | Học sinh lớp 12, phụ huynh, gia sư | Tốn 2-3 giờ tự đọc lại toàn bộ SGK mà không biết mình sai do hổng công thức lớp 11 hay lớp 12 | Vấn đề rất thật, ai cũng từng trải qua; workflow đánh giá và bù đắp lỗ hổng kiến thức rất rõ ràng. |
| 2 | Ngô Xuân Hoàng | Cảnh báo ngập lụt đô thị mùa mưa chậm trễ (trễ 45-60 phút) do phụ thuộc ít trạm đo xa, người dân không kịp né vùng ngập | Người đi xe máy / ô tô tại Hà Nội | Chờ nhân viên hiện trường tuần tra và xác minh thủ công điểm ngập mất 30-45 phút mới phát tin cảnh báo | Tác động xã hội cực lớn, nhưng lo ngại khó xin quyền truy cập luồng dữ liệu camera giao thông công cộng trong phạm vi lab. |
| 3 | Ngô Xuân Hoàng | Phát hiện ổ gà trên đường gây nguy hiểm, quy trình người dân dừng xe chụp ảnh báo cáo thủ công qua app mất 15-25 ngày mới được xử lý | Người tham gia giao thông xe máy, cơ quan quản lý đô thị | Báo cáo thủ công tốn thời gian, quy trình duyệt công văn qua các cấp hành chính rất chậm | Ý tưởng hay, giải quyết an toàn giao thông nhưng việc trám đường phụ thuộc vào ngân sách và quy trình nhà nước, AI chỉ giải quyết được khâu phát hiện. |
| 4 | Nguyễn Thế Khang | Xem lại video recording bài giảng (1.5 - 2h) để tóm tắt các công thức, thuật toán và lưu ý chính | Học viên lớp AI / lập trình | Bước tua nghe & chép tay thủ công mất 55 phút cho mỗi video 1.5h | Workflow rõ, lặp lại đều đặn mỗi tuần; băn khoăn cách AI nhận diện công thức toán và trích xuất hình ảnh bảng vẽ của giảng viên có đủ chuẩn xác. |
| 5 | Nguyễn Thế Khang | Chuyển đổi và tổng hợp kiến thức từ nhiều nguồn rời rạc (slide PDF, VLearn, thông báo Discord, tài liệu workshop) thành một bộ ghi chú ôn tập thống nhất | Học viên | Chắp nối thông tin đa nguồn ngốn 60–80 phút/ngày, dễ bỏ sót nội dung quan trọng | Workflow rõ ràng 5 bước, lặp lại hằng ngày; metric thời gian đo lường tốt (1.5–2h/ngày); cần kiểm tra quyền truy cập data tự động. |
| 6 | Nguyễn Thế Khang | Đọc và debug các lỗi traceback phức tạp trong bài tập lab lập trình AI (xung đột version thư viện, CUDA out-of-memory, tensor dimension mismatch) | Học viên lập trình AI | Đọc traceback & thử nghiệm fix thủ công tốn 1–2 tiếng mỗi lần gặp lỗi lạ | Pain point nặng nhất khi code AI; AI hiểu ngữ cảnh code tốt nhưng môi trường phần cứng mỗi máy khác nhau, dễ đưa ra giải pháp lệch môi trường local. |
| 7 | Bùi Thị Thu Uyên | Câu trả lời đã có trong Discord nhưng thành viên mới không tìm được, admin phải trả lời lặp lại cùng một nội dung | Thành viên mới & Admin cộng đồng / lớp học | Search từ khóa thất bại do không index ảnh/PDF/voice, tiếng Việt viết tắt/không dấu, trả lời bị chẻ vụn qua nhiều tin nhắn | Workflow rõ, bottleneck gọn ở 1 bước, số liệu đo được ngay (admin trả lời lặp 5–12 lần/tháng); cần làm rõ admin có thật sự thấy phiền không. |
| 8 | Bùi Thị Thu Uyên | Đi lại & chờ xe bus trong khi xe có thể trễ 10–20 phút mà không có ước lượng tại trạm | Sinh viên / người đi làm bằng xe bus tuyến cố định | Đứng chờ không có ước lượng đáng tin tại chỗ, không ra được quyết định chờ tiếp hay đi xe ôm; mất buffer phòng hờ 15–20 phút/lượt | Chi phí thật nằm ở buffer phòng hờ; nhưng nghi ngờ đây là bài toán dữ liệu GPS và hạ tầng giao thông chứ không phải bài toán AI. |
| 9 | Bùi Thị Thu Uyên | Sau mỗi lượt khám, nhân viên y tế phải tổng hợp thông tin từ nhiều trường dữ liệu thành nội dung dặn dò dễ hiểu cho bệnh nhân | Nhân viên y tế / điều dưỡng (mất 2–5h/ngày) | Gom dữ liệu từ 2–3 màn hình rồi diễn giải thuật ngữ y khoa sang lời thường; 15–30% bệnh nhân gọi lại hỏi | Rủi ro cao vì sai liều thuốc là sự cố y khoa, không phải bug phần mềm; rất khó xin dữ liệu bệnh án thật trong thời hạn buổi lab. |
| 10 | Đặng Quốc Hiệp | Tổng hợp lỗi sai lặp lại của từng học sinh để ngăn tình trạng hổng kiến thức kéo dài | Giáo viên / Gia sư (và Học sinh) | Bước tổng hợp lỗi sai cuối tháng trong workflow 5 bước (học sinh 3 tháng vẫn sai cùng dạng lỗi) | Hậu quả rõ ràng; phù hợp để so sánh Rule / Workflow / Agent (bảng ghi tay 2 phút/buổi đã giải quyết được phần lớn); danh mục lỗi còn mang tính định tính. |
| 11 | Đặng Quốc Hiệp | Soạn bài tập theo trình độ từng học sinh | Giáo viên / Gia sư | Bước chọn bài phù hợp với từng mức trình độ (tốn ~5 tiếng/tuần) | Tần suất cao, tốn thời gian; rủi ro lớn nếu đề sai đáp án làm giảm niềm tin; khó đo lường mức độ 'vừa sức' khách quan. |
| 12 | Đặng Quốc Hiệp | Tìm lại bài tập trong kho 150 file PDF/ảnh tài liệu | Giáo viên / Gia sư | Mất 8–12 phút/lần, 2–3 lần/tuần để tìm lại bài tập trong kho file PDF/ảnh | Dễ đo lường hiệu quả cụ thể; tuy nhiên giải pháp Non-AI (Rule đặt tên file) rất mạnh, impact hẹp (chỉ 1 actor), không nhất thiết cần AI. |
| 13 | Nguyễn Khánh Sơn | Soạn bài tập củng cố (30–40 câu) bám sát slide và ví dụ bài giảng trong ngày, tuần | Giáo viên THPT, Giảng viên đại học, Trợ giảng (TA) | Khâu sáng tác câu hỏi phân hóa bám ví dụ thực tế trên lớp và tự giải chi tiết từng bước để làm barem đáp án (mất 50–60'/buổi) | Tần suất lặp lại đều đặn. Ngữ cảnh khép kín trong slide bài giảng nên AI khó bịa thông tin; nhóm có thể lấy ngay slide môn học trên lớp để chạy pilot kiểm chứng được ngay. |
| 14 | Nguyễn Khánh Sơn | Biên tập bài review Affiliate từ trải nghiệm người dùng thực tế trên sàn TMĐT | Người làm Affiliate Marketing, Content Creator | Đọc thủ công 50–100 review của người mua trên sàn để nhặt lỗi thực tế và sửa văn mẫu sáo rỗng của ChatGPT (mất 40'/bài) | Giải quyết bức xúc của người làm content; tuy nhiên việc cào dữ liệu review Shopee/TikTok vướng kỹ thuật trong buổi lab, CTR cần nhiều tuần mới đo được. |
| 15 | Nguyễn Khánh Sơn | Gom biên bản họp và ghi chú rời rạc thành báo cáo đồ án chuẩn rubric | Nhóm trưởng sinh viên hoặc người tổng hợp bài nộp | Chắp vá văn phong lủng củng của 4 người thành bài liền mạch và soi từng tiêu chí rubric vào đêm muộn trước deadline 23:59 (ngốn 60–80') | Cả nhóm ai cũng từng trải qua; tuy nhiên 70% giải quyết bằng quy trình phân công và template Google Docs (No-AI), rubric mỗi môn một kiểu nên khó chuẩn hóa pipeline. |
| 16 | Nguyễn Việt Dũng | Viết weekly report tóm tắt progress nghiên cứu từ code repo, staging log, chat log | Researcher trong dự án công nghệ / AI | Prompt thủ công mất 4h/tuần để tổng hợp từ repo, staging, chat log thảo luận và milestone ra TODO tuần tới | Workflow có giá trị nhưng trùng lặp trực tiếp với case ví dụ mẫu trong tài liệu đề bài; dữ liệu phân tán nhiều hệ thống nội bộ staging/codebase khó demo trên lớp. |
| 17 | Nguyễn Việt Dũng | Tóm tắt meeting notes sau các cuộc họp dự án | Người tham gia meeting (User) | Sau mỗi meeting mất 10–15 phút nhớ lại nội dung để viết summary cá nhân; cần đủ project context để hiểu đúng | Workflow rõ và lặp lại; nhưng impact cá nhân nhỏ, cần kiểm chứng tần suất họp thực tế và mức độ bỏ sót ngoài 10–15 phút. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A: Giáo dục, Giảng dạy & Tự học | #1 (Toán 12), #4 (Tóm tắt video), #5 (Ghi chú đa nguồn), #10 (Lỗi sai lặp lại), #11 (Soạn bài theo trình độ), #12 (Kho bài tập PDF), #13 (Soạn bài tập bám slide) | Chuyển hóa học liệu thô (slide bài giảng, video ghi âm, kho bài tập) thành tài liệu giảng dạy và ôn tập có cấu trúc, kiểm tra độ hiểu bài của người học | Cụm có nhiều candidate nhất (7 bài), mức độ thấu hiểu domain của cả nhóm cao nhất vì toàn bộ thành viên đều đang là sinh viên/học viên hoặc từng làm gia sư, trợ giảng. |
| B: Tổng hợp Báo cáo & Ghi chép Tri thức | #9 (Dặn dò bệnh nhân), #15 (Báo cáo đồ án rubric), #16 (Weekly report researcher), #17 (Meeting note summary) | Thu thập các mẩu dữ liệu rời rạc từ nhiều stakeholder/hệ thống để tổng hợp thành văn bản chuẩn cho người nhận tiếp theo | Pain point rất phổ biến nhưng một số bài có thể giải quyết bằng Process/Template (No-AI), hoặc rủi ro pháp lý/y tế cao. |
| C: Tìm kiếm / Truy vấn Thông tin & Debug Kỹ thuật | #6 (Debug traceback AI), #7 (Discord FAQ search) | Người dùng bế tắc khi tìm câu trả lời đúng ngữ cảnh trong môi trường kỹ thuật số phức tạp | Cần khả năng hiểu ngữ cảnh cao (context-aware), nhưng dễ bị trôi sang bài toán kỹ thuật hạ tầng (indexing/semantic search). |
| D: Đô thị, Giao thông & Content Ngoại vi | #2 (Cảnh báo ngập lụt), #3 (Phát hiện ổ gà), #8 (Thời gian chờ xe bus), #14 (Review Affiliate TMĐT) | Tác động diện rộng ở ngoài thế giới thực hoặc nền tảng kinh doanh bên ngoài | Khó kiểm chứng trong buổi lab vì phụ thuộc dữ liệu công quyền (camera/GPS/sở GTVT) hoặc chính sách cào dữ liệu sàn TMĐT. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#17 — Tóm tắt Meeting notes và trích xuất Action items sau cuộc họp dự án** (Nguyễn Việt Dũng) | 1. **Tần suất cao & Pain point phổ biến**: Nhóm họp đồ án và dự án 3–5 buổi/tuần, mỗi buổi mất 15–20 phút tự hồi tưởng viết tóm tắt; 20–30% action item hoặc quyết định kỹ thuật bị quên lãng nếu không ghi chép ngay.<br>2. **Dễ kiểm chứng trong lab (Lab-ready 5/5)**: Nhóm có thể lấy ngay file ghi âm/transcript cuộc họp thảo luận Day 02 hôm nay để đưa vào chạy pilot kiểm chứng chất lượng và đo thời gian tức thì.<br>3. **Biên giới an toàn rõ ràng (Low Risk)**: AI chỉ draft tóm tắt và list việc cần làm; người họp chỉ mất 1–2 phút review và bổ sung trước khi gửi vào Slack/Discord. | Cần đảm bảo AI hiểu đúng ngữ cảnh dự án (project context, thuật ngữ công nghệ, tên thành viên) để không gắn nhầm người phụ trách (assignee) hoặc tóm tắt sai quyết định kiến trúc. |
| **#9 — Sau mỗi lượt khám, nhân viên y tế phải tổng hợp thông tin từ nhiều trường dữ liệu thành nội dung dặn dò dễ hiểu cho bệnh nhân** (Bùi Thị Thu Uyên) | 1. **Impact xã hội và giá trị thực tế cực lớn**: Giúp giảm tải áp lực cho nhân viên điều dưỡng (đang mất 2–5h/ngày) và giảm 15–30% cuộc gọi hỏi lại của bệnh nhân.<br>2. **Vấn đề nghẽn rất thật**: Phải chuyển hóa biệt dược, liều dùng và thuật ngữ chuyên môn phức tạp từ 2–3 màn hình bệnh án sang ngôn ngữ dễ hiểu cho người cao tuổi. | **Rủi ro y tế cực kỳ cao**: AI hallucination sai liều thuốc hoặc sai giờ uống là sự cố y khoa nghiêm trọng đe dọa tính mạng; không thể tiếp cận dữ liệu bệnh án thật trong buổi lab do luật bảo mật y tế. |
| **#13 — Soạn bài tập củng cố (30–40 câu) bám sát slide và ví dụ bài giảng** (Nguyễn Khánh Sơn) | 1. **Workflow và actor rõ ràng**: Trợ giảng (TA)/Giáo viên có quy trình hàng tuần, bottleneck khâu sáng tác câu hỏi phân hóa tốn 50–60'/buổi.<br>2. **Ngữ cảnh khép kín (Bounded Context)**: Gói gọn trong slide bài giảng, AI ít bịa thông tin.<br>3. **Đã có sẵn tư liệu**: Có slide bài học Day 01 & Day 02 để test prompt. | Giá trị tập trung hẹp vào một nhóm nhỏ người đi dạy (TA/giáo viên), trong khi meeting notes là nhu cầu dùng hàng ngày của tất cả các thành viên trong nhóm và các nhóm sinh viên khác. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#17 — Meeting note dự án (Nguyễn Việt Dũng)** | 5 | 5 | 4 | 5 | 5 | 5 | 5 | **34** |
| **#13 — Soạn bài tập củng cố bám slide (Nguyễn Khánh Sơn)** | 5 | 5 | 4 | 4 | 4 | 4 | 5 | **31** |
| **#9 — Dặn dò bệnh nhân sau khám (Bùi Thị Thu Uyên)** | 5 | 4 | 5 | 4 | 2 | 4 | 3 | **27** |

*Giải thích chấm điểm:*
- **Làm trong lab (5/5 vs 2/5)**: Bài #17 của Dũng đạt điểm tuyệt đối 5/5 vì nhóm có sẵn bản ghi âm/transcript cuộc họp Day 02 để test prompt, chạy thử pipeline trích xuất meeting note và đo thời gian ngay. Ngược lại, bài #9 của Uyên chỉ đạt 2/5 vì quy định bảo mật y tế không cho phép lấy dữ liệu bệnh án thật trong phòng lab.
- **Rủi ro sai sót (Safety & Feasibility)**: Bài #17 có rủi ro thấp, người họp duyệt nhanh trước khi post; nếu AI tóm tắt sót ý chỉ mất 1-2 phút bổ sung tay. Bài #9 nếu AI nhầm lẫn liều dùng thuốc thì hậu quả rất nghiêm trọng.
- **So sánh Rule / Workflow / Agent (5/5)**: Bài #17 phân định cực kỳ kinh điển: Rule = template ghi chú form mẫu; Workflow = pipeline Whisper STT -> trích xuất Key Decisions & Action Items theo template -> Người review -> Bot gửi Slack; Agent = tự phân tích context dự án, tự gọi API tra cứu Jira/Linear và tự giao task cho thành viên.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Người tham gia cuộc họp dự án (Developer / PM / Sinh viên làm đồ án) mất 15–20 phút sau mỗi buổi họp 45–60 phút để tự nhớ lại nội dung và viết meeting notes thủ công, thường xuyên bỏ sót 20–30% quyết định kỹ thuật và action items quan trọng do thiếu ngữ cảnh dự án.
```

**Vì sao chọn (4-5 câu):**

```text
Thứ nhất, bài toán có Actor (thành viên dự án, PM, Developer) và Workflow sau cuộc họp cực kỳ phổ biến với tần suất 3–5 buổi/tuần, diễn ra đều đặn trong bất kỳ nhóm làm đồ án hay doanh nghiệp công nghệ nào. 
Thứ hai, điểm nghẽn (bottleneck) rất rõ nét: sau cuộc họp kéo dài căng thẳng, người tham gia vừa mệt mỏi vừa phải tốn 15–20 phút lục lại trí nhớ để gõ tóm tắt, dẫn đến tình trạng viết qua loa, bỏ sót 20–30% quyết định kỹ thuật quan trọng và các đầu việc được giao. 
Thứ ba, tính khả thi trong buổi lab đạt mức tuyệt đối (5/5): nhóm có thể dùng ngay file ghi âm thảo luận Day 02 của chính nhóm mình để làm input, thực nghiệm pipeline AI trích xuất Decisions & Action Items và đo lường sự khác biệt về thời gian và độ chuẩn xác ngay lập tức. 
Thứ tư, bài toán có biên độ rủi ro rất thấp và ranh giới con người (Human Boundary) minh bạch: người họp chỉ mất 1–2 phút skim qua bản draft để bổ sung trước khi bấm gửi, không lo ngại các rủi ro pháp lý hay y tế nguy hiểm.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- #9 (Dặn dò bệnh nhân sau khám - Uyên): Dù có tác động xã hội lớn, nhưng rủi ro y tế quá cao (sai liều thuốc là sự cố y khoa nghiêm trọng); đồng thời nhóm không thể tiếp cận dữ liệu bệnh án thật của bệnh viện để thử nghiệm trong buổi học.
- #13 (Soạn bài tập củng cố bám slide - Sơn): Bài toán rất tốt về mặt ngữ cảnh khép kín, tuy nhiên phạm vi áp dụng hẹp (chỉ dành cho người đi dạy/TA), trong khi bài Meeting Note phục vụ trực tiếp cho toàn bộ 6 thành viên trong nhóm và mọi nhóm sinh viên khác.
- #5 (Tổng hợp kiến thức đa nguồn - Khang): Dữ liệu phân tán ở quá nhiều nền tảng (VLearn, Discord, video) đòi hỏi công đoạn export thủ công phức tạp, khó kiểm soát chất lượng đầu vào trong thời gian giới hạn của buổi lab.
- #1 (Hổng kiến thức Toán 12 - Hoàng): Cần xây dựng ontology và cây kiến thức Toán đồ sộ mới chẩn đoán được lỗ hổng, vượt quá quy mô của một buổi thực hành.
- #2, #3, #8 (Ngập lụt, Ổ gà, Xe bus): Phụ thuộc vào dữ liệu hạ tầng công cộng và cơ quan nhà nước, không có dữ liệu thực tế để pilot.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
- Ai lo gì: Bạn Uyên muốn giữ bài y tế (#9) vì tính nhân văn và mức độ bức xúc của điều dưỡng; bạn Sơn muốn ưu tiên bài soạn đề (#13) vì có slide sẵn ít bị hallucination. Một số thành viên cũng e ngại rằng Meeting Note đã có nhiều công cụ trên thị trường (như Otter, Teams AI, Zoom Summary).
- Chốt ra sao: Dũng và Khang phản biện rằng các công cụ hiện có chỉ tóm tắt chung chung (generic summary), không hiểu được ngữ cảnh dự án phần mềm chuyên sâu để nhặt đúng "Technical Decision" và gắn tag "@Assignee: Action Item" chuẩn xác cho từng thành viên. Về bài y tế, cả nhóm đồng thuận không mạo hiểm với dữ liệu y khoa do rào cản pháp lý và an toàn người bệnh. Về bài soạn đề, nhóm thấy Meeting Note gần gũi với công việc hàng ngày của cả 6 người hơn. Nhóm thống nhất 100% chọn bài Meeting Note của Dũng.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | | | | |
| Survey / poll | | | | # 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

> **Quy ước đánh dấu độ tin của số liệu trong bản này** (để người chấm và chính nhóm phân biệt được cái gì đo thật, cái gì mới là giả định):
>
> - `[ĐO]` — số do thành viên tự bấm giờ / đếm thật, có người chịu trách nhiệm về con số.
> - `[ƯỚC]` — số ước lượng từ trí nhớ của người trong cuộc, chưa bấm giờ.
> - `[CHƯA ĐO]` — chưa có baseline; nhóm ghi rõ sẽ đo bằng cách nào chứ không bịa số cho đẹp.
>
> Nhóm cố ý **không** trích bất kỳ số liệu thống kê nào từ AI hoặc từ trang marketing của tool nếu không mở được nguồn gốc. Phần research bên dưới chỉ mô tả **năng lực** của tool (kiểm được bằng trang sản phẩm chính thức), không trích con số kiểu "tiết kiệm x%".

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Thế Khang | 2A202602964 | Research — tìm tool/pattern đã có, kiểm link nguồn |
| 2   | Đặng Quốc Hiệp | 2A202602755 | Workflow + writer — vẽ before/after, chấp bút bản nộp nhóm |
| 3   | Nguyễn Khánh Sơn | 2A202602388 | Validation — thiết kế câu hỏi interview/poll, tổng hợp tín hiệu |
| 4   | Ngô Xuân Hoàng | 2A202602597 | Devil's advocate — ép nhóm trả lời "non-AI có đủ không", soi rủi ro |
| 5   | Bùi Thị Thu Uyên | 2A202602613 | Facilitator — điều phối pitch, giữ giờ, chốt đồng thuận khi lệch |
| 6   | Nguyễn Việt Dũng | 2A202602812 | Domain owner — người đang gặp chính bài toán được chọn, cung cấp baseline |

**Candidate problem nhóm chọn (1 câu):**

Sau mỗi meeting dự án, người **tham dự** (không phải người chủ trì) phải tự viết lại summary cho chính mình, mất 10–15 phút `[ƯỚC]` mà phần lớn thời gian là ngồi nhớ lại mạch cuộc họp và tra lại ngữ cảnh dự án (tên module, số liệu, quyết định cũ) để hiểu đúng điều vừa được bàn — nên note hay bị viết muộn, viết chung chung, và sót mất action item của chính mình.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

Nhóm 6 người: 4 người pitch 3 cards (Khang, Uyên, Hiệp, Sơn), Dũng pitch 2 → tổng **14 candidates**. Hoàng nhận vai challenge nên không pitch, tập trung hỏi ngược từng bài.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Khang | Xem lại video recording bài giảng (1.5–2h) để tóm tắt công thức, thuật toán, lưu ý chính | Học viên | Bước tua nghe & chép lại từ video | Workflow rõ, lặp đều mỗi tuần, metric thời gian đo tốt. Nghi ngờ: AI nhận diện công thức toán và trích ảnh bảng vẽ của giảng viên có đủ chuẩn xác không |
| 2 | Khang | Gộp kiến thức từ nhiều nguồn rời rạc (slide PDF, VLearn, Discord, tài liệu workshop) thành một bộ ghi chú ôn tập thống nhất | Học viên | Bước chắp nối thông tin đa nguồn | Workflow 5 bước rõ, lặp hằng ngày, metric 1.5–2h/ngày. Nghi ngờ: AI có truy cập được hết nguồn không hay phải export tay trước |
| 3 | Khang | Đọc & debug traceback phức tạp trong lab AI (xung đột version, CUDA OOM, tensor dimension mismatch) | Học viên | Bước đọc traceback và dựng giả thuyết lỗi | Pain nặng nhất khi code AI, 1–2h/lần. Nghi ngờ: mỗi máy một môi trường GPU/CUDA, AI dễ đưa giải pháp không tương thích |
| 4 | Uyên | #6 — Câu trả lời đã có trong Discord nhưng không tìm được | SV mới không biết đặt đúng từ khoá; admin phải trả lời lặp 5–12 lần/tháng | Search từ khoá thất bại → phải cuộn tay | 4 nguyên nhân đã tách rõ: (1) không index nội dung ảnh/PDF/voice — nơi chứa phần lớn câu trả lời; (2) tiếng Việt có dấu ≠ không dấu ≠ viết tắt; (3) một câu trả lời bị chẻ ra 5–10 message của 3 người nên tìm ra 1 mảnh vẫn thiếu ngữ cảnh; (4) message hữu ích bị spam/chat vặt đẩy chìm. Cần làm rõ: admin có thật sự thấy phiền không |
| 5 | Uyên | #7 — Đi lại & chờ xe bus trong khi xe có thể lỡ 10–20 phút | SV/NLĐ đi tuyến cố định, khung giờ cố định, có ràng buộc giờ vào lớp/ca làm | Bước 3–4: không có ước lượng đáng tin ngay lúc đang đứng chờ → không quyết được "chờ tiếp hay bỏ sang xe ôm" | Chi phí thật không nằm ở phút chờ mà ở buffer phòng hờ 15–20 phút/lượt mà người dùng tự cộng vào mỗi ngày. Nghi ngờ mạnh: đây là bài toán dữ liệu GPS thời gian thực chứ chưa chắc là bài toán AI |
| 6 | Uyên | #8 — Sau mỗi lượt khám, nhân viên phải tổng hợp thông tin từ nhiều trường dữ liệu thành nội dung dễ hiểu cho bệnh nhân | Nhân viên y tế / điều dưỡng (mất 2–5h/ngày); bệnh nhân chưa hiểu nên 15–30% gọi lại hỏi đúng nội dung đã dặn | Gom dữ liệu từ 2–3 màn hình rồi diễn giải thuật ngữ y khoa sang lời thường | Impact lớn nhất cả nhóm. Nhưng rủi ro cao: sai liều là sự cố y khoa, không phải bug. Và không tự lấy được dữ liệu thật trong thời hạn — phải xin phòng khám |
| 7 | Hiệp | #2 — Tổng hợp lỗi sai lặp lại của từng học sinh | Giáo viên / gia sư (và học sinh) | Nghẽn ở bước tổng hợp lỗi sai cuối tháng trong workflow 5 bước; gốc rễ là không có bước lưu lỗi ngay sau khi chấm | Hậu quả rõ ràng (học sinh 3 tháng vẫn sai cùng dạng lỗi). Phù hợp để so sánh Rule/Workflow/Agent vì bảng ghi tay 2 phút/buổi đã giải được phần lớn. Chưa có baseline theo dõi thực tế, danh mục dạng lỗi còn mang tính định tính |
| 8 | Hiệp | #1 — Soạn bài theo trình độ từng em | Giáo viên / gia sư | Bottleneck rõ ở bước chọn bài phù hợp với từng mức trình độ (~5 tiếng/tuần) | Tần suất cao và tốn thời gian nhất. Rủi ro lớn nếu đề sai đáp án làm giảm niềm tin của học sinh/phụ huynh. Khó đo mức độ "vừa sức" khách quan; giá trị có thể đến từ việc tag lại kho đề hơn là từ AI |
| 9 | Hiệp | #5 — Tìm lại bài tập trong kho 150 file PDF/ảnh | Giáo viên / gia sư (bản thân người quản lý kho) | Mất 8–12 phút/lần, 2–3 lần/tuần | Dễ đo lường hiệu quả cụ thể. Giải pháp non-AI (Rule/đặt tên file) rất mạnh, minh hoạ tốt việc Rule không kém AI. Impact hẹp (chỉ 1 actor), có thể chỉ là vấn đề quản lý/đặt tên file (process fix) |
| 10 | Sơn | Soạn bài tập củng cố (30–40 câu/đề) bám sát slide và ví dụ bài giảng trong ngày, tuần | GV THPT, giảng viên đại học, trợ giảng (TA) | Khâu sáng tác câu hỏi phân hoá bám ví dụ thực tế trên lớp và tự giải chi tiết từng bước để làm barem đáp án (50–60'/buổi) | Tần suất lặp lại đều đặn. Ngữ cảnh khép kín trong slide bài giảng nên AI khó bịa thông tin; nhóm có thể lấy ngay slide môn học để chạy pilot kiểm chứng |
| 11 | Sơn | Biên tập bài review affiliate từ trải nghiệm người dùng thực tế | Người làm affiliate marketing cá nhân, content creator review sản phẩm | Khâu đọc thủ công 50–100 review của người mua trên sàn để nhặt lỗi thực tế và sửa lại bài văn mẫu sáo rỗng của ChatGPT (40'/bài) | Đúng bức xúc của người làm content hiện nay (bài AI bị một màu, người xem lướt qua). Nhưng cào dữ liệu review Shopee/TikTok có thể vướng kỹ thuật trong buổi lab ngắn, và chỉ số CTR cần nhiều tuần mới đo được |
| 12 | Sơn | Gom biên bản họp và ghi chú rời rạc thành báo cáo đồ án chuẩn rubric | Nhóm trưởng sinh viên / người tổng hợp bài nộp đồ án | Khâu chắp vá văn phong của 4 người thành bài liền mạch và soi từng tiêu chí rubric vào đêm muộn trước deadline (60–80') | Cả nhóm ai cũng từng nếm trải mỗi tuần. Nhưng ~70% giải được bằng quy trình phân công + template Google Docs (No-AI), chưa kể rubric mỗi môn một kiểu nên khó làm pipeline chuẩn |
| 13 | Dũng | Viết weekly report | Researcher | Gom work done từ code repo + kết quả thực nghiệm từ hệ thống staging + chat log thảo luận, rồi dựa trên milestone hiện tại đưa ra TODO tuần tới; hiện prompt thủ công mất 4h/tuần | Impact thời gian lớn nhất trong nhóm. Nhưng scope rộng (3–4 hệ thống nguồn), và trùng gần hết với ví dụ mẫu trong `02-deliverable-example.md` nên nhóm tránh |
| 14 | Dũng | Meeting note | Người tham dự meeting (không phải người chủ trì) | Sau mỗi meeting, người họp mất 10–15 phút tự nhớ lại nội dung để viết summary cho bản thân; note cần đủ project knowledge để hiểu đúng điều đã thảo luận | Workflow rõ và lặp lại. Cần kiểm chứng tần suất meeting, mức độ bỏ sót, và tác động **ngoài** 10–15 phút — nhóm nghi phần ngoài mới là phần đắt |

### 3.2. Gom trùng / cluster (gom 14 ý thành 4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A. Gom nhiều nguồn rời rạc → viết lại thành văn bản cho người đọc** | #1 tóm tắt video bài giảng, #2 ghi chú đa nguồn, #6 dặn dò bệnh nhân, #12 báo cáo đồ án, #13 weekly report, #14 meeting note | Input rải rác (video, PDF, chat, nhiều màn hình phần mềm) → output là một đoạn văn phải **người khác hoặc chính mình sau này đọc là hiểu**. Nghẽn luôn nằm ở bước biến dữ liệu thô thành câu có nghĩa | Cụm đông nhất: 6/14. Cũng là cụm AI ngôn ngữ mạnh nhất — nên phải cẩn thận không chọn bài chỉ vì "AI làm được" |
| **B. Truy xuất lại thông tin đã có trong một kho lộn xộn** | #4 Discord search, #9 kho 150 file PDF/ảnh | Thông tin **đã tồn tại**, chỉ là không tìm ra. Nghẽn ở bước tìm, không ở bước tạo | Cả hai đều có non-AI mạnh (index, quy ước đặt tên) → tốt để đối chiếu Rule vs AI, nhưng impact hẹp hoặc phụ thuộc quyền truy cập dữ liệu |
| **C. Sinh / chọn nội dung dạy-học cá nhân hoá** | #7 tổng hợp lỗi sai học sinh, #8 soạn bài theo trình độ, #10 soạn bài tập củng cố | Phải ra output **khác nhau cho từng người học**, và sai thì hậu quả rơi vào người học | Đo "vừa sức / đúng trọng tâm" một cách khách quan là chỗ khó chung của cả cụm |
| **D. Không cùng pattern với ba cụm trên** | #3 debug traceback, #5 chờ xe bus, #11 review affiliate | Mỗi bài một bản chất khác: chẩn đoán kỹ thuật phụ thuộc môi trường máy / dự đoán thời gian thực từ dữ liệu GPS / sản xuất nội dung marketing đo bằng CTR | Giữ làm tham chiếu, không đưa vào shortlist: #5 không phải bài toán AI, #3 phụ thuộc môi trường từng máy, #11 vướng crawl + metric dài hạn |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

Nhóm chốt **2 bài mạnh nhất**, giữ thêm 1 bài dự phòng phòng khi bài chính vỡ lúc validate.

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#14 — Meeting note (Dũng)** | (1) Người gặp vấn đề ngồi ngay trong nhóm → hỏi baseline trực tiếp, không đoán hộ actor vắng mặt. (2) Workflow ngắn, tuyến tính, vẽ trọn được cả before/after trong 45 phút Phase 5. (3) So sánh Rule/Workflow/Agent rất rõ vì có sẵn cả template giấy (Rule) lẫn hàng chục tool thương mại (Workflow/Agent) để đối chiếu | Actor ban đầu ghi là "User" — quá mơ hồ, phải thu hẹp. Baseline 10–15' mới là ước lượng, chưa bấm giờ. Nghi ngờ lớn nhất: 10–15'/lần có đủ đau để làm không, hay pain thật nằm ở chỗ khác (sót action item, note đọc lại không hiểu) |
| **#6 — Dặn dò bệnh nhân sau khám (Uyên)** | (1) Impact lớn và cụ thể nhất: 2–5h/ngày của điều dưỡng và 15–30% bệnh nhân gọi lại. (2) Có người chịu hậu quả rõ ràng ở cả hai đầu (nhân viên y tế và bệnh nhân). (3) Bottleneck gọn: gom 2–3 màn hình rồi dịch thuật ngữ y khoa sang lời thường | Không lấy được dữ liệu thật trong thời hạn lab — phải xin phòng khám, kèm vấn đề dữ liệu cá nhân bệnh nhân. Sai liều là **sự cố y khoa**, không rollback được. Không ai trong nhóm làm ngành y → không đủ năng lực tự thẩm định output đúng/sai |
| *(dự phòng)* **#10 — Soạn bài tập củng cố bám slide (Sơn)** | Ngữ cảnh khép kín trong slide nên AI ít đất bịa; lấy được slide môn học chạy pilot ngay trong buổi lab | Trùng cụm C với 2 card của Hiệp → nhóm bị lặp góc nhìn. Barem đáp án sai thì lan tới cả lớp học sinh, cần người thật giải lại toàn bộ nên phần tiết kiệm bị ăn mòn |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#14 Meeting note** | 4 | 5 | 4 | 4 | 5 | 5 | 5 | **32** |
| #6 Dặn dò bệnh nhân sau khám | 5 | 4 | 3 | 5 | 1 | 4 | 2 | **24** |
| #10 Soạn bài tập củng cố | 4 | 4 | 4 | 3 | 4 | 4 | 4 | **27** |

Giải thích các điểm cực trị (worksheet yêu cầu nói rõ vì sao cho 5 / cho 3):

- **#14, "Làm trong lab" = 5:** nhóm chạy pilot được ngay bằng transcript của chính buổi họp nhóm hôm nay, không phải xin dữ liệu của ai.
- **#14, "Actor rõ" = 4 chứ không phải 5:** bản pitch ghi actor là "User". Nhóm phải tự thu hẹp thành "người tham dự meeting dự án, không phải người chủ trì, có nhiệm vụ mang thông tin về cho công việc của chính mình". Trừ 1 điểm để nhớ đây là chỗ nhóm đã phải sửa.
- **#6, "Làm trong lab" = 1:** không có đường nào lấy được dữ liệu thật trong 4 tiếng. Nếu tự bịa dữ liệu bệnh nhân để demo thì bài nộp đang đo một thứ không tồn tại.
- **#6, "Nhóm hiểu domain" = 2:** không ai trong nhóm làm y tế. Với bài này, không hiểu domain không chỉ làm bài chậm hơn — nó khiến nhóm **không có khả năng phát hiện output sai**, mà đó lại đúng là rủi ro chết người của bài toán.
- **#6, "Pain có evidence" = 3:** con số 2–5h/ngày và 15–30% gọi lại là do Uyên thuật lại; nhóm chưa mở được log hay nguồn chính thức nào để kiểm chéo.
- **#10, "Impact đo được" = 3:** đo được thời gian soạn đề, nhưng thứ đáng đo hơn là "đề có bám đúng bài giảng không" thì chưa có cách chấm khách quan.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#14 — Meeting note: người tham dự meeting dự án phải tự viết summary cho chính mình
sau mỗi buổi, và note phải mang đủ project knowledge thì đọc lại mới hiểu đúng.
```

**Vì sao chọn (4-5 câu):**

```text
Thứ nhất, người gặp vấn đề ngồi ngay trong nhóm (Dũng), nên mọi con số baseline đều hỏi
được trực tiếp và kiểm chéo được, thay vì nhóm đoán hộ một actor vắng mặt.

Thứ hai, workflow ngắn và tuyến tính (6 bước, dưới 15 phút), nên trong 45 phút của Phase 5
nhóm vẽ trọn được cả before lẫn after kèm thời gian từng bước, chứ không phải vẽ nửa vời.

Thứ ba, đây là bài hiếm hoi mà cả ba mức Rule / Workflow / Agent đều có phương án thật để
so: Rule là template 4 mục + 5 phút cuối buổi họp; Workflow là transcript → AI draft →
người review; Agent là bot tự vào phòng họp, tự tra Jira và tự tạo task. Nhờ vậy phần so
sánh của nhóm dựa trên phương án cụ thể chứ không phải lý thuyết.

Thứ tư, rủi ro khi AI sai ở mức chịu được: note này là bản nháp cho chính người dự họp,
sai thì người đó phát hiện ngay lúc đọc lại, không có ai ở hạ nguồn bị hại.

Thứ năm, nhóm chọn bài này dù biết nó "kém sexy" hơn bài y tế, vì tiêu chí của Day 02 là
hiểu đúng bài toán và chứng minh được kết luận, không phải chọn bài nghe to nhất.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#6 Dặn dò bệnh nhân (bài mạnh thứ hai, nhóm tiếc nhất):
Impact cao nhất, nhưng đây là bài toán mà sai một liều thuốc là sự cố y khoa chứ không
phải bug rollback được, trong khi không ai trong nhóm đủ chuyên môn để phát hiện output
sai. Cộng thêm việc không lấy được dữ liệu thật trong thời hạn lab (phải xin phòng khám,
lại vướng dữ liệu cá nhân của bệnh nhân), nhóm sẽ buộc phải demo trên dữ liệu tự bịa —
tức là đo một thứ không tồn tại. Nhóm đánh giá kết luận đúng của bài này hiện là "Not Yet",
nên chọn nó làm bài chính sẽ khiến cả Phase 5 và Phase 6 chạy trên giả định.

#10 Soạn bài tập củng cố:
Bài tốt, chạy pilot được ngay bằng slide môn học, nhưng nằm cùng cụm C với hai card của
Hiệp nên nhóm sẽ lặp lại một góc nhìn đã có. Ngoài ra giá trị tiết kiệm bị ăn mòn vì barem
đáp án vẫn phải do người thật giải lại toàn bộ.

#13 Weekly report:
Impact thời gian lớn nhất (4h/tuần) nhưng trùng gần như hoàn toàn với ví dụ mẫu trong
02-deliverable-example.md, làm sẽ thành chép lại lời giải có sẵn. Scope cũng rộng hơn hẳn
(3-4 hệ thống nguồn) so với quỹ thời gian còn lại của lab.

#4 Discord search và #9 kho 150 file PDF/ảnh:
Cả hai có non-AI quá mạnh (index + quy ước đặt tên), nhóm dự đoán kết luận sẽ là "Rule là
đủ" — đúng, nhưng sẽ làm phần so sánh Workflow/Agent trở nên hình thức.

#5 Chờ xe bus:
Chính người đưa ra đã nghi đây là bài toán dữ liệu GPS thời gian thực chứ không phải bài
toán AI. Nhóm đồng ý và loại sớm.

#3 Debug traceback và #11 review affiliate:
#3 phụ thuộc môi trường GPU/CUDA của từng máy nên không có "đáp án đúng" chung để đo;
#11 vướng crawl dữ liệu sàn và metric CTR cần nhiều tuần, không đo được trong phạm vi lab.

#1, #2, #12:
Cùng cụm A với bài được chọn và đều yếu hơn ở một điểm — #1 phụ thuộc chất lượng nhận diện
công thức toán và ảnh bảng vẽ, #2 vướng quyền truy cập VLearn/Discord, #12 tự nhận 70%
giải được bằng phân công + template.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Uyên bảo vệ #6 tới cùng, lập luận: bài có impact xã hội thật, bỏ đi thì nhóm đang chọn bài
dễ. Hoàng phản biện bằng một câu hỏi cụ thể: "trong 4 tiếng còn lại, ai trong nhóm đọc được
một đơn thuốc và nói được nó đúng hay sai?" — không ai giơ tay.

Nhóm chốt bằng cách tách hai thứ đang bị gộp làm một: mức độ đáng giải của bài toán (#6 cao
hơn) và mức độ nhóm chứng minh được điều gì trong buổi lab này (#14 cao hơn hẳn). Bài học
được ghi vào biên bản: bỏ #6 không có nghĩa #6 không đáng làm, mà là nó cần điều kiện nhóm
chưa có — dữ liệu thật và người thẩm định chuyên môn.

Dũng cũng tự nêu lo ngại ngược lại về chính bài của mình: 10-15 phút/lần có thể chưa đủ đau
để đáng làm. Nhóm không gạt đi mà biến nó thành câu hỏi số 1 phải trả lời ở Phase 4: tác
động thật nằm NGOÀI 10-15 phút đó là gì? Nhóm thống nhất trước: nếu Phase 4 không tìm ra
tác động nào ngoài thời gian, quyết định cuối sẽ hạ xuống "Not Yet".
```

---

## Phase 4 — Quick Validation + Research

> **Trạng thái dữ liệu phần 4.1:** các con số và quote dưới đây đến từ (a) 1 buổi hỏi nhanh trong nhóm và (b) poll nhanh trong lớp K4A/Discord tại buổi lab. Ô nào nhóm **chưa** có bằng chứng cứng thì ghi `[CHƯA ĐO]` kèm cách sẽ đo, không điền số cho đủ chỗ. Trước khi nộp bản cuối, các ô `⟨…⟩` phải được thay bằng quote nguyên văn có thật.

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview sâu | 3 người: 1 researcher (Dũng, chính chủ), 1 SV đi thực tập có daily/weekly meeting, 1 nhóm trưởng đồ án | 3/3 xác nhận có tự viết note riêng cho mình sau họp, tách biệt với biên bản chính thức của buổi họp. Dũng: ⟨"note của mình là để tuần sau mở ra biết tuần này đã chốt gì, không phải để gửi cho ai"⟩. Người thứ 2: ⟨"họp xong là quay lại code luôn, tối mới ngồi viết lại, lúc đó quên mất một nửa"⟩. Người thứ 3: ⟨"cái mình sợ không phải quên nội dung, mà quên mất phần việc của chính mình"⟩ | 1/3 nói với meeting ngắn dưới 20 phút thì không cần note gì, nhớ là đủ | Thu hẹp actor: chỉ tính meeting dự án ≥ 30 phút, có nhiều hơn 2 người, có bàn quyết định kỹ thuật. Bỏ khỏi phạm vi: standup ngắn, họp 1-1 xã giao |
| Survey / poll nhanh trong lớp | Poll Discord lớp K4A, mẫu mục tiêu 8–12 người `[CHƯA ĐO — chạy trong giờ lab, chốt số trước khi nộp]` | Câu hỏi poll đã soạn sẵn: (1) tuần bạn có mấy meeting ≥30'? (2) bạn có tự viết note riêng không? (3) mất bao lâu? (4) đã từng quên một việc đã nhận trong họp chưa? (5) mức đáng giải 1–5? | — | Kết quả poll dùng để quyết định đúng một việc: nếu **tần suất trung vị < 2 meeting/tuần** thì impact quá nhỏ và nhóm hạ quyết định xuống Not Yet |
| Log / ticket / review | Lịch Google Calendar 4 tuần gần nhất của Dũng `[ĐO — đếm được ngay, không cần trí nhớ]` | Đếm số buổi có ≥2 người và kéo dài ≥30 phút → ra tần suất meeting thật. Đây là nguồn đáng tin nhất nhóm có vì không phụ thuộc trí nhớ ai cả | Nếu lịch cho thấy < 2 buổi/tuần thì con số 40–60'/tuần sụp | Nhóm dùng chính con số này làm baseline tần suất trong Problem Statement, thay cho ước lượng miệng |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật KHÔNG phải là 10-15 phút gõ chữ. Pain thật có hai lớp: (1) người dự họp phải tự
tái dựng ngữ cảnh dự án trong đầu — nhớ module nào, số liệu nào, quyết định tuần trước là
gì — vì bản thu âm hay biên bản chung không mang theo phần kiến thức nền đó; và (2) hậu quả
đắt nhất không nằm trong 10-15 phút ấy mà nằm ở tuần sau: action item của chính mình bị rơi,
hoặc mở note cũ ra đọc mà không hiểu mình đã ghi gì.

Đây chính là câu trả lời cho nghi ngờ nhóm nêu ở Phase 3 ("tác động ngoài 10-15 phút là
gì"). Vì có câu trả lời này, nhóm mới giữ quyết định Go; nếu không có, nhóm đã hạ Not Yet
đúng như đã cam kết trước.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-poll.png` (ảnh chụp kết quả poll), `02-group-problem-statement-interview-notes.md` (3 bản ghi interview).

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

> Nhóm chỉ ghi **năng lực kiểm được trên trang chính thức**, không trích số liệu hiệu quả do nhà cung cấp tự công bố.

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Otter.ai | https://otter.ai/ | Bước 1–2: ghi âm, chuyển giọng nói thành transcript, tóm tắt tự động | Xử lý rất tốt phần "nghe và gõ lại" — đúng phần máy làm hơn người | Tóm tắt là tóm tắt chung cho cả buổi họp, không biết **người đọc là ai** và cũng không biết ngữ cảnh riêng của dự án | Bước transcribe coi như đã giải quyết xong, nhóm không build lại. Giá trị còn lại nằm ở việc bơm project knowledge vào và cá nhân hoá theo người dự |
| Fireflies.ai | https://fireflies.ai/ | Bước 1–3: transcript + tự trích action item + tìm kiếm trong kho meeting cũ | Có khái niệm action item như một đối tượng riêng, không chỉ là đoạn văn | Action item trích ra là của **cả buổi họp**, người dùng vẫn phải tự lọc cái nào là việc của mình | Template output của nhóm phải tách riêng mục "action item CỦA TÔI" thay vì liệt kê hết rồi bắt người đọc tự lọc |
| Granola | https://www.granola.ai/ | Bước 2–4: người vẫn tự gõ ghi chú thô trong lúc họp, AI nở ghi chú đó ra thành note hoàn chỉnh sau khi họp xong | Pattern rất đáng học: **giữ người ở trong vòng lặp ngay từ lúc họp**, AI chỉ khuếch đại cái người đã ghi | Phụ thuộc việc người dùng có chịu gõ vài dòng trong lúc họp hay không | Đây là pattern nhóm chọn làm hình mẫu: AI không thay người nghe họp, AI bồi đắp cho phần người đã bắt được |
| Microsoft Teams Premium — intelligent recap | https://www.microsoft.com/en-us/microsoft-teams/premium | Bước 1–4 trọn gói trong hệ sinh thái Teams: recap, chương mục theo thời gian, gợi ý việc cần làm | Truy cập được ngữ cảnh tổ chức (lịch, người tham dự, file đính kèm) — đúng thứ mà công cụ ngoài không có | Chỉ chạy được nếu cả tổ chức dùng Teams có license; không dùng được cho họp offline hoặc nhóm dùng Discord/Zoom lẫn lộn | Xác nhận giả thuyết cốt lõi của nhóm: giá trị đến từ **ngữ cảnh tổ chức**, không đến từ mô hình ngôn ngữ mạnh hơn |
| OpenAI Whisper (open source) | https://github.com/openai/whisper | Chỉ bước 1: transcript, chạy được offline trên máy | Miễn phí, chạy local nên dữ liệu họp không rời máy — quan trọng với meeting có nội dung nhạy cảm | Không làm gì ngoài transcript; chất lượng tiếng Việt lẫn thuật ngữ kỹ thuật tiếng Anh cần tự kiểm | Phương án dự phòng cho ràng buộc bảo mật: nếu không được đưa nội dung họp lên dịch vụ ngoài thì vẫn có đường đi |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
KHÔNG build: phần ghi âm và chuyển giọng nói thành transcript. Thị trường đã giải xong,
build lại là lãng phí cả buổi lab.

NÊN build: đúng một mẩu mà không tool nào trong 5 tool trên làm được — bơm PROJECT
KNOWLEDGE (glossary tên module, tên viết tắt, danh sách người, milestone đang chạy) vào
bước tóm tắt, và xuất ra theo template cố định 4 mục trong đó có mục "action item của
riêng tôi". Nói cách khác, phần thiếu không phải mô hình mạnh hơn mà là ngữ cảnh đúng.

Pattern đáng copy: Granola — AI không thay người nghe họp, AI nở rộng cái người đã bắt
được. Pattern này giữ nguyên trách nhiệm ở người, đúng với boundary nhóm muốn.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.md` (bản ASCII dưới đây là bản chính thức của nhóm)

```text
CURRENT STATE — 6 bước, 10-15 phút/meeting  [ƯỚC, chờ bấm giờ 5 buổi để chốt]

[1 Họp xong, mở file note nháp: 1']
→ [2 Ngồi nhớ lại mạch buổi họp, ai nói gì, chốt gì: 3-4']       <-- bottleneck (nhớ)
→ [3 Mở Jira/Notion/repo/chat tra lại ngữ cảnh dự án: 3-5']      <-- BOTTLENECK CHÍNH
→ [4 Viết summary + quyết định + TODO cho bản thân: 4-5']
→ [5 Hỏi lại đồng đội xem có sót gì không: 2' (1-2 lần/tuần)]
→ [6 Lưu vào Notion/Obsidian: 1']

Tần suất: 3-4 meeting/tuần  [ĐO bằng Google Calendar 4 tuần gần nhất]
Quy ra tuần: 40-60 phút/tuần cho riêng việc viết lại note của chính mình.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Người dự họp | Buổi họp vừa kết thúc | File note trống mở sẵn | 1' × 3-4 lần/tuần | Không nghẽn |
| 2 | Người dự họp | Trí nhớ ngắn hạn về buổi họp | Dàn ý thô trong đầu | 3-4' | **Nghẽn 1.** Phụ thuộc hoàn toàn vào trí nhớ; càng để lâu sau buổi họp càng mất. Người dự họp thường quay lại công việc ngay nên hay viết note vào buổi tối |
| 3 | Người dự họp | Jira/Notion, repo, chat log, biên bản cũ | Ngữ cảnh đủ để hiểu đúng điều vừa bàn | 3-5' | **NGHẼN CHÍNH.** Handoff ngầm: thông tin nằm rải ở 3-4 hệ thống do người khác nắm. Đây là bước duy nhất không thể rút ngắn bằng cách "cố nhớ kỹ hơn" |
| 4 | Người dự họp | Dàn ý + ngữ cảnh vừa tra | Summary + quyết định + TODO cá nhân | 4-5' | Bước tốn thời gian thứ hai, nhưng là tốn "chính đáng" vì đây là lúc suy nghĩ thật |
| 5 | Người dự họp → đồng đội | Chỗ nhớ không chắc | Xác nhận / bổ sung | 2' × 1-2 lần/tuần | **Handoff thật.** Tốn thời gian của cả người thứ hai, và không phải lúc nào cũng được trả lời ngay |
| 6 | Người dự họp | Note đã viết | Note lưu trong Notion/Obsidian | 1' | Không nghẽn |
| 7 | *(hệ quả, không nằm trong buổi viết note)* | Người dự họp | Note thiếu ngữ cảnh | Việc bị rơi / phải hỏi lại / đọc note cũ không hiểu | 1-2 lần/tuần `[CHƯA ĐO — đếm 2 tuần]` | Đây mới là chi phí đắt nhất, và nó **không** nằm trong 10-15 phút |

**Bottleneck chính (2-3 câu):**

```text
Bước 3 — tra lại ngữ cảnh dự án — là nghẽn chính, và nó là nghẽn thật chứ không phải chỉ
là bước chậm: hai bước trước nó (nhớ lại) và sau nó (viết) đều BỊ CHẶN vì thiếu ngữ cảnh
chứ không phải vì người viết gõ chậm. Bằng chứng là cùng một buổi họp, nếu người dự đã
nắm chắc dự án thì viết note mất 5 phút, còn nếu vừa nhận việc thì mất 15 phút cho đúng
buổi họp đó.

Gốc rễ: bản ghi âm và transcript mang được LỜI NÓI nhưng không mang được KIẾN THỨC NỀN của
dự án. Khi trong họp có người nói "cái pipeline v2 đang fail ở bước collate", transcript
ghi đúng từng chữ nhưng vô nghĩa với người đọc lại sau 1 tuần.

Bước 5 (hỏi lại đồng đội) là bằng chứng gián tiếp cho nghẽn này: nó chỉ tồn tại vì bước 3
làm chưa tới, và nó lây chi phí sang người thứ hai.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — 5 bước, 5-6 phút/meeting (mục tiêu)

[1 Ghi âm + auto transcript: 0' người - MÁY]
    Tool có sẵn (Otter/Fireflies/Whisper local). Người chỉ bấm nút.
    Điều kiện bắt buộc: đã xin phép tất cả người trong phòng họp.

→ [2 Nạp gói ngữ cảnh vào prompt: 0.5' - RULE]
    File glossary.md do team duy trì: tên module, từ viết tắt, tên người + vai trò,
    milestone đang chạy, 3 quyết định gần nhất. Đây là bước KHÔNG cần AI, chỉ là ghép
    file — nhưng đúng nó mới là bước giải bottleneck.

→ [3 AI draft theo template 4 mục cố định: 1' - AI]
    (a) Quyết định đã chốt   (b) Câu hỏi còn mở
    (c) ACTION ITEM CỦA TÔI  (d) Thuật ngữ/số liệu được nhắc + nghĩa trong dự án
    Bắt buộc: mỗi dòng phải trích được câu gốc trong transcript.

→ [4 Người dự họp review & sửa: 3-4' - NGƯỜI]        <-- HUMAN BOUNDARY
    Việc bắt buộc làm, không được bỏ: xác nhận mục (c) đúng là việc của mình,
    và sửa tên module/số liệu AI ghi sai.

→ [5 Lưu vào Notion/Obsidian: 0.5' - MÁY]

FALLBACK khi AI sai hoặc không dùng được:
- Họp offline/ồn, không ghi âm được → người viết tay theo đúng template 4 mục ở bước 3.
  Template là tài sản non-AI, dùng được kể cả khi không có AI. Mất ~8', vẫn tốt hơn 12'.
- AI bịa một quyết định không có trong transcript → bỏ toàn bộ draft buổi đó, viết tay,
  và ghi 1 dòng vào log lỗi. Quá 1 lần bịa trong 2 tuần → dừng pilot (xem mục Exit).
- Meeting có nội dung nhạy cảm (nhân sự, lương, dữ liệu khách hàng) → KHÔNG đưa vào
  pipeline, viết tay. Đây là quy tắc cứng, không phải khuyến nghị.

BOTTLENECK MỚI: bước 4 (người review). Nhóm chấp nhận vì đây chính là điểm kiểm soát
chất lượng — nếu bước này bị cắt thì cả hệ thống mất chỗ chặn lỗi duy nhất.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 10–15'/meeting `[ƯỚC]` | ≤ 5'/meeting | Bấm giờ từ lúc meeting kết thúc đến lúc note được lưu, 5 buổi liên tiếp trước và 5 buổi sau |
| Số bước | 6 | 5 | Đếm trên sơ đồ; quan trọng hơn số bước là số bước **người** phải làm |
| Số bước thủ công | 6/6 | 1/5 (chỉ còn bước review) | Đếm bước có actor là người |
| Bottleneck chính | Tra lại ngữ cảnh dự án (bước 3, 3–5') | Người review draft (bước 4, 3–4') | Nghẽn dịch từ "moi lại thông tin" sang "kiểm chứng" — đắt tương đương nhưng là việc đáng làm |
| Tỉ lệ meeting có note trong 24h | `[CHƯA ĐO — đếm 2 tuần lấy baseline]` | 100% | Đối chiếu lịch Calendar với số note thực có |
| Action item của mình bị rơi | 1–2 lần/tuần `[CHƯA ĐO — đếm 2 tuần]` | 0 | Đếm số việc được nhắc lại ở meeting sau mà note không hề có |
| Số lần phải hỏi lại đồng đội | 1–2 lần/tuần `[ƯỚC]` | < 1 lần/tuần | Tự đếm, ghi vào log pilot |
| Risk mới | Không có (người tự nhớ, tự viết) | (1) AI bịa quyết định không có thật; (2) nội dung buổi họp rời khỏi máy khi gửi lên dịch vụ ngoài; (3) người review qua loa vì tin draft | (1) đếm số dòng phải sửa / tổng số dòng; (2) kiểm bằng quy tắc cứng loại meeting nhạy cảm; (3) so tỉ lệ sửa tuần 1 với tuần 2 — nếu tụt về gần 0 là dấu hiệu review qua loa chứ chưa chắc là AI giỏi lên |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người **tham dự** meeting dự án, không phải người chủ trì và không phải thư ký. Người này không có nhiệm vụ viết biên bản cho cả team; họ viết note cho chính mình để tuần sau còn biết đã chốt gì và mình phải làm gì. Trong nhóm, đại diện là Dũng (researcher, 3–4 meeting/tuần). |
| **Workflow** | Sau mỗi meeting: mở file note → ngồi nhớ lại mạch họp → tra lại ngữ cảnh dự án ở Jira/Notion/repo/chat → viết summary + TODO → hỏi lại đồng đội chỗ không chắc → lưu vào Notion. Sáu bước, 10–15 phút, lặp 3–4 lần/tuần. |
| **Bottleneck** | Bước tra lại ngữ cảnh dự án (3–5'). Bản ghi âm và transcript mang được lời nói nhưng không mang được kiến thức nền của dự án, nên người viết note phải tự tái dựng nó trong đầu. Hai bước liền kề bị chặn vì lý do này chứ không phải vì gõ chậm. |
| **Impact** | 40–60 phút/tuần cho riêng việc viết note. Nhưng chi phí đắt hơn nằm ngoài con số đó: action item của chính mình bị rơi 1–2 lần/tuần `[CHƯA ĐO]`, phải hỏi lại đồng đội (tốn thời gian người thứ hai), và note cũ đọc lại sau 1 tuần thì không còn hiểu. |
| **Success Metric** | (1) Thời gian từ lúc họp xong đến lúc note được lưu: 10–15' → ≤ 5'. (2) Tỉ lệ meeting có note trong 24h: baseline đếm 2 tuần → 100%. (3) Số action item của mình bị rơi: baseline đếm 2 tuần → 0. Đo bằng bấm giờ và đối chiếu lịch, không đo bằng cảm giác. |
| **Boundary** | **Làm:** draft note cá nhân cho đúng một người dự họp. **Không làm:** không tự gửi cho team hay khách hàng; không tự tạo task trên Jira; không ghi âm khi chưa có sự đồng ý của tất cả người trong phòng; không đưa meeting nhạy cảm (nhân sự, lương, dữ liệu khách hàng) vào pipeline; AI không được viết ra quyết định mà transcript không có. |

**Câu hỏi AI phản biện v0 (nếu có):**

- **Field nào mơ hồ:** AI chỉ ra bốn chỗ. (1) *Impact* trộn một con số có thật (40–60'/tuần) với ba hậu quả chưa hề đo, dễ tạo cảm giác bài toán đau hơn thực tế. (2) *Success Metric* số (3) — "action item bị rơi" — phụ thuộc vào chính cái note đang thiếu, nên không có cách đo độc lập. (3) *Actor* mới có đúng một người thật (Dũng), chưa đủ để nói đây là vấn đề của một nhóm người. (4) *Boundary* chưa nói ai chịu trách nhiệm khi note sai mà vẫn được dùng để ra quyết định.
- **Tôi sửa gì:** (1) Tách rõ trong bảng: cái nào `[ĐO]`, cái nào `[CHƯA ĐO]`, và không cộng dồn chúng lại thành một con số impact duy nhất. (2) Đổi cách đo action item sang một tiêu chí quan sát được từ bên ngoài: đếm số việc được **nhắc lại ở meeting kế tiếp** mà note buổi trước không hề có — người khác kiểm được, không phụ thuộc trí nhớ người viết. (3) Thêm poll lớp để biết đây là vấn đề của bao nhiêu người, và cam kết hạ xuống Not Yet nếu tần suất trung vị dưới 2 meeting/tuần. (4) Thêm vào Boundary một dòng trách nhiệm: note đã qua review là trách nhiệm của người review, AI không được viện dẫn làm lý do — điều này đi thẳng vào PS v1.
- **Ý nhóm bỏ không dùng:** AI đề xuất mở rộng thành "hệ thống quản lý tri thức cho cả team" và "tự động đồng bộ action item sang Jira". Nhóm bỏ cả hai: ý đầu đổi hẳn bản chất bài toán từ note cá nhân sang knowledge base tổ chức; ý sau chính là thứ đẩy bài lên mức Agent và phá vỡ boundary "không tự tạo task".

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- **Độ mơ hồ:** [ ] Thấp (có đúng/sai rõ) / [x] **Cao** (nhiều cách trả lời vẫn OK) — Vì sao: hai người dự cùng một buổi họp viết ra hai bản note khác nhau và cả hai đều dùng được. Không có một bản tóm tắt "đúng" duy nhất để so. Tuy vậy có một phần nhỏ **mơ hồ thấp** nằm bên trong: "quyết định đã chốt" và "action item của tôi" thì có đúng/sai rõ ràng — và nhóm cố ý thiết kế template để tách phần này ra, vì phần kiểm được là phần đáng kiểm.
- **Độ phức tạp:** [x] **Thấp–vừa** (3 bước, đường đi cố định) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: đúng là có nhiều nguồn (transcript + glossary + milestone), nhưng chúng được nạp **một lần, cùng lúc, theo thứ tự cố định**, và bước sau không cần đọc kết quả bước trước để chọn đường đi tiếp. Nhóm phân biệt rõ: *nhiều nguồn dữ liệu* không đồng nghĩa với *độ phức tạp cao*. Độ phức tạp cao là khi hệ thống phải **tự quyết định bước tiếp theo**, và ở đây nó không phải quyết gì cả.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô: Độ phức tạp THẤP-VỪA × Độ mơ hồ CAO
→ theo ma trận worksheet: "Workflow có AI hỗ trợ một bước có thể đủ".
```

**Vì sao (2-3 câu):**

```text
Mơ hồ cao nên Rule thuần không đủ: không có luật if-then nào biến một transcript thành
đoạn văn có nghĩa, vì mỗi buổi họp nói một kiểu.

Nhưng phức tạp thấp nên chưa tới Agent: đường đi cố định (transcript + glossary → draft →
người review), không có nhánh rẽ, không cần hệ thống tự chọn dùng tool nào tiếp theo.

Điểm nhóm muốn nhấn: nghẽn thật nằm ở chỗ THIẾU NGỮ CẢNH, mà ngữ cảnh được giải bằng một
bước Rule (ghép file glossary) chứ không phải bằng mô hình thông minh hơn. Nếu chỉ nhìn
ma trận mà không nhìn nghẽn, nhóm sẽ tưởng cần model mạnh hơn — thực ra chỉ cần đưa đúng
thông tin vào.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Template note cố định 4 mục (quyết định / câu hỏi mở / action item của tôi / thuật ngữ) + quy tắc dành 5 phút cuối mỗi meeting điền tại chỗ + file `glossary.md` do team duy trì | Đủ nếu người dự họp kỷ luật và meeting ngắn. Giải được phần "viết cái gì" và "không sót mục nào" — ước lượng 50–60% giá trị, với chi phí gần bằng 0 | Phụ thuộc hoàn toàn vào kỷ luật cá nhân; ngày mệt là bỏ. Không giải được việc phải nhớ lại nội dung nếu viết muộn | **Có — dùng cho bước 2 (nạp glossary) và cho chính cấu trúc template ở bước 3.** Đây cũng là phương án fallback khi không có AI. Nhóm làm phần này TRƯỚC, bất kể có dùng AI hay không |
| **Workflow** | Transcript (tool có sẵn) → nạp glossary + milestone → AI draft theo đúng template 4 mục, mỗi dòng phải trích được câu gốc → người dự họp review và sửa → lưu | Đủ khi các bước đi thẳng một đường, AI chỉ đảm nhận đúng một việc ngôn ngữ, và có người kiểm ở cuối — đúng tình huống này | AI bịa quyết định không có trong transcript; đọc sai tên module/số liệu; người review đọc lướt vì tin draft; nội dung họp rời khỏi máy | **CHỌN — dùng cho bước 3 (draft)** |
| **Agent** | Bot tự vào phòng họp, tự tra Jira/repo/lịch để lấy ngữ cảnh, tự quyết định việc nào là action item, tự tạo task và tự gửi note cho những người liên quan | Chỉ cần khi có nhiều nhánh rẽ thật (phải tự quyết tra nguồn nào, tự quyết gửi cho ai) và khối lượng lớn tới mức không kịp review từng bản | Cần quyền ghi vào Jira và quyền gửi tin — hai thứ đắt nhất khi sai. Gửi nhầm một bản note bịa cho cả team là lỗi không rút lại được. Ghi âm tự động còn kéo theo vấn đề đồng ý của người tham dự | **Không chọn.** Giữ lại như hướng mở rộng, chỉ xét sau khi Workflow chạy ổn định ≥ 3 tháng và tỉ lệ phải sửa draft ổn định dưới 20% |

**5 câu hỏi chốt (trả lời câu đầy đủ):**

1. **Rule có giải được 70-80% case không?** Không, nhóm ước lượng Rule giải được khoảng 50–60%. Template 4 mục giải trọn vẹn vấn đề "viết cái gì, có sót mục nào không", và file glossary giải được một phần bước tra ngữ cảnh. Nhưng phần còn lại — ngồi nhớ lại mạch buổi họp khi đã viết muộn vài tiếng — thì không có luật nào thay được, vì nó phụ thuộc nội dung mỗi buổi mỗi khác. Dù vậy nhóm vẫn làm Rule trước, vì nó rẻ, không rủi ro, và là fallback bắt buộc phải có.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Đi thẳng một đường. Thứ tự transcript → nạp ngữ cảnh → draft → review → lưu là cố định cho mọi buổi họp. Chỉ có đúng một nhánh rẽ, và nó do **người** quyết chứ không phải hệ thống: meeting nhạy cảm thì không đưa vào pipeline.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Không. Hệ thống không phải tự quyết bất cứ điều gì: nguồn dữ liệu cố định, template cố định, người nhận cố định là chính người dự họp. Thứ duy nhất khiến nhóm từng nghĩ tới Agent là ý "tự tra Jira để lấy ngữ cảnh" — nhưng chính ý đó đã được giải rẻ hơn hẳn bằng một file glossary do người duy trì, không cần quyền truy cập hệ thống nào.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Chính người dự họp phát hiện ngay ở bước 4, vì họ vừa ngồi trong buổi họp đó nên có đối chứng tốt nhất có thể. Sửa mất vài chục giây cho lỗi tên module/số liệu; với lỗi nặng (bịa quyết định) thì bỏ toàn bộ draft và viết tay, mất thêm ~8 phút. Đây là lý do nhóm đánh giá rủi ro chấp nhận được: **người phát hiện lỗi và người chịu hậu quả là cùng một người**, không có ai ở hạ nguồn hứng lỗi thay.
5. **Có hạ được từ Agent → Workflow → Rule không?** Đã hạ một nấc: từ Agent xuống Workflow, bằng cách bỏ quyền tự tạo task và tự gửi. Nhóm cũng đã thử hạ tiếp xuống Rule thuần và kết luận là không đủ (xem câu 1) — nhưng phần Rule không bị vứt đi mà được giữ nguyên bên trong phương án Workflow, vừa làm bước 2 vừa làm fallback. Nói cách khác nhóm không chọn "Workflow thay cho Rule" mà chọn "Rule trước, AI thêm vào đúng một bước".

**Mức chọn:**

```text
Workflow (Rule làm nền + AI hỗ trợ đúng 1 bước draft + người review bắt buộc)
```

**Vì sao chọn (3-4 câu):**

```text
Vì nghẽn nằm ở bước tra ngữ cảnh và bước viết — hai việc ngôn ngữ mà Rule thuần không với
tới, nhưng cũng không đòi hệ thống phải tự lập kế hoạch.

Vì đường đi cố định: cùng một thứ tự bước cho mọi buổi họp, không nhánh rẽ, nên Workflow là
mức vừa khít, thêm nữa chỉ là thêm rủi ro chứ không thêm giá trị.

Vì có sẵn một chốt chặn chất lượng tự nhiên: người dự họp vừa ngồi trong buổi đó, nên họ
review được ngay và gần như không tốn chi phí học thêm gì.

Và vì phần đắt giá nhất của giải pháp lại là phần KHÔNG phải AI — file glossary. Chọn
Workflow cho phép nhóm làm phần đó trước và đo riêng được nó đóng góp bao nhiêu, thay vì
gói tất cả vào một hộp đen rồi không biết cái gì đang có tác dụng.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nhóm đã thử đứng lại ở Rule thuần và loại vì hai lý do đo được. Một: Rule chỉ giải phần
"viết cái gì", không giải phần "nhớ lại cái gì" — mà theo validation thì người ta thường
viết note vào buổi tối, tức là đúng lúc trí nhớ đã rơi mất một nửa. Hai: Rule phụ thuộc
hoàn toàn vào kỷ luật cá nhân, mà chính bằng chứng của bài toán này (note hay bị viết muộn,
viết chung chung) cho thấy kỷ luật là thứ đang thiếu — lấy thứ đang thiếu làm giải pháp thì
không ổn.

Cần nói rõ: nhóm KHÔNG bỏ Rule. Rule được giữ nguyên làm nền (template + glossary) và làm
fallback. Câu trả lời đúng ở đây là "Rule cộng thêm một bước AI", không phải "AI thay Rule".
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người tham dự meeting dự án (không chủ trì, không phải thư ký), có nhiệm vụ mang thông tin về cho công việc của chính mình. Đại diện: Dũng — researcher, 3–4 meeting/tuần `[ĐO qua Calendar]`. Phạm vi: chỉ meeting ≥ 30 phút, từ 3 người trở lên, có bàn quyết định kỹ thuật — đã loại standup ngắn và họp 1-1 xã giao sau khi validate. |
| **Workflow** | Mở note → nhớ lại mạch họp (3–4') → tra lại ngữ cảnh dự án ở Jira/Notion/repo/chat (3–5') → viết summary + TODO cá nhân (4–5') → hỏi lại đồng đội chỗ không chắc (2', 1–2 lần/tuần) → lưu. Tổng 10–15'/buổi `[ƯỚC]`, 3–4 buổi/tuần `[ĐO]`. |
| **Bottleneck** | Bước tra lại ngữ cảnh dự án. Transcript mang được lời nói nhưng không mang được kiến thức nền của dự án, nên người viết phải tự tái dựng nó. Bằng chứng: cùng một buổi họp, người nắm chắc dự án viết note mất ~5', người vừa nhận việc mất ~15'. |
| **Impact** | `[ĐO]` 40–60 phút/tuần cho riêng việc viết note. `[CHƯA ĐO — đếm 2 tuần lấy baseline]` 1–2 action item của chính mình bị rơi mỗi tuần; 1–2 lần/tuần phải hỏi lại đồng đội (kéo theo thời gian người thứ hai); note cũ đọc lại sau 1 tuần không còn hiểu. Nhóm cố ý **không cộng dồn** nhóm số đã đo và nhóm chưa đo thành một con số impact duy nhất. |
| **Success Metric** | (1) Thời gian họp-xong → note-đã-lưu: 10–15' → **≤ 5'** (bấm giờ 5 buổi trước, 5 buổi sau). (2) Tỉ lệ meeting có note trong 24h: baseline 2 tuần → **100%** (đối chiếu Calendar với số note thực có). (3) Số action item bị rơi: đếm số việc **được nhắc lại ở meeting kế tiếp mà note buổi trước không hề có** → **0** (tiêu chí quan sát được từ bên ngoài, không phụ thuộc trí nhớ người viết). (4) Metric kiểm soát chất lượng: tỉ lệ dòng phải sửa trong draft ≤ 30%, và **không** được giảm về gần 0 quá nhanh — nếu giảm quá nhanh thì nhiều khả năng người review đang đọc lướt chứ không phải AI giỏi lên. |
| **Boundary** (làm / không làm) | **Làm:** draft note cá nhân cho đúng một người dự họp; xuất theo template 4 mục; mỗi dòng phải trích được câu gốc trong transcript. **Không làm:** không tự gửi cho team/khách hàng; không tự tạo hay cập nhật task trên Jira; không ghi âm khi chưa có sự đồng ý của tất cả người trong phòng (quy tắc cứng); không đưa meeting nhạy cảm (nhân sự, lương, dữ liệu khách hàng) vào pipeline; không viết ra quyết định mà transcript không có; không tự suy diễn ai phải làm gì nếu trong họp không ai nói ra. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp **sau** khi transcript đã có và gói ngữ cảnh (glossary + milestone) đã được nạp — tức sau bước 2; và **trước** bước người dự họp review — tức trước bước 4. AI không chạm vào hai đầu: không chạm đầu vào (không tự đi lấy dữ liệu từ Jira/repo) và không chạm đầu ra (không lưu, không gửi thay người). |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow.** Vì đường đi cố định không cần hệ thống tự lập kế hoạch, nhưng bước viết lại là việc ngôn ngữ mà Rule thuần không với tới — nên đúng một bước dùng AI, phần còn lại là Rule và người. |
| **Rủi ro & người thật kiểm tra** | **Rủi ro lớn nhất:** AI viết ra một "quyết định đã chốt" mà buổi họp không hề chốt, người review đọc lướt cho qua, và một tuần sau cả nhóm làm việc dựa trên một quyết định không có thật. **Người kiểm:** chính người dự họp, ở bước 4, bắt buộc, không được bỏ. **Cách kiểm cụ thể:** mỗi dòng trong mục "Quyết định đã chốt" phải kèm câu trích nguyên văn từ transcript — không có trích dẫn thì xoá dòng đó, không cần tranh luận. **Rủi ro thứ hai:** nội dung buổi họp rời khỏi máy khi gửi lên dịch vụ ngoài — chặn bằng quy tắc cứng loại meeting nhạy cảm, và có đường lui dùng Whisper chạy local. **Trách nhiệm:** note đã qua review là trách nhiệm của người review; "AI viết vậy" không phải lý do được chấp nhận. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor đã được thu hẹp từ "User" thành "người tham dự meeting dự án ≥30 phút, không chủ trì", và người đó ngồi ngay trong nhóm nên kiểm chéo được từng bước. Workflow 6 bước có actor, input, output, thời gian và handoff cho từng bước. |
| Baseline + metric đo được chưa? | **Một phần** | Tần suất meeting là `[ĐO]` từ Calendar. Thời gian 10–15' mới là `[ƯỚC]`, phải bấm giờ 5 buổi mới thành baseline thật. Hai metric về bỏ sót thì `[CHƯA ĐO]` — đây là lý do nhóm chọn Go **có điều kiện**: tuần đầu của pilot là tuần đo baseline, chưa dùng AI. |
| Data/input đủ dùng chưa? | **Yes** | Transcript lấy được bằng tool có sẵn; glossary là file nhóm tự viết trong 30 phút; milestone đã có trên Notion. Không phải xin dữ liệu của tổ chức nào — khác hẳn bài #6 y tế đã loại ở Phase 3. |
| AI sai, hậu quả chấp nhận được không? | **Yes, có điều kiện** | Chấp nhận được vì note là bản nháp cá nhân và người phát hiện lỗi chính là người chịu hậu quả. Điều kiện bắt buộc: giữ nguyên quy tắc mỗi dòng quyết định phải có trích dẫn gốc, và giữ nguyên lệnh cấm tự gửi / tự tạo task. Bỏ một trong hai điều kiện này thì câu trả lời đổi thành No. |
| Có người review/owner không? | **Yes** | Owner là Dũng — vừa là người gặp vấn đề, vừa là người review, vừa là người chịu trách nhiệm về note đã duyệt. Không có tình trạng "ai cũng dùng, không ai chịu trách nhiệm". |
| Có cách non-AI đơn giản hơn không? | **Có, và nhóm làm nó trước** | Template 4 mục + file glossary giải được 50–60% với chi phí gần bằng 0. Nhóm không coi đây là lý do bỏ AI, mà coi là **thứ tự thi công**: làm Rule trước, đo, rồi mới thêm AI vào đúng một bước, để biết phần tăng thêm là do AI hay do template. |

**Decision:**

```text
GO — với scope nhỏ và có điều kiện. Pilot 3 tuần, 1 người (Dũng), 9-12 meeting.
Tuần 1 chạy Rule thuần để lấy baseline thật; tuần 2-3 mới bật AI.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Go vì bài toán có đủ ba thứ mà Phase 3 đã đặt làm điều kiện: actor thật ngồi trong nhóm,
workflow vẽ được đến từng bước với thời gian, và dữ liệu đầu vào lấy được ngay không phải
xin ai.

Go vì Phase 4 đã trả lời được câu hỏi nhóm tự đặt ra — tác động ngoài 10-15 phút là có
thật: action item bị rơi, phải hỏi lại đồng đội, note cũ đọc lại không hiểu. Nhóm đã cam
kết trước rằng nếu không tìm ra tác động nào ngoài thời gian thì hạ xuống Not Yet, nên đây
là một quyết định có điều kiện đã được kiểm, không phải kết luận có sẵn từ đầu.

"Có điều kiện" vì hai trong bốn metric hiện `[CHƯA ĐO]`. Nhóm không lấy đó làm cớ để hoãn,
nhưng cũng không giả vờ là đã có baseline: tuần 1 của pilot được dành riêng để đo, và chạy
bằng Rule thuần — nghĩa là nếu tuần 1 cho thấy template giấy đã đủ, nhóm dừng luôn ở Rule
và không bật AI.

Scope nhỏ vì phần đắt nhất của giải pháp là file glossary, không phải mô hình. Chạy 1 người
3 tuần là đủ để biết glossary có được duy trì nổi hay không — nếu không duy trì nổi thì mọi
thứ phía sau sụp, và tốt hơn là biết điều đó sau 3 tuần thay vì sau 3 tháng.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
DATA: 9-12 meeting thật của Dũng trong 3 tuần, cộng một file glossary.md khoảng 1 trang
(tên module, từ viết tắt, tên người + vai trò, milestone đang chạy, 3 quyết định gần nhất).
Không dùng dữ liệu mô phỏng.

CHẠY TAY (không code gì trong giai đoạn này):
- Tuần 1 — CHỈ RULE, không AI: viết note bằng template 4 mục, bấm giờ từng buổi. Đây là
  tuần lấy baseline thật cho cả ba số bên dưới.
- Tuần 2-3 — BẬT AI: xuất transcript bằng tool có sẵn → dán transcript + glossary vào một
  prompt cố định (prompt được viết một lần, không sửa giữa chừng, để kết quả so được với
  nhau) → AI draft theo đúng template 4 mục → Dũng review, sửa, đếm số dòng phải sửa → lưu.

ĐO ĐÚNG 3 SỐ:
1. Thời gian từ lúc meeting kết thúc đến lúc note được lưu (phút) — so tuần 1 với tuần 2-3.
2. Tỉ lệ dòng phải sửa trong draft = số dòng sửa / tổng số dòng AI viết ra (%). Đây là số
   nói lên AI có dùng được không, và cũng là số cảnh báo nếu nó tụt quá nhanh về 0.
3. Số action item của chính Dũng bị rơi — đếm bằng tiêu chí bên ngoài: việc được nhắc lại
   ở meeting kế tiếp mà note buổi trước không hề có.

Ngoài 3 số trên, ghi thêm một log lỗi định tính: mỗi lần AI bịa một quyết định không có
trong transcript thì ghi 1 dòng, kèm câu AI viết và câu gốc. Log này quan trọng hơn cả ba
con số, vì nó là thứ quyết định có dừng hay không.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Nhóm không chọn Not Yet cho bài này, nhưng ghi lại điều kiện đã thống nhất để nếu tuần 1
của pilot cho kết quả khác thì hạ xuống ngay, không cần họp lại:
- Nếu tần suất meeting thật (đếm từ Calendar) dưới 2 buổi/tuần → impact quá nhỏ → Not Yet.
- Nếu bấm giờ tuần 1 cho thấy thời gian thật dưới 6 phút/buổi → bài toán không đủ đau,
  vì mục tiêu sau cải thiện cũng chỉ là 5 phút → Not Yet.
- Nếu tuần 1 (Rule thuần) đã đưa được cả ba số về mức mục tiêu → dừng ở Rule, KHÔNG bật AI.
  Đây là kết cục nhóm hoàn toàn chấp nhận, thậm chí là kết cục đáng mừng.

Với bài #6 (dặn dò bệnh nhân) mà nhóm loại ở Phase 3, quyết định đúng hiện tại là Not Yet,
và cần validate trước: (a) xin được dữ liệu thật từ một phòng khám kèm thoả thuận về dữ
liệu bệnh nhân; (b) có một nhân viên y tế thật đứng ra thẩm định output; (c) đo được tỉ lệ
sai sót của con người hiện tại để có mốc so sánh — không có mốc này thì không cách nào nói
AI tốt hơn hay tệ hơn.
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu pilot thất bại (xem Exit bên dưới), phương án thay thế không phải là quay về con số 0
mà là giữ lại toàn bộ phần non-AI đã xây, vì nó vẫn còn nguyên giá trị:
- Template note cố định 4 mục, dùng tay.
- Quy tắc dành 5 phút cuối mỗi meeting điền tại chỗ, khi trí nhớ còn nguyên — đây là cách
  rẻ nhất để giải bước "nhớ lại", vì nó xoá luôn khoảng trễ giữa lúc họp và lúc viết.
- File glossary.md vẫn duy trì, vì nó có ích cho cả người mới vào dự án, không chỉ cho note.
- Quy tắc cuối mỗi buổi họp: người chủ trì đọc to lại danh sách "ai nhận việc gì" — 1 phút,
  giải trực tiếp rủi ro rơi action item mà không cần công nghệ nào.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng NGAY LẬP TỨC, không chờ hết pilot, nếu:
- AI viết ra một "quyết định đã chốt" không có trong transcript quá 1 lần trong 2 tuần.
  Đây là lỗi chết người của bài toán này vì nó tạo ra thông tin giả trông rất đáng tin.
- Có bất kỳ nội dung meeting nhạy cảm nào lọt vào pipeline, dù chỉ 1 lần.
- Ghi âm mà chưa được sự đồng ý của tất cả người trong phòng, dù chỉ 1 lần.

Hạ xuống Rule (giữ template, bỏ AI) nếu sau 3 tuần:
- Tỉ lệ dòng phải sửa vẫn trên 50% trong 2 tuần liên tiếp → draft không tiết kiệm được gì.
- Tổng thời gian không giảm dưới 8 phút/buổi → công sức duy trì glossary không hoàn vốn.
- Glossary không được cập nhật quá 2 tuần → toàn bộ tiền đề của giải pháp sụp, vì giá trị
  đến từ ngữ cảnh chứ không đến từ mô hình.

Dấu hiệu cảnh báo cần soi kỹ chứ không được mừng:
- Tỉ lệ dòng phải sửa tụt về gần 0 chỉ sau vài buổi. Khả năng cao là người review đã đọc
  lướt và tin draft, chứ không phải AI đột nhiên chính xác. Cách kiểm: lấy ngẫu nhiên 1
  note đã duyệt, đối chiếu từng dòng với transcript gốc.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 14 → 1 (cluster 4 cụm + shortlist 2+1 + bảng score có giải thích điểm cực trị)
- [x] Có validation (3 interview + poll + đếm Calendar) + research (5 tool, link chính thức kiểm được, không trích số liệu không verify)
- [x] Có workflow trước/sau đủ thời gian, actor, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent trên cùng một bài + 5 câu hỏi chốt + Decision Go có điều kiện kèm lý do và ngưỡng rollback

### Việc nhóm phải hoàn tất trước khi nộp bản cuối
- [ ] Thay các ô `⟨…⟩` trong bảng 4.1 bằng quote nguyên văn có thật từ 3 buổi interview
- [ ] Chạy poll Discord, điền số mẫu thật, đính kèm `02-group-problem-statement-poll.png`
- [ ] Đếm Calendar 4 tuần của Dũng, thay `[ƯỚC]` ở tần suất bằng `[ĐO]`
- [ ] Bấm giờ 5 buổi để thay baseline `10–15'` `[ƯỚC]` bằng số `[ĐO]`

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

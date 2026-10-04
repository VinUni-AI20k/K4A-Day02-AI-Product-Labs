# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thế Khang
- Mã học viên: 2A202602964
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4, Khoa CNTT, ĐH Khoa học và công nghệ Hà Nội đang theo học tại khóa Vin AI in Action
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): Học tập tại trường Vinuni, làm bài tập lab, học lecture và tự tổng hợp kiến thức ở nhà, xem video bài giảng để tóm tắt lại nội dung chính, lập trình các dự án cá nhân

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Xem lại video recording bài giảng (1.5 - 2h) để tóm tắt các công thức, thuật toán và lưu ý chính | Bản thân (học viên), các bạn trong lớp | Mất khoảng 30–45 phút/video để tua và ghi chép tóm tắt nội dung chính; tuần 3–4 video mất ~2–2.5 tiếng/tuần |
| 2 | AI có thể tốt hơn | Đọc tài liệu kỹ thuật, slide tiếng Anh và paper AI có nhiều thuật ngữ toán/mã giả trừu tượng, khó tự hệ thống hóa vào bài tập thực hành | Bản thân (SV năm 4), sinh viên theo học khóa AI | Mất 45–60 phút tự đọc mò nhưng chỉ hiểu sơ, nếu có bản tóm tắt đối chiếu code thì chỉ mất 10–15 phút nắm được ý chính |
| 3 | Lặp lại | Tự kiểm tra định dạng cấu trúc thư mục repo, tên file và đối chiếu checklist rubric markdown trước khi commit push lên GitHub nộp lab | Bản thân (học viên), TA chấm bài | Lặp lại 2 lần/tuần, mất 15–20 phút/lần rà soát thủ công từng tiêu chí, từng bị sót 1 file báo cáo |
| 4 | Tốn thời gian | Chuyển đổi và tổng hợp kiến thức từ nhiều nguồn rời rạc (slide PDF, file trên VLearn, thông báo Discord, tài liệu workshop) thành một bộ ghi chú ôn tập thống nhất | Bản thân và các học viên khác | Phải mở 4-5 tab công cụ khác nhau, mỗi ngày mất 1.5 – 2 tiếng đọc và chắp vá thông tin, dễ bỏ sót cập nhật mới |
| 5 | Pain từ người khác | Các thành viên trong nhóm liên tục hỏi lại về deadline, yêu cầu nộp bài và format báo cáo đã thông báo trên Discord/Zalo | Trưởng nhóm, thành viên trong nhóm (3-4 người) | Bị hỏi lặp lại 4–5 lần/tuần vì tin nhắn nhóm bị trôi, mất 5–10 phút mỗi lần tìm lại link cũ để gửi lại |
| 6 | Tốn thời gian | Đọc và debug các lỗi traceback phức tạp trong bài tập lab lập trình AI (lỗi version xung đột thư viện, CUDA out-of-memory, tensor dimension mismatch) | Bản thân, sinh viên làm lab AI | Mất 1–2 tiếng/lần gặp lỗi lạ, tra cứu qua 5–7 diễn đàn StackOverflow/GitHub Issues để tìm cách sửa |
| 7 | Lặp lại | Viết tài liệu hướng dẫn cài đặt môi trường (README.md, virtualenv, requirements.txt) và giải thích luồng code cho các dự án cá nhân / đồ án môn học | Bản thân, người chấm bài hoặc bạn bè clone repo về chạy | Mất 30–45 phút cho mỗi repo mới, lặp lại 2–3 lần/tháng với các bước cấu hình tương tự nhau |
| 8 | Pain từ người khác | Giảng viên và TA phản ánh học viên nộp code bài tập lab chạy được nhưng không có comment giải thích tư duy logic thuật toán | TA chấm bài, học viên bị trừ điểm | 1/3 thành viên trong nhóm từng bị TA nhắc nhở hoặc trừ 1–2 điểm/bài vì nộp code thiếu chú thích giải thuật |
| 9 | AI có thể tốt hơn | Tìm lại các câu trả lời giải đáp thắc mắc chuyên môn hoặc code snippet của TA/Mentor trên kênh chat Discord sau 1–2 tuần bị trôi sâu | Học viên trong lớp (30–40 người) | Mất 15–20 phút/lần tìm kiếm bằng search bar mặc định của Discord vì không lọc theo ngữ cảnh câu hỏi |
| 10 | Lặp lại | Tự tạo dữ liệu mẫu (mock dataset dạng JSON/CSV) với các trường và logic hợp lệ để kiểm thử các hàm xử lý dữ liệu trước khi train model | Bản thân khi code dự án cá nhân/lab | Mất 20–30 phút gõ tay dữ liệu giả lập cho mỗi module mới, lặp lại 2 lần/tuần |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Dựa vào lịch trình học tập của một sinh viên năm 4 ngành CNTT đang theo học lab AI, hãy gợi ý các tác vụ tốn thời gian, lặp lại hoặc gây pain point hàng tuần kèm số liệu đo lường cụ thể.
- Ý dùng được: Tóm tắt video lecture dài, debug traceback PyTorch/CUDA, kiểm tra checklist format repo nộp bài lab, tổng hợp ghi chú đa nguồn.
- Ý bỏ vì không phải pain thật: Tạo slide thuyết trình tự động hàng tuần (do chưa phải thuyết trình).

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
| 1 | Xem lại video recording bài giảng (1.5 - 2h) để tóm tắt các công thức, thuật toán và lưu ý chính | Workflow rõ, lặp lại đều đặn mỗi tuần; bottleneck ở bước tua nghe & chép; metric thời gian đo lường chính xác | Cách AI nhận diện công thức toán và trích xuất hình ảnh bảng vẽ của giảng viên có đủ chuẩn xác |
| 2 | Chuyển đổi và tổng hợp kiến thức từ nhiều nguồn rời rạc (slide PDF, file trên VLearn, thông báo Discord, tài liệu workshop) thành một bộ ghi chú ôn tập thống nhất | Workflow rõ ràng 5 bước, lặp lại hằng ngày; bottleneck ở bước chắp nối thông tin đa nguồn; metric thời gian đo lường tốt (1.5–2h/ngày) | Liệu AI có đủ truy cập vào tất cả nguồn (VLearn, Discord, PDF) hay cần export thủ công trước |
| 3 | Đọc và debug các lỗi traceback phức tạp trong bài tập lab lập trình AI (lỗi version xung đột thư viện, CUDA out-of-memory, tensor dimension mismatch) | Pain point nặng nhất khi code AI; tốn 1–2 tiếng mỗi lần gặp; AI hiểu ngữ cảnh code và traceback rất tốt | Môi trường phần cứng (GPU/CUDA) mỗi máy khác nhau, AI có thể đưa ra giải pháp không tương thích |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tóm tắt video recording bài giảng AI & Lecture Notes

```text
Problem 1 câu:
Mỗi tuần học viên mất 2–2.5 tiếng xem lại các video recording bài giảng (1.5–2h/video) để ghi chép tóm tắt công thức, thuật toán và giải thích code của giảng viên, trong đó bước tua video nghe đi nghe lại để hiểu đúng công thức tốn nhiều thời gian nhất.

Actor:
Bản thân (học viên) và các bạn cùng lớp Vin AI in Action cần ôn tập hoặc xem lại khi vắng buổi học.

Thời điểm / bối cảnh:
Buổi tối sau giờ học hoặc dịp cuối tuần trước khi bắt tay vào làm bài tập lab.

Current workflow 3-7 bước:
1. Mở video bài giảng (1.5 - 2h) trên nền tảng học tập / trình duyệt
2. Xem và tua tìm các đoạn giảng viên giải thích lý thuyết trọng tâm và demo code
3. Tạm dừng video nhiều lần để chép công thức và giải thích thuật toán vào ghi chú
4. Chụp ảnh màn hình các slide hoặc hình vẽ minh họa quan trọng của giảng viên
5. Tổng hợp lại thành bản ghi chú Markdown / Notion hoàn chỉnh

Bottleneck:
Bước 2 và 3: Việc tua video thủ công và nghe lại nhiều lần đoạn giảng khó để diễn giải thành ghi chú mất 30–45 phút cho mỗi video.

Impact:
Mất 2–2.5 tiếng/tuần cho 1 học viên; nếu nhân với quy mô lớp 30–40 bạn thì tổng thời gian lãng phí lên tới 60–80 giờ/tuần; việc tốn thời gian dễ gây nản và trì hoãn làm bài lab.

Success metric:
Giảm thời gian trích xuất ý chính và ghi chú từ 45 phút xuống dưới 10 phút/video, giữ được 100% công thức cốt lõi và timestamp chính xác đến từng đoạn giảng.

Non-AI alternative:
Giảng viên cung cấp slide PDF chi tiết kèm timestamp mục lục bài giảng; học viên xem video ở tốc độ 1.5x - 2x kèm phụ đề tự động mặc định.

AI hypothesis:
Dùng AI trích xuất audio thành transcript kèm timestamp, kết hợp LLM phân tích và tóm tắt theo cấu trúc chuẩn (Khái niệm - Công thức - Code logic - Lưu ý quan trọng). Học viên chỉ cần đọc bản nháp và bổ sung chi tiết.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 55 phút / video

[1 Mở video: 2'] → [2 Tua tìm đoạn trọng tâm: 15'] → [3 Dừng nghe & chép công thức: 25']  <-- bottleneck → [4 Chụp màn hình & tổng hợp: 13']

FUTURE STATE — 10 phút / video

[1 Auto trích transcript & timestamp: 1'] → [2 AI tóm tắt theo template cấu trúc: 2'] → [3 Học viên review & đối chiếu timestamp: 7']  <-- human boundary

Fallback: nếu AI tóm tắt thiếu công thức hoặc sai ngữ nghĩa toán học → Học viên bấm trực tiếp vào timestamp đi kèm để xem lại 1–2 phút video gốc.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Tổng hợp kiến thức từ nhiều nguồn rời rạc thành ghi chú ôn tập

```text
Problem 1 câu:
Mỗi ngày học viên mất 1.5–2 tiếng mở 4–5 nguồn khác nhau (slide PDF, file trên VLearn, thông báo Discord, tài liệu workshop) để chắp nối và tổng hợp thành một bộ ghi chú ôn tập thống nhất, trong đó bước đọc hiểu và đối chiếu thông tin chéo giữa các nguồn tốn nhiều thời gian nhất.

Actor:
Bản thân (học viên) và các học viên khác trong lớp Vin AI in Action.

Thời điểm / bối cảnh:
Mỗi tối sau giờ học hoặc cuối tuần khi chuẩn bị ôn tập và làm bài lab.

Current workflow 3-7 bước:
1. Mở slide PDF bài giảng trên VLearn hoặc Google Drive
2. Mở kênh Discord đọc thông báo bổ sung, Q&A của TA và các file đính kèm
3. Mở tài liệu workshop hoặc notebook Colab liên quan
4. Đọc từng nguồn và copy-paste các đoạn quan trọng vào file ghi chú cá nhân
5. Đối chiếu, sắp xếp lại theo chủ đề và loại bỏ nội dung trùng lặp giữa các nguồn

Bottleneck:
Bước 4 và 5: Việc đọc hiểu từng nguồn rồi tự tay chắp nối, đối chiếu và loại trùng lặp mất 60–80 phút, dễ bỏ sót cập nhật mới trên Discord hoặc VLearn.

Impact:
Mất 1.5–2 tiếng/ngày, tích lũy ~10 tiếng/tuần; nhiều lần phát hiện thiếu thông tin quan trọng khi làm lab vì ghi chú không đầy đủ; gây tâm lý quá tải khi phải xử lý quá nhiều tab và format khác nhau.

Success metric:
Giảm thời gian tổng hợp ghi chú từ 90 phút xuống dưới 20 phút/ngày; đảm bảo bao phủ 100% nội dung cập nhật mới từ tất cả các nguồn mà không bỏ sót.

Non-AI alternative:
Dùng template Notion/Google Docs có sẵn cấu trúc theo từng buổi học; đặt bookmark cho từng nguồn; nhờ bạn bè chia nhau ghi chú theo phân công.

AI hypothesis:
AI tự động thu thập nội dung từ các nguồn đã export (PDF, markdown Discord, notebook), phân loại theo chủ đề, loại trùng lặp và tạo bản ghi chú tổng hợp có cấu trúc. Học viên chỉ cần review, bổ sung hiểu biết cá nhân và đánh dấu phần chưa rõ.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 90 phút / ngày

[1 Mở slide PDF trên VLearn: 5'] → [2 Mở Discord đọc Q&A: 10'] → [3 Mở tài liệu workshop/Colab: 10'] → [4 Copy-paste đoạn quan trọng vào ghi chú: 35']  <-- bottleneck → [5 Đối chiếu & loại trùng lặp: 30']

FUTURE STATE — 18 phút / ngày

[1 Export các nguồn sang text/markdown: 3'] → [2 AI phân loại & tổng hợp theo chủ đề: 2'] → [3 AI tạo bản ghi chú có cấu trúc: 1'] → [4 Học viên review & bổ sung hiểu biết cá nhân: 12']  <-- human boundary

Fallback: Nếu AI tổng hợp sai hoặc thiếu nguồn → Học viên mở từng tab nguồn gốc và bổ sung thủ công vào bản ghi chú như quy trình cũ.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Debug lỗi traceback môi trường & thư viện AI/PyTorch

```text
Problem 1 câu:
Học viên mất trung bình 1–2 tiếng mỗi khi gặp lỗi traceback phức tạp (CUDA out-of-memory, version conflict package, mismatch dimension tensor) trong lúc làm lab AI, trong đó bước mò tìm root cause qua nhiều diễn đàn mất nhiều thời gian nhất.

Actor:
Bản thân (sinh viên làm bài tập lab AI) và các bạn cùng nhóm.

Thời điểm / bối cảnh:
Trong các buổi thực hành lab hoặc khi triển khai mô hình học máy trên máy cá nhân/Google Colab.

Current workflow 3-7 bước:
1. Chạy code thực nghiệm và gặp lỗi crash kèm log traceback dài
2. Đọc dòng thông báo lỗi cuối cùng để đoán nguyên nhân
3. Copy đoạn mã lỗi lên Google / StackOverflow / GitHub Issues
4. Mở 5–7 tab bài viết, đọc và thử lần lượt từng dòng lệnh gợi ý
5. Khởi động lại kernel/môi trường và chạy lại code kiểm tra

Bottleneck:
Bước 4: Đọc và thử các câu trả lời trên diễn đàn nhưng không khớp với phiên bản thư viện hoặc phần cứng hiện tại, dẫn đến cài thử nhiều package gây hỏng thêm môi trường.

Impact:
Mất 2–3 tiếng/tuần; làm chậm tiến độ nộp lab và gây tâm lý hoang mang, ức chế khi làm việc với các thư viện Deep Learning.

Success metric:
Giảm thời gian xác định và sửa lỗi từ 60–90 phút xuống dưới 15 phút cho mỗi ca traceback; tỷ lệ giải quyết đúng root cause ngay lần đầu đạt >80%.

Non-AI alternative:
Tạo và tuân thủ file requirements.txt cố định phiên bản, sử dụng Docker image môi trường chuẩn do giảng viên cung cấp, hoặc tra cứu FAQ lỗi phổ biến của môn học.

AI hypothesis:
Đưa toàn bộ traceback log + đoạn code gây lỗi + phiên bản môi trường (`pip list`, CUDA version) cho LLM phân tích, AI chỉ ra trực tiếp nguyên nhân gốc rễ và đưa code sửa đổi chính xác.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 75 phút / lần lỗi

[1 Gặp lỗi & đọc log: 5'] → [2 Search StackOverflow: 10'] → [3 Đọc 5-7 tab & thử các cách mò: 50']  <-- bottleneck → [4 Test lại: 10']

FUTURE STATE — 12 phút / lần lỗi

[1 Thu thập log lỗi + code context: 1'] → [2 AI phân tích root cause & đề xuất code fix: 2'] → [3 Học viên review code diff & chạy kiểm thử: 9']  <-- human boundary

Fallback: Nếu AI gợi ý cách fix không chạy được → Reset môi trường git về commit gần nhất và đăng bài hỏi kèm log chi tiết lên kênh Discord trợ giảng.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Tóm tắt video recording bài giảng AI & Lecture Notes
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
1. Đây là quy trình có chu kỳ lặp lại hằng tuần rất rõ ràng (mỗi tuần 2-3 video, mỗi video 1.5 - 2h) và hầu như mọi sinh viên trong lớp đều gặp phải.
2. Đo lường được số liệu chính xác: hiện tại mất 45 phút/video để tua nghe chép thủ công, giải pháp tương lai có thể kéo giảm xuống dưới 10 phút/video (tiết kiệm hơn 70% thời gian).
3. Tác động lớn đến chất lượng học tập: giúp học viên nắm chắc công thức và luồng code trọng tâm để làm lab kịp deadline mà không bị quá tải thông tin.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Với các môn toán/AI, giảng viên thường viết bảng hoặc vẽ đồ thị giải thích trực tiếp, nếu AI chỉ nghe âm thanh (transcript) mà không 'nhìn' thấy hình ảnh thì bản tóm tắt có bị thiếu sót các bước chứng minh toán học quan trọng không?
2. Nếu AI tóm tắt sai một công thức hoặc nhầm lẫn tham số code mà học viên không xem lại video kỹ, làm sao thiết kế cơ chế review (human boundary) để phát hiện ra ngay lỗi sai đó?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Problem ban đầu quá tập trung vào 'tạo chatbot hỏi đáp video' - dễ bị lan man và khó kiểm soát chất lượng; chưa làm rõ ranh giới xử lý khi bài giảng có nhiều công thức toán viết tay.
- Tôi sửa gì: Đổi từ ý tưởng chatbot sang Workflow 3 bước có human review ở cuối; bổ sung cơ chế Timestamp Fallback (bấm xem đúng đoạn video gốc nếu AI tóm tắt không rõ ý).

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge

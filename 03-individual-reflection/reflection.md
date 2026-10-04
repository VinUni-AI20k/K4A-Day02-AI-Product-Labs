# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thế Khang   
- Mã học viên: 2A202602964
- Nhóm: KHSHUD - Zone A
- Candidate problem nhóm chọn: Tóm tắt Meeting notes và trích xuất Action items sau cuộc họp dự án (Nguyễn Việt Dũng)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 10 problem cá nhân qua 4 lăng kính, chọn Top 3: Tóm tắt video lecture, Gộp kiến thức đa nguồn slide/VLearn/Discord , và Debug lỗi traceback PyTorch/CUDA. | Đóng góp 3 candidate bài toán sát sườn sinh viên vào kho 14 ý tưởng ban đầu của nhóm. |
| Pitch Problem Card | Trình bày bài #2 "Gộp kiến thức đa nguồn" (tốn 1.5–2h/ngày) và bài #1 "Tóm tắt video", phân tích chi tiết bottleneck ở khâu tua nghe/chép và gom file thủ công. | Giúp nhóm thấy rõ bức xúc của sinh viên tự học, đưa bài #2 vào danh sách xem xét sâu ở vòng hội tụ Phase 3. |
| Challenge bài của bạn khác | Chất vấn bài y tế của Uyên: chỉ ra rủi ro nghiêm trọng nếu AI sai liều thuốc và cảnh báo nhóm không thể xin dữ liệu bệnh án thật trong 4h lab; hỏi Dũng liệu 10–15' viết note có đủ đau để giải quyết không. | Cùng Hoàng kéo nhóm ra khỏi bẫy "chọn bài nghe cho to", ép nhóm đào sâu và tìm ra pain thật của meeting note nằm ở việc rơi việc tuần sau chứ không chỉ là số phút gõ chữ. |
| Gom trùng / cluster | Cùng nhóm phân loại 14 ý tưởng thành 4 cụm (A: Gom nguồn -> văn bản; B: Truy xuất; C: Cá nhân hóa dạy-học; D: Khác). | Xác định cụm A là cụm chủ lực (6/14 bài) và là thế mạnh xử lý ngôn ngữ của AI, định hướng nhóm chọn bài toán trọng tâm trong cụm này. |
| Chọn candidate problem | Chủ động lùi bài cá nhân (#2 đa nguồn) để ủng hộ bài #14 Meeting note của Dũng sau khi thấy dữ liệu Dũng có sẵn và rủi ro y tế của bài Uyên quá lớn. | Tạo sự đồng thuận cao (Consensus), giúp nhóm chốt bài nhanh gọn để dành trọn vẹn thời gian cho Phase 4 và Phase 5. |
| Validation / research | Đảm nhận vai trò chính ở mục 4.2 Research: đào sâu và đối chiếu 5 giải pháp trên thị trường (Otter, Fireflies, Granola, MS Teams, Whisper); trực tiếp kiểm chứng link nguồn. | Phát hiện ra pattern đắt giá từ Granola (AI khuếch đại ghi chú thô của người, không thay người) và khoảng trống cốt lõi: các công cụ đều thiếu "Project Knowledge". |
| Workflow nhóm | Phối hợp với Hiệp và Dũng rà soát luồng Before (6 bước) và After (5 bước); định hình bước 2 (Nạp glossary.md) là bước giải quyết nút thắt chính. | Đảm bảo workflow có tính thực thi cao, phân định rạch ròi giữa bước máy (STT), bước rule (ghép glossary), bước AI (draft), và bước người (review). |
| Problem Statement | Cùng nhóm tranh luận và hoàn thiện bảng PS v0 và v1; kiên quyết đưa vào Boundary: "không tự đồng bộ Jira/Slack" và "không ghi âm khi chưa xin phép". | Bảo vệ ranh giới an toàn (Human Boundary), chặn đứng việc nhóm bị trôi sang làm Agent tự động hóa quá đà gây mất kiểm soát. |
| Rule / Workflow / Agent | Phân tích phương án ở 3 tầng; chỉ ra template 4 mục và file glossary.md chính là tầng Rule giải quyết được 50–60% giá trị mà chi phí bằng 0. | Giúp nhóm tự tin chốt mức Workflow (chỉ dùng AI ở bước draft), không bị cuốn theo trào lưu làm Agent phức tạp. |
| Decision | Cùng nhóm bỏ phiếu chốt "Go" dựa trên bằng chứng có thể chạy pilot tức thì bằng transcript cuộc họp Day 02; đặt ra điều kiện rollback nếu AI bịa quyết định. | Nhóm có kế hoạch pilot thực nghiệm cụ thể (đo 3 con số) và kịch bản rút lui an toàn (fallback về template viết tay). |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi nằm ở phần 4.2 Research giải pháp, nơi tôi bóc tách 5 công cụ hiện có để chỉ ra bài học cốt lõi từ Granola (AI không nghe thay người mà khuếch đại ghi chú thô) và xác định bước then chốt là nạp glossary.md (Project Knowledge); cùng với việc thiết lập ranh giới cứng trong Boundary kiên quyết cấm AI tự động tạo task trên Jira.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các tác vụ tốn thời gian, lặp lại dựa trên bối cảnh sinh viên CNTT học lab AI. | Gợi ý nhanh các lăng kính đa dạng, giúp tôi liên tưởng ra lỗi CUDA/traceback và việc rà soát checklist rubric repo. | Đưa ra các gợi ý viển vông, không có thực tế như "tự động tạo slide thuyết trình hàng tuần" hoặc số liệu bịa đặt vô căn cứ. | Gạt bỏ các ý tưởng ảo; tự đo đạc lại số liệu thật từ lịch sử học tập của bản thân (bấm giờ 30–45' tua video, 1–2h debug CUDA). |
| Problem Card | Hỗ trợ cấu trúc dàn ý workflow Current State và Future State cho 3 problem cards. | Giúp định dạng sơ đồ ASCII nhanh, tách rõ các bước tuần tự và gợi ý các metric đo lường định lượng. | Ước lượng thời gian sau khi có AI quá lạc quan (từ 55' xuống 10 giây), bỏ qua thời gian con người phải đọc lại và kiểm chứng công thức. | Tự bổ sung bước Human Review (10–15 phút) và ranh giới Fallback khi AI trích xuất sai bảng vẽ hoặc công thức toán. |
| Workflow | Gợi ý các bước tự động hóa cho workflow Meeting Note của nhóm. | Đưa ra khung xử lý âm thanh: Audio -> STT -> Summarization -> Integration khá liền mạch. | Bị bệnh "Agentic hóa": đòi AI tự nghe, tự tra Jira, tự phân loại task và tự gửi vào kênh chung mà không cần ai duyệt. | Cùng Hiệp chặn đứng ý tưởng này; hạ xuống Workflow có kiểm soát: bắt buộc có bước người duyệt và nạp glossary thủ công. |
| Research | Tìm kiếm các bài học và khoảng trống tính năng từ Otter, Fireflies, Granola, Teams. | Tóm lược nhanh tính năng cốt lõi của từng công cụ, giúp tiết kiệm thời gian đọc tài liệu sản phẩm. | Ảo giác (hallucination) đưa ra các số liệu phần trăm marketing không kiểm chứng được (như "tiết kiệm 73% thời gian"). | Xóa bỏ toàn bộ số liệu marketing của AI; truy cập trực tiếp link trang chủ chính thức để kiểm chứng năng lực thực tế. |
| Problem Statement | Nhờ AI đóng vai phản biện (Devil's Advocate) soi vào bản thảo PS v0 của nhóm. | Chỉ ra rất trúng: nhóm đang trộn số liệu đo thật với hậu quả ước lượng chưa đo, và tiêu chí "rơi action item" thiếu cách đo độc lập. | Đề xuất giải pháp sửa theo hướng mở rộng scope thành "hệ thống quản trị tri thức tổ chức" (sai lệch bài toán cá nhân ban đầu). | Giữ nguyên bài toán cá nhân; tiếp thu góp ý để tách bạch nhãn [ĐO] / [CHƯA ĐO] và đổi cách đo action item qua meeting kế tiếp. |
| Rule / Workflow / Agent | Trợ giúp lập luận trả lời 5 câu hỏi chốt để phân định giữa Rule, Workflow và Agent. | Làm rõ ranh giới lý thuyết giữa hệ thống có nhánh rẽ động (Agent) và hệ thống đường ống tuyến tính (Workflow). | Cố thuyết phục nhóm nên dùng Agent vì "có thể tích hợp API gọi tool hiện đại hơn, hợp xu hướng AI 2026". | Kiên quyết chọn Workflow; chỉ ra rằng Rule template giải được 50% giá trị và Agent chỉ mang lại rủi ro gửi nhầm tin nhắn cho team. |
| Decision | Gợi ý các tiêu chí đánh giá rủi ro để đưa ra quyết định Go / Not Yet / No-Go. | Cung cấp khung đánh giá điều kiện triển khai pilot và các chỉ số đo lường hiệu quả sau thử nghiệm. | Cho rằng dự án nên "Go lớn" (triển khai cho cả lớp ngay lập tức) mà không tính đến rủi ro lộ lọt thông tin nhạy cảm cuộc họp. | Siết lại quyết định: chỉ "Go pilot nhỏ" trên chính file ghi âm của nhóm, đặt quy tắc cứng cấm đưa họp nhạy cảm vào AI. |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Sau khi nghe top 3 problems của các bạn khác thì tôi rút ra là nên ưu tiên các bài toán đã có sẵn dữ liệu đã được kiểm chứng và có tính thực tiễn .Tôi đã đóng góp được 1 vài í kiến cho candidates của nhóm về workflow và human boundary. Điều khó nhất khi viết problem statement là dễ bị thổi phồng hậu quả dự đoán mà không có kiểm chứng. Nếu làm lại tôi sẽ challenge nhóm mạnh hởn việc lấy mẫu dữ liệu thật từ đầu vào PS và có nhiều con số và dữ liệu cụ thể hơn để chứng minh. 
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Văn Biển
- Mã học viên: 2A202602416
- Nhóm: Nhóm 5 thành viên: Đoàn Bá Khải, Trần Ngọc Khuyến, Nguyễn Phúc Bảo, Nguyễn Văn An và Nguyễn Văn Biển.
- Candidate problem nhóm chọn: Trợ giảng/giảng viên bị sinh viên hỏi lặp đi lặp lại về cùng một vấn đề hoặc lỗi bài lab trên kênh chat lớp học.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 problem theo 4 lăng kính, trong đó có các bài toán về tìm tài liệu, kiểm tra hồ sơ và hỗ trợ người dùng trong workflow y tế. | Nhóm có thêm góc nhìn để so sánh; tôi nhận ra các candidate y tế ban đầu chưa có evidence mạnh bằng pain hỗ trợ lab mà cả nhóm trực tiếp quan sát. |
| Pitch Problem Card | Tôi trình bày các candidate theo actor, workflow, bottleneck và metric thay vì chỉ pitch một ý tưởng AI. | Nhóm so sánh được mức độ cụ thể và khả năng đo của từng bài. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về metric, phạm vi và phương án non-AI; đặc biệt kiểm tra liệu một bài có thật sự cần Agent hay chỉ cần checklist, FAQ hoặc Rule. | Nhóm loại bớt các bài quá rộng hoặc đã có cách giải đơn giản hơn, tránh chọn solution chỉ vì nghe “AI”. |
| Gom trùng / cluster | Tôi góp phần nhìn các candidate theo nhóm hỗ trợ lỗi lab, tự học, vận hành nhóm và chấm bài. | Nhóm rút 12 candidate về các cluster có pattern chung trước khi shortlist, thay vì vote ngay theo cảm tính. |
| Chọn candidate problem | Tôi đánh giá candidate hỗ trợ lỗi lab theo actor kép: sinh viên và TA, cùng khả năng đo thời gian chờ, câu hỏi trùng và số lần TA can thiệp. | Candidate này đạt 35/35 trong bảng score và được chọn để validation sâu hơn. |
| Validation / research | Tôi tập trung kiểm tra các metric và rủi ro chất lượng: câu hỏi trùng, phản hồi “Đã fix được/Chưa được”, nguồn trích dẫn và nguy cơ Q&A bị nhiễm bẩn. | Nhóm thu hẹp scope vào lỗi môi trường/cài đặt/cú pháp phổ biến, không ôm lỗi logic riêng lẻ; đồng thời bổ sung cơ chế ticket và hậu kiểm TA. |
| Workflow nhóm | Tôi review các bước trước/sau và yêu cầu ghi rõ thời gian, handoff, human boundary và fallback. | Workflow thể hiện được ba tầng: Rule kiểm format, Workflow tra kho Q&A và Agent truy hồi/escalate; bước sinh viên tự chạy lệnh vẫn là boundary của con người. |
| Problem Statement | Tôi góp ý để metric không chỉ là “nhanh hơn”, mà có baseline, target và cách đo; đồng thời làm rõ phần hệ thống không được làm. | PS v0/v1 có các mốc như dưới 30 giây cho câu trúng kho, giảm 70% câu TA phải gõ tay và giới hạn không truy cập máy sinh viên. |
| Rule / Workflow / Agent | Tôi giúp phân biệt phần nào nên dùng Rule, phần nào dùng Workflow và chỉ mở Agent cho câu hỏi mới/mơ hồ cần nhiều vòng truy hồi. | Nhóm chọn kiến trúc Hybrid có thể hạ cấp từng tầng, thay vì dùng Agent cho toàn bộ câu hỏi. |
| Decision | Tôi kiểm tra điều kiện Go, pilot nhỏ nhất và ngưỡng rollback, đặc biệt là tỷ lệ “Chưa được” và tỷ lệ entry bị TA loại. | Quyết định Go có phạm vi pilot 20 cặp Q&A, chạy song song với TA trong một tuần và có đường quay về FAQ/ticket thủ công. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần có dấu tay rõ nhất của tôi là lớp kiểm soát chất lượng của workflow: tôi giúp nhóm chuyển ý tưởng bot hỏi đáp thành các chỉ số có thể đo, thêm phản hồi "Đã fix được/Chưa được", cờ `chưa kiểm duyệt` cho Q&A mới và điều kiện rollback khi Agent trả lời không đáng tin. Nhờ đó, sản phẩm không chỉ được mô tả là chatbot trả lời nhanh mà có owner, human boundary và cách dừng an toàn.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm góc nhìn và phản biện danh sách problem sau khi tôi đã tự scan. | AI giúp tôi nhìn ra actor, bottleneck và metric cần có trong mỗi candidate. | AI dễ đẩy sang các ý tưởng “trợ lý AI y tế” hoặc chatbot quá rộng dù chưa có người dùng và evidence. | Tôi loại các bài chẩn đoán/tư vấn điều trị và giữ các problem có workflow cụ thể; sau đó chuyển trọng tâm theo pain thật của nhóm là lỗi lab lặp lại. |
| Problem Card | Nhờ AI đặt câu hỏi phản biện về actor, bottleneck, metric, non-AI alternative và human boundary. | AI hữu ích khi chỉ ra một card có thể đang nhảy sang Agent quá sớm. | AI dễ đưa metric đẹp như “giảm 50% thời gian” nhưng không nói baseline, cách lấy mẫu hay ai xác nhận thành công. | Tôi yêu cầu metric có baseline, target, sample và owner; với sản phẩm nhóm, tôi thêm nút phản hồi của sinh viên và hậu kiểm của TA. |
| Workflow | Dùng AI để sắp xếp mô tả thành current/future workflow và nhận diện điểm handoff. | AI giúp nhìn rõ các nhánh trúng kho, truy hồi thêm hoặc escalate. | AI dễ gộp bước của máy và người, hoặc mô tả Agent như có thể tự sửa lỗi trên máy sinh viên. | Tôi tách Rule/Workflow/Agent, giữ bước sinh viên tự chạy lệnh và TA review là human boundary, đồng thời thêm fallback khi không đủ bằng chứng. |
| Research | Dùng AI để gợi ý các pattern/tool cần kiểm tra như auto-responder, forum Q&A, RAG và ticket escalation. | AI giúp nhóm mở rộng danh sách hướng nghiên cứu nhanh hơn. | Link, tính năng và claim do AI gợi ý không mặc nhiên là evidence; một tool có thể giải quyết keyword matching nhưng không giải quyết semantic retrieval. | Nhóm chỉ giữ nguồn có thể kiểm tra, không dùng số liệu chưa verify, và ghi rõ khoảng trống/rủi ro của từng pattern trước khi rút bài học. |
| Problem Statement | Nhờ AI phản biện các field còn mơ hồ trong PS v0. | AI chỉ ra điểm yếu của metric “80% tự sửa thành công”, boundary với ảnh chụp log và cơ chế ghi ngược Q&A. | AI không biết chắc dữ liệu lớp, năng lực TA hay mức rủi ro chấp nhận được; nếu để AI viết thay, PS sẽ nghe hợp lý nhưng thiếu owner thực tế. | Tôi cùng nhóm đổi metric thành các tín hiệu có thể log, giới hạn MVP ở text/log, yêu cầu trích dẫn và đưa Q&A mới vào trạng thái `chưa kiểm duyệt`. |
| Rule / Workflow / Agent | Dùng AI để challenge việc chọn Agent và so sánh ba mức tự động hóa. | AI hỗ trợ phân biệt đường đi cố định của câu hỏi lặp lại với câu hỏi mới cần hỏi lại/truy hồi nhiều vòng. | AI thường mặc định Agent là phương án mạnh nhất và bỏ qua chi phí, hallucination, quyền truy cập và rollback. | Tôi ủng hộ kiến trúc Hybrid: Rule ở tầng format, Workflow ở tầng Q&A đã biết, Agent chỉ ở vùng khó; Agent không có quyền terminal hay tự duyệt kho. |
| Decision | Dùng AI để kiểm tra các điều kiện Go/Not Yet/No-Go và gợi ý pilot/risk checklist. | AI giúp nhóm nhìn thấy cần có pilot nhỏ, người chịu trách nhiệm và điều kiện dừng. | AI không thể thay nhóm quyết định Go chỉ từ một vài con số; đặc biệt quote/log phải do nhóm tự thu thập và kiểm chứng. | Tôi giữ quyết định Go ở phạm vi pilot một tuần, đo ba số chính và đặt ngưỡng tắt Agent hoặc quay về workflow FAQ + ticket. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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


Điều tôi học được rõ nhất khi nghe 12 candidate là một pain tốt không nhất thiết là ý tưởng có AI nhiều nhất; nó phải có actor cụ thể, bước nghẽn quan sát được và cách đo trước/sau. Ban đầu tôi nghiêng về các sản phẩm hỗ trợ nghiên cứu y tế vì đó là hướng tôi quan tâm, nhưng khi nghe nhóm phân tích lỗi lab, tôi nhận ra bằng chứng trực tiếp của 45 tin nhắn và 31 câu hỏi thuộc 4 chủ đề lặp lại mạnh hơn các giả định trong scan cá nhân của tôi. Nhóm có lúc đứng gần solution-first khi nói đến bot, RAG và Agent, nhưng việc tách Rule, Workflow và Agent đã kéo thảo luận trở lại workflow thật. Tôi thay đổi cách nhìn về Agent: Agent chỉ đáng dùng cho câu hỏi mơ hồ cần hỏi lại và truy hồi nhiều vòng, còn phần lớn câu hỏi lặp lại nên được xử lý bằng kho Q&A có kiểm duyệt. Đóng góp chính của tôi là làm rõ lớp đo lường và kiểm soát chất lượng, từ thời gian phản hồi và tỷ lệ câu hỏi TA phải gõ tay đến nút “Đã fix được/Chưa được”, trạng thái Q&A chưa kiểm duyệt và điều kiện rollback. Điều khó nhất khi viết Problem Statement không chỉ là chọn metric, mà là nối metric với hành vi thật và người chịu trách nhiệm kiểm tra nó. Ví dụ, “sinh viên tự sửa thành công” không thể đo đáng tin nếu sinh viên đọc câu trả lời rồi biến mất, nên cần tín hiệu phản hồi và ticket khi chưa được. Tôi cũng hiểu boundary quan trọng không kém tính năng: bot chỉ đọc và hướng dẫn, không truy cập máy sinh viên, không chạy lệnh, không giải bài hộ và không trả lời khi thiếu nguồn. Nếu làm lại, tôi sẽ challenge sớm hơn về tính xác thực của quote, log 45 tin nhắn và các ngưỡng 85%, 70%, 80%, vì các con số này cần được lưu kèm cách lấy mẫu và thời điểm đo để tránh tạo cảm giác chính xác giả. Sau lab, tôi có thể tự giải thích mạch problem → workflow → metric → boundary → AI fit: pain là TA trả lời lặp và sinh viên chờ; workflow là hỏi, tra cứu, trả lời hoặc escalate; metric là thời gian, tỷ lệ xử lý và chất lượng Q&A; boundary là người vẫn chạy lệnh và TA vẫn duyệt; vì vậy chọn Hybrid có rollback thay vì Agent toàn phần.
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


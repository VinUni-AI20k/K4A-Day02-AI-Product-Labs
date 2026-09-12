# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Phạm Minh Hiếu
- Mã học viên: 2A202602919
- Nhóm: [Điền tên nhóm / số nhóm]
- Candidate problem nhóm chọn: Thất thoát thông tin liên quan đến cá nhân trong Discord nhóm/lớp và các buổi Zoom không có bản tóm tắt (ý tưởng gốc: Nguyễn Việt Hoàng Hải)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan được 8 problems từ trải nghiệm intern PM: weekly report, meeting notes, user story, Jira status update, feedback tổng hợp, tài liệu onboarding, câu hỏi lặp từ PM Lead, đọc story cũ | Đóng góp 3 candidates vào pool nhóm, trong đó 2 bài (weekly report, meeting notes) đều liên quan đến cluster "thất thoát thông tin sau họp/chat" |
| Pitch Problem Card | Pitch Card #1 (weekly report) trong 2 phút: nêu rõ 7 bước workflow, bottleneck viết narrative, baseline 60-80'/tuần, và metric giảm thời gian | Card được shortlist nhưng nhóm thấy bài meeting notes/chat rộng hơn và cover nhiều người hơn |
| Challenge bài của bạn khác | Hỏi bạn Nguyễn Quang Huy khi pitch "tự động phân loại email": "Actor là ai cụ thể, workflow hiện tại mấy bước, và Rule filter có đủ không?" | Bạn Huy nhận ra bài quá rộng, không rõ bottleneck ở bước nào → loại khỏi shortlist |
| Gom trùng / cluster | Đề xuất gom bài weekly report + meeting notes + chat recap vào cụm "thất thoát thông tin ở các mối bàn giao" | Nhóm thấy pattern chung: nhiều nguồn thông tin → không ai gom → mỗi người tự đào lại |
| Chọn candidate problem | Bỏ phiếu chọn "thất thoát thông tin sau họp và trong chat" vì cover actor rộng hơn (cả team, không chỉ PM) và bottleneck rõ (bước 5 — tự đào lại) | Nhóm đồng thuận 5/5 sau khi giữ lại 2 lo ngại thành điều kiện validate |
| Validation / research | Hỏi nhanh 2 bạn cùng lớp (ngoài nhóm): cả 2 xác nhận mất 15-20'/ngày scroll lại Discord. Tìm được Slack AI, Otter.ai, Granola làm tương tự | Confirm pain thật, phát hiện phần cá nhân hoá (bước ③) là chỗ chưa tool nào làm tốt |
| Workflow nhóm | Vẽ draft current workflow 5 bước trên giấy, sau đó chuyển thành Mermaid. Đề xuất thêm "chỗ thất thoát" vào mỗi bước | Nhóm dùng bản Mermaid của tôi làm nền, bổ sung thêm chi tiết ở bước ④ (người xác nhận) |
| Problem Statement | Viết draft field Bottleneck và Success Metric cho PS v0; dùng AI phản biện để tìm field mơ hồ | AI chỉ ra metric "giảm thời gian" cần baseline cụ thể → tôi thêm "bấm giờ 5 người trong 1 tuần" |
| Rule / Workflow / Agent | Phân tích 5 câu hỏi chốt: Rule keyword chỉ bắt @mention chứ không hiểu context, Agent thêm quyền mà không thêm giá trị → lập luận Workflow đủ | Nhóm thống nhất chọn Workflow, không nâng lên Agent |
| Decision | Đề xuất "Go với scope nhỏ" kèm 4 điều kiện kiểm chứng trước (bấm giờ, tỷ lệ rơi, team chấp nhận bot, tool sẵn có) | Nhóm chọn Not Yet vì chưa kiểm chứng xong 4 điều kiện, nhưng hướng Go nếu validate xong |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi vẽ bản workflow trước/sau (cả ASCII và Mermaid) với ý tưởng đánh dấu "chỗ thất thoát" ở mỗi bước trong current state — đây là phần giúp nhóm nhìn ra bottleneck không phải ở bước viết minutes mà ở bước mỗi người tự đào lại. Tôi cũng viết phần boundary (AI được làm gì / không làm gì) dựa trên lo ngại về riêng tư khi ghi âm họp.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI gợi ý thêm problem theo 4 lăng kính cho role Intern PM | Gợi ý được problem #8 (viết user story trùng lặp) — đúng pain tôi gặp tuần trước | Gợi ý "xây chatbot FAQ nội bộ" và "tự động CI/CD" — quá rộng và không phải việc PM | Bỏ 2 ý không phải pain thật, chỉ giữ ý có workflow thật mà tôi đã gặp |
| Problem Card | Nhờ AI phản biện Card #1 theo 6 câu hỏi skeptical PM | Chỉ ra metric chất lượng narrative chưa có → tôi chưa nghĩ tới | AI đề xuất "hãy chuyển sang Agent để tự gom data từ 3 nguồn" — nhảy solution quá sớm | Giữ Workflow, thêm metric phụ "số lần PM Lead hỏi lại không tăng" |
| Workflow | Nhờ AI chuyển mô tả workflow thành Mermaid syntax | Nhanh hơn nhiều so với tự viết Mermaid từ đầu, đặc biệt phần styling (classDef, stroke-dasharray) | AI gộp bước "ghi chú rời" và "viết notes có cấu trúc" thành 1 bước, mất đi bottleneck | Tách lại thành 2 bước riêng vì bottleneck nằm ở bước viết có cấu trúc, không phải bước ghi rời |
| Research | Hỏi AI tìm tool tương tự: Slack AI, Otter, Granola, Gemini in Meet | Gợi ý được Fellow AI mà tôi chưa biết; pattern chung "AI draft, người review" giúp validate hướng Workflow | Claim "Otter giảm 80% thời gian meeting notes" không có nguồn cụ thể | Chỉ giữ link chính thức của từng tool, bỏ claim số liệu không verify được |
| Problem Statement | Nhờ AI phản biện PS v0: chỉ ra field mơ hồ, metric chưa đo được | Chỉ ra boundary chưa nói rõ "AI không được đọc DM riêng" → quan trọng cho trust | AI sửa luôn PS thay vì chỉ đặt câu hỏi — mất đi quá trình suy nghĩ của nhóm | Chỉ lấy câu hỏi AI đặt ra, tự viết lại PS với nhóm |
| Rule / Workflow / Agent | Hỏi AI so sánh 3 mức cho bài toán nhóm | Phân tích rõ: Rule chỉ bắt @mention không hiểu context, Agent cần quá nhiều permission | AI thiên về Agent "cho linh hoạt" mà không tính rủi ro permission và trust | Nhóm quyết Workflow vì các bước tuyến tính, AI không cần tự lập kế hoạch |
| Decision | Không dùng | Không dùng — nhóm tự thảo luận và bỏ phiếu | — | — |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn trong nhóm, tôi nhận ra mình hay bị kẹt trong góc nhìn PM — toàn nghĩ về report, meeting notes, user story. Bạn Nguyễn Thị Minh Khánh đưa ra bài về "designer phải đoán ý PM khi spec mập mờ" khiến tôi giật mình vì đúng pain mà tôi gây ra nhưng không nhìn thấy. Điều này dạy tôi rằng lăng kính "Pain từ người khác" rất quan trọng và nên dùng nhiều hơn.

Nhóm có một lúc bị solution-first: khi thảo luận bài meeting notes, bạn Nguyễn Khắc Giáp đề xuất ngay "xây Agent ghi chép tự động có thể gọi Google Calendar + Jira API". Tôi và bạn Nguyễn Việt Hoàng Hải challenge lại bằng câu hỏi "Nếu Rule ghi transcript + AI trích xuất tuyến tính đã đủ, thì cần Agent tự lập kế hoạch để làm gì?" — sau đó nhóm đồng ý hạ về Workflow. Đây là lần tôi thấy rõ nhất giá trị của câu hỏi "Có thể hạ mức không?" trong worksheet.

Điều khó nhất khi viết Problem Statement không phải metric mà là boundary. Metric thì biết đo thời gian, đếm lần; nhưng boundary phải nghĩ tới cả chuyện riêng tư (bot ghi âm họp nhạy cảm), quyền hạn (AI có được tự phân công việc cho người khác không), và trust (cả lớp có chấp nhận bot ghi âm buổi Zoom không). Phần boundary "AI không được đọc DM riêng, không đọc channel riêng tư hay voice chat ngoài giờ họp chính thức" là phần tôi đóng góp và nhóm dùng nguyên trong bản cuối.

Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần validation. Nhóm chỉ hỏi nhanh 2-3 người trong lớp, chưa thật sự đo baseline "15-20 phút tự đào lại mỗi ngày" — đây là con số giả định. Tôi nên đề xuất ngay từ đầu: mỗi người bấm giờ 3 ngày rồi mới chốt metric, thay vì chỉ ghi vào phần "cần kiểm chứng" cuối bài.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

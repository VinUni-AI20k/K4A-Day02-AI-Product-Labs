# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Vũ Quang Anh
- Mã học viên: 2A202602805
- Nhóm: Bttention
- Candidate problem nhóm chọn: Khi cư dân gửi yêu cầu dịch vụ không khẩn cấp bằng mô tả tự do, thông tin về vị trí, thiết bị, hình ảnh hoặc mức độ ảnh hưởng có thể thiếu; bộ phận tiếp nhận phải hỏi lại và phiếu yêu cầu có thể qua nhiều đội trước khi đúng người nhận xử lý.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 vấn đề xã hội/vận hành và chọn 3 Problem Cards để trình bày. | Tạo thêm candidate cho nhóm so sánh; Card #1 đủ rõ để đi vào shortlist và được chọn làm candidate chung. |
| Pitch Problem Card | Trình bày 3 Problem Cards, nêu actor, workflow, bottleneck, impact và hướng đo. | Card #1 về phiếu yêu cầu dịch vụ cư dân được chọn làm candidate problem của nhóm. |
| Challenge bài của bạn khác | So sánh các candidate theo độ rõ của actor, khả năng tiếp cận data, metric và phạm vi có thể làm trong lab; đặc biệt cân nhắc các bài về lừa đảo, camera và phát hiện bệnh vật nuôi. | Giúp nhóm thấy candidate cư dân có workflow, handoff và boundary dễ xác định hơn trong scope hiện tại. |
| Gom trùng / cluster | Đặt Card #1 vào cụm các bài toán phải chuẩn hóa thông tin trước khi chuyển qua nhiều bên xử lý; cùng rà pattern chung của cụm này. | Cụm A làm rõ rằng pain không chỉ là “chậm”, mà là thông tin không có cấu trúc tạo vòng hỏi lại và giao lại. |
| Chọn candidate problem | Đề xuất Card #1 và làm rõ luồng cư dân → CSKH → ban quản lý/điều phối → bộ phận xử lý → cư dân xác nhận. | Nhóm chọn bài toán phiếu yêu cầu dịch vụ cư dân để tiếp tục đào sâu. |
| Validation / research | Tìm và tổng hợp pattern từ AppFolio Smart Maintenance, ServiceNow Task Intelligence và Zendesk Intelligent Triage| Nhóm xác định được pattern AI đề xuất thông tin/phân loại, con người xác nhận; không coi quote giả lập là bằng chứng thực địa. |
| Workflow nhóm | Viết current/future workflow, bổ sung Mermaid, tách Rule, AI, CSKH, điều phối, bộ phận xử lý và nhánh khẩn cấp. | Workflow thể hiện rõ hai vòng lặp hỏi bổ sung/giao lại, human boundary và fallback khi AI không đủ tin cậy. |
| Problem Statement | Chuyển mô tả ban đầu thành PS v0/v1, xác định đúng điểm kết thúc là lúc bộ phận xử lý cuối tiếp nhận và viết công thức metric. | Nhóm giới hạn impact ở khâu hoàn thiện thông tin/phân luồng, không quy toàn bộ thời gian sửa chữa tại hiện trường cho AI. |
| Rule / Workflow / Agent | Lập ma trận độ mơ hồ–độ phức tạp và so sánh ba mức trên cùng workflow. | Nhóm chọn Workflow có kiểm soát: Rule cho điều kiện cố định, AI chỉ đề xuất, CSKH/người trực xác nhận. |
| Decision | Tổng hợp các điều kiện còn thiếu: baseline T0, log phiếu ẩn danh, owner vận hành và kiểm thử cảnh báo khẩn cấp. | Nhóm chốt Not Yet thay vì khẳng định có thể triển khai AI ngay. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```
Đóng góp rõ nhất của tôi là đưa ra candidate problem được nhóm chọn, sau đó phát triển nó thành workflow trước/sau, Problem Statement v0/v1 và hướng lựa chọn Workflow có người kiểm tra. Tôi cũng giúp giữ scope ở khâu hoàn thiện thông tin và phân luồng, không biến bài toán thành một Agent tự xử lý toàn bộ dịch vụ cư dân.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm vấn đề theo các lăng kính và tìm nguồn bối cảnh. | Giúp mở rộng danh sách lên 10 candidate thuộc nhiều lĩnh vực. | Một số ý quá rộng hoặc chỉ có số liệu xã hội, chưa chứng minh bottleneck của workflow cụ thể. | Giữ các ý có actor và cách đo; bỏ ý về hết pin/trạm sạc vì chưa thấy đó là pain cần AI giải quyết. |
| Problem Card | Phản biện actor, bottleneck, metric, phương án không dùng AI và mức Rule/Workflow/Agent. | Giúp thu hẹp Card #1 vào bước hoàn thiện thông tin và chuyển phiếu đến đúng bộ phận. | Ban đầu AI dùng nhiều thuật ngữ tiếng Anh, gắn bài toán quá chặt với Vingroup và làm ranh giới Workflow/Agent chưa rõ. | Đổi “ticket” thành “phiếu yêu cầu”, mô tả các tác nhân tổng quát và chỉ chọn Workflow vì luồng xử lý đã xác định. |
| Workflow | Chuyển mô tả thành Mermaid cho trạng thái hiện tại và sau cải tiến. | Làm rõ vòng hỏi bổ sung, chuyển sai bộ phận, bước CSKH kiểm tra và fallback. | Flow ban đầu còn ngắn, khó hiểu và chưa mô tả đầy đủ việc bộ phận xử lý trả phiếu kèm lý do. | Viết lại thành 7 bước và giữ CSKH xác nhận đề xuất AI trước khi chuyển phiếu. |
| Research | Tìm các pattern và tài liệu chính thức của AppFolio Smart Maintenance, ServiceNow Task Intelligence và Zendesk Intelligent Triage. | Giúp nhóm thấy pattern chung: AI cấu trúc hóa/đề xuất, người vận hành xác nhận và hệ thống lưu feedback. | Tài liệu của nhà cung cấp không chứng minh pain hoặc hiệu quả sẽ giống nhau ở khu dân cư Việt Nam. | Chỉ dùng nguồn để rút ra pattern thiết kế; gắn nhãn quote validation là giả lập và giữ yêu cầu phải có log/validation thật nếu làm pilot. |
| Problem Statement | Phản biện 6 field v0 và viết lại thành v1 có intervention point, boundary, metric và người kiểm tra. | Gợi ý tách “thời gian đến đúng bộ phận” khỏi “thời gian sửa chữa tại hiện trường”. | Dễ biến mục tiêu kỳ vọng thành kết quả đã có hoặc gán toàn bộ chậm trễ cho AI phân luồng. | Ghi T0 là baseline cần thu, dùng công thức đo rõ ràng và giới hạn impact của AI ở các handoff trước khi đội xử lý tiếp nhận. |
| Rule / Workflow / Agent | So sánh từng mức và tạo ma trận độ mơ hồ–độ phức tạp. | Làm rõ Rule là logic cố định, AI là phần đọc đầu vào tự do, Workflow là cách điều phối các bước. | Ban đầu AI có xu hướng đề xuất Agent quá sớm và chưa phân biệt đầy đủ việc AI phát tín hiệu khẩn cấp với người trực xác nhận khẩn cấp. | Giữ Workflow là mức đề xuất; đặt Rule/AI chỉ hỗ trợ, còn CSKH/người trực giữ quyền quyết định và fallback thủ công. |
| Decision | Hỗ trợ tổng hợp các điều kiện Go/Not Yet/No-Go và câu hỏi còn thiếu. | Nhắc nhóm kiểm tra baseline, data, owner, rủi ro và phương án non-AI. | Có thể diễn giải research hoặc quote giả lập như bằng chứng đủ để Go. | Chọn Not Yet; ghi rõ validation đang là giả lập và cần log/phỏng vấn thật trước khi quyết định pilot. |

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
Khi nghe các candidate về camera, lừa đảo, vật nuôi và vận hành, tôi nhận ra candidate tốt không chỉ cần impact lớn mà còn phải có actor, workflow và cách đo đủ rõ. Tôi đã trình bày ba Problem Cards, trong đó Card #1 về phiếu yêu cầu dịch vụ cư dân được nhóm chọn để đào sâu. Đóng góp chính của tôi là biến một mô tả “phản ánh chậm” thành luồng cụ thể từ cư dân, CSKH, điều phối đến bộ phận xử lý và cư dân xác nhận. Ban đầu tôi dùng những từ như ticket, routing và Agent khá nhiều, khiến bài toán nghiêng về solution-first và khó đọc. Khi viết lại, tôi đổi ticket thành phiếu yêu cầu, tách rõ các handoff và chỉ giữ AI ở bước hỗ trợ thông tin/phân loại. Việc vẽ workflow giúp tôi thấy hai vòng lặp quan trọng là hỏi bổ sung và trả phiếu khi giao sai bộ phận. AI hữu ích khi phản biện scope, gợi ý metric, so sánh Rule/Workflow/Agent và chuyển luồng thành Mermaid. Tuy nhiên, tôi nhận ra AI có thể làm cho số liệu bối cảnh hoặc quote giả lập trông giống bằng chứng thật nếu không ghi nhãn rõ. Vì vậy tôi giữ T0 ở trạng thái chưa đo, coi các quote trong bài là mô phỏng và giới hạn impact của AI ở thời gian đến đúng bộ phận thay vì toàn bộ thời gian sửa chữa. Điều khó nhất với tôi là xác định boundary, đặc biệt ở nhánh khẩn cấp: AI chỉ phát tín hiệu, còn người trực mới xác minh và kích hoạt SOP. Tôi đồng ý với quyết định Not Yet vì nhóm chưa có log ẩn danh, owner vận hành hoặc validation thật để chứng minh Workflow tốt hơn Rule-only. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về data access, đồng thời phỏng vấn cư dân và CSKH trước khi chốt metric và mức dùng AI.
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


# Báo cáo cá nhân — 2A202604030_TranTrongDat

## 1. Thông tin học viên

- Họ tên: Trần Trọng Đạt
- MSSV: 2A202604030
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: N8
- Link repo nhóm: https://github.com/Zellsed/K5-L3B-Day02-N8-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi nhận Noon Report của tàu, tôi muốn kiểm tra nhiên liệu, vị trí và vận tốc để theo dõi hành trình, dự đoán ETA và phát hiện sai lệch | Chủ tàu, nhân viên khai thác, thuyền trưởng, máy trưởng | Noon Report được gửi định kỳ, thường mỗi ngày vào khoảng 12 giờ theo quy trình của tàu |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi tàu xếp/dỡ hàng ở cảng, tôi muốn đối chiếu báo cáo sự kiện và hợp đồng thuê tàu để xác định thời gian laytime và khoản demurrage/despatch | Chủ tàu, người thuê tàu, bộ phận khai thác, thuyền trưởng | Cần đối chiếu SOF/NOR, điều kiện thời tiết, sự cố và các điều khoản hợp đồng; chưa đo thời gian xử lý |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi làm literature review, tôi muốn tổng hợp các nghiên cứu và truy xuất bằng chứng để xác định research gap mà không phải đọc lại tất cả tài liệu | Sinh viên, nghiên cứu sinh | Ước tính từ trải nghiệm: khoảng 30 bài, mỗi bài 10–30 trang; đọc và phân tích khoảng 1–2 giờ/bài |
| 4 | Lặp lại | Khi nâng cấp một model, tôi muốn cập nhật metrics, tham số và biểu đồ vào báo cáo theo mẫu cố định để giảm thao tác sao chép thủ công | Data Scientist, nghiên cứu sinh | Theo trải nghiệm cá nhân, mỗi lần cập nhật báo cáo mất khoảng 30 phút |
| 5 | Pain từ người khác | Khi tổng hợp báo cáo nhóm, tôi muốn các phần thống nhất giọng văn và format để không phải sửa lại toàn bộ | Sinh viên làm việc nhóm | Theo trải nghiệm cá nhân, sửa báo cáo khoảng 40 trang mất khoảng 1 giờ |
| 6 | Lặp lại | Khi học nhiều môn cùng lúc, tôi muốn tổng hợp deadline bài tập, lịch kiểm tra và lịch học vào một nơi để không bỏ sót nhiệm vụ hoặc nộp bài trễ | Sinh viên | Mỗi môn có lịch giao bài và thời hạn khác nhau; cần khảo sát số lần quên hạn và thời gian kiểm tra lịch thực tế |
| 7 | Pain từ người khác | Khi làm bài tập nhóm, tôi muốn biết ai phụ trách phần nào và tiến độ ra sao để không phải liên tục nhắn hỏi, nhắc deadline hoặc chờ phần việc của nhau | Sinh viên làm việc nhóm, trưởng nhóm | Các nhóm thường trao đổi qua tin nhắn và file chung; cần đếm số lần hỏi tiến độ và thời gian chờ trong một dự án nhóm |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi lớp có thông báo từ nhiều kênh như email, nhóm chat và hệ thống học tập, tôi muốn lọc thông tin quan trọng để không bỏ lỡ thay đổi lịch học, phòng học hay hạn nộp bài | Sinh viên | Thông báo phân tán trên nhiều kênh; chưa có số liệu thực tế về số thông báo bị bỏ sót hoặc thời gian tìm lại thông tin |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý thêm các vấn đề sinh viên thường gặp ở mục #6–#8 (quản lý deadline, theo dõi tiến độ bài nhóm, lọc thông báo). Giữ lại vì dễ quan sát và xác minh, nhưng chưa coi là bằng chứng nếu chưa khảo sát thực tế.

---

## 3. Top 3 Problem Cards (CP2)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đọc báo cáo xếp/dỡ và hợp đồng để tính laytime, DEM/DES (#2) | Phải tổng hợp nhiều chứng từ và điều khoản; sai lệch có thể ảnh hưởng trực tiếp đến chi phí | Thời gian thực tế, dữ liệu hợp đồng và mức độ phức tạp của trường hợp ngoại lệ |
| 2 | Theo dõi bất thường trong Noon Report (#1) | Lặp lại hằng ngày; dữ liệu vận hành có thể kiểm tra, so sánh | Tần suất lỗi, dữ liệu lịch sử và cách phân biệt bất thường với thay đổi điều kiện biển |
| 3 | RAG đọc và đối chiếu báo cáo nghiên cứu (#3) | Cần đọc nhiều tài liệu, truy xuất bằng chứng, tổng hợp kết quả cho literature review | Chất lượng PDF, độ chính xác trích dẫn và khả năng phát hiện research gap thực sự |

### Problem Card #1 — Đọc báo cáo xếp/dỡ để tính laytime và DEM/DES

| Trường | Nội dung |
|---|---|
| Job Story | Khi tàu xếp/dỡ hàng tại cảng, tôi muốn đối chiếu các mốc sự kiện với hợp đồng thuê tàu để lập bảng laytime và tính DEM/DES chính xác |
| Actor | Nhân viên khai thác tàu, bộ phận hợp đồng/claims, chủ tàu, người thuê tàu |
| Thời điểm / bối cảnh | Trong hoặc sau khi hoàn tất xếp/dỡ, lúc lập laytime statement và đối chiếu yêu cầu thanh toán |
| Quy trình hiện tại | 1. Nhận SOF/NOR · 2. Đọc và ghi mốc sự kiện · 3. Tra điều khoản hợp đồng · 4. Phân loại thời gian được tính · 5. Lập bảng laytime và kiểm tra DEM/DES |
| Bottleneck | Bước 2–4, đọc và đối chiếu chứng từ với điều khoản: chưa đo được số phút/lần; cần phỏng vấn nhân viên khai thác |
| Impact | Dễ bỏ sót sự kiện hoặc áp dụng sai điều khoản, chậm xử lý claim và có nguy cơ phát sinh tranh chấp chi phí |
| Success metric | Baseline: cần đo thời gian lập một bảng laytime. Target đề xuất: giảm 30% thời gian; điều kiện chất lượng: kết quả khớp bảng được người phụ trách xác nhận. Cách đo: so sánh các hồ sơ có kiểm chứng |
| Phương án không dùng AI | Chuẩn hóa biểu mẫu SOF; nhân viên nhập mốc thời gian vào Excel/laytime calculator; áp dụng quy tắc cố định và kiểm tra thủ công |
| Giả thuyết về AI | OCR đọc scan/ghi tay; RAG tìm điều khoản trong các hợp đồng mà người dùng được phép truy cập; AI gợi ý phân loại sự kiện. Bộ tính theo quy tắc thực hiện phép tính, con người duyệt trường hợp tranh chấp |
| Cảm nhận nhanh | AI (RAG + LLM) + Rule + Workflow. |

```text
HIỆN TẠI — thời gian cần đo thực tế

[1 Nhận SOF/NOR] → [2 Đọc, ghi mốc sự kiện] → [3 Tra hợp đồng] ← BOTTLENECK
→ [4 Phân loại thời gian] ← BOTTLENECK → [5 Tính DEM/DES và kiểm tra]
```

### Problem Card #2 — Theo dõi và kiểm tra Noon Report

| Trường | Nội dung |
|---|---|
| Job Story | Khi tàu gửi Noon Report, tôi muốn kiểm tra nhiên liệu, vị trí, vận tốc và tiến độ để phát hiện sai lệch và cập nhật ETA |
| Actor | Nhân viên khai thác, chủ tàu, thuyền trưởng, máy trưởng |
| Thời điểm / bối cảnh | Trong hành trình, khi tiếp nhận báo cáo định kỳ hằng ngày |
| Quy trình hiện tại | 1. Tàu gửi báo cáo · 2. Nhân viên ghi nhận thông số · 3. So với báo cáo trước/kế hoạch · 4. Xác minh sai lệch · 5. Cập nhật theo dõi và ETA |
| Bottleneck | Bước 3–4, đối chiếu nhiều thông số và xác minh biến động: chưa đo được phút/báo cáo |
| Impact | Tốn thao tác lặp lại; có thể chậm phát hiện lỗi dữ liệu, biến động nhiên liệu hoặc thay đổi ETA |
| Success metric | Baseline: cần đo thời gian kiểm tra/báo cáo và tỷ lệ cảnh báo đúng. Target đề xuất: giảm 30% thời gian mà không tăng cảnh báo sai đáng kể. Cách đo: so sánh trên báo cáo lịch sử được xác minh |
| Phương án không dùng AI | Form chuẩn, kiểm tra giá trị hợp lệ, dashboard và cảnh báo theo ngưỡng cố định |
| Giả thuyết về AI | Phát hiện bất thường trên dữ liệu vận hành kết hợp lịch sử, tốc độ, thời tiết và trạng thái tàu; nhân viên xác minh trước khi kết luận |
| Cảm nhận nhanh | Rule + Workflow + ML|

```text
HIỆN TẠI — báo cáo định kỳ hằng ngày, phút xử lý cần đo

[1 Nhận Noon Report] → [2 Nhập thông số] → [3 Đối chiếu] ← BOTTLENECK
→ [4 Xác minh sai lệch] → [5 Cập nhật ETA]
```

### Problem Card #3 — RAG đọc và tổng hợp báo cáo nghiên cứu

| Trường | Nội dung |
|---|---|
| Job Story | Khi thực hiện literature review, tôi muốn tìm, đối chiếu và trích dẫn thông tin từ nhiều bài báo bằng RAG để tổng hợp kết quả và xác định hướng nghiên cứu còn thiếu |
| Actor | Sinh viên, nghiên cứu sinh, người thực hiện literature review |
| Thời điểm / bối cảnh | Khi chuẩn bị đề cương, tổng quan tài liệu hoặc nghiên cứu mô hình mới |
| Quy trình hiện tại | 1. Tìm và tải bài báo · 2. Đọc từng bài · 3. Ghi phương pháp/kết quả · 4. So sánh các bài · 5. Viết tổng quan, kiểm tra nguồn |
| Bottleneck | Bước 2–4, đọc và đối chiếu nhiều bài: ước tính 60–120 phút/bài từ trải nghiệm cá nhân, chưa đo bằng nhật ký thời gian |
| Impact | Tốn nhiều giờ đọc lặp lại và dễ bỏ sót nghiên cứu có liên quan hoặc trích dẫn sai nguồn |
| Success metric | Baseline: 60–120 phút để đọc/phân tích một bài (ước tính). Target đề xuất: dưới 30 phút cho bản trích xuất sơ bộ/bài; chất lượng: trích dẫn phải truy ngược được tài liệu và vị trí gốc. Cách đo: thử trên 5 bài rồi đối chiếu thủ công |
| Phương án không dùng AI | Bảng literature matrix cố định; đọc abstract → methodology → result → conclusion, gắn ghi chú/trích dẫn bằng Zotero |
| Giả thuyết về AI | RAG truy xuất đoạn liên quan từ bộ PDF được phép sử dụng, tóm tắt phương pháp/kết quả và dẫn chứng theo trang; người nghiên cứu tự đánh giá research gap, không coi câu trả lời AI là kết luận đã xác minh |
| Cảm nhận nhanh | Workflow + RAG |

```text
HIỆN TẠI — khoảng 60–120'/bài đọc (ước tính)

[1 Tìm PDF] → [2 Đọc từng bài] ← BOTTLENECK → [3 Ghi kết quả]
→ [4 Đối chiếu nhiều bài] ← BOTTLENECK → [5 Viết tổng quan]
```

### Card muốn pitch nhất

Card #1 — Đọc báo cáo xếp/dỡ để tính laytime và DEM/DES.

**Câu hỏi muốn nhóm phản biện:** Khi hệ thống RAG đọc SOF/NOR và hợp đồng thuê tàu, làm thế nào để bảo đảm AI chỉ truy xuất tài liệu đúng quyền của từng bên (chủ tàu, người thuê tàu), đồng thời tránh lộ thông tin hợp đồng qua câu trả lời?

### AI phản biện (vai "PM hoài nghi")

| Card | Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|---|
| #1 | RAG trích được điều khoản không đồng nghĩa diễn giải đúng trách nhiệm và phép tính DEM/DES | Đồng ý | Tách bước trích xuất, tra điều khoản, bộ tính theo quy tắc và duyệt của nhân viên |
| #1 | Chứng từ/hợp đồng của các bên có quyền truy cập khác nhau; RAG có thể làm lộ dữ liệu | Đồng ý | Bổ sung kiểm soát quyền trước retrieval, phân quyền theo tổ chức/chuyến tàu/tài liệu |
| #2 | Nhiên liệu tăng không hẳn là lỗi; còn phụ thuộc thời tiết và trạng thái vận hành | Đồng ý | Cảnh báo để xác minh thay vì tự kết luận sai lệch |
| #3 | RAG có thể bỏ sót hoặc trích dẫn sai bài báo | Đồng ý | Bắt buộc dẫn nguồn gốc, kiểm tra độ chính xác trước khi đưa vào literature review |
| #3 | Đọc theo cấu trúc và bảng tổng quan có thể đã tiết kiệm thời gian mà không cần AI | Đồng ý một phần | Giữ phương án không AI làm baseline để kiểm chứng giá trị RAG |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**


**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**


**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**


**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**


**6.5. Điều khó nhất khi viết Problem Statement là gì?**


**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**


**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-

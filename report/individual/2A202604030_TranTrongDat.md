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
| 1 | Đọc báo cáo xếp/dỡ và hợp đồng để tính laytime, DEM/DES (#2) | Phải tổng hợp nhiều chứng từ và điều khoản; sai lệch có thể ảnh hưởng trực tiếp đến chi phí | Thời gian thực tế, dữ liệu hợp đồng và mức độ phức tạp của trường hợp ngoại lệ? |
| 2 | Chuẩn hóa format và giọng văn báo cáo nhóm (#5) | Các thành viên viết khác định dạng, bố cục và giọng văn; theo trải nghiệm mất khoảng 60 phút để sửa báo cáo 40 trang | Làm thế nào để AI chuẩn hóa báo cáo mà không làm thay đổi ý nghĩa hoặc mất thông tin quan trọng? |
| 3 | RAG đọc và đối chiếu báo cáo nghiên cứu (#3) | Cần đọc nhiều tài liệu, truy xuất bằng chứng, tổng hợp kết quả cho literature review | Chất lượng PDF, độ chính xác trích dẫn và khả năng phát hiện research gap thực sự? |

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

### Problem Card #2 — Chuẩn hóa định dạng và giọng văn báo cáo nhóm

| Trường | Nội dung |
|---|---|
| Job Story | Khi tổng hợp báo cáo từ nhiều thành viên, tôi muốn thống nhất format, bố cục và giọng văn để không phải sửa lại toàn bộ bài |
| Actor | Sinh viên làm việc nhóm, trưởng nhóm, người tổng hợp báo cáo |
| Thời điểm / bối cảnh | Khi ghép các phần do thành viên viết thành báo cáo chung trước khi nộp |
| Quy trình hiện tại | 1. Nhận bài từ các thành viên · 2. Ghép nội dung · 3. Kiểm tra format và giọng văn · 4. Sửa các phần chưa thống nhất · 5. Rà soát và nộp báo cáo |
| Bottleneck | Bước 3–4, rà soát và chỉnh sửa format, giọng văn: theo trải nghiệm cá nhân, khoảng 60 phút cho báo cáo 40 trang |
| Impact | Tốn thời gian tổng hợp, dễ bỏ sót lỗi định dạng hoặc làm sai lệch ý của thành viên khi chỉnh sửa |
| Success metric | Baseline: khoảng 60 phút/báo cáo 40 trang (trải nghiệm cá nhân). Target đề xuất: dưới 30 phút; chất lượng: giữ nguyên ý và thông tin của bản gốc. Cách đo: bấm giờ và đối chiếu trước/sau |
| Phương án không dùng AI | Thống nhất template, style và quy tắc trình bày từ đầu; dùng chức năng Styles trong Word hoặc công cụ định dạng tự động |
| Giả thuyết về AI | AI hỗ trợ chuẩn hóa giọng văn, tiêu đề và cách trình bày từ các phần báo cáo khác nhau; người tổng hợp đối chiếu với bản gốc để tránh thay đổi ý hoặc mất thông tin |
| Cảm nhận nhanh | Workflow + AI hỗ trợ chỉnh sửa |

```text
HIỆN TẠI — khoảng 60'/báo cáo 40 trang (trải nghiệm cá nhân)

[1 Nhận bài] → [2 Ghép nội dung] → [3 Kiểm tra format/giọng văn] ← BOTTLENECK
→ [4 Chỉnh sửa thống nhất] ← BOTTLENECK → [5 Rà soát và nộp]
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
| #2 | AI chuẩn hóa giọng văn và định dạng có thể làm sai ý hoặc bỏ sót thông tin gốc | Đồng ý | Yêu cầu đối chiếu với bản gốc và chỉ chấp nhận chỉnh sửa sau khi người tổng hợp kiểm tra |
| #3 | RAG có thể bỏ sót hoặc trích dẫn sai bài báo | Đồng ý | Bắt buộc dẫn nguồn gốc, kiểm tra độ chính xác trước khi đưa vào literature review |
| #3 | Đọc theo cấu trúc và bảng tổng quan có thể đã tiết kiệm thời gian mà không cần AI | Đồng ý một phần | Giữ phương án không AI làm baseline để kiểm chứng giá trị RAG |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm | Xây dựng quy trình trước/sau (CP5). | Xác định bottleneck và vị trí AI can thiệp. |
| Problem Statement | Xây dựng Problem Statement v0. | Làm rõ vấn đề, metric và boundary. |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Diễn đạt lại vấn đề, gợi ý thêm 3 ý. | Viết đúng lại các thuật ngữ chuyên môn |  | Giữ các ý phù hợp, cần kiểm chứng. |
| CP2 Problem Card | Hỗ trợ viết và phản biện 3 card. | Làm rõ bottleneck và metric. | Một số nhận định chưa kiểm chứng. | Điều chỉnh theo trải nghiệm cá nhân. |
| CP4 Research | | | | |
| CP5 Quy trình | Rà soát quy trình trước/sau. | Xác định vai trò AI và con người. | AI tự động hóa toàn bộ quy trình | Giữ bước chọn lọc và kiểm tra thủ công. |
| CP5–6 Problem Statement | Đề xuất quy trình trước/sau và Problem Statement. | Gợi ý metrics và boundary. |  | Định hướng metrics theo Grounding, Correctness và Relevance. |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Có nhiều vấn đề liên quan đến tổng hợp thông  
tin và tăng liên kết hoặc giảm thời gian   thay đổi giữa các tasks.
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**  
Ban đầu có một số ý xuất phát từ việc ứng dụng RAG để tổng hợp thông tin thay vì bắt đầu từ vấn đề. Lúc đó nhóm vấn giữ nguyên vấn đề nhưng thay đổi hướng thành tập trung vào vấn đề của người dùng rồi mới xem xét liệu các ứng dụng đó có là 
một phương pháp khả thi hay không.  
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi có đổi ý và giảm bớt quan tâm đối với các chủ đề liên quan đến chuỗi chung ứng đề phù hợp hơn với background của cả team.  

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**  
Khi vào nghiên cứu khác với suy nghĩ ban đầu là tìm nội dung phù hợp thì thứ người nghiên cứu thực sự quan tâm là các thí nghiệm và kết luận trong bài. Sử dụng nội dung phù hợp ở mô tả có thể mang ý nghĩa tổng quan hơi rộng.  

**6.5. Điều khó nhất khi viết Problem Statement là gì?**  
Phần problems người dùng đã được bàn trong pitch nhưng đến phần metrics đánh giá cần cân nhắc thêm về phương pháp để phù hợp với bài toán. Ở đây ước chừng dưới 30 phút trên bài không phải 1 bài 30 phút mà tính trung bình trên tổng số bài được input kể cả bài được đánh giá không đáng đọc. Tuy nhiên việc đọc thêm các bài này còn phụ thuộc và nhu cầu người dùng.  


**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**  
Nếu làm lại, tôi sẽ đề xuất kiểm chứng thời gian sàng lọc thực tế sớm hơn, thay vì chỉ dựa trên ước lượng 60–120 phút/bài. Tôi cũng sẽ phản biện kỹ hơn về khả năng AI đánh giá sai mức độ liên quan, đặc biệt khi bỏ sót những bài báo quan trọng, và yêu cầu so sánh với phương án không dùng AI.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.  
Nhóm lựa chọn vấn đề người nghiên cứu mất nhiều thời gian đọc các bài báo chỉ để xác định bài nào nên dành thêm thời gian để đọc cũ. Quy trình hiện tại chủ yếu dựa vào việc đọc và ghi chú thủ công, trong khi quy trình đề xuất sử dụng RAG và AI để trích xuất, tóm tắt và phân loại tài liệu theo mức độ liên quan. Hiệu quả được đánh giá thông qua thời gian sàng lọc, Grounding, Correctness và Relevance, nhằm bảo đảm vừa tiết kiệm thời gian vừa hạn chế sai sót điều quan trọng trong liêm chính học thuật. Boundary của hệ thống là không được tạo thông tin hoặc trích dẫn thiếu căn cứ và không thay người nghiên cứu đưa ra kết luận học thuật. Mức can thiệp AI tập trung vào tự động hóa việc xử lý thông tin và đề xuất mức độ ưu tiên đọc, còn con người chịu trách nhiệm kiểm chứng và đánh giá chuyên sâu đối với các bài được AI sàng lọc sẵn. Cuối cùng, người nghiên cứu ưu tiên đọc những bài có độ liên quan cao, cân nhắc các bài liên quan trung bình và tạm bỏ qua những bài ít liên quan.

---

## 7. Tài liệu tham khảo

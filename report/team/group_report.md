# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: N8
- Thành viên: xem `TEAM.md` (Vũ Đình Huy, Quách Ngọc Huy, Khương Hoàng Nguyên, Trần Trọng Đạt)
- Candidate problem được chọn (1 câu): Khi sinh viên/nghiên cứu sinh phải đọc nhiều bài báo hoặc tài liệu dài, họ mất khoảng 60–120 phút mỗi bài (ước lượng, chưa bấm giờ) chỉ để biết bài đó có đáng đọc kỹ hay không.
- Quyết định cuối: **Not Yet** (đề xuất, nhóm xác nhận ở mục 8)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

|   # | Người đưa ra        | Candidate (Job Story ngắn)                                                                                                                                   | Actor                                                      | Bottleneck                                                               | Câu hỏi phản biện nhận được (ai hỏi)                                                                      |
| --: | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
|   1 | Vũ Đình Huy         | Khi ôn thi, muốn gom ý chính từ slide, ghi chú, giáo trình để khỏi đọc lại toàn bộ                                                                           | Sinh viên ôn thi cuối kỳ                                   | Viết lại thành bản tóm tắt: ~240 phút trong 10/30 giờ ôn tập (ước lượng) | Bản tóm tắt "đủ tốt" đo thế nào? 10 giờ là mỗi môn hay cả kỳ?                                             |
|   2 | Vũ Đình Huy         | Khi làm bài nhóm, muốn biết ai làm phần nào, đến đâu để khỏi nhắn hỏi từng người                                                                             | Thành viên nhóm, đặc biệt trưởng nhóm                      | Chờ trả lời + đọc lại ~100 tin/ngày: ~35 phút/ngày (ước lượng)           | Bao nhiêu trong 100 tin/ngày thật sự là hỏi tiến độ? Bảng việc chung đã đủ chưa?                          |
|   3 | Vũ Đình Huy         | Khi đọc bài báo khoa học dài, muốn nắm nhanh vấn đề, phương pháp, kết luận để biết có nên đọc kỹ không                                                       | Sinh viên, nghiên cứu sinh                                 | Đọc toàn bộ bài: 60–120 phút/bài                                         | Mỗi kỳ phải đọc bao nhiêu bài? Tóm tắt AI có bịa/bỏ sót kết luận không?                                   |
|   4 | Quách Ngọc Huy      | Khi chưa có task mới, muốn biết việc nào có thể chủ động làm để tạo giá trị, khỏi ngồi chờ                                                                   | Software Engineer (và team)                                | Xác định việc nên chủ động làm                                           | Pain chính là thiếu task, thiếu thông tin nhu cầu của team, hay thiếu cơ chế tự xác định việc có giá trị? |
|   5 | Quách Ngọc Huy      | Khi có thời gian rảnh, muốn biết nên học gì trước để phù hợp công việc và định hướng                                                                         | Software Engineer                                          | Xác định nên học gì và theo thứ tự nào                                   | Khó nằm ở chọn chủ đề hay chọn thứ tự học?                                                                |
|   6 | Quách Ngọc Huy      | Khi cần dùng lại thông tin đã đọc/trao đổi, muốn tìm lại nhanh để khỏi nghiên cứu lại từ đầu                                                                 | Software Engineer                                          | Tìm đúng thông tin giữa chat/file/browser/ghi chú                        | Thông tin nằm chủ yếu ở đâu, tần suất thực tế bao nhiêu?                                                  |
|   7 | Khương Hoàng Nguyên | Khi đánh giá nhiều lần thử nghiệm mô hình, muốn liên kết config, dữ liệu, metric để chọn mô hình có căn cứ                                                   | Người phụ trách thử nghiệm/đánh giá ML/AI                  | Lục config + đối chiếu log: ~60 phút/lần đánh giá                        | 60 phút có phải mức điển hình? "Lục config" và "đối chiếu log" có tách được thành hai bước?               |
|   8 | Khương Hoàng Nguyên | Khi nhận code/dữ liệu/model từ đồng đội, muốn biết điều kiện môi trường và schema I/O để tích hợp trơn tru                                                   | Người tích hợp và người bàn giao module                    | Làm rõ schema + debug: ~90 phút/lần bàn giao                             | Metric 90 → 30 phút có tính thời gian chờ phản hồi không? Có ca bàn giao thật làm bằng chứng chưa?        |
|   9 | Khương Hoàng Nguyên | Khi theo dõi tiến độ, muốn biết chính xác việc nào đang bị blocker để điều phối kịp thời                                                                     | Trưởng nhóm; cả nhóm chịu ảnh hưởng                        | Phát hiện blocker muộn: ~1.440 phút (24 giờ)/lần                         | Blocker bắt đầu, được phát hiện, được xử lý tính từ thời điểm nào?                                        |
|  10 | Trần Trọng Đạt      | Khi làm literature review, muốn đọc và tìm ra research gap từ ~30 báo cáo dài 10–30 trang                                                                    | Nghiên cứu sinh                                            | Đọc, trích xuất, phân tích: 1–2 giờ/bài                                  |                                                                                                           |
|  11 | Trần Trọng Đạt      | Khi làm bài nhóm, muốn thống nhất format, quy tắc, giọng văn để khỏi sửa lại toàn bộ lúc tổng hợp                                                            | Sinh viên trong nhóm                                       | Sửa báo cáo tổng hợp ~40 trang: ~1 giờ                                   |                                                                                                           |
|  12 | Trần Trọng Đạt      | Khi tàu dỡ hàng ở cảng, muốn tổng hợp báo cáo thuyền trưởng, thời tiết, máy móc và điều khoản hợp đồng để xác định ai chịu trách nhiệm cho thời gian trì trệ | Chủ tàu, bộ phận khai thác, thuyền trưởng, người nhận hàng | Tổng hợp thông tin từ hợp đồng và báo cáo hiện trường (chưa có số phút)  |                                                                                                           |

### 2.2. Cluster

| Cluster                                             | Các candidate                                                                                                                                                             | Pattern chung                                                                                                                                                                                                    |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A. Đọc, tổng hợp, truy xuất thông tin rải rác       | #1 (tổng hợp ôn thi), #3 (đọc bài báo dài), #6 (tìm lại thông tin cũ), #7 (liên kết config/log/metric), #10 (literature review), #12 (tổng hợp hồ sơ dỡ hàng và hợp đồng) | Thông tin nằm ở nhiều nguồn/định dạng; người làm phải đọc lại hoặc đối chiếu thủ công trước khi ra được kết luận hay quyết định. Thời gian mất nhiều nhất ở bước đọc và tổng hợp, không phải bước ra quyết định. |
| B. Phối hợp nhóm: trạng thái, bàn giao, chuẩn chung | #2 (theo dõi tiến độ bài nhóm), #8 (điều kiện môi trường/schema khi bàn giao), #9 (phát hiện blocker muộn), #11 (thống nhất format/giọng văn)                             | Kỳ vọng và trạng thái công việc không được chia sẻ theo cách chuẩn nên phải hỏi qua chat, phát hiện muộn, hoặc sửa dồn vào cuối. Pain rơi vào người nhận/điều phối chứ không phải người làm ra đầu ra.           |
| C. Thiếu định hướng ưu tiên khi không có chỉ dẫn rõ | #4 (không biết chủ động làm gì), #5 (không biết nên học gì trước)                                                                                                         | Có thời gian và năng lực nhưng thiếu tiêu chí để chọn việc nên làm. Cluster này chỉ đến từ một người (Quách Ngọc Huy), chưa có bằng chứng từ thành viên khác.                                                    |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian sinh viên/kỹ sư mất cho việc tìm, tổng hợp thông tin và phối hợp nhóm, để dồn thời gian vào việc tạo giá trị
├── Opportunity A: Người làm cần nắm được phần cốt lõi của nhiều nguồn dài/rải rác mà không phải đọc hoặc lục lại toàn bộ
│   ├── Cần biết nhanh một tài liệu có đáng đọc kỹ không (#3, #10)   <-- candidate được chọn
│   ├── Cần gom ý chính từ nhiều nguồn thành một bản dùng được (#1, #12)
│   └── Cần tìm lại đúng thông tin/kết quả đã có, kèm căn cứ (#6, #7)
├── Opportunity B: Cả nhóm cần biết trạng thái công việc, điều kiện bàn giao và chuẩn chung ngay từ đầu, không phải hỏi từng người hay sửa dồn cuối
│   ├── Cần thấy ai làm gì, đến đâu, đang vướng gì sớm (#2, #9)
│   ├── Cần biết rõ điều kiện/giới hạn của thứ mình nhận từ người khác (#8)
│   └── Cần chuẩn chung về format, giọng văn trước khi ghép bài (#11)
└── Opportunity C: Cá nhân cần tiêu chí để chọn việc đáng làm/đáng học khi không có chỉ dẫn rõ (#4, #5)
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Dashboard/bảng tracking tiến độ" và "bảng tracking config/log" là công cụ, không phải nhu cầu; nhu cầu thật là thấy trạng thái và truy được căn cứ (đã đưa vào B và A).
- "AI tóm tắt bài báo/slide" là giải pháp; nhu cầu thật là nắm nhanh phần cốt lõi mà vẫn đáng tin (đã đưa vào A).
- "Template tóm tắt", "template báo cáo", "Roadmap kỹ năng", "Backlog việc chủ động" đều là cách giải, chưa phải pain.
- "Chatbot trả lời câu hỏi lặp của lớp" (scan #7 của Huy Vũ) là giải pháp và chưa vào top 3, nên không đưa lên cây.
- "Contract/schema bắt buộc, README bàn giao" là phương án không dùng AI; nhu cầu thật là biết điều kiện sử dụng khi nhận bàn giao (đã đưa vào B).

### 2.4. Chấm điểm shortlist (1–5)

Bản nháp để nhóm thảo luận và chốt. Với "So sánh được No AI/Rule/Workflow/Agent": 5 = có đủ phương án khả thi ở cả 4 mức để so sánh có ý nghĩa; thấp hơn khi một mức đã đủ rõ ràng hoặc các mức khó phân biệt.

| Candidate                                                           | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |   Tổng |
| ------------------------------------------------------------------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | -----: |
| S1. Đọc nhanh tài liệu dài để quyết định có đọc kỹ không (#3 + #10) |        5 |            5 |                  3 |              4 |           4 |                                      4 |                5 | **30** |
| S3. Tổng hợp slide/ghi chú để ôn thi (#1)                           |        4 |            5 |                  3 |              5 |           3 |                                      4 |                5 | **29** |
| S2. Theo dõi tiến độ, trạng thái bài nhóm (#2 + #9)                 |        4 |            4 |                  3 |              3 |           4 |                                      3 |                5 | **26** |

**Candidate được chọn:** S1. Khi sinh viên/nghiên cứu sinh phải đọc nhiều bài báo hoặc tài liệu dài, họ mất khoảng 60–120 phút mỗi bài chỉ để biết bài đó có đáng đọc kỹ hay không.

**Vì sao chọn:**

- Điểm cao nhất (30/35), và là candidate duy nhất do hai thành viên nêu độc lập (Huy Vũ #3 và Đạt #10), nên pain có nhiều khả năng là chung chứ không phải riêng một người.
- Bottleneck nằm ở một bước cụ thể (đọc toàn bộ bài chỉ để quyết định), dễ bấm giờ và dễ kiểm chứng với bạn học ở CP4.
- Cả nhóm đều là sinh viên/nghiên cứu sinh nên hiểu domain.

**Vì sao loại các candidate còn lại:**

- **S3 (tổng hợp ôn thi, 29):** impact lớn nhất (10/30 giờ ôn tập, khoảng 33%) nhưng chỉ một người nêu, theo mùa thi nên khó kiểm chứng sớm, và chất lượng bản tóm tắt khó đo nên kém vừa sức lab. Cùng cluster A, nên là hướng mở rộng nếu S1 đứng vững.
- **S2 (tiến độ bài nhóm, 26):** bottleneck chưa tách được (100 tin/ngày chưa phân biệt tin hỏi tiến độ với tin trao đổi nội dung); chính Huy Vũ ghi "No AI hoặc Rule có thể đã đủ".
- **Cluster C (#4, #5):** chỉ một người nêu, bottleneck và impact còn định tính, chưa có số phút.
- **#7, #8:** đặc thù người làm ML/AI, chỉ một thành viên gặp, khó kiểm chứng với bạn học ngoài nhóm.
- **#11, #12:** #11 chưa có bằng chứng ngoài một người; #12 cần kiến thức hợp đồng hàng hải mà cả nhóm khó kiểm chứng trong một buổi lab.

**Xử lý bất đồng (nếu có):** S1 chỉ hơn S3 một điểm (30 so với 29), chênh lệch này nằm trong sai số chấm. Tiêu chí phân xử đề xuất: (1) candidate nào có nhiều người độc lập cùng gặp hơn, (2) candidate nào kiểm chứng được nhanh hơn trong một buổi. Cả hai đều nghiêng về S1. Nếu nhóm không đồng ý, ghi lại ý kiến khác ở đây.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định                                                                                                                                  | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | ----------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 | Sinh viên/nghiên cứu sinh phải đọc nhiều bài dài mỗi kỳ (đủ nhiều để việc tiết kiệm thời gian đáng kể).                                   | Value                                              |                5 |                      2 | Có                |
|   2 | Bước đọc toàn bộ chỉ để quyết định có đọc kỹ hay không thực sự mất khoảng 60–120 phút/bài.                                                | Value                                              |                5 |                      2 | Có                |
|   3 | Phần đáng kể các bài đọc cuối cùng bị loại hoặc chỉ đọc một phần, nên việc quyết định sớm tiết kiệm được thời gian.                       | Value                                              |                4 |                      1 | Có                |
|   4 | Cách không dùng AI (đọc 3 lượt: abstract → hình/bảng → kết luận, kèm khung ghi chú cố định) chưa đủ để đưa thời gian về dưới 15 phút/bài. | Value                                              |                5 |                      1 | Có                |
|   5 | Một bản tóm tắt (vấn đề, phương pháp, kết luận) đủ đúng để quyết định, không bịa hoặc bỏ sót kết luận chính.                              | Feasibility                                        |                5 |                      2 | Có                |
|   6 | Người dùng sẽ tin và dùng bản tóm tắt nếu luôn có bước đối chiếu với abstract và kết luận gốc.                                            | Usability                                          |                4 |                      1 | Sau               |

_Lưu ý: điểm "Đã có bằng chứng" dựa trên báo cáo cá nhân của Huy Vũ và Đạt (đều là ước lượng của bản thân) và research ở mục 3.3; chưa có bấm giờ hay phỏng vấn thật._

**Giả định nhóm kiểm chứng trong buổi này:** #1, #2, #3, #4 và #5 (quan trọng cao, bằng chứng thấp). #6 để sau khi có bản thử.

### 3.2. Kiểm chứng

**Cách đã dùng:** Chưa phỏng vấn và chưa bấm giờ. Nhóm mới tổng hợp tín hiệu từ hai báo cáo cá nhân (Huy Vũ, Đạt) và research công cụ có sẵn. Kế hoạch kiểm chứng (cần làm trước CP6, hoặc ghi rõ là chưa làm): phỏng vấn nhanh 2–3 bạn học theo Mom Test và bấm giờ 3 bài thật. Các nội dung dưới đây là **tín hiệu và kế hoạch**, chưa phải bằng chứng đã xác nhận.

**Interview snapshot** (điền sau khi phỏng vấn; hiện để trống có chủ đích, không điền số liệu giả)

| Trường                                            | Nội dung                                                                                                          |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | Chưa thực hiện. Đề xuất: 1 sinh viên làm tiểu luận/đồ án, 1–2 nghiên cứu sinh hoặc bạn đang làm literature review |
| Câu nói đáng nhớ nhất (nguyên văn)                | Chưa có dữ liệu                                                                                                   |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Chưa có dữ liệu                                                                                                   |
| Hiện đang xử lý bằng cách nào (workaround)?       | Giả định: đọc abstract rồi đọc lướt kết luận; cần kiểm chứng                                                      |
| Mất bao lâu, bao lần?                             | Chưa đo được. Tự ước lượng: 60–120 phút/bài (Huy Vũ), 1–2 giờ/bài (Đạt)                                           |
| Insight / opportunity rút ra                      | Cần tách thời gian bước "quyết định đọc kỹ" khỏi bước "đọc và trích xuất để dùng" (số của Đạt có thể gộp cả hai)  |

**Câu hỏi nên dùng để phỏng vấn (hỏi hành vi đã xảy ra, không hỏi ý tưởng):**

1. Lần gần nhất bạn phải đọc một bài báo hoặc tài liệu dài là khi nào, để làm gì?
2. Bạn đã làm gì từ lúc tải bài về đến lúc quyết định bài đó có dùng được hay không?
3. Lần đó bạn mất khoảng bao lâu, và có bấm giờ hay chỉ nhớ?
4. Trong số bài bạn đã đọc kỳ trước, bao nhiêu bài cuối cùng không dùng đến?
5. Bạn đã thử cách nào để đọc nhanh hơn chưa, kết quả ra sao?
6. Khi bạn bỏ sót hoặc hiểu sai một bài, chuyện đó đã xảy ra ra sao?

**Tổng hợp:**

| Nguồn                      | Số người / số mẫu | Tín hiệu xác nhận                                                  | Tín hiệu phản bác                                                                               |
| -------------------------- | ----------------: | ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| Báo cáo cá nhân Huy Vũ     |                 1 | 1 bài 20–30 trang, 3–4 phút/trang, tức 60–120 phút/bài             | Đây là ước lượng, chưa bấm giờ; chính Huy Vũ chưa biết mỗi kỳ phải đọc bao nhiêu bài            |
| Báo cáo cá nhân Đạt        |                 1 | Literature review cần ít nhất ~30 bài dài 10–30 trang, 1–2 giờ/bài | Con số 1–2 giờ gồm đọc và trích xuất phân tích, chưa tách riêng bước quyết định đọc kỹ          |
| Phương án không AI đã biết |                 — | —                                                                  | Đọc theo 3 lượt (abstract → hình/bảng → kết luận) có thể đã đưa thời gian xuống nhiều; chưa thử |
| Phỏng vấn bạn học          |                 0 | Chưa có                                                            | Chưa có                                                                                         |
| Bấm giờ thực tế            |                 0 | Chưa có                                                            | Chưa có                                                                                         |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- Thu hẹp từ "đọc nhanh hơn" sang "quyết định có đọc kỹ hay không", vì đây mới là bước nhóm có thể đo và là bottleneck chung của hai người.
- Giữ 60–120 phút/bài ở dạng giả thuyết cần bấm giờ, không dùng làm baseline chính thức.
- Thêm giả định #4: phương án không AI phải được thử trước, để tránh nhảy sang AI sớm.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link                                                                                                                            | Giải bước nào trong quy trình?                                                       | Điểm mạnh                                                                                           | Khoảng trống / rủi ro                                                                                                                                                                                                                                                       | Bài học cho nhóm                                                                                                   |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Semantic Scholar TLDR    | https://www.semanticscholar.org/product/tldr                                                                                    | Bước quyết định có đọc kỹ không: hiển thị tóm tắt một câu ngay trên kết quả tìm kiếm | Tóm tắt do mô hình tạo (mục tiêu và kết quả chính) và giúp quyết định bài nào đưa vào danh sách đọc | Chỉ một câu; theo bài tin tức trên The Batch, mô hình chỉ xét abstract, phần mở đầu và kết luận, nên không thay được việc nắm phương pháp. Chỉ có với bài trong kho của Semantic Scholar, không nhận tài liệu tự đưa vào                                                    | Quyết định "đọc kỹ hay không" có thể dựa trên abstract + mở đầu + kết luận, đúng với cách đối chiếu nhóm định dùng |
| Elicit                   | https://libguides.bcu.ac.uk/generativeAI/data-extraction và https://www.casrai.org/dictionary/term/elicit-ai-research-assistant | Tìm bài, tóm tắt và trích xuất dữ liệu vào bảng so sánh nhiều bài                    | Trích xuất dữ liệu từ PDF tự tải lên vào bảng; hữu ích cho literature review                        | Hướng dẫn thư viện BCU nêu bản miễn phí giới hạn và chỉ bản trả phí mới có tóm tắt và xuất csv/bib. Một nghiên cứu khả thi được CASRAI dẫn lại cho biết Elicit không trích được dữ liệu chỉ có trong hình/bảng và nên dùng như người rà thứ hai, không thay hoàn toàn người | Hình/bảng là điểm yếu chung; phải giữ bước con người đối chiếu và đánh dấu phần chưa đọc được                      |
| NotebookLM (Google)      | https://www.casrai.org/guides/notebooklm-for-research-workflows                                                                 | Tóm tắt và hỏi đáp trên bộ tài liệu tự tải lên                                       | Câu trả lời bám vào tài liệu đã tải, có trích dẫn tới đoạn gốc trong nguồn                          | Trích dẫn chỉ trỏ tới đoạn trong file đã tải, không có thông tin thư mục (DOI, tạp chí); không biết gì ngoài nguồn đã đưa vào                                                                                                                                               | Mẫu "chỉ dùng nguồn người dùng đưa vào + trích dẫn về đoạn gốc" phù hợp trực tiếp với boundary của nhóm            |

Ghi chú: thông tin về các công cụ lấy từ trang sản phẩm và hướng dẫn của bên thứ ba; nhóm **chưa tự thử** để kiểm tra độ chính xác. Gói miễn phí và giới hạn có thể đã thay đổi.

**Nhận xét sau research:**

- Việc tóm tắt bài báo bằng AI đã có sẵn từ nhiều công cụ; nhóm không cần và không nên tự xây công cụ mới.
- Khoảng trống còn lại là **quy trình quanh công cụ**: bước đối chiếu bắt buộc với abstract và kết luận gốc, đánh dấu phần hình/bảng chưa đọc được, và đo thời gian quyết định. Cả ba công cụ đều nhấn mạnh người dùng phải kiểm lại.
- Vì vậy hướng phù hợp là dùng công cụ có sẵn trong một **workflow bán thủ công** có con người kiểm tra, không phải agent tự đọc và tự quyết.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
[1 Tìm và tải bài: ~10']
          ↓
[2 Đọc toàn bộ bài: 60–120']  <-- BOTTLENECK
          ↓
[3 Ghi lại vấn đề, phương pháp, kết luận: ~20']
          ↓
[4 Quyết định có đọc kỹ hay bỏ: ~5']
```

| Bước | Actor                       | Input           | Output                                 | Thời gian / tần suất                     | Ghi chú                                                      |
| ---: | --------------------------- | --------------- | -------------------------------------- | ---------------------------------------- | ------------------------------------------------------------ |
|    1 | Sinh viên / nghiên cứu sinh | Chủ đề, từ khóa | File PDF của bài                       | ~10 phút/bài (ước lượng)                 | Mỗi bài mới                                                  |
|    2 | Sinh viên / nghiên cứu sinh | PDF 10–30 trang | Hiểu sơ bộ nội dung bài                | 60–120 phút/bài (20–30 trang × 3–4 phút) | **Bottleneck**: đọc toàn bộ chỉ để biết có đáng đọc kỹ không |
|    3 | Sinh viên / nghiên cứu sinh | Phần đã đọc     | Ghi chú: vấn đề, phương pháp, kết luận | ~20 phút/bài (ước lượng)                 |                                                              |
|    4 | Sinh viên / nghiên cứu sinh | Ghi chú         | Quyết định đọc kỹ hoặc loại            | ~5 phút/bài (ước lượng)                  |                                                              |

Tổng hiện tại: khoảng 95–155 phút/bài (cộng các ước lượng, chưa bấm giờ). Bước 1, 3, 4 là ước lượng của nhóm; riêng bước 2 có công thức tính từ số trang × phút/trang.

**Bottleneck chính:** Bước 2, đọc toàn bộ bài chỉ để biết có đáng đọc kỹ hay không.

### 4.2. Quy trình tương lai

```text
PDF của bài (người dùng chọn và tải)
            ↓
[Rule] Kiểm tra PDF đọc được; lấy abstract, kết luận gốc, tên các mục làm bản đối chiếu
            ↓
[AI] Tóm tắt 3 mục: vấn đề, phương pháp, kết luận
     chỉ từ nội dung bài, mỗi ý ghi rõ nằm ở mục/trang nào;
     đánh dấu phần hình/bảng chưa đọc được
            ↓
[Con người] Đối chiếu bản tóm tắt với abstract và kết luận gốc
        ↙                          ↘
   Khớp                       Không khớp / thiếu
     ↓                              ↓
[Con người] Quyết định:      Quay về: đọc theo 3 lượt
đọc kỹ / đọc phần cụ thể /   (abstract → hình/bảng → kết luận)
loại bài                     hoặc đọc toàn bộ
```

- **Rule:** kiểm tra PDF có chữ chọn được hay là ảnh scan; tách sẵn abstract, kết luận và danh sách mục của bài gốc để con người đối chiếu.
- **AI:** tóm tắt vấn đề, phương pháp, kết luận từ văn bản bài đưa vào, kèm vị trí trong bài; ghi rõ phần nào chưa đọc được.
- **Con người:** đối chiếu với abstract và kết luận gốc, rồi quyết định đọc kỹ, chỉ đọc phần cụ thể hoặc loại bài.
- **Boundary:** AI không được dùng nguồn hay số liệu ngoài bài; không được suy đoán nội dung hình/bảng/công thức mà nó không đọc được; không tự loại bài thay người dùng.
- **Phương án quay về:** nếu tóm tắt không khớp abstract/kết luận, thiếu mục hoặc PDF là ảnh scan thì bỏ bản tóm tắt và đọc theo 3 lượt hoặc đọc toàn bộ như hiện nay.

### 4.3. Before / after

| Chỉ số               |                    Trước |                                                                            Sau (kỳ vọng) | Ghi chú                                                                                         |
| -------------------- | -----------------------: | ---------------------------------------------------------------------------------------: | ----------------------------------------------------------------------------------------------- |
| Số bước              |                        4 |                                                                                        5 | Thêm bước Rule chuẩn bị và bước đối chiếu; đổi lại bước đọc toàn bộ biến mất                    |
| Tổng thời gian / bài | ~95–155 phút (ước lượng) |                                                   Mục tiêu dưới 15 phút để ra quyết định | Chưa đo thực tế; baseline cần bấm giờ lại                                                       |
| Số bước thủ công     |                        4 |                                                                                        3 | Chọn/tải bài, đối chiếu, quyết định                                                             |
| Bottleneck chính     |          Đọc toàn bộ bài |                                       Đối chiếu bản tóm tắt với abstract và kết luận gốc | Chuyển từ đọc sang kiểm tra                                                                     |
| Rủi ro mới phát sinh |        Đọc lâu, dễ bỏ dở | AI bịa hoặc bỏ sót kết luận; người dùng tin quá mức; bỏ sót nội dung nằm trong hình/bảng | Giảm bằng bước đối chiếu bắt buộc, ràng buộc chỉ dùng nội dung bài, đánh dấu phần chưa đọc được |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung                                                                                                                                                                                                                                                                                                                                                                             |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Actor**                                                                  | Sinh viên và nghiên cứu sinh phải đọc nhiều bài báo/tài liệu chuyên ngành dài khi làm tiểu luận, đồ án hoặc literature review.                                                                                                                                                                                                                                                       |
| **Quy trình**                                                              | Tìm và tải bài → đọc toàn bộ → ghi lại vấn đề, phương pháp, kết luận → quyết định có đọc kỹ hay không.                                                                                                                                                                                                                                                                               |
| **Bottleneck**                                                             | Bước đọc toàn bộ bài chỉ để biết bài đó có đáng đọc kỹ hay không: 20–30 trang × 3–4 phút = 60–120 phút/bài (ước lượng, chưa bấm giờ).                                                                                                                                                                                                                                                |
| **Impact**                                                                 | Với literature review cần khoảng 30 bài (Đạt), riêng việc đọc và trích xuất có thể tốn 30–60 giờ (1–2 giờ/bài). Con số này gộp cả đọc và trích xuất, chưa tách riêng bước quyết định đọc kỹ.                                                                                                                                                                                         |
| **Success Metric** (baseline → target, cách đo)                            | **Baseline:** 60–120 phút/bài (ước lượng); bấm giờ lại 3 bài thật để xác nhận. **Target:** dưới 15 phút/bài để quyết định có đọc kỹ hay không. **Chất lượng:** phần tóm tắt khớp với abstract và kết luận của bài gốc; không bỏ sót bài đáng đọc nào trong 3 bài thử (đề xuất, nhóm xác nhận). **Cách đo:** bấm giờ từ lúc mở bài đến lúc quyết định, đối chiếu tóm tắt với bài gốc. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI chỉ tóm tắt từ văn bản bài người dùng đưa vào, không thêm nguồn hay số liệu ngoài bài, không suy đoán nội dung hình/bảng không đọc được, không tự loại bài. Con người luôn đối chiếu với abstract và kết luận gốc trước khi dùng.                                                                                                                                                 |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **Đồng ý (AI phản biện trong báo cáo Huy Vũ):** tóm tắt của AI có thể bịa hoặc bỏ sót kết luận chính của bài → thêm bước đối chiếu bắt buộc và ràng buộc "không dùng nguồn ngoài bài".
- **Đồng ý:** các số phút đều là ước lượng, chưa bấm giờ → để Baseline ở dạng giả thuyết, bấm giờ 3 bài trước khi coi là baseline chính thức.
- **Đồng ý:** số 1–2 giờ/bài của Đạt gộp cả đọc và trích xuất, chưa tách bước quyết định → ghi rõ trong Impact.
- **Đồng ý:** cách không AI (đọc 3 lượt) có thể đã đủ → so sánh trực tiếp ở mục 6 và đặt làm điều kiện dừng ở mục 8.
- **Đồng ý:** không biết mỗi kỳ phải đọc bao nhiêu bài → thêm vào việc cần hỏi/đếm ở CP4.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **độ mơ hồ thấp đến trung bình × độ phức tạp trung bình** (đổi tên ô cho khớp worksheet nếu khác).

Vì sao:

- Độ mơ hồ thấp đến trung bình: đầu ra mong muốn rõ (tóm tắt vấn đề, phương pháp, kết luận) và kiểm tra được bằng cách đối chiếu với abstract và kết luận gốc.
- Độ phức tạp trung bình: các bước cố định, nhưng bài dài, nhiều định dạng, có hình/bảng/công thức mà công cụ không đọc tốt.
- Không có bước nào cần AI tự quyết bước tiếp theo, nên không cần Agent.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm                                                                                    | Đủ khi nào                                                         | Rủi ro                                                                 | Chọn?                                                     |
| ------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------- | --------------------------------------------------------- |
| **No AI** (sửa quy trình) | Đọc theo 3 lượt (abstract → hình/bảng → kết luận) với khung ghi chú cố định (vấn đề / phương pháp / kết luận) | Khi đọc 3 lượt đã đưa thời gian về dưới 15 phút/bài                | Vẫn phụ thuộc kỷ luật của người đọc; chưa biết thời gian thực          | Không chọn làm đích; **dùng làm baseline phải thử trước** |
| **Rule**                  | Tách sẵn abstract, kết luận và danh sách mục của bài để đọc nhanh                                             | Khi bài có cấu trúc chuẩn và chỉ cần xem abstract                  | Không tóm tắt được phương pháp; hỏng với bài cấu trúc lạ hoặc PDF scan | Dùng như bước đầu trong workflow                          |
| **Workflow**              | Rule chuẩn bị → AI tóm tắt 3 mục từ bài đưa vào kèm vị trí → con người đối chiếu → quyết định                 | Khi đọc 3 lượt chưa đủ nhanh và có thể đối chiếu tóm tắt với nguồn | AI bịa/bỏ sót kết luận; bỏ sót nội dung hình/bảng                      | **Chọn (có điều kiện)**                                   |
| **Agent**                 | AI tự tìm bài, tự đọc, tự quyết đọc hay bỏ                                                                    | Khi các bước không cố định và người dùng giao hẳn việc             | Bỏ sót bài quan trọng, nguồn bịa, khó kiểm tra                         | Không chọn                                                |

**Mức chọn:** Workflow, với điều kiện đã thử và xác nhận No AI (đọc 3 lượt) chưa đủ.

**Vì sao không chọn mức đơn giản hơn:**

- No AI và Rule chưa được thử với số liệu thật, nên hiện chưa chứng minh được là chúng không đủ. Đây là lý do quyết định ở mục 8 là Not Yet.
- Rule chỉ lấy được abstract và kết luận, không tóm tắt được phương pháp, trong khi người đọc cần nắm phương pháp để biết có đáng đọc kỹ.
- Nếu thử No AI mà đạt dưới 15 phút/bài thì nhóm dừng ở No AI và không cần AI.

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung                                                                                                                                                       |
| ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          | Bản tóm tắt vấn đề, phương pháp, kết luận của bài, mỗi ý kèm vị trí (mục/trang) trong bài; đánh dấu phần chưa đọc được.                                        |
| **Judgment** — con người cân nhắc, quyết định gì?                 | Đối chiếu tóm tắt với abstract và kết luận gốc; quyết định đọc kỹ, chỉ đọc phần cụ thể hay loại bài theo mục tiêu của tiểu luận/đồ án.                         |
| **Action** — hành động cuối cùng là gì, ai làm?                   | Người dùng đọc kỹ hoặc loại bài và ghi vào khung ghi chú. AI không hành động thay.                                                                             |
| **Outcome** — đo kết quả bằng gì?                                 | Thời gian từ lúc mở bài đến lúc quyết định (phút); tỷ lệ tóm tắt khớp bài gốc; số bài đáng đọc bị loại nhầm.                                                   |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | File PDF/văn bản của bài, abstract và kết luận gốc, mục tiêu đọc (đề tài). Có sẵn nếu PDF có chữ chọn được; PDF scan hoặc nội dung chỉ nằm trong hình thì khó. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   | Người dùng đánh dấu tóm tắt sai/thiếu; so quyết định ban đầu với quyết định sau khi đọc kỹ.                                                                    |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? **Augment.** Bằng chứng: Huy Vũ ghi "tôi luôn đối chiếu với abstract và kết luận của bài gốc"; hai người cần tự quyết bài nào đáng đọc kỹ vì phụ thuộc đề tài của họ.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? **Bỏ sót tệ hơn**: bỏ sót kết luận hoặc loại nhầm bài đáng đọc làm mất tài liệu quan trọng mà người dùng không biết; báo nhầm chỉ tốn thêm vài phút đọc. Thiết kế xử lý: AI không đề xuất loại bài khi không chắc, mặc định gợi ý phần nên đọc thêm, đánh dấu rõ phần chưa đọc được, và người dùng luôn đối chiếu với abstract và kết luận gốc.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                                                                                                                                                                                                                                                   |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                       | Sinh viên và nghiên cứu sinh phải đọc nhiều bài báo/tài liệu chuyên ngành dài khi làm tiểu luận, đồ án hoặc literature review.                                                                                                                             |
| **Quy trình**                                   | Tìm và tải bài → [Rule] lấy abstract/kết luận/danh sách mục → [AI] tóm tắt 3 mục kèm vị trí → [Con người] đối chiếu → quyết định đọc kỹ / đọc phần cụ thể / loại bài.                                                                                      |
| **Bottleneck**                                  | Bước đọc toàn bộ bài chỉ để biết có đáng đọc kỹ hay không: 60–120 phút/bài (ước lượng, cần bấm giờ xác nhận).                                                                                                                                              |
| **Impact**                                      | Literature review cỡ 30 bài có thể tốn 30–60 giờ cho đọc và trích xuất (số gộp, cần tách riêng bước quyết định).                                                                                                                                           |
| **Success Metric** (baseline → target, cách đo) | Baseline: 60–120 phút/bài (bấm giờ lại 3 bài), và thời gian của phương án No AI (đọc 3 lượt) trên cùng 3 bài. Target: dưới 15 phút/bài để quyết định. Chất lượng: tóm tắt khớp abstract và kết luận gốc; không loại nhầm bài đáng đọc nào trong 3 bài thử. |
| **Boundary**                                    | AI chỉ dùng văn bản bài đưa vào; không thêm nguồn hay số liệu ngoài bài; không suy đoán nội dung hình/bảng/công thức không đọc được; không tự loại bài; con người đối chiếu trước khi dùng.                                                                |
| **AI intervention point**                       | Một điểm duy nhất: bước tóm tắt 3 mục (vấn đề, phương pháp, kết luận) sau khi Rule chuẩn bị đầu vào và trước khi con người đối chiếu.                                                                                                                      |
| **Mức chọn**                                    | Workflow                                                                                                                                                                                                                                                   |
| **Rủi ro & người kiểm tra**                     | Rủi ro: AI bịa hoặc bỏ sót kết luận; bỏ sót nội dung nằm trong hình/bảng; người dùng tin quá mức. Người kiểm tra: chính người đọc (sinh viên/nghiên cứu sinh), đối chiếu với abstract và kết luận gốc.                                                     |

**Thay đổi so với v0 và lý do:**

| Trường                                  | v0                                                         | v1                                                                                          | Vì sao đổi                                                                    |
| --------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Success Metric                          | Target dưới 15 phút/bài; chất lượng khớp abstract/kết luận | Thêm baseline của phương án No AI trên cùng 3 bài, và tiêu chí không loại nhầm bài đáng đọc | Cần chứng minh AI tốt hơn cách không dùng AI, không chỉ tốt hơn "đọc toàn bộ" |
| Boundary                                | AI chỉ dùng nội dung bài, không tự loại bài                | Thêm: không suy đoán hình/bảng không đọc được, phải đánh dấu                                | Research cho thấy công cụ hiện có yếu ở hình/bảng (mục 3.3)                   |
| Quy trình                               | Quy trình hiện tại 4 bước                                  | Quy trình tương lai có Rule, AI, con người và đường quay về                                 | Cần chỉ rõ AI chen ở đâu và khi AI sai thì làm gì                             |
| AI intervention point, Mức chọn, Rủi ro | Chưa có                                                    | Một điểm can thiệp; Workflow; rủi ro và người kiểm tra                                      | Theo yêu cầu v1                                                               |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí               | Đạt khi                                                                | Không đạt khi                                           |
| --: | ---------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------- |
|   1 | Bám nguồn              | Mọi ý trong tóm tắt đều tìm thấy trong bài và có vị trí kèm theo       | Có số liệu, nguồn hoặc nhận định không có trong bài     |
|   2 | Đủ 3 mục               | Có đủ vấn đề, phương pháp, kết luận                                    | Thiếu ít nhất 1 mục                                     |
|   3 | Kết luận khớp          | Kết luận cùng hướng với abstract/kết luận của tác giả, không phóng đại | Kết luận sai hướng, bỏ sót kết quả chính hoặc phóng đại |
|   4 | Trung thực về giới hạn | Ghi rõ phần không đọc được (hình, bảng, công thức)                     | Diễn giải nội dung hình/bảng khi không đọc được         |
|   5 | Tốc độ                 | Từ lúc mở bài đến lúc quyết định dưới 15 phút                          | Từ 15 phút trở lên hoặc phải đọc toàn bộ để chắc chắn   |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng                                                                                                                                                             |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       | **TB**                                                | Hai thành viên cùng nêu pain, nhưng số phút là ước lượng, chưa có phỏng vấn hay bấm giờ, và cách không AI (đọc 3 lượt) chưa được thử.                                          |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Thấp**                                              | Người dùng chính là người đọc, đối chiếu được với abstract và kết luận gốc; tóm tắt có vị trí trong bài nên dễ kiểm tra.                                                       |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     | **Thấp đến TB**                                       | Công cụ có sẵn (Semantic Scholar TLDR, Elicit, NotebookLM) và đầu vào là PDF đã có; điểm yếu là hình/bảng và PDF scan.                                                         |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     | **Thấp đến TB**                                       | Chi phí thấp nếu dùng gói miễn phí nhưng có giới hạn; cần kiểm tra điều khoản khi tải bài có bản quyền hoặc tài liệu của trường lên công cụ bên thứ ba. Mỗi người tự vận hành. |

### 8.2. Kết luận

**Quyết định:** **Not Yet** (đề xuất; nhóm xác nhận)

**Lý do:** Candidate được chọn có cơ sở tốt hơn các phương án khác nhưng chưa có bằng chứng đo thật: chưa phỏng vấn ai, chưa bấm giờ, chưa biết mỗi kỳ phải đọc bao nhiêu bài, và chưa thử cách không AI. Quyết định Go ở thời điểm này sẽ dựa trên ước lượng của hai người trong nhóm.

**Nếu Go — pilot nhỏ nhất:** Chọn 3 bài thật, bấm giờ 3 cách (đọc toàn bộ, đọc 3 lượt, workflow có AI + đối chiếu), so sánh thời gian và kiểm tra tóm tắt có khớp bài gốc không.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. Bấm giờ baseline trên 3 bài thật (đọc toàn bộ để quyết định), tách khỏi thời gian trích xuất.
2. Thử phương án No AI (đọc 3 lượt) trên cùng 3 bài và ghi thời gian.
3. Phỏng vấn 2–3 bạn học (câu hỏi ở mục 3.2): số bài mỗi kỳ, tỷ lệ bài cuối cùng bị loại.
4. Thử một công cụ ở mục 3.3 trên 3 bài đó, kiểm tra độ khớp với abstract và kết luận gốc.

**Nếu No-Go — nên làm gì thay AI:** Dùng khung đọc 3 lượt (abstract → hình/bảng → kết luận) với khung ghi chú cố định.

**Ngưỡng dừng** (đề xuất, nhóm chốt số): Nếu sau khi bấm giờ 3 bài mà baseline thực thấp hơn 30 phút/bài, hoặc đọc 3 lượt đã đạt dưới 15 phút/bài, thì quay về No AI (đọc 3 lượt). Nếu tóm tắt của AI không khớp abstract hoặc kết luận gốc ở từ 1/3 bài trở lên, thì dừng workflow AI và quay về Rule hoặc No AI.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có phỏng vấn và chưa bấm giờ; baseline 60–120 phút/bài là ước lượng của hai thành viên trong nhóm, nên mọi kết luận về impact còn là giả thuyết.
- Số 1–2 giờ/bài của Đạt gộp đọc và trích xuất, chưa tách bước quyết định.
- Đạt chưa điền Top 3, Problem Card và câu hỏi phản biện; các candidate #10–12 được chọn tạm từ bảng Scan.
- Cột "câu hỏi phản biện" mới lấy từ báo cáo cá nhân, chưa có tên người hỏi thật.
- Thông tin về công cụ ở mục 3.3 lấy từ hướng dẫn bên thứ ba, nhóm chưa tự thử; điểm số ở mục 2.4 và các ngưỡng ở mục 8 là đề xuất cần cả nhóm xác nhận.
- Hướng tiếp theo: thực hiện 4 việc ở mục 8.2 (Not Yet); nếu S1 đứng vững, thử mở rộng sang S3 (tổng hợp ôn thi) vì cùng cluster A.

## 10. Tài liệu tham khảo

- Semantic Scholar TLDR: https://www.semanticscholar.org/product/tldr
- The Batch, "Very Short, Did Read" (mô tả TLDR chỉ xét abstract, mở đầu, kết luận): https://www.deeplearning.ai/the-batch/very-short-did-read
- Thư viện BCU, AI và data extraction (Elicit): https://libguides.bcu.ac.uk/generativeAI/data-extraction
- CASRAI, Elicit (AI Research Assistant): https://www.casrai.org/dictionary/term/elicit-ai-research-assistant
- CASRAI, NotebookLM for research workflows: https://www.casrai.org/guides/notebooklm-for-research-workflows
- Báo cáo cá nhân của Vũ Đình Huy, Quách Ngọc Huy, Khương Hoàng Nguyên, Trần Trọng Đạt (`report/individual/`)

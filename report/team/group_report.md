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

Mỗi người pitch top 3 từ báo cáo cá nhân (mục 3). Cột cuối là câu hỏi phản biện ghi trong lúc nghe.

|   # | Người đưa ra        | Candidate (Job Story ngắn)                                                                                                           | Actor                                                     | Bottleneck                                                               | Câu hỏi phản biện nhận được                                                                                                                                                                         |
| --: | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Vũ Đình Huy         | Khi ôn thi, muốn gom ý chính từ slide, ghi chú, giáo trình để khỏi đọc lại toàn bộ                                                   | Sinh viên ôn thi cuối kỳ                                  | Viết lại thành bản tóm tắt: ~240 phút trong 10/30 giờ ôn tập (ước lượng) | Bản tóm tắt "đủ tốt" đo thế nào? 10 giờ là mỗi môn hay cả kỳ?                                                                                                                                       |
|   2 | Vũ Đình Huy         | Khi làm bài nhóm, muốn biết ai làm phần nào, đến đâu để khỏi nhắn hỏi từng người                                                     | Thành viên nhóm, đặc biệt trưởng nhóm                     | Chờ trả lời + đọc lại ~100 tin/ngày: ~35 phút/ngày (ước lượng)           | Bao nhiêu trong 100 tin/ngày thật sự là hỏi tiến độ? Bảng việc chung đã đủ chưa?                                                                                                                    |
|   3 | Vũ Đình Huy         | Khi đọc bài báo khoa học dài, muốn nắm nhanh vấn đề, phương pháp, kết luận để biết có nên đọc kỹ không                               | Sinh viên, nghiên cứu sinh                                | Đọc toàn bộ bài: 60–120 phút/bài                                         | Mỗi kỳ phải đọc bao nhiêu bài? Tóm tắt AI có bịa/bỏ sót kết luận không?                                                                                                                             |
|   4 | Quách Ngọc Huy      | Khi chưa có task mới, muốn biết việc nào có thể chủ động làm để tạo giá trị, khỏi ngồi chờ                                           | Software Engineer (và team)                               | Xác định việc nên chủ động làm                                           | Pain chính là thiếu task, thiếu thông tin nhu cầu của team, hay thiếu cơ chế tự xác định việc có giá trị?                                                                                           |
|   5 | Quách Ngọc Huy      | Khi có thời gian rảnh, muốn biết nên học gì trước để phù hợp công việc và định hướng                                                 | Software Engineer                                         | Xác định nên học gì và theo thứ tự nào                                   | Khó nằm ở chọn chủ đề hay chọn thứ tự học?                                                                                                                                                          |
|   6 | Quách Ngọc Huy      | Khi cần dùng lại thông tin đã đọc/trao đổi, muốn tìm lại nhanh để khỏi nghiên cứu lại từ đầu                                         | Software Engineer                                         | Tìm đúng thông tin giữa chat/file/browser/ghi chú                        | Thông tin nằm chủ yếu ở đâu, tần suất thực tế bao nhiêu?                                                                                                                                            |
|   7 | Khương Hoàng Nguyên | Khi đánh giá nhiều lần thử nghiệm mô hình, muốn liên kết config, dữ liệu, metric để chọn mô hình có căn cứ                           | Người phụ trách thử nghiệm/đánh giá ML/AI                 | Lục config + đối chiếu log: ~60 phút/lần đánh giá                        | 60 phút có phải mức điển hình? "Lục config" và "đối chiếu log" có tách được thành hai bước?                                                                                                         |
|   8 | Khương Hoàng Nguyên | Khi nhận code/dữ liệu/model từ đồng đội, muốn biết điều kiện môi trường và schema I/O để tích hợp trơn tru                           | Người tích hợp và người bàn giao module                   | Làm rõ schema + debug: ~90 phút/lần bàn giao                             | Metric 90 → 30 phút có tính thời gian chờ phản hồi không? Có ca bàn giao thật làm bằng chứng chưa?                                                                                                  |
|   9 | Khương Hoàng Nguyên | Khi theo dõi tiến độ, muốn biết chính xác việc nào đang bị blocker để điều phối kịp thời                                             | Trưởng nhóm; cả nhóm chịu ảnh hưởng                       | Phát hiện blocker muộn: ~1.440 phút (24 giờ)/lần                         | Blocker bắt đầu, được phát hiện, được xử lý tính từ thời điểm nào?                                                                                                                                  |
|  10 | Trần Trọng Đạt      | Khi làm literature review, muốn đọc và tìm ra research gap từ ~30 báo cáo dài 10–30 trang mà không phải đọc lại tất cả               | Sinh viên, nghiên cứu sinh                                | Đọc, trích xuất, đối chiếu giữa các bài: 60–120 phút/bài (ước tính)      | 1–2 giờ/bài đã bấm giờ chưa, hay mới là ước tính? Mất thời gian ở bước đọc hay bước đối chiếu giữa các bài? Nếu dùng công cụ đọc hộ mà trích sai/bỏ sót nguồn thì kiểm tra thế nào?                 |
|  11 | Trần Trọng Đạt      | Khi làm bài nhóm, muốn thống nhất format, bố cục, giọng văn để khỏi sửa lại toàn bộ lúc tổng hợp                                     | Sinh viên làm việc nhóm, người tổng hợp báo cáo           | Kiểm tra và sửa format/giọng văn báo cáo ~40 trang: ~60 phút             | 60 phút là số đo hay ước lượng? Template + Styles trong Word đã giải được phần lớn chưa? Chuẩn hóa giọng văn có làm sai ý người viết không?                                                         |
|  12 | Trần Trọng Đạt      | Khi tàu xếp/dỡ hàng ở cảng, muốn đối chiếu báo cáo sự kiện (SOF/NOR) với hợp đồng thuê tàu để xác định laytime và demurrage/despatch | Chủ tàu, người thuê tàu, bộ phận khai thác, thuyền trưởng | Đọc, đối chiếu chứng từ với điều khoản hợp đồng (chưa có số phút)        | Một bảng laytime mất bao nhiêu phút? Cả nhóm chưa ai gặp nhân viên khai thác tàu, kiểm chứng bằng cách nào trong một buổi? Quyền truy cập hợp đồng của từng bên (chủ tàu, người thuê) xử lý ra sao? |

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
- "RAG đọc và đối chiếu báo cáo nghiên cứu" (tiêu đề card #3 của Đạt) và "OCR/RAG tra điều khoản hợp đồng" (card #1 của Đạt) là công cụ; nhu cầu thật là truy được bằng chứng kèm vị trí nguồn gốc (đã đưa vào A, dòng #10 và #12).
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

Vì sao "Pain có bằng chứng" chỉ 3 ở cả ba candidate: toàn bộ số phút/số tin hiện là ước lượng cá nhân, chưa ai bấm giờ hay đếm thật.

**Candidate được chọn:** S1. Khi sinh viên/nghiên cứu sinh phải đọc nhiều bài báo hoặc tài liệu dài, họ mất khoảng 60–120 phút mỗi bài chỉ để biết bài đó có đáng đọc kỹ hay không.

**Vì sao chọn:**

- Điểm cao nhất (30/35), hơn S3 một điểm và hơn S2 bốn điểm.
- Hai thành viên nêu độc lập cùng pain này (Huy Vũ #3 và Đạt #10) và hai ước lượng gần nhau (60–120 phút so với 1–2 giờ/bài). S2 cũng có hai người pitch (Huy Vũ #2, Nguyên #9; Đạt cũng ghi ở scan #7) nhưng mỗi người đo một thứ khác nhau (tin nhắn/ngày so với phút phát hiện blocker), nên chưa thống nhất được bottleneck.
- Bottleneck nằm ở một bước cụ thể (đọc toàn bộ bài chỉ để quyết định), dễ bấm giờ và dễ kiểm chứng với bạn học ở CP4.
- Nhóm hiểu domain: Huy Vũ và Đạt trực tiếp gặp pain này; Ngọc Huy cũng ghi một pain gần (tìm thông tin đáng tin khi gặp công nghệ mới, scan #3).

**Vì sao loại các candidate còn lại:**

- **S3 (tổng hợp ôn thi, 29):** impact lớn nhất (10/30 giờ ôn tập, khoảng 33%) nhưng chỉ một người nêu, theo mùa thi nên khó kiểm chứng sớm, và chất lượng bản tóm tắt khó đo nên kém vừa sức lab. Cùng cluster A, nên là hướng mở rộng nếu S1 đứng vững.
- **S2 (tiến độ bài nhóm, 26):** bottleneck chưa tách được (100 tin/ngày chưa phân biệt tin hỏi tiến độ với tin trao đổi nội dung; "blocker" của Nguyên chưa có định nghĩa thời điểm bắt đầu/phát hiện); chính Huy Vũ ghi "No AI hoặc Rule có thể đã đủ" và card blocker của Nguyên cũng tự đánh giá là chỉ cần Rule.
- **Cluster C (#4, #5):** chỉ một người nêu, bottleneck và impact còn định tính, chưa có số phút.
- **#7, #8:** đặc thù người làm ML/AI, chỉ một thành viên pitch, khó kiểm chứng với bạn học ngoài nhóm; chính Nguyên ghi chưa tách được thời gian chờ khỏi thời gian debug ở #8.
- **#11:** chỉ Đạt pitch (Huy Vũ có ghi ở scan #4, 45 phút chỉnh slide, nhưng chưa vào top 3); template + Styles trong Word có thể đã đủ, ít chỗ cho AI.
- **#12:** cần kiến thức hợp đồng hàng hải; cả nhóm chưa có người làm trong ngành để kiểm chứng trong một buổi lab, và Đạt chưa đo được số phút.

**Xử lý bất đồng (nếu có):** S1 chỉ hơn S3 một điểm (30 so với 29), chênh lệch này nằm trong sai số chấm. Tiêu chí phân xử đề xuất: (1) candidate nào có nhiều người độc lập cùng gặp hơn, (2) candidate nào kiểm chứng được nhanh hơn trong một buổi. Với S1 và S3, cả hai tiêu chí đều nghiêng về S1 (hai người so với một người; đọc bài báo bấm giờ được ngay, không phải chờ mùa thi). Nếu nhóm không đồng ý, ghi lại ý kiến khác ở đây.

**Điều cần kiểm ở CP4 cho S1:** (1) bấm giờ thật 3–5 bài; (2) mỗi kỳ mỗi người phải đọc bao nhiêu bài; (3) bước nào chiếm thời gian nhất: đọc hay đối chiếu giữa các bài; (4) tóm tắt tự động có bỏ sót hoặc bịa kết luận không (cần đối chiếu với abstract và kết luận gốc).

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 |          |                                                    |                  |                        |                   |
|   2 |          |                                                    |                  |                        |                   |
|   3 |          |                                                    |                  |                        |                   |
|   4 |          |                                                    |                  |                        |                   |
|   5 |          |                                                    |                  |                        |                   |
|   6 |          |                                                    |                  |                        |                   |

_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |          |
| Câu nói đáng nhớ nhất (nguyên văn)                |          |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |          |
| Hiện đang xử lý bằng cách nào (workaround)?       |          |
| Mất bao lâu, bao lần?                             |          |
| Insight / opportunity rút ra                      |          |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
| ----- | ----------------: | ----------------- | ----------------- |
|       |                   |                   |                   |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
|    1 |       |       |        |                      |         |
|    2 |       |       |        |                      |         |
|    3 |       |       |        |                      |         |
|    4 |       |       |        |                      |         |
|    5 |       |       |        |                      |         |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước              |       |               |         |
| Tổng thời gian       |       |               |         |
| Số bước thủ công     |       |               |         |
| Bottleneck chính     |       |               |         |
| Rủi ro mới phát sinh |       |               |         |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  |          |
| **Quy trình**                                                              |          |
| **Bottleneck**                                                             |          |
| **Impact**                                                                 |          |
| **Success Metric** (baseline → target, cách đo)                            |          |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |          |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- ***

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

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

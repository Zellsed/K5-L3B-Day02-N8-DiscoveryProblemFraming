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

Bài của nhóm nằm ở ô: **Độ mơ hồ cao × độ phức tạp thấp–trung bình**.

Vì sao: Một bài báo có thể được đánh giá là liên quan theo nhiều tiêu chí nghiên cứu khác nhau; việc trích xuất phương pháp và kết quả cũng cần hiểu ngữ cảnh, nên độ mơ hồ cao. Tuy nhiên, các bước sàng lọc có thể định trước: nhập PDF và câu hỏi nghiên cứu → trích xuất thông tin → dẫn về đoạn gốc → người nghiên cứu kiểm tra → quyết định đọc kỹ. AI không cần tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Literature matrix, checklist tiêu chí liên quan; đọc abstract → methodology → results → conclusion | Cấu trúc bài rõ, số bài ít hoặc cách này đã đưa thời gian xuống dưới 30 phút/bài | Vẫn phải tự tìm và tổng hợp thông tin rải rác | Là phương án đối chứng và quay về |
| **Rule** | Lọc theo từ khóa, năm, loại bài; điền các trường metadata cố định | Chỉ cần thu hẹp danh sách bằng tiêu chí xác định trước | Có thể bỏ sót bài dùng thuật ngữ khác; không hiểu phương pháp và kết quả | Dùng cho bước lọc sơ bộ, không chọn làm mức chính |
| **Workflow** | Các bước cố định: nhập PDF → AI truy xuất và trích xuất phương pháp/kết quả kèm trang hoặc đoạn nguồn → người nghiên cứu đối chiếu → quyết định đọc kỹ | Cần hiểu nội dung bài, nhưng quy trình và điểm kiểm tra đã rõ | Trích xuất sai, dẫn sai nguồn hoặc bỏ sót bài liên quan | **Mức đề xuất để thử nghiệm** |
| **Agent** | AI tự tìm thêm tài liệu, chọn công cụ, thay đổi hướng tìm và tự kết luận bài nào cần đọc | Chỉ phù hợp nếu các bước không thể định trước và đã có cơ chế kiểm soát đáng tin cậy | Khó truy vết quyết định, tăng quyền truy cập và phạm vi sai sót | Không chọn |

**Mức chọn:** Workflow có AI ở bước trích xuất sơ bộ, người nghiên cứu quyết định cuối cùng.

**Vì sao không chọn mức đơn giản hơn:** Rule không đủ để hiểu và đối chiếu phương pháp, kết quả được diễn đạt bằng nhiều cách. No AI là phương án đối chứng cần thử trước: hiện chưa có số đo chứng minh checklist và literature matrix không thể rút thời gian sàng lọc xuống dưới 30 phút/bài. Vì vậy, chọn Workflow để so sánh trong pilot, chưa khẳng định AI tạo thêm giá trị.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Bản trích xuất sơ bộ gồm câu hỏi/mục tiêu, phương pháp, kết quả chính và các đoạn có thể liên quan tới tiêu chí sàng lọc; mỗi ý kèm vị trí trong PDF. Nếu không tìm thấy, ghi “chưa tìm thấy”. |
| **Judgment** — con người cân nhắc, quyết định gì? | Người nghiên cứu kiểm tra đoạn gốc, đánh giá mức độ liên quan với câu hỏi nghiên cứu và quyết định đọc kỹ, loại hoặc cần xem thêm. |
| **Action** — hành động cuối cùng là gì, ai làm? | Người nghiên cứu ghi quyết định cùng lý do vào literature matrix và chọn bài để đọc kỹ. |
| **Outcome** — đo kết quả bằng gì? | Thời gian từ lúc bắt đầu xem một bài đến khi ghi quyết định sàng lọc; tỷ lệ thông tin có dẫn chứng đúng; số bài liên quan bị bỏ sót so với đánh giá thủ công. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | PDF được phép sử dụng, câu hỏi nghiên cứu và tiêu chí liên quan do nhóm viết trước. Nhóm có thể cung cấp PDF, nhưng cần kiểm tra quyền sử dụng và khả năng đọc các bản scan. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Các chỗ người nghiên cứu sửa bản trích xuất, dẫn chứng sai, mục bị thiếu và quyết định sàng lọc khác với đánh giá thủ công. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Chọn augment: AI chuẩn bị thông tin để người nghiên cứu kiểm tra và quyết định. Đây là lựa chọn thiết kế của nhóm; báo cáo hiện chưa có phỏng vấn CP4 để khẳng định người dùng thật sự muốn cách hỗ trợ này.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Bỏ sót một bài liên quan tệ hơn báo nhầm một bài ít liên quan, vì bài bị bỏ sót có thể không được đọc kỹ và làm lệch tổng quan tài liệu. Workflow cần hiện nguồn cho từng ý, cho phép trạng thái “chưa rõ/cần xem thêm” và không tự động loại bài chỉ dựa vào câu trả lời AI. Báo nhầm cũng được ghi lại để đo thời gian đọc phát sinh.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên, nghiên cứu sinh thực hiện literature review với nhiều bài báo dài. |
| **Quy trình** | Tìm và tải bài → sàng lọc từng bài theo câu hỏi nghiên cứu → ghi thông tin vào literature matrix → đọc kỹ các bài phù hợp → đối chiếu và viết tổng quan. |
| **Bottleneck** | Mất khoảng **60–120 phút/bài để quyết định có đọc kỹ bài đó hay không**. Đây là ước tính từ trải nghiệm cá nhân, chưa phải số đo bằng đồng hồ. |
| **Impact** | Sàng lọc khoảng 30 bài có thể tốn nhiều thời gian; người nghiên cứu có nguy cơ bỏ sót bài liên quan hoặc ghi nhận định không truy được về nguồn. Chưa có số đo thực tế cho cả tập bài. |
| **Success Metric** (baseline → target, cách đo) | Baseline ước tính **60–120 phút/bài** → mục tiêu **dưới 30 phút/bài** để có quyết định sàng lọc đã kiểm tra nguồn. Bấm giờ cùng một điểm bắt đầu/kết thúc trên ít nhất 5 bài; đối chiếu Workflow với checklist + literature matrix trên các bài tương đương. Chất lượng: mọi nhận định dùng để ra quyết định phải dẫn đúng đoạn/trang gốc; không bỏ sót bài liên quan trong tập kiểm thử do người nghiên cứu đánh giá thủ công. |
| **Boundary** | AI chỉ xử lý PDF được phép sử dụng; không tự kết luận research gap, không tạo trích dẫn không có trong nguồn và không tự loại bài. Người nghiên cứu phải mở đoạn gốc để kiểm tra trước khi ghi quyết định. Khi nguồn không đọc được hoặc chứng cứ mâu thuẫn, đánh dấu “cần xem thêm” và quay về đọc thủ công. |
| **AI intervention point** | Sau khi có PDF và tiêu chí sàng lọc, trước khi người nghiên cứu quyết định có đọc kỹ bài hay không. |
| **Mức chọn** | Workflow. |
| **Rủi ro & người kiểm tra** | Rủi ro trích xuất sai, dẫn sai trang, bỏ sót kết quả hoặc đánh giá sai mức liên quan. Người nghiên cứu kiểm từng thông tin dùng để ra quyết định với PDF gốc và ghi phần đã sửa. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Phạm vi | Đọc, đối chiếu và tổng hợp nhiều bài | Đo riêng bước quyết định **có đọc kỹ từng bài hay không** | Khớp với baseline 60–120 phút/bài mà nhóm đã chốt |
| Boundary | Người nghiên cứu kiểm tra và tự đánh giá research gap | Thêm quy tắc không tự loại bài, đánh dấu “cần xem thêm”, quay về đọc thủ công | Giảm rủi ro bỏ sót bài liên quan |
| Success Metric | Dưới 30 phút/bản trích xuất sơ bộ/bài | Dưới 30 phút **đến quyết định sàng lọc đã kiểm tra nguồn**, kèm tiêu chí chất lượng | Đảm bảo baseline và target đo cùng một công việc |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Truy được về nguồn | Mọi thông tin dùng để quyết định có trang/đoạn đúng trong PDF gốc | Có nhận định không có nguồn hoặc dẫn sai vị trí |
| 2 | Trích xuất đúng | Mục tiêu, phương pháp và kết quả chính khớp với nội dung đoạn gốc | Diễn giải ngược kết quả, nhầm phương pháp hoặc tự thêm kết luận |
| 3 | Không bỏ sót thông tin quyết định | Nêu được các bằng chứng liên quan tới tiêu chí sàng lọc đã định; chỗ chưa rõ được đánh dấu | Bỏ qua bằng chứng khiến một bài liên quan bị loại |
| 4 | Thể hiện sự không chắc chắn | Nội dung không tìm thấy, mâu thuẫn hoặc không đọc được được ghi rõ để người dùng xem thêm | Đưa ra kết luận chắc chắn khi thiếu chứng cứ |
| 5 | Dùng được để sàng lọc | Người nghiên cứu kiểm tra nguồn và ghi được quyết định cùng lý do | Phải đọc lại gần như toàn bộ bài chỉ để hiểu hoặc sửa bản trích xuất |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Hai thành viên nêu pain tương tự, nhưng baseline 60–120 phút/bài chưa được bấm giờ; báo cáo chưa có kiểm chứng với người ngoài nhóm hoặc so sánh với checklist không dùng AI. |
| **Usability** | Người dùng có hiểu và sửa được đầu ra của AI không? | **Trung bình** | Việc đối chiếu đoạn nguồn phù hợp với cách làm literature review, nhưng chưa thử xem người dùng có kiểm tra được nhanh và nhất quán không. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Trung bình** | Có thể thử với một tập PDF nhỏ và quy trình cố định; chất lượng PDF scan, bảng biểu và trích dẫn theo trang chưa được kiểm tra. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **Trung bình** | Cần xác nhận quyền đưa từng PDF vào công cụ và chi phí xử lý; người nghiên cứu vẫn chịu trách nhiệm về quyết định và trích dẫn. |

### 8.2. Kết luận

**Quyết định:** Not Yet đối với việc triển khai Workflow; tiến hành kiểm chứng nhỏ trước.

**Lý do:** Rủi ro Value còn Cao vì chưa đo baseline và chưa biết cách làm không dùng AI có đủ đạt mục tiêu hay không. Theo tiêu chí trong worksheet, chưa nên gọi là “Go” khi còn rủi ro Cao có thể kiểm chứng nhanh.

**Nếu Go — pilot nhỏ nhất:** Sau khi kiểm chứng pain, thử 5 bài PDF được phép sử dụng. Với cùng tiêu chí sàng lọc, bấm giờ cách dùng checklist + literature matrix và Workflow; người nghiên cứu kiểm nguồn, chấm 5 tiêu chí eval và ghi quyết định cuối cùng. Không cần xây Agent.

**Nếu Not Yet — cần kiểm chứng gì trước:** Bấm giờ thực tế ít nhất 5 bài theo đúng định nghĩa “từ lúc bắt đầu xem bài đến khi quyết định có đọc kỹ”; hỏi 2–3 người từng sàng lọc bài gần đây về cách họ làm và thời gian thực tế; thử checklist không dùng AI; kiểm tra quyền sử dụng và khả năng đọc các PDF mẫu.

**Nếu No-Go — nên làm gì thay AI:** Dùng checklist sàng lọc, literature matrix và công cụ quản lý trích dẫn; chỉ mở lại hướng AI nếu số đo cho thấy vẫn còn bottleneck đáng kể.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): Nếu sau 2 tuần hoặc 5 bài thử mà checklist không dùng AI đã đạt dưới 30 phút/bài với quyết định kiểm tra được nguồn, không triển khai Workflow. Nếu Workflow có bất kỳ bài liên quan nào bị đề xuất loại mà người kiểm tra thủ công phát hiện, hoặc không giảm thời gian sàng lọc so với checklist, dừng pilot và quay về quy trình thủ công.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- Baseline 60–120 phút/bài chỉ là ước lượng của hai thành viên, chưa được bấm giờ. Con số 1–2 giờ/bài của Đạt còn gộp đọc và trích xuất, chưa tách riêng thời gian đến quyết định có đọc kỹ bài hay không; impact và mục tiêu dưới 30 phút/bài vì thế chưa được kiểm chứng.
- Chưa có phỏng vấn hoặc khảo sát người ngoài nhóm. Nhóm cũng chưa thử checklist, literature matrix và các công cụ đã tham khảo để biết phương án không dùng AI có đủ giải quyết pain hay không.
- PDF scan, bảng biểu và cách diễn đạt giữa các ngành có thể khiến AI trích xuất thiếu hoặc dẫn sai nguồn. Người nghiên cứu vẫn phải kiểm tra nhận định với bài gốc; quyền sử dụng PDF và chi phí xử lý cũng chưa được xác nhận.
- Phạm vi mục tiêu hiện chỉ là sàng lọc từng bài để quyết định có đọc kỹ, chưa bao gồm đọc kỹ, đối chiếu nhiều bài, tìm research gap hay viết tổng quan.
- Bằng chứng hội tụ nhóm cần đối chiếu lại: báo cáo cá nhân của Đạt đã có Top 3 và ba Problem Card, nhưng bảng pitch #10–12 chưa được cập nhật theo bản đó; người đặt các câu hỏi phản biện chưa được ghi nhận. Điểm ở mục 2.4 và ngưỡng ở mục 8 là đề xuất cần cả nhóm xác nhận.

**Hướng tiếp theo:**

1. Đối chiếu bảng pitch #10–12 với Problem Card của Đạt; xác nhận nguồn gốc câu hỏi phản biện, điểm shortlist và các ngưỡng quyết định với cả nhóm.
2. Thực hiện kiểm chứng **Not Yet** ở mục 8.2: hỏi 2–3 người từng sàng lọc bài gần đây; bấm giờ ít nhất 5 bài, tách thời gian đọc, trích xuất và ra quyết định; thử checklist và literature matrix làm đối chứng.
3. Nếu bước sàng lọc vẫn là bottleneck, thử Workflow trên PDF được phép sử dụng; ghi thời gian, lỗi dẫn chứng và bài liên quan bị bỏ sót theo tiêu chí mục 7. Chỉ mở rộng sang đối chiếu nhiều bài hoặc S3 (tổng hợp ôn thi) sau khi S1 đạt tiêu chí thời gian và chất lượng.

## 10. Tài liệu tham khảo

1. Anthropic. (2024). [*Building effective agents*](https://www.anthropic.com/research/building-effective-agents). Phân biệt Workflow và Agent; tham khảo mục 6.2.
2. Google PAIR. [*User Needs + Defining Success*](https://pair.withgoogle.com/guidebook-v2/chapter/user-needs/). Cân nhắc augment và automate ở mục 6.4.
3. Google PAIR. [*Errors + Graceful Failure*](https://pair.withgoogle.com/chapter/errors-failing/). Xem xét lỗi báo nhầm, bỏ sót và khả năng người dùng kiểm tra, sửa lỗi ở mục 6.4 và 7.
4. Lewis, P., et al. (2020). [*Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*](https://arxiv.org/abs/2005.11401). Nền tảng tham khảo cho hướng truy xuất thông tin từ tài liệu; không chứng minh công cụ của nhóm dẫn nguồn chính xác.
5. Zotero. [*PDF Reader and Note Editor*](https://www.zotero.org/support/pdf_reader). Phương án không dùng AI: chú thích PDF và liên kết ghi chú với vị trí gốc.
6. PRISMA. [*PRISMA 2020 statement*](https://www.prisma-statement.org/prisma-2020-statement). Chỉ tham khảo cách ghi nhận sàng lọc nếu nhóm thực hiện systematic review; không bắt buộc cho mọi literature review.
7. Semantic Scholar. [*TLDR*](https://www.semanticscholar.org/product/tldr). Ví dụ công cụ tóm tắt bài báo, cần đối chiếu khi hoàn thiện mục 3.3.
8. Birmingham City University Library. [*Data extraction*](https://libguides.bcu.ac.uk/generativeAI/data-extraction). Tổng quan công cụ trích xuất dữ liệu, gồm Elicit, và giới hạn cần người kiểm tra; nguồn để hoàn thiện mục 3.3.
9. CASRAI. [*NotebookLM for Research Workflows*](https://www.casrai.org/guides/notebooklm-for-research-workflows). Ví dụ công cụ làm việc với tài liệu đã tải lên; nguồn để hoàn thiện mục 3.3.

Nguồn nội bộ: [Báo cáo cá nhân của các thành viên](../individual/) (Vũ Đình Huy, Quách Ngọc Huy, Khương Hoàng Nguyên, Trần Trọng Đạt).

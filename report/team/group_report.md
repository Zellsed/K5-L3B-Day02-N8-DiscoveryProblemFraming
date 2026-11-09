# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

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
- Baseline chưa được đo: Mốc 60–120 phút/bài là ước tính từ trải nghiệm của nhóm, với ý nghĩa đã chốt là thời gian để quyết định có đọc kỹ bài đó hay không. Nhóm cần bấm giờ theo cùng một điểm bắt đầu và kết thúc trước khi đánh giá mức cải thiện.
- Chưa kiểm chứng đủ với người ngoài nhóm: Hai thành viên nêu pain tương tự, nhưng chưa đủ để kết luận sinh viên và nghiên cứu sinh khác cũng gặp vấn đề ở cùng mức độ. Cần hỏi 2–3 người về lần sàng lọc bài gần nhất, cách họ làm và thời gian thực tế.
- Chưa chứng minh cần AI: Checklist, literature matrix và cách đọc có thứ tự có thể đã giảm đáng kể thời gian. Nhóm cần đo phương án này trước, rồi mới so sánh với Workflow có AI.
- Chất lượng đầu ra phụ thuộc tài liệu: PDF scan, bảng biểu và cách diễn đạt khác nhau giữa các ngành có thể khiến AI trích xuất thiếu hoặc dẫn sai vị trí. Mỗi nhận định dùng để ra quyết định vẫn cần người nghiên cứu đối chiếu với bài gốc.
- Phạm vi hiện tại chỉ là sàng lọc: Mục tiêu dưới 30 phút/bài áp dụng cho quyết định có đọc kỹ hay không; chưa đo thời gian đọc kỹ, đối chiếu nhiều bài, xác định research gap hay viết tổng quan.

**Hướng tiếp theo:** Nhóm bấm giờ ít nhất 5 bài bằng checklist và literature matrix, đồng thời kiểm chứng pain với người ngoài nhóm. Nếu bước sàng lọc vẫn là bottleneck, nhóm thử Workflow trên các PDF được phép sử dụng, ghi thời gian, lỗi dẫn chứng và bài liên quan bị bỏ sót. Chỉ mở rộng sang đối chiếu nhiều bài hoặc hỗ trợ tìm research gap sau khi bước sàng lọc đạt tiêu chí về thời gian và chất lượng.

## 10. Tài liệu tham khảo

- Anthropic. (2024). Building effective agents. Dùng cho mục 6.2: phân biệt Workflow và Agent, và lý do chọn mức can thiệp đơn giản đủ dùng.
- Google PAIR. User Needs + Defining Success. Dùng cho mục 6.4: quyết định AI hỗ trợ người nghiên cứu hay tự động làm thay.
- Google PAIR. Errors + Graceful Failure. Dùng cho mục 6.4 và 7: xem xét lỗi báo nhầm, bỏ sót và cách để người dùng kiểm tra, sửa lỗi.
- Zotero. PDF Reader and Note Editor. Dùng cho phương án không dùng AI: chú thích PDF, đưa ghi chú vào tài liệu và liên kết trở lại trang gốc.
- PRISMA. PRISMA 2020 statement. Tham khảo cách ghi nhận quá trình sàng lọc tài liệu nếu nhóm thực hiện systematic review; đây không phải yêu cầu bắt buộc cho mọi literature review.

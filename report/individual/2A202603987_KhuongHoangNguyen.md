# Báo cáo cá nhân — 2A202603987_KhuongHoangNguyen

> Đổi tên file theo quy tắc `MSSV_HoTen.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn.

## 1. Thông tin học viên

- Họ tên: Khương Hoàng Nguyên
- MSSV: 2A202603987
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 8N
- Link repo nhóm: [https://github.com/Zellsed/K5-L3B-Day02-N8-DiscoveryProblemFraming.git](https://github.com/Zellsed/K5-L3B-Day02-N8-DiscoveryProblemFraming.git)

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi có một bài nộp sắp đến deadline, tôi muốn tự kiểm tra bài theo rubric và cấu trúc repo, để phát hiện thiếu sót trước khi nộp. | Sinh viên | Xảy ra mỗi bài nộp; cần kiểm tra nhiều mục; thời gian kiểm tra và số lỗi phát hiện trước deadline cần được ghi nhận. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi có transcript hoặc nội dung cuộc họp nhóm, tôi muốn xác định biên bản, quyết định và action items kèm owner/deadline, để mọi người biết việc cần làm tiếp theo. | Thành viên nhóm, đặc biệt người ghi biên bản và người vắng họp | Xảy ra sau mỗi cuộc họp; thông tin nằm trong transcript, ghi chú và trao đổi nhóm; đo số action item bị bỏ sót hoặc thiếu owner/deadline. |
| 3 | Tốn thời gian | Khi tạo pull request, tôi muốn rà soát thay đổi để phát hiện lỗi và giúp reviewer hiểu nhanh hơn, để giảm thời gian review và số vòng sửa đổi. | Người tạo PR và reviewer | Xảy ra với mỗi PR; đo thời gian reviewer cần, số comment sửa lỗi và số vòng review. |
| 4 | Lặp lại | Khi bắt đầu một bài lab mới, tôi muốn xác định các bước chuẩn bị và kiểm tra bắt buộc thường lặp lại, để không bỏ sót yêu cầu trước khi làm. | Sinh viên | Lặp lại ở nhiều lab; đo số yêu cầu bị bỏ sót, thời gian chuẩn bị và số lần phải thiết lập lại. |
| 5 | Tốn thời gian | Khi nhận một bài tập hoặc yêu cầu project mới, tôi muốn xác định các đầu việc, phụ thuộc và mốc cần hoàn thành, để lập kế hoạch phù hợp với thời gian trong tuần. | Sinh viên | Xảy ra mỗi bài tập hoặc milestone; đo thời gian lập kế hoạch và tỷ lệ đầu việc trễ hạn. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi đánh giá kết quả của nhiều lần thử nghiệm, tôi muốn liên kết cấu hình, dữ liệu, metric và nhận xét của từng lần chạy, để rút ra kết luận có căn cứ. | Thành viên phụ trách thử nghiệm/đánh giá | Thông tin phân tán qua nhiều lần chạy; đo thời gian tạo kết luận, tỷ lệ kết luận truy ngược được và số lần thử nghiệm phải lặp lại. |
| 7 | Pain từ người khác | Khi trưởng nhóm theo dõi tiến độ, họ muốn biết đầu việc đang bị chặn, người phụ trách và mốc có nguy cơ trễ, để điều phối kịp thời. | Trưởng nhóm và cả nhóm | Xảy ra trong các buổi cập nhật; đo số blocker được phát hiện trước deadline, tỷ lệ quá hạn và thời gian blocker tồn tại. |
| 8 | Pain từ người khác | Khi sử dụng code, dữ liệu hoặc mô hình do thành viên khác tạo ra, tôi muốn biết điều kiện sử dụng và các giới hạn đã biết, để tránh áp dụng sai hoặc tạo kết quả không đáng tin cậy. | Thành viên sử dụng đầu ra của đồng đội | Xảy ra khi tích hợp thành phần; đo số lỗi tích hợp, số lần dùng sai giả định và thời gian xác minh đầu ra. |

**Nếu có dùng AI để gợi ý thêm:**

- **Lý do chọn:** Tôi giữ lại các ý 4, 5, 6, 7 và 8 (tương ứng các gợi ý 1, 4, 10, 12, 14 của AI) vì chúng phù hợp với vấn đề hiện tại mà tôi đang gặp phải.
- **Lý do bỏ:** Tôi bỏ các gợi ý còn lại vì những vấn đề đó thường đã được giải quyết hoặc tôi chưa gặp phải trong công việc học tập và build project hiện tại.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Liên kết config, dữ liệu và metric của nhiều lần thử nghiệm mô hình | Pain lớn, xảy ra trực tiếp khi build/evaluate AI và có metric thời gian rõ ràng. | Chưa đo đủ số lần thử nghiệm và chưa xác minh thời gian 60 phút là mức điển hình. |
| 2 | Làm rõ điều kiện môi trường và schema I/O khi nhận module từ đồng đội | Ảnh hưởng trực tiếp đến tốc độ tích hợp và có thể kiểm chứng qua các ca bàn giao thực tế. | Chưa tách được phần thời gian do chờ phản hồi khỏi phần debug và sửa wrapper. |
| 3 | Phát hiện blocker kỹ thuật sớm khi theo dõi tiến độ dự án | Nếu phát hiện muộn sẽ ảnh hưởng cả milestone và nhiều thành viên trong nhóm. | Chưa có định nghĩa thống nhất về thời điểm blocker bắt đầu, được phát hiện và được xử lý. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đánh giá kết quả nhiều lần thử nghiệm mô hình, tôi muốn liên kết cấu hình tham số, dữ liệu và metric, để chọn được mô hình tối ưu nhanh chóng và có căn cứ vững chắc. |
| Actor | Thành viên phụ trách thử nghiệm và đánh giá ML/AI |
| Thời điểm / bối cảnh | Sau khi chạy nhiều lần train/evaluation với các config và tập dữ liệu khác nhau. |
| Quy trình hiện tại (3–7 bước) | 1. Chạy train → 2. Chép log/metric → 3. Lục lại config cũ → 4. So sánh và viết nhận xét |
| Bottleneck (bước nào, mất bao nhiêu phút) | Lục tìm config và đối chiếu log, khoảng 60 phút mỗi lần đánh giá. |
| Impact (nếu không giải thì sao) | Chọn mô hình chậm, thiếu căn cứ; có nguy cơ bỏ sót kết quả tốt hoặc lặp lại thử nghiệm. |
| Success metric (baseline → target) | Thời gian liên kết và so sánh một lần thử nghiệm: 60 phút → 5 phút. |
| Phương án không dùng AI | Quy ước lưu config/log, đặt tên thống nhất và bảng tracking cho mỗi lần chạy. |
| Giả thuyết về AI (nếu có) | Chưa xác định; chỉ xem xét sau khi workflow và rule đơn giản không đạt mục tiêu. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Chạy train → Chép log/metric → Lục config cũ → So sánh kết quả → Viết nhận xét
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận code, dữ liệu hoặc model từ đồng đội, tôi muốn biết rõ điều kiện môi trường và schema I/O, để tích hợp trơn tru và tránh lỗi phát sinh do sai giả định. |
| Actor | Người tích hợp module và người bàn giao module |
| Thời điểm / bối cảnh | Khi kéo artifact từ đồng đội về và tích hợp vào môi trường local hoặc project chung. |
| Quy trình hiện tại (3–7 bước) | 1. Kéo artifact → 2. Chạy thử local → 3. Gặp lỗi schema/environment và chat hỏi → 4. Viết code wrapper |
| Bottleneck (bước nào, mất bao nhiêu phút) | Trao đổi làm rõ schema và debug lỗi, khoảng 90 phút mỗi lần bàn giao. |
| Impact (nếu không giải thì sao) | Tích hợp chậm, phát sinh lỗi do sai giả định và làm gián đoạn công việc của cả người nhận lẫn người bàn giao. |
| Success metric (baseline → target) | Thời gian tích hợp một module: 90 phút → 30 phút. |
| Phương án không dùng AI | Contract/schema bắt buộc, README bàn giao, checklist environment và validation đầu vào/đầu ra. |
| Giả thuyết về AI (nếu có) | Chưa xác định; cần kiểm tra trước liệu contract và validation có giải quyết được phần lớn lỗi hay không. |
| Cảm nhận nhanh | Rule + Workflow |

Quy trình nháp hiện tại:

```text
Kéo artifact → Chạy thử local → Phát hiện lỗi schema/environment → Chat hỏi → Viết wrapper → Chạy lại
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi theo dõi tiến độ tổng thể dự án, tôi muốn biết chính xác các đầu việc đang bị nghẽn (blocker), để điều phối hỗ trợ kịp thời trước khi vỡ kế hoạch milestone. |
| Actor | Trưởng nhóm; toàn bộ thành viên chịu ảnh hưởng khi blocker kéo dài |
| Thời điểm / bối cảnh | Trong các lần cập nhật tiến độ và trước các mốc milestone của project. |
| Quy trình hiện tại (3–7 bước) | 1. Kiểm tra task → 2. Nhận cập nhật chung chung → 3. Phát hiện blocker muộn → 4. Họp khẩn cấp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Trễ phát hiện blocker kỹ thuật, có thể kéo dài khoảng 1.440 phút (24 giờ) mỗi lần. |
| Impact (nếu không giải thì sao) | Hỗ trợ đến muộn, milestone bị đe dọa và nhiều thành viên có thể bị chặn theo. |
| Success metric (baseline → target) | Thời gian từ khi blocker xuất hiện đến khi được nhận diện: 1.440 phút → 360 phút. |
| Phương án không dùng AI | Trạng thái task chuẩn, owner bắt buộc, nhịp cập nhật định kỳ và quy tắc cảnh báo task quá hạn. |
| Giả thuyết về AI (nếu có) | Chưa xác định; chỉ xem xét sau khi dữ liệu trạng thái và rule cảnh báo cơ bản hoạt động ổn định. |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
Kiểm tra task → Nhận cập nhật chung chung → Phát hiện blocker muộn → Họp khẩn cấp → Điều phối hỗ trợ
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Đây là vấn đề tôi muốn pitch nhất vì pain lặp lại trong quá trình build/evaluate AI và có mục tiêu giảm thời gian cụ thể.
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 chưa xác định actor đủ cụ thể; “thành viên thử nghiệm & đánh giá” còn rộng. | Có | Xác định actor chính là người phụ trách chạy và đánh giá thí nghiệm ML/AI. |
| Card #1 gộp “lục config” và “đối chiếu log”; bottleneck chưa phải một bước duy nhất. | Có | Tách riêng hai bước và ghi nhận thời gian của từng bước trong một lần thử nghiệm thực tế. |
| Card #1 chưa có mốc đo rõ ràng cho 60 → 5 phút và chưa chứng minh đã thử workflow không AI. | Có | Định nghĩa thời điểm bắt đầu/kết thúc; kiểm tra trước phương án quy ước lưu config, log và bảng tracking. |
| Card #2 chưa có bằng chứng từ một ca bàn giao cụ thể; actor người tích hợp/người bàn giao còn rộng. | Có | Ghi lại một ca tích hợp thực tế, artifact, lỗi schema/environment và người chịu pain chính. |
| Card #2 gộp trao đổi làm rõ schema với debug; metric 90 → 30 phút chưa nêu rõ có tính thời gian chờ hay không. | Có | Tách thời gian chờ và thời gian thao tác; đo riêng thời gian xác minh schema, sửa wrapper và chạy thử. |
| Card #3 mô tả “phát hiện blocker muộn” như hậu quả, chưa xác định bước và thời điểm đo cụ thể. | Có | Xác định actor chính là trưởng nhóm, định nghĩa blocker bắt đầu/kết thúc và thử trước nhịp cập nhật, owner, trạng thái chuẩn. |
| Cả ba card đều có nguy cơ nhảy sang AI trước khi kiểm tra rule/workflow hoặc validation đơn giản. | Có | Bổ sung phương án không AI và chỉ xem xét AI nếu các cách này không đạt metric mục tiêu. |

---

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
| Problem Statement | Viết Problem Statement v1 với actor, quy trình sàng lọc, baseline ước tính, mục tiêu, boundary và tiêu chí đánh giá. | Mục 7 báo cáo nhóm; tách rõ thời gian đến quyết định sàng lọc đã kiểm tra nguồn khỏi thời gian tạo bản trích xuất. |
| Mức can thiệp AI | So sánh No AI, Rule, Workflow, Agent; xác định Workflow là mức đề xuất để thử nghiệm, người nghiên cứu quyết định cuối cùng. | Mục 6 báo cáo nhóm; có AI Canvas và phương án đối chứng không dùng AI. |
| Quyết định | Đánh giá bốn rủi ro Value, Usability, Feasibility, Viability và đề xuất Not Yet cùng bước kiểm chứng, pilot và ngưỡng dừng. | Mục 8 báo cáo nhóm; chưa triển khai khi baseline và giá trị tăng thêm của AI chưa được đo. |
| Hạn chế và hướng tiếp theo | Bổ sung các giới hạn của baseline, kiểm chứng người dùng, phương án không AI, chất lượng PDF và phạm vi sàng lọc; nêu kế hoạch đo và thử nghiệm tiếp. | Mục 9 báo cáo nhóm; các điểm chưa có bằng chứng được ghi rõ. |
| Tài liệu tham khảo | Bổ sung sáu tài liệu và nêu mục đích sử dụng, gồm Anthropic, Google PAIR, RAG, Zotero và PRISMA. | Mục 10 báo cáo nhóm; PRISMA chỉ dùng khi thực hiện systematic review, RAG không được xem là bằng chứng về độ chính xác của công cụ nhóm. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý vấn đề theo bốn lăng kính. | Có thêm năm ý phù hợp để đưa vào bảng scan. | Một số ý đã được giải quyết hoặc chưa xảy ra với tôi. | Giữ ý 1, 4, 10, 12, 14; bỏ các ý còn lại theo trải nghiệm hiện tại. |
| CP2 Problem Card | Nhờ AI đóng vai product manager hoài nghi để phản biện ba card. | Chỉ ra actor còn rộng, quy trình và bottleneck chưa được xác minh, metric thiếu định nghĩa. | Phản biện chưa cung cấp bằng chứng thực địa hay thời gian đo thật. | Ghi nhận điều chưa chắc, phương án không AI và các phép đo cần kiểm tra trong mục phản biện. |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | Dùng AI hỗ trợ đưa nội dung CP6 đã soạn vào cấu trúc báo cáo nhóm và bổ sung nguồn tham khảo. | Giúp trình bày ma trận bốn mức, AI Canvas, Problem Statement v1, rủi ro và kết luận nhất quán. | AI không thể xác nhận baseline 60–120 phút/bài hoặc hiệu quả của Workflow khi chưa có pilot. | Giữ baseline là ước tính, chọn Not Yet và yêu cầu so sánh với checklist không dùng AI trước khi triển khai. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

> Bản nháp giả định theo ngôi thứ nhất; cần đối chiếu và viết lại bằng trải nghiệm thật trước khi nộp.

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Tôi nhận ra cùng một chủ đề nghiên cứu có thể chứa nhiều pain khác nhau. Khi nghe các bạn trình bày, tôi chú ý hơn đến actor, bước nghẽn và bằng chứng, thay vì chỉ chọn vấn đề nghe hấp dẫn hoặc dễ xây sản phẩm.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có lúc tôi nghĩ ngay đến AI đọc và tóm tắt PDF. Khi so sánh với checklist và literature matrix, tôi thấy nhóm chưa chứng minh được AI cần thiết. Vì vậy, chúng tôi giữ phương án không AI để đối chứng và quyết định Not Yet.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Ban đầu tôi xem mốc 60–120 phút mỗi bài như baseline đáng tin. Sau phản biện, tôi nhận ra đó chỉ là ước tính và chưa rõ đo đến lúc trích xuất hay đến quyết định sàng lọc. Tôi sửa metric theo mốc thứ hai và đề xuất bấm giờ.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Phần research khiến tôi chú ý rằng Zotero đã hỗ trợ chú thích PDF và liên kết ghi chú về nguồn gốc. Điều đó làm phương án không AI mạnh hơn tôi tưởng. Nhóm chưa có kết quả phỏng vấn hay số đo thực tế, nên tôi chưa thể kết luận người dùng cần Workflow.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là thu hẹp từ “đọc và tổng hợp nhiều bài” thành đúng bước sàng lọc từng bài. Nếu không xác định điểm bắt đầu và kết thúc, mục tiêu dưới 30 phút sẽ không so sánh được với baseline; tôi cũng phải ghi rõ AI không được tự loại bài.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ bấm giờ vài bài và hỏi người từng sàng lọc tài liệu trước khi chọn mức can thiệp. Tôi cũng sẽ hỏi nhóm liệu checklist, Zotero và literature matrix đã đủ tốt chưa, đồng thời yêu cầu kiểm tra kỹ các trường hợp AI bỏ sót bài liên quan.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- Sáu nguồn tham khảo cho phần CP6 và hướng tiếp theo được liệt kê, kèm phạm vi sử dụng, tại [mục 10 của báo cáo nhóm](../team/group_report.md#10-tài-liệu-tham-khảo).

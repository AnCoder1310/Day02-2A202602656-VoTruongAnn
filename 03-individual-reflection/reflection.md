# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên:Võ Trường An
- Mã học viên:2A202602656
- Nhóm:Vanno
- Candidate problem nhóm chọn:Sinh viên và khách đến VinUni gặp khó khăn khi tìm phòng học/hội trường trong tòa nhà phức tạp và tìm quán ăn phù hợp quanh Ocean Park vì thông tin indoor map và tiện nghi xung quanh bị phân tán.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đưa ra các vấn đề về debug frontend/backend/database, tìm file/module trong codebase và setup project. | Bổ sung Cluster C, cho thấy pattern developer workflow có nhiều người cùng gặp. |
| Pitch Problem Card | Trình bày pain của developer khi debug nhiều layer và khi phải tìm đúng file/module trong project lớn. | Nhóm nhận ra workflow developer rõ nhưng cần repo/log thật để validate. |
| Challenge bài của bạn khác | So sánh các candidate về actor, workflow, metric và khả năng làm trong lab. | Giúp phân biệt problem có evidence với problem mới chỉ là ý tưởng giải pháp. |
| Gom trùng / cluster | Đưa các candidate developer vào Cluster C cùng Quang. | Làm rõ pattern chung: developer mất thời gian tìm hiểu, truy vết và xử lý codebase. |
| Chọn candidate problem | Tham gia chấm điểm và so sánh Campus navigation với developer workflow và các candidate khác. | Đồng thuận chọn Campus navigation làm final candidate. |
| Validation / research | **Bạn cần điền theo việc bạn thực sự đã làm, không nên tự bịa.** | |
| Workflow nhóm | Góp góc nhìn về việc xác định actor, bottleneck, metric và boundary trong workflow. | Workflow được cụ thể hóa thành current state → future state và có human boundary. |
| Problem Statement | Góp ý về metric/boundary, đặc biệt việc phân biệt estimate với baseline đã validate. | PS v0/v1 ghi rõ 15–20 phút mới là estimate và cần đo lại. |
| Rule / Workflow / Agent | Đánh giá bài toán từ góc nhìn developer/AI và tham gia so sánh Rule, Workflow, Agent. | Nhóm chọn Workflow thay vì Agent; Rule được giữ cho các bước deterministic. |
| Decision | Tham gia đánh giá Go / Not Yet / No-Go. | Nhóm chốt **Not Yet** vì baseline, data và data owner chưa được xác nhận. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý/kiểm tra cách diễn đạt candidate problem. | Giúp nhìn lại problem dưới góc actor, pain, bottleneck. | AI dễ làm problem nghe chung chung. | Tôi giữ pain developer cụ thể: debug nhiều layer, tìm file/module. |
| Problem Card | Kiểm tra problem có đủ actor, bottleneck, metric chưa. | Giúp phát hiện phần còn thiếu. | AI không biết pain đó có thật với tôi hay không. | Tôi dựa vào trải nghiệm làm project để xác định pain. |
| Workflow | Gợi ý cách biểu diễn Current → Future State. | Giúp nhận ra bottleneck và human boundary. | AI có thể đề xuất workflow quá lý tưởng. | Tôi giữ developer/user là người verify kết quả. |
| Research | Nếu có dùng AI để tìm/gợi ý solution. | Giúp mở rộng các pattern có thể so sánh. | Không được lấy số liệu/link AI đưa mà chưa kiểm chứng. | Tôi giữ các claim chưa verify ở dạng giả định/Not Yet. |
| Problem Statement | Gợi ý kiểm tra Actor → Workflow → Bottleneck → Impact → Metric → Boundary. | Giúp phát hiện PS còn mơ hồ. | AI không thể xác nhận baseline thực tế. | Tôi giữ 15–20 phút là estimate, không coi là baseline. |
| Rule / Workflow / Agent | So sánh mức AI phù hợp. | Giúp nhìn ra Agent chưa cần thiết. | AI thường dễ nghiêng về Agent vì nghe mạnh hơn. | Tôi chọn Workflow và giữ Rule cho phần deterministic. |
| Decision | Kiểm tra logic Go/Not Yet/No-Go. | Giúp tìm điều kiện còn thiếu. | AI không thể thay nhóm xác nhận dữ liệu campus. | Tôi giữ **Not Yet** vì chưa có validation/data owner. |

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



```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI


# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Anh Quân
- Mã học viên: 2A202602598
- Nhóm: 
- Candidate problem nhóm chọn: 

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 8 problems theo 4 lăng kính, bấm giờ 2 lần thực tế để có số (weekly report: 40', gộp bài: 70'), ghi quote trực tiếp từ thành viên nhóm | Có 8 dòng đủ actor + số đo; 2 quotes thật làm bằng chứng cho nhóm tin vào pain |
| Pitch Problem Card | Pitch Card #1 (weekly report) trong 2 phút: mở bằng số 40' vs 13', vẽ nhanh workflow 7 bước trên giấy, kết bằng 2 câu hỏi tự challenge | Nhóm thấy Card #1 có workflow rõ nhất; được chọn vào shortlist để thảo luận thêm |
| Challenge bài của bạn khác | Hỏi thẳng vào metric khi bạn pitch: "Bạn đo 'dễ hiểu hơn' bằng gì? Ai đo? Bao giờ đo?" — không để câu impact chung chung trôi qua | Bạn đó sửa lại metric cụ thể hơn trước khi nhóm score; nhóm hình thành thói quen hỏi metric sau mỗi pitch |
| Gom trùng / cluster | Nhận ra Card weekly report của tôi và Card "viết meeting recap" của bạn khác cùng cluster: đều là "tổng hợp văn bản từ nhiều nguồn rời rạc" — đề nghị gom | Nhóm tiết kiệm được 1 slot thảo luận; tập trung vào 1 candidate thay vì 2 |
| Chọn candidate problem | Điền bảng score 1–5 cho 3 candidate shortlist; giải thích vì sao cho "Làm được trong lab" điểm thấp hơn ở bài quá rộng | Nhóm có dữ liệu rõ để so sánh, tránh chọn theo cảm tính |
| Validation / research | Hỏi trực tiếp 2 intern khác trong lớp: "Tuần trước mất bao lâu viết report? Bạn làm thế nào?" — ghi lại câu trả lời vào notes | Xác nhận pain có thật bên ngoài nhóm mình; 1 bạn nói mất 45' và "làm đại" = signal đủ mạnh |
| Workflow nhóm | Vẽ bản CURRENT STATE 7 bước lên giấy rồi chụp ảnh; đề xuất thêm bước "Lục Git" mà bản đầu nhóm bỏ quên | Workflow nhóm sát thực tế hơn; nhóm thêm Git vào input list cho AI hypothesis |
| Problem Statement | Đề xuất tách boundary rõ: "AI chỉ draft, intern phải review và ký tên vào report trước khi gửi" — ngăn nhóm để AI gửi thẳng | Boundary trong PS v1 có câu cụ thể về human sign-off; mentor review khen phần này |
| Rule / Workflow / Agent | Lên tiếng khi nhóm muốn nhảy thẳng vào Agent: "Bước nào cần AI tự quyết định bước tiếp theo? Không có → Workflow là đủ" | Nhóm chọn Workflow thay vì Agent; tránh over-engineer solution |
| Decision | Điền bảng Final Decision, nhấn mạnh "Not Yet" vì baseline chưa đo đủ mẫu (chỉ có 2–3 lần bấm giờ, cần ít nhất 5) | Quyết định cuối là Not Yet + pilot plan cụ thể, không phải Go mù |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi đề xuất boundary "intern phải review và ký tên vào report trước khi gửi"
và câu hỏi tự challenge về habit Notion — cả hai xuất hiện nguyên văn trong
Problem Statement v1 và phần AI phản biện Card #1.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi thêm gợi ý problem sau khi tự scan 5 cái đầu | Gợi ý thêm 2 ý có trải nghiệm thật tương ứng: feedback comment rải rác (#6) và quy ước ngầm nhóm (#8) | Gợi ý "tự động lên lịch họp" — nhóm dùng Doodle, không phải pain thật | Bỏ ý đó; chỉ giữ ý có trải nghiệm thật của mình |
| Problem Card | Nhờ AI đóng vai skeptical PM để phản biện Card #1 | Chỉ ra 4 điểm yếu có giá trị: actor rộng, metric chưa đo baseline, non-AI alternative chưa thử, rủi ro adoption | AI không biết mentor cụ thể của nhóm có chấp nhận AI report không — đưa ra giả định chung chung | Tôi tự thêm bước "hỏi mentor trực tiếp" vào phần validate; AI không thể làm thay bước này |
| Workflow | Hỏi AI gợi ý bước nào trong workflow có thể tự động hóa | Gợi ý đúng: pull Git commits và Notion task done là input khả thi | AI đề xuất "tự động pull Slack messages" — privacy issue, công ty không cho phép pull Slack theo batch | Giữ Notion + Git; bỏ Slack vì policy; bổ sung fallback nếu intern không update Notion đều |
| Research | Hỏi AI về tool tương tự đã giải bài toán weekly report | Liệt kê được 3 tool tương tự (Standup.ly, Range, Geekbot) có hướng đúng | AI đưa số liệu adoption không có nguồn kiểm chứng được | Không dùng số AI đưa; tự search và chỉ giữ thông tin có link thật |
| Problem Statement | Nhờ AI phản biện PS v0: "field nào còn mơ hồ?" | Chỉ đúng: boundary field chưa rõ ai là người cuối cùng approve report | AI viết lại PS thay vì chỉ đặt câu hỏi — làm ngược yêu cầu prompt | Bỏ bản AI viết lại; chỉ lấy câu hỏi phản biện, tự viết lại PS v1 |
| Rule / Workflow / Agent | Hỏi AI phân tích bài toán nằm ở ô nào trong ma trận độ mơ hồ × độ phức tạp | Phân tích đúng: độ mơ hồ cao (output report mỗi tuần khác nhau) + phức tạp trung bình → Workflow phù hợp | AI gợi ý "có thể thử Agent vì nhiều nguồn dữ liệu" — không phân biệt "nhiều nguồn" ≠ "cần tự lập kế hoạch" | Giải thích lại cho nhóm: Workflow điều phối nhiều nguồn vẫn là Workflow, không phải Agent |
| Decision | Không dùng AI | — | — | Tự điền bảng Final Decision dựa trên thảo luận nhóm và dữ liệu validate; Decision là kết quả của cả nhóm sau thảo luận thật, AI không có context đó |

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
Điều tôi nhớ nhất từ buổi lab này không phải là Card của mình, mà là lúc
nghe bạn pitch vấn đề "onboarding tài liệu dày" — pain gần giống Card #3
của tôi nhưng bạn đó lại tìm ra một bằng chứng tôi không nghĩ tới: họ đếm
số lần hỏi lại trong Discord theo tuần, không phải bấm giờ. Tôi mới nhận
ra mình đã bỏ sót một nguồn evidence rất tự nhiên — log chat đang có sẵn
rồi, không cần bấm giờ thêm. Đó là lúc tôi thấy giá trị của việc nghe
người khác scan cùng một vùng vấn đề với góc nhìn khác.

Nhóm tôi có một lần bị solution-first rõ ràng: khi bạn trong nhóm nói
"hay mình làm Agent đi, cho nó tự biết pull từ đâu mỗi tuần" — câu đó
xuất hiện trước khi nhóm thậm chí đồng ý xong về bottleneck là gì. Tôi
hỏi lại: "Bước nào AI cần tự quyết định bước tiếp theo không?" và không
ai trả lời được cụ thể. Từ đó nhóm quay về vẽ lại workflow trước, rồi mới
quyết định Workflow là đủ. Nếu không hỏi câu đó, rất có thể nhóm đã mất
30 phút tiếp theo thiết kế thứ quá phức tạp cho bài toán này.

Phần tôi thấy mình đóng góp thật sự nhất là boundary trong Problem Statement
v1. Ban đầu nhóm viết "AI sẽ tổng hợp và gửi report" — tôi đề nghị sửa
thành "AI chỉ draft, intern phải review và ký tên vào report trước khi gửi".
Câu đó nghe có vẻ nhỏ nhưng thay đổi toàn bộ rủi ro của thiết kế: nếu AI
gửi thẳng, mentor không biết intern có hiểu nội dung report của mình không.

Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về baseline. Chúng tôi nói
"30–50 phút" mà không ai bấm giờ đủ 5 lần để có trung bình tin cậy — tôi
biết điều đó ngay từ đầu nhưng đã không đẩy nhóm dừng lại để đo trước
khi tiếp tục. Tôi sẽ đề xuất: "Trước khi sang Phase 4, mỗi người bấm giờ
thật lần này và lần sau — rồi mình mới có số thật để pitch."
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

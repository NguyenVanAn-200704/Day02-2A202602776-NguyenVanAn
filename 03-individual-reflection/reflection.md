# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Văn An
- Mã học viên: 2A202602776
- Nhóm: Nhóm Day 02 (Thành viên: Nguyễn Văn An, Lưu Xuân Dũng, Tạ Quang Dũng, Trương Thị Lan Anh, Hoàng Bích Ngọc)
- Candidate problem nhóm chọn: Quản lý tồn kho thực phẩm gia đình nhằm giảm thiểu lãng phí do thực phẩm bị quên, hỏng hoặc hết hạn trước khi sử dụng.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                                             | Kết quả / ảnh hưởng tới nhóm                                                                                                                                        |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scan cá nhân               | Tự scan 10 problems thuộc 4 lăng kính, dùng Claude mở rộng góc nhìn và lọc ra 3 Problem Cards (Thủ tục hành chính, Sàng lọc CV, Sinh viên tìm việc).                     | Nhóm có thêm 3 candidate đa dạng từ góc nhìn tuyển dụng, sinh viên và dịch vụ công để đưa vào kho ý tưởng chung.                                                    |
| Pitch Problem Card         | Pitch Card #1 (Chatbot tư vấn giấy tờ hành chính công chứng) với điểm nhấn là bottleneck người dân phải đi lại nhiều lần và rủi ro pháp lý nếu AI tư vấn sai.            | Mở ra cuộc thảo luận sâu trong nhóm về rủi ro đạo đức/pháp lý khi AI can thiệp vào các lĩnh vực nhạy cảm, giúp nhóm thận trọng hơn khi chọn đề tài.                 |
| Challenge bài của bạn khác | Challenge bài Weekly Report của Xuân Dũng/Quang Dũng (lấy data từ Git/Jira quá phân tán) và bài Thực phẩm của Lan Anh: "Nếu bắt nhập tay từng món thì ai kiên trì dùng?" | Giúp nhóm loại bỏ các bài toán có độ phức tạp tích hợp quá cao trong 4 tiếng lab, đồng thời chỉ ra friction nhập liệu là tử huyệt của bài toán thực phẩm.           |
| Gom trùng / cluster        | Cùng Lan Anh và Dũng gom 15 candidates thành 4 cụm (A, B, C, D); chỉ ra Candidate 1 và 4 bản chất là cùng một bài toán về báo cáo định kỳ.                               | Giảm từ 15 candidate xuống còn 4 cụm rõ ràng, giúp nhóm không bị loãng và tiết kiệm thời gian hội tụ.                                                               |
| Chọn candidate problem     | Tham gia chấm điểm ma trận 7 tiêu chí; bảo vệ quan điểm chọn bài Quản lý thực phẩm vì actor gần gũi, workflow đời sống dễ bóc tách và kiểm chứng được.                   | Nhóm đạt đồng thuận cao (34/35 điểm) chọn bài Quản lý thực phẩm để đi tiếp vào Phase 4, thay vì tranh cãi kéo dài.                                                  |
| Validation / research      | Đóng góp góc nhìn về friction nhập liệu từ kinh nghiệm cá nhân; cùng nhóm phân tích app NoWaste và USDA FoodKeeper.                                                      | Nhận ra không được để LLM tự "bịa" ngày hết hạn cho thực phẩm tươi sống; phải dùng database chuẩn và bắt buộc người dùng xác nhận dữ liệu scan.                     |
| Workflow nhóm              | Đảm nhận vai trò chính (cùng Lưu Xuân Dũng) vẽ Current Workflow 7 bước và Future Workflow 9 bước; phân định rõ ranh giới Machine/Rule - AI - Human.                      | Tạo ra bộ khung workflow trước/sau hoàn chỉnh, xác định chính xác bottleneck và chốt AI chỉ can thiệp vào bước gợi ý món ăn, giữ con người làm boundary kiểm soát.  |
| Problem Statement          | Phản biện cùng nhóm để siết từ v0 sang v1; yêu cầu làm rõ boundary "AI không tự mua hàng, không tự xóa kho" và siết chặt đối tượng hưởng lợi.                            | Problem Statement v1 chặt chẽ hơn, định rõ actor là người nấu ăn chính trong gia đình 1-4 người (≥4 bữa/tuần) và metric gắn trực tiếp với lượng thực phẩm bỏ đi.    |
| Rule / Workflow / Agent    | Đề xuất và lập luận chọn giải pháp mức Workflow; phản bác ý tưởng làm AI Agent tự động lên đơn đi chợ hoặc quản lý toàn bộ bếp.                                          | Nhóm thống nhất chọn mức Workflow: dùng Rule để cảnh báo hạn, AI gợi ý món ăn từ đồ sắp hết hạn, tránh sa đà vào Agent phức tạp, tốn kém và rủi ro cao.             |
| Decision                   | Cùng nhóm rà soát 6 câu hỏi điều kiện tiên quyết và thống nhất quyết định "Not Yet" thay vì vội vàng "Go".                                                               | Tránh cho nhóm cái bẫy "solution-first"; xác định rõ 2 việc sống còn phải validate trước khi code: người dùng có chịu nhập liệu không và baseline lãng phí thực tế. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi nằm ở bản thiết kế Future Workflow 9 bước và bảng phân chia ranh giới Rule - AI - Human, nơi tôi kiên quyết giới hạn AI chỉ đóng vai trò gợi ý công thức nấu ăn dựa trên nguyên liệu sắp hết hạn, giữ khâu xác thực dữ liệu và quyết định sử dụng hoàn toàn cho người dùng để triệt tiêu rủi ro an toàn thực phẩm.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì?                                                                      | AI hữu ích ở đâu?                                                                                           | AI sai / hời hợt ở đâu?                                                                                                                                  | Tôi sửa gì bằng nhận định của mình?                                                                                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scan                    | Dùng Claude gợi ý thêm 20 problem thực tế trong bối cảnh tuyển dụng và đời sống             | Gợi ý thêm nhiều góc nhìn đa dạng từ HR recruiter, nhân viên CSKH và quy trình văn phòng                    | Gợi ý các đề tài chung chung, sáo rỗng như "Trợ lý AI viết lại toàn bộ CV và cover letter tự động" mà không gắn với quy trình hay đo lường cụ thể        | Loại bỏ các ý tưởng viển vông; chỉ giữ lại những vấn đề bản thân từng trải nghiệm hoặc quan sát được dấu hiệu thật (như người dân đi làm thủ tục hành chính, sinh viên lọc job).             |
| Problem Card            | Nhờ AI phản biện và tìm điểm yếu của Problem Card #1 (Chatbot tư vấn thủ tục hành chính)    | Chỉ ra rất đúng rằng phần impact (% hồ sơ bị trả) của tôi mới là phỏng đoán, chưa có số liệu thực tế        | AI có xu hướng xúi giục "nâng cấp lên Agent tự động nộp hồ sơ công", bỏ qua hoàn toàn rào cản pháp lý và chữ ký số thực tế                               | Giữ nguyên mức Workflow; bổ sung kế hoạch phỏng vấn cán bộ một cửa ở Phase 4 và ghim chặt boundary: AI chỉ hỗ trợ tra cứu danh mục, tuyệt đối không tự diễn giải luật.                       |
| Workflow                | Nhờ AI rà soát luồng công việc trước/sau của bài toán quản lý thực phẩm                     | Giúp liệt kê đầy đủ các trạng thái chuyển giao thông tin (input/output) giữa các bước                       | AI đề xuất giải pháp phi thực tế: "lắp camera AI nhận diện đồ ăn trong tủ lạnh theo thời gian thực" — quá đắt đỏ và không khả thi cho gia đình phổ thông | Gạt bỏ ý tưởng camera; thiết kế lại flow với luồng barcode/receipt scan kèm bước human confirmation (người dùng bấm xác nhận), đưa chi phí và độ phức tạp về mức tối thiểu.                  |
| Research                | Dùng công cụ tìm kiếm và AI để tra cứu các ứng dụng quản lý thực phẩm đã có trên thị trường | Nhanh chóng tìm ra các case study thực tế như NoWaste, Fridgely, Samsung Food và bộ dữ liệu USDA FoodKeeper | AI trích dẫn các con số marketing một chiều như "tiết kiệm 50% chi tiêu" mà không kiểm chứng được phương pháp đo lường                                   | Bỏ qua các tuyên bố quảng cáo; tập trung đọc các review tiêu cực của người dùng trên App Store để rút ra insight: người dùng bỏ cuộc vì việc nhập inventory quá cực đoan và tốn công.        |
| Problem Statement       | Nhờ AI đóng vai "reviewer khó tính" chỉ ra các chỗ mơ hồ trong Problem Statement v0         | Phát hiện ra định nghĩa Actor của nhóm ban đầu quá rộng (người sống 1 mình rất khác hộ gia đình 4 người)    | AI gợi ý các metric mơ hồ kiểu "tăng mức độ hài lòng của người dùng lên 85%" hoặc "tối ưu hóa trải nghiệm nấu nướng"                                     | Bác bỏ gợi ý của AI; cùng nhóm định nghĩa lại metric chuẩn kỹ thuật: giảm ≥30% khối lượng/tiền thực phẩm bỏ đi và tỷ lệ ≥70% gợi ý món ăn được người dùng thực nấu.                          |
| Rule / Workflow / Agent | Hỏi AI để phản biện ranh giới giữa Rule, Workflow và Agent cho bài toán này                 | Cung cấp bộ khung 5 câu hỏi sắc bén để đánh giá độ phức tạp và độ mơ hồ của bài toán                        | AI thiên vị phương án Agent, lập luận rằng "Agent tự động đặt hàng siêu thị khi đồ hết hạn mới thể hiện hết sức mạnh của AI"                             | Tôi phản bác: việc tự động đặt hàng vi phạm nguyên tắc kiểm soát chi tiêu và sở thích của người dùng; tôi giữ vững lập luận chỉ chọn Workflow để an toàn, dễ debug và chi phí vận hành thấp. |
| Decision                | Không dùng AI                                                                               | Không dùng                                                                                                  | Không áp dụng (AI luôn có xu hướng thúc đẩy "Go" để trình diễn giải pháp)                                                                                | Nhóm tự thảo luận nội bộ dựa trên 6 câu hỏi checklist; chúng tôi chọn "Not Yet" vì nhận thức rõ: input data chưa sẵn sàng thì AI dù giỏi đến mấy cũng thất bại.                              |

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
Quá trình làm việc từ Phase 1 đến Phase 7 đã thay đổi hoàn toàn tư duy của tôi về việc ứng dụng AI: từ chỗ háo hức muốn xây dựng những thứ phức tạp sang việc cẩn trọng nhìn vào con người, quy trình và dữ liệu. Khi nghe top 3 candidate problems của các bạn trong nhóm, tôi học được cách nhìn đa chiều từ những nỗi đau thực tế của developer đến sinh viên hay người nội trợ. Tuy nhiên, nhóm tôi đã có lúc suýt rơi vào cái bẫy solution-first quen thuộc khi một số bạn ban đầu rất hào hứng muốn xây dựng một "Super Agent" tự động đọc hình ảnh tủ lạnh và tự đặt hàng siêu thị. Với vai trò là người phụ trách thiết kế workflow, tôi đã trực tiếp vẽ luồng hiện tại và tương lai để phản biện lại kỳ vọng đó. Tôi chỉ ra rằng nếu người dùng thấy phiền hà khi phải nhập liệu danh mục thực phẩm thì mọi thuật toán phức tạp phía sau đều sụp đổ ngay từ bước đầu tiên. Dấu ấn rõ nét nhất của tôi trong bản nộp nhóm chính là việc kiên quyết kéo giải pháp về mức Workflow và xác lập ranh giới kiểm soát (human boundary) nghiêm ngặt. Theo đó, Rule sẽ đảm nhiệm việc lọc hạn dùng, AI chỉ thuần túy hỗ trợ gợi ý 2-3 công thức nấu ăn từ nguyên liệu sắp hỏng, còn quyền quyết định nấu gì hay bỏ gì hoàn toàn thuộc về người dùng. Đối với tôi, điều khó nhất khi viết Problem Statement chính là xác lập Success Metric và thu hẹp Boundary, bởi việc đo lường khối lượng thực phẩm lãng phí đòi hỏi số liệu baseline thực tế chứ không thể chỉ ngồi ước đoán. Chúng tôi đã đồng thuận chọn quyết định "Not Yet" – một kết luận mà trước đây tôi có thể coi là chưa thành công, nhưng giờ tôi hiểu đó là sự dũng cảm và thực tế cần có của người làm sản phẩm khi dữ liệu chưa đủ sẵn sàng. Nếu được làm lại từ đầu, tôi sẽ thúc đẩy nhóm triển khai khảo sát và phỏng vấn người dùng sớm hơn ngay từ đầu buổi lab thay vì đến Phase 4 mới gấp rút thu thập, đồng thời mở rộng cỡ mẫu sang các hộ gia đình đông người hơn để dữ liệu baseline càng thêm vững chắc.
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

# Lịch sử thay đổi: REVIEW_FinMind_v2_20260918.html

## 2026-09-30 10:07 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/Mentor_Reviews/20260918/REVIEW_FinMind_v2_20260918`
- **Ngày và giờ:** 2026-09-30 10:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

DOCUMENT REVIEW / V1

1. Tổng quan2. Tài liệu và phạm vi3. Phát hiện4. Đối chiếu tài liệu5. Đề xuất cải thiện6. Câu hỏi phản biện7. Kế hoạch hành động8. Nguồn tham khảo

Sáng / TốiIn / Lưu PDF

Technical review · 2026-09-18

Review G2 — FinMind v2.0: đối chiếu feedback

Cần chỉnh sửa

Đọc toàn bộ 26 trang FinMind\_Project\_Proposal.pdf v2.0 và đối chiếu 14 feedback trong REVIEW\_FinMind.md ngày 2026-09-15; chưa kiểm tra code, demo, dữ liệu hay hai biểu mẫu cập nhật.

0P07P11P2

1. Tổng quan

Bản mới đã sửa đúng hướng và tiến bộ rõ rệt. Đề xuất giữ hướng Research Copilot, sửa một vòng tập trung trước khi chốt hồ sơ. Các vấn đề còn lại chủ yếu nằm ở thiết kế thí nghiệm, cách quyết định đạt/chưa đạt, một nhánh thiếu trong sơ đồ xử lý, và tính kiểm chứng của disclosure. Không cần viết lại toàn bộ proposal hoặc mở thêm chức năng.

Hai feedback P0 cũ về cam kết “không sai” và prediction thiếu thiết kế đã được xử lý ở mức tài liệu. Feedback P0 cũ về đánh giá đã có phần sửa lớn: có baseline, bộ câu hỏi, calibration/final split, audit và metric. Tuy nhiên, vẫn còn điểm cần sửa để kết quả thí nghiệm có thể diễn giải đúng. Báo cáo này không giữ nguyên mức P0 cũ một cách máy móc; các việc còn lại được ghi thành P1/P2 theo mức ảnh hưởng hiện tại.

Những phần đã sửa tốt, nên giữ

Phạm vi nhất quán hơn: tên Research Copilot; prediction, trading và khuyến nghị cá nhân hóa được đưa ra ngoài MVP. Nội dung này xuất hiện xuyên suốt phần tổng quan, objective, scope và kết luận, thay vì chỉ sửa tên đề tài. P2 tr.1–2, 5, 8–11, 25.

Bỏ bảo đảm tuyệt đối: mục Out of Scope nêu rõ không cam kết zero hallucination hay guaranteed correctness; lỗi còn lại sẽ được đo và báo cáo. P2 tr.10.

Corpus có giới hạn: 10 doanh nghiệp thuộc Banking và Technology, danh sách mã ứng viên, ba năm tài chính và bốn quý; nguồn chưa kiểm tra được ghi đúng là chưa sẵn sàng. P2 tr.5, 10, 15.

Kiến trúc cụ thể hơn: pgvector, Neo4j, Structured Retrieval, Gemini, hai lớp kiểm tra trước/sau sinh, provenance, bốn sơ đồ và tám ADR. P2 tr.16, 19–23.

Đánh giá đã thành một kế hoạch: B0–B3, 120 câu hỏi, 40 calibration/80 final, kiểm tra bởi con người, độ trễ p95 tại tải 10 người dùng, token/cost và xử lý kết quả graph không có lợi. P2 tr.9, 12–14.

Khảo sát và quản trị tốt hơn: có năm sản phẩm Việt Nam, nguồn có liên kết, thu hẹp tuyên bố tính mới; thêm bảo mật, retention, ownership và ngân sách. P2 tr.7–8, 16–18, 23–26.

Điều kiện để đóng vòng feedback này

Nhóm việc

Kết quả cần có

Thí nghiệm và nghiệm thu

Tách tác dụng graph, Structured Retrieval và lớp kiểm tra; phân biệt ngưỡng sản phẩm với giả thuyết nghiên cứu; hoàn thiện quy tắc chấm

Luồng xử lý

Bổ sung đường PASS từ Answer Verification đến câu trả lời có citation; làm rõ retry và fallback

Disclosure

Phân biệt đã dùng/dự kiến, giải thích phần trăm và dẫn đến log có thể kiểm tra

Kế hoạch

Chốt thời điểm usability test, đóng băng cấu hình cuối, lịch sprint và điều kiện hoàn thành Source Register

Giới hạn kết luận: “Đã sửa” trong báo cáo này nghĩa là vấn đề đã được xử lý trong proposal, không phải tính năng đã triển khai hay ngưỡng đã đạt. Đây vẫn là hồ sơ đề xuất. Không lấy việc chưa có kết quả cuối kỳ làm lỗi của proposal; không suy ra vi phạm sử dụng AI từ phần trăm khai báo. Không chấm lại điểm 65/100 của báo cáo cũ vì bộ rubric/form cập nhật không nằm trong đầu vào lần này.

2. Tài liệu và phạm vi

ID

Tài liệu

Cách dùng trong lần review này

P2

FinMind\_Project\_Proposal.pdf

Đọc đủ 26 trang; bìa ghi Version 2.0, ngày 16/09/2026

R1

REVIEW\_FinMind.md

Baseline feedback ngày 15/09/2026; đối chiếu F01–F14 và bảng lỗi nhất quán

H1

REVIEW\_FinMind.html

Bản trình bày của baseline, được giữ nguyên

Số trang P2 là trang vật lý PDF, tính cả bìa và mục lục; bản này in Page 1 of 26 đến Page 26 of 26. Đã trích xuất toàn bộ văn bản và kiểm tra trực tiếp hình ảnh bốn sơ đồ tr.19–22, bảng nguồn tr.15 cùng các trang bảng đánh giá/kế hoạch liên quan. Sơ đồ workflow là ảnh; kết luận F04 dựa trên việc đọc ảnh gốc, không chỉ dựa vào text extraction.

SHA-256 của PDF được review: 4461f5313f681ab17d65e4a72517ab1609aaf03905beed5e958206b1650cb679.

Ba PDF cũ được R1 dẫn chiếu hiện không còn trong workspace; chỉ có proposal mới. Vì vậy, việc so sánh bản cũ dựa trên nội dung feedback đã lưu trong R1, không phải so sánh trực tiếp từng dòng giữa hai PDF. Chưa thể xác nhận Registration Form và AI Usage Disclosure riêng đã đồng bộ với proposal mới, cũng như trạng thái ký/phê duyệt của các biểu mẫu đó.

Đã kiểm tra có chọn lọc nguồn gốc GraphRAG, tài liệu Gemini/Ragas và các trang sản phẩm dùng cho khảo sát Việt Nam. Đây là kiểm tra nguồn cho nhận xét, không phải trải nghiệm thực tế hay đánh giá nội bộ các sản phẩm cạnh tranh. Các ngưỡng và ví dụ sửa được đề xuất dưới đây không phải kết quả đo của FinMind.

3. Phát hiện

F01P1B2–B3 chưa tách được tác dụng của lớp kiểm tra khỏi Structured Retrieval

Vị trí: P2 tr.13, Table 13; tr.9 RQ1/RQ3/RQ4; tr.14 hàng Relationship correctness. Đối chiếu R1-F03 và R1-F05.

Nhận xét: B1 tắt graph, Structured Retrieval, Evidence Gate và Answer Verification. B2 thêm graph/fusion nhưng vẫn tắt hai lớp kiểm tra; B3 thêm hai lớp kiểm tra và, với numerical intents, thêm Structured Retrieval. Vì vậy, so B2 với B3 trên toàn bộ tập sẽ đồng thời thay đổi nhiều yếu tố. Table 15 còn cho phép dùng “B2 or B3” để xét cải thiện H1, trong khi B3 khác B1 nhiều hơn riêng graph.

Tác động: Nếu B3 tốt hơn, chưa thể quy phần cải thiện đó riêng cho graph hoặc Evidence Gate/Answer Verification. RQ3 hỏi tác dụng giảm unsupported claims của hai lớp kiểm tra, nhưng hiện chưa có đối chứng giữ Structured Retrieval cố định. Đây là vấn đề diễn giải thí nghiệm, không phải kết luận kiến trúc B3 sai.

Đề xuất: Chỉ định trước cặp so sánh và yếu tố thay đổi cho từng RQ. Giữ B1↔B2 để đo gói graph retrieval/fusion, với cùng corpus, generator, prompt, context budget và chính sách reranking dùng chung; ghi rõ phần thuật toán nào thuộc thay đổi được đo. Để đo hai lớp kiểm tra, thêm một cấu hình phân tích B3 có Structured Retrieval nhưng tắt Gate/Verifier, rồi so với B3 đầy đủ. Nếu không đủ nguồn lực, thu hẹp RQ3 thành báo cáo hiệu quả tổng thể B3 và nói rõ chưa cô lập đóng góp nhân quả của từng thàn...

Không cần biến đề tài thành một ma trận thí nghiệm lớn. Một đối chứng bổ sung có mục đích rõ hoặc một cách viết RQ thận trọng hơn là đủ. B0↔B1 vẫn có ích để so cách trả lời câu số liệu; cần ghi đây là so hệ thống đầu cuối, vì B0 không yêu cầu Gemini sinh tự do còn B1 có.

Điều kiện đóng: Có bảng RQ → cặp cấu hình → thành phần thay đổi → subset → metric → kết luận được phép đưa ra. Không dùng kết quả B3↔B1 để kết luận riêng “graph giúp tăng X”.

F02P1Điều kiện nghiệm thu còn lẫn với giả thuyết graph phải tốt hơn

Vị trí: P2 tr.14, Table 15 và đoạn Acceptance decision; tr.9 H1/H4; tr.24 Table 28. Đối chiếu R1-F03.

Nhận xét: Table 15 chứa cả các ngưỡng sản phẩm, mục tiêu H1 tăng ít nhất 5 điểm phần trăm và yêu cầu Quantitative Correctness “exceeds B1”. Sau bảng lại yêu cầu tất cả hard thresholds đạt để chấp nhận B3, nhưng đồng thời cho phép graph không có lợi và được tắt theo routing. Table 28 nói metric đạt hoặc sai lệch được báo cáo minh bạch. Chưa có cột nào xác định rõ đâu là hard gate, đâu là giả thuyết được phép không được ủng hộ.

Tác động: Cùng một kết quả “B3 đủ an toàn nhưng graph không cải thiện” có thể bị hiểu là đạt hoặc không đạt. Báo cáo trung thực một kết quả trung tính không tự động làm sản phẩm thất bại; ngược lại, công khai một sai lệch cũng không tự động miễn điều kiện an toàn đã chốt.

Đề xuất: Tách ba nhóm: điều kiện nghiệm thu sản phẩm; giả thuyết nghiên cứu; số đo chỉ cần báo cáo. Giữ ngưỡng độ đúng, citation, refusal, coverage và độ trễ theo quyết định của nhóm; đưa H1 và phần “tốt hơn baseline” của H4 vào nhóm giả thuyết. Đồng bộ Table 15, Acceptance decision và Table 28. Nêu cách xử lý một hard gate không đạt: sửa và đánh giá lại theo quy trình được định nghĩa, hoặc xin điều chỉnh phạm vi có ghi nhận; không chỉ ghi “đã báo cáo”.

Đoạn tắt graph sau khi nhìn kết quả final còn cần làm rõ: không dùng 80 câu final để chọn category/routing tối ưu rồi báo điểm mới trên chính 80 câu đó như kết quả độc lập. Có thể chốt routing từ calibration, hoặc báo kết quả cấu hình đã khóa trước và ghi cấu hình điều chỉnh sau final là exploratory, cần dữ liệu độc lập để xác nhận.

Điều kiện đóng: Một bảng phân loại gate/hypothesis/report-only và quy tắc thay đổi cấu hình sau final, đủ để hai người đánh giá cùng hồ sơ ra cùng quyết định.

F03P1Metric và phân bổ tập final cần đủ chi tiết để chấm nhất quán

Vị trí: P2 tr.13–14, Tables 14–15; tr.9 H1/H3/RQ5; tr.11 FR11. Đối chiếu R1-F03 và R1-F07.

Nhận xét: Bộ đánh giá đã tiến bộ đáng kể, nhưng còn thiếu một số quy tắc quyết định trực tiếp điểm đạt/chưa đạt. Citation Accuracy mô tả kiểm tra ID/URL/hash/locator với golden evidence, chưa định nghĩa rõ đơn vị chấm là cặp claim–citation có hỗ trợ đúng nghĩa. Citation Completeness chỉ yêu cầu báo cáo trong khi FR11 yêu cầu mọi material claim có nguồn. Chưa ghi chính xác số câu từng nhóm trong 40/80 split, ngôn ngữ, cách chấm partial answer, mẫu số của numerical correctness, hay cách xử lý câu ...

Tác động: Một citation đúng tài liệu nhưng gắn sai phát biểu vẫn có thể bị chấm đạt nếu chỉ so ID. Hai evaluator có thể cho kết quả khác nhau với cùng câu trả lời một phần. Nhóm nhỏ ở tập final cũng làm kết luận từ chối đúng và cải thiện 5 điểm phần trăm rất nhạy với một câu, dù tổng bộ là 120 câu.

Đề xuất: Bổ sung một phụ lục metric contract ngắn, gồm các nội dung sau.

Citation Accuracy: tử số là số cặp claim–citation mà evidence tại locator thực sự hỗ trợ đúng nội dung, công ty, kỳ, đơn vị và phạm vi báo cáo; mẫu số là tổng cặp được chấm. Cho phép evidence tương đương đã được adjudicate, không buộc chỉ một ID golden nếu có nhiều nguồn hợp lệ.

Citation Completeness: chốt rõ là gate hay report-only. Nếu vẫn giữ FR11 “every material claim”, giải thích cơ chế chặn claim không đủ nguồn và cách kiểm tra điều đó; không chỉ dựa vào việc URL tồn tại.

Quantitative Correctness: chọn đơn vị là fact hay question; quy định tolerance, câu nhiều số, thiếu số, refusal, partial answer và mẫu số bằng 0. Báo thêm answer coverage để không tăng độ đúng bằng cách chỉ trả lời rất ít câu dễ.

Công bố số câu mỗi category trong calibration/final, phân bổ Việt/Anh và các nhóm sector/period cần báo cáo. Nêu subset nào chỉ đủ mô tả khám phá. Với refusal và adversarial, chấm rõ hành vi mong đợi theo từng case, không gộp mọi phản hồi một phần thành refusal đúng.

Chốt Ragas version, evaluator model/prompt và cách tổng hợp điểm; khóa cả cấu hình chấm. Với claim hỗ trợ, citation và các ca khó cần con người, xác định ai chấm toàn bộ điểm chính và ai audit độc lập.

Về cỡ mẫu: Proposal có 25 câu relationship và 10 câu insufficient-evidence trước khi chia. Nếu phân bổ final thành 17 câu relationship thì một câu tương đương khoảng 5,9 điểm phần trăm; nếu có 7 câu refusal thì 6/7 chỉ đạt khoảng 85,7%. Đây là ví dụ minh họa, không phải số câu final đã được nhóm xác nhận. Không bắt buộc tăng ngay tổng 120; cần báo số đếm, khoảng bất định và tránh diễn giải một câu cải thiện thành bằng chứng mạnh. “Audit ít nhất 20% của 80” chỉ bảo đảm tối thiểu 16 câu audit toàn...

Ragas Faithfulness đo mức hỗ trợ của response bởi context đã truy xuất; điểm cao không tự xác minh dữ liệu gốc đúng. Noise Sensitivity dùng câu hỏi, reference, response và retrieved contexts; không nên coi một điểm Noise Sensitivity là toàn bộ bằng chứng chống prompt injection. Cần test hành vi tấn công riêng. Ragas Faithfulness, Ragas Noise Sensitivity.

Với RQ5, nên xét khoảng tin cậy của chênh lệch phù hợp với thiết kế so sánh; chỉ nhìn hai khoảng tin cậy riêng lẻ có chồng lấn hay không chưa phải một quy tắc đầy đủ để kết luận khác biệt. Nếu mẫu quá nhỏ, giữ đúng nhãn exploratory.

Điều kiện đóng: Hai người dùng cùng metric contract chấm được một bộ ví dụ đúng/sai/partial/refusal mà không phải tự đoán mẫu số hoặc điều kiện đạt.

F04P1Workflow thiếu nhánh PASS từ Answer Verification đến câu trả lời

Vị trí: P2 tr.21, Figure 3; caption nằm ở tr.22. Đối chiếu R1-F05/R1-F06; đây là lỗi quan sát trực tiếp ở sơ đồ mới.

Nhận xét: Evidence Gate có nhánh Pass vào Context Builder và nhánh fail vào Safe Fallback. Nhưng diamond Answer Verification chỉ thể hiện nhánh RETRY once và nhánh unsupported after verification; không có đường PASS sang Citation Engine hoặc Response Composer. Citation Engine có đường đi ra Response Composer nhưng không có đường vào từ câu trả lời đã được xác minh.

Tác động: Luồng thành công chưa khép kín trong tài liệu. Người triển khai không biết chính xác claim/citation đã kiểm tra được chuyển đến đâu, hoặc citation được tạo trước hay sau khi verifier kiểm tra coverage. Phần prose nói kiểm tra citation là hợp lý, nhưng sơ đồ chưa thể hiện hợp đồng đó.

Đề xuất: Vẽ đủ luồng tạo candidate claim/citation → verification → PASS → response. Cho phép Citation Engine xây ánh xạ evidence trước verifier, hoặc làm rõ Gemini trả candidate citation IDs rồi verifier kiểm tra trước khi Citation Engine định dạng link. Nhánh fail lần đầu được repair tối đa một lần; fail lần hai chuyển fallback; request chỉ được release một câu trả lời đã đạt policy hoặc một fallback có trạng thái rõ.

Đề nghị kèm một bảng bốn ca: đạt ngay; repair rồi đạt; repair vẫn thất bại; gate từ chối trước generation. Ghi output status và số lần gọi Gemini của từng ca. Đây là hợp đồng thiết kế cần bổ sung, chưa yêu cầu kết quả chạy ở giai đoạn proposal.

Structured output giúp ràng buộc cấu trúc phản hồi; Google vẫn yêu cầu ứng dụng kiểm tra giá trị và xử lý đầu ra đúng schema nhưng sai nghĩa. Vì vậy, việc có schema không thay thế được verifier ở luồng này. Gemini Structured Outputs, Best practices.

F05P1Nguồn dữ liệu đã minh bạch trạng thái nhưng chưa đủ để đóng feedback khả thi

Vị trí: P2 tr.15, mục 7.1; tr.5, 10, 18, 24 về corpus và đầu ra. Đối chiếu R1-F04 và phần dữ liệu của R1-F10.

Nhận xét: Bản mới đã nêu đúng 10 mã ứng viên và quy định Source Register; đây là phần sửa tốt. Tuy nhiên, chính tài liệu xác nhận URL issuer IR từng mã còn thiếu, nhà cung cấp OHLCV chưa được chọn, nguồn news/research chưa đóng băng và văn bản kế toán cụ thể chưa được đăng ký. Đồng thời, scope/MVP/đầu ra vẫn có dashboard giá cuối ngày và corpus ba năm/bốn quý; Table 28 thêm “as available” nhưng chưa nêu mức thiếu được chấp nhận.

Tác động: Chưa biết phần nào bắt buộc phải có để hoàn thành MVP nếu nguồn dữ liệu không được thông qua. Một snapshot CSV chỉ là fallback cụ thể khi đã có nguồn được phép dùng và ngày dữ liệu xác định. Danh sách portal chưa tự chứng minh mức bao phủ hay chất lượng trích xuất bảng.

Đề xuất: Giữ việc hoàn thiện dữ liệu ở Sprint 1 như đã dự kiến, nhưng thêm điều kiện đóng rõ: bảng company–period, URL trực tiếp, tình trạng truy cập/điều kiện sử dụng đã kiểm tra, tài liệu mẫu, metric tối thiểu, người xác nhận và phương án khi thiếu. Tách corpus lõi khỏi nguồn bổ sung. Quy định FR/dashboard nào được giảm nếu OHLCV/news chưa sẵn sàng, thay vì vừa để Should vừa coi mọi màn hình là đầu ra bắt buộc.

Một bảng 10 công ty × 7 kỳ mục tiêu tạo 70 ô theo dõi company–period; không đồng nghĩa 70 PDF, vì một tài liệu có thể chứa nhiều kỳ. Thử trích xuất trên ít nhất mẫu đại diện của mỗi ngành để kiểm tra kỳ, đơn vị, hợp nhất/riêng lẻ, rồi ước lượng effort. Mức mẫu cụ thể do nhóm chốt, không phải yêu cầu cố định của trường.

Điều kiện đóng: Có mốc chấp nhận Source Register, tiêu chí bao phủ tối thiểu và quyết định giảm scope nếu không đạt. Có thể đóng phần sửa proposal bằng một kế hoạch có điều kiện rõ; chưa được ghi “nguồn đã verified” khi bảng vẫn để pending. Review này không kết luận nguồn nào đang bị sử dụng trái phép.

F06P1Disclosure vẫn chưa giải thích phần trăm và trạng thái đã sử dụng

Vị trí: P2 tr.17–18, mục 10.2 và Tables 20–23. Đối chiếu R1-F11/F12/F13/F14.

Nhận xét: Proposal đã có disclosure trực tiếp, nêu công cụ, mục đích, cam kết review và làm chủ code. Tuy nhiên, phần mở đầu nói các giá trị intended/estimated phải được đối chiếu với actual usage log trước final submission, còn team declaration tr.18 xác nhận thông tin chính xác. Chưa phân tách từng task đã làm đến ngày nào với task dự kiến. Các tỷ lệ Backend/Core 60%, UI 70%, Testing 30%, Documentation 50% vẫn không có mẫu số hay phương pháp ước lượng.

Tác động: Người đọc chưa biết con số mô tả đóng góp thực tế hay dự tính; không thể kiểm tra sự thay đổi so với các tỷ lệ R1 đã ghi nhận. Đây là feedback còn tồn tại trực tiếp, không được coi là đã sửa chỉ vì thêm bảng vào proposal. Phần trăm lớn hoặc nhỏ tự nó không chứng minh thiếu làm chủ hay vi phạm chính sách.

Đề xuất: Ghi rõ snapshot “đã sử dụng đến ngày…” và tách kế hoạch tương lai. Với mỗi phần trăm, nêu đo theo task, effort tự ước lượng hay cách khác; phạm vi, thời điểm, người xác nhận và một ví dụ tính. Nếu chưa có cơ sở tính, ghi chưa đo/ước tính sơ bộ thay vì tạo độ chính xác giả. Liên kết log ngắn theo task: công cụ, ngày, nội dung hỗ trợ, phần được giữ/sửa/bỏ, người review và commit hoặc tài liệu minh chứng khi đã tồn tại.

Tên sản phẩm/platform và model nên tách riêng theo thông tin thực sự quan sát được; không tự suy ra model từ tên giao diện. Cam kết sở hữu code nên giữ và gắn với walkthrough/tests ở đúng giai đoạn, không cần đòi kết quả cuối kỳ ngay lúc này. Đồng bộ biểu mẫu disclosure riêng nếu biểu mẫu đó vẫn được dùng để nộp.

Điều kiện đóng: Mỗi nhóm tỷ lệ có cách hiểu duy nhất; task thực tế và dự kiến phân biệt được; có nơi lưu log và người chịu trách nhiệm. Chính sách học phần cần đối chiếu với bản chính thức của nhóm, không suy diễn thêm giới hạn phần trăm từ review này.

F07P1Kế hoạch chưa đặt rõ mốc kiểm tra usability trên bản tích hợp và khóa B3

Vị trí: P2 tr.6–7, Table 5; tr.12 NFR06; tr.18 Table 24. Đối chiếu R1-F03/F10 và góp ý kế hoạch cũ.

Nhận xét: Study 12 người và tiêu chí 8/12 tìm được bằng chứng trong hai phút đã cụ thể. Timeline đặt user validation ở Sprint 1 cùng UI prototype; Copilot, citation viewer, Gate/Verifier và B3 xuất hiện ở Sprint 5. Chưa nói study nào dùng prototype để tìm vấn đề, study nào xác nhận NFR06 trên bản tích hợp. Sprint 4 đóng băng fusion/thresholds, nhưng Gate/Verifier đến Sprint 5 mới hoàn thiện; chưa có mốc khóa toàn bộ cấu hình B3 và evaluator trước Sprint 6.

Tác động: Bằng chứng từ prototype có thể bị dùng nhầm làm nghiệm thu usability sản phẩm cuối. Các rule mới ở Sprint 5 có thể chưa được calibration đầy đủ trước khi chạy final. Đây là thiếu mốc và dependency trong kế hoạch, không chứng minh nhóm sẽ làm sai quy trình.

Đề xuất: Tách validation nhu cầu/prototype ở Sprint 1 với kiểm tra NFR06 trên bản tích hợp ở cuối Sprint 5 hoặc đầu Sprint 6. Chỉ định phiên bản app, người điều phối, thời lượng dự kiến và đầu ra. Giữ 40 câu calibration cho cả rule Gate/Verifier mới; thêm mốc khóa code/config/evaluator/routing sau calibration B3 và trước lần mở tập final. Ước lượng các việc này trong ngân sách 900 person-hours hiện có.

Kế hoạch 12 người là nghiên cứu usability nhỏ có chủ đích; cách giới hạn suy rộng đã viết tốt. Nếu muốn kết luận “tiết kiệm thời gian nghiên cứu”, cần thiết kế so với thao tác thủ công tương ứng hoặc chỉ giữ đó là mục tiêu, vì tiêu chí tìm được citation hiện tại chưa trực tiếp đo mức tiết kiệm so với quy trình cũ.

F08P2Lịch 12 tuần và một số tham chiếu trang chưa khớp bản xuất PDF

Vị trí: P2 tr.2, tr.3–4, tr.18 và tr.21–22. Đối chiếu bảng lỗi nhất quán của R1.

Nhận xét: Sprint 6 đã sửa đúng thành 23/11–06/12/2026. Nhưng Sprint 1 ghi 10/09–27/09, kéo dài 18 ngày lịch trong khi toàn kế hoạch gọi là sáu sprint hai tuần; 10/09–06/12 là 88 ngày nếu tính cả hai đầu, không đúng 84 ngày của 12 tuần. Mục lục và List of Figures ghi mục 12.2/Figure 2 ở tr.19, thực tế ở tr.20. Figure 3 ở tr.21 nhưng caption bị đẩy riêng sang tr.22.

Tác động: Gây nhầm khi tính capacity và khi hội đồng tra sơ đồ. Đây là lỗi lịch/biên tập, không phải lý do bác bỏ hướng đề tài.

Đề xuất: Nếu đúng với lịch thực tế, tách 10–13/09 thành kickoff và đặt Sprint 1 từ 14–27/09; khi đó sáu sprint hai tuần kết thúc 06/12. Nếu nhóm thực sự chọn 10 workdays phân bố trong 18 ngày đầu, giữ lịch nhưng giải thích khoảng ngày và sửa tuyên bố thời lượng cho nhất quán. Cập nhật toàn bộ fields mục lục/danh mục sau dàn trang, giữ caption cùng hình và kiểm tra lại PDF xuất cuối.

4. Đối chiếu tài liệu

Trạng thái từng feedback cũ

“Đã sửa ở mức proposal” chỉ đóng lỗi của hồ sơ thiết kế. “Một phần” nghĩa là nội dung đã bổ sung nhưng còn việc cụ thể hoặc cần một điều kiện hoàn thành. “Chưa đóng” là yêu cầu trọng tâm cũ vẫn chưa được giải quyết. Mã R1-Fxx là mã cũ; Fxx không có tiền tố trong báo cáo này là phát hiện của lần review mới.

Feedback cũ

Trạng thái

Bằng chứng trong P2 và việc còn lại

R1-F01 — Cam kết zero hallucination/0% sai

Đã sửa ở mức proposal

Tr.10 loại bỏ bảo đảm tuyệt đối; tr.14 chuyển sang metric và residual error. Không tiếp tục yêu cầu sửa lỗi này như thể còn nguyên

R1-F02 — Prediction thiếu thiết kế

Đã sửa ở mức proposal

Tr.1–2, 5, 10, 25 chốt Research Copilot, prediction ngoài MVP; không còn buộc nhóm xây mô hình dự đoán

R1-F03 — Chỉ có tên metric, chưa có thí nghiệm

Một phần, tiến bộ lớn

Tr.9, 12–14 có RQ, B0–B3, 120 câu, 40/80 split, audit và CI. Cần xử lý F01–F03/F07 mới

R1-F04 — Scope dữ liệu không lượng hóa

Một phần

Tr.5 có 10 mã, hai ngành, ba năm/bốn quý; tr.15 thừa nhận nguồn còn pending. Cần gate nguồn và coverage theo F05

R1-F05 — Thiếu quyết định kiến trúc

Một phần, tiến bộ lớn

Tr.16, 19–23 có stack, bốn hình, Structured Retrieval và ADR. Sửa luồng PASS ở F04; chốt contract/fusion/model cụ thể theo đầu ra Sprint 1

R1-F06 — Ngưỡng fallback và thứ tự xử lý mâu thuẫn

Đã sửa ở mức nguyên tắc

Tr.11–12, 21–23 dùng relevance cao tốt hơn, hai lớp kiểm tra và mandatory-branch failure. Lỗi mới của Figure 3 được theo dõi riêng ở F04

R1-F07 — Citation chỉ gắn metadata

Một phần, đã có thiết kế claim-level

Tr.7–8, 11, 22 yêu cầu claim, hash, trang/bảng và provenance. F03 cần làm rõ phép chấm claim–citation và completeness; bước triển khai cần trace mẫu

R1-F08 — Tính mới vượt bằng chứng

Đã sửa ở mức proposal

Tr.7–8 khảo sát năm sản phẩm Việt Nam, phân biệt tính năng công bố với thông tin chưa công bố; thừa nhận chatbot không tự tạo novelty

R1-F09 — Reference GraphRAG không khớp

Đã sửa phần reference học thuật chính

Tr.25 dùng đúng bài Edge và cộng sự, có hyperlink và phạm vi sử dụng. Văn bản kế toán cụ thể vẫn là việc Source Register ở F05

R1-F10 — NFR, bảo mật, dữ liệu khó nghiệm thu

Một phần, tiến bộ lớn

Tr.12, 16, 23–25 có tải/latency, retention 30 ngày, quyền đọc, injection, token budget. Cần hoàn thiện metric/load manifest, nguồn và mốc usability theo F03/F05/F07

R1-F11 — Chưa tách AI đã dùng và dự kiến

Một phần

Tr.17 đã dùng nhãn intended/estimated nhưng chưa tách từng task và snapshot thực tế. Xem F06

R1-F12 — Tỷ lệ AI không có cách tính

Chưa đóng

Tr.17 đổi thành 60/70/30/50% nhưng vẫn không có phương pháp và mẫu số. Xem F06

R1-F13 — Bằng chứng làm chủ phần lõi

Đã bổ sung kế hoạch phù hợp giai đoạn

Tr.5, 18, 24 nêu ownership, review, tests, walkthrough và experiment logs. Bằng chứng thực hiện cần được tạo trong sprint; chưa đánh giá năng lực từ lời cam kết

R1-F14 — Vai trò, disclosure, xác nhận

Một phần; chưa đủ đầu vào để kiểm tra toàn bộ

Tr.2/5 đã có vai trò, tr.17–18 có disclosure trong proposal. Hai form cập nhật không có trong lần này; không xác nhận thay trạng thái chữ ký hay đồng bộ liên tài liệu

Các lỗi nhất quán cũ đã được xử lý và phần chưa xác nhận

Mục

Kết quả lần này

Mã học phần

P2 dùng CMU-SE 450 nhất quán tại bìa/thông tin dự án; chưa xác nhận với form riêng hoặc lịch chính thức

Python

P2 dùng Python 3.13 nhất quán tr.15–16; đây chưa phải bằng chứng toàn bộ dependency đã chạy thành công

Ngày Sprint 6

Đã sửa 23/11/2026; vấn đề thời lượng Sprint 1 còn ở F08

Placeholder tên LLM và “bge-m3và”

Không còn chỗ trống như bản cũ; đã ghi Gemini và BAAI/bge-m3. Exact model/config là đầu ra cần khóa trước benchmark

Docker service list

Tr.12 NFR08 liệt kê React, FastAPI, PostgreSQL/pgvector và Neo4j; lỗi PostgreSQL lặp đã được xử lý

Hình kiến trúc và workflow

Đã có bốn hình thực sự, không tiếp tục nhận xét hồ sơ chỉ có mô tả chữ; Figure 3 cần sửa F04

Trang dư cuối tài liệu

Tr.26 có nội dung References; không còn trang cuối chỉ có số trang như phản ánh cũ

Rubric 14–16 tuần, ký tự thừa, chữ ký của form cũ

Không thể xác nhận đã sửa vì các biểu mẫu đó không có trong đầu vào hiện tại

“Approved by” trên bìa

Tr.1 vẫn có tên mentor và ô xác nhận; ô trống không chứng minh vi phạm hay đã được phê duyệt. Nên ghi rõ trạng thái hồ sơ khi nộp

Kiểm tra nguồn của phần đã sửa

Reference GraphRAG đã chuyển sang đúng bài của Darren Edge và cộng sự, bản đầu năm 2024. Bài này mô tả graph và community summaries cho query-focused summarization. FinMind dùng traversal tối đa hai hop; có thể dùng bài làm động cơ nghiên cứu, nhưng không nên coi đó là cùng một triển khai hay bằng chứng sẵn có rằng cấu hình FinMind sẽ tăng chất lượng. Bài GraphRAG gốc.

Các trang nhà cung cấp hỗ trợ việc xác nhận sự tồn tại và mô tả chức năng công bố của DNSE Ensa, FireAnt Copilot, VPBankS StockGuru, Finhay HayBuddy và MASA AI. Cách viết “chưa được công bố trong nguồn khảo sát” của P2 phù hợp hơn khẳng định “đối thủ không có”. Không suy ra năng lực nội bộ hay độ chính xác thực tế từ trang giới thiệu.

Với HayBuddy, nguồn có mô tả quy trình truy xuất và tổng hợp ở mức khái quát; vì vậy “chưa công bố internal grounding method” nên được hiểu hẹp là chưa đủ chi tiết để tái tạo/đánh giá cơ chế grounding, không phải không có mô tả quy trình nào.

5. Đề xuất cải thiện

Sửa ít nhưng đóng được các điểm chính

Giữ nguyên hướng đề tài và các phần đã làm tốt. Có thể hoàn thiện vòng này bằng một phụ lục evaluation ngắn, một Figure 3 sửa lại, một bảng disclosure có phương pháp, và timeline/source gate được cập nhật.

Câu hỏi

So sánh/đầu ra đề xuất

Giới hạn kết luận

Graph có ích không?

B1↔B2 trên cùng câu, cố định các thành phần ngoài gói graph/fusion

Kết luận về gói graph/fusion đã thử; không tự gán mọi thay đổi của B3 cho graph

Hai lớp kiểm tra có ích không?

B3 tắt Gate/Verifier ↔ B3 đầy đủ; giữ routing Structured Retrieval như nhau

Có thể đánh giá tác dụng chung của hai lớp; muốn tách từng lớp cần thí nghiệm riêng, không bắt buộc trong MVP

Structured Retrieval xử lý số liệu ra sao?

B0↔B1 trên numerical subset; báo thêm B3 để thấy đầu ra sản phẩm

Nêu rõ B0 là deterministic control, không có cùng quá trình sinh văn bản như B1

Sản phẩm đủ điều kiện dùng trong demo không?

B3 so với các hard gates đã chốt, gồm coverage, citation, refusal và vận hành

Không phụ thuộc bắt buộc vào việc graph thắng baseline

Một mẫu wording cho acceptance

Đoạn sau là đề xuất biên tập, nhóm cần chốt ngưỡng thật trước khi dùng:

MVP acceptance is determined by the predefined product quality, safety and operational gates. H1 and the comparative part of H4 are research hypotheses; neutral or negative results do not by themselves fail the MVP. Routing is selected on calibration data and frozen before final evaluation. Any configuration changed after inspecting final results is reported as exploratory and requires independent confirmation before receiving a new final-performance claim.

Không tự sửa số 0.90, 0.95 hoặc tải 10 người dùng khi chưa có lý do. Cần làm rõ ý nghĩa, mẫu số, subset và điều kiện đo trước; sau calibration, nếu cần đổi target thì ghi phiên bản và lý do trước final.

Đầu ra thiết kế hợp lý cho Sprint 1

Các mục dưới đây hoàn thiện R1-F05, không phải yêu cầu triển khai toàn bộ hệ thống ngay trong proposal.

Một ví dụ xuyên suốt: câu hỏi so sánh hai kỳ → fact IDs, kỳ/đơn vị/scope → phép tính → evidence package → claim/citation → kết quả verifier. Hình logic tr.22 hiện mô tả Retrieval Evidence qua chunk; cần giải thích cách truy vết evidence từ structured fact và graph relation cũng như phép tính từ nhiều đầu vào.

Một ADR fusion đủ cụ thể: công thức score/rank, cách chuẩn hóa mỗi nhánh, trọng số hoặc cơ chế hợp nhất, reranker, top-k/context cap, conflict policy và cách calibration. Chỉ đưa score về \[0,1\] chưa tự làm chúng có cùng ý nghĩa hay thành xác suất đúng.

Một run manifest mẫu cho Gemini model ID, embedding revision, generation parameters, evaluator, phần cứng, corpus, budget, timeout/retry và tải đo. Trong load test, phân biệt số người dùng mô phỏng với số request thực sự đang đồng thời; ghi thời lượng, warm-up, request mix, cache và số mẫu.

Source Register có owner và reviewer cụ thể; bổ sung secondary reviewer cho các module lõi như nguyên tắc ở tr.5 đã yêu cầu.

Giữ ranh giới nghiên cứu hợp lý

120 câu là bộ đánh giá khởi điểm nhỏ nhưng có thể dùng được cho capstone nếu quy trình minh bạch. Không cần mở rộng đề tài sang prediction, khảo sát đại diện toàn thị trường hoặc chứng minh ưu thế trước mọi sản phẩm thương mại. Đóng góp phù hợp là một pipeline có thể tái chạy và giải thích được: cấu hình nào giúp nhóm câu nào, sai ở đâu, đổi lại bao nhiêu độ trễ/chi phí.

6. Câu hỏi phản biện

Câu hỏi dựa trên bản sửa

Bằng chứng nhóm nên chuẩn bị

B3 tốt hơn B2 vì graph, vì Structured Retrieval hay vì verifier?

Bảng cấu hình theo từng công tắc và cặp so sánh cho RQ1/RQ3/RQ4

Nếu graph không tăng 5 điểm phần trăm nhưng B3 đạt các ngưỡng an toàn thì đề tài có đạt không?

Bảng tách hard gate và hypothesis; chính sách giữ/tắt graph chốt trước final

Citation trỏ đúng file nhưng claim lấy nhầm kỳ có được tính đúng không?

Ví dụ chấm âm và metric contract ở cấp claim–citation

Với số câu relationship/refusal thực sự nằm trong final, một câu sai đổi bao nhiêu điểm?

Ma trận số lượng 40/80, số đếm lỗi/tổng và khoảng bất định

Workflow đi đâu khi Answer Verification trả PASS?

Figure 3 đã sửa và bốn ca success/repair/fallback có output status

Có evidence từ SQL nhưng không có chunk thì trace được đến tài liệu và phép tính thế nào?

Evidence schema và một trace số liệu mẫu từ nguồn đến claim

Nếu chưa có nguồn OHLCV được chấp nhận cuối Sprint 1 thì scope nào thay đổi?

Source Register, coverage matrix, fallback có nguồn và quyết định Must/Should

60% backend và 70% UI đang đo cái gì?

Cách tính, thời điểm khai báo, log theo task và ví dụ phần sinh viên sửa/bác bỏ

Study 12 người đánh giá prototype hay release nào?

Protocol, app version, lịch chạy và tiêu chí NFR06 tương ứng

Một tài liệu chứa chỉ dẫn độc hại làm hệ thống thực hiện hành vi gì?

Case có hành vi mong đợi, trace quyền công cụ và kết quả kiểm tra; không chỉ điểm Noise Sensitivity

7. Kế hoạch hành động

Các owner sau là phân công đề xuất dựa trên vai trò trong P2, không phải xác nhận nhóm đã nhận việc. Có thể thay đổi theo thực tế; mỗi việc cần một người quyết định và một người kiểm tra.

Thời điểm

Việc

Owner đề xuất

Điều kiện hoàn thành

Trước khi chốt bản sửa

F01: ma trận cấu hình và ánh xạ RQ

Nhân + Huyền, Hưng duyệt scope

Mỗi kết luận có đúng đối chứng; không gán tác dụng B3 riêng cho graph

Trước khi chốt bản sửa

F02–F03: gate, hypothesis và metric contract

Huyền + Nhân, Quân kiểm tra số liệu

Chốt mẫu số, split, audit, citation support, partial/refusal và routing/final policy

Trước khi chốt bản sửa

F04: sửa Figure 3

Hưng + Nhân

Có đường PASS, retry tối đa một lần và fallback rõ

Trước khi chốt bản sửa

F06: disclosure có phương pháp

Cả nhóm, Hưng tổng hợp

Đã dùng/dự kiến phân biệt được; các tỷ lệ có nghĩa và có log tham chiếu

Trước khi chốt bản sửa

F07–F08: lịch và mốc validation/freeze

Huyền + Vũ

Có mốc usability trên bản tích hợp, freeze B3 và lịch nhất quán; cập nhật mục lục

Kết thúc Sprint 1

F05: nguồn và coverage có điều kiện chấp nhận

Quân, Hưng rà nguồn

URL trực tiếp, bao phủ mã/kỳ, mẫu ingest, owner/reviewer và scope fallback

Sprint 1–3

Hoàn thiện ADR, evidence contract và baseline

Nhân + Quân + Hưng

Trace mẫu đi được qua SQL/graph/vector đến claim; config có phiên bản

Cuối Sprint 5, trước final

Calibration B3 và usability theo kế hoạch

Huyền + Vũ, cả nhóm hỗ trợ

Gate/Verifier được calibration; cấu hình runtime/evaluator được khóa; rõ build dùng cho NFR06

Sprint 6

Chạy đánh giá cuối và báo cáo đúng giới hạn

Huyền + Nhân

Giữ tập final, lưu raw outputs, số đếm, CI và quyết định không dựa vào chỉnh test sau kết quả

Đồng bộ các thay đổi đã chốt sang Registration Form và AI Usage Disclosure riêng nếu chúng vẫn thuộc bộ hồ sơ nộp.

Thêm một bảng response-to-feedback ngắn vào hồ sơ nộp lại: feedback ID, phần sửa, trang, trạng thái và bằng chứng còn hẹn ở sprint nào.

Xác nhận trạng thái phê duyệt/ô chữ ký với đúng người và đúng thời điểm; không tự điền thay người ký.

Nhận xét mentor gửi nhóm: Bản 2.0 đã tiếp thu phần lớn định hướng góp ý và chuyển đề tài về phạm vi có thể bảo vệ. Vòng tiếp theo nên tập trung làm cho phép đo và quyết định đạt/chưa đạt trở nên rõ ràng, sửa luồng thành công trong sơ đồ và làm disclosure kiểm chứng được. Giữ những phần đã sửa tốt; không cần tăng số công nghệ hoặc tính năng để chứng minh độ khó.

8. Nguồn tham khảo

Nguồn chính là proposal v2.0 và review baseline. Các nguồn ngoài dưới đây được kiểm tra ngày 18/09/2026, dùng đúng phạm vi ghi kèm; không sao chép các tuyên bố tiếp thị thành kết quả đánh giá của FinMind.

Edge và cộng sự — From Local to Global: xác minh reference học thuật đã sửa và phân biệt phương pháp trong bài với cấu hình FinMind.

Google Gemini — Structured Outputs: phân biệt ràng buộc schema với kiểm tra giá trị/ngữ nghĩa, dùng ở F04.

Ragas — Faithfulness: phạm vi đo hỗ trợ từ retrieved context, dùng ở F03.

Ragas — Noise Sensitivity: đầu vào và phạm vi metric, dùng ở F03.

DNSE — Kênh tư vấn đầu tư/Ensa: đối chiếu mô tả chức năng công bố trong khảo sát.

FireAnt — FireAnt Copilot: đối chiếu mô tả chức năng công bố trong khảo sát.

VPBankS — StockGuru: đối chiếu hướng dẫn hỏi đáp và chế độ tương tác.

Finhay — HayBuddy: đối chiếu chức năng và mô tả quy trình ở mức khái quát.

Mirae Asset — MASA AI: đối chiếu thông báo chính thức và nguồn dữ liệu trung tâm phân tích; nội dung xác nhận qua bản được công cụ tìm kiếm lập chỉ mục khi việc mở chi tiết không ổn định.

Nguồn: REVIEW\_FinMind\_v2.md · Định dạng document-review/v1 · Kết luận là nhận xét của reviewer.

## 2026-09-29 17:27 - DOI TEN / DI CHUYEN

- **Người đăng:** nguyenquocanh41@gmail.com
- **Tên / vị trí:** `00_Management/Mentor_Reviews/20260918/REVIEW_FinMind_v2_20260918.html`
- **Vị trí cũ:** `00_Management/Mentor_Reviews/REVIEW_FinMind_v2_20260918.html`
- **Ngày và giờ:** 2026-09-29 17:27

## 2026-09-25 17:22 - TAO MOI

- **Người đăng:** nguyenquocanh41@gmail.com
- **Tên / vị trí:** `00_Management/Mentor_Reviews/REVIEW_FinMind_v2_20260918.html`
- **Ngày và giờ:** 2026-09-25 17:22


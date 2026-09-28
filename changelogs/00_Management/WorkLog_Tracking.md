# Lịch sử thay đổi: Bảng tính không có tiêu đề

## 2026-09-28 15:52 - SUA NOI DUNG

- **Người đăng:** khong ro
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 15:52

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	1	FinMind MVP	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	SRS/PoC, dữ liệu, truy vấn, ứng dụng, đánh giá và bàn giao.		1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đã hoàn thành	146	132	Giữ giờ gốc; kiểm tra P47 ở Sprint 1 để tránh tính trùng.**

🟢 **	S1-T24	Vẽ mô hình node–edge Neo4j	Thiết kế mô hình dữ liệu	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có mô hình node–edge Neo4j kèm provenance.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	4	6	Hồ Phạm Đăng Nhân	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6	7	Hồ Phạm Đăng Nhân	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T34	Nạp node và edge mẫu vào Neo4j	PoC graph và đối chiếu nguồn	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có graph mẫu trong Neo4j.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3	3	Hồ Phạm Đăng Nhân	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S1-T35	Truy vấn Neo4j để kiểm thử	PoC graph và đối chiếu nguồn	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có kết quả truy vấn graph kèm nguồn.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3	1	Hồ Phạm Đăng Nhân	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	132																										**

🟢 **	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.					3	1			2									**

🟢 **	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6	7	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.							3	3	1									**

🟢 **	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.						2												**

🟢 **	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.												2						**

🟢 **	Sprint 1	S1-T34	M06	2	Nạp node và edge mẫu vào Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Có graph mẫu trong Neo4j.	Giữ kế hoạch Sprint 1 đã nhập.									1			2						**

🟢 **	Sprint 1	S1-T35	M06	2	Truy vấn Neo4j để kiểm thử	Hồ Phạm Đăng Nhân	Đã hoàn thành	3	1	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Có kết quả truy vấn graph kèm nguồn.	Giữ kế hoạch Sprint 1 đã nhập.												1						**

🟢 **					Tổng giờ các task			146	132																							**

🟢 **					Giờ thực tế theo ngày (tự tính)				126						12	7	1	1	12	10	12	8	12	0	0	14	9	7	9	12	0	0**

🟢 **	Giờ thực tế đã ghi	132**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M04	1	Thiết kế mô hình dữ liệu	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	24	17	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M05	1	PoC thu thập và tìm kiếm vector	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	7	7	1	Đã hoàn thành	24	23	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M06	1	PoC graph và đối chiếu nguồn	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	15	8	Sprint 1 Backlog**

~~	1	FinMind MVP	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	SRS/PoC, dữ liệu, truy vấn, ứng dụng, đánh giá và bàn giao.		1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đã hoàn thành	146	121	Giữ giờ gốc; kiểm tra P47 ở Sprint 1 để tránh tính trùng.~~

~~	S1-T24	Vẽ mô hình node–edge Neo4j	Thiết kế mô hình dữ liệu	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có mô hình node–edge Neo4j kèm provenance.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	4		Hồ Phạm Đăng Nhân	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6	6	Hồ Phạm Đăng Nhân	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T34	Nạp node và edge mẫu vào Neo4j	PoC graph và đối chiếu nguồn	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có graph mẫu trong Neo4j.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3		Hồ Phạm Đăng Nhân	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T35	Truy vấn Neo4j để kiểm thử	PoC graph và đối chiếu nguồn	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có kết quả truy vấn graph kèm nguồn.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3		Hồ Phạm Đăng Nhân	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	121																										~~

~~	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.					3	1								3				~~

~~	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6	6	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.						2	3	1										~~

~~	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.								2										~~

~~	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.									2									~~

~~	Sprint 1	S1-T34	M06	2	Nạp node và edge mẫu vào Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Có graph mẫu trong Neo4j.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T35	M06	2	Truy vấn Neo4j để kiểm thử	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Có kết quả truy vấn graph kèm nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~					Tổng giờ các task			146	121																							~~

~~					Giờ thực tế theo ngày (tự tính)				122						12	7	1	1	12	10	12	8	10	0	0	9	9	10	9	12	0	0~~

~~	Giờ thực tế đã ghi	122~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M04	1	Thiết kế mô hình dữ liệu	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	24	11	Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M05	1	PoC thu thập và tìm kiếm vector	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	7	7	1	Đã hoàn thành	24	22	Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M06	1	PoC graph và đối chiếu nguồn	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	15	5	Sprint 1 Backlog~~

## 2026-09-28 15:47 - SUA NOI DUNG

- **Người đăng:** khong ro
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 15:47

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	1	FinMind MVP	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	SRS/PoC, dữ liệu, truy vấn, ứng dụng, đánh giá và bàn giao.		1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đã hoàn thành	146	121	Giữ giờ gốc; kiểm tra P47 ở Sprint 1 để tránh tính trùng.**

🟢 **	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6	6	Hồ Phạm Đăng Nhân	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T32	Trích xuất entity cho graph mẫu	PoC graph và đối chiếu nguồn	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có danh sách thực thể graph có ID.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2	2	Hồ Phạm Đăng Nhân	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T33	Trích xuất quan hệ và provenance cho edge	PoC graph và đối chiếu nguồn	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2	2	Hồ Phạm Đăng Nhân	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S1-T40	Vẽ usecase diagram cho từng đặc tả use case	Hoàn thiện SRS và các sơ đồ	Vẽ sơ đồ use case riêng cho từng đặc tả, thể hiện người sử dụng và chức năng liên quan.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Các sơ đồ khớp actor, tên chức năng và mã use case trong SRS.	Đối chiếu ảnh Jira Sprint 1. Chưa xác nhận người phụ trách và ngày bắt đầu; deadline chưa hiển thị trong ảnh.	Trung bình	Đã hoàn thành	M03	FinMind	1	4	6	Hồ Phạm Đăng Nhân	Fri Sep 25 2...**

🟢 **	S1-T41	Vẽ usecase Diagram tổng	Hoàn thiện SRS và các sơ đồ	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Đối chiếu ảnh Jira Sprint 1. Chưa xác nhận người phụ trách và ngày bắt đầu.	Trung bình	Đã hoàn thành	M03	FinMind	1	5	3	Trần Diệu Huyền	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT...**

🟢 **	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	121																										**

🟢 **	Sprint 1	S1-T04	M01	Khởi động	Soạn bộ câu hỏi nghiên cứu và khảo sát	Trần Diệu Huyền	Đã hoàn thành	2	3	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.	3																	**

🟢 **	Sprint 1	S1-T06	M01	1	Kiểm tra lại phạm vi và thống nhất	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.		3			3													**

🟢 **	Sprint 1	S1-T07	M02	1	Lập danh sách nguồn dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.						3												**

🟢 **	Sprint 1	S1-T10	M02	1	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.							3											**

🟢 **	Sprint 1	S1-T11	M02	1	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Trần Diệu Huyền	Đã hoàn thành	4	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.								3										**

🟢 **	Sprint 1	S1-T12	M02	1	Xác định nguồn dự phòng và đánh giá tính khả thi	Trần Diệu Huyền	Đã hoàn thành	3	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.									3									**

🟢 **	Sprint 1	S1-T13	M03	1	Rà soát SRS và danh mục use case	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	Có bảng đối chiếu UC–FR/NFR đã rà.	Giữ kế hoạch Sprint 1 đã nhập.												3	3					**

🟢 **	Sprint 1	S1-T18	M03	1	Rà soát tính nhất quán SRS	Trần Diệu Huyền	Đã hoàn thành	4	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS có đúng hình, số mục và mã tham chiếu.	Giữ kế hoạch Sprint 1 đã nhập.														3				**

🟢 **	Sprint 1	S1-T21	M04	1	Đặc tả chuẩn hóa và định danh dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Giữ kế hoạch Sprint 1 đã nhập.															3			**

🟢 **	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.					3	1								3				**

🟢 **	Sprint 1	S1-T25	M04	2	Đối chiếu ID giữa các mô hình dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có quy tắc ánh xạ ID giữa các mô hình.	Giữ kế hoạch Sprint 1 đã nhập.																3		**

🟢 **	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6	6	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.						2	3	1										**

🟢 **	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.								2										**

🟢 **	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.									2									**

🟢 **	Sprint 1	S1-T40	M03	2	Vẽ usecase diagram cho từng đặc tả use case	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case riêng cho từng đặc tả, thể hiện người sử dụng và chức năng liên quan.	Các sơ đồ khớp actor, tên chức năng và mã use case trong SRS.	File gốc có công thức cộng giờ các task khác trong dòng này. Cần kiểm tra để tránh tính trùng.	6																	**

🟢 **	Sprint 1	S1-T41	M03	2	Vẽ usecase Diagram tổng	Trần Diệu Huyền	Đã hoàn thành	5	3	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Giữ kế hoạch Sprint 1 đã nhập.																3		**

🟢 **					Tổng giờ các task			146	121																							**

🟢 **					Giờ thực tế theo ngày (tự tính)				122						12	7	1	1	12	10	12	8	10	0	0	9	9	10	9	12	0	0**

🟢 **	Giờ thực tế đã ghi	122**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M05	1	PoC thu thập và tìm kiếm vector	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	7	7	1	Đã hoàn thành	24	22	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M06	1	PoC graph và đối chiếu nguồn	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	15	5	Sprint 1 Backlog**

~~	1	FinMind MVP	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	SRS/PoC, dữ liệu, truy vấn, ứng dụng, đánh giá và bàn giao.		1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đã hoàn thành	146	111	Giữ giờ gốc; kiểm tra P47 ở Sprint 1 để tránh tính trùng.~~

~~	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6		Hồ Phạm Đăng Nhân	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T32	Trích xuất entity cho graph mẫu	PoC graph và đối chiếu nguồn	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có danh sách thực thể graph có ID.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2		Hồ Phạm Đăng Nhân	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T33	Trích xuất quan hệ và provenance cho edge	PoC graph và đối chiếu nguồn	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2		Hồ Phạm Đăng Nhân	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T40	Vẽ usecase diagram cho từng đặc tả use case	Hoàn thiện SRS và các sơ đồ	Vẽ sơ đồ use case riêng cho từng đặc tả, thể hiện người sử dụng và chức năng liên quan.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Các sơ đồ khớp actor, tên chức năng và mã use case trong SRS.	Đối chiếu ảnh Jira Sprint 1. Chưa xác nhận người phụ trách và ngày bắt đầu; deadline chưa hiển thị trong ảnh.	Trung bình	Đã hoàn thành	M03	FinMind	1	4	3	Hồ Phạm Đăng Nhân	Fri Sep 25 2...~~

~~	S1-T41	Vẽ usecase Diagram tổng	Hoàn thiện SRS và các sơ đồ	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Đối chiếu ảnh Jira Sprint 1. Chưa xác nhận người phụ trách và ngày bắt đầu.	Trung bình	Đã hoàn thành	M03	FinMind	1	5	6	Trần Diệu Huyền	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT...~~

~~	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	111																										~~

~~	Sprint 1	S1-T04	M01	Khởi động	Soạn bộ câu hỏi nghiên cứu và khảo sát	Trần Diệu Huyền	Đã hoàn thành	2	3	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T06	M01	1	Kiểm tra lại phạm vi và thống nhất	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T07	M02	1	Lập danh sách nguồn dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T10	M02	1	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T11	M02	1	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Trần Diệu Huyền	Đã hoàn thành	4	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T12	M02	1	Xác định nguồn dự phòng và đánh giá tính khả thi	Trần Diệu Huyền	Đã hoàn thành	3	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T13	M03	1	Rà soát SRS và danh mục use case	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	Có bảng đối chiếu UC–FR/NFR đã rà.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T18	M03	1	Rà soát tính nhất quán SRS	Trần Diệu Huyền	Đã hoàn thành	4	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS có đúng hình, số mục và mã tham chiếu.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T21	M04	1	Đặc tả chuẩn hóa và định danh dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T25	M04	2	Đối chiếu ID giữa các mô hình dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có quy tắc ánh xạ ID giữa các mô hình.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6		Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2		Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2		Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T40	M03	2	Vẽ usecase diagram cho từng đặc tả use case	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	3	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case riêng cho từng đặc tả, thể hiện người sử dụng và chức năng liên quan.	Các sơ đồ khớp actor, tên chức năng và mã use case trong SRS.	File gốc có công thức cộng giờ các task khác trong dòng này. Cần kiểm tra để tránh tính trùng.	3																	~~

~~	Sprint 1	S1-T41	M03	2	Vẽ usecase Diagram tổng	Trần Diệu Huyền	Đã hoàn thành	5	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~					Tổng giờ các task			146	111																							~~

~~					Giờ thực tế theo ngày (tự tính)				63						6	4	1	1	6	4	6	2	5	0	0	6	6	4	6	6	0	0~~

~~	Giờ thực tế đã ghi	111~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M05	1	PoC thu thập và tìm kiếm vector	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	7	7	1	Đã hoàn thành	24	16	Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M06	1	PoC graph và đối chiếu nguồn	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	15		Sprint 1 Backlog~~

## 2026-09-28 15:07 - SUA NOI DUNG

- **Người đăng:** khong ro
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 15:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	1	FinMind MVP	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	SRS/PoC, dữ liệu, truy vấn, ứng dụng, đánh giá và bàn giao.		1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đã hoàn thành	146	111	Giữ giờ gốc; kiểm tra P47 ở Sprint 1 để tránh tính trùng.**

🟢 **	S1-T04	Soạn bộ câu hỏi nghiên cứu và khảo sát	Chốt nhu cầu và phạm vi MVP	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Vai trò người dùng, phạm vi và danh sách chức năng được nhóm thống nhất.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M01	FinMind	1	2	3	Trần Diệu Huyền	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Khởi động**

🟢 **	S1-T06	Kiểm tra lại phạm vi và thống nhất	Chốt nhu cầu và phạm vi MVP	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Vai trò người dùng, phạm vi và danh sách chức năng được nhóm thống nhất.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M01	FinMind	1	4	6	Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T07	Lập danh sách nguồn dữ liệu	Chốt nguồn và điều kiện dùng dữ liệu	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	2	3	Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T10	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Chốt nguồn và điều kiện dùng dữ liệu	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	2	3	Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T11	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Chốt nguồn và điều kiện dùng dữ liệu	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	4	3	Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T12	Xác định nguồn dự phòng và đánh giá tính khả thi	Chốt nguồn và điều kiện dùng dữ liệu	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	3	3	Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T13	Rà soát SRS và danh mục use case	Hoàn thiện SRS và các sơ đồ	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Có bảng đối chiếu UC–FR/NFR đã rà.	Worklog Sprint 1, tuần 2	Cao	Đã hoàn thành	M03	FinMind	1	4	6	Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T14	Vẽ context và business function diagram	Hoàn thiện SRS và các sơ đồ	Thể hiện tác nhân, hệ thống ngoài và phân rã chức năng; đối chiếu nội dung với SRS.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Có context và business function diagram khớp SRS.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M03	FinMind	1	5	6	Đinh Huỳnh Vũ	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T18	Rà soát tính nhất quán SRS	Hoàn thiện SRS và các sơ đồ	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	SRS có đúng hình, số mục và mã tham chiếu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M03	FinMind	1	4	3	Trần Diệu Huyền	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T21	Đặc tả chuẩn hóa và định danh dữ liệu	Thiết kế mô hình dữ liệu	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Worklog Sprint 1, tuần 2	Cao	Đã hoàn thành	M04	FinMind	1	3	3	Trần Diệu Huyền	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T25	Đối chiếu ID giữa các mô hình dữ liệu	Thiết kế mô hình dữ liệu	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có quy tắc ánh xạ ID giữa các mô hình.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	3	3	Trần Diệu Huyền	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S1-T41	Vẽ usecase Diagram tổng	Hoàn thiện SRS và các sơ đồ	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Đối chiếu ảnh Jira Sprint 1. Chưa xác nhận người phụ trách và ngày bắt đầu.	Trung bình	Đã hoàn thành	M03	FinMind	1	5	6	Trần Diệu Huyền	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT...**

🟢 **	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	111																										**

🟢 **	Sprint 1	S1-T04	M01	Khởi động	Soạn bộ câu hỏi nghiên cứu và khảo sát	Trần Diệu Huyền	Đã hoàn thành	2	3	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T06	M01	1	Kiểm tra lại phạm vi và thống nhất	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T07	M02	1	Lập danh sách nguồn dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T10	M02	1	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T11	M02	1	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Trần Diệu Huyền	Đã hoàn thành	4	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T12	M02	1	Xác định nguồn dự phòng và đánh giá tính khả thi	Trần Diệu Huyền	Đã hoàn thành	3	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T13	M03	1	Rà soát SRS và danh mục use case	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	Có bảng đối chiếu UC–FR/NFR đã rà.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T14	M03	1	Vẽ context và business function diagram	Đinh Huỳnh Vũ	Đã hoàn thành	5	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thể hiện tác nhân, hệ thống ngoài và phân rã chức năng; đối chiếu nội dung với SRS.	Có context và business function diagram khớp SRS.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T18	M03	1	Rà soát tính nhất quán SRS	Trần Diệu Huyền	Đã hoàn thành	4	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS có đúng hình, số mục và mã tham chiếu.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T21	M04	1	Đặc tả chuẩn hóa và định danh dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T25	M04	2	Đối chiếu ID giữa các mô hình dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có quy tắc ánh xạ ID giữa các mô hình.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T41	M03	2	Vẽ usecase Diagram tổng	Trần Diệu Huyền	Đã hoàn thành	5	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **					Tổng giờ các task			146	111																							**

🟢 **	Giờ thực tế đã ghi	111**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	M01	1	Chốt nhu cầu và phạm vi MVP	Vai trò người dùng, phạm vi và danh sách chức năng được nhóm thống nhất.	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	18	25	Sprint 1 Backlog**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	M02	1	Chốt nguồn và điều kiện dùng dữ liệu	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	17	12	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M03	1	Hoàn thiện SRS và các sơ đồ	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	9	9	1	Đã hoàn thành	48	47	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M04	1	Thiết kế mô hình dữ liệu	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	24	11	Sprint 1 Backlog**

~~	1	FinMind MVP	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	SRS/PoC, dữ liệu, truy vấn, ứng dụng, đánh giá và bàn giao.		1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đã hoàn thành	146	63	Giữ giờ gốc; kiểm tra P47 ở Sprint 1 để tránh tính trùng.~~

~~	S1-T04	Soạn bộ câu hỏi nghiên cứu và khảo sát	Chốt nhu cầu và phạm vi MVP	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Vai trò người dùng, phạm vi và danh sách chức năng được nhóm thống nhất.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M01	FinMind	1	2		Trần Diệu Huyền	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Khởi động~~

~~	S1-T06	Kiểm tra lại phạm vi và thống nhất	Chốt nhu cầu và phạm vi MVP	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Vai trò người dùng, phạm vi và danh sách chức năng được nhóm thống nhất.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M01	FinMind	1	4		Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T07	Lập danh sách nguồn dữ liệu	Chốt nguồn và điều kiện dùng dữ liệu	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	2		Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T10	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Chốt nguồn và điều kiện dùng dữ liệu	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	2		Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T11	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Chốt nguồn và điều kiện dùng dữ liệu	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	4		Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T12	Xác định nguồn dự phòng và đánh giá tính khả thi	Chốt nguồn và điều kiện dùng dữ liệu	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Worklog Sprint 1, tuần 1	Cao	Đã hoàn thành	M02	FinMind	1	3		Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T13	Rà soát SRS và danh mục use case	Hoàn thiện SRS và các sơ đồ	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Có bảng đối chiếu UC–FR/NFR đã rà.	Worklog Sprint 1, tuần 2	Cao	Đã hoàn thành	M03	FinMind	1	4		Trần Diệu Huyền	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T14	Vẽ context và business function diagram	Hoàn thiện SRS và các sơ đồ	Thể hiện tác nhân, hệ thống ngoài và phân rã chức năng; đối chiếu nội dung với SRS.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Có context và business function diagram khớp SRS.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M03	FinMind	1	5		Đinh Huỳnh Vũ	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T18	Rà soát tính nhất quán SRS	Hoàn thiện SRS và các sơ đồ	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	SRS có đúng hình, số mục và mã tham chiếu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M03	FinMind	1	4		Trần Diệu Huyền	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T21	Đặc tả chuẩn hóa và định danh dữ liệu	Thiết kế mô hình dữ liệu	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Worklog Sprint 1, tuần 2	Cao	Đã hoàn thành	M04	FinMind	1	3		Trần Diệu Huyền	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T25	Đối chiếu ID giữa các mô hình dữ liệu	Thiết kế mô hình dữ liệu	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có quy tắc ánh xạ ID giữa các mô hình.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	3		Trần Diệu Huyền	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T41	Vẽ usecase Diagram tổng	Hoàn thiện SRS và các sơ đồ	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Đối chiếu ảnh Jira Sprint 1. Chưa xác nhận người phụ trách và ngày bắt đầu.	Trung bình	Đã hoàn thành	M03	FinMind	1	5		Trần Diệu Huyền	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+...~~

~~	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	63																										~~

~~	Sprint 1	S1-T04	M01	Khởi động	Soạn bộ câu hỏi nghiên cứu và khảo sát	Trần Diệu Huyền	Đã hoàn thành	2		Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T06	M01	1	Kiểm tra lại phạm vi và thống nhất	Trần Diệu Huyền	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T07	M02	1	Lập danh sách nguồn dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T10	M02	1	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T11	M02	1	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Trần Diệu Huyền	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T12	M02	1	Xác định nguồn dự phòng và đánh giá tính khả thi	Trần Diệu Huyền	Đã hoàn thành	3		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T13	M03	1	Rà soát SRS và danh mục use case	Trần Diệu Huyền	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	Có bảng đối chiếu UC–FR/NFR đã rà.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T14	M03	1	Vẽ context và business function diagram	Đinh Huỳnh Vũ	Đã hoàn thành	5		Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thể hiện tác nhân, hệ thống ngoài và phân rã chức năng; đối chiếu nội dung với SRS.	Có context và business function diagram khớp SRS.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T18	M03	1	Rà soát tính nhất quán SRS	Trần Diệu Huyền	Đã hoàn thành	4		Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS có đúng hình, số mục và mã tham chiếu.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T21	M04	1	Đặc tả chuẩn hóa và định danh dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3		Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T25	M04	2	Đối chiếu ID giữa các mô hình dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3		Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có quy tắc ánh xạ ID giữa các mô hình.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T41	M03	2	Vẽ usecase Diagram tổng	Trần Diệu Huyền	Đã hoàn thành	5		Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~					Tổng giờ các task			146	63																							~~

~~	Giờ thực tế đã ghi	63~~

~~Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	M01	1	Chốt nhu cầu và phạm vi MVP	Vai trò người dùng, phạm vi và danh sách chức năng được nhóm thống nhất.	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	18	16	Sprint 1 Backlog~~

~~Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	M02	1	Chốt nguồn và điều kiện dùng dữ liệu	Có danh sách nguồn chính thức, nguồn dự phòng và quy tắc sử dụng.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	17		Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M03	1	Hoàn thiện SRS và các sơ đồ	SRS khớp use case, FR/NFR và đủ context, business function, activity, sequence, state.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	9	9	1	Đã hoàn thành	48	26	Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M04	1	Thiết kế mô hình dữ liệu	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	24	5	Sprint 1 Backlog~~

## 2026-09-28 14:47 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 14:47

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 14:37 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 14:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 14:02 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 14:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S2-WBS04	Xác định phần dữ liệu nào được chấp nhận làm evidence chính	Xác nhận nguồn báo cáo của 10 công ty	Đối chiếu 3 năm tài chính và 4 quý gần nhất tại ngày chốt. Tách kỳ thiếu; không coi là dữ liệu đã có.	5 công ty có URL kiểm tra được hoặc ghi rõ kỳ chưa tìm thấy.**

🟢 **	Sprint 2	S2-WBS04	S2-G01	1	Xác định phần dữ liệu nào được chấp nhận làm evidence chính	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu 3 năm tài chính và 4 quý gần nhất tại ngày chốt. Tách kỳ thiếu; không coi là dữ liệu đã có.	Danh mục công ty, kỳ, URL và trạng thái nguồn được nhóm duyệt.	Danh sách 10 công ty và phạm vi kỳ báo cáo trong SRS.														**

~~	S2-WBS04	Chốt phạm vi dữ liệu được phép nạp	Xác nhận nguồn báo cáo của 10 công ty	Đối chiếu 3 năm tài chính và 4 quý gần nhất tại ngày chốt. Tách kỳ thiếu; không coi là dữ liệu đã có.	5 công ty có URL kiểm tra được hoặc ghi rõ kỳ chưa tìm thấy.~~

~~	Sprint 2	S2-WBS04	S2-G01	1	Chốt phạm vi dữ liệu được phép nạp	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu 3 năm tài chính và 4 quý gần nhất tại ngày chốt. Tách kỳ thiếu; không coi là dữ liệu đã có.	Danh mục công ty, kỳ, URL và trạng thái nguồn được nhóm duyệt.	Danh sách 10 công ty và phạm vi kỳ báo cáo trong SRS.														~~

## 2026-09-28 13:57 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 13:52 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:52

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 13:47 - SUA NOI DUNG

- **Người đăng:** khong ro
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:47

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 13:42 - SUA NOI DUNG

- **Người đăng:** khong ro
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:42

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 13:32 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:32

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 13:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S1-T24	Vẽ mô hình node–edge Neo4j	Thiết kế mô hình dữ liệu	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có mô hình node–edge Neo4j kèm provenance.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	4		Hồ Phạm Đăng Nhân	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6		Hồ Phạm Đăng Nhân	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T32	Trích xuất entity cho graph mẫu	PoC graph và đối chiếu nguồn	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có danh sách thực thể graph có ID.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2		Hồ Phạm Đăng Nhân	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T33	Trích xuất quan hệ và provenance cho edge	PoC graph và đối chiếu nguồn	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2		Hồ Phạm Đăng Nhân	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S1-T34	Nạp node và edge mẫu vào Neo4j	PoC graph và đối chiếu nguồn	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có graph mẫu trong Neo4j.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3		Hồ Phạm Đăng Nhân	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S1-T35	Truy vấn Neo4j để kiểm thử	PoC graph và đối chiếu nguồn	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có kết quả truy vấn graph kèm nguồn.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3		Hồ Phạm Đăng Nhân	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6		Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2		Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2		Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T34	M06	2	Nạp node và edge mẫu vào Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Có graph mẫu trong Neo4j.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T35	M06	2	Truy vấn Neo4j để kiểm thử	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Có kết quả truy vấn graph kèm nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M04	1	Thiết kế mô hình dữ liệu	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	24	5	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M05	1	PoC thu thập và tìm kiếm vector	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	7	7	1	Đã hoàn thành	24	16	Sprint 1 Backlog**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M06	1	PoC graph và đối chiếu nguồn	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	15		Sprint 1 Backlog**

~~	S1-T24	Vẽ mô hình node–edge Neo4j	Thiết kế mô hình dữ liệu	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có mô hình node–edge Neo4j kèm provenance.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	4		Hồ Phạm Đăng Nhân	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6		Hồ Phạm Đăng Nhân	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S1-T32	Trích xuất entity cho graph mẫu	PoC graph và đối chiếu nguồn	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có danh sách thực thể graph có ID.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2		Hồ Phạm Đăng Nhân	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T33	Trích xuất quan hệ và provenance cho edge	PoC graph và đối chiếu nguồn	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	2		Hồ Phạm Đăng Nhân	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T34	Nạp node và edge mẫu vào Neo4j	PoC graph và đối chiếu nguồn	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có graph mẫu trong Neo4j.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3		Hồ Phạm Đăng Nhân	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T35	Truy vấn Neo4j để kiểm thử	PoC graph và đối chiếu nguồn	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Có kết quả truy vấn graph kèm nguồn.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M06	FinMind	1	3		Hồ Phạm Đăng Nhân	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6		Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T32	M06	2	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2		Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2		Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T34	M06	2	Nạp node và edge mẫu vào Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Có graph mẫu trong Neo4j.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T35	M06	2	Truy vấn Neo4j để kiểm thử	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Có kết quả truy vấn graph kèm nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M04	1	Thiết kế mô hình dữ liệu	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	24	5	Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M05	1	PoC thu thập và tìm kiếm vector	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	7	7	1	Đã hoàn thành	24	16	Sprint 1 Backlog~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	M06	1	PoC graph và đối chiếu nguồn	Neo4j có node/edge kèm provenance; truy vấn graph/SQL mẫu và báo cáo PoC.	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	6	6	1	Đã hoàn thành	15		Sprint 1 Backlog~~

## 2026-09-28 13:22 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:22

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S1-T24	Vẽ mô hình node–edge Neo4j	Thiết kế mô hình dữ liệu	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có mô hình node–edge Neo4j kèm provenance.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	4		Hồ Phạm Đăng Nhân	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6		Hồ Phạm Đăng Nhân	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.																		**

🟢 **	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6		Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.																		**

~~	S1-T24	Vẽ mô hình node–edge Neo4j	Thiết kế mô hình dữ liệu	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có pipeline, ERD PostgreSQL, lược đồ pgvector, node–edge Neo4j và ánh xạ ID.	Có mô hình node–edge Neo4j kèm provenance.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M04	FinMind	1	4		Hồ Phạm Đăng Nhân	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S1-T29	Tạo thử truy vấn quan hệ bằng Neo4j	PoC thu thập và tìm kiếm vector	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Tài liệu mẫu có hash/nguồn; chunk, embedding và truy vấn pgvector thử được.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Worklog Sprint 1, tuần 2	Trung bình	Đã hoàn thành	M05	FinMind	1	6		Hồ Phạm Đăng Nhân	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	Sprint 1	S1-T24	M04	2	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T29	M05	2	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6		Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

## 2026-09-28 13:17 - SUA NOI DUNG

- **Người đăng:** khong ro
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 13:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 12:07 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-09-28 12:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-09-28 11:57 - TAO MOI

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/Bảng tính không có tiêu đề`
- **Ngày và giờ:** 2026-09-28 11:57


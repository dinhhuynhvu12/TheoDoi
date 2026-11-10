## 2026-10-21 21:24 - TAO MOI

## 2026-11-10 13:22 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 13:22

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS04.2	Đặt ngưỡng tin cậy và quy tắc chọn nhánh	Thư viện vector và Hybrid Router	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3		Huyền 	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15...**

🟢 **	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3		Huyền	Mon Nov 09 2026 07:00:00 GMT+0700 (Ind...**

🟢 **	S5-WBS05.3	Kiểm thử graph thật, graph rỗng và lỗi kết nối	Web Chat tích hợp Neo4j	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2	Cao	Chưa bắt đầu	S5-G03	FinMind	5	2		Huyền	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS07.1	Chốt điều kiện fallback và JSON phân loại	Fallback phân loại bằng AI	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2	Cao	Chưa bắt đầu	S5-G05	FinMind	5	2		Huyền	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS07.3	Kiểm thử fallback và trường hợp cả hai bước thất bại	Fallback phân loại bằng AI	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2	Cao	Chưa bắt đầu	S5-G05	FinMind	5	2		Huyền	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 5	S5-WBS04.2	S5-G02	1	Đặt ngưỡng tin cậy và quy tắc chọn nhánh	Huyền 	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1															**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router	Huyền	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2															**

🟢 **	Sprint 5	S5-WBS05.3	S5-G03	1	Kiểm thử graph thật, graph rỗng và lỗi kết nối	Huyền	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2															**

🟢 **	Sprint 5	S5-WBS07.1	S5-G05	1	Chốt điều kiện fallback và JSON phân loại	Huyền	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2															**

🟢 **	Sprint 5	S5-WBS07.3	S5-G05	1	Kiểm thử fallback và trường hợp cả hai bước thất bại	Huyền	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2															**

~~	S5-WBS04.2	Đặt ngưỡng tin cậy và quy tắc chọn nhánh	Thư viện vector và Hybrid Router	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 ...~~

~~	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochin...~~

~~	S5-WBS05.3	Kiểm thử graph thật, graph rỗng và lỗi kết nối	Web Chat tích hợp Neo4j	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2	Cao	Chưa bắt đầu	S5-G03	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS07.1	Chốt điều kiện fallback và JSON phân loại	Fallback phân loại bằng AI	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2	Cao	Chưa bắt đầu	S5-G05	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS07.3	Kiểm thử fallback và trường hợp cả hai bước thất bại	Fallback phân loại bằng AI	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2	Cao	Chưa bắt đầu	S5-G05	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS04.2	S5-G02	1	Đặt ngưỡng tin cậy và quy tắc chọn nhánh		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1															~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2															~~

~~	Sprint 5	S5-WBS05.3	S5-G03	1	Kiểm thử graph thật, graph rỗng và lỗi kết nối		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2															~~

~~	Sprint 5	S5-WBS07.1	S5-G05	1	Chốt điều kiện fallback và JSON phân loại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2															~~

~~	Sprint 5	S5-WBS07.3	S5-G05	1	Kiểm thử fallback và trường hợp cả hai bước thất bại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2															~~

## 2026-11-10 13:17 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 13:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-10 10:57 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 10:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	Sprint 5 gồm 40 task. Tuần 1 sửa lỗi và nối truy xuất (60h). Tuần 2 tối ưu Chat, nhận định xu hướng, Admin và theo dõi (60h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																												**

~~	Sprint 5 gồm 40 task. Tuần 1 sửa lỗi và nối truy xuất (58h). Tuần 2 tối ưu Chat, nhận định xu hướng, Admin và theo dõi (58h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																												~~

## 2026-11-10 10:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 10:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS02.2	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	5		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochin...**

🟢 **	S5-WBS06.2	Kiểm tra refresh thất bại và chống gửi trùng	Refresh token cho Chat	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	3		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **								5	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	120	0	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	Số task	40	Giờ dự kiến	120	Tổng giờ thực tế đã ghi																								**

🟢 **	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Nguyễn Minh Quân	Chưa bắt đầu	5		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1															**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2															**

🟢 **	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng	Nguyễn Minh Quân	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1															**

🟢 **					Tổng giờ theo task			120	0																				**

🟢 **					Chênh kế hoạch task − kế hoạch ngày: -30 h. 																								**

🟢 **Phạm vi (task)	40	Done hiện tại	0	Giờ dự kiến	120	Done thiếu ngày	0					**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	66	2	0.030303030303030304	258	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G01	5	Tái hiện lỗi và sửa truy xuất BCTN	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	5	0	0	Chưa bắt đầu	14		Sprint 5 Backlog**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G02	5	Thư viện vector và Hybrid Router	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	17		Sprint 5 Backlog**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G04	5	Refresh token cho Chat	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	6		Sprint 5 Backlog**

~~	S5-WBS02.2	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochin...~~

~~	S5-WBS06.2	Kiểm tra refresh thất bại và chống gửi trùng	Refresh token cho Chat	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	2		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~								5	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	116	0	36 task chi tiết; lịch và phân công đề xuất.~~

~~	Số task	40	Giờ dự kiến	116	Tổng giờ thực tế đã ghi																								~~

~~	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Nguyễn Minh Quân	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1															~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2															~~

~~	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng	Nguyễn Minh Quân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1															~~

~~					Tổng giờ theo task			116	0																				~~

~~					Chênh kế hoạch task − kế hoạch ngày: -34 h. 																								~~

~~Phạm vi (task)	40	Done hiện tại	0	Giờ dự kiến	116	Done thiếu ngày	0					~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	66	2	0.030303030303030304	254	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G01	5	Tái hiện lỗi và sửa truy xuất BCTN	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	5	0	0	Chưa bắt đầu	12		Sprint 5 Backlog~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G02	5	Thư viện vector và Hybrid Router	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	16		Sprint 5 Backlog~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G04	5	Refresh token cho Chat	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	5		Sprint 5 Backlog~~

## 2026-11-10 10:02 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 10:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-10 09:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 09:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS08.2	Lấy chỉ tiêu từ các kỳ BCTC và dữ liệu giá gần nhất	Nhận định xu hướng doanh nghiệp	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn. Lấy khối lượng giao dịch, nước ngoài mua bán, thanh khoảng	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC, giá hiện có	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0...**

🟢 **	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC và dữ liệu giá gần nhất	Nguyễn Minh Quân	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn. Lấy khối lượng giao dịch, nước ngoài mua bán, thanh khoảng	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC, giá hiện có															**

~~	S5-WBS08.2	Lấy chỉ tiêu từ các kỳ BCTC gần nhất	Nhận định xu hướng doanh nghiệp	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC gần nhất	Nguyễn Minh Quân	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có															~~

## 2026-11-10 09:22 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 09:22

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochin...**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện. Có bộ kiểm thử bao phủ 90% coverage, và phải đạt từ 90% tỷ lệ thành công thì mới được pass  .	S5-WBS04.2, S5-WBS03.2															**

~~	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															~~

## 2026-11-10 09:17 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-10 09:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS04.3	Tạo và Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Tạo và Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															**

🟢 **Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	40	0	0	40	34.29			5.71		S5-WBS08.2		**

~~	S5-WBS04.3	Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															~~

~~Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	40				34.29			5.71		S5-WBS08.2		~~

## 2026-11-09 21:17 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 21:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS01.2	Tái hiện lỗi hội thoại và hết hạn token	Tái hiện lỗi và sửa truy xuất BCTN	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS04.3	Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 5	S5-WBS01.2	S5-G01	1	Tái hiện lỗi hội thoại và hết hạn token	Nhân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có															**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															**

~~	S5-WBS01.2	Tái hiện lỗi hội thoại và hết hạn token	Tái hiện lỗi và sửa truy xuất BCTN	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS04.3	Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS01.2	S5-G01	1	Tái hiện lỗi hội thoại và hết hạn token		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có															~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router	Nhân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															~~

## 2026-11-09 21:12 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 21:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS03.1	Chốt nhãn ý định và ranh giới giữa các nhãn	Thư viện vector và Hybrid Router	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS03.2	Soạn cụm từ mẫu và bộ câu kiểm thử riêng	Thư viện vector và Hybrid Router	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+07...**

🟢 **	S5-WBS03.3	Vector hóa và lưu phiên bản thư viện	Thư viện vector và Hybrid Router	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS04.1	Đối chiếu vector câu hỏi với thư viện	Thư viện vector và Hybrid Router	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 5	S5-WBS03.1	S5-G02	1	Chốt nhãn ý định và ranh giới giữa các nhãn	Nhân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—															**

🟢 **	Sprint 5	S5-WBS03.2	S5-G02	1	Soạn cụm từ mẫu và bộ câu kiểm thử riêng	Nhân	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1															**

🟢 **	Sprint 5	S5-WBS03.3	S5-G02	1	Vector hóa và lưu phiên bản thư viện	Nhân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2															**

🟢 **	Sprint 5	S5-WBS04.1	S5-G02	1	Đối chiếu vector câu hỏi với thư viện	Nhân	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3															**

~~	S5-WBS03.1	Chốt nhãn ý định và ranh giới giữa các nhãn	Thư viện vector và Hybrid Router	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS03.2	Soạn cụm từ mẫu và bộ câu kiểm thử riêng	Thư viện vector và Hybrid Router	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (...~~

~~	S5-WBS03.3	Vector hóa và lưu phiên bản thư viện	Thư viện vector và Hybrid Router	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS04.1	Đối chiếu vector câu hỏi với thư viện	Thư viện vector và Hybrid Router	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS03.1	S5-G02	1	Chốt nhãn ý định và ranh giới giữa các nhãn		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—															~~

~~	Sprint 5	S5-WBS03.2	S5-G02	1	Soạn cụm từ mẫu và bộ câu kiểm thử riêng		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1															~~

~~	Sprint 5	S5-WBS03.3	S5-G02	1	Vector hóa và lưu phiên bản thư viện		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2															~~

~~	Sprint 5	S5-WBS04.1	S5-G02	1	Đối chiếu vector câu hỏi với thư viện		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3															~~

## 2026-11-09 21:07 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 21:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS04.3	Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2		Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router	Nhân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															**

~~	S5-WBS04.3	Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															~~

## 2026-11-09 21:02 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 21:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS02.2	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS06.1	Dùng cơ chế refresh token chung cho request Chat	Refresh token cho Chat	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	3		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS06.2	Kiểm tra refresh thất bại và chống gửi trùng	Refresh token cho Chat	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	2		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS08.2	Lấy chỉ tiêu từ các kỳ BCTC gần nhất	Nhận định xu hướng doanh nghiệp	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Nguyễn Minh Quân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Nguyễn Minh Quân	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1															**

🟢 **	Sprint 5	S5-WBS06.1	S5-G04	1	Dùng cơ chế refresh token chung cho request Chat	Nguyễn Minh Quân	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập															**

🟢 **	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng	Nguyễn Minh Quân	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1															**

🟢 **	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC gần nhất	Nguyễn Minh Quân	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có															**

~~	S5-WBS02.2	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS06.1	Dùng cơ chế refresh token chung cho request Chat	Refresh token cho Chat	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS06.2	Kiểm tra refresh thất bại và chống gửi trùng	Refresh token cho Chat	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS08.2	Lấy chỉ tiêu từ các kỳ BCTC gần nhất	Nhận định xu hướng doanh nghiệp	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1															~~

~~	Sprint 5	S5-WBS06.1	S5-G04	1	Dùng cơ chế refresh token chung cho request Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập															~~

~~	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1															~~

~~	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC gần nhất		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có															~~

## 2026-11-09 20:53 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 20:53

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS01.1	Tái hiện lỗi hỏi chức vụ và BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3		Đinh Huỳnh Vũ	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Ind...**

🟢 **	S5-WBS02.1	Tìm điều kiện chặn câu hỏi BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2		Đinh Huỳnh Vũ	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS02.3	Kiểm thử truy xuất BCTN bằng dữ liệu thật	Tái hiện lỗi và sửa truy xuất BCTN	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2		Đinh Huỳnh Vũ	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS14	Hoàn thiện trang Admin quản lý quyền truy cập	Admin, Watchlist và nghiệm thu	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồ...**

🟢 **	S5-WBS15	Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)	Admin, Watchlist và nghiệm thu	Cho người dùng thêm hoặc bỏ doanh nghiệp theo mã, xem giá và biến động gần nhất, kỳ BCTC mới nhất và nhận định xu hướng khi có dữ liệu. Gắn liên kết mở chi tiết doanh nghiệp.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Thêm và bỏ mã được, danh sách giữ đúng theo tài khoản sau khi tải lại. Giá, kỳ BCTC và xu hướ...**

🟢 **	Sprint 5	S5-WBS01.1	S5-G01	1	Tái hiện lỗi hỏi chức vụ và BCTN	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4															**

🟢 **	Sprint 5	S5-WBS02.1	S5-G01	1	Tìm điều kiện chặn câu hỏi BCTN	Đinh Huỳnh Vũ	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1															**

🟢 **	Sprint 5	S5-WBS02.3	S5-G01	1	Kiểm thử truy xuất BCTN bằng dữ liệu thật	Đinh Huỳnh Vũ	Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2															**

🟢 **	Sprint 5	S5-WBS14	S5-G09	2	Hoàn thiện trang Admin quản lý quyền truy cập	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồng đăng nhập và p...**

🟢 **	Sprint 5	S5-WBS15	S5-G09	2	Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Cho người dùng thêm hoặc bỏ doanh nghiệp theo mã, xem giá và biến động gần nhất, kỳ BCTC mới nhất và nhận định xu hướng khi có dữ liệu. Gắn liên kết mở chi tiết doanh nghiệp.	Thêm và bỏ mã được, danh sách giữ đúng theo tài khoản sau khi tải lại. Giá, kỳ BCTC và xu hướng khớp mã. Có tr...**

~~	S5-WBS01.1	Tái hiện lỗi hỏi chức vụ và BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	...~~

~~	S5-WBS02.1	Tìm điều kiện chặn câu hỏi BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS02.3	Kiểm thử truy xuất BCTN bằng dữ liệu thật	Tái hiện lỗi và sửa truy xuất BCTN	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS14	Hoàn thiện trang Admin quản lý quyền truy cập	Admin, Watchlist và nghiệm thu	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồ...~~

~~	S5-WBS15	Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)	Admin, Watchlist và nghiệm thu	Cho người dùng thêm hoặc bỏ doanh nghiệp theo mã, xem giá và biến động gần nhất, kỳ BCTC mới nhất và nhận định xu hướng khi có dữ liệu. Gắn liên kết mở chi tiết doanh nghiệp.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Thêm và bỏ mã được, danh sách giữ đúng theo tài khoản sau khi tải lại. Giá, kỳ BCTC và xu hướ...~~

~~	Sprint 5	S5-WBS01.1	S5-G01	1	Tái hiện lỗi hỏi chức vụ và BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4															~~

~~	Sprint 5	S5-WBS02.1	S5-G01	1	Tìm điều kiện chặn câu hỏi BCTN		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1															~~

~~	Sprint 5	S5-WBS02.3	S5-G01	1	Kiểm thử truy xuất BCTN bằng dữ liệu thật		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2															~~

~~	Sprint 5	S5-WBS14	S5-G09	2	Hoàn thiện trang Admin quản lý quyền truy cập		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồng đăng nhập và phân quyền hiệ...~~

~~	Sprint 5	S5-WBS15	S5-G09	2	Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Cho người dùng thêm hoặc bỏ doanh nghiệp theo mã, xem giá và biến động gần nhất, kỳ BCTC mới nhất và nhận định xu hướng khi có dữ liệu. Gắn liên kết mở chi tiết doanh nghiệp.	Thêm và bỏ mã được, danh sách giữ đúng theo tài khoản sau khi tải lại. Giá, kỳ BCTC và xu hướng khớp mã. Có trạng thái danh...~~

## 2026-11-09 20:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 20:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S5-WBS13.1	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat	Admin, Watchlist và nghiệm thu	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+...**

🟢 **	S5-WBS13.2	Đánh giá router và fallback trên bộ câu riêng	Admin, Watchlist và nghiệm thu	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **	S5-WBS13.3	Đối chiếu nhận định xu hướng và citation	Admin, Watchlist và nghiệm thu	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GM...**

🟢 **	S5-WBS13.4	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Admin, Watchlist và nghiệm thu	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	2			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT...**

🟢 **	S5-WBS14	Hoàn thiện trang Admin quản lý quyền truy cập	Admin, Watchlist và nghiệm thu	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồ...**

🟢 **	S5-WBS15	Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)	Admin, Watchlist và nghiệm thu	Cho người dùng thêm hoặc bỏ doanh nghiệp theo mã, xem giá và biến động gần nhất, kỳ BCTC mới nhất và nhận định xu hướng khi có dữ liệu. Gắn liên kết mở chi tiết doanh nghiệp.	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Thêm và bỏ mã được, danh sách giữ đúng theo tài khoản sau khi tải lại. Giá, kỳ BCTC và xu hướ...**

🟢 **	Sprint 5	S5-WBS15	S5-G09	2	Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Cho người dùng thêm hoặc bỏ doanh nghiệp theo mã, xem giá và biến động gần nhất, kỳ BCTC mới nhất và nhận định xu hướng khi có dữ liệu. Gắn liên kết mở chi tiết doanh nghiệp.	Thêm và bỏ mã được, danh sách giữ đúng theo tài khoản sau khi tải lại. Giá, kỳ BCTC và xu hướng khớp mã. Có trạng thái danh...**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G09	5	Admin, Watchlist và nghiệm thu	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	20		Sprint 5 Backlog**

🟢 **S5-G09	5	Admin, Watchlist và nghiệm thu	S5-WBS13.1: Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat**

🟢 **S5-WBS15: Hoàn thiện danh sách theo dõi doanh nghiệp (Watchlist)	Có kết quả hồi quy và demo. Admin quản lý được quyền truy cập. Người dùng theo dõi được doanh nghiệp quan tâm và xem cập nhật có nguồn.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.**

~~	S5-WBS13.1	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat	Vận hành, theo dõi và nghiệm thu	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)...~~

~~	S5-WBS13.2	Đánh giá router và fallback trên bộ câu riêng	Vận hành, theo dõi và nghiệm thu	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS13.3	Đối chiếu nhận định xu hướng và citation	Vận hành, theo dõi và nghiệm thu	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Tim...~~

~~	S5-WBS13.4	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Vận hành, theo dõi và nghiệm thu	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	2			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time...~~

~~	S5-WBS14	Hoàn thiện trang Admin quản lý quyền truy cập	Vận hành, theo dõi và nghiệm thu	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồng đăng nhập và phân ...~~

~~	S5-WBS15	Hoàn thiện trang theo dõi vận hành Chat	Vận hành, theo dõi và nghiệm thu	Hiển thị số request, lỗi, thời gian phản hồi và số lần fallback theo khoảng thời gian từ trace có sẵn. Cho xem chi tiết bằng trace ID, hạn chế dữ liệu nhạy cảm.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Admin lọc theo thời gian và đối chiếu được số liệu với trace. Có trạng thái rỗng và lỗi tải. Người không có quyền bị chặn.	S5-WBS05.3, S5-WBS07...~~

~~	Sprint 5	S5-WBS15	S5-G09	2	Hoàn thiện trang theo dõi vận hành Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Hiển thị số request, lỗi, thời gian phản hồi và số lần fallback theo khoảng thời gian từ trace có sẵn. Cho xem chi tiết bằng trace ID, hạn chế dữ liệu nhạy cảm.	Admin lọc theo thời gian và đối chiếu được số liệu với trace. Có trạng thái rỗng và lỗi tải. Người không có quyền bị chặn.	S5-WBS05.3, S5-WBS07.3, quyền...~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G09	5	Vận hành, theo dõi và nghiệm thu	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	20		Sprint 5 Backlog~~

~~S5-G09	5	Vận hành, theo dõi và nghiệm thu	S5-WBS13.1: Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat~~

~~S5-WBS15: Hoàn thiện trang theo dõi vận hành Chat	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.~~

## 2026-11-09 20:12 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 20:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								5	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	116	0	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	S5-WBS13.1	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat	Vận hành, theo dõi và nghiệm thu	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)...**

🟢 **	S5-WBS13.2	Đánh giá router và fallback trên bộ câu riêng	Vận hành, theo dõi và nghiệm thu	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS13.3	Đối chiếu nhận định xu hướng và citation	Vận hành, theo dõi và nghiệm thu	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Tim...**

🟢 **	S5-WBS13.4	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Vận hành, theo dõi và nghiệm thu	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	2			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time...**

🟢 **	S5-WBS14	Hoàn thiện trang Admin quản lý quyền truy cập	Vận hành, theo dõi và nghiệm thu	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồng đăng nhập và phân ...**

🟢 **	S5-WBS15	Hoàn thiện trang theo dõi vận hành Chat	Vận hành, theo dõi và nghiệm thu	Hiển thị số request, lỗi, thời gian phản hồi và số lần fallback theo khoảng thời gian từ trace có sẵn. Cho xem chi tiết bằng trace ID, hạn chế dữ liệu nhạy cảm.	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Admin lọc theo thời gian và đối chiếu được số liệu với trace. Có trạng thái rỗng và lỗi tải. Người không có quyền bị chặn.	S5-WBS05.3, S5-WBS07...**

🟢 **	Sprint 5 gồm 40 task. Tuần 1 sửa lỗi và nối truy xuất (58h). Tuần 2 tối ưu Chat, nhận định xu hướng, Admin và theo dõi (58h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																												**

🟢 **	Số task	40	Giờ dự kiến	116	Tổng giờ thực tế đã ghi																								**

🟢 **	Sprint 5	S5-WBS14	S5-G09	2	Hoàn thiện trang Admin quản lý quyền truy cập		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bổ sung màn hình danh sách người dùng và vai trò. Nối chức năng cập nhật quyền bằng API hiện có, hiển thị lỗi và yêu cầu xác nhận trước khi đổi quyền.	Admin xem và cập nhật được vai trò hợp lệ. Tài khoản thường bị chặn cả ở UI lẫn API. Có ca kiểm thử quyền và lỗi cập nhật.	Luồng đăng nhập và phân quyền hiệ...**

🟢 **	Sprint 5	S5-WBS15	S5-G09	2	Hoàn thiện trang theo dõi vận hành Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Hiển thị số request, lỗi, thời gian phản hồi và số lần fallback theo khoảng thời gian từ trace có sẵn. Cho xem chi tiết bằng trace ID, hạn chế dữ liệu nhạy cảm.	Admin lọc theo thời gian và đối chiếu được số liệu với trace. Có trạng thái rỗng và lỗi tải. Người không có quyền bị chặn.	S5-WBS05.3, S5-WBS07.3, quyền...**

🟢 **					Tổng giờ theo task			116	0																				**

🟢 **					Chênh kế hoạch task − kế hoạch ngày: -34 h. 																								**

🟢 **Hiện tại: 0/40 task Done · còn 40 task · 0 Done thiếu ngày												**

🟢 **Phạm vi (task)	40	Done hiện tại	0	Giờ dự kiến	116	Done thiếu ngày	0					**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	40		0	40	40			0		S5-WBS07.3		**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	40	0	0	40	37.14			2.86		S5-WBS08.1		**

🟢 **Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	40				34.29			5.71		S5-WBS08.2		**

🟢 **Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	40				31.43			8.57		S5-WBS08.3		**

🟢 **Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	40				28.57			11.43		S5-WBS09.1		**

🟢 **Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	40				25.71			14.29		S5-WBS09.2		**

🟢 **Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	40				22.86			17.14		S5-WBS09.3		**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	40				20			20		S5-WBS10.1		**

🟢 **Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	40				17.14			22.86		S5-WBS10.2		**

🟢 **Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	40				14.29			25.71		S5-WBS10.3		**

🟢 **Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	40				11.43			28.57		S5-WBS10.4		**

🟢 **Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	40				8.57			31.43		S5-WBS11.1		**

🟢 **Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	40				5.71			34.29		S5-WBS11.2		**

🟢 **Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	40				2.86			37.14		S5-WBS12.1		**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	40				0			40		S5-WBS12.2		**

🟢 **Hiện tại	40		0	40						S5-WBS12.3		**

🟢 **										S5-WBS14		**

🟢 **										S5-WBS15		**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	66	2	0.030303030303030304	254	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G09	5	Vận hành, theo dõi và nghiệm thu	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	20		Sprint 5 Backlog**

🟢 **Tổng task	199		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						**

🟢 **Độ hoàn thành	0.5276381909547738		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **S5-G09	5	Vận hành, theo dõi và nghiệm thu	S5-WBS13.1: Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat**

🟢 **S5-WBS13.4: Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại**

🟢 **S5-WBS14: Hoàn thiện trang Admin quản lý quyền truy cập**

🟢 **S5-WBS15: Hoàn thiện trang theo dõi vận hành Chat	Có kết quả hồi quy và demo, trang Admin kiểm soát được quyền và trang theo dõi đối chiếu được số liệu với trace.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.**

~~								5	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	108	0	36 task chi tiết; lịch và phân công đề xuất.~~

~~	S5-WBS13.1	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat	Hồi quy, đánh giá và demo	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS13.2	Đánh giá router và fallback trên bộ câu riêng	Hồi quy, đánh giá và demo	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS13.3	Đối chiếu nhận định xu hướng và citation	Hồi quy, đánh giá và demo	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS13.4	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Hồi quy, đánh giá và demo	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	2			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	Sprint 5 gồm 38 task con. Tuần 1 sửa lỗi và nối truy xuất (58h); tuần 2 tối ưu Chat và nhận định xu hướng (50h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																												~~

~~	Số task	38	Giờ dự kiến	108	Tổng giờ thực tế đã ghi																								~~

~~					Tổng giờ theo task			108	0																				~~

~~					Chênh kế hoạch task − kế hoạch ngày: -42 h. 																								~~

~~Hiện tại: 0/38 task Done · còn 38 task · 0 Done thiếu ngày												~~

~~Phạm vi (task)	38	Done hiện tại	0	Giờ dự kiến	108	Done thiếu ngày	0					~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38			0		S5-WBS07.3		~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29			2.71		S5-WBS08.1		~~

~~Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57			5.43		S5-WBS08.2		~~

~~Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86			8.14		S5-WBS08.3		~~

~~Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14			10.86		S5-WBS09.1		~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43			13.57		S5-WBS09.2		~~

~~Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71			16.29		S5-WBS09.3		~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19			19		S5-WBS10.1		~~

~~Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29			21.71		S5-WBS10.2		~~

~~Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57			24.43		S5-WBS10.3		~~

~~Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86			27.14		S5-WBS10.4		~~

~~Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14			29.86		S5-WBS11.1		~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43			32.57		S5-WBS11.2		~~

~~Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71			35.29		S5-WBS12.1		~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0			38		S5-WBS12.2		~~

~~Hiện tại	38		0	38						S5-WBS12.3		~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	64	2	0.03125	246	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G09	5	Hồi quy, đánh giá và demo	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	12		Sprint 5 Backlog~~

~~Tổng task	197		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						~~

~~Độ hoàn thành	0.5329949238578681		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~S5-G09	5	Hồi quy, đánh giá và demo	S5-WBS13.1: Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat~~

~~S5-WBS13.4: Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.~~

## 2026-11-09 16:02 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 16:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-09 15:57 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-09 15:42 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:42

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **Sprint 1 Report												**

🟢 **Hiện tại: 42/42 task Done · còn 0 task · 42 Done thiếu ngày												**

🟢 **Đường theo ngày gồm 42 task ước tính (41 theo nhật ký giờ, 1 theo deadline).												**

🟢 **Phạm vi (task)	42	Done hiện tại	42	Giờ dự kiến	146	Done thiếu ngày	42					**

🟢 **Giờ thực tế	163	Bắt đầu	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0					**

🟢 **Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.												**

🟢 **Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.												**

🟢 **										Mã task	Ngày dùng để vẽ	Nguồn mốc**

🟢 **										Mã task	Ngày dùng để vẽ	Nguồn mốc**

🟢 **										Mã task	Ngày dùng để vẽ	Nguồn mốc**

🟢 **										Mã task	Ngày dùng để vẽ	Nguồn mốc**

🟢 **										Mã task	Ngày dùng để vẽ	Nguồn mốc**

🟢 **										Mã task	Ngày dùng để vẽ	Nguồn mốc**

🟢 **										S1-T01	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T02	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T03	Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T04	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T05	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T06	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T07	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T08	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T09	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T10	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T11	Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T12	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T13	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T14	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S1-T15	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T16	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Ưu tiên ngày thực tế ở cột P, rồi ngày cuối có ghi giờ, rồi deadline. Xem nguồn từng task ở cột K–M. Hàng Hiện tại lấy trạng thái từ backlog.										S1-T17	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Ngày	Phạm vi (task)	Done theo ngày\*	Done lũy kế\*	Task còn lại\*	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch		S1-T18	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		0	42	42			0		S1-T19	Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	2	2	40	40.85	6	6	1.15		S1-T20	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	2	40	39.7	7	13	2.3		S1-T21	Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	2	40	39.7	1	14	2.3		S1-T22	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	2	40	39.7		14	2.3		S1-T23	Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	2	4	38	35.96	14	28	6.04		S1-T24	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	5	9	33	31.64	12	40	10.36		S1-T25	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	2	11	31	27.33	15	55	14.67		S1-T26	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	4	15	27	23.01	11	66	18.99		S1-T27	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	3	18	24	19.27	14	80	22.73		S1-T28	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	18	24	19.27		80	22.73		S1-T29	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	18	24	19.27		80	22.73		S1-T30	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	2	20	22	15.53	15	95	26.47		S1-T31	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	4	24	18	11.22	15	110	30.78		S1-T32	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	6	30	12	6.9	13	123	35.1		S1-T33	Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	5	35	7	3.16	15	138	38.84		S1-T34	Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	5	40	2	0	16	154	42		S1-T35	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	1	41	1	0	3	157	42		S1-T36	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	1	42	0	0		157	42		S1-T37	Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Hiện tại	42		42	0						S1-T38	Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T39	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T40	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T41	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S1-T42	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sprint 2 Report												**

🟢 **Hiện tại: 28/28 task Done · còn 0 task · 28 Done thiếu ngày												**

🟢 **Đường theo ngày gồm 28 task ước tính (21 theo nhật ký giờ, 7 theo deadline).												**

🟢 **Phạm vi (task)	28	Done hiện tại	28	Giờ dự kiến	141	Done thiếu ngày	28					**

🟢 **Giờ thực tế	122	Bắt đầu	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0					**

🟢 **										S2-WBS01	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS02	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS03	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS04	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS05	Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS06	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS07	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS08	Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS09	Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS10	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS11	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **										S2-WBS12	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Ưu tiên ngày thực tế ở cột P, rồi ngày cuối có ghi giờ, rồi deadline. Xem nguồn từng task ở cột K–M. Hàng Hiện tại lấy trạng thái từ backlog.										S2-WBS13	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Ngày	Phạm vi (task)	Done theo ngày\*	Done lũy kế\*	Task còn lại\*	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch		S2-WBS14	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28		0	28	28			0		S2-WBS15	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	1	1	27	26	7	7	2		S2-WBS16	Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	2	3	25	24	12	19	4		S2-WBS17	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	2	5	23	22	13	32	6		S2-WBS18	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	3	8	20	20	13	45	8		S2-WBS19	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	4	12	16	18	11	56	10		S2-WBS20	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	2	14	14	16	6	62	12		S2-WBS21	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	14	14	14		62	14		S2-WBS22	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	1	15	13	12	12	74	16		S2-WBS23	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	3	18	10	10	13	87	18		S2-WBS24	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	3	21	7	8	13	100	20		S2-WBS25	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	1	22	6	6	11	111	22		S2-WBS26	Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	6	28	0	4	11	122	24		S2-WBS27	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	28	0	2		122	26		S2-WBS28	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	28	0	0		122	28				**

🟢 **Hiện tại	28		28	0								**

🟢 **Sprint 3 Report												**

🟢 **Hiện tại: 29/36 task Done · còn 7 task · 29 Done thiếu ngày												**

🟢 **Đường theo ngày gồm 29 task ước tính (12 theo nhật ký giờ, 17 theo deadline).												**

🟢 **Phạm vi (task)	36	Done hiện tại	29	Giờ dự kiến	150	Done thiếu ngày	29					**

🟢 **Giờ thực tế	52	Bắt đầu	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0					**

🟢 **										S3-WBS01	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS06	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS11	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS16	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS19		**

🟢 **										S3-WBS24		**

🟢 **										S3-WBS29		**

🟢 **										S3-WBS02	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS07	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS12	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS17	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS20	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS25	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS30		**

🟢 **										S3-WBS34		**

🟢 **										S3-WBS05	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Ưu tiên ngày thực tế ở cột P, rồi ngày cuối có ghi giờ, rồi deadline. Xem nguồn từng task ở cột K–M. Hàng Hiện tại lấy trạng thái từ backlog.										S3-WBS10	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Ngày	Phạm vi (task)	Done theo ngày\*	Done lũy kế\*	Task còn lại\*	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch		S3-WBS15	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36		0	36	36			0		S3-WBS23	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	4	4	32	32.4	5	5	3.6		S3-WBS28	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	2	6	30	28.8	9	14	7.2		S3-WBS33	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	5	11	25	25.2	6	20	10.8		S3-WBS36		**

🟢 **Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	2	13	23	21.6	3	23	14.4		S3-WBS03	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	4	17	19	18	3	26	18		S3-WBS08	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	1	18	18	18	1	27	18		S3-WBS13	Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	18	18	18		27	18		S3-WBS18	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	2	20	16	14.4	7	34	21.6		S3-WBS21	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	1	21	15	10.8	3	37	25.2		S3-WBS26	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	3	24	12	7.2	3	40	28.8		S3-WBS31	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	2	26	10	3.6	3	43	32.4		S3-WBS35	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: nhật ký giờ**

🟢 **Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	3	29	7	0	3	46	36		S3-WBS04	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	29	7	0		46	36		S3-WBS09	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	29	7	0		46	36		S3-WBS14	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Hiện tại	36		29	7						S3-WBS22	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS27	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S3-WBS32		**

🟢 **Sprint 4 Report												**

🟢 **Hiện tại: 6/17 task Done · còn 11 task · 6 Done thiếu ngày												**

🟢 **Đường theo ngày gồm 6 task ước tính (0 theo nhật ký giờ, 6 theo deadline).												**

🟢 **Phạm vi (task)	17	Done hiện tại	6	Giờ dự kiến	128	Done thiếu ngày	6					**

🟢 **Giờ thực tế		Bắt đầu	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0					**

🟢 **										S4-WBS04		**

🟢 **										S4-WBS07		**

🟢 **										S4-WBS11		**

🟢 **										S4-WBS16		**

🟢 **										S4-WBS03		**

🟢 **										S4-WBS08		**

🟢 **										S4-WBS12		**

🟢 **										S4-WBS17		**

🟢 **										S4-WBS05		**

🟢 **										S4-WBS13		**

🟢 **										S4-WBS14		**

🟢 **										S4-WBS01	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S4-WBS02	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S4-WBS09	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S4-WBS06	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **										S4-WBS10	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Ưu tiên ngày thực tế ở cột P, rồi ngày cuối có ghi giờ, rồi deadline. Xem nguồn từng task ở cột K–M. Hàng Hiện tại lấy trạng thái từ backlog.										S4-WBS15	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	Ước tính: deadline**

🟢 **Ngày	Phạm vi (task)	Done theo ngày\*	Done lũy kế\*	Task còn lại\*	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch				**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17		0	17	17			0				**

🟢 **Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0	17	15.79			1.21				**

🟢 **Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0	17	14.57			2.43				**

🟢 **Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0	17	13.36			3.64				**

🟢 **Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	2	2	15	12.14			4.86				**

🟢 **Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	2	4	13	10.93			6.07				**

🟢 **Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	4	13	9.71			7.29				**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	4	13	8.5			8.5				**

🟢 **Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	4	13	7.29			9.71				**

🟢 **Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	4	13	6.07			10.93				**

🟢 **Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	4	13	4.86			12.14				**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	1	5	12	3.64			13.36				**

🟢 **Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	1	6	11	2.43			14.57				**

🟢 **Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	6	11	1.21			15.79				**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	6	11	0			17				**

🟢 **Hiện tại	17		6	11								**

🟢 **Sprint 5 Report												**

🟢 **Hiện tại: 0/38 task Done · còn 38 task · 0 Done thiếu ngày												**

🟢 **Đường theo ngày gồm 0 task ước tính (0 theo nhật ký giờ, 0 theo deadline).												**

🟢 **Đường theo ngày gồm 0 task ước tính (0 theo nhật ký giờ, 0 theo deadline).												**

🟢 **Phạm vi (task)	38	Done hiện tại	0	Giờ dự kiến	108	Done thiếu ngày	0					**

🟢 **Giờ thực tế		Bắt đầu	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0					**

🟢 **										S5-WBS01.1		**

🟢 **										S5-WBS01.2		**

🟢 **										S5-WBS02.1		**

🟢 **										S5-WBS02.2		**

🟢 **										S5-WBS02.3		**

🟢 **										S5-WBS03.1		**

🟢 **										S5-WBS03.2		**

🟢 **										S5-WBS03.3		**

🟢 **										S5-WBS04.1		**

🟢 **										S5-WBS04.2		**

🟢 **										S5-WBS04.3		**

🟢 **										S5-WBS05.1		**

🟢 **										S5-WBS05.2		**

🟢 **										S5-WBS05.3		**

🟢 **										S5-WBS06.1		**

🟢 **										S5-WBS06.2		**

🟢 **Ưu tiên ngày thực tế ở cột P, rồi ngày cuối có ghi giờ, rồi deadline. Xem nguồn từng task ở cột K–M. Hàng Hiện tại lấy trạng thái từ backlog.										S5-WBS07.1		**

🟢 **Ngày	Phạm vi (task)	Done theo ngày\*	Done lũy kế\*	Task còn lại\*	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch		S5-WBS07.2		**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38			0		S5-WBS07.3		**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29			2.71		S5-WBS08.1		**

🟢 **Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57			5.43		S5-WBS08.2		**

🟢 **Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86			8.14		S5-WBS08.3		**

🟢 **Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14			10.86		S5-WBS09.1		**

🟢 **Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43			13.57		S5-WBS09.2		**

🟢 **Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71			16.29		S5-WBS09.3		**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19			19		S5-WBS10.1		**

🟢 **Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29			21.71		S5-WBS10.2		**

🟢 **Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57			24.43		S5-WBS10.3		**

🟢 **Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86			27.14		S5-WBS10.4		**

🟢 **Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14			29.86		S5-WBS11.1		**

🟢 **Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43			32.57		S5-WBS11.2		**

🟢 **Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71			35.29		S5-WBS12.1		**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0			38		S5-WBS12.2		**

🟢 **Hiện tại	38		0	38						S5-WBS12.3		**

🟢 **										S5-WBS13.1		**

🟢 **										S5-WBS13.2		**

🟢 **										S5-WBS13.3		**

🟢 **										S5-WBS13.4		**

🟢 **Sprint 6 Report												**

🟢 **Hiện tại: 0/36 task Done · còn 36 task · 0 Done thiếu ngày												**

🟢 **Phạm vi (task)	36	Done hiện tại	0	Giờ dự kiến	150	Done thiếu ngày	0					**

🟢 **Giờ thực tế		Bắt đầu	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0					**

🟢 **										S6-WBS01		**

🟢 **										S6-WBS02		**

🟢 **										S6-WBS03		**

🟢 **										S6-WBS04		**

🟢 **										S6-WBS05		**

🟢 **										S6-WBS06		**

🟢 **										S6-WBS07		**

🟢 **										S6-WBS08		**

🟢 **										S6-WBS09		**

🟢 **										S6-WBS10		**

🟢 **										S6-WBS11		**

🟢 **										S6-WBS12		**

🟢 **										S6-WBS13		**

🟢 **										S6-WBS14		**

🟢 **										S6-WBS15		**

🟢 **										S6-WBS16		**

🟢 **Ưu tiên ngày thực tế ở cột P, rồi ngày cuối có ghi giờ, rồi deadline. Xem nguồn từng task ở cột K–M. Hàng Hiện tại lấy trạng thái từ backlog.										S6-WBS17		**

🟢 **Ngày	Phạm vi (task)	Done theo ngày\*	Done lũy kế\*	Task còn lại\*	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch		S6-WBS18		**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			0		S6-WBS19		**

🟢 **Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				32.4			3.6		S6-WBS20		**

🟢 **Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.8			7.2		S6-WBS21		**

🟢 **Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.2			10.8		S6-WBS22		**

🟢 **Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				21.6			14.4		S6-WBS23		**

🟢 **Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18		S6-WBS24		**

🟢 **Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18		S6-WBS25		**

🟢 **Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18		S6-WBS26		**

🟢 **Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				14.4			21.6		S6-WBS27		**

🟢 **Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.8			25.2		S6-WBS28		**

🟢 **Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.2			28.8		S6-WBS29		**

🟢 **Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				3.6			32.4		S6-WBS30		**

🟢 **Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36		S6-WBS31		**

🟢 **Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36		S6-WBS32		**

🟢 **Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36		S6-WBS33		**

🟢 **Hiện tại	36		0	36						S6-WBS34		**

🟢 **										S6-WBS35		**

🟢 **										S6-WBS36		**

~~Sprint 1 Report								~~

~~Hiện tại: 42/42 task Done · còn 0 task · 42 Done thiếu ngày								~~

~~Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								~~

~~Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								~~

~~Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								~~

~~Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								~~

~~Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								~~

~~Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								~~

~~Phạm vi (task)	42	Done hiện tại	42	Giờ dự kiến	146	Done thiếu ngày	42	~~

~~Giờ thực tế	163	Bắt đầu	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	~~

~~Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.								~~

~~Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.								~~

~~Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								~~

~~Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								~~

~~Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								~~

~~Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								~~

~~Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								~~

~~Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								~~

~~Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch~~

~~Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch~~

~~Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch~~

~~Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch~~

~~Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch~~

~~Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch~~

~~Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42				42			0~~

~~Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42				40.85	6	6	1.15~~

~~Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42				39.7	7	13	2.3~~

~~Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42				39.7	1	14	2.3~~

~~Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42				39.7		14	2.3~~

~~Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42				35.96	14	28	6.04~~

~~Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42				31.64	12	40	10.36~~

~~Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42				27.33	15	55	14.67~~

~~Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42				23.01	11	66	18.99~~

~~Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42				19.27	14	80	22.73~~

~~Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42				19.27		80	22.73~~

~~Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42				19.27		80	22.73~~

~~Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42				15.53	15	95	26.47~~

~~Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42				11.22	15	110	30.78~~

~~Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42				6.9	13	123	35.1~~

~~Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42				3.16	15	138	38.84~~

~~Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42				0	16	154	42~~

~~Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42				0	3	157	42~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42				0		157	42~~

~~Hiện tại	42		42	0				~~

~~Sprint 2 Report								~~

~~Hiện tại: 28/28 task Done · còn 0 task · 28 Done thiếu ngày								~~

~~Phạm vi (task)	28	Done hiện tại	28	Giờ dự kiến	141	Done thiếu ngày	28	~~

~~Giờ thực tế	122	Bắt đầu	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28				28			0~~

~~Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28				26	7	7	2~~

~~Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28				24	12	19	4~~

~~Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28				22	13	32	6~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28				20	13	45	8~~

~~Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28				18	11	56	10~~

~~Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28				16	6	62	12~~

~~Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28				14		62	14~~

~~Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28				12	12	74	16~~

~~Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28				10	13	87	18~~

~~Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28				8	13	100	20~~

~~Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28				6	11	111	22~~

~~Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28				4	11	122	24~~

~~Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28				2		122	26~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28				0		122	28~~

~~Hiện tại	28		28	0				~~

~~Sprint 3 Report								~~

~~Hiện tại: 29/36 task Done · còn 7 task · 29 Done thiếu ngày								~~

~~Phạm vi (task)	36	Done hiện tại	29	Giờ dự kiến	150	Done thiếu ngày	29	~~

~~Giờ thực tế	52	Bắt đầu	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			0~~

~~Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36				32.4	5	5	3.6~~

~~Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.8	9	14	7.2~~

~~Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.2	6	20	10.8~~

~~Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36				21.6	3	23	14.4~~

~~Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36				18	3	26	18~~

~~Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36				18	1	27	18~~

~~Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36				18		27	18~~

~~Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36				14.4	7	34	21.6~~

~~Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.8	3	37	25.2~~

~~Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.2	3	40	28.8~~

~~Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				3.6	3	43	32.4~~

~~Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				0	3	46	36~~

~~Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				0		46	36~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				0		46	36~~

~~Hiện tại	36		29	7				~~

~~Sprint 4 Report								~~

~~Hiện tại: 6/17 task Done · còn 11 task · 6 Done thiếu ngày								~~

~~Phạm vi (task)	17	Done hiện tại	6	Giờ dự kiến	128	Done thiếu ngày	6	~~

~~Giờ thực tế		Bắt đầu	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17				17			0~~

~~Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17				15.79			1.21~~

~~Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17				14.57			2.43~~

~~Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17				13.36			3.64~~

~~Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17				12.14			4.86~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17				10.93			6.07~~

~~Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17				9.71			7.29~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17				8.5			8.5~~

~~Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17				7.29			9.71~~

~~Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17				6.07			10.93~~

~~Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17				4.86			12.14~~

~~Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17				3.64			13.36~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17				2.43			14.57~~

~~Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17				1.21			15.79~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17				0			17~~

~~Hiện tại	17		6	11				~~

~~Sprint 5 Report								~~

~~Hiện tại: 0/38 task Done · còn 38 task · 0 Done thiếu ngày								~~

~~Phạm vi (task)	38	Done hiện tại	0	Giờ dự kiến	108	Done thiếu ngày	0	~~

~~Giờ thực tế		Bắt đầu	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38			0~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29			2.71~~

~~Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57			5.43~~

~~Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86			8.14~~

~~Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14			10.86~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43			13.57~~

~~Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71			16.29~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19			19~~

~~Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29			21.71~~

~~Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57			24.43~~

~~Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86			27.14~~

~~Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14			29.86~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43			32.57~~

~~Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71			35.29~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0			38~~

~~Hiện tại	38		0	38				~~

~~Sprint 6 Report								~~

~~Hiện tại: 0/36 task Done · còn 36 task · 0 Done thiếu ngày								~~

~~Phạm vi (task)	36	Done hiện tại	0	Giờ dự kiến	150	Done thiếu ngày	0	~~

~~Giờ thực tế		Bắt đầu	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			0~~

~~Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				32.4			3.6~~

~~Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.8			7.2~~

~~Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.2			10.8~~

~~Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				21.6			14.4~~

~~Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18~~

~~Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18~~

~~Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18~~

~~Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				14.4			21.6~~

~~Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.8			25.2~~

~~Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.2			28.8~~

~~Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				3.6			32.4~~

~~Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36~~

~~Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36~~

~~Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36~~

~~Hiện tại	36		0	36				~~

## 2026-11-09 15:37 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **					Tổng giờ theo task			146	163																								**

🟢 **					Kế hoạch giờ theo ngày			146								4	4			13	15	15	15	13			13	15	15	13	11		**

🟢 **					Giờ đã ghi theo ngày				157							6	7	1	0	14	12	15	11	14	0	0	15	15	13	15	16	3	0**

🟢 **					Chênh giờ thực tế theo task − giờ ghi theo ngày: 6 h.																												**

🟢 **Hiện tại: 42/42 task Done · còn 0 task · 42 Done thiếu ngày								**

🟢 **Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								**

🟢 **Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								**

🟢 **Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								**

🟢 **Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								**

🟢 **Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								**

🟢 **Biểu đồ chỉ chạy trong khung sprint. Điền ngày hoàn thành thực tế ở cột P để bổ sung đường tiến độ theo ngày.								**

🟢 **Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								**

🟢 **Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								**

🟢 **Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								**

🟢 **Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								**

🟢 **Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								**

🟢 **Đường kế hoạch theo phân bổ giờ từng ngày nếu khớp tổng giờ task, nếu không thì dùng đường lý tưởng tuyến tính. Hàng Hiện tại nằm ngoài biểu đồ.								**

🟢 **Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch**

🟢 **Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch**

🟢 **Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch**

🟢 **Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch**

🟢 **Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch**

🟢 **Ngày	Phạm vi (task)	Done trong ngày có ghi	Done lũy kế có ngày	Còn lại thực tế	Còn lại theo kế hoạch	Giờ thực tế/ngày	Giờ thực tế lũy kế	Done theo kế hoạch**

🟢 **Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42				42			0**

🟢 **Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42				40.85	6	6	1.15**

🟢 **Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42				39.7	7	13	2.3**

🟢 **Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42				39.7	1	14	2.3**

🟢 **Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42				39.7		14	2.3**

🟢 **Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42				35.96	14	28	6.04**

🟢 **Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42				31.64	12	40	10.36**

🟢 **Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42				27.33	15	55	14.67**

🟢 **Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42				23.01	11	66	18.99**

🟢 **Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42				19.27	14	80	22.73**

🟢 **Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42				19.27		80	22.73**

🟢 **Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42				19.27		80	22.73**

🟢 **Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42				15.53	15	95	26.47**

🟢 **Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42				11.22	15	110	30.78**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42				6.9	13	123	35.1**

🟢 **Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42				3.16	15	138	38.84**

🟢 **Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42				0	16	154	42**

🟢 **Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42				0	3	157	42**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42				0		157	42**

🟢 **Hiện tại	42		42	0				**

🟢 **					Tổng giờ theo task			141	122																				**

🟢 **					Kế hoạch giờ theo ngày			150								15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Kế hoạch giờ theo ngày			150								15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Kế hoạch giờ theo ngày			150								15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Kế hoạch giờ theo ngày			150								15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Kế hoạch giờ theo ngày			150								15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Giờ đã ghi theo ngày				122							7	12	13	13	11	6	0	12	13	13	11	11	0	0**

🟢 **					Chênh kế hoạch task − kế hoạch ngày: -9 h. 																								**

🟢 **Hiện tại: 28/28 task Done · còn 0 task · 28 Done thiếu ngày								**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28				28			0**

🟢 **Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28				26	7	7	2**

🟢 **Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28				24	12	19	4**

🟢 **Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28				22	13	32	6**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28				20	13	45	8**

🟢 **Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28				18	11	56	10**

🟢 **Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28				16	6	62	12**

🟢 **Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28				14		62	14**

🟢 **Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28				12	12	74	16**

🟢 **Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28				10	13	87	18**

🟢 **Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28				8	13	100	20**

🟢 **Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28				6	11	111	22**

🟢 **Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28				4	11	122	24**

🟢 **Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28				2		122	26**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28				0		122	28**

🟢 **Hiện tại	28		28	0				**

🟢 **					Tổng giờ theo task			150	52																				**

🟢 **					Giờ đã ghi theo ngày				46							5	9	6	3	3	1	0	7	3	3	3	3	0	0**

🟢 **					Chênh giờ thực tế theo task − giờ ghi theo ngày: 6 h.																								**

🟢 **Hiện tại: 29/36 task Done · còn 7 task · 29 Done thiếu ngày								**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			0**

🟢 **Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36				32.4	5	5	3.6**

🟢 **Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.8	9	14	7.2**

🟢 **Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.2	6	20	10.8**

🟢 **Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36				21.6	3	23	14.4**

🟢 **Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36				18	3	26	18**

🟢 **Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36				18	1	27	18**

🟢 **Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36				18		27	18**

🟢 **Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36				14.4	7	34	21.6**

🟢 **Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.8	3	37	25.2**

🟢 **Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.2	3	40	28.8**

🟢 **Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				3.6	3	43	32.4**

🟢 **Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				0	3	46	36**

🟢 **Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				0		46	36**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				0		46	36**

🟢 **Hiện tại	36		29	7				**

🟢 **					Tổng giờ theo task			128	0																				**

🟢 **					Giờ đã ghi theo ngày				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0**

🟢 **					Giờ đã ghi theo ngày				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0**

🟢 **					Giờ đã ghi theo ngày				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0**

🟢 **					Chênh kế hoạch task − kế hoạch ngày: -22 h. 																								**

🟢 **Hiện tại: 6/17 task Done · còn 11 task · 6 Done thiếu ngày								**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17				17			0**

🟢 **Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17				15.79			1.21**

🟢 **Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17				14.57			2.43**

🟢 **Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17				13.36			3.64**

🟢 **Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17				12.14			4.86**

🟢 **Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17				10.93			6.07**

🟢 **Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17				9.71			7.29**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17				8.5			8.5**

🟢 **Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17				7.29			9.71**

🟢 **Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17				6.07			10.93**

🟢 **Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17				4.86			12.14**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17				3.64			13.36**

🟢 **Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17				2.43			14.57**

🟢 **Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17				1.21			15.79**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17				0			17**

🟢 **Hiện tại	17		6	11				**

🟢 **					Tổng giờ theo task			108	0																				**

🟢 **					Chênh kế hoạch task − kế hoạch ngày: -42 h. 																								**

🟢 **Hiện tại: 0/38 task Done · còn 38 task · 0 Done thiếu ngày								**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38			0**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29			2.71**

🟢 **Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57			5.43**

🟢 **Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86			8.14**

🟢 **Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14			10.86**

🟢 **Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43			13.57**

🟢 **Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71			16.29**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19			19**

🟢 **Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29			21.71**

🟢 **Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57			24.43**

🟢 **Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86			27.14**

🟢 **Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14			29.86**

🟢 **Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43			32.57**

🟢 **Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71			35.29**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0			38**

🟢 **Hiện tại	38		0	38				**

🟢 **					Tổng giờ theo task			150	0																				**

🟢 **Hiện tại: 0/36 task Done · còn 36 task · 0 Done thiếu ngày								**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			0**

🟢 **Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				32.4			3.6**

🟢 **Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.8			7.2**

🟢 **Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.2			10.8**

🟢 **Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				21.6			14.4**

🟢 **Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18**

🟢 **Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18**

🟢 **Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			18**

🟢 **Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				14.4			21.6**

🟢 **Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.8			25.2**

🟢 **Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.2			28.8**

🟢 **Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				3.6			32.4**

🟢 **Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36**

🟢 **Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36**

🟢 **Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			36**

🟢 **Hiện tại	36		0	36				**

~~					Tổng giờ các task			146	163																								~~

~~					Giờ dự kiến theo ngày (cả nhóm)				146							4	4			13	15	15	15	13			13	15	15	13	11		~~

~~					Giờ thực tế theo ngày (tự tính)				157							6	7	1	0	14	12	15	11	14	0	0	15	15	13	15	16	3	0~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ~~

~~Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42				42			09/09~~

~~Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			39.67	6	6	10/09~~

~~Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			37.33	7	13	11/09~~

~~Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			35	1	14	12/09~~

~~Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			32.67		14	13/09~~

~~Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			30.33	14	28	14/09~~

~~Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			28	12	40	15/09~~

~~Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			25.67	15	55	16/09~~

~~Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			23.33	11	66	17/09~~

~~Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			21	14	80	18/09~~

~~Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			18.67		80	19/09~~

~~Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			16.33		80	20/09~~

~~Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			14	15	95	21/09~~

~~Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			11.67	15	110	22/09~~

~~Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			9.33	13	123	23/09~~

~~Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			7	15	138	24/09~~

~~Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			4.67	16	154	25/09~~

~~Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			2.33	3	157	26/09~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			0		157	27/09~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		42	0				Hiện tại~~

~~					Tổng giờ các task			141	122																				~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ thực tế theo ngày (tự tính)				122							7	12	13	13	11	6	0	12	13	13	11	11	0	0~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28				28			27/09~~

~~Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			26	7	7	28/09~~

~~Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			24	12	19	29/09~~

~~Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			22	13	32	30/09~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			20	13	45	01/10~~

~~Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			18	11	56	02/10~~

~~Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			16	6	62	03/10~~

~~Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			14		62	04/10~~

~~Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			12	12	74	05/10~~

~~Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			10	13	87	06/10~~

~~Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			8	13	100	07/10~~

~~Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			6	11	111	08/10~~

~~Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			4	11	122	09/10~~

~~Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			2		122	10/10~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			0		122	11/10~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	28		28	0				Hiện tại~~

~~					Tổng giờ các task			150	52																				~~

~~					Giờ thực tế theo ngày (tự tính)				46							5	9	6	3	3	1	0	7	3	3	3	3	0	0~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			11/10~~

~~Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			33.43	5	5	12/10~~

~~Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			30.86	9	14	13/10~~

~~Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			28.29	6	20	14/10~~

~~Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			25.71	3	23	15/10~~

~~Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			23.14	3	26	16/10~~

~~Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			20.57	1	27	17/10~~

~~Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			18		27	18/10~~

~~Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			15.43	7	34	19/10~~

~~Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			12.86	3	37	20/10~~

~~Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			10.29	3	40	21/10~~

~~Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			7.71	3	43	22/10~~

~~Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			5.14	3	46	23/10~~

~~Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			2.57		46	24/10~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			0		46	25/10~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	36		29	7				Hiện tại~~

~~					Tổng giờ các task			128	0																				~~

~~					Giờ thực tế theo ngày (tự tính)				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0~~

~~					Giờ thực tế theo ngày (tự tính)				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0~~

~~					Giờ thực tế theo ngày (tự tính)				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17				17			25/10~~

~~Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			15.79			26/10~~

~~Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			14.57			27/10~~

~~Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			13.36			28/10~~

~~Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			12.14			29/10~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			10.93			30/10~~

~~Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			9.71			31/10~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			8.5			01/11~~

~~Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			7.29			02/11~~

~~Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			6.07			03/11~~

~~Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			4.86			04/11~~

~~Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			3.64			05/11~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			2.43			06/11~~

~~Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			1.21			07/11~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			0			08/11~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	17		6	11				Hiện tại~~

~~					Tổng giờ các task			108	0																				~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38			08/11~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29			09/11~~

~~Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57			10/11~~

~~Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86			11/11~~

~~Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14			12/11~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43			13/11~~

~~Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71			14/11~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19			15/11~~

~~Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29			16/11~~

~~Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57			17/11~~

~~Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86			18/11~~

~~Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14			19/11~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43			20/11~~

~~Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71			21/11~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0			22/11~~

~~					Tổng giờ các task			150	0																				~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			22/11~~

~~Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				33.43			23/11~~

~~Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				30.86			24/11~~

~~Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.29			25/11~~

~~Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.71			26/11~~

~~Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				23.14			27/11~~

~~Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				20.57			28/11~~

~~Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			29/11~~

~~Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				15.43			30/11~~

~~Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				12.86			01/12~~

~~Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.29			02/12~~

~~Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.71			03/12~~

~~Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				5.14			04/12~~

~~Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				2.57			05/12~~

~~Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			06/12~~

## 2026-11-09 15:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **Sprint 1 Report								**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.								**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.								**

🟢 **Phạm vi (task)	42	Done hiện tại	42	Giờ dự kiến	146	Done thiếu ngày	42	**

🟢 **Giờ thực tế	163	Bắt đầu	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	**

🟢 **Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.								**

🟢 **Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.								**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.								**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế	Mốc biểu đồ**

🟢 **Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42				42			09/09**

🟢 **Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			39.67	6	6	10/09**

🟢 **Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			37.33	7	13	11/09**

🟢 **Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			35	1	14	12/09**

🟢 **Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			32.67		14	13/09**

🟢 **Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			30.33	14	28	14/09**

🟢 **Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			28	12	40	15/09**

🟢 **Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			25.67	15	55	16/09**

🟢 **Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			23.33	11	66	17/09**

🟢 **Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			21	14	80	18/09**

🟢 **Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			18.67		80	19/09**

🟢 **Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			16.33		80	20/09**

🟢 **Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			14	15	95	21/09**

🟢 **Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			11.67	15	110	22/09**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			9.33	13	123	23/09**

🟢 **Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			7	15	138	24/09**

🟢 **Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			4.67	16	154	25/09**

🟢 **Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			2.33	3	157	26/09**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			0		157	27/09**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		42	0				Hiện tại**

🟢 **Sprint 2 Report								**

🟢 **Phạm vi (task)	28	Done hiện tại	28	Giờ dự kiến	141	Done thiếu ngày	28	**

🟢 **Giờ thực tế	122	Bắt đầu	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28				28			27/09**

🟢 **Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			26	7	7	28/09**

🟢 **Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			24	12	19	29/09**

🟢 **Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			22	13	32	30/09**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			20	13	45	01/10**

🟢 **Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			18	11	56	02/10**

🟢 **Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			16	6	62	03/10**

🟢 **Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			14		62	04/10**

🟢 **Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			12	12	74	05/10**

🟢 **Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			10	13	87	06/10**

🟢 **Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			8	13	100	07/10**

🟢 **Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			6	11	111	08/10**

🟢 **Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			4	11	122	09/10**

🟢 **Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			2		122	10/10**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			0		122	11/10**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	28		28	0				Hiện tại**

🟢 **Sprint 3 Report								**

🟢 **Phạm vi (task)	36	Done hiện tại	29	Giờ dự kiến	150	Done thiếu ngày	29	**

🟢 **Giờ thực tế	52	Bắt đầu	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			11/10**

🟢 **Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			33.43	5	5	12/10**

🟢 **Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			30.86	9	14	13/10**

🟢 **Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			28.29	6	20	14/10**

🟢 **Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			25.71	3	23	15/10**

🟢 **Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			23.14	3	26	16/10**

🟢 **Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			20.57	1	27	17/10**

🟢 **Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			18		27	18/10**

🟢 **Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			15.43	7	34	19/10**

🟢 **Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			12.86	3	37	20/10**

🟢 **Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			10.29	3	40	21/10**

🟢 **Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			7.71	3	43	22/10**

🟢 **Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			5.14	3	46	23/10**

🟢 **Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			2.57		46	24/10**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			0		46	25/10**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	36		29	7				Hiện tại**

🟢 **Sprint 4 Report								**

🟢 **Phạm vi (task)	17	Done hiện tại	6	Giờ dự kiến	128	Done thiếu ngày	6	**

🟢 **Giờ thực tế		Bắt đầu	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17				17			25/10**

🟢 **Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			15.79			26/10**

🟢 **Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			14.57			27/10**

🟢 **Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			13.36			28/10**

🟢 **Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			12.14			29/10**

🟢 **Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			10.93			30/10**

🟢 **Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			9.71			31/10**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			8.5			01/11**

🟢 **Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			7.29			02/11**

🟢 **Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			6.07			03/11**

🟢 **Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			4.86			04/11**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			3.64			05/11**

🟢 **Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			2.43			06/11**

🟢 **Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			1.21			07/11**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			0			08/11**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	17		6	11				Hiện tại**

🟢 **Sprint 5 Report								**

🟢 **Phạm vi (task)	38	Done hiện tại	0	Giờ dự kiến	108	Done thiếu ngày	0	**

🟢 **Giờ thực tế		Bắt đầu	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38			08/11**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29			09/11**

🟢 **Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57			10/11**

🟢 **Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86			11/11**

🟢 **Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14			12/11**

🟢 **Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43			13/11**

🟢 **Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71			14/11**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19			15/11**

🟢 **Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29			16/11**

🟢 **Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57			17/11**

🟢 **Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86			18/11**

🟢 **Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14			19/11**

🟢 **Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43			20/11**

🟢 **Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71			21/11**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0			22/11**

🟢 **Sprint 6 Report								**

🟢 **Phạm vi (task)	36	Done hiện tại	0	Giờ dự kiến	150	Done thiếu ngày	0	**

🟢 **Giờ thực tế		Bắt đầu	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0	**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36			22/11**

🟢 **Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				33.43			23/11**

🟢 **Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				30.86			24/11**

🟢 **Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.29			25/11**

🟢 **Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.71			26/11**

🟢 **Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				23.14			27/11**

🟢 **Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				20.57			28/11**

🟢 **Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18			29/11**

🟢 **Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				15.43			30/11**

🟢 **Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				12.86			01/12**

🟢 **Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.29			02/12**

🟢 **Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.71			03/12**

🟢 **Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				5.14			04/12**

🟢 **Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				2.57			05/12**

🟢 **Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0			06/12**

~~Sprint 1 Report							~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							~~

~~Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							~~

~~Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							~~

~~Phạm vi (task)	42	Done hiện tại	42	Giờ dự kiến	146	Done thiếu ngày	42~~

~~Giờ thực tế	163	Bắt đầu	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0~~

~~Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.							~~

~~Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.							~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							~~

~~Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42				42		~~

~~Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			39.67	6	6~~

~~Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			37.33	7	13~~

~~Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			35	1	14~~

~~Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			32.67		14~~

~~Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			30.33	14	28~~

~~Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			28	12	40~~

~~Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			25.67	15	55~~

~~Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			23.33	11	66~~

~~Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			21	14	80~~

~~Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			18.67		80~~

~~Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			16.33		80~~

~~Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			14	15	95~~

~~Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			11.67	15	110~~

~~Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			9.33	13	123~~

~~Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			7	15	138~~

~~Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			4.67	16	154~~

~~Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			2.33	3	157~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			0		157~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		42	0			~~

~~Sprint 2 Report							~~

~~Phạm vi (task)	28	Done hiện tại	28	Giờ dự kiến	141	Done thiếu ngày	28~~

~~Giờ thực tế	122	Bắt đầu	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28				28		~~

~~Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			26	7	7~~

~~Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			24	12	19~~

~~Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			22	13	32~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			20	13	45~~

~~Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			18	11	56~~

~~Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			16	6	62~~

~~Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			14		62~~

~~Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			12	12	74~~

~~Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			10	13	87~~

~~Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			8	13	100~~

~~Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			6	11	111~~

~~Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			4	11	122~~

~~Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			2		122~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			0		122~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	28		28	0			~~

~~Sprint 3 Report							~~

~~Phạm vi (task)	36	Done hiện tại	29	Giờ dự kiến	150	Done thiếu ngày	29~~

~~Giờ thực tế	52	Bắt đầu	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36				36		~~

~~Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			33.43	5	5~~

~~Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			30.86	9	14~~

~~Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			28.29	6	20~~

~~Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			25.71	3	23~~

~~Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			23.14	3	26~~

~~Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			20.57	1	27~~

~~Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			18		27~~

~~Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			15.43	7	34~~

~~Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			12.86	3	37~~

~~Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			10.29	3	40~~

~~Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			7.71	3	43~~

~~Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			5.14	3	46~~

~~Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			2.57		46~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			0		46~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	36		29	7			~~

~~Sprint 4 Report							~~

~~Phạm vi (task)	17	Done hiện tại	6	Giờ dự kiến	128	Done thiếu ngày	6~~

~~Giờ thực tế		Bắt đầu	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17				17		~~

~~Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			15.79		~~

~~Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			14.57		~~

~~Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			13.36		~~

~~Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			12.14		~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			10.93		~~

~~Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			9.71		~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			8.5		~~

~~Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			7.29		~~

~~Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			6.07		~~

~~Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			4.86		~~

~~Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			3.64		~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			2.43		~~

~~Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			1.21		~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			0		~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	17		6	11			~~

~~Sprint 5 Report							~~

~~Phạm vi (task)	38	Done hiện tại	0	Giờ dự kiến	108	Done thiếu ngày	0~~

~~Giờ thực tế		Bắt đầu	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38		~~

~~Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29		~~

~~Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57		~~

~~Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86		~~

~~Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14		~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43		~~

~~Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71		~~

~~Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19		~~

~~Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29		~~

~~Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57		~~

~~Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86		~~

~~Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14		~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43		~~

~~Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71		~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0		~~

~~Sprint 6 Report							~~

~~Phạm vi (task)	36	Done hiện tại	0	Giờ dự kiến	150	Done thiếu ngày	0~~

~~Giờ thực tế		Bắt đầu	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0~~

~~Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36		~~

~~Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				33.43		~~

~~Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				30.86		~~

~~Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.29		~~

~~Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.71		~~

~~Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				23.14		~~

~~Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				20.57		~~

~~Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18		~~

~~Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				15.43		~~

~~Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				12.86		~~

~~Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.29		~~

~~Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.71		~~

~~Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				5.14		~~

~~Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				2.57		~~

~~Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0		~~

## 2026-11-09 15:23 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:23

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							**

🟢 **Burnup và Burndown dùng số task. Mốc hôm nay lấy trực tiếp trạng thái hiện tại từ backlog.							**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							**

🟢 **Điền Ngày hoàn thành thực tế trong backlog để dựng đường lịch sử. Nếu còn Done thiếu ngày, report hiện mốc hiện tại và để trống các điểm lịch sử chưa đủ dữ liệu.							**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							**

🟢 **Mốc đầu là ngày trước sprint. Điểm sau ngày kết thúc là trạng thái quan sát hôm nay nếu còn task Done thiếu ngày hoặc có task hoàn thành muộn.							**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong theo ngày có ghi	Xong lũy kế thực tế	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42				42		**

🟢 **Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			39.67	6	6**

🟢 **Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			37.33	7	13**

🟢 **Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			35	1	14**

🟢 **Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			32.67		14**

🟢 **Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			30.33	14	28**

🟢 **Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			28	12	40**

🟢 **Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			25.67	15	55**

🟢 **Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			23.33	11	66**

🟢 **Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			21	14	80**

🟢 **Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			18.67		80**

🟢 **Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			16.33		80**

🟢 **Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			14	15	95**

🟢 **Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			11.67	15	110**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			9.33	13	123**

🟢 **Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			7	15	138**

🟢 **Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			4.67	16	154**

🟢 **Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			2.33	3	157**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	0			0		157**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		42	0			**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28				28		**

🟢 **Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			26	7	7**

🟢 **Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			24	12	19**

🟢 **Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			22	13	32**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			20	13	45**

🟢 **Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			18	11	56**

🟢 **Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			16	6	62**

🟢 **Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			14		62**

🟢 **Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			12	12	74**

🟢 **Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			10	13	87**

🟢 **Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			8	13	100**

🟢 **Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			6	11	111**

🟢 **Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			4	11	122**

🟢 **Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			2		122**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0			0		122**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	28		28	0			**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36				36		**

🟢 **Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			33.43	5	5**

🟢 **Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			30.86	9	14**

🟢 **Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			28.29	6	20**

🟢 **Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			25.71	3	23**

🟢 **Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			23.14	3	26**

🟢 **Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			20.57	1	27**

🟢 **Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			18		27**

🟢 **Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			15.43	7	34**

🟢 **Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			12.86	3	37**

🟢 **Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			10.29	3	40**

🟢 **Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			7.71	3	43**

🟢 **Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			5.14	3	46**

🟢 **Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			2.57		46**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0			0		46**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	36		29	7			**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17				17		**

🟢 **Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			15.79		**

🟢 **Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			14.57		**

🟢 **Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			13.36		**

🟢 **Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			12.14		**

🟢 **Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			10.93		**

🟢 **Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			9.71		**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			8.5		**

🟢 **Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			7.29		**

🟢 **Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			6.07		**

🟢 **Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			4.86		**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			3.64		**

🟢 **Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			2.43		**

🟢 **Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			1.21		**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0			0		**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	17		6	11			**

~~Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							~~

~~Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							~~

~~Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							~~

~~Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							~~

~~Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							~~

~~Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							~~

~~Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							~~

~~Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							~~

~~Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							~~

~~Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							~~

~~Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							~~

~~Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							~~

~~Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							~~

~~Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							~~

~~Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							~~

~~Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							~~

~~Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							~~

~~Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							~~

~~Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế~~

~~Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		0		42		~~

~~Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		39.67	6	6~~

~~Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		37.33	7	13~~

~~Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		35	1	14~~

~~Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		32.67		14~~

~~Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		30.33	14	28~~

~~Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		28	12	40~~

~~Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		25.67	15	55~~

~~Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		23.33	11	66~~

~~Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		21	14	80~~

~~Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		18.67		80~~

~~Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		16.33		80~~

~~Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		14	15	95~~

~~Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		11.67	15	110~~

~~Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		9.33	13	123~~

~~Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		7	15	138~~

~~Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		4.67	16	154~~

~~Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		2.33	3	157~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		0		157~~

~~Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28		0		28		~~

~~Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		26	7	7~~

~~Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		24	12	19~~

~~Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		22	13	32~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		20	13	45~~

~~Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		18	11	56~~

~~Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		16	6	62~~

~~Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		14		62~~

~~Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		12	12	74~~

~~Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		10	13	87~~

~~Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		8	13	100~~

~~Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		6	11	111~~

~~Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		4	11	122~~

~~Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		2		122~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		0		122~~

~~Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36		0		36		~~

~~Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		33.43	5	5~~

~~Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		30.86	9	14~~

~~Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		28.29	6	20~~

~~Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		25.71	3	23~~

~~Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		23.14	3	26~~

~~Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		20.57	1	27~~

~~Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		18		27~~

~~Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		15.43	7	34~~

~~Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		12.86	3	37~~

~~Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		10.29	3	40~~

~~Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		7.71	3	43~~

~~Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		5.14	3	46~~

~~Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		2.57		46~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		0		46~~

~~Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17		0		17		~~

~~Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		15.79		~~

~~Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		14.57		~~

~~Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		13.36		~~

~~Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		12.14		~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		10.93		~~

~~Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		9.71		~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		8.5		~~

~~Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		7.29		~~

~~Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		6.07		~~

~~Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		4.86		~~

~~Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		3.64		~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		2.43		~~

~~Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		1.21		~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		0		~~

## 2026-11-09 15:12 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-09 15:07 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 15:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **---**

🟢 **---**

🟢 **---**

🟢 **---**

🟢 **---**

🟢 **	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																																**

🟢 **	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																																**

🟢 **	Giữ nguyên 42 task, trạng thái, người phụ trách và giờ đã nhập. Trước 14/09 được ghi là Khởi động.																																**

🟢 **	FinMind Sprint 1 Backlog																																**

🟢 **	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	163																											**

🟢 **	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Ngày hoàn thành thực tế	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **	Sprint 1	S1-T01	M01	Khởi động	Xác định các nhóm người dùng chính	Thái Quốc Hưng	Đã hoàn thành	1	1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định nhà đầu tư, chuyên viên phân tích và quản trị dữ liệu cùng nhu cầu chính của từng nhóm.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.		1																	**

🟢 **	Sprint 1	S1-T02	M01	Khởi động	Chốt phạm vi và giới hạn của bản MVP	Thái Quốc Hưng	Đã hoàn thành	3	4	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định chức năng thuộc MVP, phần mở rộng và các nội dung nằm ngoài phạm vi dự án.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.		2	1					1											**

🟢 **	Sprint 1	S1-T03	M01	Khởi động	Lập danh sách chức năng theo thứ tự ưu tiên	Thái Quốc Hưng	Đã hoàn thành	4	7	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Phân loại chức năng bắt buộc, nên có và có thể thực hiện ở giai đoạn sau.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.			3	1				2	1										**

🟢 **	Sprint 1	S1-T04	M01	Khởi động	Soạn bộ câu hỏi nghiên cứu và khảo sát	Trần Diệu Huyền	Đã hoàn thành	2	3	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.		3																	**

🟢 **	Sprint 1	S1-T05	M01	1	Thực hiện nghiên cứu và tổng hợp kết quả	Thái Quốc Hưng	Đã hoàn thành	4	4	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Thực hiện khảo sát hoặc phỏng vấn và tổng hợp các phát hiện quan trọng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.						3	1												**

🟢 **	Sprint 1	S1-T06	M01	1	Kiểm tra lại phạm vi và thống nhất	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.			3			3													**

🟢 **	Sprint 1	S1-T07	M02	1	Lập danh sách nguồn dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.							3												**

🟢 **	Sprint 1	S1-T08	M02	1	Tìm nguồn chính thức cho 5 công ty Ngân hàng	Nguyễn Minh Quân	Đã hoàn thành	3	2	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tìm trang quan hệ cổ đông, báo cáo tài chính và công bố thông tin chính thức.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.						2													**

🟢 **	Sprint 1	S1-T09	M02	1	Tìm nguồn chính thức cho 5 công ty Công nghệ	Nguyễn Minh Quân	Đã hoàn thành	3	2	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tìm trang quan hệ cổ đông, báo cáo tài chính và công bố thông tin chính thức.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.							2												**

🟢 **	Sprint 1	S1-T10	M02	1	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.								3											**

🟢 **	Sprint 1	S1-T11	M02	1	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Trần Diệu Huyền	Đã hoàn thành	4	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.									3										**

🟢 **	Sprint 1	S1-T12	M02	1	Xác định nguồn dự phòng và đánh giá tính khả thi	Trần Diệu Huyền	Đã hoàn thành	3	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.										3									**

🟢 **	Sprint 1	S1-T13	M03	1	Rà soát SRS và danh mục use case	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	Có bảng đối chiếu UC–FR/NFR đã rà.	Giữ kế hoạch Sprint 1 đã nhập.													3	3					**

🟢 **	Sprint 1	S1-T14	M03	1	Vẽ context và business function diagram	Đinh Huỳnh Vũ	Đã hoàn thành	5	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thể hiện tác nhân, hệ thống ngoài và phân rã chức năng; đối chiếu nội dung với SRS.	Có context và business function diagram khớp SRS.	Giữ kế hoạch Sprint 1 đã nhập.																			**

🟢 **	Sprint 1	S1-T15	M03	1	Vẽ activity diagram theo use case	Thái Quốc Hưng	Đã hoàn thành	8	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Mô tả luồng chính, nhánh thay thế và ngoại lệ; kiểm tra node bắt đầu/kết thúc và lưu hình cùng draw.io.	Có activity diagrams và file chỉnh sửa được.	Giữ kế hoạch Sprint 1 đã nhập.										2			3	1					**

🟢 **	Sprint 1	S1-T16	M03	1	Vẽ sequence diagram theo use case	Đinh Huỳnh Vũ	Đã hoàn thành	8	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thể hiện actor, giao diện, dịch vụ và kho dữ liệu; thông điệp phải khớp kịch bản của từng use case.	Có sequence diagrams theo use case.	Giữ kế hoạch Sprint 1 đã nhập.						3	3												**

🟢 **	Sprint 1	S1-T17	M03	1	Vẽ state diagram cho đối tượng có vòng đời	Thái Quốc Hưng	Đã hoàn thành	6	5	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Gom các use case liên quan; xác định trạng thái, sự kiện, điều kiện chuyển và điểm kết thúc.	Có state diagrams cho vòng đời cần mô tả.	Giữ kế hoạch Sprint 1 đã nhập.														2	3				**

🟢 **	Sprint 1	S1-T18	M03	1	Rà soát tính nhất quán SRS	Trần Diệu Huyền	Đã hoàn thành	4	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS có đúng hình, số mục và mã tham chiếu.	Giữ kế hoạch Sprint 1 đã nhập.															3				**

🟢 **	Sprint 1	S1-T19	M04	1	Chia pipeline dữ liệu thành các phần nhỏ	Nguyễn Minh Quân	Đã hoàn thành	4	5	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tách thu thập, chuẩn hóa, chunk/embedding, graph, truy vấn vector/graph và ranh giới đầu vào/đầu ra.	Có bản đồ các bước xử lý dữ liệu và đầu vào/đầu ra.	Giữ kế hoạch Sprint 1 đã nhập.								3	2										**

🟢 **	Sprint 1	S1-T20	M04	1	Đặc tả nguồn và cách cào dữ liệu mẫu	Nguyễn Minh Quân	Đã hoàn thành	2	2	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chọn nguồn được phép dùng; ghi URL, loại tài liệu, lịch lấy, phiên bản và điều kiện truy cập.	Có danh sách nguồn được phép dùng và cách lấy.	Giữ kế hoạch Sprint 1 đã nhập.									1	1									**

🟢 **	Sprint 1	S1-T21	M04	1	Đặc tả chuẩn hóa và định danh dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Giữ kế hoạch Sprint 1 đã nhập.																3			**

🟢 **	Sprint 1	S1-T22	M04	2	Vẽ ERD dữ liệu nghiệp vụ PostgreSQL	Nguyễn Minh Quân	Đã hoàn thành	4	4	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thiết kế công ty, tài liệu, nguồn, dữ kiện tài chính, khóa chính/ngoại và quan hệ truy vết.	Có ERD PostgreSQL cho dữ liệu nghiệp vụ.	Giữ kế hoạch Sprint 1 đã nhập.										2			2						**

🟢 **	Sprint 1	S1-T23	M04	2	Vẽ lược đồ bảng chunk/embedding pgvector	Đinh Huỳnh Vũ	Đã hoàn thành	3	4	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định chunk, embedding, vector dimension, metadata, source locator và liên kết với PostgreSQL.	Có lược đồ chunk/embedding của pgvector.	Giữ kế hoạch Sprint 1 đã nhập.								3	1										**

🟢 **	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.						3	1			2									**

🟢 **	Sprint 1	S1-T25	M04	2	Đối chiếu ID giữa các mô hình dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có quy tắc ánh xạ ID giữa các mô hình.	Giữ kế hoạch Sprint 1 đã nhập.																	3		**

🟢 **	Sprint 1	S1-T26	M05	2	Cào bộ tài liệu mẫu theo nguồn đã chọn	Nguyễn Minh Quân	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy PoC trên vài tài liệu trong phạm vi corpus; lưu tệp gốc và nhật ký URL/thời điểm.	Có bộ tài liệu mẫu và nhật ký lấy dữ liệu.	Giữ kế hoạch Sprint 1 đã nhập.													1	2					**

🟢 **	Sprint 1	S1-T27	M05	2	Ghi hash, phiên bản và metadata nguồn	Nguyễn Minh Quân	Đã hoàn thành	2	2	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Lưu checksum, ngày công bố, công ty, kỳ báo cáo và trạng thái trùng lặp của tài liệu mẫu.	Có checksum, phiên bản, metadata của mẫu.	Giữ kế hoạch Sprint 1 đã nhập.														1	1				**

🟢 **	Sprint 1	S1-T28	M05	2	Parse và chuẩn hóa tài liệu mẫu	Đinh Huỳnh Vũ	Đã hoàn thành	3	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Trích văn bản/bảng, chuẩn hóa ticker, kỳ, đơn vị và đánh dấu bản ghi lỗi để không đưa vào index.	Có dữ liệu mẫu chuẩn hóa, lỗi được cách ly.	Giữ kế hoạch Sprint 1 đã nhập.										3			3						**

🟢 **	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6	8	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.								3	3	1					1				**

🟢 **	Sprint 1	S1-T30	M05	2	Tạo embedding và nạp mẫu vào pgvector	Đinh Huỳnh Vũ	Đã hoàn thành	3	4	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vector hóa chunk hợp lệ; ghi model/version, dimension và khóa liên kết về tài liệu gốc.	Có embedding mẫu trong pgvector.	Giữ kế hoạch Sprint 1 đã nhập.														3	1				**

🟢 **	Sprint 1	S1-T31	M05	2	Truy vấn pgvector để kiểm thử	Đinh Huỳnh Vũ	Đã hoàn thành	3	6	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng câu hỏi mẫu để kiểm tra top-k, khoảng cách vector và khả năng truy về đúng đoạn nguồn.	Có kết quả tìm vector theo câu hỏi mẫu.	Giữ kế hoạch Sprint 1 đã nhập.																3	3		**

🟢 **	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.							2												**

🟢 **	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	5	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.													2		2	1			**

🟢 **	Sprint 1	S1-T34	M06	2	Nạp node và edge mẫu vào Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Có graph mẫu trong Neo4j.	Giữ kế hoạch Sprint 1 đã nhập.													1			2			**

🟢 **	Sprint 1	S1-T35	M06	2	Truy vấn Neo4j để kiểm thử	Hồ Phạm Đăng Nhân	Đã hoàn thành	3	3	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Có kết quả truy vấn graph kèm nguồn.	Giữ kế hoạch Sprint 1 đã nhập.														3					**

🟢 **	Sprint 1	S1-T36	M06	2	Truy vấn dữ kiện PostgreSQL để đối chiếu	Nguyễn Minh Quân	Đã hoàn thành	3	2	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy số liệu mẫu theo công ty, chỉ số, kỳ và đơn vị; so với bản ghi nguồn đã chuẩn hóa.	Có kết quả số liệu PostgreSQL để đối chiếu.	Giữ kế hoạch Sprint 1 đã nhập.															2				**

🟢 **	Sprint 1	S1-T37	M06	2	Tổng hợp kết quả cào và cập nhật SRS	Nguyễn Minh Quân	Đã hoàn thành	2	1	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Ghi truy vấn, kết quả đúng/sai, lỗi và giới hạn; sửa lược đồ/đặc tả nếu bằng chứng thử nghiệm yêu cầu.	Có báo cáo PoC và các điểm cần sửa trong SRS.	Giữ kế hoạch Sprint 1 đã nhập.																1			**

🟢 **	Sprint 1	S1-T38	M04	2	Tạo Git repository và cấu trúc dự án ban đầu	Nguyễn Minh Quân	Đã hoàn thành	1	1	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo kho mã nguồn Git và các thư mục ban đầu để cả nhóm lưu, chia sẻ và quản lý phiên bản mã.	Repository truy cập được; cấu trúc thư mục và hướng dẫn khởi động được lưu.	Giữ kế hoạch Sprint 1 đã nhập.																1			**

🟢 **	Sprint 1	S1-T39	M03	1	Chuẩn bị Golden Test Set phiên bản đầu tiên	Thái Quốc Hưng	Đã hoàn thành	4	4	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Soạn bộ câu hỏi kiểm thử ban đầu, đáp án tham chiếu và thông tin nguồn để kiểm tra kết quả trả lời.	Có danh sách câu hỏi, đáp án và nguồn đối chiếu; chưa coi đây là bộ test cuối đã khóa.	Giữ kế hoạch Sprint 1 đã nhập.																3	1		**

🟢 **	Sprint 1	S1-T40	M03	2	Vẽ usecase diagram cho từng đặc tả use case	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case riêng cho từng đặc tả, thể hiện người sử dụng và chức năng liên quan.	Các sơ đồ khớp actor, tên chức năng và mã use case trong SRS.	File gốc có công thức cộng giờ các task khác trong dòng này. Cần kiểm tra để tránh tính trùng.																	3	3	**

🟢 **	Sprint 1	S1-T41	M03	2	Vẽ usecase Diagram tổng	Trần Diệu Huyền	Đã hoàn thành	5	3	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Giữ kế hoạch Sprint 1 đã nhập.																	3		**

🟢 **	Sprint 1	S1-T42	M05	2	Xây dựng module chuẩn hóa dữ liệu & khử lỗi	Nguyễn Minh Quân	Đã hoàn thành	4	4	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xây dựng phần xử lý dữ liệu mẫu để thống nhất định dạng và xử lý giá trị số không hợp lệ.	Có module, dữ liệu trước/sau xử lý và kết quả kiểm thử các trường hợp số không hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.																1	3		**

🟢 **					Tổng giờ các task			146	163																								**

🟢 **					Giờ dự kiến theo ngày (cả nhóm)				146							4	4			13	15	15	15	13			13	15	15	13	11		**

🟢 **					Giờ thực tế theo ngày (tự tính)				157							6	7	1	0	14	12	15	11	14	0	0	15	15	13	15	16	3	0**

🟢 **Sprint 1 Report**

🟢 **Sprint 1 Report							**

🟢 **Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							**

🟢 **Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							**

🟢 **Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							**

🟢 **Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							**

🟢 **Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							**

🟢 **Burnup tăng theo số task hoàn thành có ngày. Burndown giảm theo số task còn lại. Hai biểu đồ dùng số task.							**

🟢 **Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							**

🟢 **Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							**

🟢 **Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							**

🟢 **Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							**

🟢 **Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							**

🟢 **Trong backlog, chọn Đã hoàn thành và nhập Ngày hoàn thành thực tế. Task thiếu ngày vẫn được đếm ở ô Done nhưng chưa vào đường Burnup.							**

🟢 **Phạm vi (task)	42	Done hiện tại	42	Giờ dự kiến	146	Done thiếu ngày	42**

🟢 **Giờ thực tế	163	Bắt đầu	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0**

🟢 **Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.							**

🟢 **Chênh lệch giữa giờ thực tế trên backlog và giờ đã phân theo ngày đến hôm nay: 6h.							**

🟢 **Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							**

🟢 **Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							**

🟢 **Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							**

🟢 **Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							**

🟢 **Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							**

🟢 **Mốc đầu là ngày trước sprint. Phạm vi lấy từ backlog hiện tại. Khi còn task Done thiếu ngày, đường Burndown thực tế để trống.							**

🟢 **Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Ngày	Phạm vi (task)	Xong trong ngày	Xong lũy kế có ngày	Còn lại thực tế	Còn lại lý tưởng	Giờ thực tế/ngày	Giờ thực tế lũy kế**

🟢 **Wed Sep 09 2026 07:00:00 GMT+0700 (Indochina Time)	42		0		42		**

🟢 **Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		39.67	6	6**

🟢 **Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		37.33	7	13**

🟢 **Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		35	1	14**

🟢 **Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		32.67		14**

🟢 **Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		30.33	14	28**

🟢 **Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		28	12	40**

🟢 **Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		25.67	15	55**

🟢 **Thu Sep 17 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		23.33	11	66**

🟢 **Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		21	14	80**

🟢 **Sat Sep 19 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		18.67		80**

🟢 **Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		16.33		80**

🟢 **Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		14	15	95**

🟢 **Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		11.67	15	110**

🟢 **Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		9.33	13	123**

🟢 **Thu Sep 24 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		7	15	138**

🟢 **Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		4.67	16	154**

🟢 **Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		2.33	3	157**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	42	0	0		0		157**

🟢 **	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																												**

🟢 **	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																												**

🟢 **	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																												**

🟢 **	Sprint 2 có hai đầu ra UI riêng: file thiết kế chỉnh sửa được và frontend source chạy với mock. Huyền lead UI, thiết kế luồng/visual và review; Nhân thiết kế wireframe, bàn giao hai mốc có duyệt để Vũ làm prototype song song. Giờ review ở WBS24 và WBS32, không cộng hai lần. Chỉ đánh dấu task hoàn thành khi đủ toàn bộ đầu ra; mốc trung gian không phải hoàn thành task.																												**

🟢 **Hưng/Quân: cào, chuẩn hóa, PostgreSQL. Vũ/Nhân/Huyền: thiết kế, prototype, code mock. Giờ thực tế chỉ nhập khi đã làm.																												**

🟢 **	FinMind Sprint 2 Backlog																												**

🟢 **	Số task	28	Giờ dự kiến	141	Tổng giờ thực tế đã ghi	122																							**

🟢 **	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Ngày hoàn thành thực tế	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 03 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **	Sprint 2	S2-WBS01	S2-G01	1	Chốt hợp đồng dữ liệu đầu vào/đầu ra	Nguyễn Minh Quân	Đã hoàn thành	3	4	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Rà soát giá, tỷ số, KQKD, CĐKT, LCTT; chốt schema raw/normalized; phân biệt quý/năm.	Có schema thống nhất raw/normalized; JSON UTF-8 hợp lệ; xử lý an toàn NaN/null.	ERD Sprint 1; mẫu payload API; danh sách 10 mã.		1	3												**

🟢 **Kết quả cần có: Có mẫu bản ghi và trường bắt buộc; phân biệt 0 với thiếu dữ liệu. UI và người làm DB dùng cùng tên trường.	Thái Quốc Hưng	Đã hoàn thành	2	1	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng ERD Sprint 1 để chốt company\_id, loại nguồn, URL, ngày công bố/lấy, hash, phiên bản, kỳ, đơn vị và vị trí nguồn. Thống nhất mẫu facts và News với UI; không vẽ lại ERD từ đầu.	Có mẫu bản ghi và trường bắt buộc; phân biệt 0 với thiếu dữ li...**

🟢 **	Sprint 2	S2-WBS03	S2-G02	1	Làm ổn định bộ thu thập dữ liệu (Collector)	Nguyễn Minh Quân	Đã hoàn thành	5	6	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy collector cào 10 mã (5 Bank + 5 Tech); bổ sung retry, timeout, cô lập lỗi từng mã để không dừng pipeline	Collector chạy ổn định 10 mã; log lỗi độc lập; có CLI chạy lại từng mã.	Schema raw; endpoint API; danh sách 10 mã (5 Bank + 5 Tech).				4	2										**

🟢 **Kết quả cần có: Lấy đúng bài mẫu và nguồn gốc; có retry/log và lý do loại bài. Bộ cào chỉ hỗ trợ danh sách nguồn đã chốt.	Thái Quốc Hưng	Đã hoàn thành	5	7	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tái dùng khung crawler chung, cấu hình các nguồn News được duyệt. Lấy danh sách/nội dung trong khoảng ngày, xử lý phân trang, lọc công ty và lưu URL/ngày/hash/version. Không làm crawler tổng quát cho mọi website hoặc vượt paywall.	Lấy đúng bài...**

🟢 **	Sprint 2	S2-WBS05	S2-G02	1	Chuẩn hóa dữ liệu số & Bảo toàn dữ liệu nguồn	Nguyễn Minh Quân	Đã hoàn thành	6	7	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	File raw JSON thu được từ Collector; quy tắc ép kiểu dữ liệu và chuẩn hóa kỳ báo cáo.	Chuẩn hóa key kỳ, ép kiểu số liệu; giữ nguyên bản raw; giữ nguyên key lạ chưa xác minh; tách biệt đơn vị VND, %, EPS.	Dữ liệu normalized truy ngược được về raw; không tự đoán hoặc làm mất key nguồn.					...**

🟢 **	Sprint 2	S2-WBS06	S2-G03	1	Xây dựng bộ OCR Router bóc tách PDF 	Nguyễn Minh Quân	Đã hoàn thành	6	6	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Kho file PDF BCTC/BCTN mẫu đã tải từ Sprint 1; công cụ hệ thống (pdftotext, pdftoppm, tesseract tiếng Việt).	Tuyến text\_layer chạy tức thì; trang scan có text và toạ độ BBox.	Tuyến text\_layer chạy tức thì; trang scan có text và toạ độ BBox từ Tesseract.					2	4									**

🟢 **	Sprint 2	S2-WBS07	S2-G03	2	Tích hợp LLM Vision xử lý bảng scan	Nguyễn Minh Quân	Đã hoàn thành	7	8	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Ảnh PNG render từ các trang scan/bảng phức tạp; API Key Gemini và OpenRouter; JSON Schema yêu cầu.	Gọi Gemini 3.8 Flash ép JSON trích xuất bảng Markdown; thêm OpenRouter fallback; cache SHA-256; chặn rate limit 429.	LLM đọc nguyên văn bảng biểu, con dấu \[stamp\] cho các trang scan khó.											4	4...**

🟢 **Kết quả cần có: News đúng khoảng ngày và công ty, giữ URL/nội dung gốc; không gộp hai bài khác chỉ vì cùng tiêu đề. Bài thiếu ngày/công ty rõ ràng được cách ly.	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng quy tắc lọc đã chốt để làm sạch nội dung, chuẩn ngày và gắn công ty có bằng chứng. So URL/hash để liên kết bản trùng hoặc đăng lại; giữ bài gốc. Không thêm phân tích cảm xúc hay tóm tắt AI trong Spri...**

🟢 **Kết quả cần có: Migration chạy trên DB mới, khóa ngoại đúng và lưu/đọc được ba loại nguồn với locator. Có hướng dẫn chạy, không lưu secrets trong source.	Thái Quốc Hưng	Đã hoàn thành	7	6	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Triển khai ERD đã có cho source/document/version/facts/News/Evidence; tái dùng script nạp mẫu. Tạo khóa và ràng buộc, thử một luồng lưu/đọc từ dữ liệu chuẩn về bản gốc. Chưa làm embedding, graph hay API nghiệp v...**

🟢 **Kết quả cần có: Mẫu đúng được nhận, mẫu sai bị cách ly và không vào corpus hợp lệ. Bản sửa phải kiểm lại; thiếu bản gốc không được cho qua.	Thái Quốc Hưng	Đã hoàn thành	3	3	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Gắn kiểm tra vào pipeline nạp: ID, ngày/kỳ, đơn vị, scope, nguồn, hash và locator. Dùng bảng/file quarantine đơn giản có reason code, chưa làm màn hình hay công cụ sửa dữ liệu thật. Sửa lỗi và chạy lại kiểm tra trong chính ta...**

🟢 **Kết quả cần có: Dữ liệu được nạp đều qua validation. Có bảng độ phủ, mẫu đối chiếu và lỗi đã xử lý; nguồn bắt buộc còn thiếu thì không nghiệm thu data hoàn thành.	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy script nạp, đối chiếu số item với danh sách bắt buộc và audit nội dung/số theo mẫu kiểm đã duyệt. Kiểm liên kết về nguồn, tổng hợp thiếu/lỗi theo công ty và kỳ; review data và kiểm lại lỗi nằm tron...**

🟢 **	Sprint 2	S2-WBS12	S2-G09	2	Đối soát chéo số liệu (Cross-check) chống sai lệch	Nguyễn Minh Quân	Đã hoàn thành	4	4	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Bản text OCR từ Tesseract và bản text Markdown từ LLM của cùng một trang PDF.	Đối soát số giữa Tesseract và LLM (numberAgreement); gắn cờ NUMBERS\_UNVERIFIED cho trang BCTC lệch số; escalate model.	Loại bỏ rủi ro AI đọc sai số; gắn nhãn trạng thái OK/REVIEW trên từng trang.											...**

🟢 **Kết quả cần có: Có file sơ đồ luồng/sitemap chỉnh sửa được, liệt kê đủ màn hình, quyền và đường quay lại; nhóm duyệt trước khi thiết kế wireframe.	Trần Diệu Huyền	Đã hoàn thành	2		Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền làm lead UI, đối chiếu use case MVP để vẽ sơ đồ màn hình theo vai trò và luồng đăng nhập, chọn công ty, hỏi, xem nguồn, history/watchlist. Chỉ vẽ luồng cần code Sprint 2, không thêm xuất PDF/Markdown.	Có file sơ ...**

🟢 **Kết quả cần có: Mốc 1 và mốc 2 đều có link/file wireframe chỉnh sửa được và ý kiến duyệt của Huyền. Chỉ đánh dấu hoàn thành WBS18 khi đủ toàn bộ màn hình MVP và các lỗi điều hướng chặn đã sửa; bàn giao một mốc không đồng nghĩa hoàn thành cả task.	Hồ Phạm Đăng Nhân	Đã hoàn thành	5	10	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Nhân dùng sitemap đã duyệt để vẽ wireframe chỉnh sửa được và bàn giao theo hai mốc: mốc 1 (29/09) gồm chọn công ty...**

🟢 **Kết quả cần có: Có file thiết kế chỉnh sửa được gồm style, component mẫu và các trạng thái; nhóm xác nhận tính nhất quán với wireframe.	Trần Diệu Huyền	Đã hoàn thành	4		Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền chốt màu, chữ, khoảng cách, bảng, form, nút, citation marker và các trạng thái loading/empty/error/missing-data từ sitemap đã duyệt và bộ component sẵn có. Có thể làm quy tắc chung song song với wireframe của Nhân; áp dụng ...**

🟢 **Kết quả cần có: Có link/file prototype bấm thử cho đầy đủ màn hình và trạng thái lỗi mẫu, khớp cả hai mốc wireframe/visual; Huyền review và Vũ sửa lỗi chặn. Prototype mốc 1 chỉ là bàn giao trung gian, chưa được tính hoàn thành WBS20.	Đinh Huỳnh Vũ	Đã hoàn thành	7	10	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Vũ dựng prototype từng màn hình ngay sau khi wireframe mốc tương ứng được Huyền duyệt và có visual áp dụng; làm trước luồng chọn cô...**

🟢 **Kết quả cần có: Source clone/cài/chạy/build được theo README; khung trang hoạt động, không có secrets; layout cuối khớp màn hình đã duyệt.	Đinh Huỳnh Vũ	Đã hoàn thành	6	3	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Vũ dựng project frontend, lệnh chạy/build, cấu hình môi trường và mock adapter từ repository Sprint 1 trước khi nhận đủ wireframe. Chỉ ghép menu/layout của từng màn hình sau khi wireframe và visual mốc đó được duyệt; giữ chỗ rõ...**

🟢 **Kết quả cần có: Component tái sử dụng và mock tách riêng, có trạng thái đủ/rỗng/lỗi và hướng dẫn đổi API; tích hợp được với các màn hình đã duyệt.	Hồ Phạm Đăng Nhân	Đã hoàn thành	8	7	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Nhân cấu hình bảng/form/nút/filter/modal và fixture đủ/rỗng/lỗi từ schema chung, quy tắc visual đã có. Có thể làm component và mock độc lập trong khi hoàn thiện wireframe; tích hợp theo từng màn hình được duyệt với ...**

🟢 **Kết quả cần có: Routes và trạng thái truy cập hoạt động với mock, các phần cần API thật được liệt kê. Có smoke test điều hướng tuần 1.	Trần Diệu Huyền	Đã hoàn thành	5		Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền dùng router chung để nối màn hình, code form login/logout, phiên hết hạn và vai trò mẫu. Có thể chuẩn bị route map và phiên mẫu từ sitemap trong khi Nhân làm wireframe; chỉ ghép layout và smoke test điều hướng khi skeleton/c...**

🟢 **Kết quả cần có: Có checklist duyệt từng mốc wireframe, review prototype, danh sách lỗi chặn và bộ file thiết kế/API mock bàn giao; chỉ chốt khi đủ hai mốc.	Trần Diệu Huyền	Đã hoàn thành	4		Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền review từng mốc wireframe của Nhân ngay khi bàn giao, ghi rõ màn hình đã duyệt/chờ sửa và bàn giao cho Vũ bắt đầu prototype phần tương ứng. Sau đó review prototype đầy đủ so với sitemap, wireframe, visua...**

🟢 **Kết quả cần có: Màn hình code chạy được, đủ trạng thái chính và nhãn nguồn/đơn vị/ngày; không chỉ bàn giao ảnh thiết kế.	Hồ Phạm Đăng Nhân	Đã hoàn thành	7	7	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng bảng/filter/card chung để hiển thị 10 mã, kỳ, profile/facts/News và nguồn. Đổi company/period cập nhật fixture; nếu panel thị trường có trong scope ghi mock/EOD, không live. Không tích hợp nguồn hay API thị trường mới.	Màn hình code chạ...**

🟢 **Kết quả cần có: Các luồng đã chốt chạy với mock và nhãn rõ; filter/payload đúng, kết quả chờ/lỗi/thiếu không bị hiển thị như verified.	Trần Diệu Huyền	Đã hoàn thành	6		Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng form, chat/result và bảng chung để nhập câu hỏi, chọn công ty/kỳ, xem response/so sánh mẫu. Thêm partial/insufficient-data/refusal và retry; không làm streaming tùy biến, backend RAG hoặc tư vấn đầu tư.	Các luồng đã chốt chạy...**

🟢 **Kết quả cần có: Các luồng MVP chạy được với mock, không trùng watchlist và không mở URL client tùy ý. Không có xuất PDF/Markdown; thiếu API thật được ghi rõ.	Trần Diệu Huyền	Đã hoàn thành	6		Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tái dùng modal/detail/list/form để mở citation ID, xem locator/fact/provenance, xem/xóa history, pin/unpin và feedback. Chỉ mô phỏng lưu theo user, chưa xây backend lưu trữ; xác nhận thao tác xóa và thử lỗi ...**

🟢 **Kết quả cần có: Viewer thao tác được và mở đúng provenance mẫu; thử graph rỗng/lỗi, chặn hơn hai hop. Backend sẽ kiểm giới hạn khi nối thật.	Hồ Phạm Đăng Nhân	Đã hoàn thành	7	6	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng component/thư viện graph đã chọn, nạp fixture node/edge, chọn root, mở rộng tối đa hai hop và xem nguồn edge. Không tự viết thuật toán layout, animation hoặc Neo4j API trong task này.	Viewer thao tác được và mở đúng ...**

🟢 **Kết quả cần có: Các màn hình operator trong checklist chạy với mock, có counts/reason/refresh-time và trạng thái lỗi; không lộ secrets.	Đinh Huỳnh Vũ	Đã hoàn thành	5	4	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng chung bảng/list/detail/form cho source, runs/counts/retries và quarantine. Đổi cấu hình/fixture theo trang thay vì viết một hệ thống quản trị riêng; thao tác quan trọng có xác nhận. Không gọi bộ cào thật từ mock UI.	Các màn h...**

🟢 **Kết quả cần có: Trang có đủ luồng MVP và trạng thái không đủ điều kiện/lỗi với mock, hợp đồng API thật được liệt kê.	Đinh Huỳnh Vũ	Đã hoàn thành	4	6	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng lại trang quản trị của task trước, thay schema/form/fixture cho manifest/promote/restore, ngưỡng/budget và trace. Kiểm giá trị và readiness mẫu, không làm backend quản lý cấu hình/audit hoặc telemetry thật.	Trang có đủ luồng MVP và trạng thái k...**

🟢 **Kết quả cần có: Màn hình evaluator trong checklist thao tác được, phân biệt partial/completed/thiếu trace và không hiển thị điểm giả như kết quả thật.	Đinh Huỳnh Vũ	Đã hoàn thành	5	5	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng bảng/form/detail chung để nhập/review/freeze ca mẫu, chọn B0–B3 và xem run/metrics fixture. Thêm calibration/final và quyền mẫu; chưa tạo 120 câu thật, chạy Ragas hoặc xây engine đánh giá.	Màn hình evaluator tr...**

🟢 **Kết quả cần có: Có checklist đối chiếu thiết kế–code và biên bản review UI, bản build chạy được; màn hình lệch thiết kế hoặc lỗi chặn chưa sửa thì chưa ký bàn giao.	Trần Diệu Huyền	Đã hoàn thành	2		Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền đối chiếu code của Vũ/Nhân với bản thiết kế và prototype, chạy smoke test màn hình/route/trạng thái bằng mock trên bản build sạch. Ghi lỗi chặn về đúng task để chủ task sửa, xác nhận lại sau sửa...**

🟢 **					Tổng giờ các task			141	122																				**

🟢 **					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Giờ dự kiến theo ngày (cả nhóm)				150							15	15	15	15	15	0	0	15	15	15	15	15	0	0**

🟢 **					Giờ thực tế theo ngày (tự tính)				122							7	12	13	13	11	6	0	12	13	13	11	11	0	0**

🟢 **Sprint 2 Report**

🟢 **Sprint 2 Report							**

🟢 **Phạm vi (task)	28	Done hiện tại	28	Giờ dự kiến	141	Done thiếu ngày	28**

🟢 **Giờ thực tế	122	Bắt đầu	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0**

🟢 **Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	28		0		28		**

🟢 **Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		26	7	7**

🟢 **Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		24	12	19**

🟢 **Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		22	13	32**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		20	13	45**

🟢 **Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		18	11	56**

🟢 **Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		16	6	62**

🟢 **Sun Oct 04 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		14		62**

🟢 **Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		12	12	74**

🟢 **Tue Oct 06 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		10	13	87**

🟢 **Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		8	13	100**

🟢 **Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		6	11	111**

🟢 **Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		4	11	122**

🟢 **Sat Oct 10 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		2		122**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	28	0	0		0		122**

🟢 **	FinMind Sprint 3 Backlog																												**

🟢 **	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	52																							**

🟢 **	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Ngày hoàn thành thực tế	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 17 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **	Sprint 3	S3-WBS01	S3-G01	1	Chốt hợp đồng chunk ID và cấu trúc nguồn	Đinh Huỳnh Vũ	Đã hoàn thành	2		Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cùng Hưng thống nhất mỗi đoạn tài liệu sẽ mang những thông tin nào: mã đoạn, mã tài liệu, phiên bản dữ liệu và vị trí trang/mục/bảng. Bước 2: Viết 2 đoạn dữ liệu mẫu theo đúng cấu trúc đó để mọi người có thể code song song. Bước 3: Kiểm tra cùng một đoạn luôn nhận cùng mã khi chạy lại.	Có ...**

🟢 **	Sprint 3	S3-WBS06	S3-G01	1	Nâng cấp chunker cho mục và bảng	Đinh Huỳnh Vũ	Đã hoàn thành	7		Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy tài liệu BCTC/BCTN đã chuẩn hóa ở Sprint 2, xem các mục và bảng dài thường bị cắt sai ở đâu. Bước 2: Nâng cấp bộ chia đoạn hiện có để mỗi đoạn có nội dung đủ hiểu và không xé ngang bảng số liệu. Bước 3: Viết ví dụ kiểm tra cho văn bản thường, bảng nhiều dòng và chạy lại để chắc không sinh đoạn...**

🟢 **	Sprint 3	S3-WBS11	S3-G01	1	Gắn locator vào từng chunk	Đinh Huỳnh Vũ	Đã hoàn thành	4		Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Với mỗi đoạn Vũ đã chia, lưu rõ nó đến từ tài liệu nào, trang nào, mục hoặc bảng nào. Bước 2: Lấy vài đoạn mẫu, bấm/mở lại tài liệu gốc tại vị trí ghi trong đoạn. Bước 3: Sửa các trường hợp trích dẫn nhảy sai trang, sai bảng hoặc không mở được.	Chunk mẫu truy được vị trí nguồn chính xác trong tài liệu.	...**

🟢 **	Sprint 3	S3-WBS16	S3-G01	1	Tạo manifest chunk phiên bản đầu	Đinh Huỳnh Vũ	Đã hoàn thành	2		Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Ghi một bản kê cho lần chia tài liệu: tài liệu đầu vào, mã kiểm tra nội dung, cấu hình chia đoạn và danh sách mã đoạn. Bước 2: Chạy lại cùng tài liệu để xác nhận không tạo bản sao. Bước 3: Thay một tài liệu mẫu và kiểm tra bản kê cho biết chính xác phần nào đã đổi.	Có manifest phiên bản và danh sá...**

🟢 **	Sprint 3	S3-WBS19	S3-G01	2	Ổn định chunker trên tài liệu khó	Đinh Huỳnh Vũ	Đang test	3		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thử bộ chia đoạn trên báo cáo có bảng dài, nhiều cột, đổi trang hoặc tiêu đề không đều. Bước 2: Ghi lại từng lỗi và sửa các lỗi nằm trong phạm vi 3 giờ đã phân. Bước 3: Chạy lại toàn bộ ví dụ cũ để chắc sửa bảng khó không làm hỏng tài liệu đơn giản; ghi rõ phần chưa hỗ trợ.	Test hồi quy trên mẫu khó ...**

🟢 **	Sprint 3	S3-WBS24	S3-G01	2	Kiểm tra citation locator đầu-cuối	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy một câu trả lời mẫu của B1 và mở từng trích dẫn về đúng đoạn nguồn. Bước 2: Kiểm tra đặc biệt bảng trải nhiều trang và hai phiên bản cùng một tài liệu. Bước 3: Sửa trường hợp trích dẫn sai trang, sai bảng hoặc trỏ sang phiên bản dữ liệu khác.	Citation mẫu dẫn đúng document/trang/bảng và không...**

🟢 **	Sprint 3	S3-WBS29	S3-G06	2	Rà soát chéo Golden40 theo lô	Đinh Huỳnh Vũ	Chưa bắt đầu	8		Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nhận Golden40 theo từng lô 10 câu từ Huyền, không chờ đủ 40 mới bắt đầu. Bước 2: Với mỗi câu, mở tài liệu gốc, kiểm tra đáp án, đơn vị/kỳ và vị trí nguồn; ghi đúng/sai và lý do. Bước 3: Trả danh sách bất đồng cho Huyền sửa, rồi xác nhận lại trước khi bộ câu hỏi được khóa.	Mỗi ca có dấu review người th...**

🟢 **	Sprint 3	S3-WBS02	S3-G02	1	Chốt mô hình embedding và cấu hình	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng vài đoạn văn mẫu để thử mô hình biến chữ thành dãy số (embedding), nhờ đó máy có thể tìm đoạn gần nghĩa. Bước 2: Ghi rõ tên/phiên bản mô hình, số chiều của dãy số và số đoạn xử lý mỗi lần. Bước 3: Lưu cấu hình và một kết quả mẫu để nhóm dùng chung; chưa cần đợi Vũ chia xong tài liệu thậ...**

🟢 **	Sprint 3	S3-WBS07	S3-G02	1	Tạo embedding theo lô có báo lỗi	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cho chương trình nhận nhiều đoạn văn mẫu một lần và tạo vector cho từng đoạn. Bước 2: Nếu một đoạn bị lỗi, ghi rõ mã đoạn và lý do, chỉ thử lại có giới hạn, không làm mất các đoạn thành công. Bước 3: Chạy thử một lô có cả đoạn tốt và đoạn lỗi để chứng minh có thể xử lý lại đúng phần lỗi.	Một m...**

🟢 **	Sprint 3	S3-WBS12	S3-G02	1	Lưu vector và metadata vào pgvector	Hồ Phạm Đăng Nhân	Đã hoàn thành	5		Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chuẩn bị nơi lưu vector trong PostgreSQL/pgvector và liên kết mỗi vector với đúng mã đoạn, tài liệu, công ty và phiên bản dữ liệu. Bước 2: Kiểm tra kích thước vector và ngăn lưu trùng khi chạy lại. Bước 3: Lưu thử từ dữ liệu mẫu, sau đó chuyển sang các đoạn thật khi Vũ bàn giao.	Vector mẫu ...**

🟢 **	Sprint 3	S3-WBS17	S3-G02	1	Ingest thử corpus vào pgvector	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy một nhóm đoạn thật đã được Vũ gắn nguồn và tạo vector. Bước 2: Nạp vào pgvector, ghi số đoạn thành công, số lỗi và lý do lỗi. Bước 3: Truy vấn lại để đối chiếu số lượng, mã tài liệu, phiên bản; chạy lại không được nhân đôi dữ liệu.	Truy vấn pgvector thấy đúng số chunk hợp lệ và lỗi được lưu ...**

🟢 **	Sprint 3	S3-WBS20	S3-G02	2	Tạo chỉ mục pgvector và đo baseline	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Có kết quả bas...**

🟢 **	Sprint 3	S3-WBS25	S3-G02	2	Truy vấn vector có lọc phạm vi	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Ca lọc sai công ty/kỳ...**

🟢 **	Sprint 3	S3-WBS30	S3-G02	2	Ghi timing và lỗi retrieval	Hồ Phạm Đăng Nhân	Đang test	3		Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Với mỗi lần tìm kiếm vector, ghi thời gian chạy, số đoạn tìm được, điểm của các đoạn và mã lỗi nếu có. Bước 2: Che thông tin nhạy cảm trong lỗi/log. Bước 3: Chạy câu hỏi thành công và câu hỏi lỗi để chắc người kiểm tra có đủ dấu vết tìm nguyên nhân chậm hoặc sai.	Một truy vấn có trace thật đủ phân tích...**

🟢 **	Sprint 3	S3-WBS34	S3-G02	2	Kiểm thử E2E vector retrieval	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chọn một tài liệu sạch và chạy toàn bộ đường đi: Vũ chia đoạn, Nhân tạo/lưu vector, rồi tìm lại đoạn bằng câu hỏi. Bước 2: So số đoạn, mã nguồn, phiên bản và trích dẫn ở từng bước. Bước 3: Chạy lại để kiểm tra không trùng; lỗi nào chưa sửa được phải ghi rõ người phụ trách.	Ca E2E qua hoặc có lỗi k...**

🟢 **	Sprint 3	S3-WBS05	S3-G08	1	Chốt thiết kế tài khoản và API	Nguyễn Minh Quân	Đã hoàn thành	3	2	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Xem các trang đăng nhập/đăng ký hiện có, phần tài khoản và phiên đăng nhập trong cơ sở dữ liệu. Bước 2: Vẽ luồng người dùng cho đăng ký, đăng nhập, quên mật khẩu, đặt lại mật khẩu và đăng xuất. Bước 3: Chốt cách quản lý đăng nhập và danh sách API cần làm trước khi code, kèm quy tắc không ghi mật...**

🟢 **	Sprint 3	S3-WBS10	S3-G08	1	Code đăng ký và đăng nhập backend	Nguyễn Minh Quân	Đã hoàn thành	8	6	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo chức năng đăng ký bằng thông tin hợp lệ và lưu mật khẩu dưới dạng đã bảo vệ, không lưu bản gốc. Bước 2: Tạo đăng nhập, xử lý sai mật khẩu và giới hạn thử liên tiếp; trả thông báo không tiết lộ dữ liệu nhạy cảm. Bước 3: Kiểm thử tài khoản đúng/sai và xác nhận người dùng không tự cấp quyền ...**

🟢 **	Sprint 3	S3-WBS15	S3-G08	1	Nối login/register UI với API	Nguyễn Minh Quân	Đã hoàn thành	4	3	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nối màn hình đăng nhập/đăng ký hiện có với API thật thay vì dữ liệu giả. Bước 2: Hiển thị trạng thái đang xử lý, nhập sai, lỗi mạng và đăng nhập thành công sao cho người dùng hiểu. Bước 3: Kiểm tra giao diện không lưu mật khẩu hoặc mã khôi phục trong trình duyệt.	Luồng UI đăng nhập/đăng ký dùng b...**

🟢 **	Sprint 3	S3-WBS23	S3-G08	2	Code quên và đặt lại mật khẩu	Nguyễn Minh Quân	Đã hoàn thành	6	4	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo luồng người dùng nhập email để xin đặt lại mật khẩu; phản hồi giống nhau dù email có tồn tại hay không. Bước 2: Phát mã/đường dẫn khôi phục chỉ dùng một lần và có hạn, lưu bản đã bảo vệ, rồi cho người dùng đặt mật khẩu mới. Bước 3: Làm màn hình quên/đặt lại mật khẩu và thử mã đúng, mã hết hạn...**

🟢 **	Sprint 3	S3-WBS28	S3-G08	2	Hoàn thiện session logout refresh	Nguyễn Minh Quân	Đã hoàn thành	4	3	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cho người dùng đăng xuất và làm phiên đăng nhập hết hiệu lực theo cách đã chọn. Bước 2: Xử lý trường hợp phiên hết hạn: thử làm mới an toàn nếu được phép, nếu không thì đưa về trang đăng nhập. Bước 3: Thử mã phiên sai, hết hạn và đã đăng xuất để chắc không truy cập tiếp được.	Logout thu hồi p...**

🟢 **	Sprint 3	S3-WBS33	S3-G08	2	Bảo vệ API theo vai trò	Nguyễn Minh Quân	Đã hoàn thành	3	3	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Liệt kê API tài khoản, nguồn dữ liệu, corpus, truy vấn và đánh giá nằm trong phạm vi Sprint 3, cùng vai trò được phép dùng từng API. Bước 2: Kiểm tra quyền ở máy chủ, không chỉ ẩn nút trên giao diện. Bước 3: Thử tài khoản thiếu quyền gọi trực tiếp từng API và xác nhận bị từ chối.	Sai vai trò bị từ chối...**

🟢 **	Sprint 3	S3-WBS36	S3-G08	2	Kiểm thử bảo mật tài khoản	Trần Diệu Huyền 	Chưa bắt đầu	2		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thử đặt lại mật khẩu bằng mã hết hạn và mã đã dùng; cả hai phải bị từ chối. Bước 2: Thử đăng xuất rồi dùng lại phiên và thử tài khoản sai vai trò gọi API. Bước 3: Xem log không lộ mật khẩu, mã reset hoặc việc email có tồn tại; lỗi chưa qua phải để mở, không đánh dấu hoàn thành.	Các ca bảo mật thiết yế...**

🟢 **	Sprint 3	S3-WBS03	S3-G04	1	Chốt intent và phạm vi câu hỏi B1	Thái Quốc Hưng	Đã hoàn thành	4	4	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Liệt kê thông tin phải hiểu từ câu hỏi: công ty, thời kỳ và chỉ tiêu tài chính. Bước 2: Viết ví dụ câu hỏi đủ thông tin, thiếu thông tin và mơ hồ. Bước 3: Quy định khi nào hệ thống được tìm dữ liệu, khi nào phải hỏi lại người dùng; thử bằng dữ liệu mẫu trước.	Có bảng intent, scope và ca kiểm th...**

🟢 **	Sprint 3	S3-WBS08	S3-G04	1	Chốt cấu trúc evidence pack	Thái Quốc Hưng	Đã hoàn thành	3	3	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Quy định một gói bằng chứng cần có nội dung đoạn, mã nguồn, vị trí trang/bảng, phiên bản dữ liệu và điểm phù hợp. Bước 2: Tạo vài gói mẫu và cho luồng trả lời B1 đọc thử, ngay cả khi tìm kiếm vector thật chưa xong. Bước 3: Kiểm tra gói thiếu vị trí nguồn hoặc phiên bản bị báo lỗi rõ ràng.	B1 đọc được...**

🟢 **	Sprint 3	S3-WBS13	S3-G04	1	Dựng B1 retrieval orchestration bằng fixture	Thái Quốc Hưng	Đã hoàn thành	5	6	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nối phần hiểu câu hỏi với mẫu kết quả tìm kiếm và gói bằng chứng đã thống nhất. Bước 2: Cho B1 chạy thử với dữ liệu mẫu để kiểm tra đường đi từ câu hỏi đến danh sách nguồn. Bước 3: Xử lý riêng trường hợp không tìm thấy nguồn, kết quả rỗng hoặc hết thời gian; chưa phải đợi dữ liệu vec...**

🟢 **	Sprint 3	S3-WBS18	S3-G04	1	Xử lý B1 khi câu hỏi hoặc nguồn mơ hồ	Thái Quốc Hưng	Đã hoàn thành	3	3	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng câu hỏi thiếu công ty/kỳ/chỉ tiêu để thử B1. Bước 2: Viết câu trả lời yêu cầu người dùng làm rõ thay vì đoán. Bước 3: Với câu hỏi đủ thông tin nhưng không có nguồn phù hợp, cho hệ thống nói chưa đủ bằng chứng và không tự tạo số liệu.	Ca thiếu công ty/kỳ hoặc không có nguồn không bị bịa...**

🟢 **	Sprint 3	S3-WBS21	S3-G04	2	Nối B1 với retrieval và Gemini	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng dữ liệu mẫu để hoàn thiện phần gửi câu hỏi và bằng chứng cho Gemini. Bước 2: Khi Nhân bàn giao truy vấn vector có lọc, thay đầu vào mẫu bằng đoạn thật, giữ mã nguồn trong câu trả lời. Bước 3: Ghi phiên bản mô hình, prompt, giới hạn ngữ cảnh và kiểm tra B1 không bật cơ chế kiểm chứng riêng của...**

🟢 **	Sprint 3	S3-WBS26	S3-G04	2	Kiểm tra trích dẫn và câu trả lời B1	Thái Quốc Hưng	Đã hoàn thành	3	2	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy vài câu trả lời B1 có nguồn đầy đủ, nguồn thiếu và nguồn mâu thuẫn. Bước 2: Kiểm tra từng nhận định có mã bằng chứng tương ứng và trích dẫn mở được. Bước 3: Với nhận định không chứng minh được, sửa câu trả lời thành thận trọng hoặc báo chưa đủ bằng chứng.	Không có claim vô nguồn trong ca...**

🟢 **	Sprint 3	S3-WBS31	S3-G04	2	Áp giới hạn token timeout và budget	Thái Quốc Hưng	Đã hoàn thành	3	4	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	Ca...**

🟢 **	Sprint 3	S3-WBS35	S3-G04	2	Chạy B1 trên Golden40 đã khóa	Thái Quốc Hưng	Đã hoàn thành	4	3	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	...**

🟢 **	Sprint 3	S3-WBS04	S3-G06	1	Chốt phân bổ Golden40	Trần Diệu Huyền	Đã hoàn thành	3		Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lập danh sách đúng 40 câu hỏi để hiệu chỉnh hệ thống, chia đều theo loại câu hỏi, ngành, ngôn ngữ và thời kỳ đã chốt. Bước 2: Đánh mã từng câu, giao thành các lô 10 câu cho người kiểm tra. Bước 3: Đối chiếu để không trùng với 80 câu của bộ kiểm tra cuối, vì bộ cuối không được dùng để chỉnh hệ thống.	Bảng p...**

🟢 **	Sprint 3	S3-WBS09	S3-G06	1	Soạn Golden40 lô 1–2	Trần Diệu Huyền	Đã hoàn thành	6		Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Soạn 20 câu hỏi đầu theo phân bổ đã duyệt, kèm đáp án ngắn, đơn vị và kỳ báo cáo. Bước 2: Với mỗi đáp án, ghi tài liệu gốc và trang/mục/bảng có thể mở lại để kiểm chứng. Bước 3: Đánh dấu câu còn nghi ngờ và gửi từng lô 10 câu cho người rà soát, không chờ xong cả bộ.	20 ca có đáp án và locator mở lại được; đ...**

🟢 **	Sprint 3	S3-WBS14	S3-G06	1	Soạn Golden40 lô 3–4	Trần Diệu Huyền	Đã hoàn thành	6		Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Soạn nốt 20 câu còn lại để đủ 40 câu, không chỉ viết câu hỏi mà phải có đáp án và nguồn chứng minh. Bước 2: Kiểm tra toàn bộ 40 câu có đúng tỷ lệ loại câu/ngành/ngôn ngữ đã định. Bước 3: Gửi từng lô 10 câu cho Vũ rà soát và ghi rõ câu cần sửa.	Đủ 40 ca có đáp án, nguồn gốc và trạng thái cần review.	Golden40...**

🟢 **	Sprint 3	S3-WBS22	S3-G06	2	Hoàn thiện đáp án và locator Golden40	Trần Diệu Huyền	Đã hoàn thành	8		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Mở lại tài liệu gốc cho từng câu trong Golden40 để kiểm tra đáp án, đơn vị, kỳ và vị trí trang/bảng. Bước 2: Sửa câu trùng, câu mơ hồ hoặc đáp án chưa có nguồn chắc chắn. Bước 3: Chuyển từng lô đã ổn cho Vũ rà soát độc lập, kèm danh sách chỗ còn bất đồng.	40 ca đủ trường bắt buộc; mỗi ca có...**

🟢 **	Sprint 3	S3-WBS27	S3-G06	2	Khóa Golden40 sau rà soát chéo	Trần Diệu Huyền	Đã hoàn thành	2		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nhận bản rà soát của Vũ cho từng lô 10 câu. Bước 2: Cùng Vũ giải quyết tất cả câu còn bất đồng về đáp án hoặc vị trí nguồn. Bước 3: Lưu bản Golden40 cuối cùng với mã phiên bản và mã kiểm tra nội dung; từ đây không sửa âm thầm khi chạy đánh giá.	40 ca có version khóa; không còn bất đồng chưa xử lý....**

🟢 **	Sprint 3	S3-WBS32	S3-G06	2	Chuẩn bị metric và bàn giao Golden40	Trần Diệu Huyền	Chưa bắt đầu	5		Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Viết tiêu chí chấm câu trả lời: đúng số liệu, có nguồn mở lại được, trả lời đủ ý và trường hợp cần người kiểm tra. Bước 2: Thử cách tính trên vài ca mẫu, ghi kết quả tạm. Bước 3: Sau khi Golden40 được khóa, chạy lại trên bản khóa và bàn giao bảng lỗi cùng phiên bản dùng cho Sprint 4.	Có metri...**

🟢 **					Tổng giờ các task			150	52																				**

🟢 **					Giờ thực tế theo ngày (tự tính)				46							5	9	6	3	3	1	0	7	3	3	3	3	0	0**

🟢 **Sprint 3 Report**

🟢 **Sprint 3 Report							**

🟢 **Phạm vi (task)	36	Done hiện tại	29	Giờ dự kiến	150	Done thiếu ngày	29**

🟢 **Giờ thực tế	52	Bắt đầu	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0**

🟢 **Sun Oct 11 2026 07:00:00 GMT+0700 (Indochina Time)	36		0		36		**

🟢 **Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		33.43	5	5**

🟢 **Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		30.86	9	14**

🟢 **Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		28.29	6	20**

🟢 **Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		25.71	3	23**

🟢 **Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		23.14	3	26**

🟢 **Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		20.57	1	27**

🟢 **Sun Oct 18 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		18		27**

🟢 **Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		15.43	7	34**

🟢 **Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		12.86	3	37**

🟢 **Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		10.29	3	40**

🟢 **Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		7.71	3	43**

🟢 **Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		5.14	3	46**

🟢 **Sat Oct 24 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		2.57		46**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	36	0	0		0		46**

🟢 **	Mục tiêu Sprint 4: Graph RAG cho quan hệ doanh nghiệp, chức vụ và sự kiện; Hybrid Router chọn VECTOR/GRAPH/BOTH. Dùng lại chunk và B1 Sprint 3.																												**

🟢 **	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																												**

🟢 **	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																												**

🟢 **	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																												**

🟢 **	Phân công theo nhóm đã chốt. WBS10 tuần 1; WBS09 tuần 2. WBS17 là một task chung: Nhân 7h và Huyền 6h, tổng 13 giờ công. Ngày và giờ là đề xuất; dùng fixture khi chờ đầu vào.																												**

🟢 **	FinMind Sprint 4 Backlog																												**

🟢 **	Số task	17	Giờ dự kiến	128	Tổng giờ thực tế đã ghi			Tuần 1 (h)	65	Tuần 2 (h)	63																		**

🟢 **	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Ngày hoàn thành thực tế	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 31 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **4. Bàn giao quan hệ ứng viên có đoạn nguồn; thử ca nhiều chức vụ, nhiều công ty, thiếu thời gian và nguồn mâu thuẫn.	Quan hệ chức vụ đủ người, tổ chức, chức danh và provenance; không nhầm trạng thái hoặc thời gian; ca chưa rõ được đánh dấu.	WBS01; dùng WBS02 thật để nghiệm thu. Có thể làm bằng fixture song song WBS03/WBS05 và phần lưu metadata WBS07.															**

🟢 **4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	WBS01 và trạng thái WBS06 (có thể chốt interface song song). Dùng repository fixture trước DB thật. Phối hợp khóa extraction/version với Nhân WBS08.															**

🟢 **4. Chạy hồi quy các câu B1 đã hoạt động và bàn giao adapter thật cho WBS13.	VECTOR chạy được nguồn thật, giữ phạm vi/metadata và không làm hỏng B1; có test các ca rỗng/lỗi.	WBS10 và Vector RAG Sprint 3. Không chờ WBS09. Làm sớm đầu tuần 2 để Vũ còn thời gian WBS16.															**

🟢 **5. Bàn giao báo cáo full-load, lỗi còn lại và phiên dữ liệu. 8h là công chuẩn bị, theo dõi và đối chiếu, không phải cam kết thời gian máy/LLM hay duyệt thủ công mọi quan hệ.	Toàn bộ News đã chốt có trạng thái, không mất tin lỗi; có báo cáo mẫu/full-load riêng và danh sách lỗi chưa xử lý. Không coi mọi quan hệ trích xuất là đã được chấp nhận.	WBS01–08 và kiểm tra mẫu WBS09.5 đạt. Batch runner làm trước bằng fixture; không cần chờ router/chat/UI. Phụ thuộc hạn mức dịch vụ và quyền chạy dữ liệu thậ...**

🟢 **4. Dùng ID WBS02 để xuất đúng contract; kiểm tra mẫu hợp lệ, sai chiều, thiếu chủ thể và hai tên chỉ xuất hiện cùng đoạn.	Có quan hệ doanh nghiệp ứng viên kèm nguồn, trạng thái và thời gian nếu có; test không tạo quan hệ chỉ từ đồng xuất hiện.	Contract WBS01; chuẩn hóa thật WBS02 để đóng task. Có thể code bằng entity fixture từ 27/10, không phải đợi WBS02 xong mới bắt đầu.															**

🟢 **4. Xử lý lỗi nạp dở, chuẩn bị resume và đối chiếu số liệu/khóa giữa hai hệ thống. Nghiệm thu phần ghi bằng fixture ở tuần 1; WBS09 nối extraction thật tuần 2.	Bộ ghi graph có test chống trùng, không lẫn phiên, giữ extraction/nguồn và không công bố lần nạp dở. Có graph fixture dùng cho truy vấn.	WBS01; thống nhất metadata/version với WBS07. Không phải đợi full extractor; dùng graph fixture trước. WBS09 chịu trách nhiệm ghép dữ liệu thật.															**

🟢 **4. Chuẩn bị adapter bằng fixture từ đầu tuần, nối retrieval thật sau khi WBS09 bàn giao; kiểm tra không lộ quan hệ chờ duyệt.	GRAPH chạy bằng graph thật đúng scope, có nguồn và lỗi rõ; đọc lại nguồn bằng ID không bị gắn nhãn BOTH.	Contract WBS10; WBS09 thật để đóng task. Có thể code adapter bằng fixture trước, không đứng chờ pipeline ghép xong.															**

🟢 **5. Cùng bàn giao bộ test, kết quả chạy thật, bảng so sánh B1/B2, báo cáo full-load và giới hạn còn lại. Chỉ hoàn thành task khi cả phần Nhân và Huyền đạt. Tổng 13 giờ công = Nhân 7 giờ + Huyền 6 giờ, không phải 13 giờ mỗi người.	Có bộ test và kết quả thật cho VECTOR/GRAPH/BOTH và ba nhóm quan hệ; bảng B1/B2 có chất lượng và thời gian phản hồi; citation đúng nguồn; có kiểm thử lỗi/E2E/hồi quy, báo cáo full-load và danh sách lỗi còn lại. Không mặc định B2 tốt hơn B1.	Chuẩn bị bộ ca bằng WBS01/fixt...**

🟢 **5.  Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 của Vũ.															**

🟢 **5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.															**

🟢 **5. Giữ cấu hình B1 để so sánh; không tự bật Evidence Gate/verifier B3 thuộc sprint sau.	Câu trả lời/citation truy lại được nguồn, không bịa quan hệ/số liệu hoặc che lỗi nhánh; có test và gói bàn giao.	Evidence contract và WBS11–13. Có thể chuẩn bị formatter/citation bằng fixture trước, nghiệm thu sau tuyến thật.															**

🟢 **4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầu ra ngày 26/10 mở đường cho WBS02–08 và WBS10.															**

🟢 **4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.															**

🟢 **5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fixture trước; không viết lại repository/extractor. WBS12 dùng retrieval này; WBS16 chỉ full-load sau 09.5 đạt.															**

🟢 **4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ cả ba extractor mới chuẩn bị quy tắc.															**

🟢 **5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-load.															**

🟢 **5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.															**

🟢 **					Tổng giờ các task			128	0																				**

🟢 **					Giờ thực tế theo ngày (tự tính)				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0**

🟢 **					Giờ thực tế theo ngày (tự tính)				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0**

🟢 **					Giờ thực tế theo ngày (tự tính)				0							0	0	0	0	0	0	0	0	0	0	0	0	0	0**

🟢 **Sprint 4 Report**

🟢 **Sprint 4 Report							**

🟢 **Phạm vi (task)	17	Done hiện tại	6	Giờ dự kiến	128	Done thiếu ngày	6**

🟢 **Giờ thực tế		Bắt đầu	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0**

🟢 **Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	17		0		17		**

🟢 **Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		15.79		**

🟢 **Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		14.57		**

🟢 **Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		13.36		**

🟢 **Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		12.14		**

🟢 **Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		10.93		**

🟢 **Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		9.71		**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		8.5		**

🟢 **Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		7.29		**

🟢 **Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		6.07		**

🟢 **Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		4.86		**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		3.64		**

🟢 **Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		2.43		**

🟢 **Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		1.21		**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	17	0	0		0		**

🟢 **	Sprint 5 gồm 38 task con. Tuần 1 sửa lỗi và nối truy xuất (58h); tuần 2 tối ưu Chat và nhận định xu hướng (50h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																												**

🟢 **	FinMind Sprint 5 Backlog																												**

🟢 **	Số task	38	Giờ dự kiến	108	Tổng giờ thực tế đã ghi																								**

🟢 **	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Ngày hoàn thành thực tế	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 14 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **	Sprint 5	S5-WBS01.1	S5-G01	1	Tái hiện lỗi hỏi chức vụ và BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4															**

🟢 **	Sprint 5	S5-WBS01.2	S5-G01	1	Tái hiện lỗi hội thoại và hết hạn token		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có															**

🟢 **	Sprint 5	S5-WBS02.1	S5-G01	1	Tìm điều kiện chặn câu hỏi BCTN		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1															**

🟢 **	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1															**

🟢 **	Sprint 5	S5-WBS02.3	S5-G01	1	Kiểm thử truy xuất BCTN bằng dữ liệu thật		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2															**

🟢 **	Sprint 5	S5-WBS03.1	S5-G02	1	Chốt nhãn ý định và ranh giới giữa các nhãn		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—															**

🟢 **	Sprint 5	S5-WBS03.2	S5-G02	1	Soạn cụm từ mẫu và bộ câu kiểm thử riêng		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1															**

🟢 **	Sprint 5	S5-WBS03.3	S5-G02	1	Vector hóa và lưu phiên bản thư viện		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2															**

🟢 **	Sprint 5	S5-WBS04.1	S5-G02	1	Đối chiếu vector câu hỏi với thư viện		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3															**

🟢 **	Sprint 5	S5-WBS04.2	S5-G02	1	Đặt ngưỡng tin cậy và quy tắc chọn nhánh		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1															**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2															**

🟢 **	Sprint 5	S5-WBS05.1	S5-G03	1	Nối router vào luồng xử lý tin nhắn Web Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Gọi router trong backend khi Web Chat gửi tin và ghi trace. Có thể chuẩn bị tích hợp bằng mẫu.	Trace xác nhận Web Chat gọi router và chọn nhánh.	S5-WBS04.2															**

🟢 **	Sprint 5	S5-WBS05.2	S5-G03	1	Nối nhánh GRAPH với Neo4j qua adapter hiện có		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng graph adapter để lấy quan hệ đã duyệt, chức vụ và nguồn tương ứng.	Câu hỏi chức vụ trả đúng người, chức vụ và bằng chứng.	S5-WBS05.1, graph có dữ liệu đã duyệt															**

🟢 **	Sprint 5	S5-WBS05.3	S5-G03	1	Kiểm thử graph thật, graph rỗng và lỗi kết nối		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2															**

🟢 **	Sprint 5	S5-WBS06.1	S5-G04	1	Dùng cơ chế refresh token chung cho request Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập															**

🟢 **	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1															**

🟢 **	Sprint 5	S5-WBS07.1	S5-G05	1	Chốt điều kiện fallback và JSON phân loại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2															**

🟢 **	Sprint 5	S5-WBS07.2	S5-G05	1	Nối AI bên thứ ba vào bước phân loại		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Gọi AI khi cần, giới hạn thời gian, xác thực nhãn và chuyển kết quả về router FinMind. Chuẩn bị bằng phản hồi mẫu.	Nhãn hợp lệ tiếp tục truy xuất trong FinMind. Trace ghi lần gọi.	S5-WBS07.1															**

🟢 **	Sprint 5	S5-WBS07.3	S5-G05	1	Kiểm thử fallback và trường hợp cả hai bước thất bại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2															**

🟢 **	Sprint 5	S5-WBS08.1	S5-G06	1	Chuẩn bị chuỗi giá theo mã doanh nghiệp		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chốt khoảng giá, lấy ngày đầu/cuối, số phiên và nguồn theo mã.	Có chuỗi giá mẫu và mức biến động truy được nguồn.	Dữ liệu giá hiện có															**

🟢 **	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC gần nhất		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có															**

🟢 **	Sprint 5	S5-WBS08.3	S5-G06	1	Chuẩn hóa đầu vào cho mô hình xu hướng		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ghép mã, chuẩn hóa đơn vị và chọn kỳ so sánh tương đương. Đánh dấu thiếu dữ liệu.	Có đầu vào theo doanh nghiệp, kỳ, đơn vị và trạng thái đủ dữ liệu.	S5-WBS08.1, S5-WBS08.2															**

🟢 **	Sprint 5	S5-WBS09.1	S5-G07	2	Kế thừa công ty, kỳ và chủ đề giữa các lượt		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng phạm vi hội thoại hiện tại, ưu tiên công ty hoặc kỳ mới nếu người dùng thay đổi.	Câu nối tiếp giữ đúng phạm vi và chuyển phạm vi khi được yêu cầu.	S5-WBS05.1															**

🟢 **	Sprint 5	S5-WBS09.2	S5-G07	2	Xử lý liệt kê và giới thiệu tổng quan		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Liệt kê nội dung đang nói. Tổng quan đúng doanh nghiệp và truy xuất thêm khi cần.	Hai câu mẫu chạy đúng trong phiên nhiều lượt.	S5-WBS09.1															**

🟢 **	Sprint 5	S5-WBS09.3	S5-G07	2	Xử lý tổng hợp nãy giờ		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tóm tắt nội dung phiên hiện tại và giữ các nguồn đã dẫn.	Không lẫn nội dung giữa các phiên, nguồn còn đối chiếu được.	S5-WBS09.1															**

🟢 **	Sprint 5	S5-WBS10.1	S5-G06	2	Tính nhóm tín hiệu giá		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tính biến động theo khoảng đã chốt và đánh dấu thiếu phiên hoặc thiếu giá.	Có tín hiệu giá và dữ liệu dùng để tính.	S5-WBS08.1, S5-WBS08.3															**

🟢 **	Sprint 5	S5-WBS10.2	S5-G06	2	Tính nhóm tín hiệu tài chính		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tính thay đổi doanh thu, lợi nhuận và dòng tiền khi có kỳ tương đương.	Có tín hiệu từng chỉ tiêu và nguồn tương ứng.	S5-WBS08.2, S5-WBS08.3															**

🟢 **	Sprint 5	S5-WBS10.3	S5-G06	2	Gộp tín hiệu và trả nhãn xu hướng		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng quy tắc chấm điểm giải thích được để gộp tín hiệu giá và tài chính.	Trả đi lên, đi xuống, trái chiều hoặc chưa đủ dữ liệu. Ca trái chiều thể hiện hai tín hiệu riêng.	S5-WBS10.1, S5-WBS10.2															**

🟢 **	Sprint 5	S5-WBS10.4	S5-G06	2	Kiểm thử quy tắc chấm điểm		Chưa bắt đầu	2		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thử cùng tăng, cùng giảm, trái chiều và thiếu kỳ.	Mỗi nhãn giải thích được bằng số liệu đầu vào.	S5-WBS10.3															**

🟢 **	Sprint 5	S5-WBS11.1	S5-G06	2	Nối ý định xu hướng với mô hình nhận định		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Khi nhận diện câu hỏi xu hướng, gọi mô hình với đúng mã và phạm vi. Chuẩn bị bằng kết quả mẫu trước.	Trace xác nhận Chat gọi mô hình đúng đầu vào.	S5-WBS04.2, S5-WBS05.1, S5-WBS10.3 để nghiệm thu thật															**

🟢 **	Sprint 5	S5-WBS11.2	S5-G06	2	Hiển thị nhận định xu hướng trong Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tách diễn biến giá và tình hình tài chính, ghi kỳ, chỉ tiêu, nguồn và phần còn thiếu.	Chat đưa nhận định đúng công ty, kỳ và có nguồn kiểm tra được.	S5-WBS11.1, S5-WBS10.3															**

🟢 **	Sprint 5	S5-WBS12.1	S5-G08	2	Định dạng câu trả lời theo yêu cầu		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng danh sách cho liệt kê, bảng cho so sánh và tóm tắt cho tổng quan.	Câu trả lời có đúng cấu trúc người dùng yêu cầu.	S5-WBS09.2, S5-WBS09.3 cho ca nối tiếp															**

🟢 **	Sprint 5	S5-WBS12.2	S5-G08	2	Ghép bằng chứng graph và tài liệu cho BOTH		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ghép kết quả theo đúng mã công ty và kỳ, gắn citation sát nhận định.	Cả hai loại bằng chứng được dùng đúng phạm vi và nguồn.	S5-WBS05.2, nhánh Vector hiện có															**

🟢 **	Sprint 5	S5-WBS12.3	S5-G08	2	Xử lý kết quả rỗng, thiếu nguồn và lỗi một nhánh		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ trình bày phần có căn cứ, ghi rõ phần còn thiếu và thử ca fallback thất bại.	Câu trả lời phân biệt rỗng, thiếu bằng chứng và lỗi nhánh.	S5-WBS07.3, S5-WBS12.1, S5-WBS12.2															**

🟢 **	Sprint 5	S5-WBS13.1	S5-G09	2	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3															**

🟢 **	Sprint 5	S5-WBS13.2	S5-G09	2	Đánh giá router và fallback trên bộ câu riêng		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3															**

🟢 **	Sprint 5	S5-WBS13.3	S5-G09	2	Đối chiếu nhận định xu hướng và citation		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2															**

🟢 **	Sprint 5	S5-WBS13.4	S5-G09	2	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại		Chưa bắt đầu	2		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3															**

🟢 **					Tổng giờ các task			108	0																				**

🟢 **Sprint 5 Report**

🟢 **Sprint 5 Report							**

🟢 **Phạm vi (task)	38	Done hiện tại	0	Giờ dự kiến	108	Done thiếu ngày	0**

🟢 **Giờ thực tế		Bắt đầu	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	38		0	38	38		**

🟢 **Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	38	0	0	38	35.29		**

🟢 **Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	38				32.57		**

🟢 **Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	38				29.86		**

🟢 **Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	38				27.14		**

🟢 **Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	38				24.43		**

🟢 **Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	38				21.71		**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	38				19		**

🟢 **Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	38				16.29		**

🟢 **Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	38				13.57		**

🟢 **Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	38				10.86		**

🟢 **Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	38				8.14		**

🟢 **Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	38				5.43		**

🟢 **Sat Nov 21 2026 07:00:00 GMT+0700 (Indochina Time)	38				2.71		**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	38				0		**

🟢 **	Ngày, giờ và phân công là đề xuất. Tuần 1 và 2 tính từ thứ Hai bắt đầu sprint; chỉ làm khi đầu vào đã sẵn sàng.																												**

🟢 **	FinMind Sprint 6 Backlog																												**

🟢 **	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi																								**

🟢 **	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Ngày hoàn thành thực tế	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 28 2026 07:00:00 GMT+0700 (Indochi...**

🟢 **	Sprint 6	S6-WBS01	S6-G01	1	Kiểm tra bộ 80 ca đã khóa	Trần Diệu Huyền	Chưa bắt đầu	4		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu phiên bản, phân bổ ca và locators được reviewer duyệt. Runtime không được đọc đáp án chuẩn.	Có 80 ca final hợp lệ tách khỏi dữ liệu tuning.	Phiên bản bàn giao của sprint trước đã được duyệt.															**

🟢 **	Sprint 6	S6-WBS02	S6-G01	1	Kiểm tra manifest B0 B1 B2 B3	Trần Diệu Huyền	Chưa bắt đầu	5		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu code tag, corpus, model, prompt, threshold và evaluator đã chốt ở Sprint 5.	Bốn cấu hình được ghi rõ và không thay đổi giữa các ca.	Phiên bản bàn giao của sprint trước đã được duyệt.															**

🟢 **	Sprint 6	S6-WBS03	S6-G01	1	Tạo run ID và checkpoint hạ tầng	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thiết lập lưu trạng thái từng câu và cách chạy tiếp chỉ khi hạ tầng lỗi với manifest không đổi.	Có thể resume lỗi hạ tầng mà không thay cấu hình hoặc chọn lại kết quả.	Phiên bản bàn giao của sprint trước đã được duyệt.															**

🟢 **	Sprint 6	S6-WBS04	S6-G01	1	Kiểm tra cách ly nhãn và quyền evaluator	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ evaluator đọc gold labels; xác nhận API runtime không nhận đáp án chuẩn.	Không có nhãn final trong context hoặc log đầu vào generator.	Phiên bản bàn giao của sprint trước đã được duyệt.															**

🟢 **	Sprint 6	S6-WBS05	S6-G02	1	Chạy và lưu đầu ra B0	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy các câu bằng cấu hình structured control; ghi trả lời hoặc không trả lời và lý do.	Có kết quả từng câu của B0 với manifest và trace.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS06	S6-G02	1	Chạy và lưu đầu ra B1	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy vector RAG đúng tag, giữ output, citation, latency và token.	Không bật các thành phần chỉ thuộc B3 trong B1.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS07	S6-G02	1	Chạy và lưu đầu ra B2	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hybrid graph vector cùng corpus và bộ final; ghi nhánh graph và fusion.	Có đủ dữ liệu từng câu để đối chiếu với B1.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS08	S6-G02	1	Chạy và lưu đầu ra B3	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy cả Gate và verifier, kể cả nhánh sửa có giới hạn; ghi cả fallback hoặc partial.	Mỗi tag chỉ có lượt final hợp lệ theo policy, không chọn lượt đẹp nhất.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS09	S6-G03	1	Tính đúng số độ trung thực và citation	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng định nghĩa và phiên bản evaluator để tính quality metrics từ kết quả thực tế.	Mỗi điểm truy ra được output, gold và cách tính.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS10	S6-G03	1	Tính recall coverage và an toàn thiếu dữ liệu	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu theo hash và locator nguồn; kiểm tra cả số liệu bịa, missing-data và false refusal.	Có số đúng sai và mẫu lỗi cho từng chỉ số bắt buộc.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS11	S6-G03	1	So sánh theo loại câu ngành và ngôn ngữ	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tách kết quả B0 B3 theo nhóm và khoảng tin cậy theo protocol; không chỉ báo overall.	Bảng phân tích nêu số mẫu và nhóm không đủ kết luận.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS12	S6-G03	1	Đối chiếu Gate và giả thuyết nghiên cứu	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tách ngưỡng nghiệm thu khỏi giả thuyết và số chỉ để báo cáo; ghi các mục chưa đạt.	Không biến mục tiêu hoặc giả thuyết thành kết quả đã đo.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS13	S6-G04	1	Kiểm tra các ca số liệu và citation quan trọng	Thái Quốc Hưng	Chưa bắt đầu	6		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Rà thủ công các lỗi số liệu, citation và các nhóm phải audit theo SRS.	Có biên bản reviewer và giải quyết bất đồng.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS14	S6-G04	1	Chạy tải 10 yêu cầu đồng thời	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng môi trường và corpus đã ghi, đo latency từ nhận yêu cầu đến kết quả cuối.	Có cấu hình tải, máy chạy và raw latency của từng yêu cầu.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS15	S6-G04	1	Tính p95 và thời gian nhánh sửa	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tính p95 cho answered requests gồm controlled repair; báo riêng refusal và partial.	Bảng tốc độ không loại lượt sửa để làm đẹp số đo.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS16	S6-G04	1	Tổng hợp token và chi phí thực tế	Hồ Phạm Đăng Nhân	Chưa bắt đầu	2		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy token từng request theo mô hình và lần gọi; đối chiếu budget và lưu rate dùng để tính nếu có.	Báo cáo phân biệt token đo được và chi phí chưa xác định.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS17	S6-G05	2	Kiểm thử phân quyền và phiên hết hạn	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy cập sai vai trò, hết hạn phiên và dữ liệu của người khác với các API chính.	Không vượt quyền hoặc đọc lịch sử ngoài chính sách.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS18	S6-G05	2	Kiểm thử bí mật retention và log	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khóa API, dữ liệu nhạy cảm, chính sách xóa trace và lỗi subsystem.	Không lộ bí mật; thao tác xóa và review có vết kiểm tra được.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS19	S6-G05	2	Chạy lại luồng nghiệp vụ từ đầu đến cuối	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Thử tìm công ty, đặt câu hỏi, so sánh, mở nguồn và fallback trên bản bàn giao.	Có kết quả kiểm thử cho các luồng Must và ca lỗi chính.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS20	S6-G05	2	Hoàn thiện ma trận yêu cầu và test	Nguyễn Minh Quân	Chưa bắt đầu	4		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Liên kết từng FR NFR Must với test ID, kết quả và bằng chứng; ghi mục chưa đạt.	Không có yêu cầu Must chỉ đánh dấu đạt mà thiếu bằng chứng.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS21	S6-G06	2	Đóng gói Docker Compose	Nguyễn Minh Quân	Chưa bắt đầu	4		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Đóng gói frontend, API, PostgreSQL pgvector và Neo4j với cấu hình tài nguyên rõ ràng.	Khởi động được bộ dịch vụ trên môi trường được ghi.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS22	S6-G06	2	Viết migration và cấu hình triển khai mẫu	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị migration, biến môi trường mẫu không có secret và cách nạp corpus hợp lệ.	Người khác biết cần cấu hình gì mà không nhận khóa thật của nhóm.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS23	S6-G06	2	Thử cài trên môi trường sạch	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Triển khai theo hướng dẫn, không dùng file hoặc cấu hình ẩn chỉ có trên máy dev.	Có log cài sạch và danh sách bước cần sửa.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS24	S6-G06	2	Đóng gói manifest và dữ liệu đánh giá	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Lưu output từng câu, metrics, cấu hình và code tag để kiểm tra lại benchmark.	Gói đánh giá tái hiện được nguồn của từng kết quả trong phạm vi quyền lưu.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS25	S6-G07	2	Cập nhật SRS theo bản triển khai thực tế	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu chức năng Must đã làm, sơ đồ và ràng buộc với code tag bàn giao.	SRS không mô tả chức năng optional chưa triển khai như đã có.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS26	S6-G07	2	Viết hướng dẫn sử dụng và quản trị	Thái Quốc Hưng	Chưa bắt đầu	5		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Giải thích đăng nhập, tìm công ty, hỏi, mở nguồn; hướng dẫn nguồn, corpus, budgets và xử lý lỗi.	Người đọc làm theo được từng luồng cơ bản.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS27	S6-G07	2	Viết báo cáo kiểm thử và hạn chế	Trần Diệu Huyền	Chưa bắt đầu	4		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Tổng hợp kết quả, lỗi tồn, dữ liệu thiếu và giới hạn phạm vi; đính kèm vị trí bằng chứng.	Báo cáo nêu cả mục chưa đạt, không chỉ các ca thành công.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS28	S6-G07	2	Hoàn thiện form và khai báo AI thực tế	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Điền các form được cung cấp, khai báo công cụ AI và phần sử dụng dựa trên nhật ký thật.	Không tự tạo phần trăm sử dụng AI hoặc xác nhận khi chưa có dữ liệu.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS29	S6-G08	2	Soạn báo cáo nghiên cứu và slide kết quả	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Trình bày B0 B3, giả thuyết, metrics, mẫu lỗi và giới hạn bằng số đo thực tế.	Bảng trong báo cáo khớp gói đánh giá đã lưu.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS30	S6-G08	2	Chuẩn bị kịch bản demo các luồng chính	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Chọn ca hỏi số liệu, giải thích, quan hệ, so sánh và thiếu dữ liệu trên evaluated tag.	Demo dùng đúng phiên bản đã đánh giá, không thay cấu hình ngầm.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS31	S6-G08	2	Diễn tập demo và kiểm tra checklist	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Thử mở nguồn, fallback và khởi động dịch vụ; chuẩn bị cách giải thích khi hệ thống hoặc nguồn lỗi.	Nhóm biết thao tác và người phụ trách từng phần demo.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS32	S6-G08	2	Chốt hồ sơ nghiệm thu và bàn giao	Hồ Phạm Đăng Nhân	Chưa bắt đầu	2		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Bàn giao code tag, tài liệu, manifests và danh sách lỗi tồn; ghi quyết định đạt hoặc chưa đạt.	Có danh mục bàn giao và người nhận xác nhận các phần thực tế đã có.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.															**

🟢 **	Sprint 6	S6-WBS33	S6-G09	1	Kiểm tra tính đầy đủ của raw benchmark	Thái Quốc Hưng	Chưa bắt đầu	5		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Rà số ca, trace và output của từng cấu hình; chỉ resume lỗi hạ tầng theo policy.	Không mất ca hoặc xuất bản aggregate khi thiếu trace.	Các task chức năng liên quan có đầu ra để kiểm tra.															**

🟢 **	Sprint 6	S6-WBS34	S6-G09	1	Sửa lỗi công cụ đánh giá và đóng gói	Trần Diệu Huyền	Chưa bắt đầu	6		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Sửa lỗi hạ tầng hoặc pipeline báo cáo; thay đổi sau final phải ghi exploratory nếu làm đổi tag.	Không thay kết quả final cũ bằng một lượt chạy tùy chọn.	Các task chức năng liên quan có đầu ra để kiểm tra.															**

🟢 **	Sprint 6	S6-WBS35	S6-G09	2	Sửa lỗi bàn giao và kiểm thử hồi quy	Trần Diệu Huyền	Chưa bắt đầu	5		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Ưu tiên lỗi triển khai, quyền và mất nguồn; ghi tag sửa sau final và phạm vi kiểm tra lại.	Lỗi đã đóng có test lại và khác biệt so với evaluated tag được công bố.	Các task chức năng liên quan có đầu ra để kiểm tra.															**

🟢 **	Sprint 6	S6-WBS36	S6-G09	2	Review cuối với nhóm và mentor	Thái Quốc Hưng	Chưa bắt đầu	6		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra Gates, tài liệu, demo và lỗi tồn trước khi xác nhận dự án hoàn tất.	Có quyết định nghiệm thu dựa trên bằng chứng, không chỉ dựa vào phần trăm task.	Các task chức năng liên quan có đầu ra để kiểm tra.															**

🟢 **					Tổng giờ các task			150	0																				**

🟢 **Sprint 6 Report**

🟢 **Sprint 6 Report							**

🟢 **Phạm vi (task)	36	Done hiện tại	0	Giờ dự kiến	150	Done thiếu ngày	0**

🟢 **Giờ thực tế		Bắt đầu	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kết thúc	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	Done sau sprint	0**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	36				36		**

🟢 **Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	36				33.43		**

🟢 **Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	36				30.86		**

🟢 **Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	36				28.29		**

🟢 **Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	36				25.71		**

🟢 **Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	36				23.14		**

🟢 **Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	36				20.57		**

🟢 **Sun Nov 29 2026 07:00:00 GMT+0700 (Indochina Time)	36				18		**

🟢 **Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	36				15.43		**

🟢 **Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	36				12.86		**

🟢 **Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	36				10.29		**

🟢 **Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	36				7.71		**

🟢 **Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	36				5.14		**

🟢 **Sat Dec 05 2026 07:00:00 GMT+0700 (Indochina Time)	36				2.57		**

🟢 **Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)	36				0		**

~~	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																															~~

~~	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																															~~

~~	Giữ nguyên 42 task, trạng thái, người phụ trách và giờ đã nhập. Trước 14/09 được ghi là Khởi động.																															~~

~~	FinMind Sprint 1 Backlog																															~~

~~	Số task	42	Giờ dự kiến	146	Tổng giờ thực tế đã ghi	163																										~~

~~	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Sep 11 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Sep 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 13 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 16 2026...~~

~~	Sprint 1	S1-T01	M01	Khởi động	Xác định các nhóm người dùng chính	Thái Quốc Hưng	Đã hoàn thành	1	1	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định nhà đầu tư, chuyên viên phân tích và quản trị dữ liệu cùng nhu cầu chính của từng nhóm.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.	1																	~~

~~	Sprint 1	S1-T02	M01	Khởi động	Chốt phạm vi và giới hạn của bản MVP	Thái Quốc Hưng	Đã hoàn thành	3	4	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định chức năng thuộc MVP, phần mở rộng và các nội dung nằm ngoài phạm vi dự án.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.	2	1					1											~~

~~	Sprint 1	S1-T03	M01	Khởi động	Lập danh sách chức năng theo thứ tự ưu tiên	Thái Quốc Hưng	Đã hoàn thành	4	7	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Phân loại chức năng bắt buộc, nên có và có thể thực hiện ở giai đoạn sau.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.		3	1				2	1										~~

~~	Sprint 1	S1-T04	M01	Khởi động	Soạn bộ câu hỏi nghiên cứu và khảo sát	Trần Diệu Huyền	Đã hoàn thành	2	3	Thu Sep 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị câu hỏi để tìm hiểu khó khăn, nhu cầu và kỳ vọng của người dùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.	3																	~~

~~	Sprint 1	S1-T05	M01	1	Thực hiện nghiên cứu và tổng hợp kết quả	Thái Quốc Hưng	Đã hoàn thành	4	4	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Thực hiện khảo sát hoặc phỏng vấn và tổng hợp các phát hiện quan trọng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.					3	1												~~

~~	Sprint 1	S1-T06	M01	1	Kiểm tra lại phạm vi và thống nhất	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kết quả nghiên cứu với phạm vi MVP và ghi nhận quyết định cuối cùng.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.		3			3													~~

~~	Sprint 1	S1-T07	M02	1	Lập danh sách nguồn dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo danh sách nguồn, loại tài liệu, đơn vị phát hành, đường dẫn và phạm vi dữ liệu cần thu thập.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.						3												~~

~~	Sprint 1	S1-T08	M02	1	Tìm nguồn chính thức cho 5 công ty Ngân hàng	Nguyễn Minh Quân	Đã hoàn thành	3	2	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tìm trang quan hệ cổ đông, báo cáo tài chính và công bố thông tin chính thức.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.					2													~~

~~	Sprint 1	S1-T09	M02	1	Tìm nguồn chính thức cho 5 công ty Công nghệ	Nguyễn Minh Quân	Đã hoàn thành	3	2	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tìm trang quan hệ cổ đông, báo cáo tài chính và công bố thông tin chính thức.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.						2												~~

~~	Sprint 1	S1-T10	M02	1	Kiểm tra điều kiện truy cập và sử dụng dữ liệu	Trần Diệu Huyền	Đã hoàn thành	2	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khả năng truy cập, lưu trữ, xử lý và trích dẫn dữ liệu trong hệ thống.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.							3											~~

~~	Sprint 1	S1-T11	M02	1	Xây dựng quy tắc kiểm tra và chốt bộ dữ liệu	Trần Diệu Huyền	Đã hoàn thành	4	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định cách kiểm tra công ty, kỳ báo cáo, đơn vị, phiên bản và tài liệu trùng lặp.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.								3										~~

~~	Sprint 1	S1-T12	M02	1	Xác định nguồn dự phòng và đánh giá tính khả thi	Trần Diệu Huyền	Đã hoàn thành	3	3	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị nguồn thay thế và đánh giá rủi ro khi nguồn chính thay đổi hoặc không truy cập được.	Cần xác nhận nhóm đã làm, bỏ hay chuyển sang sprint khác.	Giữ kế hoạch Sprint 1 đã nhập.									3									~~

~~	Sprint 1	S1-T13	M03	1	Rà soát SRS và danh mục use case	Trần Diệu Huyền	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu UC01–UC24 với FR/NFR, business rules và phạm vi MVP; thống nhất tên, mã và điều kiện.	Có bảng đối chiếu UC–FR/NFR đã rà.	Giữ kế hoạch Sprint 1 đã nhập.												3	3					~~

~~	Sprint 1	S1-T14	M03	1	Vẽ context và business function diagram	Đinh Huỳnh Vũ	Đã hoàn thành	5	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thể hiện tác nhân, hệ thống ngoài và phân rã chức năng; đối chiếu nội dung với SRS.	Có context và business function diagram khớp SRS.	Giữ kế hoạch Sprint 1 đã nhập.																		~~

~~	Sprint 1	S1-T15	M03	1	Vẽ activity diagram theo use case	Thái Quốc Hưng	Đã hoàn thành	8	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Mô tả luồng chính, nhánh thay thế và ngoại lệ; kiểm tra node bắt đầu/kết thúc và lưu hình cùng draw.io.	Có activity diagrams và file chỉnh sửa được.	Giữ kế hoạch Sprint 1 đã nhập.									2			3	1					~~

~~	Sprint 1	S1-T16	M03	1	Vẽ sequence diagram theo use case	Đinh Huỳnh Vũ	Đã hoàn thành	8	6	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thể hiện actor, giao diện, dịch vụ và kho dữ liệu; thông điệp phải khớp kịch bản của từng use case.	Có sequence diagrams theo use case.	Giữ kế hoạch Sprint 1 đã nhập.					3	3												~~

~~	Sprint 1	S1-T17	M03	1	Vẽ state diagram cho đối tượng có vòng đời	Thái Quốc Hưng	Đã hoàn thành	6	5	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Gom các use case liên quan; xác định trạng thái, sự kiện, điều kiện chuyển và điểm kết thúc.	Có state diagrams cho vòng đời cần mô tả.	Giữ kế hoạch Sprint 1 đã nhập.													2	3				~~

~~	Sprint 1	S1-T18	M03	1	Rà soát tính nhất quán SRS	Trần Diệu Huyền	Đã hoàn thành	4	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Đặt đúng số mục, tên hình; kiểm tra mã UC, FR/NFR và sự nhất quán giữa đặc tả với các sơ đồ.	SRS có đúng hình, số mục và mã tham chiếu.	Giữ kế hoạch Sprint 1 đã nhập.														3				~~

~~	Sprint 1	S1-T19	M04	1	Chia pipeline dữ liệu thành các phần nhỏ	Nguyễn Minh Quân	Đã hoàn thành	4	5	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tách thu thập, chuẩn hóa, chunk/embedding, graph, truy vấn vector/graph và ranh giới đầu vào/đầu ra.	Có bản đồ các bước xử lý dữ liệu và đầu vào/đầu ra.	Giữ kế hoạch Sprint 1 đã nhập.							3	2										~~

~~	Sprint 1	S1-T20	M04	1	Đặc tả nguồn và cách cào dữ liệu mẫu	Nguyễn Minh Quân	Đã hoàn thành	2	2	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chọn nguồn được phép dùng; ghi URL, loại tài liệu, lịch lấy, phiên bản và điều kiện truy cập.	Có danh sách nguồn được phép dùng và cách lấy.	Giữ kế hoạch Sprint 1 đã nhập.								1	1									~~

~~	Sprint 1	S1-T21	M04	1	Đặc tả chuẩn hóa và định danh dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Sun Sep 20 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định company ID, kỳ báo cáo, đơn vị, source ID, document hash và quy tắc kiểm tra trước khi lập chỉ mục.	Có quy tắc chuẩn hóa ID, kỳ, đơn vị, nguồn.	Giữ kế hoạch Sprint 1 đã nhập.															3			~~

~~	Sprint 1	S1-T22	M04	2	Vẽ ERD dữ liệu nghiệp vụ PostgreSQL	Nguyễn Minh Quân	Đã hoàn thành	4	4	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thiết kế công ty, tài liệu, nguồn, dữ kiện tài chính, khóa chính/ngoại và quan hệ truy vết.	Có ERD PostgreSQL cho dữ liệu nghiệp vụ.	Giữ kế hoạch Sprint 1 đã nhập.									2			2						~~

~~	Sprint 1	S1-T23	M04	2	Vẽ lược đồ bảng chunk/embedding pgvector	Đinh Huỳnh Vũ	Đã hoàn thành	3	4	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định chunk, embedding, vector dimension, metadata, source locator và liên kết với PostgreSQL.	Có lược đồ chunk/embedding của pgvector.	Giữ kế hoạch Sprint 1 đã nhập.							3	1										~~

~~	Sprint 1	S1-T24	M04	1	Vẽ mô hình node–edge Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	6	Mon Sep 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn node, kiểu quan hệ, thuộc tính và provenance cho từng edge; giới hạn truy vấn hai hop.	Có mô hình node–edge Neo4j kèm provenance.	Giữ kế hoạch Sprint 1 đã nhập.					3	1			2									~~

~~	Sprint 1	S1-T25	M04	2	Đối chiếu ID giữa các mô hình dữ liệu	Trần Diệu Huyền	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra ánh xạ company/source/document/chunk ID và provenance để truy vấn có thể quay về bằng chứng gốc.	Có quy tắc ánh xạ ID giữa các mô hình.	Giữ kế hoạch Sprint 1 đã nhập.																3		~~

~~	Sprint 1	S1-T26	M05	2	Cào bộ tài liệu mẫu theo nguồn đã chọn	Nguyễn Minh Quân	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy PoC trên vài tài liệu trong phạm vi corpus; lưu tệp gốc và nhật ký URL/thời điểm.	Có bộ tài liệu mẫu và nhật ký lấy dữ liệu.	Giữ kế hoạch Sprint 1 đã nhập.												1	2					~~

~~	Sprint 1	S1-T27	M05	2	Ghi hash, phiên bản và metadata nguồn	Nguyễn Minh Quân	Đã hoàn thành	2	2	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Lưu checksum, ngày công bố, công ty, kỳ báo cáo và trạng thái trùng lặp của tài liệu mẫu.	Có checksum, phiên bản, metadata của mẫu.	Giữ kế hoạch Sprint 1 đã nhập.													1	1				~~

~~	Sprint 1	S1-T28	M05	2	Parse và chuẩn hóa tài liệu mẫu	Đinh Huỳnh Vũ	Đã hoàn thành	3	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Trích văn bản/bảng, chuẩn hóa ticker, kỳ, đơn vị và đánh dấu bản ghi lỗi để không đưa vào index.	Có dữ liệu mẫu chuẩn hóa, lỗi được cách ly.	Giữ kế hoạch Sprint 1 đã nhập.									3			3						~~

~~	Sprint 1	S1-T29	M05	1	Tạo thử truy vấn quan hệ bằng Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	6	8	Wed Sep 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Viết và chạy thử truy vấn quan hệ trên dữ liệu mẫu trong Neo4j.	Truy vấn chạy được và kết quả quan hệ được đối chiếu với dữ liệu mẫu.	Giữ kế hoạch Sprint 1 đã nhập.							3	3	1					1				~~

~~	Sprint 1	S1-T30	M05	2	Tạo embedding và nạp mẫu vào pgvector	Đinh Huỳnh Vũ	Đã hoàn thành	3	4	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vector hóa chunk hợp lệ; ghi model/version, dimension và khóa liên kết về tài liệu gốc.	Có embedding mẫu trong pgvector.	Giữ kế hoạch Sprint 1 đã nhập.													3	1				~~

~~	Sprint 1	S1-T31	M05	2	Truy vấn pgvector để kiểm thử	Đinh Huỳnh Vũ	Đã hoàn thành	3	6	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng câu hỏi mẫu để kiểm tra top-k, khoảng cách vector và khả năng truy về đúng đoạn nguồn.	Có kết quả tìm vector theo câu hỏi mẫu.	Giữ kế hoạch Sprint 1 đã nhập.															3	3		~~

~~	Sprint 1	S1-T32	M06	1	Trích xuất entity cho graph mẫu	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	2	Tue Sep 15 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện công ty, chỉ số, tài liệu, kỳ và sự kiện; ánh xạ entity ID ổn định.	Có danh sách thực thể graph có ID.	Giữ kế hoạch Sprint 1 đã nhập.						2												~~

~~	Sprint 1	S1-T33	M06	2	Trích xuất quan hệ và provenance cho edge	Hồ Phạm Đăng Nhân	Đã hoàn thành	2	5	Mon Sep 21 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xác định quan hệ có bằng chứng, hướng edge và source locator; không tạo cạnh suy đoán.	Có edge chỉ tạo từ bằng chứng hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.												2		2	1			~~

~~	Sprint 1	S1-T34	M06	2	Nạp node và edge mẫu vào Neo4j	Hồ Phạm Đăng Nhân	Đã hoàn thành	3	3	Tue Sep 22 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo graph thử nghiệm, kiểm tra ràng buộc ID và liên kết mỗi edge với nguồn.	Có graph mẫu trong Neo4j.	Giữ kế hoạch Sprint 1 đã nhập.												1			2			~~

~~	Sprint 1	S1-T35	M06	2	Truy vấn Neo4j để kiểm thử	Hồ Phạm Đăng Nhân	Đã hoàn thành	3	3	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy vấn một hoặc hai bước theo công ty và quan hệ; kiểm tra kết quả cùng provenance.	Có kết quả truy vấn graph kèm nguồn.	Giữ kế hoạch Sprint 1 đã nhập.													3					~~

~~	Sprint 1	S1-T36	M06	2	Truy vấn dữ kiện PostgreSQL để đối chiếu	Nguyễn Minh Quân	Đã hoàn thành	3	2	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy số liệu mẫu theo công ty, chỉ số, kỳ và đơn vị; so với bản ghi nguồn đã chuẩn hóa.	Có kết quả số liệu PostgreSQL để đối chiếu.	Giữ kế hoạch Sprint 1 đã nhập.														2				~~

~~	Sprint 1	S1-T37	M06	2	Tổng hợp kết quả cào và cập nhật SRS	Nguyễn Minh Quân	Đã hoàn thành	2	1	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Ghi truy vấn, kết quả đúng/sai, lỗi và giới hạn; sửa lược đồ/đặc tả nếu bằng chứng thử nghiệm yêu cầu.	Có báo cáo PoC và các điểm cần sửa trong SRS.	Giữ kế hoạch Sprint 1 đã nhập.															1			~~

~~	Sprint 1	S1-T38	M04	2	Tạo Git repository và cấu trúc dự án ban đầu	Nguyễn Minh Quân	Đã hoàn thành	1	1	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo kho mã nguồn Git và các thư mục ban đầu để cả nhóm lưu, chia sẻ và quản lý phiên bản mã.	Repository truy cập được; cấu trúc thư mục và hướng dẫn khởi động được lưu.	Giữ kế hoạch Sprint 1 đã nhập.															1			~~

~~	Sprint 1	S1-T39	M03	1	Chuẩn bị Golden Test Set phiên bản đầu tiên	Thái Quốc Hưng	Đã hoàn thành	4	4	Fri Sep 18 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Soạn bộ câu hỏi kiểm thử ban đầu, đáp án tham chiếu và thông tin nguồn để kiểm tra kết quả trả lời.	Có danh sách câu hỏi, đáp án và nguồn đối chiếu; chưa coi đây là bộ test cuối đã khóa.	Giữ kế hoạch Sprint 1 đã nhập.															3	1		~~

~~	Sprint 1	S1-T40	M03	2	Vẽ usecase diagram cho từng đặc tả use case	Hồ Phạm Đăng Nhân	Đã hoàn thành	4	6	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case riêng cho từng đặc tả, thể hiện người sử dụng và chức năng liên quan.	Các sơ đồ khớp actor, tên chức năng và mã use case trong SRS.	File gốc có công thức cộng giờ các task khác trong dòng này. Cần kiểm tra để tránh tính trùng.																3	3	~~

~~	Sprint 1	S1-T41	M03	2	Vẽ usecase Diagram tổng	Trần Diệu Huyền	Đã hoàn thành	5	3	Fri Sep 25 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Vẽ sơ đồ use case tổng để thể hiện toàn bộ chức năng và các nhóm người dùng của FinMind.	Sơ đồ tổng khớp danh mục use case và phạm vi SRS.	Giữ kế hoạch Sprint 1 đã nhập.																3		~~

~~	Sprint 1	S1-T42	M05	2	Xây dựng module chuẩn hóa dữ liệu & khử lỗi	Nguyễn Minh Quân	Đã hoàn thành	4	4	Sat Sep 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Sep 27 2026 07:00:00 GMT+0700 (Indochina Time)	Xây dựng phần xử lý dữ liệu mẫu để thống nhất định dạng và xử lý giá trị số không hợp lệ.	Có module, dữ liệu trước/sau xử lý và kết quả kiểm thử các trường hợp số không hợp lệ.	Giữ kế hoạch Sprint 1 đã nhập.															1	3		~~

~~					Tổng giờ các task			146	163																							~~

~~					Giờ dự kiến theo ngày (cả nhóm)				146						4	4			13	15	15	15	13			13	15	15	13	11		~~

~~					Giờ thực tế theo ngày (tự tính)				157						6	7	1	0	14	12	15	11	14	0	0	15	15	13	15	16	3	0~~

~~Sprint 1 Reports~~

~~	FinMind Sprint 1 Reports	~~

~~	Dữ liệu báo cáo Sprint 1	~~

~~	Số task trong Sprint 1	42~~

~~	Task đã hoàn thành	42~~

~~	Giờ dự kiến	146~~

~~	Giờ thực tế đã ghi	163~~

~~	Biểu đồ burn-down/burn-up cần giờ làm thực tế theo ngày; hiện chưa có dữ liệu được nhóm xác nhận.	~~

~~	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																											~~

~~	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																											~~

~~	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																											~~

~~	Sprint 2 có hai đầu ra UI riêng: file thiết kế chỉnh sửa được và frontend source chạy với mock. Huyền lead UI, thiết kế luồng/visual và review; Nhân thiết kế wireframe, bàn giao hai mốc có duyệt để Vũ làm prototype song song. Giờ review ở WBS24 và WBS32, không cộng hai lần. Chỉ đánh dấu task hoàn thành khi đủ toàn bộ đầu ra; mốc trung gian không phải hoàn thành task.																											~~

~~Hưng/Quân: cào, chuẩn hóa, PostgreSQL. Vũ/Nhân/Huyền: thiết kế, prototype, code mock. Giờ thực tế chỉ nhập khi đã làm.																											~~

~~	FinMind Sprint 2 Backlog																											~~

~~	Số task	28	Giờ dự kiến	141	Tổng giờ thực tế đã ghi	122																						~~

~~	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 04 2026...~~

~~	Sprint 2	S2-WBS01	S2-G01	1	Chốt hợp đồng dữ liệu đầu vào/đầu ra	Nguyễn Minh Quân	Đã hoàn thành	3	4	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Rà soát giá, tỷ số, KQKD, CĐKT, LCTT; chốt schema raw/normalized; phân biệt quý/năm.	Có schema thống nhất raw/normalized; JSON UTF-8 hợp lệ; xử lý an toàn NaN/null.	ERD Sprint 1; mẫu payload API; danh sách 10 mã.	1	3												~~

~~Kết quả cần có: Có mẫu bản ghi và trường bắt buộc; phân biệt 0 với thiếu dữ liệu. UI và người làm DB dùng cùng tên trường.	Thái Quốc Hưng	Đã hoàn thành	2	1	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 03 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng ERD Sprint 1 để chốt company\_id, loại nguồn, URL, ngày công bố/lấy, hash, phiên bản, kỳ, đơn vị và vị trí nguồn. Thống nhất mẫu facts và News với UI; không vẽ lại ERD từ đầu.	Có mẫu bản ghi và trường bắt buộc; phân biệt 0 với thiếu dữ li...~~

~~	Sprint 2	S2-WBS03	S2-G02	1	Làm ổn định bộ thu thập dữ liệu (Collector)	Nguyễn Minh Quân	Đã hoàn thành	5	6	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy collector cào 10 mã (5 Bank + 5 Tech); bổ sung retry, timeout, cô lập lỗi từng mã để không dừng pipeline	Collector chạy ổn định 10 mã; log lỗi độc lập; có CLI chạy lại từng mã.	Schema raw; endpoint API; danh sách 10 mã (5 Bank + 5 Tech).			4	2										~~

~~Kết quả cần có: Lấy đúng bài mẫu và nguồn gốc; có retry/log và lý do loại bài. Bộ cào chỉ hỗ trợ danh sách nguồn đã chốt.	Thái Quốc Hưng	Đã hoàn thành	5	7	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tái dùng khung crawler chung, cấu hình các nguồn News được duyệt. Lấy danh sách/nội dung trong khoảng ngày, xử lý phân trang, lọc công ty và lưu URL/ngày/hash/version. Không làm crawler tổng quát cho mọi website hoặc vượt paywall.	Lấy đúng bài...~~

~~	Sprint 2	S2-WBS05	S2-G02	1	Chuẩn hóa dữ liệu số & Bảo toàn dữ liệu nguồn	Nguyễn Minh Quân	Đã hoàn thành	6	7	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	File raw JSON thu được từ Collector; quy tắc ép kiểu dữ liệu và chuẩn hóa kỳ báo cáo.	Chuẩn hóa key kỳ, ép kiểu số liệu; giữ nguyên bản raw; giữ nguyên key lạ chưa xác minh; tách biệt đơn vị VND, %, EPS.	Dữ liệu normalized truy ngược được về raw; không tự đoán hoặc làm mất key nguồn.					...~~

~~	Sprint 2	S2-WBS06	S2-G03	1	Xây dựng bộ OCR Router bóc tách PDF 	Nguyễn Minh Quân	Đã hoàn thành	6	6	Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Kho file PDF BCTC/BCTN mẫu đã tải từ Sprint 1; công cụ hệ thống (pdftotext, pdftoppm, tesseract tiếng Việt).	Tuyến text\_layer chạy tức thì; trang scan có text và toạ độ BBox.	Tuyến text\_layer chạy tức thì; trang scan có text và toạ độ BBox từ Tesseract.				2	4									~~

~~	Sprint 2	S2-WBS07	S2-G03	2	Tích hợp LLM Vision xử lý bảng scan	Nguyễn Minh Quân	Đã hoàn thành	7	8	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Ảnh PNG render từ các trang scan/bảng phức tạp; API Key Gemini và OpenRouter; JSON Schema yêu cầu.	Gọi Gemini 3.8 Flash ép JSON trích xuất bảng Markdown; thêm OpenRouter fallback; cache SHA-256; chặn rate limit 429.	LLM đọc nguyên văn bảng biểu, con dấu \[stamp\] cho các trang scan khó.										4	4	...~~

~~Kết quả cần có: News đúng khoảng ngày và công ty, giữ URL/nội dung gốc; không gộp hai bài khác chỉ vì cùng tiêu đề. Bài thiếu ngày/công ty rõ ràng được cách ly.	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng quy tắc lọc đã chốt để làm sạch nội dung, chuẩn ngày và gắn công ty có bằng chứng. So URL/hash để liên kết bản trùng hoặc đăng lại; giữ bài gốc. Không thêm phân tích cảm xúc hay tóm tắt AI trong Spri...~~

~~Kết quả cần có: Migration chạy trên DB mới, khóa ngoại đúng và lưu/đọc được ba loại nguồn với locator. Có hướng dẫn chạy, không lưu secrets trong source.	Thái Quốc Hưng	Đã hoàn thành	7	6	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Triển khai ERD đã có cho source/document/version/facts/News/Evidence; tái dùng script nạp mẫu. Tạo khóa và ràng buộc, thử một luồng lưu/đọc từ dữ liệu chuẩn về bản gốc. Chưa làm embedding, graph hay API nghiệp v...~~

~~Kết quả cần có: Mẫu đúng được nhận, mẫu sai bị cách ly và không vào corpus hợp lệ. Bản sửa phải kiểm lại; thiếu bản gốc không được cho qua.	Thái Quốc Hưng	Đã hoàn thành	3	3	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Gắn kiểm tra vào pipeline nạp: ID, ngày/kỳ, đơn vị, scope, nguồn, hash và locator. Dùng bảng/file quarantine đơn giản có reason code, chưa làm màn hình hay công cụ sửa dữ liệu thật. Sửa lỗi và chạy lại kiểm tra trong chính ta...~~

~~Kết quả cần có: Dữ liệu được nạp đều qua validation. Có bảng độ phủ, mẫu đối chiếu và lỗi đã xử lý; nguồn bắt buộc còn thiếu thì không nghiệm thu data hoàn thành.	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy script nạp, đối chiếu số item với danh sách bắt buộc và audit nội dung/số theo mẫu kiểm đã duyệt. Kiểm liên kết về nguồn, tổng hợp thiếu/lỗi theo công ty và kỳ; review data và kiểm lại lỗi nằm tron...~~

~~	Sprint 2	S2-WBS12	S2-G09	2	Đối soát chéo số liệu (Cross-check) chống sai lệch	Nguyễn Minh Quân	Đã hoàn thành	4	4	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Bản text OCR từ Tesseract và bản text Markdown từ LLM của cùng một trang PDF.	Đối soát số giữa Tesseract và LLM (numberAgreement); gắn cờ NUMBERS\_UNVERIFIED cho trang BCTC lệch số; escalate model.	Loại bỏ rủi ro AI đọc sai số; gắn nhãn trạng thái OK/REVIEW trên từng trang.											...~~

~~Kết quả cần có: Có file sơ đồ luồng/sitemap chỉnh sửa được, liệt kê đủ màn hình, quyền và đường quay lại; nhóm duyệt trước khi thiết kế wireframe.	Trần Diệu Huyền	Đã hoàn thành	2		Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Sep 28 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền làm lead UI, đối chiếu use case MVP để vẽ sơ đồ màn hình theo vai trò và luồng đăng nhập, chọn công ty, hỏi, xem nguồn, history/watchlist. Chỉ vẽ luồng cần code Sprint 2, không thêm xuất PDF/Markdown.	Có file sơ ...~~

~~Kết quả cần có: Mốc 1 và mốc 2 đều có link/file wireframe chỉnh sửa được và ý kiến duyệt của Huyền. Chỉ đánh dấu hoàn thành WBS18 khi đủ toàn bộ màn hình MVP và các lỗi điều hướng chặn đã sửa; bàn giao một mốc không đồng nghĩa hoàn thành cả task.	Hồ Phạm Đăng Nhân	Đã hoàn thành	5	10	Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Nhân dùng sitemap đã duyệt để vẽ wireframe chỉnh sửa được và bàn giao theo hai mốc: mốc 1 (29/09) gồm chọn công ty...~~

~~Kết quả cần có: Có file thiết kế chỉnh sửa được gồm style, component mẫu và các trạng thái; nhóm xác nhận tính nhất quán với wireframe.	Trần Diệu Huyền	Đã hoàn thành	4		Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền chốt màu, chữ, khoảng cách, bảng, form, nút, citation marker và các trạng thái loading/empty/error/missing-data từ sitemap đã duyệt và bộ component sẵn có. Có thể làm quy tắc chung song song với wireframe của Nhân; áp dụng ...~~

~~Kết quả cần có: Có link/file prototype bấm thử cho đầy đủ màn hình và trạng thái lỗi mẫu, khớp cả hai mốc wireframe/visual; Huyền review và Vũ sửa lỗi chặn. Prototype mốc 1 chỉ là bàn giao trung gian, chưa được tính hoàn thành WBS20.	Đinh Huỳnh Vũ	Đã hoàn thành	7	10	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Vũ dựng prototype từng màn hình ngay sau khi wireframe mốc tương ứng được Huyền duyệt và có visual áp dụng; làm trước luồng chọn cô...~~

~~Kết quả cần có: Source clone/cài/chạy/build được theo README; khung trang hoạt động, không có secrets; layout cuối khớp màn hình đã duyệt.	Đinh Huỳnh Vũ	Đã hoàn thành	6	3	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Vũ dựng project frontend, lệnh chạy/build, cấu hình môi trường và mock adapter từ repository Sprint 1 trước khi nhận đủ wireframe. Chỉ ghép menu/layout của từng màn hình sau khi wireframe và visual mốc đó được duyệt; giữ chỗ rõ...~~

~~Kết quả cần có: Component tái sử dụng và mock tách riêng, có trạng thái đủ/rỗng/lỗi và hướng dẫn đổi API; tích hợp được với các màn hình đã duyệt.	Hồ Phạm Đăng Nhân	Đã hoàn thành	8	7	Wed Sep 30 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Nhân cấu hình bảng/form/nút/filter/modal và fixture đủ/rỗng/lỗi từ schema chung, quy tắc visual đã có. Có thể làm component và mock độc lập trong khi hoàn thiện wireframe; tích hợp theo từng màn hình được duyệt với ...~~

~~Kết quả cần có: Routes và trạng thái truy cập hoạt động với mock, các phần cần API thật được liệt kê. Có smoke test điều hướng tuần 1.	Trần Diệu Huyền	Đã hoàn thành	5		Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền dùng router chung để nối màn hình, code form login/logout, phiên hết hạn và vai trò mẫu. Có thể chuẩn bị route map và phiên mẫu từ sitemap trong khi Nhân làm wireframe; chỉ ghép layout và smoke test điều hướng khi skeleton/c...~~

~~Kết quả cần có: Có checklist duyệt từng mốc wireframe, review prototype, danh sách lỗi chặn và bộ file thiết kế/API mock bàn giao; chỉ chốt khi đủ hai mốc.	Trần Diệu Huyền	Đã hoàn thành	4		Tue Sep 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 02 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền review từng mốc wireframe của Nhân ngay khi bàn giao, ghi rõ màn hình đã duyệt/chờ sửa và bàn giao cho Vũ bắt đầu prototype phần tương ứng. Sau đó review prototype đầy đủ so với sitemap, wireframe, visua...~~

~~Kết quả cần có: Màn hình code chạy được, đủ trạng thái chính và nhãn nguồn/đơn vị/ngày; không chỉ bàn giao ảnh thiết kế.	Hồ Phạm Đăng Nhân	Đã hoàn thành	7	7	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng bảng/filter/card chung để hiển thị 10 mã, kỳ, profile/facts/News và nguồn. Đổi company/period cập nhật fixture; nếu panel thị trường có trong scope ghi mock/EOD, không live. Không tích hợp nguồn hay API thị trường mới.	Màn hình code chạ...~~

~~Kết quả cần có: Các luồng đã chốt chạy với mock và nhãn rõ; filter/payload đúng, kết quả chờ/lỗi/thiếu không bị hiển thị như verified.	Trần Diệu Huyền	Đã hoàn thành	6		Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng form, chat/result và bảng chung để nhập câu hỏi, chọn công ty/kỳ, xem response/so sánh mẫu. Thêm partial/insufficient-data/refusal và retry; không làm streaming tùy biến, backend RAG hoặc tư vấn đầu tư.	Các luồng đã chốt chạy...~~

~~Kết quả cần có: Các luồng MVP chạy được với mock, không trùng watchlist và không mở URL client tùy ý. Không có xuất PDF/Markdown; thiếu API thật được ghi rõ.	Trần Diệu Huyền	Đã hoàn thành	6		Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tái dùng modal/detail/list/form để mở citation ID, xem locator/fact/provenance, xem/xóa history, pin/unpin và feedback. Chỉ mô phỏng lưu theo user, chưa xây backend lưu trữ; xác nhận thao tác xóa và thử lỗi ...~~

~~Kết quả cần có: Viewer thao tác được và mở đúng provenance mẫu; thử graph rỗng/lỗi, chặn hơn hai hop. Backend sẽ kiểm giới hạn khi nối thật.	Hồ Phạm Đăng Nhân	Đã hoàn thành	7	6	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng component/thư viện graph đã chọn, nạp fixture node/edge, chọn root, mở rộng tối đa hai hop và xem nguồn edge. Không tự viết thuật toán layout, animation hoặc Neo4j API trong task này.	Viewer thao tác được và mở đúng ...~~

~~Kết quả cần có: Các màn hình operator trong checklist chạy với mock, có counts/reason/refresh-time và trạng thái lỗi; không lộ secrets.	Đinh Huỳnh Vũ	Đã hoàn thành	5	4	Mon Oct 05 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng chung bảng/list/detail/form cho source, runs/counts/retries và quarantine. Đổi cấu hình/fixture theo trang thay vì viết một hệ thống quản trị riêng; thao tác quan trọng có xác nhận. Không gọi bộ cào thật từ mock UI.	Các màn h...~~

~~Kết quả cần có: Trang có đủ luồng MVP và trạng thái không đủ điều kiện/lỗi với mock, hợp đồng API thật được liệt kê.	Đinh Huỳnh Vũ	Đã hoàn thành	4	6	Wed Oct 07 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng lại trang quản trị của task trước, thay schema/form/fixture cho manifest/promote/restore, ngưỡng/budget và trace. Kiểm giá trị và readiness mẫu, không làm backend quản lý cấu hình/audit hoặc telemetry thật.	Trang có đủ luồng MVP và trạng thái k...~~

~~Kết quả cần có: Màn hình evaluator trong checklist thao tác được, phân biệt partial/completed/thiếu trace và không hiển thị điểm giả như kết quả thật.	Đinh Huỳnh Vũ	Đã hoàn thành	5	5	Thu Oct 08 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng bảng/form/detail chung để nhập/review/freeze ca mẫu, chọn B0–B3 và xem run/metrics fixture. Thêm calibration/final và quyền mẫu; chưa tạo 120 câu thật, chạy Ragas hoặc xây engine đánh giá.	Màn hình evaluator tr...~~

~~Kết quả cần có: Có checklist đối chiếu thiết kế–code và biên bản review UI, bản build chạy được; màn hình lệch thiết kế hoặc lỗi chặn chưa sửa thì chưa ký bàn giao.	Trần Diệu Huyền	Đã hoàn thành	2		Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 09 2026 07:00:00 GMT+0700 (Indochina Time)	Huyền đối chiếu code của Vũ/Nhân với bản thiết kế và prototype, chạy smoke test màn hình/route/trạng thái bằng mock trên bản build sạch. Ghi lỗi chặn về đúng task để chủ task sửa, xác nhận lại sau sửa...~~

~~					Tổng giờ các task			141	122																			~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150						15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150						15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150						15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150						15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ dự kiến theo ngày (cả nhóm)				150						15	15	15	15	15	0	0	15	15	15	15	15	0	0~~

~~					Giờ thực tế theo ngày (tự tính)				122						7	12	13	13	11	6	0	12	13	13	11	11	0	0~~

~~	FinMind Sprint 3 Backlog																											~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	52																						~~

~~	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 17 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 18 2026...~~

~~	Sprint 3	S3-WBS01	S3-G01	1	Chốt hợp đồng chunk ID và cấu trúc nguồn	Đinh Huỳnh Vũ	Đã hoàn thành	2		Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cùng Hưng thống nhất mỗi đoạn tài liệu sẽ mang những thông tin nào: mã đoạn, mã tài liệu, phiên bản dữ liệu và vị trí trang/mục/bảng. Bước 2: Viết 2 đoạn dữ liệu mẫu theo đúng cấu trúc đó để mọi người có thể code song song. Bước 3: Kiểm tra cùng một đoạn luôn nhận cùng mã khi chạy lại.	Có ...~~

~~	Sprint 3	S3-WBS06	S3-G01	1	Nâng cấp chunker cho mục và bảng	Đinh Huỳnh Vũ	Đã hoàn thành	7		Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy tài liệu BCTC/BCTN đã chuẩn hóa ở Sprint 2, xem các mục và bảng dài thường bị cắt sai ở đâu. Bước 2: Nâng cấp bộ chia đoạn hiện có để mỗi đoạn có nội dung đủ hiểu và không xé ngang bảng số liệu. Bước 3: Viết ví dụ kiểm tra cho văn bản thường, bảng nhiều dòng và chạy lại để chắc không sinh đoạn...~~

~~	Sprint 3	S3-WBS11	S3-G01	1	Gắn locator vào từng chunk	Đinh Huỳnh Vũ	Đã hoàn thành	4		Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Với mỗi đoạn Vũ đã chia, lưu rõ nó đến từ tài liệu nào, trang nào, mục hoặc bảng nào. Bước 2: Lấy vài đoạn mẫu, bấm/mở lại tài liệu gốc tại vị trí ghi trong đoạn. Bước 3: Sửa các trường hợp trích dẫn nhảy sai trang, sai bảng hoặc không mở được.	Chunk mẫu truy được vị trí nguồn chính xác trong tài liệu.	...~~

~~	Sprint 3	S3-WBS16	S3-G01	1	Tạo manifest chunk phiên bản đầu	Đinh Huỳnh Vũ	Đã hoàn thành	2		Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Ghi một bản kê cho lần chia tài liệu: tài liệu đầu vào, mã kiểm tra nội dung, cấu hình chia đoạn và danh sách mã đoạn. Bước 2: Chạy lại cùng tài liệu để xác nhận không tạo bản sao. Bước 3: Thay một tài liệu mẫu và kiểm tra bản kê cho biết chính xác phần nào đã đổi.	Có manifest phiên bản và danh sá...~~

~~	Sprint 3	S3-WBS19	S3-G01	2	Ổn định chunker trên tài liệu khó	Đinh Huỳnh Vũ	Đang test	3		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thử bộ chia đoạn trên báo cáo có bảng dài, nhiều cột, đổi trang hoặc tiêu đề không đều. Bước 2: Ghi lại từng lỗi và sửa các lỗi nằm trong phạm vi 3 giờ đã phân. Bước 3: Chạy lại toàn bộ ví dụ cũ để chắc sửa bảng khó không làm hỏng tài liệu đơn giản; ghi rõ phần chưa hỗ trợ.	Test hồi quy trên mẫu khó ...~~

~~	Sprint 3	S3-WBS24	S3-G01	2	Kiểm tra citation locator đầu-cuối	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy một câu trả lời mẫu của B1 và mở từng trích dẫn về đúng đoạn nguồn. Bước 2: Kiểm tra đặc biệt bảng trải nhiều trang và hai phiên bản cùng một tài liệu. Bước 3: Sửa trường hợp trích dẫn sai trang, sai bảng hoặc trỏ sang phiên bản dữ liệu khác.	Citation mẫu dẫn đúng document/trang/bảng và không...~~

~~	Sprint 3	S3-WBS29	S3-G06	2	Rà soát chéo Golden40 theo lô	Đinh Huỳnh Vũ	Chưa bắt đầu	8		Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nhận Golden40 theo từng lô 10 câu từ Huyền, không chờ đủ 40 mới bắt đầu. Bước 2: Với mỗi câu, mở tài liệu gốc, kiểm tra đáp án, đơn vị/kỳ và vị trí nguồn; ghi đúng/sai và lý do. Bước 3: Trả danh sách bất đồng cho Huyền sửa, rồi xác nhận lại trước khi bộ câu hỏi được khóa.	Mỗi ca có dấu review người th...~~

~~	Sprint 3	S3-WBS02	S3-G02	1	Chốt mô hình embedding và cấu hình	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng vài đoạn văn mẫu để thử mô hình biến chữ thành dãy số (embedding), nhờ đó máy có thể tìm đoạn gần nghĩa. Bước 2: Ghi rõ tên/phiên bản mô hình, số chiều của dãy số và số đoạn xử lý mỗi lần. Bước 3: Lưu cấu hình và một kết quả mẫu để nhóm dùng chung; chưa cần đợi Vũ chia xong tài liệu thậ...~~

~~	Sprint 3	S3-WBS07	S3-G02	1	Tạo embedding theo lô có báo lỗi	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cho chương trình nhận nhiều đoạn văn mẫu một lần và tạo vector cho từng đoạn. Bước 2: Nếu một đoạn bị lỗi, ghi rõ mã đoạn và lý do, chỉ thử lại có giới hạn, không làm mất các đoạn thành công. Bước 3: Chạy thử một lô có cả đoạn tốt và đoạn lỗi để chứng minh có thể xử lý lại đúng phần lỗi.	Một m...~~

~~	Sprint 3	S3-WBS12	S3-G02	1	Lưu vector và metadata vào pgvector	Hồ Phạm Đăng Nhân	Đã hoàn thành	5		Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chuẩn bị nơi lưu vector trong PostgreSQL/pgvector và liên kết mỗi vector với đúng mã đoạn, tài liệu, công ty và phiên bản dữ liệu. Bước 2: Kiểm tra kích thước vector và ngăn lưu trùng khi chạy lại. Bước 3: Lưu thử từ dữ liệu mẫu, sau đó chuyển sang các đoạn thật khi Vũ bàn giao.	Vector mẫu ...~~

~~	Sprint 3	S3-WBS17	S3-G02	1	Ingest thử corpus vào pgvector	Hồ Phạm Đăng Nhân	Đã hoàn thành	3		Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy một nhóm đoạn thật đã được Vũ gắn nguồn và tạo vector. Bước 2: Nạp vào pgvector, ghi số đoạn thành công, số lỗi và lý do lỗi. Bước 3: Truy vấn lại để đối chiếu số lượng, mã tài liệu, phiên bản; chạy lại không được nhân đôi dữ liệu.	Truy vấn pgvector thấy đúng số chunk hợp lệ và lỗi được lưu ...~~

~~	Sprint 3	S3-WBS20	S3-G02	2	Tạo chỉ mục pgvector và đo baseline	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Có kết quả bas...~~

~~	Sprint 3	S3-WBS25	S3-G02	2	Truy vấn vector có lọc phạm vi	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Ca lọc sai công ty/kỳ...~~

~~	Sprint 3	S3-WBS30	S3-G02	2	Ghi timing và lỗi retrieval	Hồ Phạm Đăng Nhân	Đang test	3		Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Với mỗi lần tìm kiếm vector, ghi thời gian chạy, số đoạn tìm được, điểm của các đoạn và mã lỗi nếu có. Bước 2: Che thông tin nhạy cảm trong lỗi/log. Bước 3: Chạy câu hỏi thành công và câu hỏi lỗi để chắc người kiểm tra có đủ dấu vết tìm nguyên nhân chậm hoặc sai.	Một truy vấn có trace thật đủ phân tích...~~

~~	Sprint 3	S3-WBS34	S3-G02	2	Kiểm thử E2E vector retrieval	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chọn một tài liệu sạch và chạy toàn bộ đường đi: Vũ chia đoạn, Nhân tạo/lưu vector, rồi tìm lại đoạn bằng câu hỏi. Bước 2: So số đoạn, mã nguồn, phiên bản và trích dẫn ở từng bước. Bước 3: Chạy lại để kiểm tra không trùng; lỗi nào chưa sửa được phải ghi rõ người phụ trách.	Ca E2E qua hoặc có lỗi k...~~

~~	Sprint 3	S3-WBS05	S3-G08	1	Chốt thiết kế tài khoản và API	Nguyễn Minh Quân	Đã hoàn thành	3	2	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Xem các trang đăng nhập/đăng ký hiện có, phần tài khoản và phiên đăng nhập trong cơ sở dữ liệu. Bước 2: Vẽ luồng người dùng cho đăng ký, đăng nhập, quên mật khẩu, đặt lại mật khẩu và đăng xuất. Bước 3: Chốt cách quản lý đăng nhập và danh sách API cần làm trước khi code, kèm quy tắc không ghi mật...~~

~~	Sprint 3	S3-WBS10	S3-G08	1	Code đăng ký và đăng nhập backend	Nguyễn Minh Quân	Đã hoàn thành	8	6	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo chức năng đăng ký bằng thông tin hợp lệ và lưu mật khẩu dưới dạng đã bảo vệ, không lưu bản gốc. Bước 2: Tạo đăng nhập, xử lý sai mật khẩu và giới hạn thử liên tiếp; trả thông báo không tiết lộ dữ liệu nhạy cảm. Bước 3: Kiểm thử tài khoản đúng/sai và xác nhận người dùng không tự cấp quyền ...~~

~~	Sprint 3	S3-WBS15	S3-G08	1	Nối login/register UI với API	Nguyễn Minh Quân	Đã hoàn thành	4	3	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nối màn hình đăng nhập/đăng ký hiện có với API thật thay vì dữ liệu giả. Bước 2: Hiển thị trạng thái đang xử lý, nhập sai, lỗi mạng và đăng nhập thành công sao cho người dùng hiểu. Bước 3: Kiểm tra giao diện không lưu mật khẩu hoặc mã khôi phục trong trình duyệt.	Luồng UI đăng nhập/đăng ký dùng b...~~

~~	Sprint 3	S3-WBS23	S3-G08	2	Code quên và đặt lại mật khẩu	Nguyễn Minh Quân	Đã hoàn thành	6	4	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo luồng người dùng nhập email để xin đặt lại mật khẩu; phản hồi giống nhau dù email có tồn tại hay không. Bước 2: Phát mã/đường dẫn khôi phục chỉ dùng một lần và có hạn, lưu bản đã bảo vệ, rồi cho người dùng đặt mật khẩu mới. Bước 3: Làm màn hình quên/đặt lại mật khẩu và thử mã đúng, mã hết hạn...~~

~~	Sprint 3	S3-WBS28	S3-G08	2	Hoàn thiện session logout refresh	Nguyễn Minh Quân	Đã hoàn thành	4	3	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cho người dùng đăng xuất và làm phiên đăng nhập hết hiệu lực theo cách đã chọn. Bước 2: Xử lý trường hợp phiên hết hạn: thử làm mới an toàn nếu được phép, nếu không thì đưa về trang đăng nhập. Bước 3: Thử mã phiên sai, hết hạn và đã đăng xuất để chắc không truy cập tiếp được.	Logout thu hồi p...~~

~~	Sprint 3	S3-WBS33	S3-G08	2	Bảo vệ API theo vai trò	Nguyễn Minh Quân	Đã hoàn thành	3	3	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Liệt kê API tài khoản, nguồn dữ liệu, corpus, truy vấn và đánh giá nằm trong phạm vi Sprint 3, cùng vai trò được phép dùng từng API. Bước 2: Kiểm tra quyền ở máy chủ, không chỉ ẩn nút trên giao diện. Bước 3: Thử tài khoản thiếu quyền gọi trực tiếp từng API và xác nhận bị từ chối.	Sai vai trò bị từ chối...~~

~~	Sprint 3	S3-WBS36	S3-G08	2	Kiểm thử bảo mật tài khoản	Trần Diệu Huyền 	Chưa bắt đầu	2		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thử đặt lại mật khẩu bằng mã hết hạn và mã đã dùng; cả hai phải bị từ chối. Bước 2: Thử đăng xuất rồi dùng lại phiên và thử tài khoản sai vai trò gọi API. Bước 3: Xem log không lộ mật khẩu, mã reset hoặc việc email có tồn tại; lỗi chưa qua phải để mở, không đánh dấu hoàn thành.	Các ca bảo mật thiết yế...~~

~~	Sprint 3	S3-WBS03	S3-G04	1	Chốt intent và phạm vi câu hỏi B1	Thái Quốc Hưng	Đã hoàn thành	4	4	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Liệt kê thông tin phải hiểu từ câu hỏi: công ty, thời kỳ và chỉ tiêu tài chính. Bước 2: Viết ví dụ câu hỏi đủ thông tin, thiếu thông tin và mơ hồ. Bước 3: Quy định khi nào hệ thống được tìm dữ liệu, khi nào phải hỏi lại người dùng; thử bằng dữ liệu mẫu trước.	Có bảng intent, scope và ca kiểm th...~~

~~	Sprint 3	S3-WBS08	S3-G04	1	Chốt cấu trúc evidence pack	Thái Quốc Hưng	Đã hoàn thành	3	3	Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Quy định một gói bằng chứng cần có nội dung đoạn, mã nguồn, vị trí trang/bảng, phiên bản dữ liệu và điểm phù hợp. Bước 2: Tạo vài gói mẫu và cho luồng trả lời B1 đọc thử, ngay cả khi tìm kiếm vector thật chưa xong. Bước 3: Kiểm tra gói thiếu vị trí nguồn hoặc phiên bản bị báo lỗi rõ ràng.	B1 đọc được...~~

~~	Sprint 3	S3-WBS13	S3-G04	1	Dựng B1 retrieval orchestration bằng fixture	Thái Quốc Hưng	Đã hoàn thành	5	6	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nối phần hiểu câu hỏi với mẫu kết quả tìm kiếm và gói bằng chứng đã thống nhất. Bước 2: Cho B1 chạy thử với dữ liệu mẫu để kiểm tra đường đi từ câu hỏi đến danh sách nguồn. Bước 3: Xử lý riêng trường hợp không tìm thấy nguồn, kết quả rỗng hoặc hết thời gian; chưa phải đợi dữ liệu vec...~~

~~	Sprint 3	S3-WBS18	S3-G04	1	Xử lý B1 khi câu hỏi hoặc nguồn mơ hồ	Thái Quốc Hưng	Đã hoàn thành	3	3	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng câu hỏi thiếu công ty/kỳ/chỉ tiêu để thử B1. Bước 2: Viết câu trả lời yêu cầu người dùng làm rõ thay vì đoán. Bước 3: Với câu hỏi đủ thông tin nhưng không có nguồn phù hợp, cho hệ thống nói chưa đủ bằng chứng và không tự tạo số liệu.	Ca thiếu công ty/kỳ hoặc không có nguồn không bị bịa...~~

~~	Sprint 3	S3-WBS21	S3-G04	2	Nối B1 với retrieval và Gemini	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng dữ liệu mẫu để hoàn thiện phần gửi câu hỏi và bằng chứng cho Gemini. Bước 2: Khi Nhân bàn giao truy vấn vector có lọc, thay đầu vào mẫu bằng đoạn thật, giữ mã nguồn trong câu trả lời. Bước 3: Ghi phiên bản mô hình, prompt, giới hạn ngữ cảnh và kiểm tra B1 không bật cơ chế kiểm chứng riêng của...~~

~~	Sprint 3	S3-WBS26	S3-G04	2	Kiểm tra trích dẫn và câu trả lời B1	Thái Quốc Hưng	Đã hoàn thành	3	2	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy vài câu trả lời B1 có nguồn đầy đủ, nguồn thiếu và nguồn mâu thuẫn. Bước 2: Kiểm tra từng nhận định có mã bằng chứng tương ứng và trích dẫn mở được. Bước 3: Với nhận định không chứng minh được, sửa câu trả lời thành thận trọng hoặc báo chưa đủ bằng chứng.	Không có claim vô nguồn trong ca...~~

~~	Sprint 3	S3-WBS31	S3-G04	2	Áp giới hạn token timeout và budget	Thái Quốc Hưng	Đã hoàn thành	3	4	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	Ca...~~

~~	Sprint 3	S3-WBS35	S3-G04	2	Chạy B1 trên Golden40 đã khóa	Thái Quốc Hưng	Đã hoàn thành	4	3	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	...~~

~~	Sprint 3	S3-WBS04	S3-G06	1	Chốt phân bổ Golden40	Trần Diệu Huyền	Đã hoàn thành	3		Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lập danh sách đúng 40 câu hỏi để hiệu chỉnh hệ thống, chia đều theo loại câu hỏi, ngành, ngôn ngữ và thời kỳ đã chốt. Bước 2: Đánh mã từng câu, giao thành các lô 10 câu cho người kiểm tra. Bước 3: Đối chiếu để không trùng với 80 câu của bộ kiểm tra cuối, vì bộ cuối không được dùng để chỉnh hệ thống.	Bảng p...~~

~~	Sprint 3	S3-WBS09	S3-G06	1	Soạn Golden40 lô 1–2	Trần Diệu Huyền	Đã hoàn thành	6		Tue Oct 13 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Soạn 20 câu hỏi đầu theo phân bổ đã duyệt, kèm đáp án ngắn, đơn vị và kỳ báo cáo. Bước 2: Với mỗi đáp án, ghi tài liệu gốc và trang/mục/bảng có thể mở lại để kiểm chứng. Bước 3: Đánh dấu câu còn nghi ngờ và gửi từng lô 10 câu cho người rà soát, không chờ xong cả bộ.	20 ca có đáp án và locator mở lại được; đ...~~

~~	Sprint 3	S3-WBS14	S3-G06	1	Soạn Golden40 lô 3–4	Trần Diệu Huyền	Đã hoàn thành	6		Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Soạn nốt 20 câu còn lại để đủ 40 câu, không chỉ viết câu hỏi mà phải có đáp án và nguồn chứng minh. Bước 2: Kiểm tra toàn bộ 40 câu có đúng tỷ lệ loại câu/ngành/ngôn ngữ đã định. Bước 3: Gửi từng lô 10 câu cho Vũ rà soát và ghi rõ câu cần sửa.	Đủ 40 ca có đáp án, nguồn gốc và trạng thái cần review.	Golden40...~~

~~	Sprint 3	S3-WBS22	S3-G06	2	Hoàn thiện đáp án và locator Golden40	Trần Diệu Huyền	Đã hoàn thành	8		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Mở lại tài liệu gốc cho từng câu trong Golden40 để kiểm tra đáp án, đơn vị, kỳ và vị trí trang/bảng. Bước 2: Sửa câu trùng, câu mơ hồ hoặc đáp án chưa có nguồn chắc chắn. Bước 3: Chuyển từng lô đã ổn cho Vũ rà soát độc lập, kèm danh sách chỗ còn bất đồng.	40 ca đủ trường bắt buộc; mỗi ca có...~~

~~	Sprint 3	S3-WBS27	S3-G06	2	Khóa Golden40 sau rà soát chéo	Trần Diệu Huyền	Đã hoàn thành	2		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nhận bản rà soát của Vũ cho từng lô 10 câu. Bước 2: Cùng Vũ giải quyết tất cả câu còn bất đồng về đáp án hoặc vị trí nguồn. Bước 3: Lưu bản Golden40 cuối cùng với mã phiên bản và mã kiểm tra nội dung; từ đây không sửa âm thầm khi chạy đánh giá.	40 ca có version khóa; không còn bất đồng chưa xử lý....~~

~~	Sprint 3	S3-WBS32	S3-G06	2	Chuẩn bị metric và bàn giao Golden40	Trần Diệu Huyền	Chưa bắt đầu	5		Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Viết tiêu chí chấm câu trả lời: đúng số liệu, có nguồn mở lại được, trả lời đủ ý và trường hợp cần người kiểm tra. Bước 2: Thử cách tính trên vài ca mẫu, ghi kết quả tạm. Bước 3: Sau khi Golden40 được khóa, chạy lại trên bản khóa và bàn giao bảng lỗi cùng phiên bản dùng cho Sprint 4.	Có metri...~~

~~					Tổng giờ các task			150	52																			~~

~~					Giờ thực tế theo ngày (tự tính)				46						5	9	6	3	3	1	0	7	3	3	3	3	0	0~~

~~	Mục tiêu Sprint 4: Graph RAG cho quan hệ doanh nghiệp, chức vụ và sự kiện; Hybrid Router chọn VECTOR/GRAPH/BOTH. Dùng lại chunk và B1 Sprint 3.																											~~

~~	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																											~~

~~	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																											~~

~~	Chỉ nhập giờ thực tế ở cột ngày màu vàng. Giờ thực tế là tổng các ngày đã ghi, để trống khi chưa ghi giờ.																											~~

~~	Phân công theo nhóm đã chốt. WBS10 tuần 1; WBS09 tuần 2. WBS17 là một task chung: Nhân 7h và Huyền 6h, tổng 13 giờ công. Ngày và giờ là đề xuất; dùng fixture khi chờ đầu vào.																											~~

~~	FinMind Sprint 4 Backlog																											~~

~~	Số task	17	Giờ dự kiến	128	Tổng giờ thực tế đã ghi			Tuần 1 (h)	65	Tuần 2 (h)	63																	~~

~~	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Oct 31 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 01 2026...~~

~~4. Bàn giao quan hệ ứng viên có đoạn nguồn; thử ca nhiều chức vụ, nhiều công ty, thiếu thời gian và nguồn mâu thuẫn.	Quan hệ chức vụ đủ người, tổ chức, chức danh và provenance; không nhầm trạng thái hoặc thời gian; ca chưa rõ được đánh dấu.	WBS01; dùng WBS02 thật để nghiệm thu. Có thể làm bằng fixture song song WBS03/WBS05 và phần lưu metadata WBS07.														~~

~~4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	WBS01 và trạng thái WBS06 (có thể chốt interface song song). Dùng repository fixture trước DB thật. Phối hợp khóa extraction/version với Nhân WBS08.														~~

~~4. Chạy hồi quy các câu B1 đã hoạt động và bàn giao adapter thật cho WBS13.	VECTOR chạy được nguồn thật, giữ phạm vi/metadata và không làm hỏng B1; có test các ca rỗng/lỗi.	WBS10 và Vector RAG Sprint 3. Không chờ WBS09. Làm sớm đầu tuần 2 để Vũ còn thời gian WBS16.														~~

~~5. Bàn giao báo cáo full-load, lỗi còn lại và phiên dữ liệu. 8h là công chuẩn bị, theo dõi và đối chiếu, không phải cam kết thời gian máy/LLM hay duyệt thủ công mọi quan hệ.	Toàn bộ News đã chốt có trạng thái, không mất tin lỗi; có báo cáo mẫu/full-load riêng và danh sách lỗi chưa xử lý. Không coi mọi quan hệ trích xuất là đã được chấp nhận.	WBS01–08 và kiểm tra mẫu WBS09.5 đạt. Batch runner làm trước bằng fixture; không cần chờ router/chat/UI. Phụ thuộc hạn mức dịch vụ và quyền chạy dữ liệu thậ...~~

~~4. Dùng ID WBS02 để xuất đúng contract; kiểm tra mẫu hợp lệ, sai chiều, thiếu chủ thể và hai tên chỉ xuất hiện cùng đoạn.	Có quan hệ doanh nghiệp ứng viên kèm nguồn, trạng thái và thời gian nếu có; test không tạo quan hệ chỉ từ đồng xuất hiện.	Contract WBS01; chuẩn hóa thật WBS02 để đóng task. Có thể code bằng entity fixture từ 27/10, không phải đợi WBS02 xong mới bắt đầu.														~~

~~4. Xử lý lỗi nạp dở, chuẩn bị resume và đối chiếu số liệu/khóa giữa hai hệ thống. Nghiệm thu phần ghi bằng fixture ở tuần 1; WBS09 nối extraction thật tuần 2.	Bộ ghi graph có test chống trùng, không lẫn phiên, giữ extraction/nguồn và không công bố lần nạp dở. Có graph fixture dùng cho truy vấn.	WBS01; thống nhất metadata/version với WBS07. Không phải đợi full extractor; dùng graph fixture trước. WBS09 chịu trách nhiệm ghép dữ liệu thật.														~~

~~4. Chuẩn bị adapter bằng fixture từ đầu tuần, nối retrieval thật sau khi WBS09 bàn giao; kiểm tra không lộ quan hệ chờ duyệt.	GRAPH chạy bằng graph thật đúng scope, có nguồn và lỗi rõ; đọc lại nguồn bằng ID không bị gắn nhãn BOTH.	Contract WBS10; WBS09 thật để đóng task. Có thể code adapter bằng fixture trước, không đứng chờ pipeline ghép xong.														~~

~~5. Cùng bàn giao bộ test, kết quả chạy thật, bảng so sánh B1/B2, báo cáo full-load và giới hạn còn lại. Chỉ hoàn thành task khi cả phần Nhân và Huyền đạt. Tổng 13 giờ công = Nhân 7 giờ + Huyền 6 giờ, không phải 13 giờ mỗi người.	Có bộ test và kết quả thật cho VECTOR/GRAPH/BOTH và ba nhóm quan hệ; bảng B1/B2 có chất lượng và thời gian phản hồi; citation đúng nguồn; có kiểm thử lỗi/E2E/hồi quy, báo cáo full-load và danh sách lỗi còn lại. Không mặc định B2 tốt hơn B1.	Chuẩn bị bộ ca bằng WBS01/fixt...~~

~~5.  Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 của Vũ.														~~

~~5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.														~~

~~5. Giữ cấu hình B1 để so sánh; không tự bật Evidence Gate/verifier B3 thuộc sprint sau.	Câu trả lời/citation truy lại được nguồn, không bịa quan hệ/số liệu hoặc che lỗi nhánh; có test và gói bàn giao.	Evidence contract và WBS11–13. Có thể chuẩn bị formatter/citation bằng fixture trước, nghiệm thu sau tuyến thật.														~~

~~4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầu ra ngày 26/10 mở đường cho WBS02–08 và WBS10.														~~

~~4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.														~~

~~5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fixture trước; không viết lại repository/extractor. WBS12 dùng retrieval này; WBS16 chỉ full-load sau 09.5 đạt.														~~

~~4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ cả ba extractor mới chuẩn bị quy tắc.														~~

~~5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-load.														~~

~~5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.														~~

~~					Tổng giờ các task			128	0																			~~

~~					Giờ thực tế theo ngày (tự tính)				0						0	0	0	0	0	0	0	0	0	0	0	0	0	0~~

~~					Giờ thực tế theo ngày (tự tính)				0						0	0	0	0	0	0	0	0	0	0	0	0	0	0~~

~~					Giờ thực tế theo ngày (tự tính)				0						0	0	0	0	0	0	0	0	0	0	0	0	0	0~~

~~	Sprint 5 gồm 38 task con. Tuần 1 sửa lỗi và nối truy xuất (58h); tuần 2 tối ưu Chat và nhận định xu hướng (50h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																											~~

~~	FinMind Sprint 5 Backlog																											~~

~~	Số task	38	Giờ dự kiến	108	Tổng giờ thực tế đã ghi																							~~

~~	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 14 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026...~~

~~	Sprint 5	S5-WBS01.1	S5-G01	1	Tái hiện lỗi hỏi chức vụ và BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4														~~

~~	Sprint 5	S5-WBS01.2	S5-G01	1	Tái hiện lỗi hội thoại và hết hạn token		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có														~~

~~	Sprint 5	S5-WBS02.1	S5-G01	1	Tìm điều kiện chặn câu hỏi BCTN		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1														~~

~~	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1														~~

~~	Sprint 5	S5-WBS02.3	S5-G01	1	Kiểm thử truy xuất BCTN bằng dữ liệu thật		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2														~~

~~	Sprint 5	S5-WBS03.1	S5-G02	1	Chốt nhãn ý định và ranh giới giữa các nhãn		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—														~~

~~	Sprint 5	S5-WBS03.2	S5-G02	1	Soạn cụm từ mẫu và bộ câu kiểm thử riêng		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1														~~

~~	Sprint 5	S5-WBS03.3	S5-G02	1	Vector hóa và lưu phiên bản thư viện		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2														~~

~~	Sprint 5	S5-WBS04.1	S5-G02	1	Đối chiếu vector câu hỏi với thư viện		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3														~~

~~	Sprint 5	S5-WBS04.2	S5-G02	1	Đặt ngưỡng tin cậy và quy tắc chọn nhánh		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1														~~

~~	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2														~~

~~	Sprint 5	S5-WBS05.1	S5-G03	1	Nối router vào luồng xử lý tin nhắn Web Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Gọi router trong backend khi Web Chat gửi tin và ghi trace. Có thể chuẩn bị tích hợp bằng mẫu.	Trace xác nhận Web Chat gọi router và chọn nhánh.	S5-WBS04.2														~~

~~	Sprint 5	S5-WBS05.2	S5-G03	1	Nối nhánh GRAPH với Neo4j qua adapter hiện có		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng graph adapter để lấy quan hệ đã duyệt, chức vụ và nguồn tương ứng.	Câu hỏi chức vụ trả đúng người, chức vụ và bằng chứng.	S5-WBS05.1, graph có dữ liệu đã duyệt														~~

~~	Sprint 5	S5-WBS05.3	S5-G03	1	Kiểm thử graph thật, graph rỗng và lỗi kết nối		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2														~~

~~	Sprint 5	S5-WBS06.1	S5-G04	1	Dùng cơ chế refresh token chung cho request Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập														~~

~~	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1														~~

~~	Sprint 5	S5-WBS07.1	S5-G05	1	Chốt điều kiện fallback và JSON phân loại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2														~~

~~	Sprint 5	S5-WBS07.2	S5-G05	1	Nối AI bên thứ ba vào bước phân loại		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Gọi AI khi cần, giới hạn thời gian, xác thực nhãn và chuyển kết quả về router FinMind. Chuẩn bị bằng phản hồi mẫu.	Nhãn hợp lệ tiếp tục truy xuất trong FinMind. Trace ghi lần gọi.	S5-WBS07.1														~~

~~	Sprint 5	S5-WBS07.3	S5-G05	1	Kiểm thử fallback và trường hợp cả hai bước thất bại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2														~~

~~	Sprint 5	S5-WBS08.1	S5-G06	1	Chuẩn bị chuỗi giá theo mã doanh nghiệp		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chốt khoảng giá, lấy ngày đầu/cuối, số phiên và nguồn theo mã.	Có chuỗi giá mẫu và mức biến động truy được nguồn.	Dữ liệu giá hiện có														~~

~~	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC gần nhất		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có														~~

~~	Sprint 5	S5-WBS08.3	S5-G06	1	Chuẩn hóa đầu vào cho mô hình xu hướng		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ghép mã, chuẩn hóa đơn vị và chọn kỳ so sánh tương đương. Đánh dấu thiếu dữ liệu.	Có đầu vào theo doanh nghiệp, kỳ, đơn vị và trạng thái đủ dữ liệu.	S5-WBS08.1, S5-WBS08.2														~~

~~	Sprint 5	S5-WBS09.1	S5-G07	2	Kế thừa công ty, kỳ và chủ đề giữa các lượt		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng phạm vi hội thoại hiện tại, ưu tiên công ty hoặc kỳ mới nếu người dùng thay đổi.	Câu nối tiếp giữ đúng phạm vi và chuyển phạm vi khi được yêu cầu.	S5-WBS05.1														~~

~~	Sprint 5	S5-WBS09.2	S5-G07	2	Xử lý liệt kê và giới thiệu tổng quan		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Liệt kê nội dung đang nói. Tổng quan đúng doanh nghiệp và truy xuất thêm khi cần.	Hai câu mẫu chạy đúng trong phiên nhiều lượt.	S5-WBS09.1														~~

~~	Sprint 5	S5-WBS09.3	S5-G07	2	Xử lý tổng hợp nãy giờ		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tóm tắt nội dung phiên hiện tại và giữ các nguồn đã dẫn.	Không lẫn nội dung giữa các phiên, nguồn còn đối chiếu được.	S5-WBS09.1														~~

~~	Sprint 5	S5-WBS10.1	S5-G06	2	Tính nhóm tín hiệu giá		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tính biến động theo khoảng đã chốt và đánh dấu thiếu phiên hoặc thiếu giá.	Có tín hiệu giá và dữ liệu dùng để tính.	S5-WBS08.1, S5-WBS08.3														~~

~~	Sprint 5	S5-WBS10.2	S5-G06	2	Tính nhóm tín hiệu tài chính		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tính thay đổi doanh thu, lợi nhuận và dòng tiền khi có kỳ tương đương.	Có tín hiệu từng chỉ tiêu và nguồn tương ứng.	S5-WBS08.2, S5-WBS08.3														~~

~~	Sprint 5	S5-WBS10.3	S5-G06	2	Gộp tín hiệu và trả nhãn xu hướng		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng quy tắc chấm điểm giải thích được để gộp tín hiệu giá và tài chính.	Trả đi lên, đi xuống, trái chiều hoặc chưa đủ dữ liệu. Ca trái chiều thể hiện hai tín hiệu riêng.	S5-WBS10.1, S5-WBS10.2														~~

~~	Sprint 5	S5-WBS10.4	S5-G06	2	Kiểm thử quy tắc chấm điểm		Chưa bắt đầu	2		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thử cùng tăng, cùng giảm, trái chiều và thiếu kỳ.	Mỗi nhãn giải thích được bằng số liệu đầu vào.	S5-WBS10.3														~~

~~	Sprint 5	S5-WBS11.1	S5-G06	2	Nối ý định xu hướng với mô hình nhận định		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Khi nhận diện câu hỏi xu hướng, gọi mô hình với đúng mã và phạm vi. Chuẩn bị bằng kết quả mẫu trước.	Trace xác nhận Chat gọi mô hình đúng đầu vào.	S5-WBS04.2, S5-WBS05.1, S5-WBS10.3 để nghiệm thu thật														~~

~~	Sprint 5	S5-WBS11.2	S5-G06	2	Hiển thị nhận định xu hướng trong Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tách diễn biến giá và tình hình tài chính, ghi kỳ, chỉ tiêu, nguồn và phần còn thiếu.	Chat đưa nhận định đúng công ty, kỳ và có nguồn kiểm tra được.	S5-WBS11.1, S5-WBS10.3														~~

~~	Sprint 5	S5-WBS12.1	S5-G08	2	Định dạng câu trả lời theo yêu cầu		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng danh sách cho liệt kê, bảng cho so sánh và tóm tắt cho tổng quan.	Câu trả lời có đúng cấu trúc người dùng yêu cầu.	S5-WBS09.2, S5-WBS09.3 cho ca nối tiếp														~~

~~	Sprint 5	S5-WBS12.2	S5-G08	2	Ghép bằng chứng graph và tài liệu cho BOTH		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ghép kết quả theo đúng mã công ty và kỳ, gắn citation sát nhận định.	Cả hai loại bằng chứng được dùng đúng phạm vi và nguồn.	S5-WBS05.2, nhánh Vector hiện có														~~

~~	Sprint 5	S5-WBS12.3	S5-G08	2	Xử lý kết quả rỗng, thiếu nguồn và lỗi một nhánh		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ trình bày phần có căn cứ, ghi rõ phần còn thiếu và thử ca fallback thất bại.	Câu trả lời phân biệt rỗng, thiếu bằng chứng và lỗi nhánh.	S5-WBS07.3, S5-WBS12.1, S5-WBS12.2														~~

~~	Sprint 5	S5-WBS13.1	S5-G09	2	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3														~~

~~	Sprint 5	S5-WBS13.2	S5-G09	2	Đánh giá router và fallback trên bộ câu riêng		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3														~~

~~	Sprint 5	S5-WBS13.3	S5-G09	2	Đối chiếu nhận định xu hướng và citation		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2														~~

~~	Sprint 5	S5-WBS13.4	S5-G09	2	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại		Chưa bắt đầu	2		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3														~~

~~					Tổng giờ các task			108	0																			~~

~~	Ngày, giờ và phân công là đề xuất. Tuần 1 và 2 tính từ thứ Hai bắt đầu sprint; chỉ làm khi đầu vào đã sẵn sàng.																											~~

~~	FinMind Sprint 6 Backlog																											~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi																							~~

~~	Sprint	Mã task	Mã việc tổng quát	Tuần trong sprint	Công việc	Phụ trách	Tình trạng	Giờ dự kiến	Giờ thực tế	Bắt đầu dự kiến	Deadline	Cần làm gì	Điều kiện hoàn thành	Đầu vào cần có	Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 28 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 29 2026...~~

~~	Sprint 6	S6-WBS01	S6-G01	1	Kiểm tra bộ 80 ca đã khóa	Trần Diệu Huyền	Chưa bắt đầu	4		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu phiên bản, phân bổ ca và locators được reviewer duyệt. Runtime không được đọc đáp án chuẩn.	Có 80 ca final hợp lệ tách khỏi dữ liệu tuning.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 6	S6-WBS02	S6-G01	1	Kiểm tra manifest B0 B1 B2 B3	Trần Diệu Huyền	Chưa bắt đầu	5		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu code tag, corpus, model, prompt, threshold và evaluator đã chốt ở Sprint 5.	Bốn cấu hình được ghi rõ và không thay đổi giữa các ca.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 6	S6-WBS03	S6-G01	1	Tạo run ID và checkpoint hạ tầng	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thiết lập lưu trạng thái từng câu và cách chạy tiếp chỉ khi hạ tầng lỗi với manifest không đổi.	Có thể resume lỗi hạ tầng mà không thay cấu hình hoặc chọn lại kết quả.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 6	S6-WBS04	S6-G01	1	Kiểm tra cách ly nhãn và quyền evaluator	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ evaluator đọc gold labels; xác nhận API runtime không nhận đáp án chuẩn.	Không có nhãn final trong context hoặc log đầu vào generator.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 6	S6-WBS05	S6-G02	1	Chạy và lưu đầu ra B0	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy các câu bằng cấu hình structured control; ghi trả lời hoặc không trả lời và lý do.	Có kết quả từng câu của B0 với manifest và trace.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.														~~

~~	Sprint 6	S6-WBS06	S6-G02	1	Chạy và lưu đầu ra B1	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy vector RAG đúng tag, giữ output, citation, latency và token.	Không bật các thành phần chỉ thuộc B3 trong B1.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.														~~

~~	Sprint 6	S6-WBS07	S6-G02	1	Chạy và lưu đầu ra B2	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hybrid graph vector cùng corpus và bộ final; ghi nhánh graph và fusion.	Có đủ dữ liệu từng câu để đối chiếu với B1.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.														~~

~~	Sprint 6	S6-WBS08	S6-G02	1	Chạy và lưu đầu ra B3	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy cả Gate và verifier, kể cả nhánh sửa có giới hạn; ghi cả fallback hoặc partial.	Mỗi tag chỉ có lượt final hợp lệ theo policy, không chọn lượt đẹp nhất.	Kiểm tra đầu ra liên quan của S6-G01 trước khi làm.														~~

~~	Sprint 6	S6-WBS09	S6-G03	1	Tính đúng số độ trung thực và citation	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng định nghĩa và phiên bản evaluator để tính quality metrics từ kết quả thực tế.	Mỗi điểm truy ra được output, gold và cách tính.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.														~~

~~	Sprint 6	S6-WBS10	S6-G03	1	Tính recall coverage và an toàn thiếu dữ liệu	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu theo hash và locator nguồn; kiểm tra cả số liệu bịa, missing-data và false refusal.	Có số đúng sai và mẫu lỗi cho từng chỉ số bắt buộc.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.														~~

~~	Sprint 6	S6-WBS11	S6-G03	1	So sánh theo loại câu ngành và ngôn ngữ	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tách kết quả B0 B3 theo nhóm và khoảng tin cậy theo protocol; không chỉ báo overall.	Bảng phân tích nêu số mẫu và nhóm không đủ kết luận.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.														~~

~~	Sprint 6	S6-WBS12	S6-G03	1	Đối chiếu Gate và giả thuyết nghiên cứu	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Tách ngưỡng nghiệm thu khỏi giả thuyết và số chỉ để báo cáo; ghi các mục chưa đạt.	Không biến mục tiêu hoặc giả thuyết thành kết quả đã đo.	Kiểm tra đầu ra liên quan của S6-G02 trước khi làm.														~~

~~	Sprint 6	S6-WBS13	S6-G04	1	Kiểm tra các ca số liệu và citation quan trọng	Thái Quốc Hưng	Chưa bắt đầu	6		Mon Nov 23 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Rà thủ công các lỗi số liệu, citation và các nhóm phải audit theo SRS.	Có biên bản reviewer và giải quyết bất đồng.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.														~~

~~	Sprint 6	S6-WBS14	S6-G04	1	Chạy tải 10 yêu cầu đồng thời	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Nov 24 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng môi trường và corpus đã ghi, đo latency từ nhận yêu cầu đến kết quả cuối.	Có cấu hình tải, máy chạy và raw latency của từng yêu cầu.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.														~~

~~	Sprint 6	S6-WBS15	S6-G04	1	Tính p95 và thời gian nhánh sửa	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Wed Nov 25 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tính p95 cho answered requests gồm controlled repair; báo riêng refusal và partial.	Bảng tốc độ không loại lượt sửa để làm đẹp số đo.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.														~~

~~	Sprint 6	S6-WBS16	S6-G04	1	Tổng hợp token và chi phí thực tế	Hồ Phạm Đăng Nhân	Chưa bắt đầu	2		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy token từng request theo mô hình và lần gọi; đối chiếu budget và lưu rate dùng để tính nếu có.	Báo cáo phân biệt token đo được và chi phí chưa xác định.	Kiểm tra đầu ra liên quan của S6-G03 trước khi làm.														~~

~~	Sprint 6	S6-WBS17	S6-G05	2	Kiểm thử phân quyền và phiên hết hạn	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Thử truy cập sai vai trò, hết hạn phiên và dữ liệu của người khác với các API chính.	Không vượt quyền hoặc đọc lịch sử ngoài chính sách.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.														~~

~~	Sprint 6	S6-WBS18	S6-G05	2	Kiểm thử bí mật retention và log	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra khóa API, dữ liệu nhạy cảm, chính sách xóa trace và lỗi subsystem.	Không lộ bí mật; thao tác xóa và review có vết kiểm tra được.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.														~~

~~	Sprint 6	S6-WBS19	S6-G05	2	Chạy lại luồng nghiệp vụ từ đầu đến cuối	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Thử tìm công ty, đặt câu hỏi, so sánh, mở nguồn và fallback trên bản bàn giao.	Có kết quả kiểm thử cho các luồng Must và ca lỗi chính.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.														~~

~~	Sprint 6	S6-WBS20	S6-G05	2	Hoàn thiện ma trận yêu cầu và test	Nguyễn Minh Quân	Chưa bắt đầu	4		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Liên kết từng FR NFR Must với test ID, kết quả và bằng chứng; ghi mục chưa đạt.	Không có yêu cầu Must chỉ đánh dấu đạt mà thiếu bằng chứng.	Kiểm tra đầu ra liên quan của S6-G04 trước khi làm.														~~

~~	Sprint 6	S6-WBS21	S6-G06	2	Đóng gói Docker Compose	Nguyễn Minh Quân	Chưa bắt đầu	4		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Đóng gói frontend, API, PostgreSQL pgvector và Neo4j với cấu hình tài nguyên rõ ràng.	Khởi động được bộ dịch vụ trên môi trường được ghi.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.														~~

~~	Sprint 6	S6-WBS22	S6-G06	2	Viết migration và cấu hình triển khai mẫu	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn bị migration, biến môi trường mẫu không có secret và cách nạp corpus hợp lệ.	Người khác biết cần cấu hình gì mà không nhận khóa thật của nhóm.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.														~~

~~	Sprint 6	S6-WBS23	S6-G06	2	Thử cài trên môi trường sạch	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Triển khai theo hướng dẫn, không dùng file hoặc cấu hình ẩn chỉ có trên máy dev.	Có log cài sạch và danh sách bước cần sửa.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.														~~

~~	Sprint 6	S6-WBS24	S6-G06	2	Đóng gói manifest và dữ liệu đánh giá	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Lưu output từng câu, metrics, cấu hình và code tag để kiểm tra lại benchmark.	Gói đánh giá tái hiện được nguồn của từng kết quả trong phạm vi quyền lưu.	Kiểm tra đầu ra liên quan của S6-G05 trước khi làm.														~~

~~	Sprint 6	S6-WBS25	S6-G07	2	Cập nhật SRS theo bản triển khai thực tế	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu chức năng Must đã làm, sơ đồ và ràng buộc với code tag bàn giao.	SRS không mô tả chức năng optional chưa triển khai như đã có.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.														~~

~~	Sprint 6	S6-WBS26	S6-G07	2	Viết hướng dẫn sử dụng và quản trị	Thái Quốc Hưng	Chưa bắt đầu	5		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Giải thích đăng nhập, tìm công ty, hỏi, mở nguồn; hướng dẫn nguồn, corpus, budgets và xử lý lỗi.	Người đọc làm theo được từng luồng cơ bản.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.														~~

~~	Sprint 6	S6-WBS27	S6-G07	2	Viết báo cáo kiểm thử và hạn chế	Trần Diệu Huyền	Chưa bắt đầu	4		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Tổng hợp kết quả, lỗi tồn, dữ liệu thiếu và giới hạn phạm vi; đính kèm vị trí bằng chứng.	Báo cáo nêu cả mục chưa đạt, không chỉ các ca thành công.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.														~~

~~	Sprint 6	S6-WBS28	S6-G07	2	Hoàn thiện form và khai báo AI thực tế	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Điền các form được cung cấp, khai báo công cụ AI và phần sử dụng dựa trên nhật ký thật.	Không tự tạo phần trăm sử dụng AI hoặc xác nhận khi chưa có dữ liệu.	Kiểm tra đầu ra liên quan của S6-G06 trước khi làm.														~~

~~	Sprint 6	S6-WBS29	S6-G08	2	Soạn báo cáo nghiên cứu và slide kết quả	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 30 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Trình bày B0 B3, giả thuyết, metrics, mẫu lỗi và giới hạn bằng số đo thực tế.	Bảng trong báo cáo khớp gói đánh giá đã lưu.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.														~~

~~	Sprint 6	S6-WBS30	S6-G08	2	Chuẩn bị kịch bản demo các luồng chính	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Dec 01 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Chọn ca hỏi số liệu, giải thích, quan hệ, so sánh và thiếu dữ liệu trên evaluated tag.	Demo dùng đúng phiên bản đã đánh giá, không thay cấu hình ngầm.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.														~~

~~	Sprint 6	S6-WBS31	S6-G08	2	Diễn tập demo và kiểm tra checklist	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Wed Dec 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Thử mở nguồn, fallback và khởi động dịch vụ; chuẩn bị cách giải thích khi hệ thống hoặc nguồn lỗi.	Nhóm biết thao tác và người phụ trách từng phần demo.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.														~~

~~	Sprint 6	S6-WBS32	S6-G08	2	Chốt hồ sơ nghiệm thu và bàn giao	Hồ Phạm Đăng Nhân	Chưa bắt đầu	2		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Bàn giao code tag, tài liệu, manifests và danh sách lỗi tồn; ghi quyết định đạt hoặc chưa đạt.	Có danh mục bàn giao và người nhận xác nhận các phần thực tế đã có.	Kiểm tra đầu ra liên quan của S6-G07 trước khi làm.														~~

~~	Sprint 6	S6-WBS33	S6-G09	1	Kiểm tra tính đầy đủ của raw benchmark	Thái Quốc Hưng	Chưa bắt đầu	5		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Rà số ca, trace và output của từng cấu hình; chỉ resume lỗi hạ tầng theo policy.	Không mất ca hoặc xuất bản aggregate khi thiếu trace.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 6	S6-WBS34	S6-G09	1	Sửa lỗi công cụ đánh giá và đóng gói	Trần Diệu Huyền	Chưa bắt đầu	6		Thu Nov 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 27 2026 07:00:00 GMT+0700 (Indochina Time)	Sửa lỗi hạ tầng hoặc pipeline báo cáo; thay đổi sau final phải ghi exploratory nếu làm đổi tag.	Không thay kết quả final cũ bằng một lượt chạy tùy chọn.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 6	S6-WBS35	S6-G09	2	Sửa lỗi bàn giao và kiểm thử hồi quy	Trần Diệu Huyền	Chưa bắt đầu	5		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Ưu tiên lỗi triển khai, quyền và mất nguồn; ghi tag sửa sau final và phạm vi kiểm tra lại.	Lỗi đã đóng có test lại và khác biệt so với evaluated tag được công bố.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 6	S6-WBS36	S6-G09	2	Review cuối với nhóm và mentor	Thái Quốc Hưng	Chưa bắt đầu	6		Thu Dec 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Dec 04 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra Gates, tài liệu, demo và lỗi tồn trước khi xác nhận dự án hoàn tất.	Có quyết định nghiệm thu dựa trên bằng chứng, không chỉ dựa vào phần trăm task.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~					Tổng giờ các task			150	0																			~~

## 2026-11-09 14:42 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-09 14:42

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								5	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	108	0	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	S5-WBS01.1	Tái hiện lỗi hỏi chức vụ và BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	...**

🟢 **	S5-WBS01.2	Tái hiện lỗi hội thoại và hết hạn token	Tái hiện lỗi và sửa truy xuất BCTN	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS02.1	Tìm điều kiện chặn câu hỏi BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS02.2	Chuẩn hóa loại tài liệu và bộ lọc BCTN	Tái hiện lỗi và sửa truy xuất BCTN	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1	Cao	Chưa bắt đầu	S5-G01	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS02.3	Kiểm thử truy xuất BCTN bằng dữ liệu thật	Tái hiện lỗi và sửa truy xuất BCTN	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2	Cao	Chưa bắt đầu	S5-G01	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS03.1	Chốt nhãn ý định và ranh giới giữa các nhãn	Thư viện vector và Hybrid Router	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS03.2	Soạn cụm từ mẫu và bộ câu kiểm thử riêng	Thư viện vector và Hybrid Router	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (...**

🟢 **	S5-WBS03.3	Vector hóa và lưu phiên bản thư viện	Thư viện vector và Hybrid Router	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS04.1	Đối chiếu vector câu hỏi với thư viện	Thư viện vector và Hybrid Router	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS04.2	Đặt ngưỡng tin cậy và quy tắc chọn nhánh	Thư viện vector và Hybrid Router	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1	Cao	Chưa bắt đầu	S5-G02	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 ...**

🟢 **	S5-WBS04.3	Chạy bộ câu kiểm thử router	Thư viện vector và Hybrid Router	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2	Cao	Chưa bắt đầu	S5-G02	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS05.1	Nối router vào luồng xử lý tin nhắn Web Chat	Web Chat tích hợp Neo4j	Gọi router trong backend khi Web Chat gửi tin và ghi trace. Có thể chuẩn bị tích hợp bằng mẫu.	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Trace xác nhận Web Chat gọi router và chọn nhánh.	S5-WBS04.2	Cao	Chưa bắt đầu	S5-G03	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS05.2	Nối nhánh GRAPH với Neo4j qua adapter hiện có	Web Chat tích hợp Neo4j	Dùng graph adapter để lấy quan hệ đã duyệt, chức vụ và nguồn tương ứng.	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Câu hỏi chức vụ trả đúng người, chức vụ và bằng chứng.	S5-WBS05.1, graph có dữ liệu đã duyệt	Cao	Chưa bắt đầu	S5-G03	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS05.3	Kiểm thử graph thật, graph rỗng và lỗi kết nối	Web Chat tích hợp Neo4j	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2	Cao	Chưa bắt đầu	S5-G03	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS06.1	Dùng cơ chế refresh token chung cho request Chat	Refresh token cho Chat	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS06.2	Kiểm tra refresh thất bại và chống gửi trùng	Refresh token cho Chat	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1	Vừa	Chưa bắt đầu	S5-G04	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS07.1	Chốt điều kiện fallback và JSON phân loại	Fallback phân loại bằng AI	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2	Cao	Chưa bắt đầu	S5-G05	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS07.2	Nối AI bên thứ ba vào bước phân loại	Fallback phân loại bằng AI	Gọi AI khi cần, giới hạn thời gian, xác thực nhãn và chuyển kết quả về router FinMind. Chuẩn bị bằng phản hồi mẫu.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Nhãn hợp lệ tiếp tục truy xuất trong FinMind. Trace ghi lần gọi.	S5-WBS07.1	Cao	Chưa bắt đầu	S5-G05	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS07.3	Kiểm thử fallback và trường hợp cả hai bước thất bại	Fallback phân loại bằng AI	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2	Cao	Chưa bắt đầu	S5-G05	FinMind	5	2			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS08.1	Chuẩn bị chuỗi giá theo mã doanh nghiệp	Nhận định xu hướng doanh nghiệp	Chốt khoảng giá, lấy ngày đầu/cuối, số phiên và nguồn theo mã.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có chuỗi giá mẫu và mức biến động truy được nguồn.	Dữ liệu giá hiện có	Cao	Chưa bắt đầu	S5-G06	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS08.2	Lấy chỉ tiêu từ các kỳ BCTC gần nhất	Nhận định xu hướng doanh nghiệp	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS08.3	Chuẩn hóa đầu vào cho mô hình xu hướng	Nhận định xu hướng doanh nghiệp	Ghép mã, chuẩn hóa đơn vị và chọn kỳ so sánh tương đương. Đánh dấu thiếu dữ liệu.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có đầu vào theo doanh nghiệp, kỳ, đơn vị và trạng thái đủ dữ liệu.	S5-WBS08.1, S5-WBS08.2	Cao	Chưa bắt đầu	S5-G06	FinMind	5	3			Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	1**

🟢 **	S5-WBS09.1	Kế thừa công ty, kỳ và chủ đề giữa các lượt	Ngữ cảnh và thao tác hội thoại	Dùng phạm vi hội thoại hiện tại, ưu tiên công ty hoặc kỳ mới nếu người dùng thay đổi.	Giữ phạm vi đúng, xử lý liệt kê, tổng quan và tổng hợp trong phiên hiện tại.	Câu nối tiếp giữ đúng phạm vi và chuyển phạm vi khi được yêu cầu.	S5-WBS05.1	Vừa	Chưa bắt đầu	S5-G07	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS09.2	Xử lý liệt kê và giới thiệu tổng quan	Ngữ cảnh và thao tác hội thoại	Liệt kê nội dung đang nói. Tổng quan đúng doanh nghiệp và truy xuất thêm khi cần.	Giữ phạm vi đúng, xử lý liệt kê, tổng quan và tổng hợp trong phiên hiện tại.	Hai câu mẫu chạy đúng trong phiên nhiều lượt.	S5-WBS09.1	Vừa	Chưa bắt đầu	S5-G07	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS09.3	Xử lý tổng hợp nãy giờ	Ngữ cảnh và thao tác hội thoại	Tóm tắt nội dung phiên hiện tại và giữ các nguồn đã dẫn.	Giữ phạm vi đúng, xử lý liệt kê, tổng quan và tổng hợp trong phiên hiện tại.	Không lẫn nội dung giữa các phiên, nguồn còn đối chiếu được.	S5-WBS09.1	Vừa	Chưa bắt đầu	S5-G07	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS10.1	Tính nhóm tín hiệu giá	Nhận định xu hướng doanh nghiệp	Tính biến động theo khoảng đã chốt và đánh dấu thiếu phiên hoặc thiếu giá.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có tín hiệu giá và dữ liệu dùng để tính.	S5-WBS08.1, S5-WBS08.3	Cao	Chưa bắt đầu	S5-G06	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS10.2	Tính nhóm tín hiệu tài chính	Nhận định xu hướng doanh nghiệp	Tính thay đổi doanh thu, lợi nhuận và dòng tiền khi có kỳ tương đương.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Có tín hiệu từng chỉ tiêu và nguồn tương ứng.	S5-WBS08.2, S5-WBS08.3	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS10.3	Gộp tín hiệu và trả nhãn xu hướng	Nhận định xu hướng doanh nghiệp	Dùng quy tắc chấm điểm giải thích được để gộp tín hiệu giá và tài chính.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Trả đi lên, đi xuống, trái chiều hoặc chưa đủ dữ liệu. Ca trái chiều thể hiện hai tín hiệu riêng.	S5-WBS10.1, S5-WBS10.2	Cao	Chưa bắt đầu	S5-G06	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indo...**

🟢 **	S5-WBS10.4	Kiểm thử quy tắc chấm điểm	Nhận định xu hướng doanh nghiệp	Thử cùng tăng, cùng giảm, trái chiều và thiếu kỳ.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Mỗi nhãn giải thích được bằng số liệu đầu vào.	S5-WBS10.3	Cao	Chưa bắt đầu	S5-G06	FinMind	5	2			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS11.1	Nối ý định xu hướng với mô hình nhận định	Nhận định xu hướng doanh nghiệp	Khi nhận diện câu hỏi xu hướng, gọi mô hình với đúng mã và phạm vi. Chuẩn bị bằng kết quả mẫu trước.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Trace xác nhận Chat gọi mô hình đúng đầu vào.	S5-WBS04.2, S5-WBS05.1, S5-WBS10.3 để nghiệm thu thật	Cao	Chưa bắt đầu	S5-G06	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00...**

🟢 **	S5-WBS11.2	Hiển thị nhận định xu hướng trong Chat	Nhận định xu hướng doanh nghiệp	Tách diễn biến giá và tình hình tài chính, ghi kỳ, chỉ tiêu, nguồn và phần còn thiếu.	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Chat đưa nhận định đúng công ty, kỳ và có nguồn kiểm tra được.	S5-WBS11.1, S5-WBS10.3	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS12.1	Định dạng câu trả lời theo yêu cầu	Tối ưu câu trả lời và bằng chứng	Dùng danh sách cho liệt kê, bảng cho so sánh và tóm tắt cho tổng quan.	Định dạng đúng ý định, gắn nguồn đúng nhận định và xử lý khi một nhánh thiếu kết quả.	Câu trả lời có đúng cấu trúc người dùng yêu cầu.	S5-WBS09.2, S5-WBS09.3 cho ca nối tiếp	Cao	Chưa bắt đầu	S5-G08	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS12.2	Ghép bằng chứng graph và tài liệu cho BOTH	Tối ưu câu trả lời và bằng chứng	Ghép kết quả theo đúng mã công ty và kỳ, gắn citation sát nhận định.	Định dạng đúng ý định, gắn nguồn đúng nhận định và xử lý khi một nhánh thiếu kết quả.	Cả hai loại bằng chứng được dùng đúng phạm vi và nguồn.	S5-WBS05.2, nhánh Vector hiện có	Cao	Chưa bắt đầu	S5-G08	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS12.3	Xử lý kết quả rỗng, thiếu nguồn và lỗi một nhánh	Tối ưu câu trả lời và bằng chứng	Chỉ trình bày phần có căn cứ, ghi rõ phần còn thiếu và thử ca fallback thất bại.	Định dạng đúng ý định, gắn nguồn đúng nhận định và xử lý khi một nhánh thiếu kết quả.	Câu trả lời phân biệt rỗng, thiếu bằng chứng và lỗi nhánh.	S5-WBS07.3, S5-WBS12.1, S5-WBS12.2	Cao	Chưa bắt đầu	S5-G08	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS13.1	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat	Hồi quy, đánh giá và demo	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	4			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS13.2	Đánh giá router và fallback trên bộ câu riêng	Hồi quy, đánh giá và demo	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS13.3	Đối chiếu nhận định xu hướng và citation	Hồi quy, đánh giá và demo	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2	Cao	Chưa bắt đầu	S5-G09	FinMind	5	3			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	S5-WBS13.4	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Hồi quy, đánh giá và demo	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3	Cao	Chưa bắt đầu	S5-G09	FinMind	5	2			Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	2**

🟢 **	Sprint 5 gồm 38 task con. Tuần 1 sửa lỗi và nối truy xuất (58h); tuần 2 tối ưu Chat và nhận định xu hướng (50h). Ngày là khung theo tuần. Phân công tối đa 15h/người/tuần.																											**

🟢 **	Số task	38	Giờ dự kiến	108	Tổng giờ thực tế đã ghi																							**

🟢 **	Sprint 5	S5-WBS01.1	S5-G01	1	Tái hiện lỗi hỏi chức vụ và BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hai câu hỏi trên Web Chat, đối chiếu graph và BCTN trong DB, ghi trace từ router tới truy xuất.	Có hai câu mẫu, dữ liệu đối chiếu và bước chọn sai nguồn hoặc chặn tìm kiếm.	Dữ liệu Sprint 4														**

🟢 **	Sprint 5	S5-WBS01.2	S5-G01	1	Tái hiện lỗi hội thoại và hết hạn token		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy hội thoại nhiều lượt và gửi tin sau khi access token hết hạn.	Có hai ca tái hiện cùng kết quả thực tế và kỳ vọng.	Web Chat hiện có														**

🟢 **	Sprint 5	S5-WBS02.1	S5-G01	1	Tìm điều kiện chặn câu hỏi BCTN		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Theo dõi luồng từ nhận câu hỏi đến bộ lọc tài liệu, chỉ ra điều kiện chặn.	Tái hiện bằng một BCTN có trong DB và xác định đúng bước chặn.	S5-WBS01.1														**

🟢 **	Sprint 5	S5-WBS02.2	S5-G01	1	Chuẩn hóa loại tài liệu và bộ lọc BCTN		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ BCTN, báo cáo thường niên và annual report về cùng loại. Truyền mã công ty và kỳ xuống tìm kiếm.	Ba cách gọi đi cùng bộ lọc và giữ đúng mã công ty, kỳ.	S5-WBS02.1														**

🟢 **	Sprint 5	S5-WBS02.3	S5-G01	1	Kiểm thử truy xuất BCTN bằng dữ liệu thật		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử BCTN có nguồn, sai kỳ, thiếu tài liệu và không có quyền.	Ca có quyền lấy đúng đoạn. Các ca còn lại phản hồi đúng tình trạng.	S5-WBS02.2														**

🟢 **	Sprint 5	S5-WBS03.1	S5-G02	1	Chốt nhãn ý định và ranh giới giữa các nhãn		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa nhãn số liệu, BCTC/BCTN, News, chức vụ, quan hệ, xu hướng và kết hợp.	Có bảng nhãn và ví dụ phân biệt các ý định dễ nhầm.	—														**

🟢 **	Sprint 5	S5-WBS03.2	S5-G02	1	Soạn cụm từ mẫu và bộ câu kiểm thử riêng		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Viết mẫu có dấu, không dấu, viết tắt và cặp dễ nhầm. Tách câu kiểm thử khỏi thư viện dùng để đối chiếu.	Có bộ mẫu gắn nhãn và bộ test riêng, gồm hỏi chức vụ so với hỏi tin bổ nhiệm.	S5-WBS03.1														**

🟢 **	Sprint 5	S5-WBS03.3	S5-G02	1	Vector hóa và lưu phiên bản thư viện		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo vector cho các câu mẫu và lưu nhãn, phiên bản thư viện và embedding.	Có dữ liệu vector và thông tin phiên bản để tái tạo.	S5-WBS03.2														**

🟢 **	Sprint 5	S5-WBS04.1	S5-G02	1	Đối chiếu vector câu hỏi với thư viện		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng mô hình embedding để tính độ tương đồng và lấy nhóm ý định gần nhất.	Trả được các nhóm gần nhất và điểm tương đồng.	S5-WBS03.3														**

🟢 **	Sprint 5	S5-WBS04.2	S5-G02	1	Đặt ngưỡng tin cậy và quy tắc chọn nhánh		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng điểm cao nhất, khoảng cách hai nhóm đầu và thông tin công ty/kỳ để chọn nhánh, hỏi lại hoặc báo cần fallback.	Có đầu ra VECTOR, GRAPH, BOTH, ASK\_CLARIFICATION hoặc tín hiệu fallback theo từng ca.	S5-WBS04.1														**

🟢 **	Sprint 5	S5-WBS04.3	S5-G02	1	Chạy bộ câu kiểm thử router		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy bộ test riêng và ghi nhãn, điểm, lý do và nhánh.	Có bảng kỳ vọng và thực tế, gồm câu chức vụ, kết hợp và thiếu dữ kiện.	S5-WBS04.2, S5-WBS03.2														**

🟢 **	Sprint 5	S5-WBS05.1	S5-G03	1	Nối router vào luồng xử lý tin nhắn Web Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Gọi router trong backend khi Web Chat gửi tin và ghi trace. Có thể chuẩn bị tích hợp bằng mẫu.	Trace xác nhận Web Chat gọi router và chọn nhánh.	S5-WBS04.2														**

🟢 **	Sprint 5	S5-WBS05.2	S5-G03	1	Nối nhánh GRAPH với Neo4j qua adapter hiện có		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng graph adapter để lấy quan hệ đã duyệt, chức vụ và nguồn tương ứng.	Câu hỏi chức vụ trả đúng người, chức vụ và bằng chứng.	S5-WBS05.1, graph có dữ liệu đã duyệt														**

🟢 **	Sprint 5	S5-WBS05.3	S5-G03	1	Kiểm thử graph thật, graph rỗng và lỗi kết nối		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy ca có dữ liệu, không có quan hệ và lỗi Neo4j trên luồng Web Chat.	Trace xác nhận gọi graph thật. Chat phân biệt rỗng và lỗi truy xuất.	S5-WBS05.2														**

🟢 **	Sprint 5	S5-WBS06.1	S5-G04	1	Dùng cơ chế refresh token chung cho request Chat		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Nối request Chat vào luồng auth chung và thử lại có kiểm soát khi nhận 401.	Phiên hợp lệ tiếp tục dùng được sau refresh.	Có thể làm độc lập														**

🟢 **	Sprint 5	S5-WBS06.2	S5-G04	1	Kiểm tra refresh thất bại và chống gửi trùng		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử nhiều request 401, refresh hết hạn và gửi lại tin nhắn.	Không tạo hai tin. Khi refresh hết hạn, yêu cầu đăng nhập lại.	S5-WBS06.1														**

🟢 **	Sprint 5	S5-WBS07.1	S5-G05	1	Chốt điều kiện fallback và JSON phân loại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Quy định điểm thấp, hai nhóm sát nhau hoặc lỗi phân loại. Chốt nhãn cho phép và ngữ cảnh tối thiểu gửi đi.	Có contract phân loại và quy tắc kiểm tra kết quả.	S5-WBS03.1, S5-WBS04.2														**

🟢 **	Sprint 5	S5-WBS07.2	S5-G05	1	Nối AI bên thứ ba vào bước phân loại		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Gọi AI khi cần, giới hạn thời gian, xác thực nhãn và chuyển kết quả về router FinMind. Chuẩn bị bằng phản hồi mẫu.	Nhãn hợp lệ tiếp tục truy xuất trong FinMind. Trace ghi lần gọi.	S5-WBS07.1														**

🟢 **	Sprint 5	S5-WBS07.3	S5-G05	1	Kiểm thử fallback và trường hợp cả hai bước thất bại		Chưa bắt đầu	2		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Thử AI trả đúng, sai nhãn, timeout và câu rõ ý định.	Ca thất bại hỏi lại. Câu rõ ý định xử lý nội bộ.	S5-WBS07.2														**

🟢 **	Sprint 5	S5-WBS08.1	S5-G06	1	Chuẩn bị chuỗi giá theo mã doanh nghiệp		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Chốt khoảng giá, lấy ngày đầu/cuối, số phiên và nguồn theo mã.	Có chuỗi giá mẫu và mức biến động truy được nguồn.	Dữ liệu giá hiện có														**

🟢 **	Sprint 5	S5-WBS08.2	S5-G06	1	Lấy chỉ tiêu từ các kỳ BCTC gần nhất		Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy doanh thu, lợi nhuận, dòng tiền nếu có. Ghi kỳ, đơn vị, ngày công bố nếu có và đoạn nguồn.	Có số liệu theo kỳ cùng bằng chứng gốc.	Dữ liệu BCTC hiện có														**

🟢 **	Sprint 5	S5-WBS08.3	S5-G06	1	Chuẩn hóa đầu vào cho mô hình xu hướng		Chưa bắt đầu	3		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	Ghép mã, chuẩn hóa đơn vị và chọn kỳ so sánh tương đương. Đánh dấu thiếu dữ liệu.	Có đầu vào theo doanh nghiệp, kỳ, đơn vị và trạng thái đủ dữ liệu.	S5-WBS08.1, S5-WBS08.2														**

🟢 **	Sprint 5	S5-WBS09.1	S5-G07	2	Kế thừa công ty, kỳ và chủ đề giữa các lượt		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng phạm vi hội thoại hiện tại, ưu tiên công ty hoặc kỳ mới nếu người dùng thay đổi.	Câu nối tiếp giữ đúng phạm vi và chuyển phạm vi khi được yêu cầu.	S5-WBS05.1														**

🟢 **	Sprint 5	S5-WBS09.2	S5-G07	2	Xử lý liệt kê và giới thiệu tổng quan		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Liệt kê nội dung đang nói. Tổng quan đúng doanh nghiệp và truy xuất thêm khi cần.	Hai câu mẫu chạy đúng trong phiên nhiều lượt.	S5-WBS09.1														**

🟢 **	Sprint 5	S5-WBS09.3	S5-G07	2	Xử lý tổng hợp nãy giờ		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tóm tắt nội dung phiên hiện tại và giữ các nguồn đã dẫn.	Không lẫn nội dung giữa các phiên, nguồn còn đối chiếu được.	S5-WBS09.1														**

🟢 **	Sprint 5	S5-WBS10.1	S5-G06	2	Tính nhóm tín hiệu giá		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tính biến động theo khoảng đã chốt và đánh dấu thiếu phiên hoặc thiếu giá.	Có tín hiệu giá và dữ liệu dùng để tính.	S5-WBS08.1, S5-WBS08.3														**

🟢 **	Sprint 5	S5-WBS10.2	S5-G06	2	Tính nhóm tín hiệu tài chính		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tính thay đổi doanh thu, lợi nhuận và dòng tiền khi có kỳ tương đương.	Có tín hiệu từng chỉ tiêu và nguồn tương ứng.	S5-WBS08.2, S5-WBS08.3														**

🟢 **	Sprint 5	S5-WBS10.3	S5-G06	2	Gộp tín hiệu và trả nhãn xu hướng		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng quy tắc chấm điểm giải thích được để gộp tín hiệu giá và tài chính.	Trả đi lên, đi xuống, trái chiều hoặc chưa đủ dữ liệu. Ca trái chiều thể hiện hai tín hiệu riêng.	S5-WBS10.1, S5-WBS10.2														**

🟢 **	Sprint 5	S5-WBS10.4	S5-G06	2	Kiểm thử quy tắc chấm điểm		Chưa bắt đầu	2		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thử cùng tăng, cùng giảm, trái chiều và thiếu kỳ.	Mỗi nhãn giải thích được bằng số liệu đầu vào.	S5-WBS10.3														**

🟢 **	Sprint 5	S5-WBS11.1	S5-G06	2	Nối ý định xu hướng với mô hình nhận định		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Khi nhận diện câu hỏi xu hướng, gọi mô hình với đúng mã và phạm vi. Chuẩn bị bằng kết quả mẫu trước.	Trace xác nhận Chat gọi mô hình đúng đầu vào.	S5-WBS04.2, S5-WBS05.1, S5-WBS10.3 để nghiệm thu thật														**

🟢 **	Sprint 5	S5-WBS11.2	S5-G06	2	Hiển thị nhận định xu hướng trong Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tách diễn biến giá và tình hình tài chính, ghi kỳ, chỉ tiêu, nguồn và phần còn thiếu.	Chat đưa nhận định đúng công ty, kỳ và có nguồn kiểm tra được.	S5-WBS11.1, S5-WBS10.3														**

🟢 **	Sprint 5	S5-WBS12.1	S5-G08	2	Định dạng câu trả lời theo yêu cầu		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng danh sách cho liệt kê, bảng cho so sánh và tóm tắt cho tổng quan.	Câu trả lời có đúng cấu trúc người dùng yêu cầu.	S5-WBS09.2, S5-WBS09.3 cho ca nối tiếp														**

🟢 **	Sprint 5	S5-WBS12.2	S5-G08	2	Ghép bằng chứng graph và tài liệu cho BOTH		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Ghép kết quả theo đúng mã công ty và kỳ, gắn citation sát nhận định.	Cả hai loại bằng chứng được dùng đúng phạm vi và nguồn.	S5-WBS05.2, nhánh Vector hiện có														**

🟢 **	Sprint 5	S5-WBS12.3	S5-G08	2	Xử lý kết quả rỗng, thiếu nguồn và lỗi một nhánh		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ trình bày phần có căn cứ, ghi rõ phần còn thiếu và thử ca fallback thất bại.	Câu trả lời phân biệt rỗng, thiếu bằng chứng và lỗi nhánh.	S5-WBS07.3, S5-WBS12.1, S5-WBS12.2														**

🟢 **	Sprint 5	S5-WBS13.1	S5-G09	2	Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat		Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy lại ca chức vụ, BCTN, ngữ cảnh và token hết hạn.	Có kết quả pass/fail và trace cho đủ bốn lỗi.	S5-WBS02.3, S5-WBS05.3, S5-WBS06.2, S5-WBS09.2, S5-WBS09.3														**

🟢 **	Sprint 5	S5-WBS13.2	S5-G09	2	Đánh giá router và fallback trên bộ câu riêng		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Đo tỷ lệ chọn đúng nhánh, câu hay nhầm, số lần fallback và thời gian phản hồi.	Có kết quả trên cùng bộ câu để đối chiếu.	S5-WBS04.3, S5-WBS07.3														**

🟢 **	Sprint 5	S5-WBS13.3	S5-G09	2	Đối chiếu nhận định xu hướng và citation		Chưa bắt đầu	3		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu giá và BCTC gốc cho ca đủ dữ liệu, trái chiều và thiếu dữ liệu.	Số liệu, kỳ, nhãn và citation khớp nguồn ở các ca thử.	S5-WBS10.4, S5-WBS11.2, S5-WBS12.2														**

🟢 **	Sprint 5	S5-WBS13.4	S5-G09	2	Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại		Chưa bắt đầu	2		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Tập hợp câu hỏi demo, kỳ vọng, kết quả thực tế, trace và lỗi còn mở.	Có kịch bản demo toàn luồng và danh sách lỗi còn mở.	S5-WBS13.1, S5-WBS13.2, S5-WBS13.3														**

🟢 **					Tổng giờ các task			108	0																			**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	64	2	0.03125	246	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G01	5	Tái hiện lỗi và sửa truy xuất BCTN	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	5	0	0	Chưa bắt đầu	12		Sprint 5 Backlog**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G02	5	Thư viện vector và Hybrid Router	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	16		Sprint 5 Backlog**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G03	5	Web Chat tích hợp Neo4j	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	8		Sprint 5 Backlog**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G04	5	Refresh token cho Chat	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	5		Sprint 5 Backlog**

🟢 **Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G05	5	Fallback phân loại bằng AI	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	7		Sprint 5 Backlog**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G06	5	Nhận định xu hướng doanh nghiệp	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	9	0	0	Chưa bắt đầu	29		Sprint 5 Backlog**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G07	5	Ngữ cảnh và thao tác hội thoại	Giữ phạm vi đúng, xử lý liệt kê, tổng quan và tổng hợp trong phiên hiện tại.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	9		Sprint 5 Backlog**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G08	5	Tối ưu câu trả lời và bằng chứng	Định dạng đúng ý định, gắn nguồn đúng nhận định và xử lý khi một nhánh thiếu kết quả.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	10		Sprint 5 Backlog**

🟢 **Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G09	5	Hồi quy, đánh giá và demo	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	12		Sprint 5 Backlog**

🟢 **Tổng task	197		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						**

🟢 **Độ hoàn thành	0.5329949238578681		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **S5-G01	5	Tái hiện lỗi và sửa truy xuất BCTN	S5-WBS01.1: Tái hiện lỗi hỏi chức vụ và BCTN**

🟢 **S5-WBS01.2: Tái hiện lỗi hội thoại và hết hạn token**

🟢 **S5-WBS02.1: Tìm điều kiện chặn câu hỏi BCTN**

🟢 **S5-WBS02.2: Chuẩn hóa loại tài liệu và bộ lọc BCTN**

🟢 **S5-WBS02.3: Kiểm thử truy xuất BCTN bằng dữ liệu thật	Có trace tái hiện bốn lỗi Sprint 4 và truy xuất được BCTN đúng công ty, kỳ và quyền.	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	5	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G02	5	Thư viện vector và Hybrid Router	S5-WBS03.1: Chốt nhãn ý định và ranh giới giữa các nhãn**

🟢 **S5-WBS03.2: Soạn cụm từ mẫu và bộ câu kiểm thử riêng**

🟢 **S5-WBS03.3: Vector hóa và lưu phiên bản thư viện**

🟢 **S5-WBS04.1: Đối chiếu vector câu hỏi với thư viện**

🟢 **S5-WBS04.2: Đặt ngưỡng tin cậy và quy tắc chọn nhánh**

🟢 **S5-WBS04.3: Chạy bộ câu kiểm thử router	Phân loại ý định bằng thư viện vector có phiên bản, chọn tuyến đúng và có bộ câu kiểm thử riêng.	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	6	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G03	5	Web Chat tích hợp Neo4j	S5-WBS05.1: Nối router vào luồng xử lý tin nhắn Web Chat**

🟢 **S5-WBS05.2: Nối nhánh GRAPH với Neo4j qua adapter hiện có**

🟢 **S5-WBS05.3: Kiểm thử graph thật, graph rỗng và lỗi kết nối	Web Chat gọi router, lấy quan hệ đã duyệt và nguồn. Phân biệt graph rỗng với lỗi kết nối.	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G04	5	Refresh token cho Chat	S5-WBS06.1: Dùng cơ chế refresh token chung cho request Chat**

🟢 **S5-WBS06.2: Kiểm tra refresh thất bại và chống gửi trùng	Chat tiếp tục sau refresh hợp lệ, xử lý phiên hết hạn và tránh gửi trùng.	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G05	5	Fallback phân loại bằng AI	S5-WBS07.1: Chốt điều kiện fallback và JSON phân loại**

🟢 **S5-WBS07.2: Nối AI bên thứ ba vào bước phân loại**

🟢 **S5-WBS07.3: Kiểm thử fallback và trường hợp cả hai bước thất bại	Chỉ gọi fallback khi cần. Kiểm tra nhãn, ghi trace và hỏi lại khi không phân loại được.	Sun Nov 15 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G06	5	Nhận định xu hướng doanh nghiệp	S5-WBS08.1: Chuẩn bị chuỗi giá theo mã doanh nghiệp**

🟢 **S5-WBS08.2: Lấy chỉ tiêu từ các kỳ BCTC gần nhất**

🟢 **S5-WBS08.3: Chuẩn hóa đầu vào cho mô hình xu hướng**

🟢 **S5-WBS10.1: Tính nhóm tín hiệu giá**

🟢 **S5-WBS10.2: Tính nhóm tín hiệu tài chính**

🟢 **S5-WBS10.3: Gộp tín hiệu và trả nhãn xu hướng**

🟢 **S5-WBS10.4: Kiểm thử quy tắc chấm điểm**

🟢 **S5-WBS11.1: Nối ý định xu hướng với mô hình nhận định**

🟢 **S5-WBS11.2: Hiển thị nhận định xu hướng trong Chat	Nhận định giải thích được từ giá và BCTC, có kỳ, nguồn và trạng thái dữ liệu thiếu hoặc trái chiều.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	9	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G07	5	Ngữ cảnh và thao tác hội thoại	S5-WBS09.1: Kế thừa công ty, kỳ và chủ đề giữa các lượt**

🟢 **S5-WBS09.2: Xử lý liệt kê và giới thiệu tổng quan**

🟢 **S5-WBS09.3: Xử lý tổng hợp nãy giờ	Giữ phạm vi đúng, xử lý liệt kê, tổng quan và tổng hợp trong phiên hiện tại.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G08	5	Tối ưu câu trả lời và bằng chứng	S5-WBS12.1: Định dạng câu trả lời theo yêu cầu**

🟢 **S5-WBS12.2: Ghép bằng chứng graph và tài liệu cho BOTH**

🟢 **S5-WBS12.3: Xử lý kết quả rỗng, thiếu nguồn và lỗi một nhánh	Định dạng đúng ý định, gắn nguồn đúng nhận định và xử lý khi một nhánh thiếu kết quả.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	3	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **S5-G09	5	Hồi quy, đánh giá và demo	S5-WBS13.1: Chạy hồi quy bốn lỗi Sprint 4 trên Web Chat**

🟢 **S5-WBS13.2: Đánh giá router và fallback trên bộ câu riêng**

🟢 **S5-WBS13.3: Đối chiếu nhận định xu hướng và citation**

🟢 **S5-WBS13.4: Chuẩn bị kịch bản demo và tổng hợp lỗi còn lại	Có kết quả hồi quy, đánh giá router/fallback, đối chiếu nguồn và kịch bản demo.	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.**

~~								5	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 22 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	150	0	36 task chi tiết; lịch và phân công đề xuất.~~

~~	S5-WBS01	Cài kiểm tra độ liên quan bằng chứng	Kiểm tra bằng chứng trước khi trả lời	Đọc điểm đã chuẩn hóa và ngưỡng theo cấu hình; trả PASS hoặc lý do không đạt.	Bằng chứng không liên quan bị chặn trước khi sinh nháp.~~

~~Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.~~

~~Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.~~

~~Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.~~

~~Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.~~

~~Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.~~

~~Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.~~

~~Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.~~

~~Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.~~

~~Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.~~

~~Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.~~

~~Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.~~

~~Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.~~

~~Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Bằng chứng không liên quan bị chặn trước khi sinh nháp.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G01	FinMind	5	4		Thái Quốc Hưng	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS02	Cài kiểm tra kỳ độ mới và phiên bản	Kiểm tra bằng chứng trước khi trả lời	So với ngày chốt corpus, kỳ và bản sửa đổi hợp lệ; không dùng ngày chạy làm chuẩn độ mới duy nhất.	Bằng chứng không liên quan bị chặn trước khi sinh nháp.~~

~~Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G01	FinMind	5	5		Thái Quốc Hưng	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS03	Cài kiểm tra độ phủ và mâu thuẫn	Kiểm tra bằng chứng trước khi trả lời	Kiểm tra nhánh bắt buộc, nguồn của từng công ty và số liệu xung đột theo chính sách SRS.	Bằng chứng không liên quan bị chặn trước khi sinh nháp.~~

~~Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G01	FinMind	5	4		Nguyễn Minh Quân	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS04	Cho mọi tuyến B3 đi qua Gate	Kiểm tra bằng chứng trước khi trả lời	Áp dụng Gate cả câu trả lời số liệu không dùng Gemini; ghi quyết định vào trace.	Bằng chứng không liên quan bị chặn trước khi sinh nháp.~~

~~Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G01	FinMind	5	4		Đinh Huỳnh Vũ	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS05	Tạo context và danh sách citation ID	Sinh nháp trong context được duyệt	Chỉ dùng bằng chứng đã qua Gate, giới hạn số đoạn và token theo cấu hình.	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.~~

~~Nháp theo schema và có candidate evidence cho các nhận định.~~

~~Nháp theo schema và có candidate evidence cho các nhận định.~~

~~Nháp theo schema và có candidate evidence cho các nhận định.~~

~~Nháp theo schema và có candidate evidence cho các nhận định.~~

~~Nháp theo schema và có candidate evidence cho các nhận định.~~

~~Nháp theo schema và có candidate evidence cho các nhận định.~~

~~Nháp sai cấu trúc không được hiển thị như kết quả cuối.~~

~~Nháp sai cấu trúc không được hiển thị như kết quả cuối.~~

~~Nháp sai cấu trúc không được hiển thị như kết quả cuối.~~

~~Nháp sai cấu trúc không được hiển thị như kết quả cuối.~~

~~Nháp sai cấu trúc không được hiển thị như kết quả cuối.~~

~~Nháp sai cấu trúc không được hiển thị như kết quả cuối.~~

~~Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4		Hồ Phạm Đăng Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS06	Gọi Gemini để tạo nháp có cấu trúc	Sinh nháp trong context được duyệt	Yêu cầu tách từng nhận định, dữ kiện và ID bằng chứng; lưu phiên bản model và prompt.	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.~~

~~Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Nháp theo schema và có candidate evidence cho các nhận định.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4		Nguyễn Minh Quân	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS07	Kiểm tra định dạng nháp từ Gemini	Sinh nháp trong context được duyệt	Từ chối JSON lỗi, trường thiếu hoặc ID lạ trước khi đưa sang citation binding.	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.~~

~~Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Nháp sai cấu trúc không được hiển thị như kết quả cuối.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4		Đinh Huỳnh Vũ	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS08	Nối tuyến nháp số liệu chính xác	Sinh nháp trong context được duyệt	Dùng nháp từ công thức cố định cho câu phù hợp, nhưng vẫn đi qua citation và verifier.	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.~~

~~Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G02	FinMind	5	4		Hồ Phạm Đăng Nhân	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS09	Gắn từng nhận định với Evidence	Gắn trích dẫn và mở nguồn chứng minh	Tạo Claim và Citation từ ID nội bộ đã duyệt; không nhận URL tự do làm trích dẫn.	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.~~

~~ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.~~

~~ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.~~

~~ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.~~

~~ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.~~

~~ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.~~

~~ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.~~

~~Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.~~

~~Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.~~

~~Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.~~

~~Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.~~

~~Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.~~

~~Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.~~

~~Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G03	FinMind	5	4		Hồ Phạm Đăng Nhân	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS10	Tạo API mở chi tiết trích dẫn	Gắn trích dẫn và mở nguồn chứng minh	Trả tiêu đề, publisher, ngày, hash, kỳ và vị trí trang bảng dòng hoặc mục.	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.~~

~~Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G03	FinMind	5	4		Trần Diệu Huyền	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS11	Hiện nguồn và đoạn liên quan trên UI	Gắn trích dẫn và mở nguồn chứng minh	Làm preview hoặc link nguồn chính thức; chỉ rõ passage, fact hoặc path đang chứng minh.	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.~~

~~Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G03	FinMind	5	4		Nguyễn Minh Quân	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS12	Hiện vết tính toán và nguồn từng edge	Gắn trích dẫn và mở nguồn chứng minh	Với số tính toán, hiện input và công thức; với graph, hiện provenance từng bước.	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.~~

~~Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G03	FinMind	5	5		Đinh Huỳnh Vũ	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS13	Kiểm tra số đơn vị kỳ và công ty	Kiểm chứng nháp trước khi phát hành	So các số trong nháp với FinancialFact; kiểm tra unit, period, scope và chính sách dung sai.	Nháp sai số hoặc sai phạm vi không đạt verifier.~~

~~Kết quả tính sai hoặc thiếu input bị chặn.~~

~~Kết quả tính sai hoặc thiếu input bị chặn.~~

~~Kết quả tính sai hoặc thiếu input bị chặn.~~

~~Kết quả tính sai hoặc thiếu input bị chặn.~~

~~Kết quả tính sai hoặc thiếu input bị chặn.~~

~~Kết quả tính sai hoặc thiếu input bị chặn.~~

~~Nhận định không được hỗ trợ không thể được phát hành.~~

~~Nhận định không được hỗ trợ không thể được phát hành.~~

~~Nhận định không được hỗ trợ không thể được phát hành.~~

~~Nhận định không được hỗ trợ không thể được phát hành.~~

~~Nhận định không được hỗ trợ không thể được phát hành.~~

~~Nhận định không được hỗ trợ không thể được phát hành.~~

~~UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Nháp sai số hoặc sai phạm vi không đạt verifier.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G04	FinMind	5	6		Trần Diệu Huyền	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS14	Kiểm tra công thức và đầu vào	Kiểm chứng nháp trước khi phát hành	Đối chiếu Calculation với công thức đã duyệt và các fact đầu vào của kết quả.	Nháp sai số hoặc sai phạm vi không đạt verifier.~~

~~UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Kết quả tính sai hoặc thiếu input bị chặn.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G04	FinMind	5	3		Nguyễn Minh Quân	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS15	Kiểm tra trích dẫn và độ phủ nhận định	Kiểm chứng nháp trước khi phát hành	Xác minh citation ID được phép và nguồn có chứng minh nhận định; kiểm tra các ý quan trọng còn thiếu nguồn.	Nháp sai số hoặc sai phạm vi không đạt verifier.~~

~~UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Nhận định không được hỗ trợ không thể được phát hành.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G04	FinMind	5	3		Hồ Phạm Đăng Nhân	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS16	Tạo Response Composer sau PASS	Kiểm chứng nháp trước khi phát hành	Chỉ dựng câu trả lời cuối khi verifier đạt; giữ trạng thái partial hoặc thiếu dữ liệu theo chính sách.	Nháp sai số hoặc sai phạm vi không đạt verifier.~~

~~UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G04	FinMind	5	2		Đinh Huỳnh Vũ	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS17	Cài tối đa một lần sửa có kiểm soát	Sửa nháp có giới hạn và từ chối an toàn	Sửa nháp bằng đúng bằng chứng đã duyệt, không tìm nguồn tùy tiện hoặc lặp vô hạn.	Trace ghi lần sửa và không vượt giới hạn một lần.~~

~~Nháp sửa chỉ được phát hành sau kết quả PASS mới.~~

~~Nháp sửa chỉ được phát hành sau kết quả PASS mới.~~

~~Nháp sửa chỉ được phát hành sau kết quả PASS mới.~~

~~Nháp sửa chỉ được phát hành sau kết quả PASS mới.~~

~~Nháp sửa chỉ được phát hành sau kết quả PASS mới.~~

~~Nháp sửa chỉ được phát hành sau kết quả PASS mới.~~

~~Không có số hoặc nguồn tự tạo trong fallback.~~

~~Không có số hoặc nguồn tự tạo trong fallback.~~

~~Không có số hoặc nguồn tự tạo trong fallback.~~

~~Không có số hoặc nguồn tự tạo trong fallback.~~

~~Không có số hoặc nguồn tự tạo trong fallback.~~

~~Không có số hoặc nguồn tự tạo trong fallback.~~

~~Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Trace ghi lần sửa và không vượt giới hạn một lần.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G05	FinMind	5	4		Thái Quốc Hưng	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS18	Gắn lại trích dẫn và kiểm tra nháp sửa	Sửa nháp có giới hạn và từ chối an toàn	Chạy citation binding và verifier lại sau sửa, không dùng kết quả kiểm tra cũ.	Trace ghi lần sửa và không vượt giới hạn một lần.~~

~~Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Nháp sửa chỉ được phát hành sau kết quả PASS mới.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G05	FinMind	5	4		Thái Quốc Hưng	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS19	Trả lý do thiếu dữ liệu hoặc lỗi kiểm chứng	Sửa nháp có giới hạn và từ chối an toàn	Dùng mã lý do rõ ràng khi Gate fail hoặc sửa vẫn fail; chỉ nêu thông tin đã xác minh.	Trace ghi lần sửa và không vượt giới hạn một lần.~~

~~Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Không có số hoặc nguồn tự tạo trong fallback.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G05	FinMind	5	4		Nguyễn Minh Quân	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS20	Từ chối tư vấn giao dịch ngoài phạm vi	Sửa nháp có giới hạn và từ chối an toàn	Chặn buy sell hold, target price và nội dung ngoài phạm vi; gợi ý câu hỏi nghiên cứu phù hợp.	Trace ghi lần sửa và không vượt giới hạn một lần.~~

~~Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G05	FinMind	5	4		Đinh Huỳnh Vũ	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS21	Làm màn hình câu hỏi và bộ lọc	Hoàn thiện giao diện Copilot	Cho nhập câu hỏi Việt Anh, chọn công ty và kỳ; kiểm tra chiều dài và định dạng trước khi gửi.	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.~~

~~Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.~~

~~Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.~~

~~Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.~~

~~Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.~~

~~Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.~~

~~Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.~~

~~Marker mở được đúng trích dẫn của nhận định.~~

~~Marker mở được đúng trích dẫn của nhận định.~~

~~Marker mở được đúng trích dẫn của nhận định.~~

~~Marker mở được đúng trích dẫn của nhận định.~~

~~Marker mở được đúng trích dẫn của nhận định.~~

~~Marker mở được đúng trích dẫn của nhận định.~~

~~Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Đinh Huỳnh Vũ	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS22	Hiện trạng thái chờ và lỗi yêu cầu	Hoàn thiện giao diện Copilot	Hiển thị đang xử lý, timeout và thử lại theo chính sách; giữ trace ID cho chẩn đoán.	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.~~

~~Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Đinh Huỳnh Vũ	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS23	Hiện câu trả lời và citation marker	Hoàn thiện giao diện Copilot	Trình bày từng nhận định với marker nguồn, đơn vị, kỳ và nhãn thiếu dữ liệu nếu có.	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.~~

~~Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Marker mở được đúng trích dẫn của nhận định.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Hồ Phạm Đăng Nhân	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS24	Nối đăng nhập chọn công ty và Copilot	Hoàn thiện giao diện Copilot	Giữ phiên hợp lệ và context công ty đã chọn; xử lý hết hạn phiên và xóa lựa chọn.	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.~~

~~Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G06	FinMind	5	4		Nguyễn Minh Quân	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS25	Kiểm tra phạm vi câu hỏi so sánh	So sánh công ty và tích hợp B3	Yêu cầu ít nhất hai công ty trong corpus và chỉ tiêu có thể đối chiếu.	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.~~

~~Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.~~

~~Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.~~

~~Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.~~

~~Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.~~

~~Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.~~

~~Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.~~

~~Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.~~

~~Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.~~

~~Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.~~

~~Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.~~

~~Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.~~

~~Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.~~

~~Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G07	FinMind	5	4		Hồ Phạm Đăng Nhân	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS26	Căn chỉnh số liệu giữa các công ty	So sánh công ty và tích hợp B3	Đối chiếu kỳ, đơn vị và phạm vi báo cáo; không gộp số không tương đồng thành một kết luận.	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.~~

~~Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G07	FinMind	5	4		Trần Diệu Huyền	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS27	Kiểm chứng nhận định so sánh	So sánh công ty và tích hợp B3	Chạy Gate, citation và verifier cho bằng chứng từng công ty; chỉ trả phần được hỗ trợ.	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.~~

~~Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G07	FinMind	5	4		Nguyễn Minh Quân	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS28	Tích hợp cấu hình B3 và trace đầy đủ	So sánh công ty và tích hợp B3	Nối retrieval, Gate, draft, citation, verifier, composer và một lần sửa; ghi từng bước.	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.~~

~~Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G07	FinMind	5	7		Hồ Phạm Đăng Nhân	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS29	Kiểm thử prompt injection trong tài liệu	An toàn và chuẩn bị đánh giá cuối	Dùng các ca tài liệu chứa lệnh lạ; giữ tài liệu là dữ liệu, không cho thay đổi quyền hoặc policy.	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.~~

~~B3 không bịa số hoặc locator trong các ca được thử.~~

~~B3 không bịa số hoặc locator trong các ca được thử.~~

~~B3 không bịa số hoặc locator trong các ca được thử.~~

~~B3 không bịa số hoặc locator trong các ca được thử.~~

~~B3 không bịa số hoặc locator trong các ca được thử.~~

~~B3 không bịa số hoặc locator trong các ca được thử.~~

~~Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.~~

~~Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.~~

~~Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.~~

~~Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.~~

~~Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.~~

~~Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.~~

~~Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G08	FinMind	5	5		Trần Diệu Huyền	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS30	Kiểm thử thiếu bằng chứng và lỗi nguồn	An toàn và chuẩn bị đánh giá cuối	Thử các ca insufficient-data và adversarial từ bộ hiệu chỉnh; không dùng nhãn bộ cuối để tuning.	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.~~

~~Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	B3 không bịa số hoặc locator trong các ca được thử.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G08	FinMind	5	3		Nguyễn Minh Quân	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS31	Đánh giá khả năng người dùng kiểm tra nguồn	An toàn và chuẩn bị đánh giá cuối	Thực hiện nghiên cứu NFR06 theo protocol, ghi task success và thời gian xác minh claim.	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.~~

~~Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G08	FinMind	5	3		Đinh Huỳnh Vũ	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS32	Gắn tag runtime và evaluator trước final	An toàn và chuẩn bị đánh giá cuối	Khóa corpus, model, prompt, thresholds, code và phiên bản judge sau tuning trên calibration.	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.~~

~~Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G08	FinMind	5	2		Thái Quốc Hưng	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS33	Kiểm thử Gate citation và verifier	Tích hợp và nghiệm thu Sprint 5	Chạy các ca PASS FAIL, sai số, ID nguồn lạ và tuyến không dùng Gemini.	Không có nháp chưa kiểm chứng được phát hành.~~

~~Có kết quả test lại trước khi đóng lỗi.~~

~~Có kết quả test lại trước khi đóng lỗi.~~

~~Có kết quả test lại trước khi đóng lỗi.~~

~~Có kết quả test lại trước khi đóng lỗi.~~

~~Có kết quả test lại trước khi đóng lỗi.~~

~~Có kết quả test lại trước khi đóng lỗi.~~

~~Kết quả và trace thống nhất, không vượt policy.~~

~~Kết quả và trace thống nhất, không vượt policy.~~

~~Kết quả và trace thống nhất, không vượt policy.~~

~~Kết quả và trace thống nhất, không vượt policy.~~

~~Kết quả và trace thống nhất, không vượt policy.~~

~~Kết quả và trace thống nhất, không vượt policy.~~

~~Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Không có nháp chưa kiểm chứng được phát hành.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G09	FinMind	5	5		Trần Diệu Huyền	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS34	Sửa lỗi kiểm chứng và nguồn tuần 1	Tích hợp và nghiệm thu Sprint 5	Sửa lỗi trong log đã ghi; chạy lại đúng ca chứng minh lỗi được xử lý.	Không có nháp chưa kiểm chứng được phát hành.~~

~~Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Có kết quả test lại trước khi đóng lỗi.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G09	FinMind	5	6		Thái Quốc Hưng	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S5-WBS35	Kiểm thử B3 so sánh và bảo mật	Tích hợp và nghiệm thu Sprint 5	Chạy luồng đầy đủ, một lần sửa, fallback và giới hạn API; đo cả thời gian sửa.	Không có nháp chưa kiểm chứng được phát hành.~~

~~Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Kết quả và trace thống nhất, không vượt policy.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G09	FinMind	5	5		Thái Quốc Hưng	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S5-WBS36	Review B3 và điều kiện mở final	Tích hợp và nghiệm thu Sprint 5	Đối chiếu các yêu cầu Must và cấu hình đóng băng; ghi optional UI được hoãn nếu thiếu thời gian.	Không có nháp chưa kiểm chứng được phát hành.~~

~~Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S5-G09	FinMind	5	6		Trần Diệu Huyền	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	Ngày, giờ và phân công là đề xuất. Tuần 1 và 2 tính từ thứ Hai bắt đầu sprint; chỉ làm khi đầu vào đã sẵn sàng.																											~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi																							~~

~~	Sprint 5	S5-WBS01	S5-G01	1	Cài kiểm tra độ liên quan bằng chứng	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Đọc điểm đã chuẩn hóa và ngưỡng theo cấu hình; trả PASS hoặc lý do không đạt.	Bằng chứng không liên quan bị chặn trước khi sinh nháp.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 5	S5-WBS02	S5-G01	1	Cài kiểm tra kỳ độ mới và phiên bản	Thái Quốc Hưng	Chưa bắt đầu	5		Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	So với ngày chốt corpus, kỳ và bản sửa đổi hợp lệ; không dùng ngày chạy làm chuẩn độ mới duy nhất.	Bằng chứng sai kỳ hoặc sai phiên bản có mã lý do cụ thể.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 5	S5-WBS03	S5-G01	1	Cài kiểm tra độ phủ và mâu thuẫn	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra nhánh bắt buộc, nguồn của từng công ty và số liệu xung đột theo chính sách SRS.	Thiếu phần bắt buộc không được đánh dấu đủ bằng chứng.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 5	S5-WBS04	S5-G01	1	Cho mọi tuyến B3 đi qua Gate	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Áp dụng Gate cả câu trả lời số liệu không dùng Gemini; ghi quyết định vào trace.	Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 5	S5-WBS05	S5-G02	1	Tạo context và danh sách citation ID	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ dùng bằng chứng đã qua Gate, giới hạn số đoạn và token theo cấu hình.	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.	Kiểm tra đầu ra liên quan của S5-G01 trước khi làm.														~~

~~	Sprint 5	S5-WBS06	S5-G02	1	Gọi Gemini để tạo nháp có cấu trúc	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Yêu cầu tách từng nhận định, dữ kiện và ID bằng chứng; lưu phiên bản model và prompt.	Nháp theo schema và có candidate evidence cho các nhận định.	Kiểm tra đầu ra liên quan của S5-G01 trước khi làm.														~~

~~	Sprint 5	S5-WBS07	S5-G02	1	Kiểm tra định dạng nháp từ Gemini	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Từ chối JSON lỗi, trường thiếu hoặc ID lạ trước khi đưa sang citation binding.	Nháp sai cấu trúc không được hiển thị như kết quả cuối.	Kiểm tra đầu ra liên quan của S5-G01 trước khi làm.														~~

~~	Sprint 5	S5-WBS08	S5-G02	1	Nối tuyến nháp số liệu chính xác	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng nháp từ công thức cố định cho câu phù hợp, nhưng vẫn đi qua citation và verifier.	Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Kiểm tra đầu ra liên quan của S5-G01 trước khi làm.														~~

~~	Sprint 5	S5-WBS09	S5-G03	1	Gắn từng nhận định với Evidence	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Tạo Claim và Citation từ ID nội bộ đã duyệt; không nhận URL tự do làm trích dẫn.	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.	Kiểm tra đầu ra liên quan của S5-G02 trước khi làm.														~~

~~	Sprint 5	S5-WBS10	S5-G03	1	Tạo API mở chi tiết trích dẫn	Trần Diệu Huyền	Chưa bắt đầu	4		Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Trả tiêu đề, publisher, ngày, hash, kỳ và vị trí trang bảng dòng hoặc mục.	ID hợp lệ mở đúng metadata; ID không thuộc câu trả lời bị chặn.	Kiểm tra đầu ra liên quan của S5-G02 trước khi làm.														~~

~~	Sprint 5	S5-WBS11	S5-G03	1	Hiện nguồn và đoạn liên quan trên UI	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Làm preview hoặc link nguồn chính thức; chỉ rõ passage, fact hoặc path đang chứng minh.	Người đọc biết nguồn nào hỗ trợ nhận định đang chọn.	Kiểm tra đầu ra liên quan của S5-G02 trước khi làm.														~~

~~	Sprint 5	S5-WBS12	S5-G03	1	Hiện vết tính toán và nguồn từng edge	Đinh Huỳnh Vũ	Chưa bắt đầu	5		Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Với số tính toán, hiện input và công thức; với graph, hiện provenance từng bước.	Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Kiểm tra đầu ra liên quan của S5-G02 trước khi làm.														~~

~~	Sprint 5	S5-WBS13	S5-G04	1	Kiểm tra số đơn vị kỳ và công ty	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	So các số trong nháp với FinancialFact; kiểm tra unit, period, scope và chính sách dung sai.	Nháp sai số hoặc sai phạm vi không đạt verifier.	Kiểm tra đầu ra liên quan của S5-G03 trước khi làm.														~~

~~	Sprint 5	S5-WBS14	S5-G04	1	Kiểm tra công thức và đầu vào	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Nov 10 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu Calculation với công thức đã duyệt và các fact đầu vào của kết quả.	Kết quả tính sai hoặc thiếu input bị chặn.	Kiểm tra đầu ra liên quan của S5-G03 trước khi làm.														~~

~~	Sprint 5	S5-WBS15	S5-G04	1	Kiểm tra trích dẫn và độ phủ nhận định	Hồ Phạm Đăng Nhân	Chưa bắt đầu	3		Wed Nov 11 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Xác minh citation ID được phép và nguồn có chứng minh nhận định; kiểm tra các ý quan trọng còn thiếu nguồn.	Nhận định không được hỗ trợ không thể được phát hành.	Kiểm tra đầu ra liên quan của S5-G03 trước khi làm.														~~

~~	Sprint 5	S5-WBS16	S5-G04	1	Tạo Response Composer sau PASS	Đinh Huỳnh Vũ	Chưa bắt đầu	2		Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Chỉ dựng câu trả lời cuối khi verifier đạt; giữ trạng thái partial hoặc thiếu dữ liệu theo chính sách.	UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Kiểm tra đầu ra liên quan của S5-G03 trước khi làm.														~~

~~	Sprint 5	S5-WBS17	S5-G05	2	Cài tối đa một lần sửa có kiểm soát	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Sửa nháp bằng đúng bằng chứng đã duyệt, không tìm nguồn tùy tiện hoặc lặp vô hạn.	Trace ghi lần sửa và không vượt giới hạn một lần.	Kiểm tra đầu ra liên quan của S5-G04 trước khi làm.														~~

~~	Sprint 5	S5-WBS18	S5-G05	2	Gắn lại trích dẫn và kiểm tra nháp sửa	Thái Quốc Hưng	Chưa bắt đầu	4		Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy citation binding và verifier lại sau sửa, không dùng kết quả kiểm tra cũ.	Nháp sửa chỉ được phát hành sau kết quả PASS mới.	Kiểm tra đầu ra liên quan của S5-G04 trước khi làm.														~~

~~	Sprint 5	S5-WBS19	S5-G05	2	Trả lý do thiếu dữ liệu hoặc lỗi kiểm chứng	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng mã lý do rõ ràng khi Gate fail hoặc sửa vẫn fail; chỉ nêu thông tin đã xác minh.	Không có số hoặc nguồn tự tạo trong fallback.	Kiểm tra đầu ra liên quan của S5-G04 trước khi làm.														~~

~~	Sprint 5	S5-WBS20	S5-G05	2	Từ chối tư vấn giao dịch ngoài phạm vi	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	Chặn buy sell hold, target price và nội dung ngoài phạm vi; gợi ý câu hỏi nghiên cứu phù hợp.	Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Kiểm tra đầu ra liên quan của S5-G04 trước khi làm.														~~

~~	Sprint 5	S5-WBS21	S5-G06	2	Làm màn hình câu hỏi và bộ lọc	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Cho nhập câu hỏi Việt Anh, chọn công ty và kỳ; kiểm tra chiều dài và định dạng trước khi gửi.	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.	Kiểm tra đầu ra liên quan của S5-G05 trước khi làm.														~~

~~	Sprint 5	S5-WBS22	S5-G06	2	Hiện trạng thái chờ và lỗi yêu cầu	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Hiển thị đang xử lý, timeout và thử lại theo chính sách; giữ trace ID cho chẩn đoán.	Người dùng không nhầm yêu cầu lỗi với câu trả lời hoàn tất.	Kiểm tra đầu ra liên quan của S5-G05 trước khi làm.														~~

~~	Sprint 5	S5-WBS23	S5-G06	2	Hiện câu trả lời và citation marker	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Trình bày từng nhận định với marker nguồn, đơn vị, kỳ và nhãn thiếu dữ liệu nếu có.	Marker mở được đúng trích dẫn của nhận định.	Kiểm tra đầu ra liên quan của S5-G05 trước khi làm.														~~

~~	Sprint 5	S5-WBS24	S5-G06	2	Nối đăng nhập chọn công ty và Copilot	Nguyễn Minh Quân	Chưa bắt đầu	4		Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	Giữ phiên hợp lệ và context công ty đã chọn; xử lý hết hạn phiên và xóa lựa chọn.	Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Kiểm tra đầu ra liên quan của S5-G05 trước khi làm.														~~

~~	Sprint 5	S5-WBS25	S5-G07	2	Kiểm tra phạm vi câu hỏi so sánh	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Yêu cầu ít nhất hai công ty trong corpus và chỉ tiêu có thể đối chiếu.	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.	Kiểm tra đầu ra liên quan của S5-G06 trước khi làm.														~~

~~	Sprint 5	S5-WBS26	S5-G07	2	Căn chỉnh số liệu giữa các công ty	Trần Diệu Huyền	Chưa bắt đầu	4		Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu kỳ, đơn vị và phạm vi báo cáo; không gộp số không tương đồng thành một kết luận.	Bảng so sánh nêu giả định và từng khoảng trống dữ liệu.	Kiểm tra đầu ra liên quan của S5-G06 trước khi làm.														~~

~~	Sprint 5	S5-WBS27	S5-G07	2	Kiểm chứng nhận định so sánh	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy Gate, citation và verifier cho bằng chứng từng công ty; chỉ trả phần được hỗ trợ.	Không so sánh một cặp khi thiếu dữ kiện bắt buộc của một bên.	Kiểm tra đầu ra liên quan của S5-G06 trước khi làm.														~~

~~	Sprint 5	S5-WBS28	S5-G07	2	Tích hợp cấu hình B3 và trace đầy đủ	Hồ Phạm Đăng Nhân	Chưa bắt đầu	7		Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	Nối retrieval, Gate, draft, citation, verifier, composer và một lần sửa; ghi từng bước.	Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Kiểm tra đầu ra liên quan của S5-G06 trước khi làm.														~~

~~	Sprint 5	S5-WBS29	S5-G08	2	Kiểm thử prompt injection trong tài liệu	Trần Diệu Huyền	Chưa bắt đầu	5		Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng các ca tài liệu chứa lệnh lạ; giữ tài liệu là dữ liệu, không cho thay đổi quyền hoặc policy.	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.	Kiểm tra đầu ra liên quan của S5-G07 trước khi làm.														~~

~~	Sprint 5	S5-WBS30	S5-G08	2	Kiểm thử thiếu bằng chứng và lỗi nguồn	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Nov 17 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thử các ca insufficient-data và adversarial từ bộ hiệu chỉnh; không dùng nhãn bộ cuối để tuning.	B3 không bịa số hoặc locator trong các ca được thử.	Kiểm tra đầu ra liên quan của S5-G07 trước khi làm.														~~

~~	Sprint 5	S5-WBS31	S5-G08	2	Đánh giá khả năng người dùng kiểm tra nguồn	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Wed Nov 18 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Thực hiện nghiên cứu NFR06 theo protocol, ghi task success và thời gian xác minh claim.	Có dữ liệu quan sát thật, consent và kết quả thay vì chỉ tuyên bố dễ dùng.	Kiểm tra đầu ra liên quan của S5-G07 trước khi làm.														~~

~~	Sprint 5	S5-WBS32	S5-G08	2	Gắn tag runtime và evaluator trước final	Thái Quốc Hưng	Chưa bắt đầu	2		Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	Khóa corpus, model, prompt, thresholds, code và phiên bản judge sau tuning trên calibration.	Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Kiểm tra đầu ra liên quan của S5-G07 trước khi làm.														~~

~~	Sprint 5	S5-WBS33	S5-G09	1	Kiểm thử Gate citation và verifier	Trần Diệu Huyền	Chưa bắt đầu	5		Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy các ca PASS FAIL, sai số, ID nguồn lạ và tuyến không dùng Gemini.	Không có nháp chưa kiểm chứng được phát hành.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 5	S5-WBS34	S5-G09	1	Sửa lỗi kiểm chứng và nguồn tuần 1	Thái Quốc Hưng	Chưa bắt đầu	6		Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	Sửa lỗi trong log đã ghi; chạy lại đúng ca chứng minh lỗi được xử lý.	Có kết quả test lại trước khi đóng lỗi.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 5	S5-WBS35	S5-G09	2	Kiểm thử B3 so sánh và bảo mật	Thái Quốc Hưng	Chưa bắt đầu	5		Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy luồng đầy đủ, một lần sửa, fallback và giới hạn API; đo cả thời gian sửa.	Kết quả và trace thống nhất, không vượt policy.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 5	S5-WBS36	S5-G09	2	Review B3 và điều kiện mở final	Trần Diệu Huyền	Chưa bắt đầu	6		Thu Nov 19 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu các yêu cầu Must và cấu hình đóng băng; ghi optional UI được hoãn nếu thiếu thời gian.	Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~					Tổng giờ các task			150	0																			~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	62	2	0.03225806451612903	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G01	5	Kiểm tra bằng chứng trước khi trả lời	Bằng chứng không liên quan bị chặn trước khi sinh nháp.~~

~~Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	17		Sprint 5 Backlog~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G02	5	Sinh nháp trong context được duyệt	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.~~

~~Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	16		Sprint 5 Backlog~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G03	5	Gắn trích dẫn và mở nguồn chứng minh	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.~~

~~Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	17		Sprint 5 Backlog~~

~~Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G04	5	Kiểm chứng nháp trước khi phát hành	Nháp sai số hoặc sai phạm vi không đạt verifier.~~

~~UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Mon Nov 09 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	14		Sprint 5 Backlog~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G05	5	Sửa nháp có giới hạn và từ chối an toàn	Trace ghi lần sửa và không vượt giới hạn một lần.~~

~~Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	16		Sprint 5 Backlog~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G06	5	Hoàn thiện giao diện Copilot	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.~~

~~Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	16		Sprint 5 Backlog~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G07	5	So sánh công ty và tích hợp B3	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.~~

~~Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	19		Sprint 5 Backlog~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G08	5	An toàn và chuẩn bị đánh giá cuối	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.~~

~~Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Mon Nov 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	13		Sprint 5 Backlog~~

~~Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	S5-G09	5	Tích hợp và nghiệm thu Sprint 5	Không có nháp chưa kiểm chứng được phát hành.~~

~~Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Thu Nov 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	22		Sprint 5 Backlog~~

~~Tổng task	195		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						~~

~~Độ hoàn thành	0.5384615384615384		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~S5-G01	5	Kiểm tra bằng chứng trước khi trả lời	S5-WBS01: Cài kiểm tra độ liên quan bằng chứng~~

~~S5-WBS02: Cài kiểm tra kỳ độ mới và phiên bản~~

~~S5-WBS03: Cài kiểm tra độ phủ và mâu thuẫn~~

~~S5-WBS04: Cho mọi tuyến B3 đi qua Gate	Bằng chứng không liên quan bị chặn trước khi sinh nháp.~~

~~Không có đường tắt bỏ Gate ở tuyến trả lời có cấu trúc.	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G02	5	Sinh nháp trong context được duyệt	S5-WBS05: Tạo context và danh sách citation ID~~

~~S5-WBS06: Gọi Gemini để tạo nháp có cấu trúc~~

~~S5-WBS07: Kiểm tra định dạng nháp từ Gemini~~

~~S5-WBS08: Nối tuyến nháp số liệu chính xác	Context không chứa nguồn chưa duyệt hoặc ID ngoài allowlist.~~

~~Tuyến không dùng Gemini không bỏ bước kiểm chứng.	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G03	5	Gắn trích dẫn và mở nguồn chứng minh	S5-WBS09: Gắn từng nhận định với Evidence~~

~~S5-WBS10: Tạo API mở chi tiết trích dẫn~~

~~S5-WBS11: Hiện nguồn và đoạn liên quan trên UI~~

~~S5-WBS12: Hiện vết tính toán và nguồn từng edge	Mỗi nhận định quan trọng liên kết đúng nguồn chứng minh.~~

~~Không chỉ hiện nguồn chung mà thiếu các đầu vào hoặc edge liên quan.	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G04	5	Kiểm chứng nháp trước khi phát hành	S5-WBS13: Kiểm tra số đơn vị kỳ và công ty~~

~~S5-WBS14: Kiểm tra công thức và đầu vào~~

~~S5-WBS15: Kiểm tra trích dẫn và độ phủ nhận định~~

~~S5-WBS16: Tạo Response Composer sau PASS	Nháp sai số hoặc sai phạm vi không đạt verifier.~~

~~UI không hiện nháp chưa kiểm chứng như câu trả lời chính thức.	Fri Nov 13 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G05	5	Sửa nháp có giới hạn và từ chối an toàn	S5-WBS17: Cài tối đa một lần sửa có kiểm soát~~

~~S5-WBS18: Gắn lại trích dẫn và kiểm tra nháp sửa~~

~~S5-WBS19: Trả lý do thiếu dữ liệu hoặc lỗi kiểm chứng~~

~~S5-WBS20: Từ chối tư vấn giao dịch ngoài phạm vi	Trace ghi lần sửa và không vượt giới hạn một lần.~~

~~Ca ngoài phạm vi nhận lời từ chối có thể hiểu được.	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G06	5	Hoàn thiện giao diện Copilot	S5-WBS21: Làm màn hình câu hỏi và bộ lọc~~

~~S5-WBS22: Hiện trạng thái chờ và lỗi yêu cầu~~

~~S5-WBS23: Hiện câu trả lời và citation marker~~

~~S5-WBS24: Nối đăng nhập chọn công ty và Copilot	Dữ liệu gửi đúng API và lỗi đầu vào được chỉ rõ.~~

~~Luồng sử dụng chính chạy xuyên suốt mà không lẫn dữ liệu người dùng.	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G07	5	So sánh công ty và tích hợp B3	S5-WBS25: Kiểm tra phạm vi câu hỏi so sánh~~

~~S5-WBS26: Căn chỉnh số liệu giữa các công ty~~

~~S5-WBS27: Kiểm chứng nhận định so sánh~~

~~S5-WBS28: Tích hợp cấu hình B3 và trace đầy đủ	Công ty ngoài phạm vi hoặc kỳ mơ hồ được báo để làm rõ.~~

~~Manifest và trace mô tả được luồng B3 thực sự đã chạy.	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G08	5	An toàn và chuẩn bị đánh giá cuối	S5-WBS29: Kiểm thử prompt injection trong tài liệu~~

~~S5-WBS30: Kiểm thử thiếu bằng chứng và lỗi nguồn~~

~~S5-WBS31: Đánh giá khả năng người dùng kiểm tra nguồn~~

~~S5-WBS32: Gắn tag runtime và evaluator trước final	Ca tấn công không làm lộ bí mật hoặc bỏ kiểm chứng.~~

~~Tag có manifest đầy đủ; không đổi cấu hình dựa trên nhãn final.	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~S5-G09	5	Tích hợp và nghiệm thu Sprint 5	S5-WBS33: Kiểm thử Gate citation và verifier~~

~~S5-WBS34: Sửa lỗi kiểm chứng và nguồn tuần 1~~

~~S5-WBS35: Kiểm thử B3 so sánh và bảo mật~~

~~S5-WBS36: Review B3 và điều kiện mở final	Không có nháp chưa kiểm chứng được phát hành.~~

~~Nhóm xác nhận điều kiện chạy 80 ca final, hoặc nêu blocker cụ thể.	Fri Nov 20 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.~~

## 2026-11-06 14:17 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-06 14:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Chuẩn bị adapter bằng fixture từ đầu tuần, nối retrieval thật sau khi WBS09 bàn giao; kiểm tra không lộ quan hệ chờ duyệt.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	GRAPH chạy bằng graph thật đúng scope, có nguồn và lỗi rõ; đọc lại nguồn bằng ID không bị gắn nhãn BOTH.	Tuần 2. Phụ thuộc / làm trước: Contract WBS10; WBS09 thật để đóng task. Có thể code adapter bằng fixture trước, không đứng chờ pipeline ghép xong.	Cao	Đang test	S4-G03	FinMind	...**

🟢 **	Sprint 4	S4-WBS12	S4-G03	2	Nối nhánh Graph RAG vào Hybrid Router	Hồ Phạm Đăng Nhân	Đang test	5		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chuyển intent/slots của WBS10 sang tham số truy vấn WBS09; không sinh Cypher tùy ý từ câu hỏi.**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang test	19		Sprint 4 Backlog**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang test	Ngày và phân công là kế hoạch đề xuất.**

~~4. Chuẩn bị adapter bằng fixture từ đầu tuần, nối retrieval thật sau khi WBS09 bàn giao; kiểm tra không lộ quan hệ chờ duyệt.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	GRAPH chạy bằng graph thật đúng scope, có nguồn và lỗi rõ; đọc lại nguồn bằng ID không bị gắn nhãn BOTH.	Tuần 2. Phụ thuộc / làm trước: Contract WBS10; WBS09 thật để đóng task. Có thể code adapter bằng fixture trước, không đứng chờ pipeline ghép xong.	Cao	Chưa bắt đầu	S4-G03	FinMi...~~

~~	Sprint 4	S4-WBS12	S4-G03	2	Nối nhánh Graph RAG vào Hybrid Router	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chuyển intent/slots của WBS10 sang tham số truy vấn WBS09; không sinh Cypher tùy ý từ câu hỏi.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	19		Sprint 4 Backlog~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-11-05 22:47 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-05 22:47

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-05 09:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-05 09:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Tuần 2. Phụ thuộc / làm trước: Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fix...**

🟢 **	Sprint 4	S4-WBS09	S4-G03	2	Tích hợp các nhánh trích xuất và hoàn thiện graph retrieval	Thái Quốc Hưng	Đã hoàn thành	14		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. 09.1 Nối đầu ra extractor doanh nghiệp, chức vụ và sự kiện vào pipeline chung; kiểm tra cùng contract.**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	62	2	0.03225806451612903	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	19		Sprint 4 Backlog**

🟢 **Task đã hoàn thành	105		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.5384615384615384		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Tuần 2. Phụ thuộc / làm trước: Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fix...~~

~~	Sprint 4	S4-WBS09	S4-G03	2	Tích hợp các nhánh trích xuất và hoàn thiện graph retrieval	Thái Quốc Hưng	Đang làm	14		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. 09.1 Nối đầu ra extractor doanh nghiệp, chức vụ và sự kiện vào pipeline chung; kiểm tra cùng contract.~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	62	1	0.016129032258064516	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	19		Sprint 4 Backlog~~

~~Task đã hoàn thành	104		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.5333333333333333		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-11-04 10:57 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-04 10:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Chat/Graph Viewer trình bày đúng bằng chứng, thời gian và giới hạn của kết quả.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Tuần 2. Phụ thuộc / làm trước: Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.	Cao	Đã hoàn thành	S4-G06	FinMind	4	6		Trần Diệu Huyền	Mon Nov 02 2026 07:00:0...**

🟢 **	Sprint 4	S4-WBS15	S4-G06	2	Nối Graph Viewer và xem bằng chứng thật	Trần Diệu Huyền	Đã hoàn thành	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng Graph Viewer; nối API theo contract để hiển thị Company, Person, Event và quan hệ.**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	62	1	0.016129032258064516	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	12		Sprint 4 Backlog**

🟢 **Task đã hoàn thành	104		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.5333333333333333		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Chat/Graph Viewer trình bày đúng bằng chứng, thời gian và giới hạn của kết quả.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Tuần 2. Phụ thuộc / làm trước: Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.	Cao	Đang làm	S4-G06	FinMind	4	6		Trần Diệu Huyền	Mon Nov 02 2026 07:00:00 GMT...~~

~~	Sprint 4	S4-WBS15	S4-G06	2	Nối Graph Viewer và xem bằng chứng thật	Trần Diệu Huyền	Đang làm	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng Graph Viewer; nối API theo contract để hiển thị Company, Person, Event và quan hệ.~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	62	0	0	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	12		Sprint 4 Backlog~~

~~Task đã hoàn thành	103		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.5282051282051282		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-11-04 09:07 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-04 09:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Chat/Graph Viewer trình bày đúng bằng chứng, thời gian và giới hạn của kết quả.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Tuần 2. Phụ thuộc / làm trước: Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.	Cao	Đang làm	S4-G06	FinMind	4	6		Trần Diệu Huyền	Mon Nov 02 2026 07:00:00 GMT...**

🟢 **	Sprint 4	S4-WBS15	S4-G06	2	Nối Graph Viewer và xem bằng chứng thật	Trần Diệu Huyền	Đang làm	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng Graph Viewer; nối API theo contract để hiển thị Company, Person, Event và quan hệ.**

🟢 **Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	12		Sprint 4 Backlog**

🟢 **Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Chat/Graph Viewer trình bày đúng bằng chứng, thời gian và giới hạn của kết quả.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Tuần 2. Phụ thuộc / làm trước: Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	6		Trần Diệu Huyền	Mon Nov 02 2026 07:00:00...~~

~~	Sprint 4	S4-WBS15	S4-G06	2	Nối Graph Viewer và xem bằng chứng thật	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng Graph Viewer; nối API theo contract để hiển thị Company, Person, Event và quan hệ.~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	12		Sprint 4 Backlog~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-11-03 22:22 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-03 22:22

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-03 22:17 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-03 22:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-03 16:37 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-03 16:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	Tuần 1. Phụ thuộc / làm trước: WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ...**

🟢 **	Sprint 4	S4-WBS06	S4-G02	1	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trần Diệu Huyền	Đã hoàn thành	6		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xây quy tắc kiểm tra thực thể, chiều quan hệ, loại quan hệ, trường bắt buộc và đoạn nguồn có chứng minh kết luận hay không.**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	57	0.8260869565217391	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	1	0.14285714285714285	Cần xác nhận	52		Sprint 4 Backlog**

🟢 **Task đã hoàn thành	103		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.5282051282051282		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	1	0.14285714285714285	Cần xác nhận	Ngày và phân công là kế hoạch đề xuất.**

~~4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	Tuần 1. Phụ thuộc / làm trước: WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ...~~

~~	Sprint 4	S4-WBS06	S4-G02	1	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trần Diệu Huyền	Đang làm	6		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xây quy tắc kiểm tra thực thể, chiều quan hệ, loại quan hệ, trường bắt buộc và đoạn nguồn có chứng minh kết luận hay không.~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	56	0.8115942028985508	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Cần xác nhận	52		Sprint 4 Backlog~~

~~Task đã hoàn thành	102		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.5230769230769231		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Cần xác nhận	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-11-03 15:17 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-03 15:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-03 15:07 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-03 15:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-02 14:07 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-02 14:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5.  Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	Tuần 1. Phụ thuộc / làm trước: WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 củ...**

🟢 **	Sprint 4	S4-WBS05	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Nguyễn Minh Quân	Đang test	12		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan**

~~5.  Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	Tuần 1. Phụ thuộc / làm trước: WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 củ...~~

~~	Sprint 4	S4-WBS05	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Nguyễn Minh Quân	Chưa bắt đầu	12		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan~~

## 2026-11-02 13:42 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-02 13:42

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-02 13:37 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-02 13:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Dùng ID WBS02 để xuất đúng contract; kiểm tra mẫu hợp lệ, sai chiều, thiếu chủ thể và hai tên chỉ xuất hiện cùng đoạn.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Có quan hệ doanh nghiệp ứng viên kèm nguồn, trạng thái và thời gian nếu có; test không tạo quan hệ chỉ từ đồng xuất hiện.	Tuần 1. Phụ thuộc / làm trước: Contract WBS01; chuẩn hóa thật WBS02 để đóng task. Có thể code bằng entity fixture từ 27/10, không phải đ...**

🟢 **4. Xử lý lỗi nạp dở, chuẩn bị resume và đối chiếu số liệu/khóa giữa hai hệ thống. Nghiệm thu phần ghi bằng fixture ở tuần 1; WBS09 nối extraction thật tuần 2.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Bộ ghi graph có test chống trùng, không lẫn phiên, giữ extraction/nguồn và không công bố lần nạp dở. Có graph fixture dùng cho truy vấn.	Tuần 1. Phụ thuộc / làm trước: WBS01; thống nhất metadata/version với WBS07. Không p...**

🟢 **	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất sự kiện và quan hệ giữa các doang nghiệp	Hồ Phạm Đăng Nhân	Cần xác nhận	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

🟢 **	Sprint 4	S4-WBS08	S4-G02	1	Lưu graph trên Neo4j và chuẩn bị đối chiếu nguồn	Hồ Phạm Đăng Nhân	Cần xác nhận	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng phần phù hợp của GraphStore; thêm constraint/index cho Company, Person, Event và quan hệ có phiên bản.**

~~4. Dùng ID WBS02 để xuất đúng contract; kiểm tra mẫu hợp lệ, sai chiều, thiếu chủ thể và hai tên chỉ xuất hiện cùng đoạn.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Có quan hệ doanh nghiệp ứng viên kèm nguồn, trạng thái và thời gian nếu có; test không tạo quan hệ chỉ từ đồng xuất hiện.	Tuần 1. Phụ thuộc / làm trước: Contract WBS01; chuẩn hóa thật WBS02 để đóng task. Có thể code bằng entity fixture từ 27/10, không phải đ...~~

~~4. Xử lý lỗi nạp dở, chuẩn bị resume và đối chiếu số liệu/khóa giữa hai hệ thống. Nghiệm thu phần ghi bằng fixture ở tuần 1; WBS09 nối extraction thật tuần 2.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Bộ ghi graph có test chống trùng, không lẫn phiên, giữ extraction/nguồn và không công bố lần nạp dở. Có graph fixture dùng cho truy vấn.	Tuần 1. Phụ thuộc / làm trước: WBS01; thống nhất metadata/version với WBS07. Không p...~~

~~	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất sự kiện và quan hệ giữa các doang nghiệp	Hồ Phạm Đăng Nhân	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.~~

~~	Sprint 4	S4-WBS08	S4-G02	1	Lưu graph trên Neo4j và chuẩn bị đối chiếu nguồn	Hồ Phạm Đăng Nhân	Chưa bắt đầu	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng phần phù hợp của GraphStore; thêm constraint/index cho Company, Person, Event và quan hệ có phiên bản.~~

## 2026-11-02 13:32 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-02 13:32

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-11-02 08:57 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-02 08:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Tuần 2. Phụ thuộc / làm trước: Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fix...**

🟢 **	Sprint 4	S4-WBS09	S4-G03	2	Tích hợp các nhánh trích xuất và hoàn thiện graph retrieval	Thái Quốc Hưng	Đang làm	14		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. 09.1 Nối đầu ra extractor doanh nghiệp, chức vụ và sự kiện vào pipeline chung; kiểm tra cùng contract.**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	19		Sprint 4 Backlog**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Tuần 2. Phụ thuộc / làm trước: Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fix...~~

~~	Sprint 4	S4-WBS09	S4-G03	2	Tích hợp các nhánh trích xuất và hoàn thiện graph retrieval	Thái Quốc Hưng	Chưa bắt đầu	14		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. 09.1 Nối đầu ra extractor doanh nghiệp, chức vụ và sự kiện vào pipeline chung; kiểm tra cùng contract.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	19		Sprint 4 Backlog~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-11-01 17:47 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-11-01 17:47

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	Tuần 1. Phụ thuộc / làm trước: WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-lo...**

🟢 **	Sprint 4	S4-WBS10	S4-G04	1	Phân tích ý định và Hybrid Router bằng fixture	Trần Diệu Huyền	Đã hoàn thành	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Phân tích câu hỏi cùng ngữ cảnh: người dùng cần nội dung/số liệu, quan hệ, hay cả hai; lấy thực thể, thời gian và thông tin thiếu.**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	56	0.8115942028985508	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								**

🟢 **Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	15		Sprint 4 Backlog**

🟢 **Task đã hoàn thành	102		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.5230769230769231		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	1	0.5	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	Tuần 1. Phụ thuộc / làm trước: WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-lo...~~

~~	Sprint 4	S4-WBS10	S4-G04	1	Phân tích ý định và Hybrid Router bằng fixture	Trần Diệu Huyền	Đang làm	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Phân tích câu hỏi cùng ngữ cảnh: người dùng cần nội dung/số liệu, quan hệ, hay cả hai; lấy thực thể, thời gian và thông tin thiếu.~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	55	0.7971014492753623	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	15		Sprint 4 Backlog~~

~~Task đã hoàn thành	101		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.517948717948718		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-31 13:37 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-31 13:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-31 13:22 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-31 13:22

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-30 13:37 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-30 13:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	Tuần 1. Phụ thuộc / làm trước: WBS01 và trạng thái WBS06 (có thể...**

🟢 **	Sprint 4	S4-WBS07	S4-G02	1	Quản lý metadata và phiên graph trên Supabase	Đinh Huỳnh Vũ	Cần xác nhận	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đối chiếu schema thật, chuẩn bị migration bổ sung liên kết extraction với thực thể, chunk/locator và graph version; chỉ bổ sung phần thiếu.**

~~4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	Tuần 1. Phụ thuộc / làm trước: WBS01 và trạng thái WBS06 (có thể...~~

~~	Sprint 4	S4-WBS07	S4-G02	1	Quản lý metadata và phiên graph trên Supabase	Đinh Huỳnh Vũ	Đang làm	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đối chiếu schema thật, chuẩn bị migration bổ sung liên kết extraction với thực thể, chunk/locator và graph version; chỉ bổ sung phần thiếu.~~

## 2026-10-30 12:32 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-30 12:32

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-30 12:27 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-30 12:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Bàn giao quan hệ ứng viên có đoạn nguồn; thử ca nhiều chức vụ, nhiều công ty, thiếu thời gian và nguồn mâu thuẫn.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Quan hệ chức vụ đủ người, tổ chức, chức danh và provenance; không nhầm trạng thái hoặc thời gian; ca chưa rõ được đánh dấu.	Tuần 1. Phụ thuộc / làm trước: WBS01; dùng WBS02 thật để nghiệm thu. Có thể làm bằng fixture song song WBS03/WBS05 và phần lưu metadata WBS...**

🟢 **4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	Tuần 1. Phụ thuộc / làm trước: WBS01 và trạng thái WBS06 (có thể...**

🟢 **	Sprint 4	S4-WBS04	S4-G02	1	Trích xuất quan hệ chức vụ	Đinh Huỳnh Vũ	Cần xác nhận	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xác định người–chức vụ–doanh nghiệp; giữ tên chức vụ gốc và ánh xạ tên chuẩn theo contract.**

🟢 **	Sprint 4	S4-WBS07	S4-G02	1	Quản lý metadata và phiên graph trên Supabase	Đinh Huỳnh Vũ	Đang làm	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đối chiếu schema thật, chuẩn bị migration bổ sung liên kết extraction với thực thể, chunk/locator và graph version; chỉ bổ sung phần thiếu.**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Cần xác nhận	52		Sprint 4 Backlog**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Cần xác nhận	Ngày và phân công là kế hoạch đề xuất.**

~~4. Bàn giao quan hệ ứng viên có đoạn nguồn; thử ca nhiều chức vụ, nhiều công ty, thiếu thời gian và nguồn mâu thuẫn.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Quan hệ chức vụ đủ người, tổ chức, chức danh và provenance; không nhầm trạng thái hoặc thời gian; ca chưa rõ được đánh dấu.	Tuần 1. Phụ thuộc / làm trước: WBS01; dùng WBS02 thật để nghiệm thu. Có thể làm bằng fixture song song WBS03/WBS05 và phần lưu metadata WBS...~~

~~4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	Tuần 1. Phụ thuộc / làm trước: WBS01 và trạng thái WBS06 (có thể...~~

~~	Sprint 4	S4-WBS04	S4-G02	1	Trích xuất quan hệ chức vụ	Đinh Huỳnh Vũ	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xác định người–chức vụ–doanh nghiệp; giữ tên chức vụ gốc và ánh xạ tên chuẩn theo contract.~~

~~	Sprint 4	S4-WBS07	S4-G02	1	Quản lý metadata và phiên graph trên Supabase	Đinh Huỳnh Vũ	Chưa bắt đầu	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đối chiếu schema thật, chuẩn bị migration bổ sung liên kết extraction với thực thể, chunk/locator và graph version; chỉ bổ sung phần thiếu.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Đang làm	52		Sprint 4 Backlog~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-30 09:17 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-30 09:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								3	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	150	52	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	S3-WBS21	Nối B1 với retrieval và Gemini	B1 Vector RAG	Bước 1: Dùng dữ liệu mẫu để hoàn thiện phần gửi câu hỏi và bằng chứng cho Gemini. Bước 2: Khi Nhân bàn giao truy vấn vector có lọc, thay đầu vào mẫu bằng đoạn thật, giữ mã nguồn trong câu trả lời. Bước 3: Ghi phiên bản mô hình, prompt, giới hạn ngữ cảnh và kiểm tra B1 không bật cơ chế kiểm chứng riêng của B3.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	B1 trả nháp có nguồn ứng viên, manifest ghi rõ thành phần bậ...**

🟢 **	S3-WBS26	Kiểm tra trích dẫn và câu trả lời B1	B1 Vector RAG	Bước 1: Lấy vài câu trả lời B1 có nguồn đầy đủ, nguồn thiếu và nguồn mâu thuẫn. Bước 2: Kiểm tra từng nhận định có mã bằng chứng tương ứng và trích dẫn mở được. Bước 3: Với nhận định không chứng minh được, sửa câu trả lời thành thận trọng hoặc báo chưa đủ bằng chứng.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Không có claim vô nguồn trong ca mẫu; citation mở được locator.	Kế hoạch Sprint 3 đã chốt theo 4 ...**

🟢 **	S3-WBS31	Áp giới hạn token timeout và budget	B1 Vector RAG	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Ca vượt trần bị chặn và có trace; cấu hình được phiên bản hóa.	Kế h...**

🟢 **	S3-WBS35	Chạy B1 trên Golden40 đã khóa	B1 Vector RAG	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Có trace từng ca; partial run được dán nhãn, không công bố aggreg...**

🟢 **	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	52																						**

🟢 **	Sprint 3	S3-WBS21	S3-G04	2	Nối B1 với retrieval và Gemini	Thái Quốc Hưng	Đã hoàn thành	5	6	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng dữ liệu mẫu để hoàn thiện phần gửi câu hỏi và bằng chứng cho Gemini. Bước 2: Khi Nhân bàn giao truy vấn vector có lọc, thay đầu vào mẫu bằng đoạn thật, giữ mã nguồn trong câu trả lời. Bước 3: Ghi phiên bản mô hình, prompt, giới hạn ngữ cảnh và kiểm tra B1 không bật cơ chế kiểm chứng riêng của...**

🟢 **	Sprint 3	S3-WBS26	S3-G04	2	Kiểm tra trích dẫn và câu trả lời B1	Thái Quốc Hưng	Đã hoàn thành	3	2	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy vài câu trả lời B1 có nguồn đầy đủ, nguồn thiếu và nguồn mâu thuẫn. Bước 2: Kiểm tra từng nhận định có mã bằng chứng tương ứng và trích dẫn mở được. Bước 3: Với nhận định không chứng minh được, sửa câu trả lời thành thận trọng hoặc báo chưa đủ bằng chứng.	Không có claim vô nguồn trong ca...**

🟢 **	Sprint 3	S3-WBS31	S3-G04	2	Áp giới hạn token timeout và budget	Thái Quốc Hưng	Đã hoàn thành	3	4	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	Ca...**

🟢 **	Sprint 3	S3-WBS35	S3-G04	2	Chạy B1 trên Golden40 đã khóa	Thái Quốc Hưng	Đã hoàn thành	4	3	Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	...**

🟢 **					Tổng giờ các task			150	52																			**

🟢 **					Giờ thực tế theo ngày (tự tính)				46						5	9	6	3	3	1	0	7	3	3	3	3	0	0**

🟢 **Gói bằng chứng có ID ổn định và không mất metadata bắt buộc.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	30	31	Sprint 3 Backlog**

~~								3	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	150	37	36 task chi tiết; lịch và phân công đề xuất.~~

~~	S3-WBS21	Nối B1 với retrieval và Gemini	B1 Vector RAG	Bước 1: Dùng dữ liệu mẫu để hoàn thiện phần gửi câu hỏi và bằng chứng cho Gemini. Bước 2: Khi Nhân bàn giao truy vấn vector có lọc, thay đầu vào mẫu bằng đoạn thật, giữ mã nguồn trong câu trả lời. Bước 3: Ghi phiên bản mô hình, prompt, giới hạn ngữ cảnh và kiểm tra B1 không bật cơ chế kiểm chứng riêng của B3.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	B1 trả nháp có nguồn ứng viên, manifest ghi rõ thành phần bậ...~~

~~	S3-WBS26	Kiểm tra trích dẫn và câu trả lời B1	B1 Vector RAG	Bước 1: Lấy vài câu trả lời B1 có nguồn đầy đủ, nguồn thiếu và nguồn mâu thuẫn. Bước 2: Kiểm tra từng nhận định có mã bằng chứng tương ứng và trích dẫn mở được. Bước 3: Với nhận định không chứng minh được, sửa câu trả lời thành thận trọng hoặc báo chưa đủ bằng chứng.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Không có claim vô nguồn trong ca mẫu; citation mở được locator.	Kế hoạch Sprint 3 đã chốt theo 4 ...~~

~~	S3-WBS31	Áp giới hạn token timeout và budget	B1 Vector RAG	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Ca vượt trần bị chặn và có trace; cấu hình được phiên bản hóa.	Kế h...~~

~~	S3-WBS35	Chạy B1 trên Golden40 đã khóa	B1 Vector RAG	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Có trace từng ca; partial run được dán nhãn, không công bố aggreg...~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	37																						~~

~~	Sprint 3	S3-WBS21	S3-G04	2	Nối B1 với retrieval và Gemini	Thái Quốc Hưng	Đã hoàn thành	5		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng dữ liệu mẫu để hoàn thiện phần gửi câu hỏi và bằng chứng cho Gemini. Bước 2: Khi Nhân bàn giao truy vấn vector có lọc, thay đầu vào mẫu bằng đoạn thật, giữ mã nguồn trong câu trả lời. Bước 3: Ghi phiên bản mô hình, prompt, giới hạn ngữ cảnh và kiểm tra B1 không bật cơ chế kiểm chứng riêng của ...~~

~~	Sprint 3	S3-WBS26	S3-G04	2	Kiểm tra trích dẫn và câu trả lời B1	Thái Quốc Hưng	Đã hoàn thành	3		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Lấy vài câu trả lời B1 có nguồn đầy đủ, nguồn thiếu và nguồn mâu thuẫn. Bước 2: Kiểm tra từng nhận định có mã bằng chứng tương ứng và trích dẫn mở được. Bước 3: Với nhận định không chứng minh được, sửa câu trả lời thành thận trọng hoặc báo chưa đủ bằng chứng.	Không có claim vô nguồn trong ca ...~~

~~	Sprint 3	S3-WBS31	S3-G04	2	Áp giới hạn token timeout và budget	Thái Quốc Hưng	Đã hoàn thành	3		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	Ca ...~~

~~	Sprint 3	S3-WBS35	S3-G04	2	Chạy B1 trên Golden40 đã khóa	Thái Quốc Hưng	Đã hoàn thành	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	C...~~

~~					Tổng giờ các task			150	37																			~~

~~					Giờ thực tế theo ngày (tự tính)				31						5	9	6	3	3	1	0	4	0	0	0	0	0	0~~

~~Gói bằng chứng có ID ổn định và không mất metadata bắt buộc.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	30	16	Sprint 3 Backlog~~

## 2026-10-30 09:12 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-30 09:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								3	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	150	37	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	S3-WBS13	Dựng B1 retrieval orchestration bằng fixture	B1 Vector RAG	Bước 1: Nối phần hiểu câu hỏi với mẫu kết quả tìm kiếm và gói bằng chứng đã thống nhất. Bước 2: Cho B1 chạy thử với dữ liệu mẫu để kiểm tra đường đi từ câu hỏi đến danh sách nguồn. Bước 3: Xử lý riêng trường hợp không tìm thấy nguồn, kết quả rỗng hoặc hết thời gian; chưa phải đợi dữ liệu vector thật.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	B1 trên fixture trả schema đúng, không tạo câu trả lời ...**

🟢 **	S3-WBS18	Xử lý B1 khi câu hỏi hoặc nguồn mơ hồ	B1 Vector RAG	Bước 1: Dùng câu hỏi thiếu công ty/kỳ/chỉ tiêu để thử B1. Bước 2: Viết câu trả lời yêu cầu người dùng làm rõ thay vì đoán. Bước 3: Với câu hỏi đủ thông tin nhưng không có nguồn phù hợp, cho hệ thống nói chưa đủ bằng chứng và không tự tạo số liệu.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Ca thiếu công ty/kỳ hoặc không có nguồn không bị bịa câu trả lời.	Kế hoạch Sprint 3 đã chốt theo 4 người vector + Quâ...**

🟢 **	S3-WBS31	Áp giới hạn token timeout và budget	B1 Vector RAG	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Ca vượt trần bị chặn và có trace; cấu hình được phiên bản hóa.	Kế h...**

🟢 **	S3-WBS35	Chạy B1 trên Golden40 đã khóa	B1 Vector RAG	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Có trace từng ca; partial run được dán nhãn, không công bố aggreg...**

🟢 **4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...**

🟢 **4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Đã ...**

🟢 **	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	37																						**

🟢 **	Sprint 3	S3-WBS13	S3-G04	1	Dựng B1 retrieval orchestration bằng fixture	Thái Quốc Hưng	Đã hoàn thành	5	6	Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nối phần hiểu câu hỏi với mẫu kết quả tìm kiếm và gói bằng chứng đã thống nhất. Bước 2: Cho B1 chạy thử với dữ liệu mẫu để kiểm tra đường đi từ câu hỏi đến danh sách nguồn. Bước 3: Xử lý riêng trường hợp không tìm thấy nguồn, kết quả rỗng hoặc hết thời gian; chưa phải đợi dữ liệu vec...**

🟢 **	Sprint 3	S3-WBS18	S3-G04	1	Xử lý B1 khi câu hỏi hoặc nguồn mơ hồ	Thái Quốc Hưng	Đã hoàn thành	3	3	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng câu hỏi thiếu công ty/kỳ/chỉ tiêu để thử B1. Bước 2: Viết câu trả lời yêu cầu người dùng làm rõ thay vì đoán. Bước 3: Với câu hỏi đủ thông tin nhưng không có nguồn phù hợp, cho hệ thống nói chưa đủ bằng chứng và không tự tạo số liệu.	Ca thiếu công ty/kỳ hoặc không có nguồn không bị bịa...**

🟢 **	Sprint 3	S3-WBS31	S3-G04	2	Áp giới hạn token timeout và budget	Thái Quốc Hưng	Đã hoàn thành	3		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	Ca ...**

🟢 **	Sprint 3	S3-WBS35	S3-G04	2	Chạy B1 trên Golden40 đã khóa	Thái Quốc Hưng	Đã hoàn thành	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	C...**

🟢 **					Tổng giờ các task			150	37																			**

🟢 **					Giờ thực tế theo ngày (tự tính)				31						5	9	6	3	3	1	0	4	0	0	0	0	0	0**

🟢 **	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Đã hoàn thành	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.**

🟢 **	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Đã hoàn thành	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	55	0.7971014492753623	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								**

🟢 **Gói bằng chứng có ID ổn định và không mất metadata bắt buộc.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	30	16	Sprint 3 Backlog**

🟢 **Nạp lặp không tạo node trùng; ID sai bị chặn.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	2	1	Đã hoàn thành	13		Sprint 4 Backlog**

🟢 **Task đã hoàn thành	101		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.517948717948718		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Gói bằng chứng có ID ổn định và không mất metadata bắt buộc.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	8	1	Đã hoàn thành	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Nạp lặp không tạo node trùng; ID sai bị chặn.	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	2	1	Đã hoàn thành	Ngày và phân công là kế hoạch đề xuất.**

~~								3	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	150	28	36 task chi tiết; lịch và phân công đề xuất.~~

~~	S3-WBS13	Dựng B1 retrieval orchestration bằng fixture	B1 Vector RAG	Bước 1: Nối phần hiểu câu hỏi với mẫu kết quả tìm kiếm và gói bằng chứng đã thống nhất. Bước 2: Cho B1 chạy thử với dữ liệu mẫu để kiểm tra đường đi từ câu hỏi đến danh sách nguồn. Bước 3: Xử lý riêng trường hợp không tìm thấy nguồn, kết quả rỗng hoặc hết thời gian; chưa phải đợi dữ liệu vector thật.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	B1 trên fixture trả schema đúng, không tạo câu trả lời ...~~

~~	S3-WBS18	Xử lý B1 khi câu hỏi hoặc nguồn mơ hồ	B1 Vector RAG	Bước 1: Dùng câu hỏi thiếu công ty/kỳ/chỉ tiêu để thử B1. Bước 2: Viết câu trả lời yêu cầu người dùng làm rõ thay vì đoán. Bước 3: Với câu hỏi đủ thông tin nhưng không có nguồn phù hợp, cho hệ thống nói chưa đủ bằng chứng và không tự tạo số liệu.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Ca thiếu công ty/kỳ hoặc không có nguồn không bị bịa câu trả lời.	Kế hoạch Sprint 3 đã chốt theo 4 người vector + Quâ...~~

~~	S3-WBS31	Áp giới hạn token timeout và budget	B1 Vector RAG	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Ca vượt trần bị chặn và có trace; cấu hình được phiên bản hóa.	Kế h...~~

~~	S3-WBS35	Chạy B1 trên Golden40 đã khóa	B1 Vector RAG	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	B1 nhận câu hỏi, tìm bằng chứng vector và trả lời có nguồn theo manifest.	Có trace từng ca; partial run được dán nhãn, không công bố aggreg...~~

~~4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...~~

~~4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Đan...~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	28																						~~

~~	Sprint 3	S3-WBS13	S3-G04	1	Dựng B1 retrieval orchestration bằng fixture	Thái Quốc Hưng	Đã hoàn thành	5		Wed Oct 14 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 15 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Nối phần hiểu câu hỏi với mẫu kết quả tìm kiếm và gói bằng chứng đã thống nhất. Bước 2: Cho B1 chạy thử với dữ liệu mẫu để kiểm tra đường đi từ câu hỏi đến danh sách nguồn. Bước 3: Xử lý riêng trường hợp không tìm thấy nguồn, kết quả rỗng hoặc hết thời gian; chưa phải đợi dữ liệu vect...~~

~~	Sprint 3	S3-WBS18	S3-G04	1	Xử lý B1 khi câu hỏi hoặc nguồn mơ hồ	Thái Quốc Hưng	Đã hoàn thành	3		Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 16 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Dùng câu hỏi thiếu công ty/kỳ/chỉ tiêu để thử B1. Bước 2: Viết câu trả lời yêu cầu người dùng làm rõ thay vì đoán. Bước 3: Với câu hỏi đủ thông tin nhưng không có nguồn phù hợp, cho hệ thống nói chưa đủ bằng chứng và không tự tạo số liệu.	Ca thiếu công ty/kỳ hoặc không có nguồn không bị bịa ...~~

~~	Sprint 3	S3-WBS31	S3-G04	2	Áp giới hạn token timeout và budget	Thái Quốc Hưng	Đang làm	3		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chốt trần số token, thời gian và chi phí cho một lần trả lời, đưa các mức này vào cấu hình có phiên bản. Bước 2: Trước và trong lúc gọi Gemini, kiểm tra còn trong giới hạn hay không. Bước 3: Nếu vượt giới hạn, dừng và ghi lý do rõ ràng; thử để chắc không phát sinh cuộc gọi ngoài ngân sách.	Ca vượt ...~~

~~	Sprint 3	S3-WBS35	S3-G04	2	Chạy B1 trên Golden40 đã khóa	Thái Quốc Hưng	Chưa bắt đầu	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Chỉ sau khi Huyền thông báo Golden40 đã khóa, chạy B1 trên đúng 40 câu với cùng phiên bản tài liệu, mô hình, prompt và cấu hình. Bước 2: Lưu cho từng câu: câu trả lời, nguồn đã dùng, thời gian, token và lỗi. Bước 3: Nếu thiếu kết quả/dấu vết, đánh dấu lần chạy chưa đủ, không công bố điểm tổng hợp.	Có...~~

~~					Tổng giờ các task			150	28																			~~

~~					Giờ thực tế theo ngày (tự tính)				22						5	9	4	0	0	0	0	4	0	0	0	0	0	0~~

~~	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Đang làm	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.~~

~~	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Đang làm	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	51	0.7391304347826086	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								~~

~~Gói bằng chứng có ID ổn định và không mất metadata bắt buộc.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	6	0.75	Đang làm	30	7	Sprint 3 Backlog~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	13		Sprint 4 Backlog~~

~~Task đã hoàn thành	97		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.49743589743589745		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Gói bằng chứng có ID ổn định và không mất metadata bắt buộc.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	6	0.75	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-28 10:37 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-28 10:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-28 10:27 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-28 10:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-27 16:12 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-27 16:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-27 16:07 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-27 16:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	Tuần 1. Phụ thuộc / làm trước: WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-lo...**

🟢 **	Sprint 4	S4-WBS10	S4-G04	1	Phân tích ý định và Hybrid Router bằng fixture	Trần Diệu Huyền	Đang làm	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Phân tích câu hỏi cùng ngữ cảnh: người dùng cần nội dung/số liệu, quan hệ, hay cả hai; lấy thực thể, thời gian và thông tin thiếu.**

🟢 **Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	15		Sprint 4 Backlog**

🟢 **Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	Tuần 1. Phụ thuộc / làm trước: WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-lo...~~

~~	Sprint 4	S4-WBS10	S4-G04	1	Phân tích ý định và Hybrid Router bằng fixture	Trần Diệu Huyền	Chưa bắt đầu	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Phân tích câu hỏi cùng ngữ cảnh: người dùng cần nội dung/số liệu, quan hệ, hay cả hai; lấy thực thể, thời gian và thông tin thiếu.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	15		Sprint 4 Backlog~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-27 13:12 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-27 13:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	Tuần 2. Phụ thuộc / làm trước: WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.	Rất cao	Chưa bắt đầu	S4-G04	FinMind	4	7		Nguyễn Minh Quân	Mon Nov 02 2026 07:00:00 GM...**

🟢 **	S4-WBS17	Kiểm thử, đánh giá B1/B2 và bàn giao Sprint 4	Kiểm thử, đánh giá và bàn giao Sprint 4	1. Nhân và Huyền thống nhất bộ câu hỏi, nguồn và kết quả kỳ vọng cho quan hệ doanh nghiệp, chức vụ, sự kiện và ba tuyến VECTOR/GRAPH/BOTH.**

🟢 **2. Nhân (7 giờ): chạy benchmark B1/B2 trên cùng corpus, model và cấu hình; đối chiếu route, thực thể, chiều quan hệ, thời gian, bằng chứng và thời gian phản hồi; lưu đầu ra từng câu và phân tích ca sai.**

🟢 **2. Nhân (7 giờ): chạy benchmark B1/B2 trên cùng corpus, model và cấu hình; đối chiếu route, thực thể, chiều quan hệ, thời gian, bằng chứng và thời gian phản hồi; lưu đầu ra từng câu và phân tích ca sai.**

🟢 **3. Huyền (6 giờ): kiểm tra xuyên suốt câu hỏi → chat → citation → Graph Viewer; đọc nguồn để đối chiếu; thử tên mơ hồ, nguồn mâu thuẫn, sai thời gian/phiên, rỗng và timeout một nhánh BOTH.**

🟢 **3. Huyền (6 giờ): kiểm tra xuyên suốt câu hỏi → chat → citation → Graph Viewer; đọc nguồn để đối chiếu; thử tên mơ hồ, nguồn mâu thuẫn, sai thời gian/phiên, rỗng và timeout một nhánh BOTH.**

🟢 **4. Chạy hồi quy B1 và giao diện hiện có; đối chiếu báo cáo toàn bộ News của WBS16; ghi lỗi, mức ảnh hưởng và người xử lý.**

🟢 **4. Chạy hồi quy B1 và giao diện hiện có; đối chiếu báo cáo toàn bộ News của WBS16; ghi lỗi, mức ảnh hưởng và người xử lý.**

🟢 **5. Cùng bàn giao bộ test, kết quả chạy thật, bảng so sánh B1/B2, báo cáo full-load và giới hạn còn lại. Chỉ hoàn thành task khi cả phần Nhân và Huyền đạt. Tổng 13 giờ công = Nhân 7 giờ + Huyền 6 giờ, không phải 13 giờ mỗi người.	Đánh giá B1/B2, kiểm thử xuyên suốt, nguồn và hồi quy; bàn giao kết quả mẫu/full-load.	Có bộ test và kết quả thật cho VECTOR/GRAPH/BOTH và ba nhóm quan hệ; bảng B1/B2 có chất lượng và thời gian phản hồi; citation đúng nguồn; có kiểm thử lỗi/E2E/hồi quy, báo cáo full-load...**

🟢 **	Phân công theo nhóm đã chốt. WBS10 tuần 1; WBS09 tuần 2. WBS17 là một task chung: Nhân 7h và Huyền 6h, tổng 13 giờ công. Ngày và giờ là đề xuất; dùng fixture khi chờ đầu vào.																											**

🟢 **	Số task	17	Giờ dự kiến	128	Tổng giờ thực tế đã ghi			Tuần 1 (h)	65	Tuần 2 (h)	63																	**

🟢 **	Sprint 4	S4-WBS17	S4-G07	2	Kiểm thử, đánh giá B1/B2 và bàn giao Sprint 4	Hồ Phạm Đăng Nhân; Trần Diệu Huyền	Chưa bắt đầu	13		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhân và Huyền thống nhất bộ câu hỏi, nguồn và kết quả kỳ vọng cho quan hệ doanh nghiệp, chức vụ, sự kiện và ba tuyến VECTOR/GRAPH/BOTH.**

🟢 **5. Cùng bàn giao bộ test, kết quả chạy thật, bảng so sánh B1/B2, báo cáo full-load và giới hạn còn lại. Chỉ hoàn thành task khi cả phần Nhân và Huyền đạt. Tổng 13 giờ công = Nhân 7 giờ + Huyền 6 giờ, không phải 13 giờ mỗi người.	Có bộ test và kết quả thật cho VECTOR/GRAPH/BOTH và ba nhóm quan hệ; bảng B1/B2 có chất lượng và thời gian phản hồi; citation đúng nguồn; có kiểm thử lỗi/E2E/hồi quy, báo cáo full-load và danh sách lỗi còn lại. Không mặc định B2 tốt hơn B1.	Chuẩn bị bộ ca bằng WBS01/fixt...**

🟢 **5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.														**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	62	0	0	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	13		Sprint 4 Backlog**

🟢 **	S4-G09	4	Tích hợp và nghiệm thu Sprint 4	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.**

🟢 **Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.			0	0	Chưa có task	Chưa có task	0		Sprint 4 Backlog**

🟢 **Tổng task	195		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						**

🟢 **Độ hoàn thành	0.49743589743589745		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.		0	0	Chưa có task	Chưa có task	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.**

~~5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	Tuần 2. Phụ thuộc / làm trước: WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.1.	Rất cao	Chưa bắt đầu	S4-G04	FinMind	4	7		Nguyễn Minh Quân	Mon Nov 02 2026 07:00:00 ...~~

~~	S4-WBS17.1	WBS17.1 – Đánh giá retrieval và so sánh B1/B2 (Nhân)	Đánh giá retrieval và so sánh B1/B2	1. Cùng Huyền chốt bộ câu hỏi/nguồn kỳ vọng cho doanh nghiệp, chức vụ, sự kiện và VECTOR/GRAPH/BOTH.~~

~~2. Chạy cùng bộ ca và điều kiện trên B1/B2; giữ corpus, model và phiên cấu hình được ghi rõ để so sánh.~~

~~2. Chạy cùng bộ ca và điều kiện trên B1/B2; giữ corpus, model và phiên cấu hình được ghi rõ để so sánh.~~

~~3. Đối chiếu route, thực thể, chiều quan hệ, thời gian, evidence, trạng thái từng nhánh và latency; ghi các ca graph giúp hoặc gây lỗi.~~

~~3. Đối chiếu route, thực thể, chiều quan hệ, thời gian, evidence, trạng thái từng nhánh và latency; ghi các ca graph giúp hoặc gây lỗi.~~

~~4. Tổng hợp chỉ số, đầu ra từng câu và kết quả full-load WBS16; không mặc định B2 tốt hơn B1.~~

~~4. Tổng hợp chỉ số, đầu ra từng câu và kết quả full-load WBS16; không mặc định B2 tốt hơn B1.~~

~~5. Phần Nhân: test/retrieval benchmark, số đo và phân tích. Huyền WBS17.2 chịu trách nhiệm E2E giao diện/citation, kiểm tra nguồn thủ công và hồi quy.	Có kết quả từng ca và số đo thực tế trên cùng điều kiện, nêu cả cải thiện và suy giảm.	Có output/trace từng câu, bảng B1/B2 và thời gian phản hồi, phân tích ca sai và giới hạn. Không trùng công với WBS17.2; cần cả hai phần để đóng WBS17.	Tuần 2. Phụ thuộc / làm trước: WBS09 và WBS11–14; nhận báo cáo WBS16 để chốt. Chuẩn bị script/case từ fixture s...~~

~~	S4-WBS17.2	WBS17.2 – Kiểm thử E2E, citation và hồi quy (Huyền)	Kiểm thử E2E và nghiệm thu Sprint 4	1. Chuẩn bị test đầu tuần cho chọn route/hỏi lại, câu hỏi trùng tên, nguồn mâu thuẫn, sai thời gian/phiên và quan hệ chưa duyệt.~~

~~2. Kiểm tra câu hỏi → chat → nguồn → Graph Viewer trên ba tuyến; đọc nguồn mẫu để đối chiếu nhận định, không chỉ nhìn schema đúng.~~

~~2. Kiểm tra câu hỏi → chat → nguồn → Graph Viewer trên ba tuyến; đọc nguồn mẫu để đối chiếu nhận định, không chỉ nhìn schema đúng.~~

~~3. Thử rỗng, timeout một nhánh BOTH, lỗi API và nạp dở; kiểm tra thông báo không che lỗi hoặc bịa nguồn.~~

~~3. Thử rỗng, timeout một nhánh BOTH, lỗi API và nạp dở; kiểm tra thông báo không che lỗi hoặc bịa nguồn.~~

~~4. Chạy hồi quy B1 và giao diện hiện có; ghi test ID, kết quả thật và lỗi cần sửa. Đối chiếu báo cáo News đã xử lý đầy đủ.~~

~~4. Chạy hồi quy B1 và giao diện hiện có; ghi test ID, kết quả thật và lỗi cần sửa. Đối chiếu báo cáo News đã xử lý đầy đủ.~~

~~5. Phần Huyền: E2E/UI, citation, kiểm tra nguồn và hồi quy. Nhân WBS17.1 sở hữu benchmark retrieval/metrics; tổng hợp bàn giao chung sau cả hai phần.	Có kiểm thử nguồn, lỗi nhánh, hồi quy và bằng chứng chạy thật trước bàn giao.	Có receipt E2E/negative/hồi quy và mẫu kiểm tra nguồn; lỗi còn lại có người xử lý/mức ảnh hưởng. Không dùng fixture để tuyên bố graph thật đạt; WBS17 chỉ đóng khi 17.1 và 17.2 đạt.	Tuần 2. Phụ thuộc / làm trước: Chuẩn bị bằng WBS01/fixture ngay đầu tuần; nghiệm thu thật c...~~

~~	Phân công theo nhóm đã chốt. WBS10 tuần 1; WBS09 tuần 2. WBS17.1 Nhân đánh giá retrieval/B1-B2, WBS17.2 Huyền test E2E/citation. Ngày và giờ là đề xuất, làm trước bằng fixture khi còn chờ đầu vào.																											~~

~~	Số task	18	Giờ dự kiến	128	Tổng giờ thực tế đã ghi			Tuần 1 (h)	65	Tuần 2 (h)	63																	~~

~~	Sprint 4	S4-WBS17.1	S4-G07	2	WBS17.1 – Đánh giá retrieval và so sánh B1/B2 (Nhân)	Hồ Phạm Đăng Nhân	Chưa bắt đầu	7		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1. Cùng Huyền chốt bộ câu hỏi/nguồn kỳ vọng cho doanh nghiệp, chức vụ, sự kiện và VECTOR/GRAPH/BOTH.~~

~~5. Phần Nhân: test/retrieval benchmark, số đo và phân tích. Huyền WBS17.2 chịu trách nhiệm E2E giao diện/citation, kiểm tra nguồn thủ công và hồi quy.	Có output/trace từng câu, bảng B1/B2 và thời gian phản hồi, phân tích ca sai và giới hạn. Không trùng công với WBS17.2; cần cả hai phần để đóng WBS17.	WBS09 và WBS11–14; nhận báo cáo WBS16 để chốt. Chuẩn bị script/case từ fixture sớm; phối hợp Huyền theo bộ test chung, không nhân đôi giờ.														~~

~~5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.1.														~~

~~	Sprint 4	S4-WBS17.2	S4-G09	2	WBS17.2 – Kiểm thử E2E, citation và hồi quy (Huyền)	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chuẩn bị test đầu tuần cho chọn route/hỏi lại, câu hỏi trùng tên, nguồn mâu thuẫn, sai thời gian/phiên và quan hệ chưa duyệt.~~

~~5. Phần Huyền: E2E/UI, citation, kiểm tra nguồn và hồi quy. Nhân WBS17.1 sở hữu benchmark retrieval/metrics; tổng hợp bàn giao chung sau cả hai phần.	Có receipt E2E/negative/hồi quy và mẫu kiểm tra nguồn; lỗi còn lại có người xử lý/mức ảnh hưởng. Không dùng fixture để tuyên bố graph thật đạt; WBS17 chỉ đóng khi 17.1 và 17.2 đạt.	Chuẩn bị bằng WBS01/fixture ngay đầu tuần; nghiệm thu thật cần WBS09–16 và báo cáo WBS17.1. Không phải đợi Nhân chạy xong mới soạn test.														~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	63	0	0	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	7		Sprint 4 Backlog~~

~~Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G09	4	Tích hợp và nghiệm thu Sprint 4	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	6		Sprint 4 Backlog~~

~~Tổng task	196		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						~~

~~Độ hoàn thành	0.49489795918367346		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.~~

## 2026-10-26 19:42 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 19:42

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 19:32 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 19:32

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 14:42 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 14:42

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...**

🟢 **4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Đan...**

🟢 **	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Đang làm	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.**

🟢 **	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Đang làm	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.**

~~4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...~~

~~4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Đan...~~

~~	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Đang làm	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.~~

~~	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Đang làm	8		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.~~

## 2026-10-26 14:37 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 14:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 14:27 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 14:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...**

🟢 **4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Đan...**

🟢 **	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Đang làm	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.**

🟢 **	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Đang làm	8		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.**

🟢 **Nạp lặp không tạo node trùng; ID sai bị chặn.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	13		Sprint 4 Backlog**

🟢 **Nạp lặp không tạo node trùng; ID sai bị chặn.	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...~~

~~4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Chư...~~

~~	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Chưa bắt đầu	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.~~

~~	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Chưa bắt đầu	8		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	13		Sprint 4 Backlog~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-26 14:02 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 14:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **2. Xác định vai trò tổ chức/tham gia , tách ngày đăng với ngày diễn ra.**

🟢 **2. Xác định vai trò tổ chức/tham gia , tách ngày đăng với ngày diễn ra.**

~~2. Xác định vai trò tổ chức/tham gia khi nguồn chứng minh; tách ngày đăng với ngày diễn ra, không tự thay thế hai ngày.~~

~~2. Xác định vai trò tổ chức/tham gia khi nguồn chứng minh; tách ngày đăng với ngày diễn ra, không tự thay thế hai ngày.~~

## 2026-10-26 13:57 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								4	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	128	0	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	Tuần 1. Phụ thuộc / làm trước: WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ...**

🟢 **	Sprint 4	S4-WBS06	S4-G02	1	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trần Diệu Huyền	Đang làm	6		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xây quy tắc kiểm tra thực thể, chiều quan hệ, loại quan hệ, trường bắt buộc và đoạn nguồn có chứng minh kết luận hay không.**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Đang làm	52		Sprint 4 Backlog**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~								4	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	128	0	36 task chi tiết; lịch và phân công đề xuất.~~

~~4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	Tuần 1. Phụ thuộc / làm trước: WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ...~~

~~	Sprint 4	S4-WBS06	S4-G02	1	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xây quy tắc kiểm tra thực thể, chiều quan hệ, loại quan hệ, trường bắt buộc và đoạn nguồn có chứng minh kết luận hay không.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Chưa bắt đầu	52		Sprint 4 Backlog~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-26 13:52 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:52

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S4-WBS05	Trích xuất sự kiện và quan hệ từ News	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan**

🟢 **5.  Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	Tuần 1. Phụ thuộc / làm trước: WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 củ...**

🟢 **	Sprint 4	S4-WBS05	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Nguyễn Minh Quân	Chưa bắt đầu	12		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan**

🟢 **5.  Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 của Vũ.														**

~~	S4-WBS05	Trích xuất sự kiện và quan hệ từ News	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan; phân biệt tin sự kiện với bình luận/tổng hợp.~~

~~5. Xuất event/quan hệ theo contract dùng chung; kiểm tra tin đồn, phủ định và câu có điều kiện. Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	Tuần 1. Phụ thuộc / làm trước: WBS01; entity fixture để bắt...~~

~~	Sprint 4	S4-WBS05	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Nguyễn Minh Quân	Chưa bắt đầu	12		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan; phân biệt tin sự kiện với bình luận/tổng hợp.~~

~~5. Xuất event/quan hệ theo contract dùng chung; kiểm tra tin đồn, phủ định và câu có điều kiện. Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 của Vũ.														~~

## 2026-10-26 13:27 - SUA NOI DUNG

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:27

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 13:22 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:22

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 13:17 - SUA NOI DUNG

- **Người đăng:** dieuhuyentran1010@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:17

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S4-WBS03	Trích xuất sự kiện và quan hệ giữa các doang nghiệp	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

🟢 **	S4-WBS14	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trả lời và giao diện có nguồn	1. Đưa bằng chứng của tuyến được chọn vào phần trả lời hiện có; trả đúng các phần yêu cầu, gắn citation với từng nhận định.**

🟢 **	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất sự kiện và quan hệ giữa các doang nghiệp	Hồ Phạm Đăng Nhân	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

🟢 **	Sprint 4	S4-WBS14	S4-G06	2	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Nguyễn Minh Quân	Chưa bắt đầu	6		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đưa bằng chứng của tuyến được chọn vào phần trả lời hiện có; trả đúng các phần yêu cầu, gắn citation với từng nhận định.**

~~	S4-WBS03	Trích xuất sự kiện và quan hệ từ News	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.~~

~~	S4-WBS14	Tạo câu trả lời và citation theo kết quả routing	Trả lời và giao diện có nguồn	1. Đưa bằng chứng của tuyến được chọn vào phần trả lời hiện có; trả đúng các phần yêu cầu, gắn citation với từng nhận định.~~

~~	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Hồ Phạm Đăng Nhân	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.~~

~~	Sprint 4	S4-WBS14	S4-G06	2	Tạo câu trả lời và citation theo kết quả routing	Nguyễn Minh Quân	Chưa bắt đầu	6		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đưa bằng chứng của tuyến được chọn vào phần trả lời hiện có; trả đúng các phần yêu cầu, gắn citation với từng nhận định.~~

## 2026-10-26 13:12 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:12

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 13:07 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 13:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S4-WBS03	Trích xuất sự kiện và quan hệ từ News	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

🟢 **	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Hồ Phạm Đăng Nhân	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

~~	S4-WBS03	Trích xuất quan hệ doanh nghiệp	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.~~

~~	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất quan hệ doanh nghiệp	Hồ Phạm Đăng Nhân	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.~~

## 2026-10-26 08:37 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 08:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-26 08:32 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-26 08:32

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-25 23:02 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-25 23:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

~~																		#N/A~~

## 2026-10-25 22:52 - SUA NOI DUNG

- **Người đăng:** yu382005@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-25 22:52

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								4	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	128	0	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	S4-WBS01	Chốt dữ liệu, schema và contract Graph RAG	Contract và thực thể graph	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.**

🟢 **2. Thống nhất Company, Person, Event; loại và chiều quan hệ; thời gian, chức vụ, tỷ lệ sở hữu nếu nguồn có.**

🟢 **2. Thống nhất Company, Person, Event; loại và chiều quan hệ; thời gian, chức vụ, tỷ lệ sở hữu nếu nguồn có.**

🟢 **3. Quy định đầu ra chung của extractor, kiểm duyệt, Supabase, Neo4j và retrieval; bắt buộc giữ mã chunk/locator, đoạn nguồn và phiên dữ liệu.**

🟢 **3. Quy định đầu ra chung của extractor, kiểm duyệt, Supabase, Neo4j và retrieval; bắt buộc giữ mã chunk/locator, đoạn nguồn và phiên dữ liệu.**

🟢 **4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Tuần 1. Phụ thuộc / làm trước: Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầ...**

🟢 **	S4-WBS02	Nhận diện và chuẩn hóa thực thể	Contract và thực thể graph	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.**

🟢 **2. Ánh xạ tên viết tắt, tên đầy đủ và ticker về ID thống nhất khi đủ căn cứ; dùng cùng ID cho mọi extractor.**

🟢 **2. Ánh xạ tên viết tắt, tên đầy đủ và ticker về ID thống nhất khi đủ căn cứ; dùng cùng ID cho mọi extractor.**

🟢 **3. Không gộp người chỉ vì trùng tên; dùng công ty, chức vụ và ngữ cảnh, chưa rõ thì trả trạng thái cần xác minh.**

🟢 **3. Không gộp người chỉ vì trùng tên; dùng công ty, chức vụ và ngữ cảnh, chưa rõ thì trả trạng thái cần xác minh.**

🟢 **4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Định danh thực thể thống nhất, có đầu vào và contract cho các nhánh làm song song.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Tuần 1. Phụ thuộc / làm trước: Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.	Rất cao	Chư...**

🟢 **	S4-WBS03	Trích xuất quan hệ doanh nghiệp	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

🟢 **2. Phân biệt sở hữu với hợp tác. Chỉ ghi tỷ lệ và thời điểm khi nguồn nêu rõ, không tự suy ngưỡng hay số phần trăm.**

🟢 **2. Phân biệt sở hữu với hợp tác. Chỉ ghi tỷ lệ và thời điểm khi nguồn nêu rõ, không tự suy ngưỡng hay số phần trăm.**

🟢 **3. Giữ đoạn chứng minh, document/chunk ID và locator; xử lý phủ định, dự kiến và quan hệ đã thay đổi.**

🟢 **3. Giữ đoạn chứng minh, document/chunk ID và locator; xử lý phủ định, dự kiến và quan hệ đã thay đổi.**

🟢 **4. Dùng ID WBS02 để xuất đúng contract; kiểm tra mẫu hợp lệ, sai chiều, thiếu chủ thể và hai tên chỉ xuất hiện cùng đoạn.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Có quan hệ doanh nghiệp ứng viên kèm nguồn, trạng thái và thời gian nếu có; test không tạo quan hệ chỉ từ đồng xuất hiện.	Tuần 1. Phụ thuộc / làm trước: Contract WBS01; chuẩn hóa thật WBS02 để đóng task. Có thể code bằng entity fixture từ 27/10, không phải đ...**

🟢 **	S4-WBS04	Trích xuất quan hệ chức vụ	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Xác định người–chức vụ–doanh nghiệp; giữ tên chức vụ gốc và ánh xạ tên chuẩn theo contract.**

🟢 **2. Phân biệt đề cử, bổ nhiệm, đang giữ chức, từ nhiệm và miễn nhiệm; giữ nhiệm kỳ hoặc thời điểm nguồn xác nhận.**

🟢 **2. Phân biệt đề cử, bổ nhiệm, đang giữ chức, từ nhiệm và miễn nhiệm; giữ nhiệm kỳ hoặc thời điểm nguồn xác nhận.**

🟢 **3. Không biến bài báo cũ thành chứng minh đang giữ chức; không ghi đè mất lịch sử hoặc gộp người trùng tên.**

🟢 **3. Không biến bài báo cũ thành chứng minh đang giữ chức; không ghi đè mất lịch sử hoặc gộp người trùng tên.**

🟢 **4. Bàn giao quan hệ ứng viên có đoạn nguồn; thử ca nhiều chức vụ, nhiều công ty, thiếu thời gian và nguồn mâu thuẫn.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Quan hệ chức vụ đủ người, tổ chức, chức danh và provenance; không nhầm trạng thái hoặc thời gian; ca chưa rõ được đánh dấu.	Tuần 1. Phụ thuộc / làm trước: WBS01; dùng WBS02 thật để nghiệm thu. Có thể làm bằng fixture song song WBS03/WBS05 và phần lưu metadata WBS...**

🟢 **	S4-WBS05	Trích xuất sự kiện và quan hệ từ News	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan; phân biệt tin sự kiện với bình luận/tổng hợp.**

🟢 **2. Xác định vai trò tổ chức/tham gia khi nguồn chứng minh; tách ngày đăng với ngày diễn ra, không tự thay thế hai ngày.**

🟢 **2. Xác định vai trò tổ chức/tham gia khi nguồn chứng minh; tách ngày đăng với ngày diễn ra, không tự thay thế hai ngày.**

🟢 **3. Phân biệt đã xảy ra, dự kiến, bị hủy và chưa xác nhận; không suy diễn tác động tài chính hoặc nhân quả.**

🟢 **3. Phân biệt đã xảy ra, dự kiến, bị hủy và chưa xác nhận; không suy diễn tác động tài chính hoặc nhân quả.**

🟢 **4. Nhận diện bài trùng/cập nhật cùng sự kiện nhưng giữ mọi nguồn hỗ trợ và thông tin mâu thuẫn.**

🟢 **4. Nhận diện bài trùng/cập nhật cùng sự kiện nhưng giữ mọi nguồn hỗ trợ và thông tin mâu thuẫn.**

🟢 **5. Xuất event/quan hệ theo contract dùng chung; kiểm tra tin đồn, phủ định và câu có điều kiện. Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	Tuần 1. Phụ thuộc / làm trước: WBS01; entity fixture để bắt...**

🟢 **	S4-WBS06	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Xây quy tắc kiểm tra thực thể, chiều quan hệ, loại quan hệ, trường bắt buộc và đoạn nguồn có chứng minh kết luận hay không.**

🟢 **2. Kiểm tra mã nguồn, locator và phiên dữ liệu; không coi JSON đúng cấu trúc là nguồn đã được xác minh.**

🟢 **2. Kiểm tra mã nguồn, locator và phiên dữ liệu; không coi JSON đúng cấu trúc là nguồn đã được xác minh.**

🟢 **3. Trả chấp nhận/chờ duyệt/từ chối cùng lý do; thống nhất với Vũ (WBS07) nơi lưu kết quả, quarantine và quyền đổi trạng thái.**

🟢 **3. Trả chấp nhận/chờ duyệt/từ chối cùng lý do; thống nhất với Vũ (WBS07) nơi lưu kết quả, quarantine và quyền đổi trạng thái.**

🟢 **4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	Tuần 1. Phụ thuộc / làm trước: WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ...**

🟢 **	S4-WBS07	Quản lý metadata và phiên graph trên Supabase	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Đối chiếu schema thật, chuẩn bị migration bổ sung liên kết extraction với thực thể, chunk/locator và graph version; chỉ bổ sung phần thiếu.**

🟢 **2. Bổ sung index và ràng buộc cần thiết; phân biệt schema version với ID lần xây graph; thống nhất trạng thái với WBS06.**

🟢 **2. Bổ sung index và ràng buộc cần thiết; phân biệt schema version với ID lần xây graph; thống nhất trạng thái với WBS06.**

🟢 **3. Code lưu/đọc extraction, nguyên nhân chờ duyệt/từ chối và quarantine; chạy lại không tạo trùng theo contract.**

🟢 **3. Code lưu/đọc extraction, nguyên nhân chờ duyệt/từ chối và quarantine; chạy lại không tạo trùng theo contract.**

🟢 **4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	Tuần 1. Phụ thuộc / làm trước: WBS01 và trạng thái WBS06 (có thể...**

🟢 **	S4-WBS08	Lưu graph trên Neo4j và chuẩn bị đối chiếu nguồn	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Tái sử dụng phần phù hợp của GraphStore; thêm constraint/index cho Company, Person, Event và quan hệ có phiên bản.**

🟢 **2. Nạp node/cạnh theo lô, giữ khóa cạnh liên kết extraction Supabase và các nguồn hỗ trợ.**

🟢 **2. Nạp node/cạnh theo lô, giữ khóa cạnh liên kết extraction Supabase và các nguồn hỗ trợ.**

🟢 **3. Chạy lại cùng đầu vào không tạo trùng; không ghi đè mất thời gian/lịch sử và provenance.**

🟢 **3. Chạy lại cùng đầu vào không tạo trùng; không ghi đè mất thời gian/lịch sử và provenance.**

🟢 **4. Xử lý lỗi nạp dở, chuẩn bị resume và đối chiếu số liệu/khóa giữa hai hệ thống. Nghiệm thu phần ghi bằng fixture ở tuần 1; WBS09 nối extraction thật tuần 2.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Bộ ghi graph có test chống trùng, không lẫn phiên, giữ extraction/nguồn và không công bố lần nạp dở. Có graph fixture dùng cho truy vấn.	Tuần 1. Phụ thuộc / làm trước: WBS01; thống nhất metadata/version với WBS07. Không p...**

🟢 **	S4-WBS10	Phân tích ý định và Hybrid Router bằng fixture	Hybrid Routing và hợp nhất bằng chứng	1. Phân tích câu hỏi cùng ngữ cảnh: người dùng cần nội dung/số liệu, quan hệ, hay cả hai; lấy thực thể, thời gian và thông tin thiếu.**

🟢 **2. Chọn VECTOR, GRAPH hoặc BOTH. Câu hỏi mơ hồ thì hỏi lại trước truy xuất, không mặc định chạy cả hai; với BOTH ghi phần việc của từng nhánh.**

🟢 **2. Chọn VECTOR, GRAPH hoặc BOTH. Câu hỏi mơ hồ thì hỏi lại trước truy xuất, không mặc định chạy cả hai; với BOTH ghi phần việc của từng nhánh.**

🟢 **3. VECTOR gồm tìm kiếm vector/BM25 hiện có. GRAPH có thể đọc đoạn nguồn qua ID để citation mà không biến thành BOTH.**

🟢 **3. VECTOR gồm tìm kiếm vector/BM25 hiện có. GRAPH có thể đọc đoạn nguồn qua ID để citation mà không biến thành BOTH.**

🟢 **4. Gọi adapter giả lập và ghi intent, route, entities, time scope, missing fields, lý do chọn tuyến và trace.**

🟢 **4. Gọi adapter giả lập và ghi intent, route, entities, time scope, missing fields, lý do chọn tuyến và trace.**

🟢 **5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	Tuần 1. Phụ thuộc / làm trước: WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-lo...**

🟢 **	S4-WBS09	Tích hợp các nhánh trích xuất và hoàn thiện graph retrieval	Tích hợp pipeline và graph retrieval	1. 09.1 Nối đầu ra extractor doanh nghiệp, chức vụ và sự kiện vào pipeline chung; kiểm tra cùng contract.**

🟢 **2. 09.2 Thống nhất ID, chiều quan hệ, thời gian; gộp trùng nhưng giữ nguồn và chuyển mâu thuẫn sang WBS06.**

🟢 **2. 09.2 Thống nhất ID, chiều quan hệ, thời gian; gộp trùng nhưng giữ nguồn và chuyển mâu thuẫn sang WBS06.**

🟢 **3. 09.3 Nối kiểm duyệt với Supabase (WBS07) và Neo4j (WBS08), đối chiếu extraction/cạnh; chỉ công bố graph version sẵn sàng khi đạt.**

🟢 **3. 09.3 Nối kiểm duyệt với Supabase (WBS07) và Neo4j (WBS08), đối chiếu extraction/cạnh; chỉ công bố graph version sẵn sàng khi đạt.**

🟢 **4. 09.4 Viết truy vấn có tham số theo thực thể, loại quan hệ, thời gian và corpus/graph version; giới hạn 1–2 hop, số kết quả và timeout.**

🟢 **4. 09.4 Viết truy vấn có tham số theo thực thể, loại quan hệ, thời gian và corpus/graph version; giới hạn 1–2 hop, số kết quả và timeout.**

🟢 **5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Tuần 2. Phụ thuộc / làm trước: Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fix...**

🟢 **	S4-WBS11	Nối nhánh Vector RAG vào Hybrid Router	Adapter truy xuất và xử lý lỗi	1. Bọc vector/BM25 hiện có thành adapter theo WBS10, không làm lại chunking/embedding.**

🟢 **2. Truyền đúng công ty, kỳ, loại nguồn và corpus; giữ nguyên evidence/citation phù hợp với contract.**

🟢 **2. Truyền đúng công ty, kỳ, loại nguồn và corpus; giữ nguyên evidence/citation phù hợp với contract.**

🟢 **3. Xử lý rỗng, lỗi và timeout; ghi trạng thái nhánh. VECTOR không gọi graph khi không cần.**

🟢 **3. Xử lý rỗng, lỗi và timeout; ghi trạng thái nhánh. VECTOR không gọi graph khi không cần.**

🟢 **4. Chạy hồi quy các câu B1 đã hoạt động và bàn giao adapter thật cho WBS13.	Dùng lại nhánh B1 với đúng scope, giữ evidence và trạng thái rỗng/lỗi rõ ràng.	VECTOR chạy được nguồn thật, giữ phạm vi/metadata và không làm hỏng B1; có test các ca rỗng/lỗi.	Tuần 2. Phụ thuộc / làm trước: WBS10 và Vector RAG Sprint 3. Không chờ WBS09. Làm sớm đầu tuần 2 để Vũ còn thời gian WBS16.	Cao	Chưa bắt đầu	S4-G05	FinMind	4	4		Đinh Huỳnh Vũ	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:...**

🟢 **	S4-WBS12	Nối nhánh Graph RAG vào Hybrid Router	Tích hợp pipeline và graph retrieval	1. Chuyển intent/slots của WBS10 sang tham số truy vấn WBS09; không sinh Cypher tùy ý từ câu hỏi.**

🟢 **2. Giữ đúng thực thể, thời gian và corpus/graph version. Nhận quan hệ được chấp nhận cùng đường đi, extraction và nguồn.**

🟢 **2. Giữ đúng thực thể, thời gian và corpus/graph version. Nhận quan hệ được chấp nhận cùng đường đi, extraction và nguồn.**

🟢 **3. Đọc lại nguồn qua ID để citation; xử lý tên mơ hồ, không có quan hệ, graph chưa sẵn sàng và timeout.**

🟢 **3. Đọc lại nguồn qua ID để citation; xử lý tên mơ hồ, không có quan hệ, graph chưa sẵn sàng và timeout.**

🟢 **4. Chuẩn bị adapter bằng fixture từ đầu tuần, nối retrieval thật sau khi WBS09 bàn giao; kiểm tra không lộ quan hệ chờ duyệt.	Các extractor nối chung với Supabase/Neo4j và trả quan hệ đúng phạm vi trong tối đa hai hop.	GRAPH chạy bằng graph thật đúng scope, có nguồn và lỗi rõ; đọc lại nguồn bằng ID không bị gắn nhãn BOTH.	Tuần 2. Phụ thuộc / làm trước: Contract WBS10; WBS09 thật để đóng task. Có thể code adapter bằng fixture trước, không đứng chờ pipeline ghép xong.	Cao	Chưa bắt đầu	S4-G03	FinMi...**

🟢 **	S4-WBS13	Thực hiện tuyến BOTH và hợp nhất bằng chứng	Hybrid Routing và hợp nhất bằng chứng	1. Nhận routing plan và phần yêu cầu của từng nhánh. Gọi VECTOR/GRAPH; nếu vector cần thực thể từ graph thì thực hiện theo thứ tự phù hợp.**

🟢 **2. Chỉ mở rộng tìm kiếm trong phạm vi được phép; gộp, khử trùng nhưng giữ provenance và nhánh tạo ra mỗi bằng chứng.**

🟢 **2. Chỉ mở rộng tìm kiếm trong phạm vi được phép; gộp, khử trùng nhưng giữ provenance và nhánh tạo ra mỗi bằng chứng.**

🟢 **3. Xếp hạng theo phương pháp thống nhất, không cộng trực tiếp cosine và điểm graph khác nghĩa.**

🟢 **3. Xếp hạng theo phương pháp thống nhất, không cộng trực tiếp cosine và điểm graph khác nghĩa.**

🟢 **4. Chặn kết quả lẫn thực thể, thời gian hoặc phiên dữ liệu; báo rõ khi một nhánh rỗng/lỗi/timeout, giữ trace chứng minh nhánh thực sự chạy.**

🟢 **4. Chặn kết quả lẫn thực thể, thời gian hoặc phiên dữ liệu; báo rõ khi một nhánh rỗng/lỗi/timeout, giữ trace chứng minh nhánh thực sự chạy.**

🟢 **5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	Chọn VECTOR/GRAPH/BOTH theo ý định; hợp nhất có provenance và không che lỗi nhánh.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	Tuần 2. Phụ thuộc / làm trước: WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.1.	Rất cao	Chưa bắt đầu	S4-G04	FinMind	4	7		Nguyễn Minh Quân	Mon Nov 02 2026 07:00:00 ...**

🟢 **	S4-WBS14	Tạo câu trả lời và citation theo kết quả routing	Trả lời và giao diện có nguồn	1. Đưa bằng chứng của tuyến được chọn vào phần trả lời hiện có; trả đúng các phần yêu cầu, gắn citation với từng nhận định.**

🟢 **2. Giữ thời gian/chức vụ và trạng thái sự kiện; không chuyển dự kiến/tin chưa xác nhận thành sự thật đã xảy ra.**

🟢 **2. Giữ thời gian/chức vụ và trạng thái sự kiện; không chuyển dự kiến/tin chưa xác nhận thành sự thật đã xảy ra.**

🟢 **3. Thiếu chứng cứ hoặc một nhánh BOTH lỗi phải báo phần còn thiếu; không dùng không tìm thấy để kết luận quan hệ không tồn tại hoặc số liệu bằng 0.**

🟢 **3. Thiếu chứng cứ hoặc một nhánh BOTH lỗi phải báo phần còn thiếu; không dùng không tìm thấy để kết luận quan hệ không tồn tại hoặc số liệu bằng 0.**

🟢 **4. Hỏi lại nguồn câu trả lời trước thì đọc đúng evidence đã lưu, không tạo nguồn mới. Kiểm tra ba tuyến bằng fixture rồi nguồn thật.**

🟢 **4. Hỏi lại nguồn câu trả lời trước thì đọc đúng evidence đã lưu, không tạo nguồn mới. Kiểm tra ba tuyến bằng fixture rồi nguồn thật.**

🟢 **5. Giữ cấu hình B1 để so sánh; không tự bật Evidence Gate/verifier B3 thuộc sprint sau.	Chat/Graph Viewer trình bày đúng bằng chứng, thời gian và giới hạn của kết quả.	Câu trả lời/citation truy lại được nguồn, không bịa quan hệ/số liệu hoặc che lỗi nhánh; có test và gói bàn giao.	Tuần 2. Phụ thuộc / làm trước: Evidence contract và WBS11–13. Có thể chuẩn bị formatter/citation bằng fixture trước, nghiệm thu sau tuyến thật.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	6		Nguyễn Minh Quân	Tue Nov 03 2026 07:00...**

🟢 **	S4-WBS15	Nối Graph Viewer và xem bằng chứng thật	Trả lời và giao diện có nguồn	1. Tái sử dụng Graph Viewer; nối API theo contract để hiển thị Company, Person, Event và quan hệ.**

🟢 **2. Bấm cạnh xem extraction, thời gian, đoạn nguồn và trạng thái; giữ locator gốc, không tạo page PDF giả cho News.**

🟢 **2. Bấm cạnh xem extraction, thời gian, đoạn nguồn và trạng thái; giữ locator gốc, không tạo page PDF giả cho News.**

🟢 **3. Giữ đúng phạm vi và phiên graph; xử lý rỗng, nhiều kết quả, lỗi tải hoặc nguồn không truy cập được.**

🟢 **3. Giữ đúng phạm vi và phiên graph; xử lý rỗng, nhiều kết quả, lỗi tải hoặc nguồn không truy cập được.**

🟢 **4. Kiểm tra dữ liệu hiển thị khớp backend và màn hình hẹp; không thay lỗi API bằng dữ liệu minh họa.**

🟢 **4. Kiểm tra dữ liệu hiển thị khớp backend và màn hình hẹp; không thay lỗi API bằng dữ liệu minh họa.**

🟢 **5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Chat/Graph Viewer trình bày đúng bằng chứng, thời gian và giới hạn của kết quả.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Tuần 2. Phụ thuộc / làm trước: Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	6		Trần Diệu Huyền	Mon Nov 02 2026 07:00:00...**

🟢 **	S4-WBS16	Chạy toàn bộ News đã chốt và đối chiếu kết quả	Trích xuất, kiểm duyệt và lưu quan hệ có nguồn	1. Chuẩn bị batch runner từ danh sách đóng băng WBS01 và interface extractor; có thể dùng fixture từ 02/11.**

🟢 **2. Chỉ chạy full-load sau receipt mẫu WBS09.5 đạt. Chạy toàn bộ News trong manifest, không tự thêm nguồn.**

🟢 **2. Chỉ chạy full-load sau receipt mẫu WBS09.5 đạt. Chạy toàn bộ News trong manifest, không tự thêm nguồn.**

🟢 **3. Ghi trạng thái từng tài liệu và số quan hệ chấp nhận/chờ duyệt/từ chối; tách không có quan hệ với xử lý lỗi.**

🟢 **3. Ghi trạng thái từng tài liệu và số quan hệ chấp nhận/chờ duyệt/từ chối; tách không có quan hệ với xử lý lỗi.**

🟢 **4. Hỗ trợ resume/chạy lại lỗi không tạo trùng; đối chiếu số tài liệu đầu vào với số có trạng thái và đối chiếu khóa Supabase–Neo4j.**

🟢 **4. Hỗ trợ resume/chạy lại lỗi không tạo trùng; đối chiếu số tài liệu đầu vào với số có trạng thái và đối chiếu khóa Supabase–Neo4j.**

🟢 **5. Bàn giao báo cáo full-load, lỗi còn lại và phiên dữ liệu. 8h là công chuẩn bị, theo dõi và đối chiếu, không phải cam kết thời gian máy/LLM hay duyệt thủ công mọi quan hệ.	Quan hệ doanh nghiệp, chức vụ, sự kiện có nguồn và trạng thái; dữ liệu lưu lại được và toàn bộ News đã chốt có báo cáo.	Toàn bộ News đã chốt có trạng thái, không mất tin lỗi; có báo cáo mẫu/full-load riêng và danh sách lỗi chưa xử lý. Không coi mọi quan hệ trích xuất là đã được chấp nhận.	Tuần 2. Phụ thuộc / làm trước: WBS01...**

🟢 **	S4-WBS17.1	WBS17.1 – Đánh giá retrieval và so sánh B1/B2 (Nhân)	Đánh giá retrieval và so sánh B1/B2	1. Cùng Huyền chốt bộ câu hỏi/nguồn kỳ vọng cho doanh nghiệp, chức vụ, sự kiện và VECTOR/GRAPH/BOTH.**

🟢 **2. Chạy cùng bộ ca và điều kiện trên B1/B2; giữ corpus, model và phiên cấu hình được ghi rõ để so sánh.**

🟢 **2. Chạy cùng bộ ca và điều kiện trên B1/B2; giữ corpus, model và phiên cấu hình được ghi rõ để so sánh.**

🟢 **3. Đối chiếu route, thực thể, chiều quan hệ, thời gian, evidence, trạng thái từng nhánh và latency; ghi các ca graph giúp hoặc gây lỗi.**

🟢 **3. Đối chiếu route, thực thể, chiều quan hệ, thời gian, evidence, trạng thái từng nhánh và latency; ghi các ca graph giúp hoặc gây lỗi.**

🟢 **4. Tổng hợp chỉ số, đầu ra từng câu và kết quả full-load WBS16; không mặc định B2 tốt hơn B1.**

🟢 **4. Tổng hợp chỉ số, đầu ra từng câu và kết quả full-load WBS16; không mặc định B2 tốt hơn B1.**

🟢 **5. Phần Nhân: test/retrieval benchmark, số đo và phân tích. Huyền WBS17.2 chịu trách nhiệm E2E giao diện/citation, kiểm tra nguồn thủ công và hồi quy.	Có kết quả từng ca và số đo thực tế trên cùng điều kiện, nêu cả cải thiện và suy giảm.	Có output/trace từng câu, bảng B1/B2 và thời gian phản hồi, phân tích ca sai và giới hạn. Không trùng công với WBS17.2; cần cả hai phần để đóng WBS17.	Tuần 2. Phụ thuộc / làm trước: WBS09 và WBS11–14; nhận báo cáo WBS16 để chốt. Chuẩn bị script/case từ fixture s...**

🟢 **	S4-WBS17.2	WBS17.2 – Kiểm thử E2E, citation và hồi quy (Huyền)	Kiểm thử E2E và nghiệm thu Sprint 4	1. Chuẩn bị test đầu tuần cho chọn route/hỏi lại, câu hỏi trùng tên, nguồn mâu thuẫn, sai thời gian/phiên và quan hệ chưa duyệt.**

🟢 **2. Kiểm tra câu hỏi → chat → nguồn → Graph Viewer trên ba tuyến; đọc nguồn mẫu để đối chiếu nhận định, không chỉ nhìn schema đúng.**

🟢 **2. Kiểm tra câu hỏi → chat → nguồn → Graph Viewer trên ba tuyến; đọc nguồn mẫu để đối chiếu nhận định, không chỉ nhìn schema đúng.**

🟢 **3. Thử rỗng, timeout một nhánh BOTH, lỗi API và nạp dở; kiểm tra thông báo không che lỗi hoặc bịa nguồn.**

🟢 **3. Thử rỗng, timeout một nhánh BOTH, lỗi API và nạp dở; kiểm tra thông báo không che lỗi hoặc bịa nguồn.**

🟢 **4. Chạy hồi quy B1 và giao diện hiện có; ghi test ID, kết quả thật và lỗi cần sửa. Đối chiếu báo cáo News đã xử lý đầy đủ.**

🟢 **4. Chạy hồi quy B1 và giao diện hiện có; ghi test ID, kết quả thật và lỗi cần sửa. Đối chiếu báo cáo News đã xử lý đầy đủ.**

🟢 **5. Phần Huyền: E2E/UI, citation, kiểm tra nguồn và hồi quy. Nhân WBS17.1 sở hữu benchmark retrieval/metrics; tổng hợp bàn giao chung sau cả hai phần.	Có kiểm thử nguồn, lỗi nhánh, hồi quy và bằng chứng chạy thật trước bàn giao.	Có receipt E2E/negative/hồi quy và mẫu kiểm tra nguồn; lỗi còn lại có người xử lý/mức ảnh hưởng. Không dùng fixture để tuyên bố graph thật đạt; WBS17 chỉ đóng khi 17.1 và 17.2 đạt.	Tuần 2. Phụ thuộc / làm trước: Chuẩn bị bằng WBS01/fixture ngay đầu tuần; nghiệm thu thật c...**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **																		#N/A**

🟢 **	Mục tiêu Sprint 4: Graph RAG cho quan hệ doanh nghiệp, chức vụ và sự kiện; Hybrid Router chọn VECTOR/GRAPH/BOTH. Dùng lại chunk và B1 Sprint 3.																											**

🟢 **	Phân công theo nhóm đã chốt. WBS10 tuần 1; WBS09 tuần 2. WBS17.1 Nhân đánh giá retrieval/B1-B2, WBS17.2 Huyền test E2E/citation. Ngày và giờ là đề xuất, làm trước bằng fixture khi còn chờ đầu vào.																											**

🟢 **	Số task	18	Giờ dự kiến	128	Tổng giờ thực tế đã ghi			Tuần 1 (h)	65	Tuần 2 (h)	63																	**

🟢 **	Sprint 4	S4-WBS01	S4-G01	1	Chốt dữ liệu, schema và contract Graph RAG	Thái Quốc Hưng	Chưa bắt đầu	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chốt danh sách tài liệu và toàn bộ News đã duyệt trong corpus; ghi ID, nguồn và số lượng, không tự mở rộng nguồn trong sprint.**

🟢 **4. Tạo fixture hợp lệ, thiếu metadata và mơ hồ cho ba nhóm quan hệ và ba tuyến VECTOR/GRAPH/BOTH; bàn giao contract ngay 26/10 để các nhánh làm song song.	Có manifest đầu vào, contract và fixture được team thống nhất. Không làm lại chunking. Giữ contract và bộ ca B1 hiện có để đối chứng.	Đầu vào: chunk, metadata nguồn, corpus và giao diện/Vector RAG Sprint 3. Không chờ graph thật. Đầu ra ngày 26/10 mở đường cho WBS02–08 và WBS10.														**

🟢 **	Sprint 4	S4-WBS02	S4-G01	1	Nhận diện và chuẩn hóa thực thể	Thái Quốc Hưng	Chưa bắt đầu	8		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đọc chunk hiện có cùng metadata; tìm tên công ty, người và sự kiện, giữ tên nguyên văn và đoạn xuất hiện.**

🟢 **4. Kiểm tra cùng đầu vào không tạo ID trùng hoặc thay đổi tùy ý; bàn giao interface/fixture sớm rồi nối bộ chuẩn hóa thật trước 29/10.	Thực thể có ID và alias nhất quán, có provenance; ca trùng tên không bị gộp sai; có test và bộ mẫu bàn giao.	Phụ thuộc WBS01. WBS03–05 được dùng thực thể fixture trước; chỉ nghiệm thu bản nối thật sau WBS02. Không phụ thuộc Neo4j/Supabase.														**

🟢 **	Sprint 4	S4-WBS03	S4-G02	1	Trích xuất quan hệ doanh nghiệp	Hồ Phạm Đăng Nhân	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Từ chunk thật, lấy phát biểu về công ty con, liên kết, sở hữu và hợp tác; xác định hai thực thể và chiều quan hệ.**

🟢 **4. Dùng ID WBS02 để xuất đúng contract; kiểm tra mẫu hợp lệ, sai chiều, thiếu chủ thể và hai tên chỉ xuất hiện cùng đoạn.	Có quan hệ doanh nghiệp ứng viên kèm nguồn, trạng thái và thời gian nếu có; test không tạo quan hệ chỉ từ đồng xuất hiện.	Contract WBS01; chuẩn hóa thật WBS02 để đóng task. Có thể code bằng entity fixture từ 27/10, không phải đợi WBS02 xong mới bắt đầu.														**

🟢 **	Sprint 4	S4-WBS04	S4-G02	1	Trích xuất quan hệ chức vụ	Đinh Huỳnh Vũ	Chưa bắt đầu	6		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xác định người–chức vụ–doanh nghiệp; giữ tên chức vụ gốc và ánh xạ tên chuẩn theo contract.**

🟢 **4. Bàn giao quan hệ ứng viên có đoạn nguồn; thử ca nhiều chức vụ, nhiều công ty, thiếu thời gian và nguồn mâu thuẫn.	Quan hệ chức vụ đủ người, tổ chức, chức danh và provenance; không nhầm trạng thái hoặc thời gian; ca chưa rõ được đánh dấu.	WBS01; dùng WBS02 thật để nghiệm thu. Có thể làm bằng fixture song song WBS03/WBS05 và phần lưu metadata WBS07.														**

🟢 **	Sprint 4	S4-WBS05	S4-G02	1	Trích xuất sự kiện và quan hệ từ News	Nguyễn Minh Quân	Chưa bắt đầu	12		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhận diện sự kiện phù hợp từ News trong manifest và các bên liên quan; phân biệt tin sự kiện với bình luận/tổng hợp.**

🟢 **5. Xuất event/quan hệ theo contract dùng chung; kiểm tra tin đồn, phủ định và câu có điều kiện. Bàn giao extractor theo lô cho WBS16; chưa chạy full-load trong task này.	Extractor sự kiện chạy được trên News thật mẫu; giữ nguồn, ngày và trạng thái; không công bố nội dung mơ hồ thành sự thật. Có test và interface batch.	WBS01; entity fixture để bắt đầu, WBS02 thật để nghiệm thu. Phần bất định chuyển WBS06. Chạy toàn bộ News thuộc WBS16 của Vũ.														**

🟢 **	Sprint 4	S4-WBS06	S4-G02	1	Kiểm tra bằng chứng, kiểm duyệt và quarantine	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Xây quy tắc kiểm tra thực thể, chiều quan hệ, loại quan hệ, trường bắt buộc và đoạn nguồn có chứng minh kết luận hay không.**

🟢 **4. Thử fixture từ 26/10, rồi thử đầu ra thật của ba extractor khi sẵn sàng. Chỉ kết quả được chấp nhận đủ điều kiện đưa vào graph trả lời.	Ba nhóm quan hệ có kết quả kiểm tra và lý do; ca mơ hồ/mâu thuẫn đi chờ duyệt; ca thiếu nguồn bị chặn; có test.	WBS01 để code ngay. Cần mẫu thật WBS03–05 để nghiệm thu từng loại. WBS07 lưu trạng thái; không chờ cả ba extractor mới chuẩn bị quy tắc.														**

🟢 **	Sprint 4	S4-WBS07	S4-G02	1	Quản lý metadata và phiên graph trên Supabase	Đinh Huỳnh Vũ	Chưa bắt đầu	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đối chiếu schema thật, chuẩn bị migration bổ sung liên kết extraction với thực thể, chunk/locator và graph version; chỉ bổ sung phần thiếu.**

🟢 **4. Kiểm tra quyền đọc/ghi thực tế của ứng dụng. Thử migration trên môi trường được phép và lưu bằng chứng; chưa gắn graph chưa hoàn tất vào corpus đang dùng.	Repository/migration được kiểm tra; metadata truy lại được nguồn; có giới hạn quyền và kiểm tra chống trùng/phiên bản. Không coi đã bật RLS là đủ nghiệm thu.	WBS01 và trạng thái WBS06 (có thể chốt interface song song). Dùng repository fixture trước DB thật. Phối hợp khóa extraction/version với Nhân WBS08.														**

🟢 **	Sprint 4	S4-WBS08	S4-G02	1	Lưu graph trên Neo4j và chuẩn bị đối chiếu nguồn	Hồ Phạm Đăng Nhân	Chưa bắt đầu	7		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng phần phù hợp của GraphStore; thêm constraint/index cho Company, Person, Event và quan hệ có phiên bản.**

🟢 **4. Xử lý lỗi nạp dở, chuẩn bị resume và đối chiếu số liệu/khóa giữa hai hệ thống. Nghiệm thu phần ghi bằng fixture ở tuần 1; WBS09 nối extraction thật tuần 2.	Bộ ghi graph có test chống trùng, không lẫn phiên, giữ extraction/nguồn và không công bố lần nạp dở. Có graph fixture dùng cho truy vấn.	WBS01; thống nhất metadata/version với WBS07. Không phải đợi full extractor; dùng graph fixture trước. WBS09 chịu trách nhiệm ghép dữ liệu thật.														**

🟢 **	Sprint 4	S4-WBS10	S4-G04	1	Phân tích ý định và Hybrid Router bằng fixture	Trần Diệu Huyền	Chưa bắt đầu	8		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1. Phân tích câu hỏi cùng ngữ cảnh: người dùng cần nội dung/số liệu, quan hệ, hay cả hai; lấy thực thể, thời gian và thông tin thiếu.**

🟢 **5. Kiểm tra nhiều cách diễn đạt, trùng tên, thiếu kỳ và yêu cầu kết hợp. Bàn giao interface cho WBS11–13; chưa đợi graph thật.	Router chọn đúng ba tuyến trên bộ ca fixture, hỏi lại đúng khi chưa rõ; có lý do/trace và contract adapter. Nối nhánh thật trong tuần 2.	WBS01 và intent/context B1 Sprint 3. Hoàn toàn có thể làm song song trích xuất dữ liệu. Không phụ thuộc WBS09 hoặc full-load.														**

🟢 **	Sprint 4	S4-WBS09	S4-G03	2	Tích hợp các nhánh trích xuất và hoàn thiện graph retrieval	Thái Quốc Hưng	Chưa bắt đầu	14		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. 09.1 Nối đầu ra extractor doanh nghiệp, chức vụ và sự kiện vào pipeline chung; kiểm tra cùng contract.**

🟢 **5. 09.5 Chạy mẫu thật đủ ba loại quan hệ, thử nạp lại/lỗi; bàn giao graph retrieval và receipt mẫu đạt trước khi Vũ chạy toàn bộ News.	Có đường chạy thật chunk → extractor → kiểm duyệt → Supabase/Neo4j → retrieval có nguồn; không trùng/lẫn phiên, không dùng quan hệ chưa duyệt. Có receipt mẫu sẵn sàng full-load.	Nghiệm thu cần WBS02–08. Có thể chuẩn bị điều phối/query từ fixture trước; không viết lại repository/extractor. WBS12 dùng retrieval này; WBS16 chỉ full-load sau 09.5 đạt.														**

🟢 **	Sprint 4	S4-WBS11	S4-G05	2	Nối nhánh Vector RAG vào Hybrid Router	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	1. Bọc vector/BM25 hiện có thành adapter theo WBS10, không làm lại chunking/embedding.**

🟢 **4. Chạy hồi quy các câu B1 đã hoạt động và bàn giao adapter thật cho WBS13.	VECTOR chạy được nguồn thật, giữ phạm vi/metadata và không làm hỏng B1; có test các ca rỗng/lỗi.	WBS10 và Vector RAG Sprint 3. Không chờ WBS09. Làm sớm đầu tuần 2 để Vũ còn thời gian WBS16.														**

🟢 **	Sprint 4	S4-WBS12	S4-G03	2	Nối nhánh Graph RAG vào Hybrid Router	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chuyển intent/slots của WBS10 sang tham số truy vấn WBS09; không sinh Cypher tùy ý từ câu hỏi.**

🟢 **4. Chuẩn bị adapter bằng fixture từ đầu tuần, nối retrieval thật sau khi WBS09 bàn giao; kiểm tra không lộ quan hệ chờ duyệt.	GRAPH chạy bằng graph thật đúng scope, có nguồn và lỗi rõ; đọc lại nguồn bằng ID không bị gắn nhãn BOTH.	Contract WBS10; WBS09 thật để đóng task. Có thể code adapter bằng fixture trước, không đứng chờ pipeline ghép xong.														**

🟢 **	Sprint 4	S4-WBS13	S4-G04	2	Thực hiện tuyến BOTH và hợp nhất bằng chứng	Nguyễn Minh Quân	Chưa bắt đầu	7		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	1. Nhận routing plan và phần yêu cầu của từng nhánh. Gọi VECTOR/GRAPH; nếu vector cần thực thể từ graph thì thực hiện theo thứ tự phù hợp.**

🟢 **5. Làm điều phối bằng hai adapter fixture trước; nối WBS11/WBS12 thật để nghiệm thu.	BOTH thực sự sử dụng hai nhánh, có bộ evidence chung và trạng thái riêng; không che phần chưa được đáp ứng.	WBS10–12. Có thể bắt đầu bằng fixture ngày 02/11; nghiệm thu sau adapter thật. Bàn giao cho WBS14 và WBS17.1.														**

🟢 **	Sprint 4	S4-WBS14	S4-G06	2	Tạo câu trả lời và citation theo kết quả routing	Nguyễn Minh Quân	Chưa bắt đầu	6		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Đưa bằng chứng của tuyến được chọn vào phần trả lời hiện có; trả đúng các phần yêu cầu, gắn citation với từng nhận định.**

🟢 **5. Giữ cấu hình B1 để so sánh; không tự bật Evidence Gate/verifier B3 thuộc sprint sau.	Câu trả lời/citation truy lại được nguồn, không bịa quan hệ/số liệu hoặc che lỗi nhánh; có test và gói bàn giao.	Evidence contract và WBS11–13. Có thể chuẩn bị formatter/citation bằng fixture trước, nghiệm thu sau tuyến thật.														**

🟢 **	Sprint 4	S4-WBS15	S4-G06	2	Nối Graph Viewer và xem bằng chứng thật	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	1. Tái sử dụng Graph Viewer; nối API theo contract để hiển thị Company, Person, Event và quan hệ.**

🟢 **5. Dùng fixture đầu tuần để dựng/test UI, chuyển sang API thật khi WBS09/WBS12 sẵn sàng.	Graph Viewer dùng dữ liệu thật, mở đúng nguồn của quan hệ; có kiểm tra rỗng/lỗi/responsive và phiên dữ liệu.	Contract/API WBS01 và WBS09; nếu dùng chung adapter chat thì WBS12. Không cần chờ BOTH hoặc phần tạo câu trả lời.														**

🟢 **	Sprint 4	S4-WBS16	S4-G02	2	Chạy toàn bộ News đã chốt và đối chiếu kết quả	Đinh Huỳnh Vũ	Chưa bắt đầu	8		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chuẩn bị batch runner từ danh sách đóng băng WBS01 và interface extractor; có thể dùng fixture từ 02/11.**

🟢 **5. Bàn giao báo cáo full-load, lỗi còn lại và phiên dữ liệu. 8h là công chuẩn bị, theo dõi và đối chiếu, không phải cam kết thời gian máy/LLM hay duyệt thủ công mọi quan hệ.	Toàn bộ News đã chốt có trạng thái, không mất tin lỗi; có báo cáo mẫu/full-load riêng và danh sách lỗi chưa xử lý. Không coi mọi quan hệ trích xuất là đã được chấp nhận.	WBS01–08 và kiểm tra mẫu WBS09.5 đạt. Batch runner làm trước bằng fixture; không cần chờ router/chat/UI. Phụ thuộc hạn mức dịch vụ và quyền chạy dữ liệu thậ...**

🟢 **	Sprint 4	S4-WBS17.1	S4-G07	2	WBS17.1 – Đánh giá retrieval và so sánh B1/B2 (Nhân)	Hồ Phạm Đăng Nhân	Chưa bắt đầu	7		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1. Cùng Huyền chốt bộ câu hỏi/nguồn kỳ vọng cho doanh nghiệp, chức vụ, sự kiện và VECTOR/GRAPH/BOTH.**

🟢 **5. Phần Nhân: test/retrieval benchmark, số đo và phân tích. Huyền WBS17.2 chịu trách nhiệm E2E giao diện/citation, kiểm tra nguồn thủ công và hồi quy.	Có output/trace từng câu, bảng B1/B2 và thời gian phản hồi, phân tích ca sai và giới hạn. Không trùng công với WBS17.2; cần cả hai phần để đóng WBS17.	WBS09 và WBS11–14; nhận báo cáo WBS16 để chốt. Chuẩn bị script/case từ fixture sớm; phối hợp Huyền theo bộ test chung, không nhân đôi giờ.														**

🟢 **	Sprint 4	S4-WBS17.2	S4-G09	2	WBS17.2 – Kiểm thử E2E, citation và hồi quy (Huyền)	Trần Diệu Huyền	Chưa bắt đầu	6		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1. Chuẩn bị test đầu tuần cho chọn route/hỏi lại, câu hỏi trùng tên, nguồn mâu thuẫn, sai thời gian/phiên và quan hệ chưa duyệt.**

🟢 **5. Phần Huyền: E2E/UI, citation, kiểm tra nguồn và hồi quy. Nhân WBS17.1 sở hữu benchmark retrieval/metrics; tổng hợp bàn giao chung sau cả hai phần.	Có receipt E2E/negative/hồi quy và mẫu kiểm tra nguồn; lỗi còn lại có người xử lý/mức ảnh hưởng. Không dùng fixture để tuyên bố graph thật đạt; WBS17 chỉ đóng khi 17.1 và 17.2 đạt.	Chuẩn bị bằng WBS01/fixture ngay đầu tuần; nghiệm thu thật cần WBS09–16 và báo cáo WBS17.1. Không phải đợi Nhân chạy xong mới soạn test.														**

🟢 **					Tổng giờ các task			128	0																			**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	69	51	0.7391304347826086	342	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								**

🟢 **Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	63	0	0	288	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								**

🟢 **Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G01	4	Tạo thực thể graph có định danh chuẩn	Danh mục node và khóa liên kết được duyệt.**

🟢 **Nạp lặp không tạo node trùng; ID sai bị chặn.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	13		Sprint 4 Backlog**

🟢 **Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G02	4	Tạo quan hệ có nguồn chứng minh	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Chưa bắt đầu	52		Sprint 4 Backlog**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G03	4	Truy vấn graph trong giới hạn hai hop	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	19		Sprint 4 Backlog**

🟢 **Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G04	4	Kết hợp bằng chứng vector và graph	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.**

🟢 **Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	15		Sprint 4 Backlog**

🟢 **Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G05	4	Tách nhánh truy vấn và hợp đồng lỗi	Có thời gian và trạng thái riêng của từng nhánh.**

🟢 **Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	4		Sprint 4 Backlog**

🟢 **Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	12		Sprint 4 Backlog**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G07	4	Kiểm tra chất lượng graph và so sánh B1 B2	Danh sách 50 edge truy về được từng locator nguồn.**

🟢 **Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	7		Sprint 4 Backlog**

🟢 **	S4-G08	4	Chốt cấu hình và chuẩn bị B3	Lý do chọn tham số và kết quả thử được lưu lại.**

🟢 **Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.			0	0	Chưa có task	Chưa có task	0		Sprint 4 Backlog**

🟢 **Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G09	4	Tích hợp và nghiệm thu Sprint 4	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.**

🟢 **Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	6		Sprint 4 Backlog**

🟢 **Tổng task	196		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						**

🟢 **Độ hoàn thành	0.49489795918367346		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Nạp lặp không tạo node trùng; ID sai bị chặn.	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Sat Nov 07 2026 07:00:00 GMT+0700 (Indochina Time)	7	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.		0	0	Chưa có task	Chưa có task	Ngày và phân công là kế hoạch đề xuất.**

🟢 **Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	1	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.**

~~								4	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Nov 08 2026 07:00:00 GMT+0700 (Indochina Time)	Chưa bắt đầu	150	0	36 task chi tiết; lịch và phân công đề xuất.~~

~~	S4-WBS01	Chốt loại node và khóa định danh	Tạo thực thể graph có định danh chuẩn	Định nghĩa Company, Document và các loại entity được phép theo SRS; thống nhất ID với PostgreSQL.	Danh mục node và khóa liên kết được duyệt.~~

~~Mỗi entity mẫu có nguồn và corpus version.~~

~~Mỗi entity mẫu có nguồn và corpus version.~~

~~Mỗi entity mẫu có nguồn và corpus version.~~

~~Mỗi entity mẫu có nguồn và corpus version.~~

~~Không tạo hai node cho cùng một công ty đã xác định.~~

~~Không tạo hai node cho cùng một công ty đã xác định.~~

~~Không tạo hai node cho cùng một công ty đã xác định.~~

~~Không tạo hai node cho cùng một công ty đã xác định.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Danh mục node và khóa liên kết được duyệt.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G01	FinMind	4	4		Hồ Phạm Đăng Nhân	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS02	Trích entity từ dữ liệu đã xác minh	Tạo thực thể graph có định danh chuẩn	Lấy công ty, tài liệu và thực thể được phép từ corpus hợp lệ; không lấy dữ liệu bị cách ly.	Danh mục node và khóa liên kết được duyệt.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Mỗi entity mẫu có nguồn và corpus version.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G01	FinMind	4	4		Hồ Phạm Đăng Nhân	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS03	Giải quyết tên trùng và tên viết tắt	Tạo thực thể graph có định danh chuẩn	Ánh xạ alias về một ID; đưa thực thể không rõ danh tính vào danh sách kiểm tra.	Danh mục node và khóa liên kết được duyệt.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Không tạo hai node cho cùng một công ty đã xác định.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G01	FinMind	4	4		Hồ Phạm Đăng Nhân	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS04	Tạo ràng buộc node Neo4j	Tạo thực thể graph có định danh chuẩn	Cài khóa duy nhất và kiểm tra kiểu dữ liệu trước khi nạp node.	Danh mục node và khóa liên kết được duyệt.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Nạp lặp không tạo node trùng; ID sai bị chặn.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G01	FinMind	4	4		Nguyễn Minh Quân	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS05	Chốt loại edge và chiều quan hệ	Tạo quan hệ có nguồn chứng minh	Định nghĩa loại quan hệ, node đầu cuối và điều kiện được tạo. Không thêm quan hệ ngoài danh mục.	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.~~

~~Quan hệ ứng viên có nguồn, vị trí và phiên bản.~~

~~Quan hệ ứng viên có nguồn, vị trí và phiên bản.~~

~~Quan hệ ứng viên có nguồn, vị trí và phiên bản.~~

~~Quan hệ ứng viên có nguồn, vị trí và phiên bản.~~

~~Quan hệ chưa xác minh được cách ly, không ghi vào graph hoạt động.~~

~~Quan hệ chưa xác minh được cách ly, không ghi vào graph hoạt động.~~

~~Quan hệ chưa xác minh được cách ly, không ghi vào graph hoạt động.~~

~~Quan hệ chưa xác minh được cách ly, không ghi vào graph hoạt động.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G02	FinMind	4	4		Đinh Huỳnh Vũ	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS06	Trích quan hệ từ bằng chứng nguồn	Tạo quan hệ có nguồn chứng minh	Ưu tiên quy tắc từ dữ kiện đã kiểm tra; nếu dùng LLM phải giữ nguyên đoạn chứng minh.	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Quan hệ ứng viên có nguồn, vị trí và phiên bản.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G02	FinMind	4	4		Nguyễn Minh Quân	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS07	Kiểm tra quan hệ trước khi ghi graph	Tạo quan hệ có nguồn chứng minh	Kiểm tra entity, loại edge, chiều và đoạn nguồn có thực sự chứng minh quan hệ.	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Quan hệ chưa xác minh được cách ly, không ghi vào graph hoạt động.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G02	FinMind	4	4		Đinh Huỳnh Vũ	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS08	Lưu edge và provenance vào Neo4j	Tạo quan hệ có nguồn chứng minh	Ghi edge đã đạt cùng evidence ID, hash, locator và corpus version; giữ lịch sử thay đổi.	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G02	FinMind	4	4		Thái Quốc Hưng	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS09	Viết truy vấn quan hệ một bước	Truy vấn graph trong giới hạn hai hop	Dùng Cypher có tham số để lấy quan hệ quanh một công ty trong corpus đang dùng.	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.~~

~~Ca thử dày đặc vẫn giữ giới hạn phạm vi và số kết quả.~~

~~Ca thử dày đặc vẫn giữ giới hạn phạm vi và số kết quả.~~

~~Ca thử dày đặc vẫn giữ giới hạn phạm vi và số kết quả.~~

~~Ca thử dày đặc vẫn giữ giới hạn phạm vi và số kết quả.~~

~~Mỗi bước trên path có locator kiểm tra được.~~

~~Mỗi bước trên path có locator kiểm tra được.~~

~~Mỗi bước trên path có locator kiểm tra được.~~

~~Mỗi bước trên path có locator kiểm tra được.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G03	FinMind	4	4		Trần Diệu Huyền	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS10	Viết truy vấn mở rộng hai bước	Truy vấn graph trong giới hạn hai hop	Mở thêm một tầng quan hệ; giới hạn số node và không mở quá hai hop.	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Ca thử dày đặc vẫn giữ giới hạn phạm vi và số kết quả.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G03	FinMind	4	4		Nguyễn Minh Quân	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS11	Trả đường quan hệ kèm từng nguồn	Truy vấn graph trong giới hạn hai hop	Đóng gói path với nguồn của từng edge, không chỉ một URL chung cho cả đường đi.	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mỗi bước trên path có locator kiểm tra được.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G03	FinMind	4	4		Đinh Huỳnh Vũ	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS12	Xử lý graph trống hoặc không sẵn sàng	Truy vấn graph trong giới hạn hai hop	Báo không có quan hệ hợp lệ hoặc lỗi nhánh graph; không tự tạo edge.	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G03	FinMind	4	6		Thái Quốc Hưng	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS13	Định tuyến câu hỏi quan hệ sang graph	Kết hợp bằng chứng vector và graph	Nhận diện câu hỏi quan hệ và xác định nhánh graph bắt buộc hoặc bổ sung theo SRS.	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.~~

~~Điểm so sánh được trên thang đã định, không so trực tiếp hai thang khác nhau.~~

~~Điểm so sánh được trên thang đã định, không so trực tiếp hai thang khác nhau.~~

~~Điểm so sánh được trên thang đã định, không so trực tiếp hai thang khác nhau.~~

~~Điểm so sánh được trên thang đã định, không so trực tiếp hai thang khác nhau.~~

~~Kết quả gộp không mất locator hoặc nhân đôi bằng chứng.~~

~~Kết quả gộp không mất locator hoặc nhân đôi bằng chứng.~~

~~Kết quả gộp không mất locator hoặc nhân đôi bằng chứng.~~

~~Kết quả gộp không mất locator hoặc nhân đôi bằng chứng.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G04	FinMind	4	5		Trần Diệu Huyền	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS14	Đưa điểm tìm kiếm về cùng thang	Kết hợp bằng chứng vector và graph	Chuẩn hóa điểm SQL, vector và graph theo hợp đồng; ghi công thức và cấu hình.	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Điểm so sánh được trên thang đã định, không so trực tiếp hai thang khác nhau.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G04	FinMind	4	3		Nguyễn Minh Quân	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS15	Gộp bằng chứng và loại trùng	Kết hợp bằng chứng vector và graph	Gộp theo evidence ID và nguồn; giữ provenance, không đếm cùng một nguồn nhiều lần.	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Kết quả gộp không mất locator hoặc nhân đôi bằng chứng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G04	FinMind	4	3		Đinh Huỳnh Vũ	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS16	Xếp lại bằng chứng theo liên quan	Kết hợp bằng chứng vector và graph	Áp dụng fusion và reranking với giới hạn context; giữ danh sách trước sau để so sánh.	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G04	FinMind	4	3		Hồ Phạm Đăng Nhân	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS17	Cho vector graph chạy độc lập	Tách nhánh truy vấn và hợp đồng lỗi	Chạy các nhánh theo routing plan với timeout và trace riêng.	Có thời gian và trạng thái riêng của từng nhánh.~~

~~Gói kết quả nói rõ nhánh lỗi và không tự kết luận đủ bằng chứng.~~

~~Gói kết quả nói rõ nhánh lỗi và không tự kết luận đủ bằng chứng.~~

~~Gói kết quả nói rõ nhánh lỗi và không tự kết luận đủ bằng chứng.~~

~~Gói kết quả nói rõ nhánh lỗi và không tự kết luận đủ bằng chứng.~~

~~Mỗi lỗi có mã và thông báo dễ hiểu.~~

~~Mỗi lỗi có mã và thông báo dễ hiểu.~~

~~Mỗi lỗi có mã và thông báo dễ hiểu.~~

~~Mỗi lỗi có mã và thông báo dễ hiểu.~~

~~Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Có thời gian và trạng thái riêng của từng nhánh.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G05	FinMind	4	4		Thái Quốc Hưng	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS18	Giữ bằng chứng của nhánh còn hoạt động	Tách nhánh truy vấn và hợp đồng lỗi	Nếu một nhánh lỗi, giữ kết quả hợp lệ của nhánh khác; đánh dấu phần phủ còn thiếu.	Có thời gian và trạng thái riêng của từng nhánh.~~

~~Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Gói kết quả nói rõ nhánh lỗi và không tự kết luận đủ bằng chứng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G05	FinMind	4	5		Thái Quốc Hưng	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS19	Chuẩn hóa mã lỗi truy vấn	Tách nhánh truy vấn và hợp đồng lỗi	Tách thiếu dữ liệu, timeout, không có quan hệ và nguồn sai phiên bản.	Có thời gian và trạng thái riêng của từng nhánh.~~

~~Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Mỗi lỗi có mã và thông báo dễ hiểu.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G05	FinMind	4	4		Nguyễn Minh Quân	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS20	Tạo hợp đồng đầu vào Evidence Gate	Tách nhánh truy vấn và hợp đồng lỗi	Bổ sung coverage, freshness và consistency vào gói bằng chứng cho B3 ở Sprint 5.	Có thời gian và trạng thái riêng của từng nhánh.~~

~~Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G05	FinMind	4	4		Đinh Huỳnh Vũ	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS21	Cấu hình B2 cùng cơ chế B1	Xây cấu hình hybrid B2	Thêm graph và fusion vào B1, giữ cùng generator, prompt và citation binding; không bật Gate hoặc verifier B3.	Manifest thể hiện khác biệt B1 B2 đúng phần thử nghiệm graph.~~

~~Nháp B2 giữ nguồn cho nhận định quan hệ.~~

~~Nháp B2 giữ nguồn cho nhận định quan hệ.~~

~~Nháp B2 giữ nguồn cho nhận định quan hệ.~~

~~Nháp B2 giữ nguồn cho nhận định quan hệ.~~

~~B1 B2 so sánh được trên cùng điều kiện chạy.~~

~~B1 B2 so sánh được trên cùng điều kiện chạy.~~

~~B1 B2 so sánh được trên cùng điều kiện chạy.~~

~~B1 B2 so sánh được trên cùng điều kiện chạy.~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Manifest thể hiện khác biệt B1 B2 đúng phần thử nghiệm graph.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	4		Hồ Phạm Đăng Nhân	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS22	Nối graph vào luồng sinh câu trả lời	Xây cấu hình hybrid B2	Đưa bằng chứng quan hệ đã xác minh vào context có giới hạn và ID nguồn.	Manifest thể hiện khác biệt B1 B2 đúng phần thử nghiệm graph.~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Nháp B2 giữ nguồn cho nhận định quan hệ.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	4		Nguyễn Minh Quân	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS23	Chạy B2 trên 40 ca hiệu chỉnh	Xây cấu hình hybrid B2	Dùng cùng corpus và bộ ca B1; ghi đầu ra, nguồn, thời gian và token từng câu.	Manifest thể hiện khác biệt B1 B2 đúng phần thử nghiệm graph.~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	B1 B2 so sánh được trên cùng điều kiện chạy.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	4		Đinh Huỳnh Vũ	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS24	Phân tích câu graph giúp hoặc gây lỗi	Xây cấu hình hybrid B2	Đối chiếu từng ca quan hệ và đa bước với B1; ghi rõ ví dụ tiến bộ hoặc suy giảm.	Manifest thể hiện khác biệt B1 B2 đúng phần thử nghiệm graph.~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G06	FinMind	4	4		Hồ Phạm Đăng Nhân	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS25	Chọn mẫu 50 edge để kiểm tra nguồn	Kiểm tra chất lượng graph và so sánh B1 B2	Lấy mẫu có loại quan hệ và công ty rõ ràng; ghi phương pháp chọn mẫu và ID.	Danh sách 50 edge truy về được từng locator nguồn.~~

~~Có báo cáo precision của mẫu và danh sách edge cần loại hoặc sửa.~~

~~Có báo cáo precision của mẫu và danh sách edge cần loại hoặc sửa.~~

~~Có báo cáo precision của mẫu và danh sách edge cần loại hoặc sửa.~~

~~Có báo cáo precision của mẫu và danh sách edge cần loại hoặc sửa.~~

~~Bảng so sánh truy về được kết quả từng câu.~~

~~Bảng so sánh truy về được kết quả từng câu.~~

~~Bảng so sánh truy về được kết quả từng câu.~~

~~Bảng so sánh truy về được kết quả từng câu.~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Danh sách 50 edge truy về được từng locator nguồn.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G07	FinMind	4	4		Trần Diệu Huyền	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS26	Đánh giá thủ công độ đúng của edge	Kiểm tra chất lượng graph và so sánh B1 B2	Đọc nguồn từng edge, ghi đúng sai và lý do; nhờ người thứ hai xử lý trường hợp bất đồng.	Danh sách 50 edge truy về được từng locator nguồn.~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Có báo cáo precision của mẫu và danh sách edge cần loại hoặc sửa.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G07	FinMind	4	6		Trần Diệu Huyền	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS27	So sánh chất lượng B1 với B2	Kiểm tra chất lượng graph và so sánh B1 B2	Tính các chỉ số và phân tích theo loại câu hỏi; dùng cùng phép đo và bộ hiệu chỉnh.	Danh sách 50 edge truy về được từng locator nguồn.~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Bảng so sánh truy về được kết quả từng câu.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G07	FinMind	4	4		Nguyễn Minh Quân	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS28	Đo chi phí và thời gian nhánh graph	Kiểm tra chất lượng graph và so sánh B1 B2	So thời gian, token và lỗi với B1; nêu phần tăng thêm do graph và fusion.	Danh sách 50 edge truy về được từng locator nguồn.~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G07	FinMind	4	5		Đinh Huỳnh Vũ	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS29	Hiệu chỉnh trọng số fusion	Chốt cấu hình và chuẩn bị B3	Thử trọng số trên bộ 40 ca; chọn cấu hình dựa trên chất lượng và chi phí.	Lý do chọn tham số và kết quả thử được lưu lại.~~

~~Ngưỡng có phiên bản, không dựa vào nhãn 80 ca cuối.~~

~~Ngưỡng có phiên bản, không dựa vào nhãn 80 ca cuối.~~

~~Ngưỡng có phiên bản, không dựa vào nhãn 80 ca cuối.~~

~~Ngưỡng có phiên bản, không dựa vào nhãn 80 ca cuối.~~

~~Có thể phục dựng đúng phiên bản đã chốt.~~

~~Có thể phục dựng đúng phiên bản đã chốt.~~

~~Có thể phục dựng đúng phiên bản đã chốt.~~

~~Có thể phục dựng đúng phiên bản đã chốt.~~

~~Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Lý do chọn tham số và kết quả thử được lưu lại.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G08	FinMind	4	5		Hồ Phạm Đăng Nhân	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS30	Chốt ngưỡng đầu vào cho Gate	Chốt cấu hình và chuẩn bị B3	Hiệu chỉnh relevance và freshness theo corpus freeze; thống nhất quy tắc coverage theo dạng câu hỏi.	Lý do chọn tham số và kết quả thử được lưu lại.~~

~~Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Ngưỡng có phiên bản, không dựa vào nhãn 80 ca cuối.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G08	FinMind	4	3		Nguyễn Minh Quân	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS31	Đóng băng cấu hình graph hợp lệ	Chốt cấu hình và chuẩn bị B3	Lưu manifest node edge, embedding, prompt và code commit cho bản chuẩn bị tích hợp B3.	Lý do chọn tham số và kết quả thử được lưu lại.~~

~~Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Có thể phục dựng đúng phiên bản đã chốt.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G08	FinMind	4	2		Đinh Huỳnh Vũ	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS32	Bàn giao gói bằng chứng cho B3	Chốt cấu hình và chuẩn bị B3	Kiểm tra API và schema giữa retrieval, citation và verifier; ghi các chỗ chưa đạt.	Lý do chọn tham số và kết quả thử được lưu lại.~~

~~Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G08	FinMind	4	2		Hồ Phạm Đăng Nhân	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS33	Kiểm thử node edge và truy vấn hai hop	Tích hợp và nghiệm thu Sprint 4	Chạy các ca ID trùng, edge sai nguồn, graph trống và vượt hai hop.	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.~~

~~Các lỗi được đóng có chứng cứ kiểm tra lại.~~

~~Các lỗi được đóng có chứng cứ kiểm tra lại.~~

~~Các lỗi được đóng có chứng cứ kiểm tra lại.~~

~~Các lỗi được đóng có chứng cứ kiểm tra lại.~~

~~Không bịa bằng chứng và không che mất lỗi nhánh.~~

~~Không bịa bằng chứng và không che mất lỗi nhánh.~~

~~Không bịa bằng chứng và không che mất lỗi nhánh.~~

~~Không bịa bằng chứng và không che mất lỗi nhánh.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G09	FinMind	4	5		Thái Quốc Hưng	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS34	Sửa lỗi graph và fusion tuần 1	Tích hợp và nghiệm thu Sprint 4	Sửa lỗi entity, locator và điểm hợp nhất đã ghi nhận, chạy lại bộ mẫu.	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Các lỗi được đóng có chứng cứ kiểm tra lại.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G09	FinMind	4	6		Trần Diệu Huyền	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	1~~

~~	S4-WBS35	Kiểm thử B2 khi một nhánh lỗi	Tích hợp và nghiệm thu Sprint 4	Mô phỏng graph hoặc vector timeout; kiểm tra trace và phần bằng chứng còn lại.	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Không bịa bằng chứng và không che mất lỗi nhánh.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G09	FinMind	4	5		Trần Diệu Huyền	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	S4-WBS36	Review benchmark và bản bàn giao	Tích hợp và nghiệm thu Sprint 4	Rà soát 50 edge, kết quả B1 B2, manifest và cấu hình chuẩn bị B3.	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Proposal đã sửa, mục 11 Timeline; SRS và phản hồi F01–F16.	Cao	Chưa bắt đầu	S4-G09	FinMind	4	6		Thái Quốc Hưng	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	2~~

~~	Sửa trạng thái, phụ trách và ngày tại sheet sprint. Product Backlog, tháng và 3 tháng tự cập nhật.																											~~

~~	Ngày, giờ và phân công là đề xuất. Tuần 1 và 2 tính từ thứ Hai bắt đầu sprint; chỉ làm khi đầu vào đã sẵn sàng.																											~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi																							~~

~~	Sprint 4	S4-WBS01	S4-G01	1	Chốt loại node và khóa định danh	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa Company, Document và các loại entity được phép theo SRS; thống nhất ID với PostgreSQL.	Danh mục node và khóa liên kết được duyệt.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 4	S4-WBS02	S4-G01	1	Trích entity từ dữ liệu đã xác minh	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy công ty, tài liệu và thực thể được phép từ corpus hợp lệ; không lấy dữ liệu bị cách ly.	Mỗi entity mẫu có nguồn và corpus version.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 4	S4-WBS03	S4-G01	1	Giải quyết tên trùng và tên viết tắt	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Ánh xạ alias về một ID; đưa thực thể không rõ danh tính vào danh sách kiểm tra.	Không tạo hai node cho cùng một công ty đã xác định.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 4	S4-WBS04	S4-G01	1	Tạo ràng buộc node Neo4j	Nguyễn Minh Quân	Chưa bắt đầu	4		Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Cài khóa duy nhất và kiểm tra kiểu dữ liệu trước khi nạp node.	Nạp lặp không tạo node trùng; ID sai bị chặn.	Phiên bản bàn giao của sprint trước đã được duyệt.														~~

~~	Sprint 4	S4-WBS05	S4-G02	1	Chốt loại edge và chiều quan hệ	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Định nghĩa loại quan hệ, node đầu cuối và điều kiện được tạo. Không thêm quan hệ ngoài danh mục.	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.	Kiểm tra đầu ra liên quan của S4-G01 trước khi làm.														~~

~~	Sprint 4	S4-WBS06	S4-G02	1	Trích quan hệ từ bằng chứng nguồn	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Ưu tiên quy tắc từ dữ kiện đã kiểm tra; nếu dùng LLM phải giữ nguyên đoạn chứng minh.	Quan hệ ứng viên có nguồn, vị trí và phiên bản.	Kiểm tra đầu ra liên quan của S4-G01 trước khi làm.														~~

~~	Sprint 4	S4-WBS07	S4-G02	1	Kiểm tra quan hệ trước khi ghi graph	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra entity, loại edge, chiều và đoạn nguồn có thực sự chứng minh quan hệ.	Quan hệ chưa xác minh được cách ly, không ghi vào graph hoạt động.	Kiểm tra đầu ra liên quan của S4-G01 trước khi làm.														~~

~~	Sprint 4	S4-WBS08	S4-G02	1	Lưu edge và provenance vào Neo4j	Thái Quốc Hưng	Chưa bắt đầu	4		Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Ghi edge đã đạt cùng evidence ID, hash, locator và corpus version; giữ lịch sử thay đổi.	Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Kiểm tra đầu ra liên quan của S4-G01 trước khi làm.														~~

~~	Sprint 4	S4-WBS09	S4-G03	1	Viết truy vấn quan hệ một bước	Trần Diệu Huyền	Chưa bắt đầu	4		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng Cypher có tham số để lấy quan hệ quanh một công ty trong corpus đang dùng.	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.	Kiểm tra đầu ra liên quan của S4-G02 trước khi làm.														~~

~~	Sprint 4	S4-WBS10	S4-G03	1	Viết truy vấn mở rộng hai bước	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Mở thêm một tầng quan hệ; giới hạn số node và không mở quá hai hop.	Ca thử dày đặc vẫn giữ giới hạn phạm vi và số kết quả.	Kiểm tra đầu ra liên quan của S4-G02 trước khi làm.														~~

~~	Sprint 4	S4-WBS11	S4-G03	1	Trả đường quan hệ kèm từng nguồn	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Đóng gói path với nguồn của từng edge, không chỉ một URL chung cho cả đường đi.	Mỗi bước trên path có locator kiểm tra được.	Kiểm tra đầu ra liên quan của S4-G02 trước khi làm.														~~

~~	Sprint 4	S4-WBS12	S4-G03	1	Xử lý graph trống hoặc không sẵn sàng	Thái Quốc Hưng	Chưa bắt đầu	6		Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Báo không có quan hệ hợp lệ hoặc lỗi nhánh graph; không tự tạo edge.	Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Kiểm tra đầu ra liên quan của S4-G02 trước khi làm.														~~

~~	Sprint 4	S4-WBS13	S4-G04	1	Định tuyến câu hỏi quan hệ sang graph	Trần Diệu Huyền	Chưa bắt đầu	5		Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Nhận diện câu hỏi quan hệ và xác định nhánh graph bắt buộc hoặc bổ sung theo SRS.	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.	Kiểm tra đầu ra liên quan của S4-G03 trước khi làm.														~~

~~	Sprint 4	S4-WBS14	S4-G04	1	Đưa điểm tìm kiếm về cùng thang	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Oct 27 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Chuẩn hóa điểm SQL, vector và graph theo hợp đồng; ghi công thức và cấu hình.	Điểm so sánh được trên thang đã định, không so trực tiếp hai thang khác nhau.	Kiểm tra đầu ra liên quan của S4-G03 trước khi làm.														~~

~~	Sprint 4	S4-WBS15	S4-G04	1	Gộp bằng chứng và loại trùng	Đinh Huỳnh Vũ	Chưa bắt đầu	3		Wed Oct 28 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Gộp theo evidence ID và nguồn; giữ provenance, không đếm cùng một nguồn nhiều lần.	Kết quả gộp không mất locator hoặc nhân đôi bằng chứng.	Kiểm tra đầu ra liên quan của S4-G03 trước khi làm.														~~

~~	Sprint 4	S4-WBS16	S4-G04	1	Xếp lại bằng chứng theo liên quan	Hồ Phạm Đăng Nhân	Chưa bắt đầu	3		Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Áp dụng fusion và reranking với giới hạn context; giữ danh sách trước sau để so sánh.	Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Kiểm tra đầu ra liên quan của S4-G03 trước khi làm.														~~

~~	Sprint 4	S4-WBS17	S4-G05	2	Cho vector graph chạy độc lập	Thái Quốc Hưng	Chưa bắt đầu	4		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy các nhánh theo routing plan với timeout và trace riêng.	Có thời gian và trạng thái riêng của từng nhánh.	Kiểm tra đầu ra liên quan của S4-G04 trước khi làm.														~~

~~	Sprint 4	S4-WBS18	S4-G05	2	Giữ bằng chứng của nhánh còn hoạt động	Thái Quốc Hưng	Chưa bắt đầu	5		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Nếu một nhánh lỗi, giữ kết quả hợp lệ của nhánh khác; đánh dấu phần phủ còn thiếu.	Gói kết quả nói rõ nhánh lỗi và không tự kết luận đủ bằng chứng.	Kiểm tra đầu ra liên quan của S4-G04 trước khi làm.														~~

~~	Sprint 4	S4-WBS19	S4-G05	2	Chuẩn hóa mã lỗi truy vấn	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Tách thiếu dữ liệu, timeout, không có quan hệ và nguồn sai phiên bản.	Mỗi lỗi có mã và thông báo dễ hiểu.	Kiểm tra đầu ra liên quan của S4-G04 trước khi làm.														~~

~~	Sprint 4	S4-WBS20	S4-G05	2	Tạo hợp đồng đầu vào Evidence Gate	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	Bổ sung coverage, freshness và consistency vào gói bằng chứng cho B3 ở Sprint 5.	Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Kiểm tra đầu ra liên quan của S4-G04 trước khi làm.														~~

~~	Sprint 4	S4-WBS21	S4-G06	2	Cấu hình B2 cùng cơ chế B1	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Thêm graph và fusion vào B1, giữ cùng generator, prompt và citation binding; không bật Gate hoặc verifier B3.	Manifest thể hiện khác biệt B1 B2 đúng phần thử nghiệm graph.	Kiểm tra đầu ra liên quan của S4-G05 trước khi làm.														~~

~~	Sprint 4	S4-WBS22	S4-G06	2	Nối graph vào luồng sinh câu trả lời	Nguyễn Minh Quân	Chưa bắt đầu	4		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Đưa bằng chứng quan hệ đã xác minh vào context có giới hạn và ID nguồn.	Nháp B2 giữ nguồn cho nhận định quan hệ.	Kiểm tra đầu ra liên quan của S4-G05 trước khi làm.														~~

~~	Sprint 4	S4-WBS23	S4-G06	2	Chạy B2 trên 40 ca hiệu chỉnh	Đinh Huỳnh Vũ	Chưa bắt đầu	4		Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Dùng cùng corpus và bộ ca B1; ghi đầu ra, nguồn, thời gian và token từng câu.	B1 B2 so sánh được trên cùng điều kiện chạy.	Kiểm tra đầu ra liên quan của S4-G05 trước khi làm.														~~

~~	Sprint 4	S4-WBS24	S4-G06	2	Phân tích câu graph giúp hoặc gây lỗi	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	Đối chiếu từng ca quan hệ và đa bước với B1; ghi rõ ví dụ tiến bộ hoặc suy giảm.	Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Kiểm tra đầu ra liên quan của S4-G05 trước khi làm.														~~

~~	Sprint 4	S4-WBS25	S4-G07	2	Chọn mẫu 50 edge để kiểm tra nguồn	Trần Diệu Huyền	Chưa bắt đầu	4		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Lấy mẫu có loại quan hệ và công ty rõ ràng; ghi phương pháp chọn mẫu và ID.	Danh sách 50 edge truy về được từng locator nguồn.	Kiểm tra đầu ra liên quan của S4-G06 trước khi làm.														~~

~~	Sprint 4	S4-WBS26	S4-G07	2	Đánh giá thủ công độ đúng của edge	Trần Diệu Huyền	Chưa bắt đầu	6		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Đọc nguồn từng edge, ghi đúng sai và lý do; nhờ người thứ hai xử lý trường hợp bất đồng.	Có báo cáo precision của mẫu và danh sách edge cần loại hoặc sửa.	Kiểm tra đầu ra liên quan của S4-G06 trước khi làm.														~~

~~	Sprint 4	S4-WBS27	S4-G07	2	So sánh chất lượng B1 với B2	Nguyễn Minh Quân	Chưa bắt đầu	4		Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Tính các chỉ số và phân tích theo loại câu hỏi; dùng cùng phép đo và bộ hiệu chỉnh.	Bảng so sánh truy về được kết quả từng câu.	Kiểm tra đầu ra liên quan của S4-G06 trước khi làm.														~~

~~	Sprint 4	S4-WBS28	S4-G07	2	Đo chi phí và thời gian nhánh graph	Đinh Huỳnh Vũ	Chưa bắt đầu	5		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	So thời gian, token và lỗi với B1; nêu phần tăng thêm do graph và fusion.	Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Kiểm tra đầu ra liên quan của S4-G06 trước khi làm.														~~

~~	Sprint 4	S4-WBS29	S4-G08	2	Hiệu chỉnh trọng số fusion	Hồ Phạm Đăng Nhân	Chưa bắt đầu	5		Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Thử trọng số trên bộ 40 ca; chọn cấu hình dựa trên chất lượng và chi phí.	Lý do chọn tham số và kết quả thử được lưu lại.	Kiểm tra đầu ra liên quan của S4-G07 trước khi làm.														~~

~~	Sprint 4	S4-WBS30	S4-G08	2	Chốt ngưỡng đầu vào cho Gate	Nguyễn Minh Quân	Chưa bắt đầu	3		Tue Nov 03 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Hiệu chỉnh relevance và freshness theo corpus freeze; thống nhất quy tắc coverage theo dạng câu hỏi.	Ngưỡng có phiên bản, không dựa vào nhãn 80 ca cuối.	Kiểm tra đầu ra liên quan của S4-G07 trước khi làm.														~~

~~	Sprint 4	S4-WBS31	S4-G08	2	Đóng băng cấu hình graph hợp lệ	Đinh Huỳnh Vũ	Chưa bắt đầu	2		Wed Nov 04 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Lưu manifest node edge, embedding, prompt và code commit cho bản chuẩn bị tích hợp B3.	Có thể phục dựng đúng phiên bản đã chốt.	Kiểm tra đầu ra liên quan của S4-G07 trước khi làm.														~~

~~	Sprint 4	S4-WBS32	S4-G08	2	Bàn giao gói bằng chứng cho B3	Hồ Phạm Đăng Nhân	Chưa bắt đầu	2		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	Kiểm tra API và schema giữa retrieval, citation và verifier; ghi các chỗ chưa đạt.	Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Kiểm tra đầu ra liên quan của S4-G07 trước khi làm.														~~

~~	Sprint 4	S4-WBS33	S4-G09	1	Kiểm thử node edge và truy vấn hai hop	Thái Quốc Hưng	Chưa bắt đầu	5		Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Chạy các ca ID trùng, edge sai nguồn, graph trống và vượt hai hop.	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 4	S4-WBS34	S4-G09	1	Sửa lỗi graph và fusion tuần 1	Trần Diệu Huyền	Chưa bắt đầu	6		Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	Sửa lỗi entity, locator và điểm hợp nhất đã ghi nhận, chạy lại bộ mẫu.	Các lỗi được đóng có chứng cứ kiểm tra lại.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 4	S4-WBS35	S4-G09	2	Kiểm thử B2 khi một nhánh lỗi	Trần Diệu Huyền	Chưa bắt đầu	5		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	Mô phỏng graph hoặc vector timeout; kiểm tra trace và phần bằng chứng còn lại.	Không bịa bằng chứng và không che mất lỗi nhánh.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~	Sprint 4	S4-WBS36	S4-G09	2	Review benchmark và bản bàn giao	Thái Quốc Hưng	Chưa bắt đầu	6		Thu Nov 05 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	Rà soát 50 edge, kết quả B1 B2, manifest và cấu hình chuẩn bị B3.	Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Các task chức năng liên quan có đầu ra để kiểm tra.														~~

~~					Tổng giờ các task			150	0																			~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	78	51	0.6538461538461539	352	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								~~

~~Sun Nov 01 2026 07:00:00 GMT+0700 (Indochina Time)	72	0	0	300	Hybrid B2, Copilot B3, kiểm chứng, bảo mật và chạy đánh giá cuối.								~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G01	4	Tạo thực thể graph có định danh chuẩn	Danh mục node và khóa liên kết được duyệt.~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	16		Sprint 4 Backlog~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G02	4	Tạo quan hệ có nguồn chứng minh	Có bảng loại edge và ví dụ hợp lệ, không hợp lệ.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	16		Sprint 4 Backlog~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G03	4	Truy vấn graph trong giới hạn hai hop	Trả node và edge hợp lệ, không cho ghép chuỗi Cypher tùy ý.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	18		Sprint 4 Backlog~~

~~Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G04	4	Kết hợp bằng chứng vector và graph	Các mẫu câu hỏi đi đúng nhánh và ghi routing plan.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Mon Oct 26 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	14		Sprint 4 Backlog~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G05	4	Tách nhánh truy vấn và hợp đồng lỗi	Có thời gian và trạng thái riêng của từng nhánh.~~

~~Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	17		Sprint 4 Backlog~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	16		Sprint 4 Backlog~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G07	4	Kiểm tra chất lượng graph và so sánh B1 B2	Danh sách 50 edge truy về được từng locator nguồn.~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	19		Sprint 4 Backlog~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G08	4	Chốt cấu hình và chuẩn bị B3	Lý do chọn tham số và kết quả thử được lưu lại.~~

~~Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Mon Nov 02 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	12		Sprint 4 Backlog~~

~~Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	S4-G09	4	Tích hợp và nghiệm thu Sprint 4	Graph chỉ chứa và trả quan hệ đã xác minh trong phạm vi.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Thu Oct 29 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	22		Sprint 4 Backlog~~

~~Tổng task	214		Bàn giao dự kiến	Sun Dec 06 2026 07:00:00 GMT+0700 (Indochina Time)						~~

~~Độ hoàn thành	0.4532710280373832		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Nạp lặp không tạo node trùng; ID sai bị chặn.	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Chọn một edge truy ra được nguồn gốc và phiên bản của nó.	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Nhánh graph lỗi không làm mất nhật ký hoặc giả lập kết quả.	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Bằng chứng đứng đầu có điểm và lý do lựa chọn kiểm tra được.	Fri Oct 30 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Schema đủ trường Gate cần dùng; chưa bật Gate cho benchmark B2.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Có danh sách ca và bằng chứng, không chỉ báo một điểm trung bình.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Có số đo thực tế; không dùng mục tiêu hiệu năng làm kết quả đo.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Sprint 5 có hợp đồng và dữ liệu đầu vào rõ ràng.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Ngày và phân công là kế hoạch đề xuất.~~

~~Nhóm duyệt đầu ra hoặc ghi rõ điều kiện chưa đạt.	Fri Nov 06 2026 07:00:00 GMT+0700 (Indochina Time)	4	0	0	Chưa bắt đầu	Khoảng 22 giờ cho tích hợp, review và sửa lỗi.~~

## 2026-10-25 20:52 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-25 20:52

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-23 11:02 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-23 11:02

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

_Không có nội dung để so sánh_

## 2026-10-23 10:57 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-23 10:57

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S3-WBS20	Tạo chỉ mục pgvector và đo baseline	Embedding và pgvector	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Có kết quả baseline, index và truy vấn trả chunk đúng corpus.	Kế hoạch Sprint 3 đã chốt the...**

🟢 **	S3-WBS25	Truy vấn vector có lọc phạm vi	Embedding và pgvector	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Ca lọc sai công ty/kỳ/corpus trả rỗng hoặc đúng phạm vi; contract cho Hưng dùng.	Kế hoạch Sprint 3...**

🟢 **	S3-WBS30	Ghi timing và lỗi retrieval	Embedding và pgvector	Bước 1: Với mỗi lần tìm kiếm vector, ghi thời gian chạy, số đoạn tìm được, điểm của các đoạn và mã lỗi nếu có. Bước 2: Che thông tin nhạy cảm trong lỗi/log. Bước 3: Chạy câu hỏi thành công và câu hỏi lỗi để chắc người kiểm tra có đủ dấu vết tìm nguyên nhân chậm hoặc sai.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Một truy vấn có trace thật đủ phân tích chậm/lỗi; không lộ secret.	Kế hoạch Sprint 3 đã chốt theo 4 người vector...**

🟢 **	Sprint 3	S3-WBS20	S3-G02	2	Tạo chỉ mục pgvector và đo baseline	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Có kết quả bas...**

🟢 **	Sprint 3	S3-WBS25	S3-G02	2	Truy vấn vector có lọc phạm vi	Hồ Phạm Đăng Nhân	Đã hoàn thành	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Ca lọc sai công ty/kỳ...**

🟢 **	Sprint 3	S3-WBS30	S3-G02	2	Ghi timing và lỗi retrieval	Hồ Phạm Đăng Nhân	Đang test	3		Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Với mỗi lần tìm kiếm vector, ghi thời gian chạy, số đoạn tìm được, điểm của các đoạn và mã lỗi nếu có. Bước 2: Che thông tin nhạy cảm trong lỗi/log. Bước 3: Chạy câu hỏi thành công và câu hỏi lỗi để chắc người kiểm tra có đủ dấu vết tìm nguyên nhân chậm hoặc sai.	Một truy vấn có trace thật đủ phân tích...**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	78	51	0.6538461538461539	352	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								**

🟢 **Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	6	0.75	Đang test	30		Sprint 3 Backlog**

🟢 **Task đã hoàn thành	97		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.4532710280373832		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	6	0.75	Đang test	Ngày và phân công là kế hoạch đề xuất.**

~~	S3-WBS20	Tạo chỉ mục pgvector và đo baseline	Embedding và pgvector	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Có kết quả baseline, index và truy vấn trả chunk đúng corpus.	Kế hoạch Sprint 3 đã chốt the...~~

~~	S3-WBS25	Truy vấn vector có lọc phạm vi	Embedding và pgvector	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Ca lọc sai công ty/kỳ/corpus trả rỗng hoặc đúng phạm vi; contract cho Hưng dùng.	Kế hoạch Sprint 3...~~

~~	S3-WBS30	Ghi timing và lỗi retrieval	Embedding và pgvector	Bước 1: Với mỗi lần tìm kiếm vector, ghi thời gian chạy, số đoạn tìm được, điểm của các đoạn và mã lỗi nếu có. Bước 2: Che thông tin nhạy cảm trong lỗi/log. Bước 3: Chạy câu hỏi thành công và câu hỏi lỗi để chắc người kiểm tra có đủ dấu vết tìm nguyên nhân chậm hoặc sai.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Một truy vấn có trace thật đủ phân tích chậm/lỗi; không lộ secret.	Kế hoạch Sprint 3 đã chốt theo 4 người vector...~~

~~	Sprint 3	S3-WBS20	S3-G02	2	Tạo chỉ mục pgvector và đo baseline	Hồ Phạm Đăng Nhân	Đang test	4		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Có kết quả baselin...~~

~~	Sprint 3	S3-WBS25	S3-G02	2	Truy vấn vector có lọc phạm vi	Hồ Phạm Đăng Nhân	Đang test	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Ca lọc sai công ty/kỳ/cor...~~

~~	Sprint 3	S3-WBS30	S3-G02	2	Ghi timing và lỗi retrieval	Hồ Phạm Đăng Nhân	Chưa bắt đầu	3		Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Với mỗi lần tìm kiếm vector, ghi thời gian chạy, số đoạn tìm được, điểm của các đoạn và mã lỗi nếu có. Bước 2: Che thông tin nhạy cảm trong lỗi/log. Bước 3: Chạy câu hỏi thành công và câu hỏi lỗi để chắc người kiểm tra có đủ dấu vết tìm nguyên nhân chậm hoặc sai.	Một truy vấn có trace thật đủ phân t...~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	78	49	0.6282051282051282	352	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								~~

~~Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	4	0.5	Đang test	30		Sprint 3 Backlog~~

~~Task đã hoàn thành	95		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.4439252336448598		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	4	0.5	Đang test	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-23 10:07 - SUA NOI DUNG

- **Người đăng:** minhquan9125@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-23 10:07

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **								3	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	150	28	36 task chi tiết; lịch và phân công đề xuất.**

🟢 **	S3-WBS28	Hoàn thiện session logout refresh	Tài khoản và phân quyền	Bước 1: Cho người dùng đăng xuất và làm phiên đăng nhập hết hiệu lực theo cách đã chọn. Bước 2: Xử lý trường hợp phiên hết hạn: thử làm mới an toàn nếu được phép, nếu không thì đưa về trang đăng nhập. Bước 3: Thử mã phiên sai, hết hạn và đã đăng xuất để chắc không truy cập tiếp được.	Các chức năng tài khoản thiết yếu hoạt động với kiểm soát quyền và kiểm thử an toàn.	Logout thu hồi phiên; refresh sai/hết hạn bị từ chối, UI trở v...**

🟢 **	S3-WBS33	Bảo vệ API theo vai trò	Tài khoản và phân quyền	Bước 1: Liệt kê API tài khoản, nguồn dữ liệu, corpus, truy vấn và đánh giá nằm trong phạm vi Sprint 3, cùng vai trò được phép dùng từng API. Bước 2: Kiểm tra quyền ở máy chủ, không chỉ ẩn nút trên giao diện. Bước 3: Thử tài khoản thiếu quyền gọi trực tiếp từng API và xác nhận bị từ chối.	Các chức năng tài khoản thiết yếu hoạt động với kiểm soát quyền và kiểm thử an toàn.	Sai vai trò bị từ chối server-side ở API trong phạm vi và có test.	K...**

🟢 **	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	28																						**

🟢 **	Sprint 3	S3-WBS28	S3-G08	2	Hoàn thiện session logout refresh	Nguyễn Minh Quân	Đã hoàn thành	4	3	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cho người dùng đăng xuất và làm phiên đăng nhập hết hiệu lực theo cách đã chọn. Bước 2: Xử lý trường hợp phiên hết hạn: thử làm mới an toàn nếu được phép, nếu không thì đưa về trang đăng nhập. Bước 3: Thử mã phiên sai, hết hạn và đã đăng xuất để chắc không truy cập tiếp được.	Logout thu hồi p...**

🟢 **	Sprint 3	S3-WBS33	S3-G08	2	Bảo vệ API theo vai trò	Nguyễn Minh Quân	Đã hoàn thành	3	3	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Liệt kê API tài khoản, nguồn dữ liệu, corpus, truy vấn và đánh giá nằm trong phạm vi Sprint 3, cùng vai trò được phép dùng từng API. Bước 2: Kiểm tra quyền ở máy chủ, không chỉ ẩn nút trên giao diện. Bước 3: Thử tài khoản thiếu quyền gọi trực tiếp từng API và xác nhận bị từ chối.	Sai vai trò bị từ chối...**

🟢 **					Tổng giờ các task			150	28																			**

🟢 **Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	78	49	0.6282051282051282	352	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								**

🟢 **API vận hành hiển thị dữ liệu thật và không lộ bí mật.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	7	6	0.8571428571428571	Đang làm	30	21	Sprint 3 Backlog**

🟢 **Task đã hoàn thành	95		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						**

🟢 **Độ hoàn thành	0.4439252336448598		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						**

🟢 **API vận hành hiển thị dữ liệu thật và không lộ bí mật.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	7	6	0.8571428571428571	Đang làm	Ngày và phân công là kế hoạch đề xuất.**

~~								3	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Sun Oct 25 2026 07:00:00 GMT+0700 (Indochina Time)	Đang thực hiện	150	22	36 task chi tiết; lịch và phân công đề xuất.~~

~~	S3-WBS28	Hoàn thiện session logout refresh	Tài khoản và phân quyền	Bước 1: Cho người dùng đăng xuất và làm phiên đăng nhập hết hiệu lực theo cách đã chọn. Bước 2: Xử lý trường hợp phiên hết hạn: thử làm mới an toàn nếu được phép, nếu không thì đưa về trang đăng nhập. Bước 3: Thử mã phiên sai, hết hạn và đã đăng xuất để chắc không truy cập tiếp được.	Các chức năng tài khoản thiết yếu hoạt động với kiểm soát quyền và kiểm thử an toàn.	Logout thu hồi phiên; refresh sai/hết hạn bị từ chối, UI trở v...~~

~~	S3-WBS33	Bảo vệ API theo vai trò	Tài khoản và phân quyền	Bước 1: Liệt kê API tài khoản, nguồn dữ liệu, corpus, truy vấn và đánh giá nằm trong phạm vi Sprint 3, cùng vai trò được phép dùng từng API. Bước 2: Kiểm tra quyền ở máy chủ, không chỉ ẩn nút trên giao diện. Bước 3: Thử tài khoản thiếu quyền gọi trực tiếp từng API và xác nhận bị từ chối.	Các chức năng tài khoản thiết yếu hoạt động với kiểm soát quyền và kiểm thử an toàn.	Sai vai trò bị từ chối server-side ở API trong phạm vi và có test.	K...~~

~~	Số task	36	Giờ dự kiến	150	Tổng giờ thực tế đã ghi	22																						~~

~~	Sprint 3	S3-WBS28	S3-G08	2	Hoàn thiện session logout refresh	Nguyễn Minh Quân	Đã hoàn thành	4		Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Thu Oct 22 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Cho người dùng đăng xuất và làm phiên đăng nhập hết hiệu lực theo cách đã chọn. Bước 2: Xử lý trường hợp phiên hết hạn: thử làm mới an toàn nếu được phép, nếu không thì đưa về trang đăng nhập. Bước 3: Thử mã phiên sai, hết hạn và đã đăng xuất để chắc không truy cập tiếp được.	Logout thu hồi ph...~~

~~	Sprint 3	S3-WBS33	S3-G08	2	Bảo vệ API theo vai trò	Nguyễn Minh Quân	Chưa bắt đầu	3		Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Liệt kê API tài khoản, nguồn dữ liệu, corpus, truy vấn và đánh giá nằm trong phạm vi Sprint 3, cùng vai trò được phép dùng từng API. Bước 2: Kiểm tra quyền ở máy chủ, không chỉ ẩn nút trên giao diện. Bước 3: Thử tài khoản thiếu quyền gọi trực tiếp từng API và xác nhận bị từ chối.	Sai vai trò bị từ chối s...~~

~~					Tổng giờ các task			150	22																			~~

~~Thu Oct 01 2026 07:00:00 GMT+0700 (Indochina Time)	78	48	0.6153846153846154	352	Corpus hợp lệ, tài khoản, vector RAG B1 và 40 câu hiệu chỉnh. Bắt đầu graph.								~~

~~API vận hành hiển thị dữ liệu thật và không lộ bí mật.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	7	5	0.7142857142857143	Đang làm	30	15	Sprint 3 Backlog~~

~~Task đã hoàn thành	94		Lưu ý	100% task chỉ có nghĩa task đã đánh dấu xong.						~~

~~Độ hoàn thành	0.4392523364485981		Điều kiện nghiệm thu	Có bằng chứng cho mọi yêu cầu Must và kết luận review cuối.						~~

~~API vận hành hiển thị dữ liệu thật và không lộ bí mật.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	7	5	0.7142857142857143	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

## 2026-10-22 07:37 - SUA NOI DUNG

- **Người đăng:** hophamdangnhandz123@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-22 07:37

**Nội dung (phần thay đổi được đánh dấu: ~~xóa~~ · cũ → mới · thêm được in đậm):**

🟢 **	S3-WBS20	Tạo chỉ mục pgvector và đo baseline	Embedding và pgvector	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Có kết quả baseline, index và truy vấn trả chunk đúng corpus.	Kế hoạch Sprint 3 đã chốt the...**

🟢 **	S3-WBS25	Truy vấn vector có lọc phạm vi	Embedding và pgvector	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Ca lọc sai công ty/kỳ/corpus trả rỗng hoặc đúng phạm vi; contract cho Hưng dùng.	Kế hoạch Sprint 3...**

🟢 **	Sprint 3	S3-WBS20	S3-G02	2	Tạo chỉ mục pgvector và đo baseline	Hồ Phạm Đăng Nhân	Đang test	4		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Có kết quả baselin...**

🟢 **	Sprint 3	S3-WBS25	S3-G02	2	Truy vấn vector có lọc phạm vi	Hồ Phạm Đăng Nhân	Đang test	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Ca lọc sai công ty/kỳ/cor...**

🟢 **Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	4	0.5	Đang test	30		Sprint 3 Backlog**

🟢 **Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	4	0.5	Đang test	Ngày và phân công là kế hoạch đề xuất.**

~~	S3-WBS20	Tạo chỉ mục pgvector và đo baseline	Embedding và pgvector	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Có kết quả baseline, index và truy vấn trả chunk đúng corpus.	Kế hoạch Sprint 3 đã chốt the...~~

~~	S3-WBS25	Truy vấn vector có lọc phạm vi	Embedding và pgvector	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Tạo, lưu và truy vấn vector đúng corpus, công ty và kỳ.	Ca lọc sai công ty/kỳ/corpus trả rỗng hoặc đúng phạm vi; contract cho Hưng dùng.	Kế hoạch Sprint 3...~~

~~	Sprint 3	S3-WBS20	S3-G02	2	Tạo chỉ mục pgvector và đo baseline	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Mon Oct 19 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Tạo cách tra cứu vector trong pgvector trên dữ liệu đã nạp. Bước 2: Dùng một bộ câu hỏi tiếng Việt/Anh cố định, đo thời gian và kiểm tra đoạn tìm được. Bước 3: Lưu cách cấu hình và kết quả ban đầu để về sau so sánh; nếu dữ liệu thật chưa sẵn, ghi rõ số đo chỉ là tạm trên mẫu.	Có kết quả base...~~

~~	Sprint 3	S3-WBS25	S3-G02	2	Truy vấn vector có lọc phạm vi	Hồ Phạm Đăng Nhân	Chưa bắt đầu	4		Tue Oct 20 2026 07:00:00 GMT+0700 (Indochina Time)	Wed Oct 21 2026 07:00:00 GMT+0700 (Indochina Time)	Bước 1: Thêm bộ lọc để chỉ tìm đoạn của đúng công ty, kỳ, loại tài liệu và phiên bản dữ liệu đang chọn. Bước 2: Trả về một số đoạn phù hợp nhất cùng điểm tương đồng và vị trí nguồn. Bước 3: Thử câu hỏi cố tình chọn sai công ty/kỳ để chắc hệ thống không lấy nhầm nguồn ngoài phạm vi.	Ca lọc sai công ty/kỳ/...~~

~~Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Mon Oct 12 2026 07:00:00 GMT+0700 (Indochina Time)	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	4	0.5	Đang làm	30		Sprint 3 Backlog~~

~~Trả được các đoạn gần nghĩa và ghi thời gian tìm kiếm.	Fri Oct 23 2026 07:00:00 GMT+0700 (Indochina Time)	8	4	0.5	Đang làm	Ngày và phân công là kế hoạch đề xuất.~~

- **Người đăng:** dunhvu47@gmail.com
- **Tên / vị trí:** `00_Management/WorkLog_Tracking`
- **Ngày và giờ:** 2026-10-21 21:24


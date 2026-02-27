# ThucHanh6_Nhom1

1. Phân tích Kỹ thuật: Quản trị Cơ sở Dữ liệu
Nội dung này yêu cầu bạn chuyển đổi tư duy từ quản lý dữ liệu phẳng (Excel) sang quản lý dữ liệu quan hệ (Access).

Giai đoạn 1: Chuẩn bị dữ liệu trên Excel

Cấu trúc: Bạn cần tạo 3 Worksheet:


Sheet 1 (Sinh viên): MSSV, Họ tên, Lớp. 


Sheet 2 (Kết quả): MSSV, MãMH, Điểm. 


Sheet 3 (Danh mục Môn học): MãMH, TênMH, Tín chỉ. 


Lưu ý: Đảm bảo cột MSSV và MãMH ở các sheet phải khớp nhau hoàn toàn về định dạng để khi chuyển sang Access có thể tạo liên kết (Relationship). 

Giai đoạn 2: Xử lý trên MS Access

Import dữ liệu: Đưa 3 bảng từ Excel vào Access. 

Thiết lập quan hệ: Đây là bước quan trọng nhất. Bạn cần nối:

MSSV (Bảng Sinh viên) → MSSV (Bảng Kết quả).

MãMH (Bảng Môn học) → MãMH (Bảng Kết quả).


Truy vấn (Query): Bạn sẽ dùng công cụ Query Design hoặc lệnh SQL để lọc dữ liệu theo 4 yêu cầu: 

Lọc theo Lớp (DI1296A1 hoặc DI1296A2). 

Lọc theo Môn học (CT178). 

Kết hợp Lớp + Môn học. 

Kết hợp Lớp + Môn học + Điểm (C). 

🔍 2. Phân tích Kỹ năng: Đánh giá thông tin (CRAAP Test)
Nhiệm vụ này không chỉ là tìm kiếm, mà là "thẩm định" giá trị của thông tin về chủ đề SQL vs NoSQL. 

Quy trình thực hiện:

Chiến lược tìm kiếm: Không chỉ dùng từ khóa đơn giản, hãy dùng toán tử như "SQL vs NoSQL" filetype:pdf để tìm các báo cáo trắng (whitepapers) hoặc bài báo khoa học. 
+1


Áp dụng bộ lọc CRAAP:
+1

C (Currency - Tính thời sự): Công nghệ thay đổi rất nhanh. Một bài viết từ năm 2015 về NoSQL có thể đã lỗi thời. Hãy ưu tiên các nguồn trong 2-3 năm gần đây. 
+2


R (Relevance - Tính liên quan): Thông tin có giải quyết đúng câu hỏi nghiên cứu về "khả năng mở rộng" hay "tính nhất quán" không? 
+2

A (Authority - Tính uy quyền): Tác giả là ai? (Ví dụ: Một chuyên gia tại Oracle sẽ có uy tín khác với một blogger cá nhân). 
+1


A (Accuracy - Tính chính xác): Có số liệu benchmark, biểu đồ so sánh thực tế không hay chỉ là lời nói suông? 
+1


P (Purpose - Mục đích): Đây là bài phân tích khách quan hay là bài quảng cáo của MongoDB/Oracle để bán sản phẩm của họ? 
+2

📝 3. Cấu trúc bài báo cáo (.docx)
Để đạt điểm cao, báo cáo của bạn nên trình bày theo bố cục sau:


Phần 1: Câu hỏi nghiên cứu & Từ khóa: Nêu rõ mục đích tìm kiếm. 


Phần 2: Bảng đánh giá CRAAP: Nên kẻ bảng gồm các cột: STT, Nguồn, 5 tiêu chí CRAAP (chấm điểm 1-5), và Nhận xét chung. 
+1


Phần 3: Tổng hợp kiến thức: Tóm tắt sự khác biệt cốt lõi giữa SQL (dữ liệu cấu trúc, tính nhất quán cao) và NoSQL (dữ liệu không cấu trúc, mở rộng linh hoạt). 


Phần 4: Tài liệu tham khảo: Trình bày theo chuẩn IEEE. 

Ví dụ: [1] Tên tác giả, "Tên bài viết," Tên tạp chí/Trang web, Năm xuất bản.

📂 4. Danh sách File cần nộp
Đảm bảo bạn có đủ 3 file sau với tên chính xác:


BUOI06_MSSV_HoTen.xlsx (Dữ liệu bảng biểu). 


BUOI06_MSSV_HoTen.accdb (Cơ sở dữ liệu & Query). 


BUOI06_MSSV_HoTen.docx (Báo cáo đánh giá CRAAP).

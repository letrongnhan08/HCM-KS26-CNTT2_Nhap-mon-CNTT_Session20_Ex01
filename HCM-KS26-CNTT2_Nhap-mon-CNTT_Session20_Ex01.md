## Bài 1 : Tối ưu từ khóa khi tìm kiếm tài liệu kỹ thuật

**Yêu cầu đầu ra:**

Truy vấn trên là "Bad Query" (gây nhiễu) vì: 

- sử dụng trên Google mà nói những câu cảm thán như "thầy ơi cho em xin" và "với ạ" khiến Google khó tìm kiếm được.
- Sử dụng từ khóa chung chung: "tài liệu học html cơ bản của trang mozilla" khiến Google hiểu đây là tìm hiểu tài liệu HTML chung chung trên Internet thay vì chính thống từ mozilla.
- Ghi không có ghi kiểu site:<tên_miền> <từ_khóa (tìm tài liệu HTML)> hoặc Toán tử " " như "tài liệu học html cơ bản của trang mozilla" để GG xác định rõ hơn 

**Viết lại truy vấn tối ưu**

site:developer.mozilla.org html cơ bản -ads -forum

**Ý nghĩa và lợi ích của việc sử dụng các toán tử**

Toán tử site:
Cú pháp: site: ví dụ (site:developer.mozilla.org)
Ý nghĩa:Khoanh vùng và ép máychỉ tìm kiếm và trả kết quả dữ liệu bên trong một tên miền được chỉ định
Lợi ích: loại bỏ tên miền khác như quảng cáo ,diễn đàn

Toán tử trừ-:
Ý nghĩa Loại bỏ tất cả các kết quả chứa những từ khóa đi sau dấu trừ.
Lợi ích: loại bỏ các bài đăng không liên quan đến HTML chính thống của mozilla

Toán tử "":
Ý nghĩa: buộc Google phải tìm kiếm chính xác 100% cụm từ nằm bên trong dấu ngoặc kép
Lợi ích: Đi thẳng vào tiêu đề HTML chính thống của mozilla
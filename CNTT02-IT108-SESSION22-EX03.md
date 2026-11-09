# Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm
## Báo cao phân tích theo mô hình IPO 
- [x] Input `đầu vào` câu trả lời kèm theo đoạn lệnh **terminal** mà AI xử lý lỗi `Path not found` khi cài python
- [x] **Process** ` xử lý & kiểm chứng` 
- Đối chiếu thông tin bằng cách tìm kiếm trên Google với các nguồn uy tín, sử dụng toán tử nâng cao như: site:stackoverflow.com "Python" "Path not found" hoặc tra cứu trực tiếp tại tài liệu chính thức của Python (python.org)

- Phân tích xem câu lệnh có chứa các từ khóa can thiệp sâu vào hệ thống (như quyền quản trị cao nhất sudo, lệnh xóa file,...) có khớp với lỗi thực tế hay không
- [x] Output `đầu ra` Đưa ra kết luận Lệnh an toàn hoặc Lệnh không an toàn / Cảnh báo AI Hallucination (bịa lệnh sai lệch hoặc gây nguy hiểm cho hệ điều hành).
## 2. Câu lệnh (Prompt) "hỏi ngược lại" AI trước khi thực thi
- [x] Hãy giải thích chi tiết từng phần trong câu lệnh bạn vừa đưa ra có tác dụng gì với hệ thống máy tính của tôi? Nó có rủi ro xóa hoặc làm lỗi hệ điều hành không? Hãy dẫn chứng nguồn tài liệu chính thống (như trang chủ Python hoặc StackOverflow) chứng minh đây là cách khắc phục chuẩn xác.
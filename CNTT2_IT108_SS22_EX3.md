**Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm** 

**Yêu cầu đầu ra:**

* input: câu trả lời của ai, gồm câu lệnh lạ bảo dán vào terminal để sửa lỗi "path not found" khi cài python  
* process:  
  1. không chạy ngay, đọc xem lệnh làm gì  
  2. copy lệnh hoặc phần lạ trong lệnh, tìm trên google bằng site:stackoverflow.com "path not found" python, hoặc xem trang chủ python.org  
  3. so sánh với cách sửa chính thức, kiểm tra hệ điều hành và phiên bản có đúng không  
  4. nếu không tìm thấy lệnh ở đâu thì nghi ai bịa (hallucination)  
* output: kết luận lệnh an toàn khi có nguồn đáng tin và đúng với máy mình. không có nguồn, hoặc lệnh xóa dữ liệu, đổi quyền, sửa hệ thống thì không an toàn, không chạy

* Prompt để hỏi ngược lại:  
  “tôi là sinh viên năm nhất, đang dùng Windows 11 và cài Python 3.12  
  tôi bị lỗi "Path not found", bạn đưa tôi câu lệnh này:  
  \[dán câu lệnh của ai vào đây\]  
  trước khi tôi chạy, hãy:  
  giải thích từng phần của lệnh làm gì bằng tiếng việt dễ hiểu  
  cho biết lệnh có xóa dữ liệu, đổi quyền hoặc sửa hệ thống không  
  cho biết lệnh có đúng với Windows 11 và Python 3.12 không  
  nếu bạn không chắc chắn thì nói thẳng, đừng đoán  
  cho tôi link tài liệu chính thức để tôi kiểm tra lại”



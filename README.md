# interview-question

## sử lý vấn đề
1. User không thể upload file lên server, về mặt logic code không có bất kỳ lỗi nào, vậy nguyên nhân nào dẫn đến việc không thể upload file trong trường hợp này ?
2. Dịch vụ hosting không cho phép website lưu trữ file trực tiếp trên server, hãy đưa ra giải pháp cho vấn đề này.
3. Hệ thống cần export một số lượng lớn thông tin người dùng hiện tại. Bạn hãy đề xuất các solution có thể có cho yêu cầu này.
  + UV cần đưa ra câu hỏi nếu yêu cầu ko rõ ràng
  + UV cần đưa ra ít nhất 2 solution cụ thể
  + UV đã đưa ra soluion tối ưu hay chưa ?
4. Nếu browser không hỗ trợ cookie, hãy đưa ra solution cụ thể để đảm bảo persistent data giữa client vs server side
5. Hãy đưa ra các soluton để tăng performacne cho một website
  + Optimized code
  + Optimized DB 
  + Optimized DB query
  + Optimized client assest (minify js, css, image)
  + Optimized HTML structure
  + Optimized assets loading time (using CDN, browser cached, E-Tags)
  + Optimized hosting server (web, db)
    - Scale up
    - Scale out
6. Nếu được giao cho chức năng xử lý upload file cho một website bạn sẽ làm như thế nào ?

## kỹ thuật lập trình
1. Mô tả session trong PHP
  + UV cần mô tả mối quan hệ giữa client vs server (cookie vs session)
  + Mặc định server sẽ lưu trữ session ntn
  + Làm sao chia sẽ thông tin giữa các trang với nhau
2. Tại sao PHP lại được gọi là Scriting language (ngôn ngữ thông dịch) ?
3. Hãy kể tên các ngôn ngữ thông dịch khác mà bạn biết ?
4. Bạn từng làm sử dụng PHP với những loại database nào ?
  - Nếu PHP muốn kết nối với MySQL server cần phải làm gì ?
  - Nếu PHP muốn kết nối với SQL server cần phải làm gì ?
  - Nếu PHP muốn kết nối với Oracle server cần phải làm gì ?
  - Nếu PHP muốn kết nối với NoSQL (mongodb, redis) cần phải làm gì ?
5. Hãy nêu sự khác biệt giữa hàm require_once(), require(), include()
6. Làm sao để chạy PHP từ CLI ? 
7. Làm sao để tăng thời gian thực thi của một script PHP
8. Quản lý dependency trong PHP như thế nào ?
9. Sự khác biệt giữa GET và POST ?
10. Cho một biến gọi là $input với các giá trị tương ứng '1,2,3,4,5,6,7,8,9'. Làm sao tính được tổng các giá trị số nguyên có trong biến $input đó ?

# Dự án Crawling Tin tức Vietnamnet

## Giới thiệu
Dự án này tập trung xây dựng hệ thống **tự động thu thập (crawl) tin tức** từ báo điện tử [Vietnamnet](https://vietnamnet.vn/).  
Hệ thống cho phép trích xuất các thông tin chính từ bài báo, bao gồm:  
- **Tiêu đề**  
- **Tác giả**  
- **Nội dung**  
- **Ảnh minh họa**  

Hiện tại, hệ thống có khả năng thu thập khoảng **100 bài viết mỗi ngày**, tạo thành một tập dữ liệu thô phục vụ cho các bài toán **Xử lý ngôn ngữ tự nhiên (NLP)** như:  
- Tóm tắt văn bản  
- Phân loại tin tức  
- Phân tích cảm xúc
  
##  Công nghệ sử dụng
- **Selenium** – điều khiển trình duyệt, thu thập dữ liệu động  
- **Requests** – gửi HTTP request, lấy nội dung trang  
- **Pillow** – xử lý và lưu trữ ảnh  
- **TQDM** – hiển thị tiến trình crawl  
- **Webdriver Manager** – tự động quản lý ChromeDriver  

# Tool Like Facebook Đa Cookie

## Giới thiệu

Đây là một script Python được thiết kế để tự động hóa việc tăng cảm xúc (like, love, care, v.v.) trên các bài đăng Facebook sử dụng nhiều tài khoản và cookie Facebook. Công cụ này sử dụng dịch vụ "Machine Liker" để giả lập các phản ứng trên các bài viết.

## Tính năng

- Tự động tăng cảm xúc trên các bài đăng Facebook.
- Hỗ trợ nhiều tài khoản thông qua việc sử dụng cookie.
- Hiệu ứng đếm ngược giữa các yêu cầu để tránh bị khóa tài khoản.

## Yêu cầu

- Python 3.x
- Các thư viện Python: `requests`, `colorama`

## Cài đặt

1. **Cloning repo**:

   ```sh
   git clone https://github.com/nuhoangcodon99/MachineLiker-Python.git
   cd MachineLiker-Python
   ```

2. **Cài đặt các thư viện cần thiết**:

   ```sh
   pip install requests colorama
   ```

3. **Tạo file `cookie.txt`**:
   - Tạo file `cookie.txt` trong thư mục dự án và thêm cookie Facebook của bạn vào file này. Mỗi cookie nên nằm trên một dòng.

## Hướng dẫn sử dụng

1. **Chạy script**:

   ```sh
   python main.py
   ```

2. **Nhập URL bài viết**:

   - Nhập URL của bài viết Facebook mà bạn muốn tăng cảm xúc.

3. **Chọn các loại cảm xúc**:

   - Nhập các loại cảm xúc mà bạn muốn tăng (like, love, care, v.v.).

4. **Chờ quá trình hoàn thành**:
   - Script sẽ tự động gửi các yêu cầu tăng cảm xúc và hiển thị thông tin quá trình trên console.

### Lưu ý

- Việc sử dụng công cụ này có thể vi phạm điều khoản dịch vụ của Facebook. Bạn tự chịu trách nhiệm về việc sử dụng công cụ này.
- Sử dụng thời gian chờ giữa các yêu cầu để tránh bị Facebook phát hiện và khóa tài khoản.

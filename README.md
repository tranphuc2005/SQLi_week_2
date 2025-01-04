# Bài Tập Tuần 2: SQL Injection

## Mục Tiêu

Mục tiêu của bài tập tuần này là hiểu và khai thác lỗ hổng SQL Injection (SQLi) trong ứng dụng web. Cụ thể, bạn sẽ:

1. **Đọc và thống kê ít nhất 100 writeup về khai thác lỗ hổng SQL Injection.**
2. **Thực hiện khai thác 1 lỗ hổng SQL Injection trong source code của bài tập web.**
3. **Vượt qua các challenge SQLi trên các nền tảng bảo mật như PortSwigger và HackTheBox.**

## Nội Dung Bài Tập

### 1. Thống Kê Các Writeup Về Khai Thác SQL Injection

- Tìm đọc ít nhất 100 writeup về khai thác lỗ hổng SQLi.
- Liệt kê writeups từ các công ty lớn như Apple, Facebook, Microsoft và các cuộc thi CTF từ CTF Time (https://ctftime.org/) hoặc HackTheBox.
- Cung cấp các liên kết trong định dạng sau:
  - [Facebook Bug Bounty Writeups](https://github.com/jaiswalakshansh/Facebook-BugBounty-Writeups)
  - Các writeup khác sẽ được liệt kê dưới dạng tương tự.

### 2. Khai Thác SQL Injection Trong Source Code Bài Tập Web

Trong bài tập này, bạn sẽ khai thác lỗ hổng SQLi trong source code của bài tập web đã được cung cấp. Bạn sẽ thực hiện khai thác theo 2 cách sau:

#### 2.1. Khai Thác Bằng Công Cụ SQLMap

- **SQLMap** là công cụ tự động hóa giúp khai thác SQL Injection trong ứng dụng web.
- Sử dụng SQLMap để khai thác lỗ hổng SQLi và dump thông tin bảng `users`.
- Mục tiêu là lấy được thông tin về các `username` và `password` của người dùng.

#### 2.2. Khai Thác Bằng Python Code

- Viết mã Python để khai thác SQLi và dump thông tin bảng `users`.
- Mục tiêu là lấy được thông tin về các `username` và `password` của người dùng.
- Bạn có thể sử dụng thư viện `requests` trong Python để gửi các yêu cầu HTTP và tấn công SQL Injection.

### 3. Vượt Qua Các Challenge SQLi Trên PortSwigger Và HackTheBox

- Truy cập vào các challenge SQLi trên [PortSwigger](https://portswigger.net/web-security/sql-injection) và [HackTheBox](https://www.hackthebox.eu/).
- Vượt qua các bài tập SQLi và cung cấp thông tin về các bài tập đã giải quyết.

## Các Bước Thực Hiện

1. **Tìm Kiếm Và Thống Kê Writeups:**
   - Sử dụng các công cụ tìm kiếm, CTF Time, và các blog, forum về bảo mật để tìm các bài viết về SQLi.
   - Tạo một danh sách gồm ít nhất 100 writeup liên quan đến SQLi và khai thác lỗ hổng SQLi.

2. **Khai Thác SQLi Trong Source Code:**
   - Sử dụng SQLMap để tự động khai thác và dump bảng `users`.
   - Viết mã Python để thực hiện khai thác thủ công thông qua SQLi.

3. **Giải Các Bài Tập Trên PortSwigger Và HackTheBox:**
   - Truy cập các bài tập SQLi trên các nền tảng bảo mật này và hoàn thành chúng.

## Yêu Cầu

- **Sử Dụng Công Cụ:** SQLMap, Python (requests).
- **Kết Quả:** Các liên kết writeup đã thống kê, mã Python thực hiện khai thác, báo cáo kết quả từ các nền tảng bảo mật.
- **Thời Gian Hoàn Thành:** Vượt qua các bài tập trong thời gian quy định.

## Tài Nguyên Tham Khảo

- [CTF Time](https://ctftime.org/)
- [HackTheBox](https://www.hackthebox.eu/)
- [PortSwigger Web Security Academy - SQL Injection](https://portswigger.net/web-security/sql-injection)

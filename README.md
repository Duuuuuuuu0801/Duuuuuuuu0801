# Ứng Dụng Chat Real-time

## Chủ Đề
Ứng dụng Chat Real-time là một nền tảng giúp người dùng trò chuyện và gửi tin nhắn theo thời gian thực.

## Thành Viên

- Nghiêm Văn Nam - B20DCCN449
- Nguyễn Huy Du - B20DCCN125
- Nguyễn Ngọc Minh - B20DCCN437

## Công nghệ sử dụng/ngôn ngữ

- Back-end: Spring Boot (Java)
- Front-end: ReactJS (JavaScript)
- WebSocket: SockJS
- Quản lý Phiên: STOMP

## Chức Năng

Dự án Chat App dự kiến có các chức năng sau:

- Đăng ký: Cho phép người dùng đăng ký tài khoản mới để tham gia vào hệ thống.
- Đăng nhập: Cho phép người dùng đăng nhập vào tài khoản của họ.
- Chat 1-1: Cho phép người dùng trò chuyện riêng tư với nhau.
- Chat Nhóm: Cho phép người dùng tạo và tham gia các cuộc trò chuyện nhóm.
- Gửi ảnh, video, file: Người dùng có thể chia sẻ ảnh, video hoặc tệp tin với người khác trong cuộc trò chuyện.
- Thông báo: Hệ thống có thể gửi thông báo cho người dùng về các sự kiện quan trọng.

### Kiến Trúc

- Ứng dụng sử dụng mô hình client-server với back-end được xây dựng trên Spring Boot và front-end sử dụng ReactJS. Giao tiếp thời gian thực được thực hiện thông qua SockJS và STOMP.

### Thư Viện Xử Lý
- Spring Boot: Xử lý logic back-end và kết nối cơ sở dữ liệu.
- ReactJS: Xây dựng giao diện người dùng linh hoạt và hiệu quả.
- SockJS và STOMP: Cung cấp giao tiếp thời gian thực giữa client và server.

## Cài đặt môi trường

1. Cài đặt JDK:
- jdk 1.8

2. Cài đặt Node.js và npm:
- npm install

## Preview giao diện

<tr>
  <center>
    - Chat 1-1
    <img src="https://scontent.fhan14-2.fna.fbcdn.net/v/t1.15752-9/400294690_861661592411358_8299794520619596524_n.png?stp=dst-png_s2048x2048&_nc_cat=106&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeGa7B0y9DRFwmg1cTAT8hbPVr3WJOE8cWhWvdYk4TxxaLMe3w0q4mlKyPLPpgkrWr1UBwxLcfTbBYRkQBNwHsy1&_nc_ohc=9tWkbfrFRSIAX8j9pUi&_nc_ht=scontent.fhan14-2.fna&oh=03_AdRXRXD3opHJex_V5whhdMxgUH_NbHP6f152AtvcFfVsDw&oe=6571C31E" />

  - Chat nhóm
  </center>
</tr>

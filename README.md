# Kybro_Auto

================================================================================
          HƯỚNG DẪN SỬ DỤNG TOOL AUTO REGISTER KRYBON (MODE 1)
================================================================================

1. CÀI ĐẶT THƯ VIỆN (CHẠY LỆNH NÀY ĐẦU TIÊN):
--------------------------------------------------------------------------------
Mở CMD tại thư mục tool và chạy lệnh:
npm install 

2. CHUẨN BỊ CÁC FILE ĐẦU VÀO (BẮT BUỘC):
--------------------------------------------------------------------------------
Bạn cần tạo các file sau nằm cùng thư mục với file p2.js:

- proxy.txt: Danh sách proxy (Mỗi dòng 1 proxy)
  Định dạng: http://user:pass@ip:port hoặc http://ip:port

- user_agents.txt: Danh sách User-Agent trình duyệt (Mỗi dòng 1 UA)
  Nếu không có file này tool sẽ lấy UA mặc định.

3. CÁCH CHẠY TOOL:
--------------------------------------------------------------------------------
Lệnh chạy: node p2.js

- Lần đầu chạy tool sẽ yêu cầu: "=> License Key : "
- Bạn dán Key bản quyền vào và nhấn Enter.
- Key sẽ được lưu vào file license.txt, lần sau chạy sẽ không hỏi lại.

4. CÁC FILE KẾT QUẢ ĐẦU RA (TOOL TỰ TẠO):
--------------------------------------------------------------------------------
- taikhoan.txt: Lưu tài khoản đã đăng ký (Email|Pass|Name).
- mail.txt: Lưu tài khoản Mail.tm để lấy OTP nếu cần (Email|Pass).
- token.txt: Lưu Access Token của tài khoản.
- last_index.txt: Lưu vị trí đang chạy, giúp tool chạy tiếp nếu bị ngắt quãng.

================================================================================

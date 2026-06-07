# Phân loại rác thải sử dụng Thị giác máy tính (MobileNetV2)

## Thông tin sinh viên thực hiện
* **Họ và tên:** Nguyễn Phan Tấn Đạt
* **MSSV:** N23DCCI012
* **Lớp:** D23CQCI01-N

## Cấu trúc thư mục mã nguồn
* `/browser`: Chứa mã nguồn để chạy suy luận (inference) trực tiếp trên trình duyệt web thông qua WebAssembly. 
* `/node`: Chứa mã nguồn để chạy thử nghiệm trên môi trường Node.js.

## Hướng dẫn cài đặt và chạy thử
Để tránh lỗi CORS policy của trình duyệt, cần chạy local server:
1. Mở Terminal tại thư mục `/browser`.
2. Chạy lệnh: `python server.py` hoặc `python3 server.py`
3. Mở trình duyệt web và truy cập: `http://localhost:8000`

## Nền tảng phát triển
* Nền tảng: Edge Impulse
* Kiến trúc: MobileNetV2 0.35

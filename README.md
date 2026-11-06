# k17_portfolio

## Sản phẩm này là gì?
Đây là hồ sơ học tập trực tuyến được làm bằng HTML5 và CSS3. Người xem có thể tìm hiểu kỹ năng đang học, các bài thực hành và cách liên hệ ngay trên một trang.

## Demo
https://nguyenchinhvietanh2005.github.io/k17_portfolio/

Bấm URL trên để truy cập website.

## Tính năng hiện có
- Năm mục điều hướng: Giới thiệu, Kỹ năng, Dự án, Học tập, Liên hệ.
- Ba thẻ giới thiệu bài tập, có hình minh họa; bảng tóm tắt học phần.
- Form thực hành kiểm tra họ tên, email và độ dài lời nhắn bằng HTML5.
- Trang kết quả có nút quay về Liên hệ. Form không gửi email thật.

## Cách mở hoặc chạy thử
1. Bấm **Truy cập website** trong mục Demo.
2. Chọn **Kỹ năng** để xem nội dung đang học.
3. Chọn **Dự án** hoặc nút **Xem dự án** để xem ba thẻ bài tập.
4. Chọn **Liên hệ**, điền dữ liệu giả vào ba trường rồi bấm **Gửi lời nhắn**.
5. Khi trang kết quả xuất hiện, bấm **Quay lại liên hệ**.

Để mở bản tải về: bấm **Code → Download ZIP** tại repository, giải nén và mở `index.html` bằng Chrome hoặc Edge. Dự án không có bước cài gói phụ thuộc.

## Cấu trúc thư mục
| Đường dẫn | Nội dung |
|---|---|
| `index.html` | Trang chính với năm phần nội dung |
| `ket-qua.html` | Thông báo sau khi gửi form thực hành |
| `css/style.css` | Kiểu chữ, màu sắc và bố cục |
| `assets/` | Ảnh phong cảnh và hình dự án |
| `CHANGELOG.md` | Ghi nhận thay đổi so với v7 |
| `docs/evidence-index.md` | Các lần thử và kết quả quan sát |
| `docs/AI_LOG.md` | Nhật ký AI cho bài Lab 8 |
| `docs/evidence/` | Ảnh chụp trang chính và trang kết quả |
| `AI_log.md` | Nhật ký cũ được giữ lại |

## Đã kiểm tra
Ngày 06/11/2026, AI hỗ trợ mở bản công khai, kiểm tra bốn hình ảnh và thao tác điều hướng. Đã gửi form bằng dữ liệu giả và dùng nút quay lại; xem [bảng kết quả](docs/evidence-index.md).

## Giới hạn và phần chưa kiểm tra
- Các địa chỉ ở ba thẻ dự án mới là dòng chữ, chưa bấm được.
- Chưa thử ở 375px, cửa sổ ẩn danh hoặc thiết bị di động thật.
- Form dùng GET nên dữ liệu xuất hiện trên URL; chỉ dùng dữ liệu giả. Chưa có chức năng nhận thư và lưu lời nhắn.
- Chưa có phiếu kiểm tra chéo hai bạn; sinh viên cần tự bổ sung kết quả thực tế.

## Khai báo AI
Chi tiết hỗ trợ soạn hồ sơ và kiểm tra nằm trong [AI_LOG](docs/AI_LOG.md). Thông tin sinh viên để tự điền trong báo cáo nộp lớp.

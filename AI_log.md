# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Nguyễn Chính Việt Anh ]
- Mã sinh viên – Lớp: [ 1771020011 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://github.com/nguyenchinhvietanh2005/k17_portfolio.git ]
- URL website: [ https://nguyenchinhvietanh2005.github.io/k17_portfolio/ ]
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ sai liên kết đến file css trong index.html ]
- Mong muốn và hiện tượng thực tế: [ mong muốn trang web hiển thị đầy đủ có cả phần css. Hiện tượng thực tế: chỉ hiển thị phần giao diện html không chạy css ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [ đã kiểm tra trong trang devtools ]
- Tôi nghi nguyên nhân là: [ lỗi liên kết đến css trong index.html ]
- Vì sao tôi nhận định như vậy: [ tôi kiểm tra thấy devtools không tải được phần css trong khi html vẫn hiển thị đầy đủ ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ github copilot ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ Tôi có URL [Trần Việt Anh - Portfolio CV].
Tôi dự đoán [sai link css].
Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu.
Chỉ tư vấn, không sửa tệp. Không kết luận đã sửa thành công. ]

- Gợi ý chính của AI:

  [ Sửa tối thiểu đề xuất: <link rel="stylesheet" href="css/style.css" /> ]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [x] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ sửa theo gợi ý của AI ]
- Lý do, dựa trên dữ kiện nào: [ tôi kiểm tra lại liên kết trong index.html dựa vào dòng liên kết bị sai ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ index.html ]
- Nội dung thay đổi hoặc cách xử lý khác: [ sửa lại phần liên kết đến css trong file index.html ]
- Commit của bản sửa, nếu có: [ đã commit ]
- Bản sửa đã deploy: [x] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [ không tải được css ] | [ đã tải được phần css ] |
| Giao diện/chức năng trên URL website | [ chỉ hiển thị mỗi giao diện html ] | [ đã tải được css và hoạt động bình thường ] |

- Cách thử lại và kết quả thực tế: [ commit rồi load lại trang và đã hoạt động được  ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ trước khi commit trang web chỉ hiển thị mỗi giao diện html và sau khi commit trang web đã hiển thị đầy đủ phần css ]

## 5. Kết luận

- [x] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [ tôi học được cách kiểm tra đường dẫn file css trong html và cách tìm lỗi giao diện web. Lần sau tôi sẽ kiểm tra kỹ cách đường dẫn trước khi deploy web ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*

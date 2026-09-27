# Tô Hình Đáp Án

Tool tạo trò chơi **tô hình bằng đáp án trắc nghiệm**: người chơi trả lời câu hỏi, rồi tô đen những ô ghi đáp án đúng. Tô xong sẽ hiện ra bức hình.

👉 **Dùng ngay:** https://nnmhuy.github.io/to-hinh-dap-an/
📖 **Hướng dẫn có hình:** https://nnmhuy.github.io/to-hinh-dap-an/readme.html

## Tính năng

- Chuyển **ảnh lưới ô đen/trắng** thành lưới (tự nhận số hàng/cột), hoặc tự vẽ trên lưới trống.
- Nhập số câu, số lựa chọn (2–6) và đáp án đúng; **random chia vùng** sao cho ô đen = đáp án đúng, các ô của một lựa chọn liền nhau, kích thước các lựa chọn ngẫu nhiên để không đoán được đáp án.
- Chỉnh tay: merge / tách vùng, sửa chữ, tô lại ô.
- Xem trước và **in / xuất PDF vector** (viền từng ô hoặc viền theo vùng), tải SVG.
- Dữ liệu tự lưu trong trình duyệt; lưu / mở file dự án `.json`.

Chạy hoàn toàn trên trình duyệt, không cần server, không gửi dữ liệu đi đâu.

## Tạo ảnh lưới từ ảnh bất kỳ

Dùng [ascii-magic.com](https://www.ascii-magic.com/app): chọn **Pixel Art**, Mode **Solid Black**, Char Opacity **100%**, Brightness **100**, canh **Pixel Size** và **Coverage**, rồi **Export PNG**. Chi tiết từng bước có ảnh minh hoạ trong [hướng dẫn](https://nnmhuy.github.io/to-hinh-dap-an/readme.html#tao-anh).

## Cấu trúc

| File | Nội dung |
|------|----------|
| `index.html` | Toàn bộ tool (HTML + CSS + JS, một file) |
| `readme.html` | Trang hướng dẫn |
| `guide/` | Ảnh chụp màn hình cho hướng dẫn |

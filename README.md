# Ghép JAR Game J2ME x2/x3/x5/x10

Công cụ ghép nhiều bản game J2ME (Java ME) vào một file JAR duy nhất, chạy hoàn toàn trên trình duyệt.

## Tính năng

- Ghép game J2ME thành nhiều bản: x2, x3, x5, x10
- Xử lý trực tiếp trên trình duyệt, không upload lên server
- Tự động đổi tên gói cho từng bản để tránh xung đột
- Chuyển đổi API MIDP chuẩn (MIDlet, Display, Canvas, Alert...) sang lib.*
- Xử lý RecordStore riêng biệt cho mỗi bản (dữ liệu lưu không đè nhau)
- Framework menu chọn game MrQuyet được nhúng sẵn

## Cách sử dụng

1. Mở file `index.html` trên trình duyệt
2. Chọn file `.jar` game gốc (kéo thả hoặc nhấn để chọn)
3. Chọn số bản muốn ghép (x2, x3, x5, x10)
4. Nhập tên hiển thị (tùy chọn)
5. Nhấn **Ghép ngay**
6. Tải file kết quả

## Yêu cầu

- Trình duyệt hỗ trợ JavaScript hiện đại
- File `.jar` game J2ME hợp lệ (có MIDlet-1 trong manifest)

## Cấu trúc

```
advanced-menu/
└── index.html    #Ứng dụng web hoàn chỉnh (HTML + CSS + JS)
```

## Công nghệ

- HTML5 / CSS3 / Vanilla JavaScript
- JSZip - Xử lý file ZIP/JAR trên trình duyệt
- Bytecode engine - Parse và sửa đổi class file Java trực tiếp

## Nguồn (Bài chia sẽ của Trần Văn Hưởng)

- Facebook: https://www.facebook.com/share/p/1EG244S5nV/

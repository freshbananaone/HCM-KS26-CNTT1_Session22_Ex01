# Bài 1: Tìm kiếm tài liệu học tập chính thống bằng Google

## 1. Chuỗi truy vấn Google

Để tìm giáo trình **"Nhập môn Công nghệ Thông tin"** dạng PDF trên website của Học viện Công nghệ Bưu chính Viễn thông (PTIT), em sử dụng câu truy vấn:

```text
site:ptit.edu.vn filetype:pdf "Nhập môn Công nghệ Thông tin" -site:123docz.net -site:tailieu.vn
```

**Ý nghĩa các toán tử:**

| Toán tử | Tác dụng |
|---|---|
| `site:ptit.edu.vn` | Chỉ tìm trên tên miền của Học viện PTIT và các trang thuộc phạm vi tên miền này. |
| `filetype:pdf` | Lọc kết quả theo định dạng tệp PDF. |
| `"Nhập môn Công nghệ Thông tin"` | Yêu cầu Google tìm đúng cụm từ tên tài liệu. |
| `-site:123docz.net` | Loại bỏ kết quả từ trang `123docz.net`. |
| `-site:tailieu.vn` | Loại bỏ kết quả từ trang `tailieu.vn`. |




## 2. Vì sao `filetype:` giúp tiết kiệm thời gian?

Theo em, nếu chỉ gõ **"tải sách Nhập môn Công nghệ Thông tin"**, Google có thể hiện nhiều bài quảng cáo, trang giới thiệu hoặc trang yêu cầu đăng ký tài khoản. Mình phải mở từng trang mới biết có tệp cần tìm hay không.

Khi thêm **`filetype:pdf`**, Google tập trung vào các kết quả dạng PDF, giúp em lọc nhanh hơn và không phải mất thời gian dò tìm nút tải sách. Kết hợp với **`site:ptit.edu.vn`** còn giúp ưu tiên nguồn chính thống từ Học viện, hạn chế việc bấm nhầm link không đáng tin cậy.

Tuy nhiên, tệp PDF trên website chính thức **không đồng nghĩa với việc chắc chắn tải công khai được**. Một số giáo trình thuộc thư viện số của trường có thể yêu cầu đăng nhập hoặc bị giới hạn quyền truy cập.

## 3. Ảnh chụp màn hình 3 kết quả đầu tiên

**Tình trạng kiểm tra:** Em chưa xác minh được 3 kết quả Google đúng với *toàn bộ* câu truy vấn ở mục 1. Việc tìm kiếm nguồn công khai cũng chưa xác nhận có bản PDF công khai với đúng tên **"Nhập môn Công nghệ Thông tin"** trên máy chủ PTIT. Vì vậy, **không tự tạo ảnh giả và không ghi các tài liệu khác thành 3 kết quả đầu tiên**.

**Cách lấy ảnh thật để nộp:**

1. Mở liên kết Google ở mục 1 và đợi trang kết quả hiển thị.
2. Nếu có từ 3 kết quả trở lên, cuộn đến vị trí thấy rõ 3 kết quả đầu và ô tìm kiếm chứa truy vấn.
3. Trên Windows nhấn **`Windows + Shift + S`**, chọn vùng chụp và lưu ảnh tên **`ket-qua-google.png`**. Trên macOS dùng **`Shift + Command + 4`**.
4. Đặt ảnh cạnh tệp `.md`, sau đó chèn vào đây bằng dòng Markdown:

```md
![Ảnh chụp 3 kết quả Google đầu tiên](ket-qua-google.png)
```

Nếu Google **không có kết quả** với truy vấn quá chặt, em sẽ chụp lại màn hình thông báo không tìm thấy và ghi rõ tình trạng thực tế, thay vì tự bịa 3 kết quả. Có thể thử nới lỏng từ khóa để tìm tài liệu gần chủ đề, nhưng phải ghi rõ đã thay đổi truy vấn.

**Truy vấn mở rộng (dự phòng, không thay thế truy vấn bắt buộc):**

```text
site:ptit.edu.vn filetype:pdf "Nhập môn" "Tin học"
```
tải, không nên nạp tiền hoặc chạy phần mềm lạ chỉ để lấy một file PDF.

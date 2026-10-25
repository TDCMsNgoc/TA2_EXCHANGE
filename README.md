# ENGLISH 2 - EXCHANGE (40 CÂU TRẮC NGHIỆM GIAO TIẾP)
### TRƯỜNG CAO ĐẲNG CÔNG NGHỆ THỦ ĐỨC (TDC)

Hệ thống trắc nghiệm trực tuyến 40 câu hỏi tiếng Anh giao tiếp chuẩn học phần **English 2 - EXCHANGE**, được thiết kế chuyên biệt để đưa lên **GitHub** và phát hành miễn phí qua **GitHub Pages**.

---

## 🌟 TÍNH NĂNG NỔI BẬT

1. **Nhận diện thương hiệu Trường Cao đẳng Công nghệ Thủ Đức**:
   - Bên góc trái hiển thị logo chính thức của trường TDC và dòng chữ nổi bật **"English 2 - EXCHANGE"**.
   - Giao diện phối màu xanh navy & cam đặc trưng, chuẩn sư phạm, tương thích tối đa trên cả điện thoại (smartphone), máy tính bảng và máy tính để bàn.

2. **Làm bài theo thời gian hiển thị (Countdown Timer)**:
   - Đồng hồ đếm ngược 40:00 hiển thị liên tục ở thanh tiêu đề.
   - Tự động cảnh báo chuyển màu đỏ khi còn dưới 5 phút.
   - Ghi nhận chính xác tổng thời gian sinh viên hoàn thành bài thi.

3. **Bảo mật đáp án - Chỉ hiển thị sau khi nộp bài**:
   - Trong quá trình làm bài, sinh viên chỉ thấy câu hỏi và các phương án lựa chọn (A, B, C, D).
   - Có bảng điều hướng 40 câu hỏi, thanh tiến độ làm bài và nút gắn sao (★) đánh dấu xem lại câu khó.
   - Cảnh báo nếu sinh viên còn câu chưa chọn trước khi xác nhận nộp bài.
   - **Sau khi nộp bài**, hệ thống lập tức mở khóa:
     - Bảng điểm chi tiết: Điểm số (trên 40), quy đổi điểm hệ 10, tỷ lệ %, xếp loại.
     - Hiển thị phương án sinh viên đã chọn (Đúng: viền xanh ✓ | Sai: viền đỏ ✗).
     - **Giải thích tại sao dùng**: Phân tích chi tiết quy tắc ngữ pháp, cấu trúc giao tiếp và nguyên nhân loại các phương án sai.
     - **Dịch nghĩa chi tiết**: Bản dịch tiếng Việt hoàn chỉnh của cả đoạn hội thoại và 4 phương án.
     - Bộ lọc xem lại tiện lợi: Xem tất cả / Chỉ xem câu đúng / Chỉ xem câu sai.
     - Chức năng **In / Lưu PDF bảng điểm** và **Xuất file Excel (CSV)** để sinh viên nộp lại cho giảng viên.

4. **Theo dõi số lượng sinh viên truy cập link (Visitor Counter)**:
   - Bộ đếm lượt truy cập thời gian thực được tích hợp trực tiếp trên thanh tiêu đề: `👁️ Truy cập: [Số lượt]`.
   - Giảng viên có thể xem trực tiếp số lượt truy cập bất cứ lúc nào qua API trực tuyến:  
     👉 `https://api.counterapi.dev/v1/tdc-english2-exchange/page-visits`
   - Bảng thống kê dành riêng cho Giảng viên hiển thị danh sách các bài thi đã nộp trên trình duyệt.

---

## 📁 CẤU TRÚC THƯ MỤC

```text
TA2-EXCHANGE/
│
├── index.html          # Trang chủ ứng dụng web (HTML5)
├── logo-tdc.png        # Logo chính thức của Trường CĐCN Thủ Đức
├── css/
│   └── style.css       # Toàn bộ giao diện, hiệu ứng & chuẩn in ấn PDF
├── js/
│   ├── questions.js    # Dữ liệu 40 câu trắc nghiệm + Đáp án + Giải thích + Dịch nghĩa
│   └── app.js          # Xử lý tính giờ, chấm điểm, khóa/mở đáp án & đếm lượt truy cập
└── README.md           # Hướng dẫn chi tiết triển khai lên GitHub Pages
```

---

## 🚀 HƯỚNG DẪN ĐƯA LÊN GITHUB & BẬT GITHUB PAGES (5 PHÚT)

Thầy/Cô có thể đưa toàn bộ thư mục này lên GitHub một cách cực kỳ đơn giản theo 1 trong 2 cách sau:

### CÁCH 1: Kéo thả trực tiếp trên website GitHub (Không cần cài đặt gì)

1. **Đăng nhập vào GitHub**: Truy cập [https://github.com](https://github.com) và đăng nhập tài khoản.
2. **Tạo Repository mới**:
   - Bấm vào dấu `+` ở góc trên bên phải chọn **New repository**.
   - Đặt tên Repository (Repository name), ví dụ: `TA2-EXCHANGE` hoặc `english2-tdc`.
   - Để chế độ **Public** (Bắt buộc Public để dùng GitHub Pages miễn phí).
   - Tích chọn **Add a README file** rồi bấm **Create repository**.
3. **Tải các file lên**:
   - Trong trang Repository vừa tạo, bấm nút **Add file** -> chọn **Upload files**.
   - Kéo thả toàn bộ các file và thư mục trong thư mục `TA2-EXCHANGE` này vào:
     - `index.html`
     - `logo-tdc.png`
     - Thư mục `css` (chứa `style.css`)
     - Thư mục `js` (chứa `questions.js` và `app.js`)
   - Cuộn xuống dưới bấm **Commit changes**.
4. **Bật GitHub Pages để lấy link website cho sinh viên**:
   - Bấm vào mục **Settings** của repository (thanh menu trên cùng).
   - Ở cột menu bên trái, tìm và bấm chọn mục **Pages**.
   - Tại phần **Build and deployment** -> **Branch**:
     - Chọn nhánh: **main** (hoặc `master`).
     - Chọn thư mục: **/ (root)**.
     - Bấm **Save**.
   - Đợi khoảng 1-2 phút, tải lại trang sẽ thấy thông báo:
     > *"Your site is live at `https://<ten-tai-khoan>.github.io/<ten-repo>/`"*
   - 👉 **Đây chính là đường link gửi cho sinh viên làm bài!**

---

### CÁCH 2: Dùng lệnh Git (Nếu đã cài Git trên máy)

Mở Terminal / PowerShell tại thư mục `d:\websiteabc\TA2-EXCHANGE` và chạy các lệnh:

```bash
git init
git add .
git commit -m "Khoi tao bai trac nghiem English 2 - EXCHANGE TDC"
git branch -M main
git remote add origin https://github.com/<ten-tai-khoan-github>/TA2-EXCHANGE.git
git push -u origin main
```
Sau đó vào **Settings -> Pages -> Branch: main -> Save** như ở Cách 1.

---

## 📊 CÁCH THEO DÕI SỐ LƯỢNG SINH VIÊN TRUY CẬP

Khi sinh viên bấm vào link GitHub Pages làm bài, số lượt truy cập sẽ tự động tăng:

1. **Xem trực tiếp trên trang web**:
   - Ở góc trên bên phải của trang web có hiển thị huy hiệu `Truy cập: X lượt`.
   - Bấm vào huy hiệu này để mở **Cửa sổ Quản trị viên & Giảng viên**.

2. **Xem từ điện thoại / máy tính bất kỳ qua link API**:
   - Giảng viên chỉ cần lưu lại đường link sau vào bookmark trình duyệt:
     `https://api.counterapi.dev/v1/tdc-english2-exchange/page-visits`
   - Mỗi lần mở link này, hệ thống sẽ trả về số lượt truy cập thực tế (ví dụ: `{"count": 145}`).

3. **Thu thập bảng điểm của từng sinh viên**:
   - Sinh viên sau khi làm bài xong có thể bấm nút **"Xuất bảng điểm CSV (Excel)"** hoặc **"In / Lưu PDF bảng điểm"** gửi cho Giảng viên qua Google Classroom, Zalo nhóm hoặc email.

---

## 📝 DANH SÁCH ĐÁP ÁN NHANH 40 CÂU

| Câu | Đáp án | Tóm tắt chủ điểm giao tiếp |
|:---:|:---:|:---|
| 1 | **A** | Đáp lại tin thi đỗ: *"Well done!"* |
| 2 | **A** | Chúc mừng thi đỗ bằng lái xe: *"Congratulations!"* |
| 3 | **D** | Nhận lời mời ăn tối lịch sự: *"Yes, I’d love to"* |
| 4 | **B** | Hỏi đường lịch sự: *"Could you tell me...?"* |
| 5 | **D** | Đáp lại câu hỏi dự đoán công việc: *"Well, I hope so"* |
| 6 | **C** | Chúc mừng Giáng sinh: *"The same to you!"* |
| 7 | **D** | Đáp lại lời cảm ơn bữa tiệc: *"You’re welcome"* |
| 8 | **C** | Từ chối lời mời ăn khi không đói: *"No, thanks"* |
| 9 | **A** | Đồng ý phục vụ nước uống lịch sự: *"Certainly, sir"* |
| 10 | **B** | Động viên trước buổi phỏng vấn: *"Good luck"* |
| 11 | **A** | Trả lời thì hiện tại hoàn thành: *"No. How about you?"* |
| 12 | **B** | Lượng từ cho gạo/cơm (không đếm được): *"A lot, please."* |
| 13 | **A** | Bày tỏ cảm thông khi bạn phải bận học: *"That’s too bad."* |
| 14 | **C** | Lượng từ cho danh từ đếm được số nhiều (peas): *"Just a few."* |
| 15 | **B** | Phản ứng vui mừng khi được miễn phí: *"That’s great."* |
| 16 | **C** | Hỏi thăm khi bạn thấy không khỏe: *"What’s wrong?"* |
| 17 | **B** | Chào tạm biệt khi bạn phải đi: *"OK. Bye."* |
| 18 | **C** | Đồng ý với lời khuyên nằm nghỉ: *"OK. That’s a good idea."* |
| 19 | **A** | Mừng cho ai đó mua được xe mới: *"Good for you."* |
| 20 | **C** | Tán thưởng khi nhận thuốc cần tìm: *"That’s great."* |
| 21 | **B** | Chúc mừng chị gái kết hôn: *"Congratulations to her!"* |
| 22 | **A** | Bỏ qua khi người khác xin lỗi: *"That’s all right."* |
| 23 | **C** | Trả lời kế hoạch Tết Trung thu (tương lai gần): *"I’m going to take..."* |
| 24 | **B** | Trả lời ngắn thì Hiện tại đơn: *"Yes, I do..."* |
| 25 | **B** | Đồng tình với lời nhận xét kiệt sức: *"You’re right. I’ve been working..."* |
| 26 | **C** | Kể về chuyến đi Đà Lạt tuần trước: *"It was wonderful..."* |
| 27 | **A** | Nhận thêm đồ uống lịch sự: *"Yes, please. It’s delicious."* |
| 28 | **C** | Chúc mừng thăng chức: *"That’s fantastic! You must be very pleased."* |
| 29 | **B** | Trấn an tuân thủ quy chế thi: *"Don’t worry. I’ll keep it switched off."* |
| 30 | **A** | Thói quen gia đình (Hiện tại đơn): *"My mother does, but..."* |
| 31 | **C** | Thì Quá khứ tiếp diễn (hành động đang xảy ra tối qua): *"I was preparing..."* |
| 32 | **B** | Trả lời trải nghiệm quá khứ: *"Yes, I have. It was a memorable experience."* |
| 33 | **A** | Dấu hiệu trời sắp mưa: *"You’re right. We should take an umbrella."* |
| 34 | **A** | Lời khuyên y tế khi đau đầu: *"You ought to get some rest..."* |
| 35 | **A** | Lý do thích đi tàu hỏa: *"Because I enjoy looking at the scenery..."* |
| 36 | **B** | Gợi ý nhà hàng kỷ niệm: *"I think Bella’s is the best..."* |
| 37 | **A** | Ngỏ ý giúp đỡ khi quá tải công việc: *"Would you like me to help you...?"* |
| 38 | **B** | Quy định đồng phục nhà máy: *"Yes, we do. It’s part of the dress code."* |
| 39 | **C** | Kế hoạch chuyển nhà tuần tới: *"Yes, I’m moving there next Friday."* |
| 40 | **A** | Lời khuyên tiết kiệm chi phí: *"You could book your flights early..."* |

---
© 2026 Trường Cao đẳng Công nghệ Thủ Đức (TDC) - Khoa Ngoại Ngữ.

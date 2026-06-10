[![Tải tại đây](https://img.shields.io/badge/⬇_Tải-Tại_Đây-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vids-automation-auto-veo/caiompjhmpmodfbfdbihlkbbeijgpial)

# 🚀 Vids Automation v1.0.0 - Tự động hóa Google Vids AI [![English](https://img.shields.io/badge/English-blue)](README.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Vids Automation** là tiện ích mở rộng giúp tự động hóa quy trình sáng tạo của bạn trên Google Vids (docs.google.com/videos). Dừng việc nhập từng prompt thủ công—tự động hóa quy trình và tạo video, hình ảnh và giọng nói (voice-over) ở quy mô lớn.

-----

## ✨ Các tính năng chính

* **🚀 Xử lý hàng loạt:** Xếp hàng hàng chục hoặc hàng trăm prompt và để tiện ích tự động gửi và tạo nội dung trên Google Vids.
* **🎬 Văn bản thành Video (Tự động VEO & Nano Banana):** Tạo video chất lượng cao từ mô tả văn bản.
* **🎬 Khung hình thành Video (Ảnh thành Video):** Chuyển đổi hình ảnh tĩnh thành video động với các prompt điều khiển chuyển động.
* **🎬 Thành phần thành Video (Components-to-Video):** Tạo chuyển động cho các thành phần giao diện người dùng và bố cục. Hỗ trợ tải lên tối đa **3 hình ảnh** cho mỗi prompt.
* **🖼️ Tạo hàng loạt Văn bản thành Ảnh:** Tạo nhiều ảnh chất lượng cao với tỷ lệ khung hình tùy chỉnh (16:9, 9:16, 1:1, 2:3, 3:2).
* **🎙️ Văn bản thành Giọng nói:** Chuyển đổi các đoạn văn bản kịch bản thành các bản thu âm giọng nói với cài đặt chất lượng tải xuống tùy chọn.
* **⚙️ Điều khiển chuyên nghiệp:**
    * **Khoảng chờ Prompt:** Thiết lập thời gian chờ tối thiểu và tối đa giữa các prompt để quản lý giới hạn tốc độ.
    * **Tự động tải xuống:** Tự động tải xuống các tài nguyên được tạo (video, ảnh, hoặc âm thanh) ở chất lượng cao khi hoàn thành.
    * **Giới hạn số đầu ra:** Hỗ trợ tối đa 1 tệp đầu ra cho mỗi prompt để tối ưu hóa hiệu suất.
* **📊 Giám sát hàng đợi thời gian thực:** Theo dõi các tác vụ hàng loạt với thanh tiến trình và danh sách prompt đang hoạt động trong Side Panel.
* **📂 Quản lý thư mục tải xuống:** Các tệp tự động tải xuống được lưu trữ khoa học theo các thư mục con dự án.
* **🌐 Đa ngôn ngữ:** Tiếng Anh, Tiếng Việt, Tiếng Trung, Tiếng Hàn, Tiếng Nhật, Tiếng Tây Ban Nha.

-----

## 📥 Cài đặt

### Cách 1: Cửa hàng Chrome trực tuyến (Khuyên dùng)
1. Truy cập [Cửa hàng Chrome trực tuyến](https://chromewebstore.google.com/detail/vids-automation-auto-veo/caiompjhmpmodfbfdbihlkbbeijgpial)
2. Nhấn **Thêm vào Chrome**.

### Cách 2: Chế độ nhà phát triển cục bộ
1. Tải xuống hoặc clone repository này về máy tính của bạn.
2. Mở Google Chrome và truy cập `chrome://extensions/`.
3. Bật công tắc **Chế độ dành cho nhà phát triển** ở góc trên cùng bên phải.
4. Nhấp vào **Tải tiện ích đã giải nén** và chọn thư mục bản dựng extension (`dist/chrome`).

-----

## 📖 Hướng dẫn sử dụng

### Bắt đầu

1. **Truy cập Google Vids**
   - Mở [docs.google.com/videos](https://docs.google.com/videos)
   - Đảm bảo bạn đã đăng nhập vào Tài khoản Google của mình.

2. **Mở tiện ích**
   - Nhấp vào biểu tượng tiện ích trên thanh công cụ Chrome. Ghim tiện ích để truy cập nhanh!

3. **Cấu hình hàng loạt**
   - Trong tab **Điều khiển**, bạn có thể thiết lập **Thời gian chờ prompt** (thời gian chờ tối thiểu/tối đa giữa các lần gửi prompt).

4. **Chọn chế độ**
   - Chọn: **Văn bản thành Video**, **Khung hình thành Video**, **Thành phần thành Video**, **Văn bản thành Ảnh**, hoặc **Văn bản thành Giọng nói**.

### 1. Chế độ Văn bản thành Video

1. Chọn chế độ **Văn bản thành Video**.
2. Nhập các prompt vào ô nhập liệu (tách biệt mỗi prompt bằng một **dòng trống**).
3. Ngoài ra, nhấp vào nút **Tải lên** để nhập prompt từ file `.txt` hoặc bảng tính `.xlsx` / `.csv`.
4. Nhấp vào **Chạy** để bắt đầu xử lý hàng loạt.

**Ví dụ Prompt:**
```
Một thành phố cyberpunk tương lai với ánh đèn neon phản chiếu trong mưa.
Camera lướt qua các con hẻm hẹp.

Một khu vườn Nhật Bản yên bình với hoa anh đào rơi xuống ao.
Camera zoom chậm vào những con cá koi đang bơi bên dưới.
```

### 2. Chế độ Khung hình thành Video

1. Chọn chế độ **Khung hình thành Video**.
2. Kéo & thả hoặc tải lên ảnh bắt đầu.
3. Nhập prompt mô tả chuyển động (tách biệt bằng các dòng trống).
4. Nhấp **Chạy**.

### 3. Chế độ Thành phần thành Video

1. Chọn chế độ **Thành phần thành Video**.
2. Tải lên các khung hình ảnh thành phần (hỗ trợ tối đa **3 ảnh** cho mỗi prompt).
3. Nhập các prompt mô tả chi tiết cách chuyển động của các thành phần.
4. Nhấp **Chạy**.

### 4. Chế độ Văn bản thành Ảnh

1. Chọn chế độ **Văn bản thành Ảnh**.
2. Nhập các prompt chi tiết ngăn cách bằng dòng trống.
3. Chọn cấu hình **Tỷ lệ khung hình** và **Mô hình ảnh** trong tab Cài đặt.
4. Nhấp **Chạy**.

### 5. Chế độ Văn bản thành Giọng nói

1. Chọn chế độ **Văn bản thành Giọng nói**.
2. Nhập các đoạn kịch bản giọng nói ngăn cách bằng dòng trống.
3. Nhấp **Chạy**.
4. Trong tab Cài đặt, bạn có thể tùy chỉnh liên kết giọng nói mặc định (`defaultAudioOption`) và tùy chọn tải xuống âm thanh.

---

## ⚙️ Cấu hình Cài đặt

Truy cập tab **Cài đặt** để tùy chỉnh quy trình tự động hóa của bạn:

* **Chế độ mặc định:** Thiết lập tab hiển thị mặc định khi mở tiện ích.
* **Tỷ lệ khung hình:** Chọn tỷ lệ khung hình mặc định (16:9, 9:16, 1:1, 2:3, 3:2).
* **Tùy chọn Video mặc định:** Cấu hình thời lượng mặc định (5s hoặc 5s-concat).
* **Tùy chọn Hình ảnh mặc định:** Chế độ đầu vào mặc định cho prompt ảnh (Tạo mới hoặc Chỉnh sửa ảnh).
* **Tùy chọn Âm thanh mặc định:** Chế độ mặc định cho prompt âm thanh (Tạo mới hoặc Kết hợp âm thanh).
* **Tự động tải xuống chất lượng Video:** Chọn độ phân giải tải xuống (Không tải xuống, 480p, 480p-upscale, 720p).
* **Tự động tải xuống chất lượng Hình ảnh:** Chọn độ phân giải ảnh (Không tải xuống, 1k).
* **Tự động tải xuống chất lượng Âm thanh:** Chọn định dạng âm thanh (Không tải xuống, Mp3 chất lượng gốc).
* **Tự động thay đổi tên tệp:** Tự động đổi tên tệp để phù hợp với thư mục và tiền tố.
* **Tên thư mục:** Xác định một thư mục con trong thư mục Tải xuống của bạn để sắp xếp gọn gàng các tệp.
* **Số lần thử lại tối đa:** Thiết lập số lần tự động thử lại khi gặp lỗi trong quá trình tạo.

---

## 💡 Mẹo & Thực hành tốt nhất

1. **Chờ thông minh:** Nếu bạn gặp phải giới hạn tốc độ hoặc bị chặn tạo, hãy tăng dải **Thời gian chờ prompt**.
2. **Cấu hình tải xuống:** Đảm bảo bạn đã tắt tùy chọn hỏi vị trí lưu của Chrome (xem bên dưới) để cho phép các tệp tự động tải xuống.
3. **Quản lý thư mục:** Luôn xác định một **Tên thư mục** tùy chỉnh trong tab Cài đặt trước khi chạy hàng loạt số lượng lớn để tránh làm lộn xộn thư mục Tải xuống mặc định của bạn.

---

## 🔧 Khắc phục sự cố

| Vấn đề | Giải pháp |
| :--- | :--- |
| **Tiện ích không hoạt động** | Đảm bảo bạn đang ở [docs.google.com/videos](https://docs.google.com/videos). Tải lại trang nếu cần thiết. |
| **Hiện hộp thoại hỏi nơi lưu tệp** | Trong Cài đặt Chrome -> Tải xuống, **Tắt** tùy chọn "Hỏi vị trí lưu từng tệp trước khi tải xuống". |
| **Lỗi khi tạo** | Google Vids có thể bị nghẽn. Tiện ích sẽ tự động thử lại prompt tối đa theo số **Số lần thử lại tối đa** đã định cấu hình. |
| **Yêu cầu đăng nhập** | Đảm bảo bạn đã đăng nhập vào Tài khoản Google hoặc Workspace đang hoạt động có quyền truy cập Google Vids. |

---

## 🔒 Quyền riêng tư & Dữ liệu

* **Xử lý tại chỗ:** Mọi lệnh tự động hóa đều được thực thi cục bộ trên trình duyệt của bạn.
* **Không thu thập dữ liệu:** Chúng tôi không thu thập, lưu trữ hoặc giám sát prompt, hình ảnh hoặc cấu hình tài khoản của bạn.
* **Lưu trữ an toàn:** Cài đặt được lưu trực tiếp bên trong công cụ lưu trữ cục bộ của Chrome.

---

## 📞 Hỗ trợ

- **Tác giả:** Trường Nguyễn
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Phản hồi:** Sử dụng liên kết "Báo lỗi" trong tiện ích.

---

## 📦 Phiên bản

Phiên bản hiện tại: **1.0.0**

---

## 📜 Bản quyền

Bản quyền © 2026 **Trường Nguyễn**. Bảo lưu mọi quyền.

Phần mềm này là tài sản riêng. Nghiêm cấm sao chép hoặc phân phối trái phép.

---

**Được thực hiện với ❤️ bởi Trường Nguyễn**

[![Tải tại đây](https://img.shields.io/badge/⬇_Tải-Tại_Đây-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vids-automation-auto-veo/caiompjhmpmodfbfdbihlkbbeijgpial)

# 🚀 Vids Automation v1.0.0 - Tự động hóa Google Vids AI [![English](https://img.shields.io/badge/English-blue)](README.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Vids Automation** là tiện ích mở rộng giúp tự động hóa quy trình sáng tạo của bạn trên Google Vids (docs.google.com/videos). Dừng việc nhập từng prompt thủ công—tự động hóa quy trình và tạo video, hình ảnh và giọng nói (voice-over) ở quy mô lớn.

-----

## ✨ Các tính năng chính

* **🚀 Xử lý hàng loạt:** Xếp hàng hàng chục hoặc hàng trăm prompt và để tiện ích tự động gửi và tạo nội dung trên Google Vids.
* **🧩 Workflow (giao diện kéo thả trực quan):** Nối prompt, ảnh và các bước tạo trên một bảng vẽ — ví dụ tạo ảnh rồi tự động dùng chính ảnh đó để tạo video. Lưu nhiều workflow, chạy từng node hoặc chạy tất cả, nhập/xuất workflow thành file.
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

### 🧩 Workflow (Giao diện kéo thả trực quan)

Workflow là giao diện kéo thả trực quan cho các quy trình nhiều bước — ví dụ: tạo vài ảnh, dùng chính các ảnh đó để tạo video, rồi nối tiếp mỗi video bằng một prompt khác. Workflow mở trong cửa sổ riêng và chạy trên tab Google Vids bạn đang mở.

#### Mở Workflow

* Nhấn **Workflow** trong tab Điều khiển (hàng nút dưới cùng).
* Đã nhập prompt hoặc tải ảnh ở side panel? Rê chuột vào **Workflow** rồi nhấn **Chuyển sang workflow**: prompt, chế độ của từng prompt và ảnh sẽ thành các node trong workflow, sẵn sàng để chạy.

#### Màn hình

| Khu vực | Gồm những gì |
| :--- | :--- |
| **Bên trái** | **Node** (bấm hoặc kéo vào bảng vẽ) và **Workflow của bạn** (danh sách workflow đã lưu) |
| **Thanh trên cùng** | Công cụ bảng vẽ: Hoàn tác/Làm lại, **Tự sắp xếp**, vừa khung nhìn, **Ví dụ**, xoá. Bên phải: nút **Chi tiết**, **Phím tắt** và trạng thái tab Google Vids |
| **Bảng vẽ** | Các node của bạn. Góc trên trái: **Chạy tất cả** (và **Dừng** khi đang chạy) và **Bật chạy nền** |

Nút **Chi tiết** cho biết điều cần chú ý: **Vấn đề (n)** màu đỏ/vàng khi có gì chặn việc chạy, **Đang chạy 3/8** khi đang tạo. Bấm vào để mở bảng gồm các vấn đề (bấm một vấn đề để nhảy tới node), tiến độ, kế hoạch chạy và cài đặt đang dùng.

#### Các loại node

| Node | Chức năng |
| :--- | :--- |
| **Nhập prompt** | Một hoặc nhiều prompt, tách nhau bằng **dòng trống** |
| **Tải ảnh lên** | Ảnh của bạn (thả file vào node). Rê chuột vào ảnh: 🔍 để xem lớn, ✕ để xoá, nút kéo ở góc để đổi thứ tự. Thứ tự (hoặc menu sắp xếp) quyết định prompt nào nhận ảnh nào |
| **Tạo ảnh** | Văn bản thành Hình ảnh, hoặc Hình ảnh thành Hình ảnh khi có ảnh nối vào. Tuỳ chọn: **Chế độ ảnh theo prompt**, **Số ảnh đầu vào tối đa mỗi Prompt**, **Tự động thêm ảnh nhân vật** |
| **Tạo video** | Văn bản thành Video, hoặc khi có ảnh nối vào: **Khung hình thành Video** / **Thành phần thành Video**. Tuỳ chọn: **Chế độ video theo prompt**, số ảnh mỗi prompt (dùng chung cài đặt với side panel), **Tự động thêm ảnh nhân vật** (Thành phần thành Video) |

Node Tạo ảnh / Tạo video tự đặt tên theo prompt đầu tiên (`image_…` / `video_…`). Mỗi dòng prompt hiển thị các ảnh mà prompt đó sẽ nhận, để bạn kiểm tra trước khi chạy. Khung xem trước theo **tỉ lệ khung hình** trong cài đặt (node 9:16 hẹp và cao hơn).

#### Nối các node

Kéo từ chấm tròn bên phải của một node và **thả vào bất kỳ chỗ nào trên node kia** — cổng phù hợp sẽ được chọn tự động. Trong lúc kéo, node nào nối được sẽ sáng viền.

| Từ | Đến | Ý nghĩa |
| :--- | :--- | :--- |
| Nhập prompt | Tạo ảnh / Tạo video | Các prompt cần tạo |
| Tải ảnh lên | Tạo ảnh / Tạo video | Ảnh tham chiếu, khung hình bắt đầu hoặc thành phần |
| Tạo ảnh | Tạo ảnh / Tạo video | **Ảnh vừa tạo** trở thành ảnh đầu vào của node đó (node đó chạy khi ảnh đã sẵn sàng) |
| Tạo video — cổng **khung cuối** | Tạo video | Video sau **nối tiếp từ khung hình cuối** của video trước |
| Tạo video — cổng **khung cuối** | Tạo ảnh | **Khung hình cuối** của mỗi video trở thành ảnh đầu vào (chạy khi video đã sẵn sàng) |

#### Chạy

* **Chạy tất cả** (góc trên trái, hoặc `Ctrl/⌘ + Enter`) chạy cả workflow theo đúng thứ tự: node nào cần ảnh được tạo sẽ tự chạy khi ảnh đã có.
* Nếu **Chạy tất cả** bị khoá, thanh trên cùng hiện **Vấn đề (n)**: bấm vào để xem cần sửa gì.
* Mỗi node Tạo ảnh / Tạo video có nút **Chạy** riêng để chỉ chạy node đó. Nút bị khoá cho tới khi các node nó phụ thuộc chạy xong (rê chuột để xem lý do).
* **Dừng** huỷ những gì đang chạy.
* Khi đang chạy, các đường nối vào node đang tạo sẽ sáng lên và có dòng chảy, để bạn thấy workflow đang ở bước nào.

> ⚠️ **Chrome tạm dừng Google Vids khi tab không hiển thị** (ví dụ cửa sổ workflow che toàn màn hình). Nhấn **Bật chạy nền** (ngay dưới **Chạy tất cả** trong workflow, hoặc ở side panel), rồi chọn tab Google Vids trong hộp thoại của Chrome. Việc này chia sẻ tab Google Vids (không ghi lại hay gửi đi đâu) để Google Vids tiếp tục tạo khi bị cửa sổ khác che. Nhãn xanh **Đang chạy nền** cho biết đã bật; nhấn ✕ để tắt.

#### Kết quả

Kết quả hiện ngay trong node Tạo ảnh / Tạo video. Rê chuột vào kết quả: 🔍 để xem lớn, ✕ để xoá (nút cục tẩy xoá toàn bộ kết quả của node). Video tự phát khi rê chuột. File vẫn được tải xuống như bình thường.

Node phía sau dùng **kết quả đầu tiên của mỗi prompt**. Muốn chọn kết quả khác, kéo nút ở góc trên trái của một kết quả thả lên kết quả khác để đổi chỗ (ảnh và video).

#### Quản lý workflow

Trong **Workflow của bạn** (bên trái): **Tạo mới**, **Nhập**, và menu **⋯** của từng workflow — **Đổi tên** (hoặc bấm đúp vào tên), **Nhân bản**, **Xuất file**, **Xoá**. Mọi thay đổi được lưu tự động.

* **Xuất file** tải về file `.json`. Đầu file có các dòng chú thích `//` mô tả mọi node, thuộc tính và cách nối, nên bạn có thể đưa file cho trợ lý AI và nhờ AI viết workflow mới. Các dòng `//` được bỏ đi khi nhập.
* **Nhập** file bằng nút Nhập, hoặc đơn giản **kéo file `.json` thả vào bảng vẽ**.

#### Phím tắt khi chỉnh sửa

Nhấn **Phím tắt** trên thanh trên cùng (hoặc phím `?`) để xem tất cả.

| Thao tác | Phím |
| :--- | :--- |
| Hoàn tác / Làm lại | `Ctrl/⌘ + Z` / `Ctrl/⌘ + Shift + Z` |
| Sao chép / Cắt / Dán node (dán được sang workflow khác) | `Ctrl/⌘ + C / X / V` |
| Nhân bản phần đang chọn | `Ctrl/⌘ + D` |
| Chọn tất cả / Chọn thêm / Quét chọn | `Ctrl/⌘ + A` / `Ctrl/⌘ + bấm` / `Shift + kéo` |
| Tự sắp xếp | `Shift + A` |
| Xoá phần đang chọn | `Delete` |
| Chạy tất cả / Chạy nền | `Ctrl/⌘ + Enter` / `Ctrl/⌘ + Shift + Enter` |

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
| **Workflow: kết quả đứng mãi ở "Đang tạo"** | Chrome đã tạm dừng tab Google Vids bị che. Bật **Bật chạy nền** (hoặc **Chạy nền**), hoặc để tab Google Vids hiển thị. |
| **Workflow: nút Chạy của một node bị mờ** | Rê chuột vào nút: chạy node mà nó phụ thuộc trước, hoặc sửa vấn đề được báo (ví dụ chưa nối prompt). |
| **Workflow: Chạy tất cả bị khoá** | Bấm **Vấn đề (n)** trên thanh trên cùng để xem cần sửa gì; bấm một vấn đề để nhảy tới node đó. |
| **Workflow: "Không tìm thấy tab Google Vids"** | Mở [Google Vids](https://docs.google.com/videos) trong một tab (chấm xanh trên thanh trên cùng cho biết đã kết nối). |

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

[![Tải tại đây](https://img.shields.io/badge/⬇_Tải-Tại_Đây-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab)

# 🚀 Vibes Automation v1.0.9 - Tự động hóa Vibes.ai AI [![English](https://img.shields.io/badge/English-blue)](README.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Vibes Automation** là một tiện ích Chrome mạnh mẽ được thiết kế để tự động hóa hoàn toàn việc tạo video và hình ảnh hàng loạt trên nền tảng **Vibes.ai**. Tiện ích cho phép bạn chạy nhiều prompt ở quy mô lớn, xây dựng và tùy chỉnh các quy trình nâng cao, và tự động tải xuống nội dung được tạo ra — tất cả với nỗ lực thủ công tối thiểu.

-----

## ✨ Các tính năng chính

* **🚀 Xử lý hàng loạt:** Xếp hàng hàng chục hoặc hàng trăm prompt và để tiện ích tự động gửi và tạo nội dung.
* **🧩 Workflow (giao diện kéo thả trực quan):** Nối prompt, ảnh và các bước tạo trên một bảng vẽ — ví dụ tạo ảnh rồi tự động dùng chính ảnh đó để tạo video. Lưu nhiều workflow, chạy từng node hoặc chạy tất cả, nhập/xuất workflow thành file.
* **🎬 Tự động Văn bản thành Video:** Tạo video từ mô tả văn bản. Hỗ trợ xử lý hàng loạt với thời gian chờ tùy chỉnh.
* **🎬 Khung hình thành Video (Frame-to-Video):** Sử dụng một ảnh tĩnh (Ảnh bắt đầu, hoặc Ảnh bắt đầu + Ảnh kết thúc) và các prompt để tạo video động với các hiệu ứng chuyển động tự động.
* **🎬 Thành phần thành Video (Ingredients-to-Video):** Tạo chuyển động cho các thành phần UI, lớp nhân vật hoặc ảnh tham chiếu thành video. Hỗ trợ tải lên nhiều ảnh (lên đến 10 ảnh).
* **🖼️ Tạo hàng loạt Văn bản thành Ảnh:** Tạo nhiều ảnh với tỷ lệ khung hình phong phú: 16:9 (YouTube), 9:16 (Shorts/Reels), 1:1 (Square), 2:3 (Portrait), 3:2 (Landscape).
* **🖼️ Ảnh thành Ảnh:** Biến đổi và nâng cao hình ảnh bằng AI dựa trên các mô tả văn bản.
* **⚙️ Điều khiển chuyên nghiệp:**
    * **Prompt đồng thời (Concurrent Prompts):** Xử lý nhiều prompt cùng lúc để tiết kiệm thời gian.
    * **Thời gian chờ ngẫu nhiên (Random Delays):** Thiết lập khoảng thời gian chờ ngẫu nhiên giữa các prompt để quản lý giới hạn tốc độ và mô phỏng hành vi của con người.
    * **Chất lượng tự động tải xuống:** Tự động tải kết quả khi tạo xong. Hỗ trợ tùy chọn chất lượng video (480p, 720p hoặc không tải) và chất lượng ảnh (1k hoặc không tải).
    * **Tự động thêm ảnh nhân vật (Auto-add Character Images):** Tự động khớp và đính kèm các hình ảnh đã tải lên tương ứng với tên nhân vật được nhắc đến trong prompt (khớp dựa trên tên tệp).
    * **Liên kết thông minh & Nối Video:** Nối các prompt lại với nhau: sử dụng chế độ "5s concat" để tự động kết hợp các lần tạo liên tiếp thành một video, hoặc "Sửa ảnh" để tái sử dụng đầu ra trước đó làm đầu vào cho prompt tiếp theo.
* **📊 Giám sát hàng đợi thời gian thực:** Theo dõi tiến trình với thanh trạng thái trực quan, danh sách prompt đang hoạt động và nhật ký chi tiết trong Side Panel.
* **📂 Quản lý tệp ngăn nắp:** Tải xuống được tự động sắp xếp vào các thư mục con theo tên dự án.
* **🌐 Đa ngôn ngữ:** Tiếng Anh, Tiếng Tây Ban Nha, Tiếng Nhật, Tiếng Hàn, Tiếng Việt, Tiếng Trung.

-----

## 📥 Cài đặt

### Cách 1: Cửa hàng Chrome trực tuyến (Khuyên dùng)
1. Truy cập [Cửa hàng Chrome trực tuyến](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab) và nhấn **Thêm vào Chrome**.

---

## 📖 Hướng dẫn sử dụng

### Bắt đầu

1. **Truy cập Vibes.ai**
   - Mở [vibes.ai/projects](https://www.vibes.ai/projects) (hoặc [vibes.ai](https://vibes.ai))
   - Tiện ích hoạt động trên các trang quản lý dự án/không gian làm việc của Vibes.ai.

2. **Mở tiện ích**
   - Nhấn biểu tượng tiện ích trên thanh công cụ Chrome. Ghim tiện ích để truy cập nhanh hơn!

3. **Cấu hình hàng loạt**
   - Trong tab **Điều khiển (Control)**, bạn có thể thiết lập:
     - **Save to folder:** Tên thư mục con bên trong thư mục Tải xuống của Chrome dành cho dự án này.
     - **Auto change file name:** Tự động đổi tên các tệp đã tải xuống theo thứ tự (ví dụ: `001_prompt_a.mp4`).
   - Trong tab **Cài đặt (Setting)**, cấu hình:
     - **Concurrent Prompts:** Số lượng prompt được xử lý đồng thời.
     - **Random Delay:** Khoảng thời gian chờ ngẫu nhiên giữa các lần gửi prompt.
     - **Auto Download Quality:** Thiết lập chất lượng video (480p/720p) hoặc ảnh (1k).

4. **Chọn chế độ**
   - Chọn một trong các chế độ: **Text to Video** (Văn bản thành Video), **Frame to Video** (Khung hình thành Video), **Ingredients to Video** (Thành phần thành Video), **Text to Image** (Văn bản thành Ảnh), hoặc **Image to Image** (Ảnh thành Ảnh).

---

### 1. Chế độ Văn bản thành Video (Text-to-Video)

1. Chọn chế độ **Text to Video**.
2. Nhập các prompt vào ô nhập liệu (tách biệt mỗi prompt bằng một **dòng trống**).
3. Hoặc nhấn biểu tượng **Tải lên** để nhập danh sách prompt từ file `.txt`, `.xlsx`, hoặc `.csv`.
4. Nhấn **Run** để bắt đầu chạy hàng loạt.

**Ví dụ Prompt:**
```
Một thành phố cyberpunk tương lai với ánh đèn neon phản chiếu dưới cơn mưa.
Camera lướt qua các con hẻm hẹp.

Một khu vườn Nhật Bản yên bình với hoa anh đào rơi xuống ao.
Camera zoom chậm vào những chú cá koi đang bơi bên dưới.
```

### 2. Chế độ Khung hình thành Video (Frame-to-Video)

1. Chọn chế độ **Frame to Video**.
2. Nhấn để tải lên hoặc kéo & thả một hoặc hai ảnh tĩnh (Ảnh bắt đầu / Ảnh kết thúc dựa trên Cài đặt).
3. Nhập các prompt (tách biệt bằng dòng trống). Ảnh được tải lên sẽ được xử lý kết hợp với từng prompt.
4. Nhấn **Run**.

### 3. Chế độ Thành phần thành Video (Ingredients-to-Video)

1. Chọn chế độ **Ingredients to Video**.
2. Tải lên các thành phần giao diện, lớp nhân vật hoặc ảnh tham chiếu (tối đa 10 ảnh).
3. Nhập prompt mô tả chi tiết các hành động và chuyển động trong cảnh.
4. (Tùy chọn) Bật **Auto-add character images** để tự động đính kèm ảnh nhân vật khớp với tên nhân vật được nhắc đến trong prompt (khớp theo tên file ảnh).
5. Nhấn **Run**.

### 4. Chế độ Văn bản thành Ảnh (Text-to-Image)

1. Chọn chế độ **Text to Image**.
2. Nhập mô tả chi tiết cho hình ảnh của bạn (ngăn cách bằng dòng trống).
3. Cấu hình **Tỷ lệ khung hình** mong muốn (16:9, 9:16, 1:1, 2:3, 3:2) và **Số đầu ra mỗi prompt** trong tab Cài đặt.
4. Nhấn **Run**.

### 5. Chế độ Ảnh thành Ảnh (Image-to-Image)

1. Chọn chế độ **Image to Image**.
2. Tải lên một hoặc nhiều ảnh nguồn.
3. Nhập prompt để tạo ra các biến thể hoặc nâng cấp hình ảnh.
4. Nhấn **Run**.

### 🧩 Workflow (Giao diện kéo thả trực quan)

Workflow là giao diện kéo thả trực quan cho các quy trình nhiều bước — ví dụ: tạo vài ảnh, dùng chính các ảnh đó để tạo video, rồi nối tiếp mỗi video bằng một prompt khác. Workflow mở trong cửa sổ riêng và chạy trên tab vibes.ai bạn đang mở.

#### Mở Workflow

* Nhấn **Workflow** trong tab Điều khiển (hàng nút dưới cùng).
* Đã nhập prompt hoặc tải ảnh ở side panel? Rê chuột vào **Workflow** rồi nhấn **Chuyển sang workflow**: prompt, chế độ của từng prompt và ảnh sẽ thành các node trong workflow, sẵn sàng để chạy.

#### Màn hình

| Khu vực | Gồm những gì |
| :--- | :--- |
| **Bên trái** | **Node** (bấm hoặc kéo vào bảng vẽ) và **Workflow của bạn** (danh sách workflow đã lưu) |
| **Thanh trên cùng** | Công cụ bảng vẽ: Hoàn tác/Làm lại, **Tự sắp xếp**, vừa khung nhìn, **Ví dụ**, xoá. Bên phải: nút **Chi tiết**, **Phím tắt** và trạng thái tab vibes.ai |
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

**Khung hình thành Video** có thể chỉ dùng khung hình đầu, hoặc **khung hình đầu và khung hình cuối** (dùng chung cài đặt với side panel). Với khung đầu và khung cuối, mỗi prompt lấy 2 ảnh theo thứ tự (prompt nối tiếp video trước lấy 1 ảnh); nếu không đủ ảnh, node hiện cảnh báo và không chạy được.

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

> ⚠️ **Chrome tạm dừng vibes.ai khi tab không hiển thị** (ví dụ cửa sổ workflow che toàn màn hình). Nhấn **Bật chạy nền** (ngay dưới **Chạy tất cả** trong workflow, hoặc ở side panel), rồi chọn tab vibes.ai trong hộp thoại của Chrome. Việc này chia sẻ tab vibes.ai (không ghi lại hay gửi đi đâu) để vibes.ai tiếp tục tạo khi bị cửa sổ khác che. Nhãn xanh **Đang chạy nền** cho biết đã bật; nhấn ✕ để tắt.

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

Truy cập tab **Cài đặt (Setting)** để tùy chỉnh trải nghiệm của bạn:

* **Default Mode:** Thiết lập chế độ mở mặc định khi khởi động.
* **Default Aspect Ratio:** Chọn tỷ lệ khung hình mặc định (16:9, 9:16, 1:1, 2:3, hoặc 3:2).
* **Outputs per Prompt:** Số video tạo ra cho mỗi prompt (tối thiểu 1, tối đa 4).
* **Outputs Image per Prompt:** Số ảnh tạo ra cho mỗi prompt (tối thiểu 1, tối đa 50).
* **Concurrent Prompts:** Số lượng prompt xử lý song song (từ 1 đến 6).
* **Random Delay:** Thiết lập thời gian chờ ngẫu nhiên giữa các prompt để tránh giới hạn tần suất.
* **Video/Image Model:** Chọn mô hình AI thế hệ tiếp theo được sử dụng để tạo.
* **Default Video Option:** Chọn thời lượng video mặc định là "5 seconds" hoặc "5 seconds (concat)".
* **Default Image Option:** Chọn giữa "New Image" (Ảnh mới) hoặc "Edit Image" (Sửa ảnh từ đầu ra trước đó).
* **Max Retries on Failure:** Số lần thử lại tối đa (1 đến 20) nếu tiến trình tạo thất bại.
* **Auto Download Quality:** Cài đặt chất lượng tải xuống tự động cho video (480p/720p/không tải) hoặc ảnh (1k/không tải).
* **Language:** Chuyển đổi ngôn ngữ hiển thị (English, Tiếng Việt, 中文, 한국어, 日本語, Español).

---

## 💡 Mẹo & Thực hành tốt nhất

1. **Giới hạn Tốc độ (Rate Limits):** Nếu bạn gặp phải giới hạn tốc độ hoặc lỗi hệ thống, hãy tăng **Random Delay** trong tab Cài đặt và giảm số **Concurrent Prompts** xuống còn 1.
2. **Nhập từ bảng tính:** Khi tải lên bảng tính (`.xlsx`/`.csv`), bạn có thể xem trước các hàng và chọn chính xác cột chứa prompt cần nhập.
3. **Liên kết Nối tiếp thông minh:** Sử dụng chế độ "5s concat" cho video hoặc "Sửa ảnh" (Edit Image) cho chuỗi ảnh để tạo cốt truyện liên tục hoặc các biến thể tiến trình liên tiếp.
4. **Đổi tên tệp:** Luôn chọn **Auto change file name** để các tệp tải xuống được đánh số rõ ràng theo thứ tự thời gian (ví dụ: `001_...`, `002_...`).

---

## 🔧 Khắc phục sự cố

| Vấn đề | Giải pháp |
| :--- | :--- |
| **Tiện ích không hoạt động** | Đảm bảo bạn đang ở trang [vibes.ai](https://vibes.ai) hoặc [vibes.ai/projects](https://www.vibes.ai/projects). Tải lại trang nếu cần. |
| **Lỗi kết nối** | Nhấn F5 / Ctrl+R để tải lại trang. Mở lại bảng side panel của tiện ích. |
| **Lỗi trong quá trình tạo** | Tiện ích sẽ tự động thử lại các prompt bị lỗi theo số lần tối đa được cấu hình trong **Max Retries**. Nhấn **Fix Error** để thiết lập lại nhanh nếu bị kẹt. |
| **Tải xuống không hoạt động** | Đảm bảo tùy chọn "Hỏi nơi lưu từng tệp trước khi tải xuống" đã được **TẮT** trong cài đặt Chrome (`chrome://settings/downloads`). |
| **Yêu cầu đăng nhập** | Đảm bảo bạn đã đăng nhập vào tài khoản Vibes.ai trên trang web và tài khoản gói Max trong tiện ích mở rộng. |
| **Workflow: kết quả đứng mãi ở "Đang tạo"** | Chrome đã tạm dừng tab vibes.ai bị che. Bật **Bật chạy nền** (hoặc **Chạy nền**), hoặc để tab vibes.ai hiển thị. |
| **Workflow: nút Chạy của một node bị mờ** | Rê chuột vào nút: chạy node mà nó phụ thuộc trước, hoặc sửa vấn đề được báo (ví dụ chưa nối prompt). |
| **Workflow: Chạy tất cả bị khoá** | Bấm **Vấn đề (n)** trên thanh trên cùng để xem cần sửa gì; bấm một vấn đề để nhảy tới node đó. |
| **Workflow: "Không tìm thấy tab vibes.ai"** | Mở [vibes.ai](https://vibes.ai) trong một tab (chấm xanh trên thanh trên cùng cho biết đã kết nối). |

---

## 🔒 Quyền riêng tư & Dữ liệu

* **Xử lý tại chỗ:** Toàn bộ logic tự động hóa được xử lý cục bộ ngay trên trình duyệt của bạn.
* **Không thu thập dữ liệu:** Chúng tôi không lưu trữ hoặc thu thập bất kỳ prompt, hình ảnh hay thông tin tài khoản nào.
* **Lưu trữ an toàn:** Các cài đặt chỉ được lưu trữ trong bộ nhớ cục bộ/đồng bộ của trình duyệt của bạn.

---

## 📞 Hỗ trợ

- **Tác giả:** Trường Nguyễn
- **Email:** kylenguyenaws@gmail.com
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Phản hồi:** Sử dụng liên kết "Report Bug" trong tab tiện ích để sao chép nhật ký gỡ lỗi (debug logs) và liên hệ hỗ trợ.

---

## 📦 Phiên bản

Phiên bản hiện tại: **1.0.9**

---

## 📜 Bản quyền

Bản quyền © 2026 **Trường Nguyễn**. Bảo lưu mọi quyền.

Phần mềm này là tài sản riêng. Nghiêm cấm sao chép hoặc phân phối trái phép dưới mọi hình thức.

---

**Được thực hiện với ❤️ bởi Trường Nguyễn**

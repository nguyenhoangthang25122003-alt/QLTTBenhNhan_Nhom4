# 🏥 MedCare – Ứng Dụng Quản Lý Thông Tin Bệnh Nhân

> Đồ án môn học | Nhóm 4 – Quản Lý Thông Tin Bệnh Nhân (QLTTBN)

---

## 📌 Giới thiệu

**MedCare** là ứng dụng web mô phỏng giao diện mobile để quản lý thông tin bệnh nhân tại cơ sở y tế. Ứng dụng được xây dựng bằng HTML, CSS và JavaScript thuần (Vanilla JS), không cần cài đặt backend hay framework.

Toàn bộ ứng dụng chạy trong **một file HTML duy nhất**, phù hợp để demo, báo cáo và học tập.

---

## 🖼️ Giao diện

Ứng dụng hiển thị dưới dạng **phone mockup** (mô phỏng màn hình điện thoại iPhone), bao gồm 4 màn hình chính điều hướng qua thanh tab phía dưới.

---

## ✨ Tính năng

### 👤 Quản lý Bệnh Nhân
- Thêm, chỉnh sửa, xóa thông tin bệnh nhân
- Thông tin chi tiết: họ tên, ngày sinh, giới tính, số điện thoại, email, CCCD, BHYT, nhóm máu, địa chỉ, tiền sử bệnh, dị ứng thuốc
- Tìm kiếm theo tên, SĐT, mã bệnh nhân, CCCD
- Lọc theo trạng thái (Hoạt động / Vô hiệu) và giới tính
- Phân trang danh sách
- Xem hồ sơ chi tiết, bật/tắt trạng thái bệnh nhân

### 📅 Quản lý Lịch Hẹn
- Đặt lịch hẹn khám cho bệnh nhân
- Chọn bác sĩ, ngày giờ, lý do khám
- Cập nhật trạng thái lịch hẹn: Chờ / Hoàn thành / Huỷ
- Lọc lịch hẹn theo trạng thái và ngày
- Thống kê lịch hẹn theo ngày

### 📋 Hồ Sơ Bệnh Án
- Xem hồ sơ khám bệnh theo từng bệnh nhân
- Chi tiết chẩn đoán, đơn thuốc, bác sĩ phụ trách

### 📊 Báo Cáo & Thống Kê
- Biểu đồ số lượng bệnh nhân đăng ký theo tháng
- Biểu đồ phân bổ giới tính và nhóm máu
- Biểu đồ tình trạng lịch hẹn
- Sử dụng thư viện **Chart.js**

---

## 🗂️ Cấu trúc dự án

```
QLTTBN_Nhóm_4/
│
└── QLTTBN_Nhóm_4.html     # Toàn bộ ứng dụng (HTML + CSS + JS)
```

---

## 🚀 Hướng dẫn chạy

1. **Clone hoặc tải về** repository này
2. Mở file `QLTTBN_Nhóm_4.html` bằng trình duyệt (Chrome, Edge, Firefox...)
3. Không cần cài đặt thêm bất cứ thứ gì

```bash
# Hoặc clone về máy
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# Mở file HTML bằng trình duyệt
```

---

## 🛠️ Công nghệ sử dụng

| Công nghệ | Mục đích |
|-----------|----------|
| HTML5 | Cấu trúc giao diện |
| CSS3 | Thiết kế, responsive, animation |
| JavaScript (Vanilla) | Xử lý logic, quản lý dữ liệu |
| LocalStorage | Lưu trữ dữ liệu phía client |
| [Chart.js](https://www.chartjs.org/) | Vẽ biểu đồ thống kê |

---

## 💾 Lưu trữ dữ liệu

Ứng dụng sử dụng **localStorage** của trình duyệt để lưu trữ dữ liệu bệnh nhân và lịch hẹn. Dữ liệu sẽ được giữ lại sau khi tải lại trang, nhưng sẽ mất nếu xoá bộ nhớ trình duyệt.

Dữ liệu mẫu được tự động nạp vào lần đầu mở ứng dụng.

---

## 👥 Nhóm thực hiện

**Nhóm 4 – Môn Quản Lý Thông Tin Bệnh Nhân**

| STT | MSSV | Họ và Tên | Vai trò |
|-----|------|-----------|---------|
| 1 | 2174802010217 | Nguyễn Hoàng Thắng | _(Vai trò)_ |
| 2 | 2174802010203 | Trang Minh Hiếu | _(Vai trò)_ |
| 3 | 2274802011024 | Phạm Lê Anh Vũ | _(Vai trò)_ |

> ✏️ **Ghi chú:** Cập nhật vai trò từng thành viên nếu cần trước khi nộp.

---

## 📄 Giấy phép

Dự án được thực hiện cho mục đích học tập. Không sử dụng cho mục đích thương mại.

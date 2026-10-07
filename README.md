# B25DCTV021 - BT7: SPA & React

**Môn:** Lập trình Web  
**Sinh viên:** Vũ Khải Hoàn  
**MSSV:** B25DCTV021  

---

## Bài 1: Virtual Calculator

📂 Thư mục: `CAL/`

Ứng dụng máy tính đơn giản xây dựng bằng React.

### Các component:
- **Display** — hiển thị kết quả (props: `expression`, `value`)
- **Button** — nút bấm (props: `label`, `color`, `onClick`)
- **Calculator** — component chính, quản lý State

### Chức năng:
- Phép tính: `+`, `−`, `×`, `÷`
- Xóa: `C` (xóa tất cả), `⌫` (xóa ký tự cuối)
- Tính kết quả: `=`
- Phần trăm: `%`
- Hỗ trợ bàn phím

---

## Bài 2: Trang CV bằng React

📂 Thư mục: `GTBT/`

Trang giới thiệu bản thân chuyển từ HTML sang React với nhiều component.

### Các component (7 component):
- **Section** — dùng `children` để bọc nội dung
- **Hero** — phần giới thiệu đầu trang
- **InfoTable** — bảng thông tin cá nhân
- **HobbyList** — danh sách sở thích
- **SkillList** — danh sách kỹ năng
- **ProjectList** — danh sách dự án
- **SocialLinks** — liên kết mạng xã hội

### Dữ liệu:
- Đặt trong mảng và truyền qua props
- `personalInfo`, `hobbies`, `skills`, `projects`, `socialLinks`

---

## Công nghệ

- React 18 (CDN)
- Babel Standalone
- HTML / CSS / JavaScript
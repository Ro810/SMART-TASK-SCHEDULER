# 🚀 Smart Task Scheduler (Web + AI)

### Dự án Thực tập cơ sở - GVHD: Thầy Nguyễn Xuân Đức

## 📌 Giới thiệu
**Smart Task Scheduler** là một ứng dụng web quản lý công việc thông minh. Hệ thống sử dụng các thuật toán **AI (Heuristic Search/A*)** để tự động phân tích deadline và mức độ quan trọng, từ đó đề xuất lộ trình làm việc tối ưu nhất.

---

## 🛠 Công nghệ sử dụng (Tech Stack)
* **Backend:** Python (FastAPI / Flask)
* **Database:** SQL (PostgreSQL/MySQL) với SQLAlchemy ORM
* **AI Engine:** Thuật toán tìm kiếm Heuristic & Greedy
* **Frontend:** HTML5, CSS3 (Bootstrap 5), JavaScript

---

## ✨ Tính năng chính

### 1. Quản lý công việc (CRUD)
* Thêm, sửa, xóa và quản lý danh sách Task.
* Phân loại công việc theo danh mục (Học tập, Dự án, Cá nhân).
* Thiết lập sự phụ thuộc giữa các Task.

### 2. Bộ não AI (Smart Logic)
* **Auto-Prioritization:** Tự động tính điểm ưu tiên dựa trên Deadline và Importance.
* **Conflict Detection:** Cảnh báo nếu các task có deadline quá sát nhau.
* **Deadlock Prevention:** Phát hiện và ngăn chặn vòng lặp phụ thuộc.

---

## 📅 Nhật ký tiến độ (Weekly Progress)

| Tuần | Nội dung công việc | Trạng thái |
| :--- | :--- | :--- |
| **Tuần 01** | Khảo sát yêu cầu, vẽ sơ đồ Use Case và định nghĩa AI Heuristic. | ✅ Hoàn thành |
| **Tuần 02** | Thiết kế ERD và thực hiện chuẩn hóa dữ liệu 3NF. | ⏳ Đang làm |
| **Tuần 03** | Khởi tạo Backend và cấu trúc Database. | 📋 Kế hoạch |

---

## 🏗 Cấu trúc thư mục
```text
/
├── backend/            # Mã nguồn xử lý Logic & API
├── frontend/           # Giao diện người dùng
├── ai_engine/          # Thuật toán sắp xếp thông minh
├── docs/               # Sơ đồ ERD, Use Case và Báo cáo PDF
└── README.md           # Hướng dẫn và tiến độ dự án

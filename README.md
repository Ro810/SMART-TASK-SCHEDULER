🚀 Smart Task Scheduler (Web + AI)
Dự án Thực tập cơ sở - GVHD: Nguyễn Xuân Đức
📌 Giới thiệu
Smart Task Scheduler là một ứng dụng web quản lý công việc thông minh. Không chỉ dừng lại ở việc ghi chú, hệ thống sử dụng các thuật toán *AI (Heuristic Search/A)** để tự động phân tích deadline, mức độ quan trọng và thời gian thực hiện, từ đó đề xuất lộ trình làm việc tối ưu nhất cho người dùng.
🛠 Công nghệ sử dụng (Tech Stack)
Backend: Python (FastAPI / Flask)
Database: SQL (PostgreSQL/MySQL) với SQLAlchemy ORM.AI 
Engine: Thuật toán tìm kiếm Heuristic & Greedy.
Frontend: HTML5, CSS3 (Bootstrap 5), JavaScript.
Tools: Git/GitHub, Draw.io.
✨ Tính năng chính
1. Quản lý công việc (CRUD)
Thêm, sửa, xóa và quản lý danh sách Task.
Phân loại công việc theo danh mục (Học tập, Dự án, Cá nhân).
Thiết lập sự phụ thuộc giữa các Task (Task A phải xong mới được làm Task B).
2. Logic AI (Smart Logic)
Auto-Prioritization: Tự động tính toán điểm ưu tiên dựa trên trọng số Deadline và Importance.
Conflict Detection: Cảnh báo nếu các task có deadline quá sát nhau mà tổng thời gian thực hiện vượt quá khả năng.
Deadlock Prevention: Phát hiện và ngăn chặn vòng lặp phụ thuộc (Circular Dependency).
📅 Nhật ký tiến độ (Weekly Progress)
Tuần  Nội dung công việc                                                 Trạng thái
01    Khảo sát yêu cầu, vẽ sơ đồ Use Case và định nghĩa AI Heuristic.    ✅ Hoàn thành
🏗 Cấu trúc thư mụcPlaintext/
├── backend/            # Mã nguồn xử lý Logic & API
├── frontend/           # Giao diện người dùng
├── ai_engine/          # Thuật toán sắp xếp thông minh
├── docs/               # Sơ đồ ERD, Use Case và Báo cáo PDF
└── README.md           # Hướng dẫn và tiến độ dự án
👨‍🏫 Thông tin hướng dẫn
Giảng viên: Nguyễn Xuân Đức
Sinh viên thực hiện: Trần Đỗ Lan Phương
Email GV: ducngx95@gmail.com# SMART-TASK-SCHEDULER 

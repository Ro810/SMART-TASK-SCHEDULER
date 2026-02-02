# Tuần 1: Xác định bài toán và liệt kê các tính năng

## 1. Khảo sát yêu cầu (Requirement Analysis)

### Nhóm tính năng cơ bản (CRUD)
- **Quản lý Task**: Thêm mới, sửa thông tin, xóa và xem danh sách công việc
- **Quản lý danh mục**: Phân loại task theo nhóm (Học tập, Việc nhà, Dự án)
- **Trạng thái**: Đánh dấu task đã hoàn thành hoặc đang thực hiện

### Nhóm tính năng "Thông minh" (AI Core)
- **Sắp xếp ưu tiên**: AI tự động đề xuất task nào nên làm trước
- **Ước tính khả thi**: Cảnh báo nếu bạn đặt quá nhiều task có deadline sát nhau mà thời gian làm không đủ
- **Gợi ý lộ trình**: Nếu Task B phụ thuộc Task A, AI sẽ ẩn Task B cho đến khi Task A hoàn thành

## 2. Phân tích Actor và Use Case

### Actor
- Người dùng (User)

### Các Use Case chính
- Đăng nhập/Đăng ký
- Quản lý Task
- Yêu cầu AI lập lịch tối ưu (Optimize Schedule)
- Xem thống kê năng suất

## 3. Xác định logic AI (Heuristic Formula)

### Công thức tính điểm ưu tiên

$$P = \frac{W_1 \cdot \text{Priority} + W_2 \cdot \text{Urgency}}{\text{EstimatedTime}}$$

**Trong đó:**

- **P**: Điểm ưu tiên (Priority Score)
- **W₁, W₂**: Các trọng số do người dùng thiết lập
- **Urgency**: Tính bằng $\frac{1}{\text{Deadline} - \text{CurrentTime}}$
- **Priority**: Mức độ ưu tiên do người dùng đặt (1-5)
- **EstimatedTime**: Thời gian ước tính để hoàn thành task

> Task có điểm P cao hơn sẽ được ưu tiên thực hiện trước.







# BÀI TẬP: SO SÁNH CÔNG CỤ GIAO TIẾP NHÓM CAMPUSPAY

## 1. Phân tích bài toán (I/O)

-   **Đầu vào:** Nhóm CampusPay có 4 ban, cần giao tiếp, chia sẻ tài liệu, quản lý nhiệm vụ và deadline.
    
-   **Đầu ra:** Hạn chế trôi tin nhắn, tìm kiếm thông tin nhanh và phối hợp công việc hiệu quả.
    

## 2. Ưu điểm và nhược điểm

### Giải pháp A – Zalo

-   **Ưu điểm:** Dễ sử dụng, quen thuộc, thuận tiện liên lạc với đối tác.
    
-   **Nhược điểm:** Tin nhắn dễ bị trôi, khó quản lý nhiệm vụ và phân loại thông tin.
    

### Giải pháp B – Lark Suite

-   **Ưu điểm:** Có Channel, Thread, Task, tìm kiếm tin nhắn và tích hợp tài liệu.
    
-   **Nhược điểm:** Cần thời gian làm quen và hướng dẫn sử dụng.
    

## 3. Bảng so sánh
| Tiêu chí | Zalo | Lark Suite |
| :-: | - | :-: |
| Chống trôi tin nhắn | ⚠️ | ✅ |
| Quản lý công việc | ⚠️ | ✅
| Dễ sử dụng | ✅  | ⚠️
| Tìm kiếm lịch sử | ⚠️ | ✅
| Làm việc bất đồng bộ | ⚠️ | ✅
## 4. Lựa chọn giải pháp

**Chọn Lark làm công cụ chính, kết hợp Zalo để liên lạc với đối tác bên ngoài.**

-   **Bẫy 1:** Lark có ứng dụng điện thoại, không bắt buộc phải có laptop.
    
-   **Bẫy 2:** Dành 1–2 ngày hướng dẫn sử dụng; nếu deadline gấp, triển khai từng bước.
    
-   **Bẫy 3:** Tiếp tục dùng Zalo với đối tác, sau đó chuyển các quyết định quan trọng vào Lark.
    

## 5. Thiết kế Channel CampusPay
| Channel  | Mục đích | Quyền đăng
| :-: | :-: | :-:
| `#thong-bao` | Thông báo, deadline | Trưởng nhóm
| `#dev` | Code, API, kỹ thuật | Ban Kỹ thuật
| `#design` | UI/UX, thiết kế | Ban Thiết kế
| `#kinh-doanh` | Kế hoạch kinh doanh, đối tác | Ban Kinh doanh
| `#task-tracking` | Theo dõi nhiệm vụ | Tất cả thành viên
| `#general` | Trao đổi chung | Tất cả thành viên

### Quy tắc chống spam @all – Quy tắc cờ đỏ

Tất cả thành viên-   Chỉ trưởng nhóm hoặc người được ủy quyền mới được dùng `@all`.
    
-   Chỉ dùng khi có việc khẩn cấp hoặc deadline quan trọng.
    
-   Thông báo phải nêu rõ công việc và thời hạn.
    
-   Trao đổi thông thường phải dùng Thread hoặc nhắc đúng người.
    



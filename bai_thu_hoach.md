# BÀI THU HOẠCH: TỔNG QUAN VỀ WEB BACKEND VÀ FASTAPI

## Phần 1: Khái niệm cơ bản

### 1. Backend là gì?
Theo cách hiểu của em, nếu một trang web là một nhà hàng thì giao diện (Frontend) chính là không gian quán, bàn ghế và thực đơn mà khách hàng nhìn thấy. Còn **Backend** chính là khu vực nhà bếp – nơi thực khách không nhìn thấy được nhưng lại là nơi xử lý toàn bộ các yêu cầu. 

Backend là phần kiến trúc chạy ngầm ở phía máy chủ, chịu trách nhiệm xử lý logic, tính toán dữ liệu, tương tác với cơ sở dữ liệu (Database) và đảm bảo cho ứng dụng hoạt động mượt mà, bảo mật.

### 2. Client – Server là gì?
Đây là một mô hình giao tiếp cơ bản trên Internet giữa hai bên:
* **Client (Phía khách):** Là thiết bị hoặc ứng dụng mà người dùng trực tiếp thao tác (như trình duyệt Chrome, ứng dụng trên điện thoại). Client đóng vai trò là người đưa ra yêu cầu (Request).
* **Server (Phía máy chủ):** Là một máy tính có cấu hình mạnh, luôn bật 24/7 để tiếp nhận yêu cầu từ Client. Nó sẽ xử lý, tìm kiếm thông tin và "trả lời" (Response) lại cho Client.

> **Ví dụ thực tế:** Khi em lướt Facebook và bấm vào nút "Xem trang cá nhân", điện thoại của em (Client) sẽ gửi một lời mời dữ liệu đến máy chủ của Facebook (Server). Server tìm đúng thông tin của em rồi gửi ngược lại để màn hình điện thoại hiển thị lên.

### 3. API là gì?
**API (Application Programming Interface)** đóng vai trò như một "người vận chuyển" hoặc một "anh shipper" kết nối giữa hai phần mềm khác nhau. Nó định nghĩa ra các quy tắc để Client và Server có thể nói chuyện và hiểu được nhau.

Nếu không có API, Client sẽ không biết phải gọi vào đâu để lấy dữ liệu, và Server cũng không biết Client đang muốn gì.

### 4. JSON là gì?
**JSON (JavaScript Object Notation)** là một định dạng văn bản dùng để lưu trữ và trao đổi dữ liệu. Điểm hay của JSON là nó cực kỳ tối giản, viết dưới dạng các cặp `khóa: giá trị` (key: value) nên cả con người đọc cũng hiểu mà máy tính xử lý cũng rất nhanh. Hiện nay, hầu hết các API đều dùng JSON để truyền tải thông tin qua lại.

```json
{
  "ten_sinh_vien": "Hoàng",
  "lop": "Công nghệ thông tin",
  "mon_hoc": "Web Backend"
}
## Khái niệm 
**Backend** : là phần hệ thống nền tảng của một ứng dụng, web mà người dùng không nhìn thấy

**Client - Sever**: Là cơ chế tương tác mạng cơ bản. Trong đó, Client đóng vai trò gửi đề xuất/yêu cầu, còn Server sẽ tiếp nhận, xử lý logic và phản hồi lại kết quả tương ứng.

**API**: cầu nối kỹ thuật số, giúp các phần mềm hoặc hệ thống khác nhau có thể hiểu nhau, từ đó trao đổi và chia sẻ dữ liệu một cách mượt mà.

**JSON**: Định dạng lưu trữ và truyền tải dữ liệu bằng văn bản (text) theo một cấu trúc quy chuẩn, gọn nhẹ. Đây là ngôn ngữ chung phổ biến nhất hiện nay để đóng gói dữ liệu khi trao đổi giữa Client và Server.

## Bản chất của Giao thức Web
**HTTP**: Là phương thức truyền tải dữ liệu nền tảng trên Internet. Nó hoạt động như một bộ quy tắc ứng xử chung để các thiết bị và máy chủ có thể "nói chuyện" và hiểu được nhau.

- **GET**: Gửi yêu cầu lên máy chủ để lấy hoặc đọc thông tin về.
- **POST**: Đẩy dữ liệu mới lên hệ thống để khởi tạo một đối tượng/tài nguyên mới.
- **PUT**: Gửi dữ liệu nhằm thay đổi, cập nhật hoặc ghi đè lên thông tin đã tồn tại.
- **DELETE**: Ra lệnh cho máy chủ gỡ bỏ hoặc xóa hẳn một tài nguyên cụ thể.

## Tìm hiểu FastAPI
**FastAPI**: là một framework mã nguồn mở của Python chuyên dụng để thiết kế và phát triển các cổng API với tốc độ xử lý tối ưu, giao diện hiện đại và độ tin cậy cao.

**Đặc điểm**: 
- Hỗ trợ lập trình bất đồng bộ
- Tự động sinh tài liệu API
- Kiểm tra kiểu dữ liệu ngay từ khi lập trình

FastAPI được dử dụng để xay dựng backend, đặc biệt là các API phục vụ nhiều loại ứng dụng khác nhau. Một số ứng dụng phổ biến:

- Backend cho web
- Backend cho ứng dụng di động
- Hệ thống quản lí

So với các web framework truyền thống, FastAPI nổi bật nhờ:
- Tốc độ cực nhanh Nhờ tận dụng tối đa cơ chế lập trình bất đồng bộ
- An toàn dữ liệu: Tự động kiểm tra và rà soát lỗi kiểu dữ liệu ngay trong quá trình code nhờ tính năng Type Hint của Python.
- Từ động sinh tài liệu API

# Nhom1_T5_Ca4-Quản lí phòng khám

"Trong thời đại số hóa ngày nay, việc quản lý và trải nghiệm chăm sóc sức khỏe trở nên dễ dàng hơn bao giờ hết, và hệ thống quản lý phòng khám tư nhân đã xuất hiện để đáp ứng các nhu cầu đa dạng của bác sĩ, nhân viên y tế và cả khách hàng.Hệ thống phòng khám tư nhân “Healthy Care” là 1 website cho phép người dùng có thể truy cập để xem các thông tin mà họ đã tra cứu liên quan đến các vấn đề về sức khỏe.

Với nhu cầu muốn tiếp cận đến nhiều tệp khách hàng hơn trước công ty quyết định xây dựng 1 website để người dùng có thể biết đến phòng khám và thao tác trên trang web các hoạt động như: đặt lịch khám, tra cứu thông tin bác sĩ, thông tin cá nhân của bản thân, hiển thị thông tin vấn đề khách hàng đang gặp phải theo mô tả của khách hàng, hiển thị chi phí khám dự kiến, và hiển thị đường dây nóng để người dùng có thể gọi điện tư vấn. 
Ngoài ra người dùng có thể xem và nắm được doanh thu của phòng khám qua các giai đoạn. Từ đó có thể tiến hành tạo bảng thống kê để lưu trữ vào hệ thống. 

Bên cạnh đó, hệ thống cũng cần phải phân quyền nhằm đảm bảo vai trò phân biệt giữa người dùng, bác sĩ và tiếp tân và cũng cần quản lí các danh sách khách hàng, danh sách đơn khám theo cách tổng quát hoặc chi tiết.Với ""Sức Khỏe Tại Đầu Ngón Tay,"" chúng tôi cam kết mang lại sự thuận tiện và hiệu quả trong việc quản lý và sử dụng dịch vụ chăm sóc sức khỏe, đồng thời cung cấp trải nghiệm tốt nhất cho cả bác sĩ và bệnh nhân. Hãy cùng chúng tôi xây dựng tương lai với sức khỏe tốt hơn."								
"Healthy Care" là một ứng dụng web quản lý phòng khám y tế được xây dựng bằng cách sử dụng mô hình ASP.NET MVC. Ứng dụng này nhằm mục đích hỗ trợ quản lý và tổ chức hoạt động của một phòng khám y tế, giúp cải thiện hiệu quả và chất lượng dịch vụ y tế.
Với mô hình ASP.NET MVC, "Healthy Care" được chia thành ba phần chính: Model, View và Controller.
1. Model: Trong phần này, "Healthy Care" sử dụng các lớp đại diện cho dữ liệu như bệnh nhân, lịch khám, bác sĩ, đơn thuốc và các thông tin y tế khác. Model chứa logic xử lý dữ liệu, bao gồm truy xuất, cập nhật và xử lý thông tin y tế.
2. View: Giao diện người dùng của "Healthy Care" được hiển thị thông qua các trang web đẹp mắt và dễ sử dụng. Giao diện này cho phép người dùng đăng ký khám, tạo hồ sơ y tế, xem lịch khám và kết quả xét nghiệm, và thực hiện các tác vụ quản lý khác. View trong ASP.NET MVC thường sử dụng các tệp tin HTML hoặc Razor để tạo nội dung giao diện.
3. Controller: Controller trong "Healthy Care" điều khiển luồng của ứng dụng và xử lý các yêu cầu từ người dùng. Controller nhận yêu cầu từ giao diện người dùng, gọi các phương thức của Model để truy xuất và xử lý dữ liệu, sau đó cập nhật lại giao diện người dùng tương ứng. Controller cũng quản lý việc định tuyến các yêu cầu và xử lý các tác vụ quản lý phòng khám.

Với sự linh hoạt của ASP.NET MVC, "Healthy Care" cho phép quản lý phòng khám thực hiện các tác vụ quan trọng như:
- Quản lý thông tin bệnh nhân: Ứng dụng cho phép quản lý và cập nhật thông tin cá nhân, lịch sử bệnh án và kết quả xét nghiệm của bệnh nhân.
- Quản lý lịch khám: "Healthy Care" hỗ trợ tạo và quản lý lịch khám của bác sĩ và bệnh nhân. Người dùng có thể đặt lịch khám, chỉnh sửa và hủy bỏ lịch khám theo nhu cầu.
- Quản lý đơn thuốc: Ứng dụng cung cấp tính năng quản lý và lưu trữ thông tin đơn thuốc của bệnh nhân, đảm bảo rằng thông tin về thuốc và liều lượng được ghi nhận chính xác và dễ dàng truy cập.
- Thống kê và báo cáo: "Healthy Care" cung cấp các báo cáo thống kê về số lượng bệnh nhân, lịch khám, các loại bệnh, và các chỉ số sức khỏe khác. Điều này giúp quản lý phòng khám có cái nhìn tổng quan về hoạt động và hiệu suất của phòng khám.
Với ASP.NET MVC, "Healthy Care" không chỉ mang lại sự tiện ích và hiệu quả trong quản lý phòng khám y tế mà còn đảm bảo tính bảo mật và ổn định. Ứng dụngsử dụng các tính năng bảo mật của ASP.NET để bảo vệ thông tin y tế của bệnh nhân và người dùng. Bên cạnh đó, việc sử dụng mô hình ASP.NET MVC cũng giúp "Healthy Care" dễ dàng mở rộng và tương thích trên các nền tảng khác nhau như Windows, Linux và macOS.
Với "Healthy Care", quản lý phòng khám y tế có thể nâng cao hiệu suất và chất lượng dịch vụ, tăng tính tiện lợi và sự hài lòng của bệnh nhân. Đồng thời, ứng dụng này cũng mang lại sự an tâm và tin tưởng cho người dùng với tính bảo mật và độ tin cậy của nền tảng ASP.NET.

Thành viên: Giang, Minh, Tùng, Công
Mỗi thành viên sẽ tương ứng với các vai trò như:

+ Giang: Team leader
+ Minh: Product owner
+ Tùng và Công: Dev
Nhóm sử dụng công nghệ MVC 

![PhongKham](https://github.com/RinKruger/Nhom_QuanLiPhongKham_T5_Ca4/assets/147702326/16b8711c-9942-4420-a9dd-7c0d94dc7e1f)

https://github.com/RinKruger/Nhom_QuanLiPhongKham_T5_Ca4/assets/144761684/5f6f572b-6fae-4529-9ad6-c192ad28e1fa

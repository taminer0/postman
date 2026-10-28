BÁO CÁO THỰC HÀNH KIỂM THỬ API BẰNG POSTMAN

1. Giới thiệu

Trong quá trình phát triển phần mềm, kiểm thử API là một hoạt động quan trọng nhằm đảm bảo các thành phần của hệ thống giao tiếp với nhau chính xác và ổn định.

Postman là công cụ hỗ trợ kiểm thử API thông qua việc gửi các HTTP request và phân tích response trả về. Công cụ cho phép xây dựng các test script tự động để kiểm tra trạng thái phản hồi, cấu trúc dữ liệu và các điều kiện nghiệp vụ.

Bài thực hành sử dụng Postman để kiểm thử các API của dịch vụ JSONPlaceholder.

2. Mục tiêu thực hành

Làm quen với công cụ Postman.

Hiểu các phương thức HTTP GET, POST, PUT và DELETE.

Thực hiện kiểm thử API thông qua HTTP request.

Xây dựng các test script tự động bằng JavaScript.

Đánh giá kết quả kiểm thử API.

Tổng hợp kết quả thành báo cáo.

3. Môi trường thực hành

Thành phần

Mô tả

Công cụ kiểm thử

Postman

API sử dụng

JSONPlaceholder

Loại API

REST API

Định dạng dữ liệu

JSON

Giao thức

HTTP/HTTPS

Ngôn ngữ viết test script

JavaScript

Địa chỉ API: https://jsonplaceholder.typicode.com

4. Nội dung thực hành

Bài thực hành tiến hành kiểm thử các chức năng:

Lấy danh sách bài viết.

Lấy thông tin bài viết theo ID.

Tạo bài viết mới.

Cập nhật bài viết.

Xóa bài viết.

Kiểm thử trường hợp bài viết không tồn tại.

Các test case được xây dựng dựa trên các phương thức HTTP tương ứng và kiểm tra kết quả trả về của API.

5. Kết quả kiểm thử

Bảng tổng hợp kết quả:

Test Case

Chức năng

Expected Status

TC01

Lấy danh sách bài viết

200 OK

TC02

Lấy bài viết theo ID

200 OK

TC03

Tạo bài viết mới

201 Created

TC04

Cập nhật bài viết

200 OK

TC05

Xóa bài viết

200 OK

TC06

Bài viết không tồn tại

404 Not Found

Kết quả thực tế được ghi nhận sau khi chạy các test case trên Postman.

6. Đánh giá

Thông qua bài thực hành, Postman hỗ trợ kiểm thử API một cách trực quan và thuận tiện.

Các test script giúp tự động hóa việc kiểm tra mã trạng thái HTTP, cấu trúc dữ liệu JSON và nội dung phản hồi. Việc tổ chức các request thành Collection cho phép quản lý và thực hiện nhiều test case trong một lần chạy.

Bên cạnh đó, việc kiểm thử các trường hợp dữ liệu không tồn tại giúp đánh giá khả năng xử lý lỗi của API.

7. Kết luận

Bài thực hành đã giúp làm quen với quy trình kiểm thử API bằng Postman, từ việc gửi HTTP request, phân tích response đến xây dựng test script và tổng hợp kết quả.

Postman là công cụ hữu ích trong kiểm thử phần mềm, đặc biệt đối với kiểm thử API và tự động hóa kiểm thử dịch vụ web.

Trong tương lai, có thể mở rộng bài thực hành bằng cách kết hợp Postman với Newman và GitHub Actions để xây dựng quy trình kiểm thử API tự động trong CI/CD.

<img width="890" height="599" alt="image" src="https://github.com/user-attachments/assets/150dd8d9-926e-4120-95c0-89b9492a1767" />
<img width="774" height="598" alt="image" src="https://github.com/user-attachments/assets/9f23c73a-df7b-457d-a922-7992074bd597" />
<img width="792" height="619" alt="image" src="https://github.com/user-attachments/assets/513af89f-fcb5-4bc1-a502-e0e611f30eba" />
<img width="817" height="574" alt="image" src="https://github.com/user-attachments/assets/f3884d2e-9153-44dd-83da-4033d434d1c5" />
<img width="800" height="569" alt="image" src="https://github.com/user-attachments/assets/81615f50-f90c-43b1-b742-6fd5e6668afe" />


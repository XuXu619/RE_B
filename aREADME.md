Tài liệu tham khảo: http://bit.ly/2eFUang

Người thực hiện: XuXu

Thực hiện lần cuối: 10/03/2017

Menu
1. Kiểu cấu trúc struct, enum

[1.1 Định nghĩa và khai báo]

[1.2 Khai báo theo một kiểu cấu trúc đã định nghĩa]

[1.3 Truy cập nhanh tới phần tử và cấu trúc]

[1.4 Thành phần kiểu FILD (nhóm BIT)]

[1.5 Mảng cấu trúc]
2. Con trỏ cấu trúc  

3. Hàm trên cấu trúc

4. Danh sách liên kết ( 1 chiều, 2 chiều)

5. Sử dụng cấp phát tĩnh động

1. Kiểu cấu trúc struct, enum
Để lưu trữ và xử lý thông tin trong máy tính ta có các biến và các mảng. Mỗi biến chứa một giá trị. Mảng có thẻ xem là tập hợp nhiều biến có cùng một kiểu giá trị và được biểu thị bằng một cái tên. Cấu trúc có thể xem như một sự mở rộng của các khái niệm biến và mảng, nó cho phép lưu trữ và xử lý các dạng thông tin phức tập hơn, Cấu trúc là một tập hợp các biến, các mảng và được biểu thị bởi một tên duy nhất. Khái niệm cấu trúc trong C có những nét tương tự như khái niệm bản ghi (record) trong Pascal hay Foxpro. Một ví dụ truyền thống về cấu trúc là phiếu ghi lương: Mỗi công nhân được miêu tả bởi một tập hợp các thuộc tính như tên, địa chỉ, ngày sinh, bật lương, ... Một vài trong thuộc này lại có thẻ là cấu trúc: Tên có thể có nhiều thành phần, địa chỉ và thậm chí ngày sinh cũng vậy.

1.1 Định nghĩa và khai báo

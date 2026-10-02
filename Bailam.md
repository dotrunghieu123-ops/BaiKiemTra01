Câu 1
Value Types (kiểu giá trị) lưu trực tiếp giá trị của biến. Khi gán một biến kiểu giá trị cho biến khác thì giá trị được sao chép thành một bản riêng. Các kiểu thường gặp là int, float, bool, struct, enum. Biến cục bộ kiểu giá trị thường được lưu trên Stack.
Reference Types (kiểu tham chiếu) lưu tham chiếu đến đối tượng. Đối tượng thường được cấp phát trên Heap. Khi gán một biến kiểu tham chiếu cho biến khác thì hai biến có thể cùng tham chiếu đến một đối tượng.
Câu 2
init cho phép thuộc tính được gán giá trị trong quá trình khởi tạo đối tượng nhưng không cho phép thay đổi sau khi đối tượng đã được khởi tạo.
Khác với set, thuộc tính có set có thể được gán và thay đổi giá trị bất cứ lúc nào.
Ứng dụng: init phù hợp với các thông tin cần cố định sau khi tạo đối tượng, như mã sinh viên, mã đơn hàng hoặc ngày tạo.
Câu 3
virtual được khai báo ở lớp cha, cho phép phương thức có thể được lớp con thay đổi cách thực hiện.
override được khai báo ở lớp con, dùng để thay đổi cách thực hiện phương thức virtual của lớp cha.
Hai từ khóa này kết hợp với nhau để thực hiện tính đa hình, giúp chương trình có thể gọi cùng một phương thức nhưng thực hiện hành vi khác nhau tùy theo đối tượng thực tế.
Câu 4
Thành phần static thuộc về Class, không thuộc về từng Object Instance.
Khi tạo nhiều đối tượng bằng new, các đối tượng đó không có bản sao riêng của thành phần static. Thành phần static được dùng chung cho toàn bộ lớp.
Vì vậy, thành phần static phải được truy xuất thông qua tên Class, không phải thông qua một Object Instance.

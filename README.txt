HƯỚNG DẪN CHẠY BÀI 1 + BÀI 2

1. Giải nén file ZIP.
2. Mở file:
   WebProgramming_Bai1_Bai2.csproj
   bằng Visual Studio.
3. Bấm F5 hoặc nút Run.
4. Trình duyệt sẽ mở trang Bài 1.

BÀI 1:
Trang chính "/"
- Lấy ngày hiện tại bằng DateTime.Now.
- Kiểm tra Saturday hoặc Sunday.
- Nếu là cuối tuần: "Have nice weekend".
- Nếu không: "Have a nice day!".

BÀI 2:
Truy cập "/Products"
- Product có 3 thuộc tính: Id, Name, Price.
- Tạo List<Product>.
- Dùng foreach để duyệt danh sách.
- Hiển thị sản phẩm trong bảng HTML.

CẤU TRÚC:
Pages/Index.cshtml       -> Bài 1
Pages/Products.cshtml    -> Bài 2
Models/Product.cs        -> Lớp Product
Program.cs               -> Cấu hình Razor Pages

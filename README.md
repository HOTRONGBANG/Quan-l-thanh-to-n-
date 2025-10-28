🧱 BẢNG MÔ TẢ CÔNG VIỆC – DỰ ÁN WEBSITE BÁN ĐỒ ĂN NHANH
🧩 Giới thiệu chung

- Dự án Website Bán Đồ Ăn Nhanh được xây dựng theo mô hình ASP.NET MVC, sử dụng C# làm ngôn ngữ lập trình và SQL Server để quản lý  cơ sở dữ liệu.
- Mục tiêu của nhóm là tạo ra một hệ thống giúp người dùng có thể dễ dàng chọn món, thêm vào giỏ hàng và đặt hàng trực tuyến. Hệ  thống cũng cung cấp trang quản trị cho admin để quản lý sản phẩm và người dùng.

🧑‍💻 Người 1 – Quản trị & Đăng nhập

-Người phụ trách phần đăng nhập, đăng ký và quản lý dữ liệu sản phẩm.
Cụ thể, bạn này chịu trách nhiệm:

-Tạo trang đăng nhập / đăng ký với phân quyền người dùng và quản trị viên (Admin/User).

-Xây dựng trang quản lý món ăn (thêm, sửa, xóa, cập nhật món ăn).

-Quản lý danh mục sản phẩm như: Burger, Gà rán, Đồ uống,…

-Xử lý phiên đăng nhập (Session) và xác thực người dùng (Authentication).

-Về cơ sở dữ liệu, người này tạo các bảng:

-Users: thông tin người dùng (ID, Username, Password, Role,...)

Categories: danh mục món ăn

Products: thông tin món ăn (tên, giá, hình ảnh, mô tả,...)

🍔 Người 2 – Trang sản phẩm & Giỏ hàng

Người thứ hai phụ trách hiển thị sản phẩm và chức năng giỏ hàng cho người dùng.
Các nhiệm vụ bao gồm:

Tạo trang danh sách sản phẩm (có phân loại theo danh mục).

Xây dựng trang chi tiết sản phẩm (hiển thị ảnh, mô tả, giá).

Xử lý chức năng thêm, xóa, cập nhật số lượng món ăn trong giỏ hàng.

Tính tổng giá trị đơn hàng và lưu dữ liệu giỏ hàng tạm thời bằng session.

Về cơ sở dữ liệu, người này quản lý:

Products: truy vấn sản phẩm từ CSDL.

Cart: bảng lưu tạm thời các món trong giỏ hàng của từng người dùng.

💳 Người 3 – Đặt hàng & Thanh toán

Người thứ ba chịu trách nhiệm xử lý phần đặt hàng và thanh toán, bao gồm:

Tạo trang Checkout (xác nhận thông tin đặt hàng).

Lưu đơn hàng vào cơ sở dữ liệu (bảng Orders và OrderDetails).

Xây dựng trang xác nhận đơn hàng và trang lịch sử mua hàng.

Quản lý trạng thái đơn hàng (đang xử lý, đã giao, hủy đơn,...)

Về cơ sở dữ liệu:

Orders: thông tin hóa đơn (người đặt, tổng tiền, ngày đặt, trạng thái).

OrderDetails: chi tiết từng món trong đơn hàng (mã sản phẩm, số lượng, đơn giá).

🎨 Người 4 – Giao diện & Trang tĩnh

Người thứ tư phụ trách thiết kế và bố cục giao diện website.
Công việc bao gồm:

Thiết kế trang chủ (Home) có banner, logo, và danh sách món nổi bật.

Xây dựng các trang tĩnh: Giới thiệu, Liên hệ, Khuyến mãi.

Tạo layout chung (_Layout.cshtml) bao gồm header, menu, footer.

Thiết kế CSS responsive đảm bảo website hiển thị tốt trên điện thoại, máy tính bảng và PC.

Về cơ sở dữ liệu:

Promotions: lưu thông tin khuyến mãi (% giảm, thời hạn,...).

Feedback: phản hồi và đánh giá của khách hàng.

⚙️ Gợi ý triển khai dự án

Người 1 phát triển khu vực quản trị (Admin Area) trong ASP.NET MVC.

Người 2 và 3 phối hợp trong khu vực người dùng (User Area) để hoàn thiện trải nghiệm đặt hàng.

Người 4 đảm nhiệm việc hoàn thiện giao diện và responsive, kết nối layout với các view khác.

📈 Tổng kết

Mỗi thành viên đều có nhiệm vụ riêng nhưng liên kết chặt chẽ với nhau trong cùng hệ thống:

Frontend (giao diện): do người 4 đảm nhiệm chính.

Backend (xử lý dữ liệu, giỏ hàng, thanh toán): do người 1–3 phụ trách.

Database (SQL Server): được chia theo chức năng từng phần, có quan hệ logic giữa các bảng (Users, Products, Orders, OrderDetails, Cart).

Dự án hướng đến mục tiêu xây dựng một website bán đồ ăn nhanh hoàn chỉnh, có thể mở rộng trong tương lai với các chức năng như thanh toán online, quản lý kho, và hệ thống đánh giá món ăn.

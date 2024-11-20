# BaiKT
Bài kiểm tra năng lực ứng viên - ReactJS.

Phần 1: Xử lý logical với ReactJS
Tạo một component ReactJS có tên là CreateOrder. Component này sẽ hiển thị một form để giúp người dùng lên đơn hàng cho khách. Form này gồm các trường sau:
Input nhập tên khách hàng.
Input nhập email khách hàng.
Input nhập số điện thoại khách hàng.
Select input để thêm sản phẩm vào giỏ hàng (mock data product).
Array giỏ hàng đã chọn, mỗi item biểu diễn 1 sản phẩm bao gồm tên sản phẩm, đơn giá, số lượng và mã khuyến mãi(2), người dùng được phép thay đổi số lượng và đơn giá của sản phẩm.
Card hiển thị tổng giá trị đơn hàng.
Radio input để lựa chọn phương thức thanh toán của khách (tiền mặt/thẻ).
Input nhập số tiền khách đưa (chỉ cần nhập khi lựa chọn phương thức thanh toán tiền mặt, khi tiền khách đưa lớn hơn số tiền cần thanh toán hiển thị thêm phần “tiền thừa trả khách”).
Button để thực hiện “Thanh toán”.
Chức năng áp mã khuyến mãi cho sản phẩm: Mã khuyến mãi có 2 loại là giảm trực tiếp số tiền hoặc giảm theo phần trăm. mỗi sản phẩm trong giỏ được áp 1 mã (Mock data khuyến mãi)
Xây dựng logic trong CreateOrder để lưu thông tin về đơn hàng đã nhập vào trong state của component. State này là 1 đối tượng
Khi người dùng click vào button "Thanh toán". Hiển thị component modal có tên là ConfirmOrder .  Component này sẽ hiển thị toàn bộ thông tin đơn hàng đã nhập bên trên (Gồm thông tin khách hàng, thông tin giỏ hàng và thông tin thanh toán).
Bonus: Thêm tính năng xóa sản phẩm khỏi giỏ hàng khi người dùng click vào một nút "Xóa" tương ứng.

Phần 2: UI/UX trong ReactJS
Sử dụng CSS hoặc thư viện sau như Material UI hoặc Ant Design để thiết kế giao diện cho bài.
Đảm bảo rằng giao diện của bạn dễ hiểu và dễ sử dụng, ví dụ như sử dụng màu sắc và biểu tượng để làm nổi bật các nút và phần tử quan trọng.
Bonus: Cải thiện UX bằng cách thêm các hiệu ứng hoặc animation khi người dùng thêm hoặc xóa sản phẩm khỏi giỏ hàng.
Yêu cầu nộp: 
Đẩy source lên github để nộp. 
Quay video demo và trình bày cách làm của bạn

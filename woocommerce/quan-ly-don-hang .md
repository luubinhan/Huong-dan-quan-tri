# Quản lý đơn hàng
Mỗi đơn hàng có thuộc tính gọi là "tình trạng đơn hàng" cho phép người quản lý shop cũng như khách hàng biết được trạng thái đơn hàng hiện tại


   * **Chờ xử lý:** đã tiếp nhận đơn hàng
   * **Bỏ qua:** thanh toán thất bại, huỷ đơn hàng
   * **Thất bại:** thanh toán không thành công hoặc bị từ chối
   * **Chờ xử lý:** Đã giảm số lượng trong kho, chờ thanh toán
   * **Đang thực hiện:** Đã nhận tiền, số lượng hàng trong kho giảm, đơn hàng chờ được giao
   * **Hoàn tất:** hoàn tất giao hàng và thanh toán 
   * **Trả hàng:** đơn hàng được trả lại
   * **Huỷ:** đơn hàng bị huỷ bởi người quản trị hoặc khách hàng

# Xem tất cả đơn hàng

```
WooCommerce > Đơn hàng 
```

Mỗi dòng trên bảng đơn hàng hiển thị địa chỉ khách hàng, email, điện thoại, tình trạng đơn hàng. Để xem chi tiết 1 đơn hàng, click vào mã đơn hàng

![image](http://i429.photobucket.com/albums/qq12/liu_zango_ne/Huong-dan-quan-tri/managing-orders-1.png)

Để lọc bớt kết quả hiển thị theo ngày, tình trạng, khách hàng, sử dụng form trên cùng màn hình

![image](http://i429.photobucket.com/albums/qq12/liu_zango_ne/Huong-dan-quan-tri/managing-orders-3-550x34.png)

Trên mỗi dòng sản phẩm, cho phép chuyển nhanh tình trạng sản phẩm sang "Hoàn tất","Đang thực hiện"

![image](http://i429.photobucket.com/albums/qq12/liu_zango_ne/Huong-dan-quan-tri/managing-orders-2.png)

# Xem/Chỉnh sửa một đơn hàng 

Trên trang chi tiết đơn hàng, bạn có thể
* Thay đổi tình trạng đơn hàng
* Thay đổi sản phẩm trong giỏ hàng
* Trừ bớt khôi phục số lượng trong kho

## Thông tin đơn hàng


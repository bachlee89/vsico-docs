---
title: Shipping
parent: Nghiệp vụ vận tải biển
nav_order: 20
---

# A. SHIPPING
1.Quy trình tổng quản nghiệp vụ Shipping.

a) Mô hình quy trình khai thác dịch vụ Shipping.
 

![Mô hình quy trình khai thác dịch vụ](../../../../../assets/images/shipping-service-model.png)

b) Mô tả quy trình

![Mô tả quy trình](../../../../../assets/images/shipping-workflows.png)
![Mô tả quy trình](../../../../../assets/images/shipping-workflows-2.png)
![Mô tả quy trình](../../../../../assets/images/shipping-workflows-3.png)

2.QUY TRÌNH NGHIỆP VỤ PHÒNG BAN EQC

a) EQC SỐ LƯỢNG
- Mô hình thực hiện cấp vỏ
![Mô hình thực hiện cấp vỏ](../../../../../assets/images/cap-vo.png)
- Mô tả quy trình:
![Mô tả quy trình cấp vỏ](../../../../../assets/images/mota-capvo.png)
![Mô tả quy trình cấp vỏ](../../../../../assets/images/mota-capvo-2.png)

b) EQC chất lượng
- Mô hình quy trình thực hiện dịch vụ
![ECQ Chất lượng](../../../../../assets/images/mohinh-ecq-chatluong.png)

- Mô tả quy trình:
![Mô tả ECQ Chất lượng](../../../../../assets/images/mota-ecq-chatluong.png)


3.Một số khái niệm khác.

a) Quản lý contr Onhire : Bổ sung thêm vỏ contr vào hệ thống
- Hình thức : Thuê, Mua, Thuê mua
- Redue: Mượn vỏ đối tác, Onhire ngắn hạn (Là những contr được onhire trong khoảng thời gian – mùa vụ)
- Có danh sách tiêu chuẩn contr được cấp vào hệ thống

b) Quản lý Contr Offhire : Loại bỏ vỏ contr trên hệ thống
-
Hình thức : Thanh lý, Trả thuê
Mục tiêu : Quản lý được lượng vỏ nắm giữ, sử dụng, khai thác, tìm ra khách hàng tiềm năng, nhu cầu hàng hóa, kinh tế thị trường, Nâng cao chất lượng dịch vụ

c) Quản lý Tàu ngoài
Mục tiêu : Quản lý tất cả thông tin liên quan đến 1 chuyến tàu ngoài. Cần làm rõ các phương thức di chuyển (Đường biển, đường bộ, đường sắt,…). Request tàu ngoài (Chức năng
cho phép user đề xuất phát sinh khi xảy ra)

d) Phí DMDT
Hàng nhập :
-
DT (thời gian contr lưu vỏ bên ngoài ) :+
Time in : Thời gian contr nhập lên bãi = thời gian distract
+
Time out : Thời gian giao hàng cho khách hàng
+
Free day : 5 ngày
-
DM (thời gian contr lưu bỏ tại bãi) :
+
Time in: Thời gian contr được dỡ trên tàu xuống bãi
+
Time out: Thời gian lấy hàng của khách hàng
+
Free day : 3 ngày
Hàng xuất:
-
DT (thời gian contr lưu vỏ bên ngoài):
+
Time in : Thời gian contr được lấy ra khỏi bãi
+
Time out : Thời gian contr được trả về bãi sau khi lấy đi
+
Free time: 7 ngày
-
DM (thời gian contr lưu bỏ tại bãi)
+
Time in: Thời gian contr được trả về bãi
+
Time out : Thời gian contr hàng được đưa lên tàu
+
Free time: 3 ngày

**Lưu ý** :
Chính sách Combine:
-
Thời gian free time sẽ được linh hoạt ở 2 đầu ( Dựa theo lượng thời gian lưu bãi trên bãi hàng xuất có thể bù trừ vào thời gian lưu contr và lưu bãi ở phía hàng nhập)
-
Đối với khách hàng đặc biệt
-
Trường hợp Combine nhập-nhập: Khi thời gian được sử dụng ít hơn thì thời gian còn lại sẽ được đẩy sang lưu bãi tại depot
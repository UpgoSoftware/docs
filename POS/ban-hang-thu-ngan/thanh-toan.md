---
description: >-
  Giao diện thanh toán trong hệ thống POS hỗ trợ nhân viên thu ngân thực hiện
  thanh toán nhanh chóng và chính xác
---

# Thanh toán

Các thành phần trong giao diện thanh toán gồm:

* Phương thức thanh toán:&#x20;
  * Tiền mặt: Lựa chọn mặc định để nhập số tiền khách hàng thanh toán bằng tiền mặt.
  * Thẻ: Tùy chọn cho giao dịch qua thẻ Visa hay thẻ ngân hàng.
  * Ví điện tử (Ví ĐT): Hỗ trợ thanh toán qua các nền tảng ví điện tử (như MoMo, VNPay,...).
* Khu vực nhập liệu thanh toán: Nhập số tiền khách hàng thanh toán trực tiếp.
* Đề xuất số tiền khách trả với nhiều mệnh giá phổ biến: Hệ thống cung cấp các lựa chọn số tiền để tăng tốc quá trình thanh toán, phù hợp với các mệnh giá tiền phổ biến.
* Khu vực thông tin thanh toán:&#x20;
  * Thành tiền: Hiển thị tổng số tiền của đơn hàng.
  * Chiết khấu sản phẩm: Tổng giá trị chiết khấu áp dụng trên từng sản phẩm (nếu có).
  * Chiết khấu mã phiếu: Tổng giá trị giảm giá từ mã giảm giá/voucher (nếu có).
  * Thanh toán: Số tiền cần khách hàng thanh toán.
  * Trả lại khách: Hiển thị số tiền cần trả lại khách nếu khách thanh toán dư.
  * Mã QR: Mã để khách hàng quét khi lựa chọn thanh toán bằng ví điện tử hay thanh toán bằng app.
* Nút chức năng:
  * Đóng: Hủy giao dịch và quay lại màn hình trước đó.
  * Voucher: Thêm hoặc áp dụng mã giảm giá cho đơn hàng.
  * Hoàn thành: Xác nhận thanh toán và hoàn tất giao dịch.

<figure><img src="../.gitbook/assets/Screenshot from 2024-12-19 14-13-45.png" alt=""><figcaption><p>Thanh toán</p></figcaption></figure>

Chức năng nút **+ Thêm PTTT:**

* Kết hợp các phương thức thanh toán, nhân viên có thể thêm các hình thức thanh toán bổ sung như:&#x20;
  * Tiền mặt.
  * Thanh toán qua thẻ.
  * Ví điện tử (MoMo, VNPay,...).
* Hiển thị số tiền của từng phương thức: Người dùng có thể nhập số tiền được thanh toán qua mỗi phương thức, đảm bảo rằng tổng số tiền khớp với giá trị hóa đơn.
* Xử lý thanh toán linh hoạt: Trường hợp khách hàng không thể thanh toán toàn bộ bằng một phương thức thanh toán mà muốn kết hợp nhiều phương thức khác nhau.

<figure><img src="../.gitbook/assets/Screenshot from 2024-12-19 14-37-01 (1).png" alt=""><figcaption><p>Thanh toán</p></figcaption></figure>

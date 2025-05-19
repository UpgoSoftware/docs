---
description: Xem hoặc tạo lịch chạy automation
---

# Schedule

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption><p>Schedule/collection</p></figcaption></figure>

Gồm các thông tin cơ bản:

* Label
* Schedule Type
* Automation
* Repository
* Status

<figure><img src=".gitbook/assets/image (17).png" alt=""><figcaption><p>Schedule/model</p></figcaption></figure>

Tạo mới Schedule cần các thông tin:

* Label
* Schedule Type: Cron
* Automation
* Repository
* Schedule Time

\*Schedule Time: dạng Cron

Lên lịch làm việc tại 1 thời điểm cụ thể mà cần lặp đi lặp lại, thực thi những tác vụ không cần tương tác.

<table data-header-hidden data-full-width="false"><thead><tr><th></th><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>*</td><td>*</td><td>*</td><td>*</td><td>*</td></tr><tr><td>Minute (1 - 59)</td><td>Hour (0 - 23)</td><td>Day of the month (1 - 31)</td><td>Month (1 - 12)</td><td>Day of the week (0 - 7)</td></tr></tbody></table>

Tóm tắt :

* **Minute** – phút của giờ mà lệnh sẽ chạy, trong khoảng từ 0 đến 59
* **Hour** – dựa trên giờ mà lệnh sẽ chạy, trong khoảng từ 0 đến 23
* **Day of the month** – dựa trên ngày của tháng mà bạn muốn chạy lệnh, trong khoảng từ 1 đến 31
* **Month** – dựa trên tháng mà lệnh cụ thể chạy, trong khoảng từ 1 đến 12
* **Day of the week** – dựa trên ngày của tuần mà bạn muốn chạy lệnh, trong khoảng từ 0 đến 7

Ngoài ra còn các cú pháp chi tiết hơn như sau :

* **Dấu hoa thị (\*)** – để xác định tất cả tham số được lên lịch
* **Dấu phẩy (,)** – để duy trì 2 hoặc nhiều lần thực thi một lệnh
* **Dấu gạch nối (-)** – để xác định khoảng thời gian thiết lập lần thực thi một lệnh
* **Dấu gạch chéo (/)** – để tạo khoảng thời gian nghỉ cụ thể
* **Cuối cùng (L)** – cho mục đích cụ thể là chỉ định ngày cuối cùng của tuần trong tháng. Ví dụ, 3L nghĩa là thứ tư cuối cùng.
* **Ngày trong tuần (W)** – để xác định ngày trong tuần gần nhất. Ví dụ, 1W nghĩa là nếu ngày 1 là thứ 7, lệnh sẽ chạy vào thứ hai (ngày 3)
* \*\*Hash (#) \*\*– để xác định ngày của tuần, theo sau bởi số chạy từ 1 đến 5. Ví dụ, 1#2 nghĩa là ngày thứ Hai thứ hai.
* **Dấu chấm hỏi (?)** – để để lại khoảng trống

Ví dụ:&#x20;

* Chạy vào lúc 3 giờ hàng ngày: 0 3 \* \* \*
* Chạy vào lúc 17h ngày chủ nhật hàng tuần: 0 17 \* \* sun
* Cứ 8 tiếng là chạy: 0 \*/8 \* \* \*
* Cứ 30 phút chạy một lần: \*/30 \* \* \* \*
* Cứ 5 phút lúc 5AM, bắt đầu lúc 5:10 AM: 10-59/5 5 \* \* \*
* Cứ chạy vào tháng 1,2,5 mỗi năm: \* \* \* 1,2,5 \*
* Cứ chạy vào ngày đầu tiên của tháng: 0 0 1 \* \*


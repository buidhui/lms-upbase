---
hidden: true
---

# Survey

## Record of changes

_A - Add M - Modify D - Delete_

| Effective Date | Update Person | A,M,D | Change Description             | Version |
| -------------- | ------------- | ----- | ------------------------------ | ------- |
| Jun 29, 2026   | Lê Thị Huế    | M     | Chuẩn hóa nội dung lên GitBook | 4.8.0   |

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên

**Đường dẫn:** [https://lms-pro.sapp.edu.vn/](https://lms-pro.sapp.edu.vn/)
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** Khảo sát khóa học (Survey)
* **Module liên quan:** My Course, Course Detail
* **Hệ thống tích hợp:** HubSpot (phiếu khảo sát được thực hiện trên HubSpot Forms)
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết:

* Học viên đăng nhập thành công vào hệ thống học tập tại [https://lms-pro.sapp.edu.vn/](https://lms-pro.sapp.edu.vn/).
* Tài khoản học viên có quyền truy cập Khóa học.
* Lớp học có Type = "Lesson".
{% endhint %}

### 1.1. Mục đích

Tài liệu này hướng dẫn học viên về quy trình hiển thị popup nhắc nhở thực hiện khảo sát và thao tác của học viên trên hệ thống LMS Pro, nhằm quản lý và theo dõi khảo sát của học viên cho lớp học chính thức.

### 1.2. Đối tượng & phạm vi áp dụng

| Vai trò  | Mô tả                                                                  | Phạm vi thao tác                                                                  |
| -------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Học viên | Người học đăng nhập vào hệ thống LMS Pro, thuộc lớp có Type = "Lesson" | Xem popup nhắc nhở khảo sát giữa khóa/cuối khóa; thực hiện hoặc nhắc lại khảo sát |

## II. Hướng dẫn chi tiết

<details>

<summary>Hệ thống hiển thị popup nhắc nhở khảo sát</summary>

{% hint style="warning" %}
**Điều kiện:**

* Học viên đăng nhập thành công vào hệ thống học tập LMS.
* Tài khoản học viên có quyền truy cập Khóa học.
{% endhint %}

Khi học viên đạt tiến độ yêu cầu, hệ thống hiển thị popup nhắc nhở khảo sát **vào lần tiếp theo** học viên mở lại khóa học. Popup hiển thị tại màn Course Detail (sau khi học viên mở khóa học).

{% stepper %}
{% step %}
**Popup khảo sát giữa khóa học**

* **Điều kiện:** Tiến độ học tập của học viên **lớn hơn hoặc bằng 50%** và **nhỏ hơn 90%**.

<figure><img src=".gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

* **Nơi hiển thị:** Màn Course Detail (sau khi học viên mở khóa học).

Nội dung hiển thị:

<figure><img src=".gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Popup khảo sát cuối khóa học**

* **Điều kiện:** Tiến độ học tập của học viên **lớn hơn hoặc bằng 90%**.

<figure><img src=".gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

* **Nơi hiển thị:** Màn Course Detail (sau khi học viên mở khóa học).

Nội dung hiển thị:

<figure><img src=".gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Học viên thao tác tại popup nhắc nhở khảo sát</summary>

{% stepper %}
{% step %}
**Chọn lựa chọn tại popup khảo sát**

Học viên thực hiện chọn 1 trong 2 lựa chọn tại popup khảo sát:

* **"Thực hiện khảo sát"** → Chuyển tiếp đến phiếu khảo sát trên HubSpot.
* **"Nhắc lại sau"** → Popup sẽ tiếp tục hiển thị lại sau 24h tính từ thời điểm click **"Nhắc lại sau"** khi học viên mở lại khóa học.
{% endstep %}

{% step %}
Học viên chọn “**Thực hiện khảo sát”**, hệ thống hiển thị popup xác nhận đã hoàn thành

Sau khi hoàn thành form khảo sát, học viên quay lại hệ thống LMS, và chọn **"Tôi đã hoàn thành"**

* **Điều kiện:** Học viên chọn **"Thực hiện khảo sát"** tại Bước 1.

<figure><img src=".gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

* **Nơi hiển thị:** Màn Course Detail (sau khi học viên mở khóa học).
{% endstep %}

{% step %}
**Bước 3: Học viên xác nhận hoàn thành khảo sát**

Học viên xác nhận hoàn thành khảo sát tại các lựa chọn của popup:

* **"Tôi đã hoàn thành"** → Popup nhắc nhở khảo sát (popup đầu tiên) sẽ không hiển thị lại với học viên tại lớp học này.
* **"Tôi sẽ làm sau"** → Học viên chọn khi chưa hoàn thành khảo sát; popup nhắc nhở khảo sát sẽ tiếp tục hiển thị lại sau 24h tính từ thời điểm click **"Tôi sẽ làm sau"** khi học viên mở lại khóa học.
{% endstep %}
{% endstepper %}

</details>

## III. Lưu Ý & Quy Tắc Nghiệp Vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Popup khảo sát chỉ áp dụng cho lớp học có Type = "Lesson".
2. Popup nhắc nhở khảo sát chỉ hiển thị khi học viên đạt mốc tiến độ tương ứng (≥ 50% và < 90% cho giữa khóa; ≥ 90% cho cuối khóa).
3. Popup chỉ hiển thị vào lần tiếp theo học viên mở lại khóa học sau khi đạt mốc tiến độ, không hiển thị ngay tức thời.
{% endhint %}

{% hint style="info" %}
### Mẹo sử dụng

1. Khi chưa sẵn sàng làm khảo sát, học viên chọn **"Nhắc lại sau"** / **"Tôi sẽ làm sau"** để popup hiển thị lại sau 24h.
{% endhint %}

## IV. Các Lỗi Thường Gặp & Cách Xử Lý

| Lỗi / Tình huống            | Nguyên nhân                                                                | Cách xử lý                                                                                         |
| --------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Không thấy popup khảo sát   | Tiến độ học tập chưa đạt mốc yêu cầu, hoặc lớp không thuộc Type = "Lesson" | Tiếp tục học để đạt mốc tiến độ; popup chỉ hiển thị với lớp Type = "Lesson"                        |
| Popup liên tục hiển thị lại | Học viên đã chọn "Nhắc lại sau" / "Tôi sẽ làm sau"                         | Popup sẽ hiển thị lại sau 24h; chọn "Tôi đã hoàn thành" sau khi làm xong khảo sát để dừng hiển thị |

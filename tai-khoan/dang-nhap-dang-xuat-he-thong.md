# Đăng nhập đăng xuất hệ thống

## Record of changes

_A - Add M - Modify D - Delete_

<table><thead><tr><th width="149">Effective Date</th><th>Update Person</th><th>A,M,D</th><th>Change Description</th><th>Version</th></tr></thead><tbody><tr><td>Jun 26, 2026</td><td>Lê Thị Huế</td><td>M</td><td>Tách &#x26; chuẩn hóa nội dung lên GitBook</td><td>4.8.0</td></tr></tbody></table>

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên

**Đường dẫn:** [http://lms-pro.sapp.edu.vn/auth/login](http://lms-pro.sapp.edu.vn/auth/login)
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** Đăng nhập / Đăng xuất (Authentication)
* **Module liên quan:** Quản lý tài khoản học viên (Operations)
* **Hệ thống tích hợp:** Hệ thống gửi email (OTP / liên kết đặt lại mật khẩu)
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết:

Học viên được cung cấp tài khoản thông qua 1 trong 3 cách sau:

* Học viên đăng ký Học thử/Thi thử thành công.
* Học viên làm thủ tục đăng ký khóa học thành công.
* Học viên được đội vận hành tạo tài khoản trên hệ thống vận hành Operations.
{% endhint %}

### 1.1. Mục đích

Tài liệu này hướng dẫn học viên các bước chi tiết để đăng nhập vào hệ thống LMS Student, xử lý các tình huống liên quan đến đăng nhập (quên mật khẩu, lưu đăng nhập) và đăng xuất khỏi hệ thống.

### 1.2. Đối tượng & phạm vi áp dụng

| Vai trò  | Mô tả                                            | Phạm vi thao tác                                   |
| -------- | ------------------------------------------------ | -------------------------------------------------- |
| Học viên | Người học đã được cấp tài khoản trên LMS Student | Đăng nhập, quên mật khẩu, lưu đăng nhập, đăng xuất |

## II. Hướng dẫn chi tiết

<details>

<summary>Đăng nhập vào hệ thống</summary>

{% stepper %}
{% step %}
**Truy cập hệ thống**

Truy cập hệ thống LMS Student theo link sau: [http://lms-pro.sapp.edu.vn/auth/login](http://lms-pro.sapp.edu.vn/auth/login)
{% endstep %}

{% step %}
## Nhập thông tin đăng nhập

* Username or Email (\*): nhập Username hoặc Email.
* Password (\*): nhập mật khẩu.

Người dùng có thể click icon 👁️ để hiển thị mật khẩu.

<figure><img src="../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Đăng nhập**

Click **Login** để đăng nhập vào hệ thống.

<figure><img src="../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

Học viên chỉ có thể đăng nhập cùng 1 tài khoản trên tối đa 3 thiết bị. Nếu đăng nhập cùng tài khoản đó trên thiết bị thứ 4, học viên cần liên hệ với đội ngũ vận hành của SAPP theo hướng dẫn trên màn hình để được hỗ trợ.

<figure><img src="../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Quên mật khẩu</summary>

{% stepper %}
{% step %}
**Mở màn hình Forgot Password**

Tại màn hình đăng nhập, click **Forgot Password?**

<figure><img src="../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Gửi yêu cầu lấy lại mật khẩu**

Tại màn hình Forgot Password, người dùng nhập Email dùng để tạo tài khoản và click **Send** để lấy mã OTP do hệ thống gửi về tài khoản Email đã nhập.

<figure><img src="../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>

| Message hiển thị     | Ghi chú             |
| -------------------- | ------------------- |
| Invalid Email        | Sai định dạng email |
| Email does not exist | Email không tồn tại |
{% endstep %}

{% step %}
**Kiểm tra email**

Truy cập Email, kiểm tra email hệ thống vừa gửi, bao gồm liên kết đặt lại mật khẩu.

<figure><img src="../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Nhập mật khẩu mới**

Người dùng bấm vào button "Đặt lại mật khẩu" trong email, lúc này hộp thoại để người dùng nhập mật khẩu hiển thị trên màn hình. Người dùng nhập mật khẩu mới thỏa mãn các điều kiện sau:

* Người dùng nhập mật khẩu mới và mật khẩu xác nhận trùng nhau.
* Yêu cầu về mật khẩu tối thiểu 8 ký tự và bao gồm ít nhất 1 chữ số và 1 ký tự in hoa.
* Người dùng có thể click icon 👁️ để hiển thị mật khẩu.

<figure><img src="../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
## Xác nhận đổi mật khẩu

Chọn **Submit** để đổi mật khẩu. Nếu mật khẩu mới hợp lệ, màn hình thông báo đổi mật khẩu thành công và hệ thống điều hướng tới màn hình Login. Lúc này, học viên có thể sử dụng Email và mật khẩu mới để đăng nhập vào hệ thống.
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Lưu đăng nhập</summary>

{% stepper %}
{% step %}
**Bật lưu đăng nhập**

Tại màn hình đăng nhập, click **Keep me logged in** để lưu đăng nhập cho những lần đăng nhập tiếp theo.

<figure><img src="../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Đăng xuất khỏi hệ thống</summary>

{% stepper %}
{% step %}
**Truy cập thông tin chi tiết của tài khoản**

Tại màn hình thông tin chi tiết của tài khoản, click **Log out** để đăng xuất và chuyển hướng đến màn hình đăng nhập.

<figure><img src="../.gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Thao tác đăng xuất**

Click **Log out** để đăng xuất và chuyển hướng đến màn hình đăng nhập.

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

</details>

## III. Lưu Ý & Quy Tắc Nghiệp Vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Mỗi tài khoản chỉ được đăng nhập đồng thời trên tối đa **3 thiết bị**. Khi đăng nhập trên thiết bị thứ 4, học viên cần liên hệ đội vận hành SAPP theo hướng dẫn trên màn hình.
2. Mật khẩu mới phải tối thiểu **8 ký tự**, bao gồm ít nhất **1 chữ số** và **1 ký tự in hoa**; mật khẩu xác nhận phải trùng với mật khẩu mới.
{% endhint %}

{% hint style="info" %}
### Mẹo sử dụng

1. Click icon con mắt 👁️ để hiển thị/ẩn mật khẩu khi nhập.
2. Bật **Keep me logged in** để không phải đăng nhập lại ở những lần truy cập sau.
{% endhint %}

## IV. Các Lỗi Thường Gặp & Cách Xử Lý

| Lỗi / Tình huống                       | Nguyên nhân                                              | Cách xử lý                                                                                          |
| -------------------------------------- | -------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Invalid Email                          | Email nhập sai định dạng                                 | Nhập lại đúng định dạng email                                                                       |
| Email does not exist                   | Email không tồn tại trong hệ thống                       | Kiểm tra lại email đăng ký, hoặc liên hệ đội vận hành SAPP                                          |
| Không đăng nhập được trên thiết bị mới | Tài khoản đã đăng nhập trên đủ 3 thiết bị                | Liên hệ đội vận hành SAPP theo hướng dẫn trên màn hình để được hỗ trợ                               |
| Không đặt lại được mật khẩu            | Mật khẩu mới chưa đủ điều kiện hoặc xác nhận không trùng | Nhập mật khẩu tối thiểu 8 ký tự, có ít nhất 1 chữ số và 1 ký tự in hoa, đảm bảo xác nhận trùng khớp |

---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: false
  tags:
    visible: true
  actions:
    visible: true
---

# Đăng nhập & Đăng xuất

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên

**Đường dẫn:**&#x20;
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** Đăng nhập/ Đăng xuất
* **Module liên quan:** Security
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết:

Học viên là nhân sự của UpBase và tài khoản được tạo trên hệ thống LMS
{% endhint %}

| Vai trò  | Mô tả                                            | Phạm vi thao tác                                   |
| -------- | ------------------------------------------------ | -------------------------------------------------- |
| Học viên | Người học đã được cấp tài khoản trên LMS Student | Đăng nhập, quên mật khẩu, lưu đăng nhập, đăng xuất |

## II. Hướng dẫn chi tiết

<details>

<summary>Đăng nhập vào hệ thống</summary>

{% stepper %}
{% step %}
**Truy cập hệ thống**

Truy cập hệ thống LMS theo link sau:

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Đăng nhập**

* Chọn đăng nhập SSO qua Lark
* Chọn đăng nhập qua mã Credential
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Đăng nhập lần đầu</summary>

Khi đăng nhập lần đầu thành công, hệ thống hiển thị phần hướng dẫn sử dụng (Product Tour) để giới thiệu giao diện.

{% stepper %}
{% step %}
**Bắt đầu Product Tour**

Tại hộp thoại chào mừng, chọn **Start Tour**.


{% endstep %}

{% step %}
**Đi qua các hộp thoại hướng dẫn**

Tại mỗi hộp thoại hướng dẫn, chọn **Next** để sang bước tiếp theo hoặc **Previous** để quay lại bước trước đó.


{% endstep %}
{% endstepper %}

{% hint style="info" %}
Product Tour chỉ hiển thị tự động ở lần đăng nhập đầu tiên. Nếu tài khoản đã đăng nhập trước đó, hộp thoại này sẽ không xuất hiện.
{% endhint %}

</details>

<details>

<summary>Quên mật khẩu</summary>

{% stepper %}
{% step %}
**Mở màn hình Forgot Password**

Tại màn hình đăng nhập, click **Forgot Password?**

<figure><img src="/broken/files/ioGvcmO5T5912jWwODqS" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Gửi yêu cầu lấy lại mật khẩu**

Tại màn hình Forgot Password, người dùng nhập Email dùng để tạo tài khoản và click **Send** để lấy mã OTP do hệ thống gửi về tài khoản Email đã nhập.

<figure><img src="/broken/files/vkICqhtUFYzi09z4ZMzk" alt=""><figcaption></figcaption></figure>

| Message hiển thị     | Ghi chú             |
| -------------------- | ------------------- |
| Invalid Email        | Sai định dạng email |
| Email does not exist | Email không tồn tại |
{% endstep %}

{% step %}
**Kiểm tra email**

Truy cập Email, kiểm tra email hệ thống vừa gửi, bao gồm liên kết đặt lại mật khẩu.

<figure><img src="/broken/files/6bzXysM78qclcilGovCp" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Nhập mật khẩu mới**

Người dùng bấm vào button "Đặt lại mật khẩu" trong email, lúc này hộp thoại để người dùng nhập mật khẩu hiển thị trên màn hình. Người dùng nhập mật khẩu mới thỏa mãn các điều kiện sau:

* Người dùng nhập mật khẩu mới và mật khẩu xác nhận trùng nhau.
* Yêu cầu về mật khẩu tối thiểu 8 ký tự và bao gồm ít nhất 1 chữ số và 1 ký tự in hoa.
* Người dùng có thể click icon 👁️ để hiển thị mật khẩu.

<figure><img src="/broken/files/GuBvavitrPQ1UPJdYh2p" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Xác nhận đổi mật khẩu**

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

<figure><img src="/broken/files/mS5RTazhUHMncJF8KorD" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Đăng xuất khỏi hệ thống</summary>

Tại màn hình thông tin chi tiết của tài khoản, chọn **Logout** để đăng xuất và chuyển hướng đến màn hình đăng nhập.

<figure><img src="../.gitbook/assets/User Profile - Overview.png" alt=""><figcaption></figcaption></figure>

</details>

## III. Lưu ý & Quy tắc nghiệp vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Hệ thống đăng nhập qua phương thức SSO Lark, do đó không có chức năng Quên mật khẩu.
{% endhint %}

## IV. Các lỗi thường gặp & Hướng dẫn xử lý

| Lỗi / Tình huống | Nguyên nhân                                                            | Cách xử lý                          |
| ---------------- | ---------------------------------------------------------------------- | ----------------------------------- |
| Không đăng nhập  | Chưa có tài khoản Lark, hoặc tài khoản Lark chưa thuộc tổ chức UpBasse | Liên hệ đội vận hành để được hỗ trợ |

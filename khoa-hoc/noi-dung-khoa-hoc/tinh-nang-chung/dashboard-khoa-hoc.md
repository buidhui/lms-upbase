---
description: Theo dõi tiến độ và kết quả học tập của khóa học qua các biểu đồ Dashboard.
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

# Dashboard khoá học

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên (Student)

**Đường dẫn:** LMS → My Course → \[Chọn Khóa học] → Dashboard
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** LMS Student — Dashboard (Khóa học)
* **Module liên quan:** My Course, Course Content, Test/Quiz, Class Management
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết

* Học viên đã đăng nhập thành công vào hệ thống LMS.
* Tài khoản đã được thêm vào Lớp (Class) gắn với Khóa học.
* Lớp có Status = **Resume** hoặc **Review** thì khi click vào Lớp, hệ thống chuyển đến màn Dashboard. Với Lớp có Status = **Ready to learn**, hệ thống chuyển đến màn Course Content (chưa có Dashboard).
{% endhint %}

## II. Tổng quan giao diện

Màn hình **Dashboard** hiển thị các biểu đồ theo dõi tiến độ và kết quả học tập của học viên trong Khóa học.

| Biểu đồ                   | Mô tả                                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------------------- |
| **Overall Progress**      | Tiến độ học tập tổng thể của học viên trong Khóa học.                                               |
| **This Week**             | So sánh số Activities hoàn thiện & thời gian học (Learning times) của tuần này với tuần liền trước. |
| **Topic Progress**        | Tiến độ học theo từng Section. Mỗi cột tương ứng với một Section.                                   |
| **Your Learning Results** | Kết quả học tập theo Section, tính dựa trên kết quả các bài test.                                   |

## III. Hướng dẫn chi tiết

<details>

<summary>Truy cập Dashboard Khóa học</summary>

{% stepper %}
{% step %}
**Truy cập Khóa học tại màn hình My Course**

Sau khi đăng nhập thành công, tại màn hình **My Course**, học viên click vào Khóa học cần xem.

<figure><img src="../../../.gitbook/assets/image (240).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Mở Dashboard từ Course Content**

Tại màn hình **Course Content**, click vào **Dashboard** để chuyển đến màn hình theo dõi tiến độ học tập.

<figure><img src="../../../.gitbook/assets/image (249).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
* Với Lớp có Status = **Resume** hoặc **Review** → click vào Lớp, hệ thống chuyển đến màn Dashboard.
* Với Lớp có Status = **Ready to learn** → click vào Lớp, hệ thống chuyển đến màn Course Content (chưa có Dashboard).
{% endhint %}
{% endstep %}
{% endstepper %}

</details>

<details>

<summary>Đọc các biểu đồ trên Dashboard</summary>

Tại màn hình Dashboard, học viên có thể xem các biểu đồ sau:

#### Overall Progress

Tiến độ học tập của học viên trong Khóa học.

> **Công thức:** Overall progress = Số activities đã hoàn thiện / Tổng số activities của Khóa học

<figure><img src="../../../.gitbook/assets/image (243).png" alt=""><figcaption></figcaption></figure>

#### This Week

So sánh số activities đã hoàn thiện & thời gian học đến thời điểm hiện tại của tuần này với tổng của tuần liền trước:

* Tuần này **> tuần trước:** hiển thị _"You've outperformed last week! Aim higher!"_
* Tuần này **= tuần trước:** hiển thị _"You've matched last week's progress. Go further!"_
* Tuần này **< tuần trước:** hiển thị _"More activities/minutes to outperform last week"_

<figure><img src="../../../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

#### Topic Progress

Tiến độ học theo từng Section. Mỗi cột tương ứng với một Section.

> **Công thức:** Topic progress = Số activities đã hoàn thiện trong Section / Tổng số activities của Section đó

<figure><img src="../../../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>

#### Your Learning Results

Kết quả học tập của học viên theo Section, tính dựa trên kết quả các bài test đã làm.

{% hint style="info" %}
**Công thức tính % Results được cấu hình riêng theo từng chương trình học.** Mỗi chương trình có bộ trọng số riêng cho các loại bài test (Module test, Topic test, Final test, Graded activities…).

_Ví dụ:_ một chương trình có thể tính % Results = **Module test (40%) + Topic test (60%)**; chương trình khác = **Topic test (30%) + Final test (70%)**.

Khi học viên click **Your Learning Results**, hệ thống hiển thị công thức tính đang áp dụng cho khóa học của mình.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (247).png" alt=""><figcaption></figcaption></figure>

Ở giữa biểu đồ là **Điểm trung bình tổng thể (Overall average score)** — trung bình kết quả của tất cả các Section đã ghi nhận điểm thành phần.

<figure><img src="../../../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>

</details>

## IV. Lưu Ý & Quy Tắc Nghiệp Vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Dashboard chỉ hiển thị khi Lớp có Status = **Resume** hoặc **Review**. Lớp có Status = **Ready to learn** sẽ điều hướng thẳng tới Course Content.
2. **Overall Progress** tính trên **tổng số Activities** của Khóa học — không phân biệt loại Activity.
3. **This Week** chỉ so sánh với tuần liền trước, không so sánh với các tuần khác trong quá khứ.
4. **Your Learning Results** dùng công thức khác nhau tùy chương trình học — click vào biểu đồ để xem công thức áp dụng cho khóa học của mình.
5. Khi học viên chỉ làm **1 trong 2 bài test**, trọng số bài test đã làm được tính là **100%** trong công thức Learning Results.
6. Với một số chương trình, kết quả Final test trong công thức Learning Results chỉ tính trên các câu **trắc nghiệm**.
7. **Overall average score** chỉ tính trung bình của các Section đã ghi nhận điểm — Section chưa có điểm không tham gia tính.
{% endhint %}

{% hint style="info" %}
### Mẹo sử dụng

1. Theo dõi **This Week** thường xuyên để duy trì động lực so với tuần trước.
2. Dùng **Topic Progress** để xác định Section còn yếu và cần học thêm.
3. Click vào **Your Learning Results** để xem công thức tính áp dụng cho khóa học của mình.
4. Đặt mục tiêu **Overall Progress** theo tuần (ví dụ: tăng 10%/tuần) để có lộ trình học rõ ràng.
{% endhint %}

## V. Các Lỗi Thường Gặp & Cách Xử Lý

| Lỗi / Tình huống                                           | Nguyên nhân                                                                         | Cách xử lý                                                                                 |
| ---------------------------------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Click vào Lớp nhưng không hiển thị Dashboard               | Lớp đang có Status = **Ready to learn**                                             | Hoàn thành ít nhất một Activity để Lớp chuyển sang Status = Resume; Dashboard sẽ hiển thị. |
| **Overall Progress** không tăng dù đã học                  | Activities chưa được đánh dấu hoàn thành                                            | Kiểm tra trạng thái Completed của từng Activity; hoàn thiện các Activity còn dở.           |
| **This Week** vẫn hiển thị _"More activities…"_            | Số Activities/thời gian học tuần này chưa vượt tuần trước                           | Tiếp tục học để vượt kết quả tuần trước; thông báo sẽ tự cập nhật.                         |
| **Topic Progress** một Section vẫn = 0% dù đã học          | Activity hoàn thành nằm ngoài Section đó, hoặc Section còn Activity chưa hoàn thành | Kiểm tra danh sách Activity của Section trong Course Content và hoàn thiện đầy đủ.         |
| **Your Learning Results** không có dữ liệu cho một Section | Học viên chưa làm bài test nào của Section đó                                       | Hoàn thành các bài test tương ứng của Section.                                             |
| Điểm Learning Results khác với điểm khi làm bài            | Công thức tính theo chương trình kết hợp nhiều loại test với trọng số khác nhau     | Click vào **Your Learning Results** để xem công thức chi tiết.                             |
| **Overall average score** thấp hơn dự kiến                 | Các Section có điểm thấp kéo trung bình xuống                                       | Xem Topic Progress để xác định Section yếu, ưu tiên làm lại bài test các Section đó.       |

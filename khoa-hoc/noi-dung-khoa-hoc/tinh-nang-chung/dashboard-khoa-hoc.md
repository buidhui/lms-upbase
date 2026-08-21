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
**Dành cho:** Học viên

**Đường dẫn:** My Course → Course Detail → Dashboard
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** Dashboard (Khóa học)
* **Module liên quan:** My Learning, Learning Activity, Test Activity
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết

* Học viên đã đăng nhập thành công vào hệ thống UpLMS.
* Khóa học có Status = **Resume** hoặc **Review**. Khóa có Status = **Ready to learn** chưa có Dashboard.
{% endhint %}

## II. Hướng dẫn chi tiết

<details>

<summary>Truy cập Dashboard Khóa học</summary>

Chọn Dashboard từ Sidebar trong một khóa học để truy cập Dashboard của khóa học đó.

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
* Khóa có Status = **Resume** hoặc **Review** → click vào Khóa, hệ thống chuyển ngay đến màn Dashboard.
* Khóa có Status = **Ready to learn** → click vào Khóa, hệ thống chuyển ngay đến màn Course Content (chưa có Dashboard).
{% endhint %}

</details>

<details>

<summary>Giải thích Dashboard</summary>

**Overall Progress:** Tiến độ học tập của học viên trong Khóa học.

> **Công thức:** Overall progress = Số Activities đã hoàn thành / Tổng số Activities của Khóa học

<figure><img src="../../../.gitbook/assets/Course Dashboard.png" alt=""><figcaption></figcaption></figure>

**This Week:** So sánh số Activities đã hoàn thành & thời gian học đến thời điểm hiện tại của tuần này với tổng của tuần liền trước:

* Tuần này **> tuần trước:** hiển thị _"You've outperformed last week! Aim higher!"_
* Tuần này **= tuần trước:** hiển thị _"You've matched last week's progress. Go further!"_
* Tuần này **< tuần trước:** hiển thị _"More activities/minutes to outperform last week"_

<figure><img src="../../../.gitbook/assets/Course Dashboard 2.png" alt=""><figcaption></figcaption></figure>

**Section Progress:** Tiến độ học theo từng Section, mỗi cột tương ứng với một Section.

> **Công thức:** Progress = Số Activities đã hoàn thành trong Section / Tổng số Activities của Section đó

<figure><img src="../../../.gitbook/assets/Course Dashboard 4.png" alt=""><figcaption></figcaption></figure>

**Your Learning Results:** Kết quả học tập của học viên theo Section, tính dựa trên kết quả các bài Test đã làm.

* Ở giữa biểu đồ là **Điểm trung bình tổng thể (Overall average score):** trung bình kết quả của tất cả các Section đã ghi nhận điểm thành phần.

<figure><img src="../../../.gitbook/assets/Course Dashboard 5.png" alt=""><figcaption></figcaption></figure>



</details>

## III. Lưu ý & Quy tắc nghiệp vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. **Overall Progress** tính trên **tổng số Activities** của Khóa học, không phân biệt loại Activity.
2. **This Week** chỉ so sánh với tuần liền trước, không so sánh với các tuần khác trong quá khứ.
3. **Overall average score** chỉ tính trung bình của các Section đã ghi nhận điểm, Section chưa có điểm không tham gia tính.
{% endhint %}

{% hint style="info" %}
### Mẹo sử dụng

1. Theo dõi **This Week** thường xuyên để duy trì động lực so với tuần trước.
2. Dùng **Section Progress** để xác định Section còn yếu và cần học thêm.
3. Đặt mục tiêu **Overall Progress** theo tuần (ví dụ: tăng 10%/tuần) để có lộ trình học rõ ràng.
{% endhint %}

## IV. Các lỗi thường gặp & Hướng dẫn xử lý

| Lỗi / Tình huống                                           | Nguyên nhân                                                                         | Cách xử lý                                                                                       |
| ---------------------------------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Click vào Lớp nhưng không hiển thị Dashboard               | Lớp đang có Status = **Ready to learn**                                             | Hoàn thành ít nhất một Activity để Lớp chuyển sang Status = Resume sau đó Dashboard sẽ hiển thị. |
| **Overall Progress** không tăng dù đã học                  | Activities chưa được đánh dấu hoàn thành                                            | Kiểm tra trạng thái Completed của từng Activity.                                                 |
| **This Week** vẫn hiển thị _"More activities…"_            | Số Activities/ thời gian học tuần này chưa vượt tuần trước                          | Tiếp tục học để vượt kết quả tuần trước, thông báo sẽ tự cập nhật.                               |
| **Section Progress** một Section vẫn = 0% dù đã học        | Activity hoàn thành nằm ngoài Section đó, hoặc Section còn Activity chưa hoàn thành | Kiểm tra danh sách Activity của Section trong Course Content.                                    |
| **Your Learning Results** không có dữ liệu cho một Section | Học viên chưa làm bài Test nào của Section đó                                       | Hoàn thành các bài Test tương ứng của Section.                                                   |
| **Overall average score** thấp hơn dự kiến                 | Các Section có điểm thấp kéo trung bình xuống                                       | Xem Section Progress để xác định Section yếu, ưu tiên làm lại bài Test các Section đó.           |

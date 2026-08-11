# Dashboard Tiến độ học - Normal Course

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên (Student)

**Đường dẫn:** LMS → My Course → \[Chọn Course có Type = Normal Course] → Dashboard
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** LMS Student — Dashboard (Khóa học)
* **Phạm vi áp dụng:** Course có **Type = Lesson** (Khóa chính / Khóa học)
* **Module liên quan:** My Course, Course Content, Test/Quiz, Class Management
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết

* User đã đăng nhập thành công vào hệ thống LMS.
* Tài khoản User đã được thêm vào Class gắn với Course có **Type = Lesson**
* Class có Status = **Resume** hoặc **Review** thì khi click vào Class, hệ thống sẽ chuyển đến màn Dashboard. Với Class có Status = **Ready to learn**, hệ thống chuyển đến màn Course Content (không có Dashboard).
{% endhint %}

## II. Tổng quan giao diện

_Giao diện màn hình Student Dashboard — Normal Course_

Màn hình **Dashboard Khóa học** hiển thị các biểu đồ theo dõi tiến độ và kết quả học tập của học viên trong Normal Course.

#### Các thành phần biểu đồ chính

| Biểu đồ                   | Mô tả                                                                               |
| ------------------------- | ----------------------------------------------------------------------------------- |
| **Overall Progress**      | Tiến độ học tập tổng thể của học viên trong Course.                                 |
| **This Week**             | So sánh số Activities hoàn thiện & Learning times của tuần này với tuần liền trước. |
| **Topic Progress**        | Tiến độ học theo từng Section của Course. Mỗi cột tương ứng với một Section.        |
| **Your Learning Results** | Kết quả học tập của học viên theo Section, tính dựa trên kết quả các bài test.      |
| **Ongoing Activities**    | Hoạt động đang diễn ra _(chưa phát triển tính năng tại giai đoạn này)._             |

## III. Hướng dẫn chi tiết

<details>

<summary>Truy cập Dashboard Khóa học</summary>

{% stepper %}
{% step %}
**Truy cập Course có Type = Normal Course**

Sau khi đăng nhập thành công, tại màn hình **My Course**, User click vào Course có **Type = Class**.

<figure><img src="../../../.gitbook/assets/image (240).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Mở Dashboard từ Course Content**

Tại màn hình **Course Content**, User click vào **Dashboard** để chuyển đến màn hình Dashboard theo dõi tiến độ học tập.

<figure><img src="../../../.gitbook/assets/image (241).png" alt=""><figcaption></figcaption></figure>

_Giao diện màn hình Student Dashboard hiển thị:_

<figure><img src="../../../.gitbook/assets/image (249).png" alt=""><figcaption></figcaption></figure>

* Với Class có Status = **Resume**, **Review** → khi click vào Class, hệ thống chuyển đến màn Dashboard.
* Với Class có Status = **Ready to learn** → khi click vào Class, hệ thống chuyển đến màn Course Content (không có Dashboard).
{% endstep %}

{% step %}
**Xem các biểu đồ theo dõi tiến độ của khóa học**

Tại màn hình Dashboard, User có thể xem các biểu đồ theo dõi tiến độ học tập của khóa học, cụ thể:

{% stepper %}
{% step %}
**Overall Progress:**

Biểu đồ hiển thị tiến độ học tập của học viên trong Course

Công thức tính: **Overall progress = Số activities đã hoàn thiện/Tổng số activities của Course**

<figure><img src="../../../.gitbook/assets/image (243).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**This week**

Hiển thị số activities đã hoàn thiện & learning times đến thời điểm hiện tại của tuần này so với tổng số activities đã hoàn thiện & learning times của tuần liền trước.

* **Số Completed Activities/Learning Times** cho đến thời điểm hiện tại của tuần này > tổng của tuần liền trước đó, hiển thị text "You've outperformed last week! Aim higher!"
* **Số Completed Activities/Learning Times** cho đến thời điểm hiện tại của tuần này = tổng của tuần liền trước đó, hiển thị text "You've matched last week's progress. Go further!"

<figure><img src="../../../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

* **Số Completed Activities/Learning Times** cho đến thời điểm hiện tại của tuần này < tổng của tuần liền trước đó, hiển thị text "More activities/minutes to outperform last week"

<figure><img src="../../../.gitbook/assets/image (245).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Topic Progress:**

Biểu đồ hiển thị tiến độ học theo Section của Course. Mỗi cột tương ứng với một Section của Course

* Công thức tính: **Topic progress = Số activities đã hoàn thiện trong từng section/Tổng số activities của section đó**

<figure><img src="../../../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Your Learning Results:**

Biểu đồ hiển thị kết quả học tập của học viên theo Section. Mỗi trục tương ứng với một Section của Course

* Công thức tính dựa theo kết quả các bài test học viên đã làm, cụ thể:
  * CFA: % Results = Module test (40%) + Topic test (60%)
  * ACCA: % Results = Graded activities (70%) + Final test (30%)
  * CMA: %Results = Module test (40%) + Topic test (60%)
  * L\&D: % Results = Topic test (30%) + Final test (70%)
* Khi User click **Your Learning Results,** hiển thị công thức tính kết quả theo chương trình học

{% hint style="info" %}
- Trường hợp học viên làm 1/2 bài test, trọng số bài test trong công thức được tính là 100%
  * Ví dụ: với chương trình CFA/CMA, khi học viên làm xong Module test, mà chưa làm Topic test, thì\
    trọng số của bài Module test là 100% hay % Results = Mock test (100%)
- Đối với công tính của ACCA, kết quả Final test chỉ dựa trên kết quả của các câu trắc nghiệm
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (247).png" alt=""><figcaption></figcaption></figure>

*   Ở giữa biểu đồ thể hiện **Điểm trung bình tổng thể (Overall average score)**. Cách tính dựa trên điểm **trung bình kết quả của tất cả các section** đã ghi nhận điểm thành phần.

    <figure><img src="../../../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
{% endstep %}
{% endstepper %}

</details>

## IV. Lưu Ý & Quy Tắc Nghiệp Vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Dashboard chỉ hiển thị khi Class có Status = **Resume** hoặc **Review**. Class có Status = **Ready to learn** sẽ điều hướng thẳng tới Course Content, không có Dashboard.
2. Công thức tính **Overall Progress** dựa trên **tổng số Activities** của Course — không phân biệt loại Activity.
3. Biểu đồ **This Week** chỉ so sánh với tuần liền trước, không so sánh với tuần khác trong quá khứ.
4. Công thức tính **Your Learning Results** khác nhau theo từng chương trình (CFA, ACCA, CMA, L\&D) — cần đối chiếu đúng chương trình của Course.
5. Khi học viên chỉ làm **1/2 bài test**, trọng số bài test được tính là **100%** trong công thức Learning Results.
6. Với **ACCA**, kết quả Final test trong công thức Learning Results chỉ tính dựa trên các câu trắc nghiệm.
7. **Overall average score** chỉ tính trung bình của các Section đã ghi nhận điểm thành phần — các Section chưa có điểm sẽ không tham gia tính trung bình.
{% endhint %}

{% hint style="info" %}
### Mẹo sử dụng

1. Theo dõi **This Week** thường xuyên để duy trì động lực và cải thiện hiệu quả học tập so với tuần trước.
2. Sử dụng **Topic Progress** để xác định Section nào còn yếu và cần dành thời gian học thêm.
3. Click trực tiếp vào **Your Learning Results** để xem công thức tính theo chương trình học của mình.
4. Khi học song song với khóa ôn (Practice Course) có liên kết, hãy ưu tiên hoàn thành test ở khóa chính (Normal Course) vì kết quả này sẽ được phản ánh trong Dashboard khóa ôn.
5. Đặt mục tiêu **Overall Progress** theo tuần (ví dụ: tăng 10%/tuần) để có lộ trình học rõ ràng.
{% endhint %}

## V. Các Lỗi Thường Gặp & Cách Xử Lý

| Lỗi / Tình huống                                           | Nguyên nhân                                                                        | Cách xử lý                                                                                                 |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Click vào Class nhưng không hiển thị Dashboard             | Class đang có Status = **Ready to learn**                                          | Hoàn thành ít nhất một Activity để Class chuyển sang Status = Resume; Dashboard sẽ hiển thị.               |
| **Overall Progress** không tăng dù đã học                  | Activities học chưa được đánh dấu hoàn thành                                       | Kiểm tra trạng thái Completed của từng Activity; quay lại hoàn thiện các Activity còn dở.                  |
| **This Week** vẫn hiển thị thông báo "More activities..."  | Số Activities/Learning times tuần này chưa vượt tuần trước                         | Tiếp tục học để vượt qua kết quả tuần trước; thông báo sẽ tự cập nhật.                                     |
| **Topic Progress** một Section vẫn = 0% dù đã học          | Activity hoàn thành nằm ngoài Section đó, hoặc Section có Activity chưa hoàn thành | Kiểm tra danh sách Activity của Section trong Course Content và hoàn thiện đầy đủ.                         |
| **Your Learning Results** không có dữ liệu cho một Section | Học viên chưa làm bài test nào của Section đó                                      | Hoàn thành các bài test (Module test / Topic test / Final test / Graded activities) tương ứng của Section. |
| Điểm Learning Results khác với điểm khi làm bài            | Công thức tính theo chương trình kết hợp nhiều loại test với trọng số khác nhau    | Click vào **Your Learning Results** để xem công thức chi tiết của chương trình.                            |
| **Overall average score** thấp hơn dự kiến                 | Các Section có điểm thấp kéo trung bình xuống                                      | Xem Topic Progress để xác định Section yếu, ưu tiên làm lại bài test các Section đó.                       |
| **Ongoing Activities** không hiển thị dữ liệu              | Tính năng chưa được phát triển tại giai đoạn này                                   | Đây là trạng thái mặc định ở thời điểm hiện tại — sẽ được phát triển trong các phiên bản tiếp theo.        |

# Dashboard Tiến độ học - Practice / Revision Course

## I. Thông tin chung

{% hint style="info" %}
**Dành cho:** Học viên (Student)

**Đường dẫn:** LMS → My Course → \[Chọn Course có Type = Practice Course] → Dashboard
{% endhint %}

{% hint style="info" %}
#### Phạm vi & Module liên quan

* **Module chính:** LMS Student — Dashboard (Khóa ôn thi)
* **Phạm vi áp dụng:** Course có **Type = Revision** (Khóa ôn / Khóa thi)
* **Module liên quan:** My Course, Course Content, Mock Test, Class Management
* **Liên kết với khóa chính:** Practice Course có thể **liên kết** với Normal Course (khóa ôn được tạo tự động khi học viên chọn kỳ thi trong lớp chính) hoặc **độc lập** (học viên được thêm thủ công vào lớp ôn).
{% endhint %}

{% hint style="warning" %}
#### Điều kiện tiên quyết

* User đã đăng nhập thành công vào hệ thống LMS.
* Tài khoản User đã được thêm vào Class gắn với Course có **Type = Revision.**
* Class có Status = **Resume** hoặc **Review** thì khi click vào Class, hệ thống sẽ chuyển đến màn Dashboard. Với Class có Status = **Ready to learn**, hệ thống chuyển đến màn Course Content (không có Dashboard).
{% endhint %}

## II. Tổng quan giao diện

_Giao diện màn hình Student Dashboard — Revision._

Màn hình **Dashboard Khóa ôn thi** hiển thị các biểu đồ theo dõi tiến độ ôn tập, dự đoán mức độ sẵn sàng thi và kết quả Mock test của học viên.

#### Các thành phần biểu đồ chính

| Biểu đồ                   | Mô tả                                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------------------- |
| **Topic Progress**        | Tiến độ học theo từng Section của Course. Mỗi cột tương ứng với một Section.                        |
| **Your Exam Prediction**  | Mức độ sẵn sàng cho kỳ thi của học viên.                                                            |
| **Your Learning Results** | Kết quả học tập theo Section — hiển thị khác nhau tùy khóa ôn có liên kết với khóa chính hay không. |
| **Mock test results**     | Kết quả bài Mock test thể hiện theo Section.                                                        |
| **Ongoing Activities**    | Hoạt động đang diễn ra _(chưa phát triển tính năng tại giai đoạn này)._                             |

#### Phân biệt khóa ôn liên kết và khóa ôn độc lập

| Loại                       | Định nghĩa                                                                                                                    |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Khóa ôn CÓ liên kết**    | Khi học viên chọn kỳ thi trong lớp chính, hệ thống tự động thêm học viên vào lớp ôn → khóa ôn này có liên kết với khóa chính. |
| **Khóa ôn KHÔNG liên kết** | Học viên được thêm thủ công vào lớp ôn (không phải lớp được tạo tự động khi chọn kỳ thi) → khóa ôn độc lập.                   |

## III. Hướng dẫn chi tiết

<details>

<summary>Truy cập Dashboard Khóa ôn thi</summary>

{% stepper %}
{% step %}
**Truy cập Course có Type = Practice Course**

Sau khi đăng nhập thành công, tại màn hình **My Course**, User click vào Course có **Type = Revision**

_Màn hình My Course — click vào Course dạng Revision_

<figure><img src="../../../.gitbook/assets/Screenshot 2026-06-23 162245.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Mở Dashboard từ Course Content**

Tại màn hình **Course Content**, User click vào **Dashboard** để chuyển đến màn hình Dashboard theo dõi tiến độ học tập.

_Màn hình Course Content (Practice Course) — click Dashboard_

<figure><img src="../../../.gitbook/assets/image (250).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
* Với Class có Status = **Resume**, **Review** → khi click vào Class, hệ thống chuyển đến màn Dashboard.
* Với Class có Status = **Ready to learn** → khi click vào Class, hệ thống chuyển đến màn Course Content (không có Dashboard).
{% endhint %}
{% endstep %}

{% step %}
**Xem các biểu đồ theo dõi tiến độ khóa ôn tập**

{% stepper %}
{% step %}
**Biểu đồ Your Learning Results — Khóa ôn CÓ liên kết với khóa chính**

_**Định nghĩa liên kết:**_ _Khi học viên chọn kỳ thi trong lớp chính, học viên sẽ được tự động thêm vào lớp ôn. Khi đó khóa ôn có liên kết với khóa chính._

<figure><img src="../../../.gitbook/assets/image (256).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
**Xem Learning Results (copy từ khóa chính)**

**Learning Results:** Biểu đồ **copy nguyên** các trục (Section) và dữ liệu các trục của biểu đồ "Learning Results" thuộc **Khóa chính (Normal Course)**.

{% hint style="warning" %}
⚠️ Kết quả các bài Test thuộc Section của **Khóa ôn (Practice Course) KHÔNG ảnh hưởng** đến biểu đồ này.
{% endhint %}

**Công thức tính** dựa theo kết quả các bài test học viên đã làm trong Khóa ôn, theo từng chương trình:

| Chương trình | Công thức tính % Results                   |
| ------------ | ------------------------------------------ |
| **CFA**      | Module test (40%) + Topic test (60%)       |
| **ACCA**     | Graded activities (70%) + Final test (30%) |
| **CMA**      | Module test (40%) + Topic test (60%)       |
| **L\&D**     | Topic test (30%) + Final test (70%)        |
{% endstep %}

{% step %}
**Xem Mock test results**

**Mock test results:**

* **Các trục Section:** Lấy nguyên các trục của khóa chính như trục của Learning Results. **Không lấy** các trục Section của khóa ôn.
* Kết quả bài Mock test được map vào sơ đồ dựa theo trường **"Belong to section"** của câu hỏi.
{% endstep %}
{% endstepper %}
{% endstep %}

{% step %}
**Biểu đồ Your Learning Results — Khóa ôn KHÔNG liên kết với khóa chính**

_**Định nghĩa không liên kết:**_ _Học viên được thêm thủ công vào lớp ôn, lớp ôn này không phải lớp được tạo tự động khi học viên chọn kỳ thi trong lớp chính. Khi đó khóa ôn không liên kết với khóa chính._

_Course chỉ có Mock test result_

<img src="../../../.gitbook/assets/image (257).png" alt="" data-size="original">

{% stepper %}
{% step %}
**Xem Mock test results**

**Mock test results:**

* **Các trục Section:** Lấy các trục của khóa ôn (Practice Course).
* **Dữ liệu mỗi trục Section:** Tính dựa trên điểm của các câu hỏi trong Mock Test thuộc Section. Trường **"Belong to section"** của câu hỏi sẽ xác định câu hỏi thuộc Section nào của khóa ôn.
  * _Ví dụ:_ Mock test có nhiều câu hỏi thuộc các section khác nhau. Câu 1 thuộc Section A, câu 2 và câu 3 thuộc Section B,... → Thì biểu đồ Mock Test result thể hiện tại Section A là kết quả của câu 1, Section B là kết quả của câu 2 + câu 3...
* **Công thức tính:** điểm đạt được của từng section / tổng điểm max của section đó.
* Khi click vào **"Mock test results"**, hệ thống chuyển tới kết quả bài Mock test để học viên có thể xem lại bài làm của mình.
{% endstep %}
{% endstepper %}
{% endstep %}

{% step %}
**Learning & Mock test Comparision**

So sánh kết quả Learning & Mock test theo từng section

<figure><img src="../../../.gitbook/assets/image (253).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Topic Progress**

Biểu đồ hiển thị tiến độ học theo Section của Course. Mỗi cột tương ứng với một Section của Course

* Công thức tính: **Topic progress = Số activities đã hoàn thiện trong từng section/Tổng số activities của section đó**

<figure><img src="../../../.gitbook/assets/image (254).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
**Your Exam Prediction**

Biểu đồ hiển thị mức độ sẵn sàng cho thi cử

* Công thức tính: **Exam readiness = Topic Progress (30%) + Mock test result (70%)**

<figure><img src="../../../.gitbook/assets/image (255).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}
{% endstep %}
{% endstepper %}

</details>

## IV. Lưu Ý & Quy Tắc Nghiệp Vụ

{% hint style="warning" %}
### Lưu ý quan trọng

1. Dashboard chỉ hiển thị khi Class có Status = **Resume** hoặc **Review**. Class có Status = **Ready to learn** sẽ điều hướng thẳng tới Course Content, không có Dashboard.
2. **Khóa ôn CÓ liên kết với khóa chính:**
   * **Learning Results** trong Practice Course **copy nguyên** từ Khóa chính, không phản ánh kết quả test trong Khóa ôn.
   * **Mock test results** dùng các Section của **khóa chính**, không dùng Section của khóa ôn.
3. **Khóa ôn KHÔNG liên kết (độc lập):**
   * **Learning Results** & **Mock test results** đều dùng các Section của chính Khóa ôn.
   * Công thức tính Learning Results khác nhau theo chương trình (CFA, ACCA, CMA, L\&D).
   * Khi học viên chỉ làm **1/2 bài test**, trọng số bài test được tính là **100%**.
   * Với **ACCA**, kết quả Final test chỉ tính dựa trên các câu trắc nghiệm.
4. **Mock test result** phân bổ điểm theo Section dựa trên trường **"Belong to section"** của từng câu hỏi.
5. **Exam readiness** được tính dựa trên **Topic Progress (30%) + Mock test result (70%)** — Mock test có trọng số cao hơn, nên cần ưu tiên làm Mock test để cải thiện dự đoán.
6. Biểu đồ **Ongoing Activities** hiện tại chưa được phát triển tính năng.
{% endhint %}

{% hint style="info" %}
### Mẹo sử dụng

1. Đối chiếu **Your Exam Prediction** với mục tiêu để biết mức độ sẵn sàng và điều chỉnh kế hoạch ôn thi.
2. Khi học khóa ôn **có liên kết** với khóa chính, cần ưu tiên hoàn thành test ở khóa chính (Normal Course) vì kết quả này sẽ được phản ánh trong Dashboard khóa ôn.
3. Khi học khóa ôn **độc lập**, làm các bài test (Module/Topic/Final/Graded activities) trong chính khóa ôn để Learning Results được cập nhật.
4. Sử dụng **Topic Progress** để xác định Section nào còn yếu, tập trung ôn các Section đó trước khi làm Mock test tiếp theo.
5. Làm nhiều Mock test ở các thời điểm khác nhau để có dự đoán **Exam Prediction** ổn định và chính xác.
{% endhint %}

## V. Các Lỗi Thường Gặp & Cách Xử Lý

| Lỗi / Tình huống                                                  | Nguyên nhân                                                                        | Cách xử lý                                                                                                                                                |
| ----------------------------------------------------------------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Click vào Class nhưng không hiển thị Dashboard                    | Class đang có Status = **Ready to learn** hoặc ở **Type = Foundation**             | <p>Hoàn thành ít nhất một Activity để Class chuyển sang Status = Resume; Dashboard sẽ hiển thị.<br>Chỉ lớp dạng Revision hoặc Lesson mới có Dashboard</p> |
| **Topic Progress** một Section vẫn = 0% dù đã học                 | Activity hoàn thành nằm ngoài Section đó, hoặc Section có Activity chưa hoàn thành | Kiểm tra danh sách Activity của Section trong Course Content và hoàn thiện đầy đủ.                                                                        |
| **Learning Results** trong khóa ôn không thay đổi dù đã làm test  | Khóa ôn đang **có liên kết** với khóa chính → Learning Results copy từ khóa chính  | Vào Khóa chính (Normal Course) làm các bài test tương ứng; kết quả sẽ được phản ánh sang Dashboard khóa ôn.                                               |
| **Mock test results** không hiển thị cho một Section              | Không có câu hỏi nào trong Mock test có trường "Belong to section" = Section đó    | Kiểm tra với người tạo Mock test/Question Bank về việc cấu hình "Belong to section" của câu hỏi.                                                          |
| Các trục Section trong Mock test results không khớp với khóa ôn   | Khóa ôn **có liên kết** với khóa chính → các trục Section lấy theo khóa chính      | Đây là hành vi đúng theo thiết kế; xem các Section của khóa chính để hiểu mapping.                                                                        |
| **Your Exam Prediction** quá thấp dù đã hoàn thành nhiều Activity | Mock test result còn thấp (trọng số 70% trong công thức)                           | Tập trung làm thêm Mock test và cải thiện điểm Mock test để nâng Exam readiness.                                                                          |
| **Your Exam Prediction** không cập nhật sau khi làm Mock test     | Bài Mock test chưa được nộp hoặc chưa chấm xong                                    | Đảm bảo đã hoàn tất và nộp bài Mock test; kiểm tra trạng thái bài làm trong Course Content.                                                               |
| Điểm Learning Results khác với điểm khi làm bài (khóa ôn độc lập) | Công thức tính theo chương trình kết hợp nhiều loại test với trọng số khác nhau    | Click vào **Your Learning Results** để xem công thức chi tiết của chương trình.                                                                           |

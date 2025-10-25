# CHÍNH SÁCH QUYỀN RIÊNG TƯ

> Áp dụng cho ứng dụng: **Ứng dụng Quản Lý Hạn Sử Dụng (HSD) – Tam Hảo QA/QC**
> Phiên bản: 1.0
> Ngày hiệu lực: **25/10/2025**
> Chủ sở hữu/Đơn vị vận hành: **Trần Đình Thụ**
> Email liên hệ: **tranthu4588@gmail.com**

---

## 1. Giới thiệu

Chính sách này giải thích cách chúng tôi thu thập, sử dụng, lưu trữ, chia sẻ và bảo vệ dữ liệu cá nhân khi bạn sử dụng Ứng dụng Quản Lý Hạn Sử Dụng (gọi tắt là “Ứng dụng”). Bằng việc cài đặt hoặc sử dụng Ứng dụng, bạn đồng ý với các nội dung trong chính sách này.

Ứng dụng được thiết kế cho hoạt động nội bộ của quán/chuỗi cửa hàng để quản lý hạn sử dụng sản phẩm, theo dõi hàng sắp hết hạn, và hỗ trợ nghiệp vụ QA/QC.

---

## 2. Phạm vi áp dụng

Chính sách áp dụng cho tất cả người dùng Ứng dụng, bao gồm **Admin**, **Staff**, **Viewer** và các tài khoản đăng nhập qua Google (Google Sign‑In), nơi Ứng dụng được phân phối (Play Store/Test nội bộ).

---

## 3. Dữ liệu chúng tôi thu thập

Tuỳ theo cách bạn sử dụng Ứng dụng, chúng tôi có thể thu thập các loại dữ liệu sau:

### 3.1. Dữ liệu tài khoản và định danh

* **Thông tin tài khoản Google** (nếu đăng nhập bằng Google): mã người dùng (UID), email, tên hiển thị, ảnh đại diện (nếu có).
* **Vai trò (role)** trong hệ thống: Admin/Staff/Viewer.

### 3.2. Dữ liệu do bạn cung cấp

* **Dữ liệu sản phẩm và hạn sử dụng**: tên hàng, nhóm hàng, điều kiện bảo quản, hạn dùng, thời điểm mở nắp/nấu, ghi chú; bao gồm cả dữ liệu nhập qua file **Excel/CSV/PDF**.
* **Lịch nhắc & thông báo**: cấu hình thời điểm nhắc, trạng thái bật/tắt thông báo cục bộ.

### 3.3. Dữ liệu thiết bị & kỹ thuật (không định danh cá nhân)

* Thông tin thiết bị cơ bản: hệ điều hành, phiên bản ứng dụng, ngôn ngữ, múi giờ.
* **Nhật ký lỗi**/chẩn đoán (nếu bật): stack trace, sự kiện lỗi để cải thiện độ ổn định.

> **Lưu ý:** Ứng dụng **không** truy cập nội dung nhạy cảm như danh bạ, vị trí chính xác, ảnh riêng tư… trừ khi bạn chủ động cung cấp trong quá trình nhập dữ liệu nghiệp vụ.

---

## 4. Nguồn thu thập dữ liệu

* **Trực tiếp từ người dùng**: khi bạn đăng nhập, tạo/sửa dữ liệu, nhập file.
* **Từ nhà cung cấp dịch vụ**: Firebase Authentication/Firestore (Google) nhằm lưu trữ và đồng bộ dữ liệu.
* **Từ thiết bị**: thông tin kỹ thuật tối thiểu để chạy tính năng thông báo cục bộ, đếm giờ, và cải thiện ổn định.

---

## 5. Mục đích sử dụng dữ liệu

* Xác thực và quản lý phiên đăng nhập (Google Sign‑In/Firebase Auth).
* Lưu trữ và đồng bộ dữ liệu hạn sử dụng (Firebase Firestore).
* Gửi **thông báo cục bộ** nhắc việc (không gửi qua máy chủ).
* Phân quyền và kiểm soát truy cập (Admin/Staff/Viewer).
* Cải thiện hiệu năng, sửa lỗi và nâng cao trải nghiệm người dùng.
* Tuân thủ yêu cầu pháp luật khi có nghĩa vụ.

---

## 6. Cơ sở pháp lý (nếu áp dụng GDPR/CCPA)

* **Thực hiện hợp đồng/lợi ích chính đáng**: cung cấp tính năng cốt lõi của Ứng dụng.
* **Sự đồng ý**: khi bạn bật các cài đặt tuỳ chọn (vd. chia sẻ phản hồi, bật thu thập lỗi).
* **Tuân thủ pháp luật**: khi cần đáp ứng yêu cầu từ cơ quan có thẩm quyền.

---

## 7. Quyền của người dùng

Tuỳ theo pháp luật áp dụng, bạn có thể có các quyền sau:

* **Truy cập**: yêu cầu bản sao dữ liệu cá nhân.
* **Chỉnh sửa**: cập nhật dữ liệu chưa chính xác.
* **Xoá**: yêu cầu xoá tài khoản/dữ liệu theo quy định.
* **Giới hạn/Xử lý**: yêu cầu hạn chế một số loại xử lý.
* **Rút lại đồng ý**: đối với xử lý dựa trên đồng ý (nếu có).
* **Khiếu nại**: tới cơ quan bảo vệ dữ liệu có thẩm quyền.

Bạn có thể **tự xoá** dữ liệu nghiệp vụ trong ứng dụng (nếu được Admin cho phép) hoặc yêu cầu qua email **[email liên hệ]**. Với dữ liệu đăng nhập Google, bạn có thể ngắt liên kết qua trang quản lý tài khoản Google của mình.

---

## 8. Lưu trữ và thời hạn

* **Firestore**: lưu trữ dữ liệu hạn sử dụng và quyền truy cập theo tài khoản.
* **Thiết bị**: bộ nhớ đệm/offline để hoạt động khi mất kết nối; cấu hình thông báo cục bộ.
* **Thời hạn**: dữ liệu được giữ cho tới khi bạn hoặc Admin xoá, hoặc khi không còn cần cho mục đích nêu trên.
* Sao lưu (nếu có) sẽ có độ trễ trước khi dữ liệu được xóa hoàn toàn.

---

## 9. Chia sẻ dữ liệu với bên thứ ba

Chúng tôi **không bán** dữ liệu cá nhân. Dữ liệu chỉ được chia sẻ với:

* **Google Firebase** (Authentication, Firestore) để xác thực và lưu trữ.
* **Cơ quan nhà nước** khi pháp luật yêu cầu.

Các nhà cung cấp dịch vụ được ràng buộc về bảo mật và chỉ xử lý dữ liệu theo hướng dẫn từ chúng tôi.

---

## 10. Bảo mật

Chúng tôi áp dụng các biện pháp kỹ thuật và tổ chức hợp lý để bảo vệ dữ liệu (phân quyền, quy tắc bảo mật Firestore, mã hoá trong truyền tải HTTPS, kiểm soát truy cập Admin). Tuy nhiên, không có hệ thống nào an toàn tuyệt đối; bạn cũng cần bảo mật thiết bị và tài khoản của mình.

---

## 11. Trẻ em

Ứng dụng hướng tới người dùng nội bộ/doanh nghiệp. Nếu bạn dưới độ tuổi theo quy định pháp luật địa phương, vui lòng sử dụng Ứng dụng dưới sự cho phép/giám sát hợp pháp.

---

## 12. Quyền hệ thống & quyền ứng dụng

* **Internet**: đồng bộ dữ liệu với Firestore.
* **Thông báo**: gửi nhắc việc cục bộ.
* **Âm thanh**: phát âm báo khi hết giờ ở màn “Đếm ngược”.
* **Đọc file** (khi bạn chọn): nhập Excel/CSV/PDF.

Chúng tôi chỉ yêu cầu các quyền cần thiết để tính năng hoạt động.

---

## 13. Liên kết bên thứ ba

Ứng dụng có thể chứa liên kết đến trang web/dịch vụ bên thứ ba. Chúng tôi không chịu trách nhiệm về nội dung hay chính sách của các bên này. Vui lòng đọc chính sách riêng của họ.

---

## 14. Chuyển dữ liệu quốc tế

Hệ thống Firebase có thể đặt máy chủ tại nhiều quốc gia. Bằng cách sử dụng Ứng dụng, bạn đồng ý việc dữ liệu có thể được chuyển và lưu trữ ngoài quốc gia của bạn, với các biện pháp bảo vệ phù hợp từ nhà cung cấp dịch vụ.

---

## 15. Thay đổi chính sách

Chúng tôi có thể cập nhật chính sách này theo thời gian. Phiên bản mới sẽ được công bố tại đường dẫn trang Chính sách. Ngày hiệu lực sẽ được cập nhật ở đầu tài liệu.

---

## 16. Liên hệ

Nếu có câu hỏi, yêu cầu truy cập/xoá dữ liệu, hoặc khiếu nại, vui lòng liên hệ:
**Email:** [tranthu4588@gmail.com]

---


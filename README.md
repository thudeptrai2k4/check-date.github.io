# CHÍNH SÁCH QUYỀN RIÊNG TƯ

> Áp dụng cho ứng dụng: **Ứng dụng Quản Lý Hạn Sử Dụng (HSD) – Tam Hảo QA/QC**
> Phiên bản: 1.0
> Ngày hiệu lực: **[điền ngày]**
> Chủ sở hữu/Đơn vị vận hành: **[Tên cá nhân/doanh nghiệp]**
> Email liên hệ: **[email liên hệ]**
> Địa chỉ liên hệ (tuỳ chọn): **[địa chỉ]**

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
* **Dịch vụ phân tích/lỗi** (tuỳ chọn, nếu bật): ví dụ Firebase Crashlytics/Analytics.
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
**Email:** [email liên hệ]
**Điện thoại (tuỳ chọn):** [số điện thoại]
**Địa chỉ (tuỳ chọn):** [địa chỉ]

---

# HƯỚNG DẪN TRIỂN KHAI TRÊN GITHUB PAGES

Bạn có 2 cách phổ biến để public trang chính sách:

## Cách A — Dùng repo chuyên cho chính sách (đường dẫn đẹp)

1. Tạo repo mới, ví dụ: `hsd-privacy-policy`.
2. Thêm file **`index.html`** (mẫu ở dưới) vào thư mục gốc.
3. Vào **Settings → Pages**:

   * **Source**: chọn **Deploy from a branch**.
   * **Branch**: chọn **`main`** và **`/ (root)`**.
   * Lưu. GitHub sẽ cấp URL dạng: `https://<username>.github.io/hsd-privacy-policy/`.

## Cách B — Dùng repo user/site (đường dẫn ngắn nhất)

1. Nếu bạn đã có repo `username.github.io`, chỉ cần đặt file trong đó.
2. Dùng thư mục con, ví dụ: `/hsd/privacy/` với `index.html`.
3. URL sẽ là: `https://<username>.github.io/hsd/privacy/`.

> **Tuỳ chọn domain riêng:** Trỏ CNAME của domain riêng về `username.github.io`, thêm file `CNAME` vào repo chứa domain.

---

## MẪU `index.html` (dán vào repo GitHub Pages)

> Bạn có thể chỉnh sửa các placeholder trong phần **Thông tin ở đầu** của chính sách.

```html
<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Chính sách quyền riêng tư – Ứng dụng Quản Lý HSD</title>
  <meta name="description" content="Chính sách quyền riêng tư cho Ứng dụng Quản Lý Hạn Sử Dụng (HSD)">
  <style>
    :root{--bg:#0b0f14;--fg:#e8eef5;--muted:#9db0c0;--card:#121922;--accent:#4cc9f0;}
    @media (prefers-color-scheme: light){:root{--bg:#ffffff;--fg:#0b0f14;--muted:#4b5563;--card:#f5f7fb;--accent:#0ea5e9;}}
    *{box-sizing:border-box} body{margin:0;background:var(--bg);color:var(--fg);font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,sans-serif}
    .wrap{max-width:860px;margin:0 auto;padding:32px 20px}
    .card{background:var(--card);border-radius:16px;padding:28px;box-shadow:0 2px 24px rgba(0,0,0,.18)}
    h1,h2,h3{line-height:1.2} h1{font-size:28px;margin:0 0 12px} h2{margin:28px 0 8px;font-size:20px}
    .meta{color:var(--muted);font-size:14px;margin-bottom:18px}
    a{color:var(--accent);text-decoration:none} a:hover{text-decoration:underline}
    ul{padding-left:20px}
    .footer{margin-top:24px;color:var(--muted);font-size:14px}
  </style>
</head>
<body>
  <main class="wrap">
    <article class="card">
      <h1>CHÍNH SÁCH QUYỀN RIÊNG TƯ</h1>
      <div class="meta">
        Áp dụng cho ứng dụng: <strong>Ứng dụng Quản Lý Hạn Sử Dụng (HSD) – Tam Hảo QA/QC</strong><br>
        Phiên bản: 1.0 · Ngày hiệu lực: <strong>[điền ngày]</strong><br>
        Chủ sở hữu: <strong>[Tên cá nhân/doanh nghiệp]</strong> · Email: <strong>[email liên hệ]</strong>
      </div>

      <!-- Bạn có thể thay thế phần nội dung dưới bằng Markdown đã duyệt -->
      <h2>1. Giới thiệu</h2>
      <p>Chính sách này giải thích cách chúng tôi thu thập, sử dụng, lưu trữ, chia sẻ và bảo vệ dữ liệu cá nhân khi bạn sử dụng Ứng dụng Quản Lý Hạn Sử Dụng ("Ứng dụng"). Bằng việc cài đặt hoặc sử dụng Ứng dụng, bạn đồng ý với các nội dung trong chính sách này.</p>

      <h2>2. Phạm vi áp dụng</h2>
      <p>Áp dụng cho tất cả người dùng: Admin, Staff, Viewer và tài khoản đăng nhập Google.</p>

      <h2>3. Dữ liệu chúng tôi thu thập</h2>
      <ul>
        <li><strong>Tài khoản Google</strong>: UID, email, tên hiển thị, ảnh (nếu có); vai trò (Admin/Staff/Viewer).</li>
        <li><strong>Dữ liệu do bạn cung cấp</strong>: sản phẩm, hạn sử dụng, điều kiện bảo quản, dữ liệu nhập từ Excel/CSV/PDF.</li>
        <li><strong>Thiết bị & kỹ thuật</strong> (không định danh): hệ điều hành, phiên bản app, ngôn ngữ, múi giờ, nhật ký lỗi (nếu bật).</li>
      </ul>

      <h2>4. Mục đích sử dụng</h2>
      <ul>
        <li>Xác thực và quản lý phiên đăng nhập (Google/Firebase Auth).</li>
        <li>Lưu trữ & đồng bộ dữ liệu hạn dùng (Firebase Firestore).</li>
        <li>Gửi thông báo cục bộ nhắc việc; phân quyền truy cập.</li>
        <li>Cải thiện hiệu năng, sửa lỗi; tuân thủ pháp luật.</li>
      </ul>

      <h2>5. Chia sẻ & bảo mật</h2>
      <p>Không bán dữ liệu. Chia sẻ với nhà cung cấp dịch vụ như Google Firebase theo hợp đồng xử lý dữ liệu; áp dụng các biện pháp bảo mật hợp lý (quy tắc Firestore, HTTPS…).</p>

      <h2>6. Quyền của bạn</h2>
      <p>Bạn có thể yêu cầu truy cập/chỉnh sửa/xoá dữ liệu, rút đồng ý (nếu áp dụng) qua <strong>[email liên hệ]</strong>. Dữ liệu đăng nhập Google có thể ngắt liên kết trong trang tài khoản Google của bạn.</p>

      <h2>7. Liên hệ</h2>
      <p>Email: <strong>[email liên hệ]</strong>. Địa chỉ/điện thoại (tuỳ chọn): <strong>[điền]</strong>.</p>

      <p class="footer">© <span id="y"></span> [Tên cá nhân/doanh nghiệp]. Chính sách có thể được cập nhật định kỳ.</p>
    </article>
  </main>
  <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
</body>
</html>
```

---

## Gợi ý tuỳ chỉnh nhanh

* Thay **[email liên hệ]**, **[Tên cá nhân/doanh nghiệp]**, **[điền ngày]** theo thực tế.
* Nếu bạn không dùng Analytics/Crashlytics, hãy xoá các dòng liên quan trong chính sách.
* Nếu bạn dùng thêm dịch vụ (vd. lưu trữ ảnh, gửi email…), thêm tên dịch vụ và mục đích sử dụng vào mục 9.

## Kiểm tra sau khi xuất bản

* Mở URL GitHub Pages trên trình duyệt ẩn danh để kiểm tra hiển thị.
* Chia sẻ URL đó trên Play Store (trường Privacy Policy) hoặc trong phần “Giới thiệu” của ứng dụng.

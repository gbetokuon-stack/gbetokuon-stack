# 🚀 Hướng Dẫn Kích Hoạt GitHub Profile Siêu Đẹp

GitHub Profile có thể tùy biến và code được 100%! Cơ chế hoạt động của GitHub như sau:
> Khi bạn tạo một repository **cùng tên với Username GitHub** của bạn và để ở chế độ **Public**, nội dung của file `README.md` trong repo đó sẽ tự động biến thành trang hồ sơ cá nhân của bạn.

---

## 🛠️ Các Bước Cài Đặt (Chỉ Mất 3 Phút)

### Bước 1: Tạo Repository Đặc Biệt trên GitHub
1. Vào GitHub, chọn **New repository** (hoặc truy cập [github.com/new](https://github.com/new)).
2. Tại ô **Repository name**: Nhập chính xác **Username GitHub** của bạn (ví dụ nếu username bạn là `nguyenvana` thì đặt tên repo là `nguyenvana`).
   - GitHub sẽ hiện thông báo bí mật: *"✨ You found a secret! `<username>/<username>` is a special repository..."*.
3. Chọn chế độ **Public**.
4. Tích chọn **Add a README file**.
5. Nhấn **Create repository**.

---

### Bước 2: Thêm Nội Dung Hồ Sơ
1. Mở file [README.md](file:///e:/ide/New%20folder/README.md) trong thư mục này.
2. Kiểm tra thông tin cá nhân:
   - Tên username `cuongacoustic`, link Facebook và Discord đã được điền sẵn.
   - Bạn chỉ cần cập nhật thêm link LinkedIn hoặc Email cá nhân nếu muốn.
   - Bổ sung hoặc thay đổi danh sách công nghệ nếu cần.
3. Dán toàn bộ nội dung file `README.md` vào repository trên GitHub của bạn và nhấn **Commit changes**.

---

### Bước 3: Kích Hoạt Đồ Họa Đóng Góp 3D Động (3D Animated Contribution Graph)
File workflow tự động đã được chuẩn bị sẵn tại: [.github/workflows/profile-3d.yml](file:///e:/ide/New%20folder/.github/workflows/profile-3d.yml).

1. Đưa thư mục `.github/workflows/` (chứa `profile-3d.yml`) và thư mục `profile-3d-contrib/` lên repository GitHub của bạn.
2. Cấp quyền ghi cho GitHub Actions:
   - Vào tab **Settings** của repository -> Chọn **Actions** -> Chọn **General**.
   - Kéo xuống mục **Workflow permissions** -> Tích chọn **Read and write permissions** -> Nhấn **Save**.
3. Kích hoạt lần đầu:
   - Vào tab **Actions** trên GitHub -> Chọn workflow **GitHub-Profile-3D-Contrib** ở menu bên trái -> Bấm **Run workflow**.
   - Sau 1 - 2 phút, Action sẽ tự động quét toàn bộ lịch sử commit và sinh ra các file đồ họa 3D Isometric đa góc nhìn (đêm, màu, v.v.) rồi tự động cập nhật mỗi ngày!

---

### 🖥️ Xem Trước Nhanh (Live Preview)
Bạn có thể mở trực tiếp file [PREVIEW.html](file:///e:/ide/New%20folder/PREVIEW.html) bằng bất kỳ trình duyệt nào (Chrome, Edge, Firefox) để:
- Nhập username GitHub của bạn và xem giao diện cập nhật ngay lập tức.
- Bấm **Sao chép README.md** để copy mã chuẩn chỉnh.

# Nhật Ký Prompt Engineering (PROMPT_LOG.md)

- **Sinh viên thực hiện:** Đặng Khánh Linh
- **Mã số sinh viên:** 125000411
- **Email học tập:** 125000411@lachong.edu.vn
- **Trường:** Đại học Lạc Hồng (LHU)
- **Đề tài:** Ứng dụng NutriPlan - Nền tảng Quản trị & Cân bằng Dinh dưỡng Sinh viên
- **Đặc tả kỹ thuật:** Semantic HTML5, CSS Variables, Theme Switcher với hiệu ứng Transition, Thanh điều hướng giao diện chuyên biệt (Sub-Navbar Tabs), Bố cục Responsive Flexbox & CSS Grid.

---

## 1. Prompt 1: Nâng cấp thanh điều hướng giao diện & mở rộng Trang chủ
- **Mục tiêu:** Tách riêng thanh điều hướng giao diện trực quan và bổ sung nội dung đa dạng cho trang chủ (lộ trình 4 bước, bảng so sánh calo thực phẩm, bộ sưu tập món ăn và form liên hệ sinh viên).
- **Prompt:**
  > "Đóng vai trò là Frontend Engineer. Hãy tái cấu trúc website NutriPlan:
  > 1. Bổ sung thanh điều hướng giao diện (Interface Navbar) cố định với các tab icon: Trang Chủ, Thực Đơn, Quét Calo AI, Trợ Lý AI, Hồ Sơ & Thống Kê.
  > 2. Mở rộng trang chủ dài hơn với các phần: Banner giới thiệu, Lộ trình 4 bước cân bằng dinh dưỡng, Bảng dữ liệu so sánh calo nhóm Thịt/Cá vs Rau/Củ, Showcase đĩa ăn và Form liên hệ.
  > 3. Cập nhật toàn bộ thông tin liên hệ thành email học tập: `125000411@lachong.edu.vn` (Đặng Khánh Linh - MSSV: 125000411)."
- **Kết quả:** Code sinh ra trang chủ hoàn chỉnh, nhiều tầng nội dung chuyên sâu và cơ chế chuyển đổi màn hình mượt mà bằng JavaScript DOM.

---

## 2. Prompt 2: Tối ưu hiệu ứng đổi màu theme và tính tương thích CSS
- **Mục tiêu:** Đồng bộ màu sắc CSS Variables (`--primary-color`, `--bg-page`, v.v.) giữa 3 chế độ (Emerald, Dark, Sunset) kèm hiệu ứng chuyển tiếp mềm mại (`transition`).
- **Prompt:**
  > "Viết CSS tối ưu cho thanh điều hướng tab mới và bảng dữ liệu dinh dưỡng. Đảm bảo khi người dùng bấm đổi màu theme, toàn bộ bảng, thẻ card, viền và thanh tab đổi màu đồng bộ với `transition: 0.4s ease`. Đảm bảo responsive hiển thị tốt trên thiết bị di động dưới 860px."
- **Kết quả:** Giao diện có độ hoàn thiện thị giác cao, chuyển màu êm ái và không vỡ layout trên màn hình nhỏ.

---

## 3. Prompt 3: Đóng gói kiểm tra nộp bài GitHub Pages
- **Mục tiêu:** Rà soát đường dẫn hình ảnh CDN, thẻ meta viewport và kiểm tra tính năng preview live trên GitHub Pages.
- **Prompt:**
  > "Kiểm tra tính độc lập của file index.html và style.css để deploy lên repository `Linh_DangKhanh_125000411` không phát sinh lỗi 404."
- **Kết quả:** Kiểm tra hoàn tất, cả 3 file sẵn sàng commit và push lên branch main của GitHub.


# Krita-VAS

Phần mềm nguồn mở tích hợp trong **Vietnews AI Studio (VAS)** — Vietnews phân phối lại đúng bản VAS dùng (mã băm SHA-256 khớp bản phát hành VAS đã ký),
kèm mã nguồn tương ứng và giấy phép. Bộ cài VAS tải từ đây trước, lỗi thì tải từ nhà phát triển gốc.

| Phần mềm | Phiên bản | Giấy phép | Bản phát hành |
|---|---|---|---|
| Krita (người dùng sửa ảnh, vẽ, tô màu ngay trên Desk) | 6.0.4.1 | GPL-3.0-or-later | [krita-6.0.4.1](../../releases/tag/krita-6.0.4.1) |

Mỗi bản phát hành: tệp chạy gốc (không sửa), `nguon--…` mã nguồn tương ứng (theo danh mục `nguon/<id>.json`), `giay-phep--…`, `SHA256SUMS.txt`.
Bản phát hành do GitHub Actions tạo (`.github/workflows/publish.yml`): tải từ nguồn gốc, kiểm mã băm ghim, sai là không phát hành.

Bản quyền phần mềm thuộc các tác giả / cộng đồng của từng dự án. Yêu cầu mã nguồn: support@vietnews.com.vn

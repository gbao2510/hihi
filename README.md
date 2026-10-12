# UDM08 - Ứng Dụng Chat TCP Đa Luồng
**Mã đề tài:** UDM08  
**Môn học:** Lập trình mạng  

## 1. Danh sách thành viên
| STT | Họ và Tên | Vai trò | Module đảm nhiệm |
|---|---|---|---|
| 1 | Ngô Gia Bảo | Nhóm trưởng | `gui_actions.py` (Tích hợp, UI, Demo) |
| 2 | [Tên TV1] | Thành viên | `server_core.py` (Lõi Server TCP) |
| 3 | [Tên TV2] | Thành viên | `server_router.py` (Bộ định tuyến JSON) |
| 4 | [Tên TV3] | Thành viên | `network_worker.py` (Luồng mạng Client) |
| 5 | [Tên TV4] | Thành viên | `gui_main.py` (Giao diện chính) |
| 6 | [Tên TV5] | Thành viên | `gui_widgets.py` (Component Đồ họa) |

## 2. Kiến trúc & Công nghệ
*   **Mô hình:** Client - Server phân tán.
*   **Giao thức lõi:** TCP (Transmission Control Protocol).
*   **Định dạng truyền tải:** JSON (có ký tự `\n` phân định gói tin).
*   **Ngôn ngữ:** Python 3.14
*   **Giao diện (GUI):** PyQt6

## 3. Cấu trúc thư mục repository
```text
UDM08_ChatApp/
├── Code/                   # Chứa toàn bộ mã nguồn Python
│   ├── Server/
│   ├── Client/
│   └── requirements.txt    # Danh sách thư viện bắt buộc
├── DOCX/                   # Báo cáo Word chi tiết
├── Extra/                  # Hình ảnh, tài nguyên, file cấu hình
├── PPTX/                   # Slide thuyết trình
└── README.md               # Tài liệu hướng dẫn này

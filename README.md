# ⚡ Thực hành Thiết kế Mạch HDL – IUH

Kho học tập và thực hành môn **Thiết kế Vi mạch số với HDL**, tập trung vào **Verilog HDL, thiết kế mạch số và FPGA DE2-115**.

Repository được tổ chức theo từng nhóm nội dung, giúp dễ tìm tài liệu, làm bài thực hành và tra cứu trong quá trình học.

## 🧭 Nội dung

| Thư mục                 | Nội dung                                               |
| ----------------------- | ------------------------------------------------------ |
| `00_Thong_tin_mon_hoc`  | Thông tin và tài liệu liên quan đến môn học            |
| `01_Bai_giang`          | Bài giảng theo chương                                  |
| `02_Ly_thuyet`          | Tài liệu lý thuyết về thiết kế mạch số và HDL          |
| `03_Thuc_hanh`          | LAB, bài tập, DE2-115, phần cứng và tài liệu thực hành |
| `04_Tai_lieu_tham_khao` | Sách và tài liệu tham khảo                             |
| `05_Huong_dan`          | Quartus II, USB Blaster và hướng dẫn nạp code          |
| `06_File_goc`           | Các file nguồn và tài liệu gốc                         |

## 📂 Cấu trúc

```text
thuc-hanh-thiet-ke-mach-hdl-iuh/
│
├── 00_Thong_tin_mon_hoc/
│
├── 01_Bai_giang/
│
├── 02_Ly_thuyet/
│
├── 03_Thuc_hanh/
│   ├── 01_DE2-115/
│   ├── 02_LAB/
│   ├── 03_TaiLieu/
│   ├── 04_Bai_tap/
│   ├── 05_Phan_cung/
│   ├── 06_Tai_lieu_bai_tap/
│   └── 07_Driver_USB_COM/
│
├── 04_Tai_lieu_tham_khao/
│
├── 05_Huong_dan/
│   ├── 01_Quartus/
│   ├── 02_USB_Blaster/
│   └── 03_Nap_code/
│
├── 06_File_goc/
│
└── README.md
```

## 🧩 Nội dung thực hành

Repository bao gồm các nội dung:

* Logic tổ hợp và mạch số cơ bản.
* Công tắc, nút nhấn và LED.
* LED 7 đoạn.
* Mạch đếm và bộ định thời.
* Bộ cộng, mạch nhân và mạch so sánh.
* Máy trạng thái hữu hạn (FSM).
* GPIO và LCD.
* UART / RS232.
* SRAM / SDRAM.
* SignalTap.
* DMA.
* Nios II và Avalon/Qsys.
* Pin assignment và kiểm thử trên kit DE2-115.

## 🛠️ Công cụ & phần cứng

```text
HDL             : Verilog HDL
FPGA Board      : DE2-115
Development     : Intel Quartus II
Programming     : USB Blaster
Signal Analysis : SignalTap
```

## 🔄 Quy trình học tập

```text
Bài giảng / Lý thuyết
          ↓
Phân tích yêu cầu
          ↓
Thiết kế mạch
          ↓
Viết Verilog HDL
          ↓
Mô phỏng / kiểm tra
          ↓
Quartus II
          ↓
Pin Assignment
          ↓
Nạp FPGA DE2-115
          ↓
Kiểm thử phần cứng
```

## 🚀 Bắt đầu

### Học lý thuyết

```text
01_Bai_giang/
02_Ly_thuyet/
```

### Làm bài thực hành

```text
03_Thuc_hanh/02_LAB/
03_Thuc_hanh/04_Bai_tap/
03_Thuc_hanh/06_Tai_lieu_bai_tap/
```

### Chuẩn bị phần cứng

```text
03_Thuc_hanh/01_DE2-115/
03_Thuc_hanh/05_Phan_cung/
03_Thuc_hanh/07_Driver_USB_COM/
```

### Cài đặt và nạp chương trình

```text
05_Huong_dan/
```

## 📌 Lưu ý

Repository giữ lại các tài liệu phục vụ học tập và thực hành, bao gồm PDF, ZIP, RAR, WMV, DOCX và các file cấu hình phần cứng.

Một số file có kích thước lớn. Có thể tải riêng từng file hoặc thư mục cần thiết thay vì clone toàn bộ repository.

Tên file và nội dung tài liệu được giữ gần với nguồn ban đầu để thuận tiện đối chiếu.

## 🎓 Mục tiêu

```text
Học lý thuyết
     ↓
Làm bài tập
     ↓
Thiết kế Verilog
     ↓
Mô phỏng
     ↓
Thực hành FPGA
     ↓
Kiểm thử phần cứng
```

## 👤 Tác giả

**Nguyễn Ngọc Hùng · IUH**

---

> Digital Design · HDL · Verilog · FPGA · DE2-115

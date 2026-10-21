# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:**Le Hong Quan
- **Lớp:**CNTT2
- **Link repository:**https://github.com/LeHogQuan/CNTT2_Nhap-mon-CNTT_OnTap-Ngay1/tree/main/trung-tam-tieng-anh
- **Hệ điều hành (Windows/macOS):**WINDOWS

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
get-childitem -force
mv .\lich_hoc.txt .\docs\
mv .\logo_trung_tam.png .\media\
mv .\anh_lop_hoc.jpg .\media\
copy-item .\media\logo_trung_tam.png .\archive\
rm .\temp_201.tmp -recurse
rm .\temp_202.tmp -recurse
cd .\logs\
dir
cd ..
cd docs
copy-item ..\media\anh_lop_hoc.jpg ..\archive\
cd ..
```

### Kết quả B1 (pwd)

```text
Path
----
C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh


PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh>

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/22/2026   3:32 AM                archive
d-----        10/22/2026   2:59 AM                data
d-----        10/22/2026   3:32 AM                docs
d-----        10/22/2026   3:00 AM                logs
d-----        10/22/2026   3:27 AM                media
------        10/19/2026  10:04 AM             83 .env
-a----        10/22/2026   2:45 AM            926 bai_lam_ngay1.md


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM             67 lich_hoc.txt


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 access.log


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png


```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**


# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:**Lê Hồng Quân
- **Lớp:**CNTT2
- **Link repository:**[https://github.com/LeHogQuan/CNTT2_Nhap-mon-CNTT_OnTap-Ngay1/new/main](https://github.com/LeHogQuan/CNTT2_Nhap-mon-CNTT_OnTap-Ngay1/blob/main/bai_lam_ngay1.md)
- **Hệ điều hành (Windows/macOS):**Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```powershell
pwd
Get-ChildItem -Force
Move-Item .\lich_hoc.txt .\docs\
Move-Item .\logo_trung_tam.png .\media\
Move-Item .\anh_lop_hoc.jpg .\media\
Copy-Item .\media\logo_trung_tam.png .\archive\
Remove-Item .\temp_201.tmp
Remove-Item .\temp_202.tmp
Set-Location .\logs
Get-ChildItem
Set-Location ..
Set-Location .\docs
Copy-Item ..\media\anh_lop_hoc.jpg ..\archive\
Set-Location ..
```

### Kết quả B1 (pwd)

```text
Path
----
D:\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: D:\trung-tam-tieng-anh

    Directory: D:\trung-tam-tieng-anh\archive
    anh_lop_hoc.jpg
    logo_trung_tam.png

    Directory: D:\trung-tam-tieng-anh\data
    hoc_vien_khoa_3.xlsx

    Directory: D:\trung-tam-tieng-anh\docs
    lich_hoc.txt

    Directory: D:\trung-tam-tieng-anh\logs
    access.log

    Directory: D:\trung-tam-tieng-anh\media
    anh_lop_hoc.jpg
    logo_trung_tam.png

.env
bai_lam_ngay1.md
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**

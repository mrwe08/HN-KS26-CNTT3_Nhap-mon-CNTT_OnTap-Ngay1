# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:Nguyễn Thế Huy**
- **Lớp:CNTT3**
- **Link repository:https://github.com/mrwe08/HN-KS26-CNTT3_Nhap-mon-CNTT_OnTap-Ngay1**
- **Hệ điều hành (Windows/macOS):macOS**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# B1
 /Users/admin/Downloads/trung-tam-tieng-anh
# B2
ls -a
# B3
mv Trung\ Tam\ Tieng\ Anh\ FINAL/lich_hoc.txt docs
mv Trung\ Tam\ Tieng\ Anh\ FINAL/logo_trung_tam.JPG media                         
mv Trung\ Tam\ Tieng\ Anh\ FINAL/anh_lop_hoc.JPG media                      
# B4
cp media/logo_trung_tam.JPG archive 
# B5 
rm Trung\ Tam\ Tieng\ Anh\ FINAL/temp_201.tmp
rm Trung\ Tam\ Tieng\ Anh\ FINAL/temp_202.tmp
# B6
cd logs
ls logs
cd ..
# B7
cd docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..

```

### Kết quả B1 (pwd)

```text
/Users/admin/Downloads/trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
.				bai_lam_ngay1.md
..				data
.DS_Store			docs
Trung Tam Tieng Anh FINAL	logs
archive				media
bai_lam_ngay1.env

./Trung Tam Tieng Anh FINAL:
.		..		.DS_Store	.env

./archive:
.			.DS_Store		logo_trung_tam.JPG
..			anh_lop_hoc.JPG

./data:
.			..			hoc_vien_khoa_3.xlsx

./docs:
.		..		archive		lich_hoc.txt

./logs:
.		..		.DS_Store	access.log

./media:
.			anh_lop_hoc.JPG
..			logo_trung_tam.JPG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**

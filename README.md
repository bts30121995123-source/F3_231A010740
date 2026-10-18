# LAB F3 – NHẬP LIỆU & FORM TRONG FLUTTER

## 1. Thông tin sinh viên
- Họ và tên: Trịnh Phạm Xuân Nghi
- MSSV: 231A010740
- Môn học: Lập trình trên các thiết bị di động (INT4211)
- Bài thực hành: Lab F3
- Công nghệ: Flutter – Dart

## 2. Nội dung bài thực hành
Xây dựng ứng dụng đăng ký học phần bằng Flutter, sử dụng Form và các control nhập liệu để thu thập và kiểm tra thông tin sinh viên.

Các chức năng chính:
- Nhập họ tên, mã số sinh viên và email
- Chọn học phần đăng ký bằng DropdownButtonFormField
- Chọn hệ đào tạo bằng RadioGroup và RadioListTile
- Chọn buổi học bằng CheckboxListTile
- Chọn số tín chỉ bằng Slider
- Bật hoặc tắt nhận thông báo bằng SwitchListTile
- Kiểm tra dữ liệu bằng validator
- Hiển thị thông tin đăng ký bằng AlertDialog
- Xóa dữ liệu và đưa biểu mẫu về trạng thái ban đầu bằng nút Làm lại

## 3. Bài nâng cao

### NC2 – Kiểm tra điều kiện đăng ký buổi học
- Nếu chọn hệ Vừa làm vừa học thì bắt buộc phải chọn buổi Tối
- Nếu không chọn buổi Tối, ứng dụng hiển thị thông báo lỗi bằng SnackBar và không cho đăng ký
- Nếu chọn đúng buổi Tối và thông tin hợp lệ, ứng dụng hiển thị hộp thoại xác nhận đăng ký

### NC3 – Giới hạn ký tự ô Họ tên
- Sử dụng thuộc tính `maxLength: 50` trong TextFormField
- Giới hạn ô Họ tên tối đa 50 ký tự
- Hiển thị bộ đếm ký tự khi người dùng nhập dữ liệu, ví dụ 20/50

## 4. Công nghệ sử dụng
- Flutter SDK
- Ngôn ngữ Dart
- Android Studio
- Android Emulator
- Git và GitHub

## 5. Cách chạy ứng dụng
Mở Terminal tại thư mục project và nhập:

```bash
flutter pub get
flutter run
```

## 6. Kết quả thực hiện
- Hoàn thành giao diện đăng ký học phần
- Kiểm tra dữ liệu nhập và hiển thị thông báo lỗi
- Hiển thị hộp thoại xác nhận khi đăng ký hợp lệ
- Chức năng Làm lại đưa biểu mẫu về trạng thái ban đầu
- Hoàn thành bài nâng cao NC2 và NC3

## 7. Cấu trúc project
```text
f3_form/
├── lib/
│   └── main.dart
├── pubspec.yaml
└── README.md
```

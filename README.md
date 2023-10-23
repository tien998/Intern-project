Dự án chứa 2 dự án con (Submodule)
Để lấy dự án về có chứa 2 dự án con, chạy lệnh:
    `git clone --recursive https://github.com/tien998/Intern-project`

2 dự án khi lấy về chưa có Migrations, vào mỗi dự án chạy 2 lệnh:
    `dotnet ef migrations add Init` tạo Migration
    `dotnet ef database update` tạo Database

Câc dịch vụ của TrainingCourse sẽ gọi API từ Identity để xác thực hoặc lấy thông tin người dùng (học sinh, giáo viên)
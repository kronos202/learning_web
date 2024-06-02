# Dự Án Công Nghệ XYZ

## Giới Thiệu

Dự án learning là một ứng dụng web được phát triển nhằm mục đích tạo ra cách học ngôn ngữ dễ dàng. Ban đầu sẽ tập trung vào 2 ngôn ngữ chính

## Mục Tiêu

- **Tăng hiệu quả khi học ngôn ngữ:** Giúp người dùng dễ dàng theo dõi tiến độ học tập.
- **Tối ưu hóa thời gian học:** Hỗ trợ học tập hiệu quả đối với người bận rộn.
- **Cung cấp báo cáo chi tiết:** Tạo báo cáo về tiến độ và hiệu quả học tập.
- **Ít tập trung vào ngữ ngáp:** Giúp người học không tập trung quá nhiều vào ngữ pháp

## Kiến Trúc

![Architecture Diagram](./images/architecture-diagram.png)

### Thành Phần Chính

- **Frontend:** React.js
- **Backend:** Node.js với Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Cài Đặt

### Yêu Cầu Hệ Thống

- **Node.js:** >= 14.x
- **MongoDB:** >= 4.x
- **NPM hoặc Yarn**

### Hướng Dẫn Cài Đặt

1. **Clone repository:**
   ```sh
   git clone https://github.com/username/xyz-project.git
   ```
2. **Cài đặt phụ thuộc:**
   ```sh
   cd xyz-project
   npm install
   # hoặc nếu dùng Yarn
   yarn install
   ```
3. **Cấu hình môi trường:**
   Tạo file `.env` trong thư mục gốc và cấu hình các biến môi trường:

   ```env
   PORT=3000
   MONGO_URI=mongodb://localhost:27017/xyz_db
   JWT_SECRET=your_jwt_secret
   ```

4. **Chạy ứng dụng:**
   ```sh
   npm start
   # hoặc nếu dùng Yarn
   yarn start
   ```

## Sử Dụng

### Tạo Người Dùng Mới

Để tạo người dùng mới, gửi yêu cầu POST tới `/api/register` với dữ liệu sau:

```json
{
  "name": "Tên Người Dùng",
  "email": "email@example.com",
  "password": "mật khẩu"
}
```

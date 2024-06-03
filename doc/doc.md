# Dự Án Công Nghệ XYZ

## Giới Thiệu

Dự án learning là một ứng dụng web được phát triển nhằm mục đích tạo ra cách học ngôn ngữ dễ dàng. Ban đầu sẽ tập trung vào 2 ngôn ngữ chính

## Mục Tiêu

- **Tập trung vào từ vựng và đọc:** Tập trung vào khả năng tăng vốn từ vựng và đọc thành thạo không bị khựng hay khó chịu với từ mới.
- **Tăng hiệu quả khi học ngôn ngữ:** Giúp người dùng dễ dàng theo dõi tiến độ học tập.
- **Tối ưu hóa thời gian học:** Hỗ trợ học tập hiệu quả đối với người bận rộn.
- **Cung cấp báo cáo chi tiết:** Tạo báo cáo về tiến độ và hiệu quả học tập.
- **Ít tập trung vào ngữ ngáp:** Giúp người học không tập trung quá nhiều vào ngữ pháp mà vẫn hiểu 1 cách dễ dàng

## Đối tượng tập trung

- **Beginer:** Giúp người học không tập
- **Medium:** Giúp người học không tập
- **Expert:** Giúp người học không tập

## Kiến Trúc

![Architecture Diagram](./images/architecture-diagram.png)

### Thành Phần Chính

- **Frontend:** React.js
- **Backend:** Node.js với Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Tính năng

### Tính năng cơ bản

#### Auth

- **Đăng ký/Đăng nhập**: email hay google/facebook

#### Dashboard User

- **Profile:** Người dùng có thể cập nhật thông tin cá nhân, hình đại diện, và cài đặt bảo mật
- **Tiến trình học tập:** Hiển thị tiến độ học tập của người dùng, bài học đã hoàn thành, điểm số, và các thành tích đạt được
- **Quản lý từ vựng:** Node.js với Express

#### Khóa học và bài học

- **Bài học:** MongoDB
- **Danh mục khóa học:** Các bài học có thể bao gồm video, audio, văn bản, hình ảnh, và bài tập.
- **Bài tập và kiểm tra:** Các bài tập tương tác, câu đố, bài kiểm tra để người dùng kiểm tra kiến thức của mình.

#### Tính năng học từ vựng

- **Luyện tập từ vựng:** JWT (JSON Web Tokens)
- **Flashcards:** JWT (JSON Web Tokens)

#### Tính năng theo dõi và đánh giá

- **Báo cáo tiến độ:** Báo cáo chi tiết về tiến độ học tập, thời gian học, và kết quả kiểm tra.
- **Đánh giá khóa học:** Người dùng có thể đánh giá và để lại nhận xét về các khóa học.

#### Tùy chỉnh giao diện người dùng

- **Dark/Light Mode:** Người dùng có thể đánh giá và để lại nhận xét về các khóa học.

#### Tùy chỉnh giao diện người dùng

- **Dark/Light Mode:** Người dùng có thể đánh giá và để lại nhận xét về các khóa học.

### Tính năng nâng cao

- **Giao diện đa ngôn ngữ** JWT (JSON Web Tokens)
- **Phân tích ngữ pháp trong bài học đó** JWT (JSON Web Tokens)
- **Âm thanh và hình ảnh** JWT (JSON Web Tokens)

## TechStack

- **Backend** Nestjs or Express
- **Frontend** Nextjs or Reactjs
- **Database** MongoDB or Postgresql
- **Deployment:** ?

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

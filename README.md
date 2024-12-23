# 🌟 **Nhóm 12 - Dự án Quản lý Sản phẩm** 🌟

## 🧑‍🤝‍🧑 **Thành viên nhóm**

| **Họ và Tên**        | **Vai trò** | **Mô tả công việc**                                                          |
| -------------------- | ----------- | ---------------------------------------------------------------------------- |
| **Võ Hữu Toàn**      | Trưởng nhóm | Quản lý dự án, phân công nhiệm vụ, giám sát tiến độ và chất lượng công việc. |
| **Nguyễn Hoàng Nam** | Developer   | Phát triển backend, xây dựng API RESTful và xử lý logic nghiệp vụ.           |
| **Huỳnh Trọng Đạt**  | Developer   | Hỗ trợ backend, tích hợp Cloudinary và xử lý lưu trữ hình ảnh.               |

---

## 🛠️ **Công nghệ sử dụng**

-   **[Cloudinary](https://cloudinary.com/):**
    -   Cung cấp giải pháp lưu trữ và quản lý hình ảnh trên nền tảng đám mây.
    -   Tích hợp các tính năng xử lý hình ảnh như nén, tối ưu hóa, và chia sẻ linh hoạt.
-   **[Express.js](https://expressjs.com/):**
    -   Framework mạnh mẽ cho Node.js, được sử dụng để xây dựng các API RESTful.
    -   Đảm bảo hiệu suất và dễ dàng mở rộng.

---

## 📌 **Chủ đề**

### **Thêm, Xóa, Sửa Sản phẩm và Lưu trữ Hình ảnh trên Cloudinary**

Hệ thống quản lý sản phẩm với các tính năng chính:

1. **Thêm sản phẩm:**
    - Tạo mới thông tin sản phẩm bao gồm tên, giá, mô tả và hình ảnh.
    - Hình ảnh được tải lên và lưu trữ trên Cloudinary.
2. **Xóa sản phẩm:**
    - Loại bỏ các sản phẩm không còn cần thiết hoặc đã lỗi thời.
3. **Sửa sản phẩm:**
    - Cập nhật thông tin sản phẩm (tên, giá, mô tả) và thay đổi hình ảnh khi cần.
4. **Lưu trữ hình ảnh:**
    - Tích hợp Cloudinary để lưu trữ hình ảnh với khả năng tối ưu hóa tự động.
    - Đảm bảo tốc độ tải nhanh và dễ dàng quản lý hình ảnh.

---

## 🌐 **Danh sách API**

| **Phương thức** | **Đường dẫn**                                                          | **Mô tả**                            |
| --------------- | ---------------------------------------------------------------------- | ------------------------------------ |
| `GET`           | `http://localhost:3000/v2/api/product/getAllProducts`                  | Lấy danh sách tất cả sản phẩm.       |
| `GET`           | `http://localhost:3000/v2/api/product/searchELT?query=U`               | Tìm kiếm sản phẩm theo từ khóa.      |
| `POST`          | `http://localhost:3000/v2/api/product/create`                          | Tạo mới một sản phẩm.                |
| `PUT`           | `http://localhost:3000/v2/api/product/update/673367f2d2f6433ff688b850` | Cập nhật thông tin sản phẩm theo ID. |
| `DELETE`        | `http://localhost:3000/v2/api/product/delete/67277852c5616d14111f374e` | Xóa sản phẩm theo ID.                |

---

## 🎯 **Mục tiêu**

-   Xây dựng hệ thống quản lý sản phẩm hiện đại, thân thiện và hiệu quả.
-   Đảm bảo hình ảnh sản phẩm được lưu trữ và quản lý một cách an toàn, tối ưu.
-   Tăng cường trải nghiệm người dùng bằng hiệu suất cao và giao diện dễ sử dụng.

---

> ✨ _"Chúng tôi cam kết mang đến giải pháp quản lý sản phẩm tối ưu nhất, với sự kết hợp hài hòa giữa công nghệ hiện đại và tinh thần làm việc nhóm đầy nhiệt huyết."_

---

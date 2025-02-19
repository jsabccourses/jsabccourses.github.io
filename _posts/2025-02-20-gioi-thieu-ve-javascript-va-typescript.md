---
title: "Giới thiệu về JavaScript và Typescript"
date: 2025-02-20
categories: [Blog]
tags: [Javascript, TypeScript, gioi-thieu]
layout: post
---

### **1. Giới thiệu về JavaScript**  

#### **Lịch sử hình thành JavaScript**  
- **Người sáng lập**: Brendan Eich  
- **Năm ra đời**: 1995  
- **Công ty phát triển**: Netscape Communications  
- **Mục đích ban đầu**:  
  - Netscape muốn tạo ra một ngôn ngữ kịch bản (scripting language) dễ sử dụng cho trình duyệt web.  
  - Brendan Eich đã phát triển JavaScript chỉ trong **10 ngày** để tích hợp vào trình duyệt **Netscape Navigator 2.0**.  
- **Tên gọi ban đầu**: Mocha → LiveScript → JavaScript (do hợp tác với Sun Microsystems, công ty phát triển Java)  

#### **JavaScript là gì?**  
JavaScript là một **ngôn ngữ lập trình thông dịch (interpreted)**, hướng sự kiện, sử dụng rộng rãi để tạo các trang web động, tương tác với người dùng mà không cần tải lại trang.  

#### **Phạm vi ứng dụng của JavaScript**  
- **Lập trình Web** (Front-end & Back-end)  
  - Dùng với HTML & CSS để xây dựng website  
  - Framework phổ biến: React.js, Vue.js, Angular  
  - Chạy trên trình duyệt, giúp tạo hiệu ứng động, xử lý sự kiện  
- **Lập trình Server-side** (Back-end)  
  - Dùng với Node.js để viết API, server  
  - Express.js, NestJS là các framework phổ biến  
- **Phát triển ứng dụng di động**  
  - React Native, Ionic  
- **Phát triển ứng dụng Desktop**  
  - Electron.js giúp tạo ứng dụng trên Windows, macOS, Linux  
- **Lập trình Game**  
  - Sử dụng Three.js, Babylon.js để làm game 2D/3D  
- **Machine Learning & AI**  
  - TensorFlow.js giúp chạy mô hình AI trên trình duyệt  

---

### **2. Giới thiệu về TypeScript**  

#### **Lịch sử hình thành TypeScript**  
- **Người sáng lập**: Anders Hejlsberg (cha đẻ của C#)  
- **Năm ra đời**: 2012  
- **Công ty phát triển**: Microsoft  
- **Mục đích**:  
  - Cải thiện JavaScript bằng cách thêm **hệ thống kiểu tĩnh (static typing)**.  
  - Giúp phát triển ứng dụng lớn dễ dàng hơn với tính năng kiểm tra lỗi trước khi chạy.  

#### **TypeScript là gì?**  
TypeScript là một **ngôn ngữ lập trình mở rộng của JavaScript** (superset), có cú pháp tương tự nhưng bổ sung **kiểu dữ liệu tĩnh (static typing)**, giúp giảm lỗi và tối ưu hóa code.  

#### **Phạm vi ứng dụng của TypeScript**  
- **Lập trình Web & Front-end**  
  - Được sử dụng trong các dự án lớn với React.js, Vue.js, Angular  
  - Giúp quản lý mã nguồn tốt hơn trong dự án quy mô lớn  
- **Lập trình Back-end**  
  - Kết hợp với Node.js, Express.js, NestJS để viết API  
- **Phát triển ứng dụng di động & Desktop**  
  - React Native, Ionic, Electron.js  
- **Lập trình Game**  
  - Dùng trong Babylon.js, Phaser  
- **AI & Machine Learning**  
  - TensorFlow.js hỗ trợ TypeScript  

---

### **3. So sánh JavaScript và TypeScript**  

| Tiêu chí | JavaScript | TypeScript |
|----------|------------|------------|
| **Kiểu dữ liệu** | Động (Dynamic Typing) | Tĩnh (Static Typing) |
| **Hỗ trợ trình duyệt** | Chạy trực tiếp trên trình duyệt | Phải biên dịch thành JavaScript |
| **Quy mô dự án** | Phù hợp với dự án nhỏ | Phù hợp với dự án lớn, bảo trì lâu dài |
| **Tính năng OOP** | Hỗ trợ một phần | Hỗ trợ tốt hơn (Class, Interface, Generics) |
| **Kiểm tra lỗi** | Chạy đến đâu kiểm tra lỗi đến đó | Phát hiện lỗi ngay khi viết code |
| **Hỗ trợ IDE** | Hỗ trợ cơ bản | Tốt hơn nhờ IntelliSense |

---

### **4. Kết luận**
- **JavaScript** là ngôn ngữ linh hoạt, phù hợp cho nhiều loại dự án.  
- **TypeScript** là một lựa chọn mạnh mẽ khi cần kiểm soát tốt hơn, giảm lỗi, đặc biệt với các dự án lớn.  
- Nếu bạn đang làm một dự án ngắn hạn hoặc nhỏ, **JavaScript** là đủ. Nếu làm dự án lớn, bảo trì lâu dài, **TypeScript** là lựa chọn tốt hơn.
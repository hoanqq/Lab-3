
# Nhập Môn Xử Lý Ảnh Số - Lab 3  
## **Biến Đổi Hình Học và Lọc Butterworth trên Ảnh RGB**  
**Sinh viên thực hiện:** Nguyễn Khắc Huy Hoàng  
**MSSV:** 2374802010151  
**Môn học:** Nhập môn Xử lý ảnh số  
**Giảng viên:** Đỗ Hữu Quân  

---

## Giới thiệu

Lab 3 tập trung vào **biến đổi hình học** (resizing, rotation) và **lọc ảnh RGB** bằng kỹ thuật Butterworth Filter. Đây là những kỹ thuật quan trọng trong tiền xử lý ảnh và nhận dạng mẫu.

---

## Nội dung chính

### 1. Biến đổi hình học (Geometric Transformations)
- **Resize ảnh** để thay đổi kích thước theo tỷ lệ hoặc kích thước cố định
- **Xoay ảnh** (Rotation) theo các góc nhất định
- Ứng dụng trong việc chuẩn hóa ảnh đầu vào cho hệ thống thị giác máy

### 2. Lọc Butterworth trên ảnh RGB
- Lọc tần số thấp hoặc cao trên từng kênh màu (R, G, B)
- Làm mịn ảnh, giảm nhiễu nhưng vẫn giữ lại thông tin chính
- Thực hiện trên ảnh màu thông qua biến đổi Fourier

---

## Công nghệ sử dụng

- **Python**
- **NumPy**
- **OpenCV (cv2)**
- **Matplotlib**
- **Pillow (PIL)**

---

## Cấu trúc thư mục

```
Lab3_NguyenKhacHuyHoang_2374802010151/
├── Lab3_NguyenKhacHuyHoang_2374802010151/
│   ├── fruit.jpg
│   ├── Lab3.IPYNB
│   ├── Lab_3_Geometric_Transformation_images.pdf
│   ├── output_fruits_modified.jpg
│   ├── pagoda.jpg
│   ├── world_cup.jpg
│   ├── exercise/
│   │   ├── colorful-ripe-tropical-fruits.jpg
│   │   ├── ha-long-bay-in-vietnam.jpg
│   │   ├── pagoda.jpg
│   │   ├── quang_ninh.jpg
│   ├── output_pagoda/
│   │   ├── pagoda_resized.jpg
│   ├── output_rgb_butterworth/
│   │   ├── filtered_colorful-ripe-tropical-fruits.jpg
│   │   ├── filtered_ha-long-bay-in-vietnam.jpg
│   │   ├── filtered_pagoda.jpg
│   │   ├── filtered_quang_ninh.jpg
│   ├── output_rotated/
│   │   ├── boat_rotated.jpg
│   │   ├── mountain_rotated.jpg
```

---

## Hướng dẫn thực hiện

### 1. Cài đặt thư viện cần thiết

```bash
pip install numpy opencv-python matplotlib pillow
```

### 2. Mở notebook và chạy

- Dùng Jupyter Notebook hoặc Google Colab mở file `Lab3.IPYNB`
- Thực hiện tuần tự các cell để quan sát kết quả
- Kiểm tra các ảnh đầu ra tại thư mục `output_*`

---

## Kết luận

Thông qua bài Lab này, sinh viên sẽ hiểu rõ hơn về các phép biến đổi hình học cơ bản và kỹ thuật lọc ảnh trong không gian tần số. Đây là nền tảng quan trọng cho xử lý ảnh nâng cao như nhận dạng, phát hiện đối tượng,...

---

## Tài liệu tham khảo

- *Digital Image Processing* – Rafael C. Gonzalez  
- [https://docs.opencv.org](https://docs.opencv.org)  
- [https://numpy.org](https://numpy.org)  
- Slide bài giảng môn Nhập môn Xử lý ảnh số – Văn Lang University

---

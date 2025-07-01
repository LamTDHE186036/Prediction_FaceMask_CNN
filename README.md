# Prediction_FaceMask_CNN

---

## Data

Tập dữ liệu được sử dụng nằm trên Kaggle. Do kích thước lớn của dữ liệu, **việc huấn luyện cần được thực hiện trên [Kaggle Notebooks](https://www.kaggle.com/code)** để tránh giới hạn dung lượng tải về.

 **Link Dataset trên Kaggle**:  
[Face Mask Detection Dataset](https://www.kaggle.com/datasets/trandailamk18hl/dataset-facemask)

Hướng dẫn sử dụng:

1. Tạo một notebook mới trên Kaggle.
2. Thêm dataset thông qua "Add Dataset".
3. Tải file `train_model/train_mask_detector.ipynb` lên và chạy trực tiếp.

---

## Train_model

Notebook `mask-detection.ipynb` sẽ thực hiện các bước sau:

- Tiền xử lý dữ liệu hình ảnh
- Xây dựng mô hình CNN
- Huấn luyện và đánh giá mô hình
- Lưu mô hình đã huấn luyện thành file `mask_detector.h5`

> **Lưu ý**: Do giới hạn của dung lượng tập dữ liệu, **việc huấn luyện nên thực hiện trên Kaggle**. Sau khi huấn luyện xong, hãy tải file `mask_detector.h5` về 

---

## Test_model

Notebook `Test_image.ipynb` sẽ:

- Tải mô hình `.h5` đã huấn luyện
- Thử nghiệm dự đoán trên **ảnh bên ngoài** (ảnh do bạn cung cấp)
- Hiển thị ảnh kèm nhãn dự đoán: **"Có khẩu trang"** hoặc **"Không khẩu trang"**


---



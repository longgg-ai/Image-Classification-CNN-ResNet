# NGHIÊN CỨU MẠNG NEURAL TRONG NHẬN DẠNG ẢNH

## 1. Giới thiệu
Dự án thực hiện nghiên cứu và xây dựng các mô hình mạng Neural trong bài toán phân loại hình ảnh, sử dụng Python và TensorFlow trên Google Colab.

Nội dung thực nghiệm gồm:
- Xây dựng mạng CNN cơ bản trên bộ dữ liệu CIFAR-10.
- Xây dựng mạng ResNet rút gọn trên bộ dữ liệu CIFAR-100.
- Huấn luyện, đánh giá và trực quan hóa kết quả nhận dạng ảnh.

## 2. CNN trên CIFAR-10

- Bộ dữ liệu: CIFAR-10 (10 lớp đối tượng).
- Mô hình: Convolutional Neural Network (CNN).
- Số lần huấn luyện: 10 epochs.
- Độ chính xác trên tập Test: **70,23%**.

## 3. ResNet trên CIFAR-100

- Bộ dữ liệu: CIFAR-100 (100 lớp đối tượng).
- Mô hình: ResNet rút gọn sử dụng Residual Block.
- Số lần huấn luyện: 15 epochs.
- Training Accuracy: **39,26%**.
- Validation Accuracy: **25,69%**.

## 4. Công nghệ sử dụng

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab (T4 GPU)

## 5. Kết quả và nhận xét

Mô hình CNN đạt độ chính xác 70,23% trên CIFAR-10.

Mô hình ResNet rút gọn trên CIFAR-100 có độ chính xác validation 25,69%. Kết quả còn hạn chế do bộ dữ liệu có 100 lớp và kiến trúc mô hình tương đối nhỏ.

Hướng cải thiện: tăng số epochs, sử dụng Data Augmentation và tối ưu kiến trúc mạng.

## 6. Các file trong dự án

- `CNN_CIFAR10.ipynb`: Code huấn luyện và đánh giá CNN trên CIFAR-10.
- `ResNet_CIFAR100.ipynb`: Code huấn luyện và đánh giá ResNet trên CIFAR-100.

## 7. Kết luận

Dự án giúp tìm hiểu nguyên lý hoạt động của mạng Neural trong nhận dạng hình ảnh, thực hành huấn luyện mô hình và đánh giá kết quả bằng Accuracy, Loss và hình ảnh dự đoán.

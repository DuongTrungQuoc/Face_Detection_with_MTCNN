# 📜 Project Nhận diện khuôn mặt

## 🥚 Giới thiệu
**Nhận diện khuôn mặt (Face Recognition)** được chia thành 2 vấn đề chính: **Phát hiện khuôn măt (Face Detection)** và **Phân biệt khuôn mặt (Face Verification)**.

**Multi-task Cascaded Convolutional Networks (MTCNN)** được dùng để **Phát hiện khuôn mặt (Face Detection)**, bao gồm 3 mạng CNN xếp chồng và đồng thời hoạt động khi detect khuôn mặt. Mỗi mạng có cấu trúc khác nhau và đảm nhiệm vai trò khác nhau trong task. Đầu ra của MTCNN là vị trí khuôn mặt và các điểm trên mặt như: mắt, mũi, miệng… 

**Facenet** được dùng để **Phân biệt khuôn mặt (Face Verification)**, được Google giới thiệu năm 2015. Tạm hiểu cách dùng model này là mình cứ đưa ảnh vào (đúng size của nó) thì nó trả ra 1 vector 128 features cho 1 khuôn mặt. Sau đó dùng SVM để phân nhóm các vector đó vào các nhóm để biết vector đó là mặt của ai.

### 🐔 Nguồn tham khảo
> **BlogEN**: [Face Recognition with FaceNet and MTCNN](https://arsfutura.com/blog/face-recognition-with-facenet-and-mtcnn) <br>
> **Newspaper**:  [Joint Face Detection and Alignment using Multi-task Cascaded Convolutional Networks](https://arxiv.org/ftp/arxiv/papers/1604/1604.02878.pdf) <br>
> **GitHub**:  [FaceNet and MTCNN Implement GitHub Repository](https://github.com/timesler/facenet-pytorch) <br>

> **BlogVN**:  [Nhận diện khuôn mặt với mạng MTCNN và FaceNet (Phần 1)](https://viblo.asia/p/nhan-dien-khuon-mat-voi-mang-mtcnn-va-facenet-phan-1-Qbq5QDN4lD8) <br>
> **BlogVN**:  [Nhận diện khuôn mặt với mạng MTCNN và FaceNet (Phần 2)](https://viblo.asia/p/nhan-dien-khuon-mat-voi-mang-mtcnn-va-facenet-phan-1-Qbq5QDN4lD8) <br>
>  **BlogVN**: [[Mì AI] Nhận dạng khuôn mặt với MTCNN và Facenet](https://miai.vn/2019/09/11/face-recog-2-0-nhan-dien-khuon-mat-trong-video-bang-mtcnn-va-facenet/?fbclid=IwY2xjawGPbO9leHRuA2FlbQIxMAABHTq4RGcDptPqs1LcFditO5_FEwav3twSB50tct3SHPReR-ouuN2mNIYfMg_aem_hdn8sPDC0StOxu9P7QvfcA) <br>

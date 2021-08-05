DeepSORT là mô hình tracking sử dụng tiền đề là pre-train của các thuật toán detection. 

Để chuẩn bị cho đồ án 2, Tôi đã dùng pre-train của đồ án 1 và bổ sung data mới mà nhóm thêm vào. 

Link tải weight detection: https://drive.google.com/file/d/1-3pfIcD76AYIgsv3A7Gd84bIQycdAene/view?usp=sharing

Bài gồm 2 file Tracking-DeepSORT.ipynb và Detection_YOLOv4_tiny.ipynb

Hướng dẫn: 
Trước tiên, chạy tuần từ theo file Detection_YOLOv4_tiny.ipynb.
Điều chỉnh các thông số theo hướng dẫn để chuẩn bị GPU cho thuật toán.
Sử dụng fork darknet cung cấp bởi Roboflow.
Chạy theo các bước đã chú thích trong file.
Lựa chọn weight mong muốn để dùng cho tracking.

Trong file Tracking-DeepSORT.ipynb cũng có chú thích code.
Cần phải "Cloning the Repository" môi trường tracking được cung cấp bởi The AI Guy.
Quan trọng nhất là covert được định dạng darknet từ file weight có sẵn thành định dạng Tensorflow theo yêu cầu của thuật toán.
Chạy các bước tiếp theo sẽ cho ra được video tracked. 

Do sai sót trong quá trình làm dữ liệu dẫn đến dữ liệu không giống với định dạng yêu cầu. Trong ipynb chưa thể cho ra được độ đo đánh giá mô hình như mong muốn. Nhóm sẽ tiếp tục nghiên cứu tìm ra cách khắc phục điểm yếu và phát triển thành quả. 
 



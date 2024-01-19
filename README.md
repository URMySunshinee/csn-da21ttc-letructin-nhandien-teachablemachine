# ĐỒ ÁN CƠ SỞ NGÀNH 
## NGHIÊN CỨU TEACHABLE MACHINE ĐỂ TẠO ỨNG DỤNG/VIDEO DEMO QUẢNG BÁ TUYỂN SINH NGÀNH TRÍ TUỆ NHÂN TẠO

| GVHD           | Sinh viên thực hiện|
| :--------------| :------------------| 
| Trầm Hoàng Nam | Lê Trực Tín        | 

## Nội dung của dự án.
Đề tài này tôi nghiên cứu sử dụng công cụ [Teachable Machine](https://teachablemachine.withgoogle.com/) để huấn luyện mô hình nhận dạng hình ảnh, âm thanh, dáng người. Sau đó tích hợp mô hình đã huấn luyện vào trong trang web HTML.

## Công cụ sử dụng trong dự án.
* [Teachable Machine](https://teachablemachine.withgoogle.com/)
* HTML
* Javascript
* p5.js (thư viện đồ họa để dựng lên mô hình trong trang web)

## Cách sử dụng sản phẩm của dự án này.
Sản phẩm cuối cùng là phần code HTML được tích hợp mô hình đã huấn luyện mà tôi để trong file **src**, bạn chỉ cần lấy nó và chạy. <br>
Kết quả sau khi chạy code: <br> ![topdev](https://i.pinimg.com/736x/3e/bf/d3/3ebfd39b3201fa9e8f3425e3820bc6e5.jpg)

## Cách thay thế mô hình huấn luyện của bạn.
Để sử dụng sản phẩm với dữ liệu huấn luyện của bạn thì thực hiện bước sau:
* B1: Truy cập vào [Teachable Machine](https://teachablemachine.withgoogle.com/) và tiến hành huấn luyện.
* B2: Bấm vào **Export Model** &rarr; **Upload my model** &rarr; Sao chép link chia sẻ mô hình của bạn.
* B3: Trong các file code html của dự án đều có một dòng code như thế này để lấy model bạn huấn luyện từ máy chủ của Teachable Machine. Và bạn chỉ cần thay thế đường dẫn trong code bằng đường dẫn mà bạn sao chép ở B2. 
~~~html
    //Model URL
    let imageModelURL = 'https://teachablemachine.withgoogle.com/models/A8GUvxrZi/';
 ~~~
 
 ## Lời cảm ơn
 Xin chân thành cảm ơn đối với các thầy cô của trường Đại học Trà Vinh, đặc biệt là các thầy cô khoa Công Nghệ Thông Tin của trường đã tạo điều kiện cho em được trải nghiệm làm Đồ án đầu tiên của em, cụ thể hơn là Đồ án Cơ Sở Ngành. Và cũng xin chân thành cảm ơn thầy Trầm Hoàng Nam (GVHD) và thầy Nguyễn Bảo Ân đã nhiệt tình hướng dẫn em hoàn thành tốt đồ án của mình.

## Thông tin tác giả:
Lê Trực Tín <br>
Email: hztinle1006@gmail.com <br>
SĐT: 0949062229


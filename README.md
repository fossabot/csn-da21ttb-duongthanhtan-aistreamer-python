<!-- Phần ảnh đầu trang -->
<a href="https://github.com/ThanhhTann/csn-da21ttb-duongthanhtan-aistreamer-python">
    <img src="https://i.ibb.co/S3tn7w4/Banner-AI-Streamer-1.gif">
</a>
<!-- Phần tiêu đề trang -->
<a href="https://github.com/ThanhhTann/csn-da21ttb-duongthanhtan-aistreamer-python">
    <img src="https://i.ibb.co/xSD8JqY/Banner-AI-Streamer-2.gif">
</a>
<!-- Phần cài đặt các tiện ích -->
<p align="center">
    <a href="https://docs.d-id.com/reference/get-started">
        <img src="https://img.shields.io/badge/D--DI-API-%235014FF" alt="D-ID">
    </a>
    <a href="https://platform.openai.com/overview">
        <img src="https://img.shields.io/badge/OpenAI-API-%235014FF" alt="Openai">
    </a>
    <a href="https://openai.com/policies/terms-of-use">
        <img src="https://img.shields.io/badge/License-OpenAI-%235014FF">
    </a>
    <a href="https://www.d-id.com/studio-end-user-license-agreement">
        <img src="https://img.shields.io/badge/License-D--ID-%235014FF">
    </a>
</p>
<!-- Phần điều khoản -->
<p align="center"> 
    <a href="https://files2.codecguide.com/K-Lite_Codec_Pack_1805_Full.exe">
        <img src="https://img.shields.io/badge/K--Lite-18.0.5-%235014FF">
    </a>
    <a href="https://www.python.org/ftp/python/3.12.1/python-3.12.1-amd64.exe">
        <img src="https://img.shields.io/badge/Python-3.12.1-%235014FF" alt="Python">
    </a>
    <a href="https://bom.so/2Thd6G">
        <img src="https://img.shields.io/badge/FFmpeg-6.1.1-%235014FF" alt="FFmpeg">
    </a>
</p>

## 🔮Tổng quan
Dự án xây dựng `phần mềm AI Streamer` đang trong quá trình nghiên cứu và triển khai ứng dụng `Trí Tuệ Nhân Tạo`, sử dụng các mô hình AI tiên tiến như `ChatGPT` và `D-ID`. Mục đích của dự án là phát triển một phần mềm có khả năng tự tạo ra nội dung đa dạng, hình ảnh và video khuôn mặt để giới thiệu và quảng bá sản phẩm, dựa trên dữ liệu đầu vào từ người dùng.
> Lưu ý: Dự án đang trong giai đoạn nghiên cứu và thử nghiệm, hiệu suất và ứng dụng thực tế của dự án chưa được xác minh và đánh giá toàn diện. Tuy nhiên, dự án này đang tiếp tục được cải tiến và phát triển với hy vọng sẽ đóng góp một phần quan trọng cho lĩnh vực thương mại điện tử trong tương lai.

## 🔮Tính năng chính
Phần mềm AI Streamer có các tính năng chính sau:
- Tự động tạo nội dung văn bản từ mô hình `Generative Pre-trained Transformer 3.5 Turbo`.
- Tự động chọn giọng nói và video khuôn mặt động để giới thiệu sản phẩm.
- Tích hợp API của `D-ID` để tạo video cùng với giọng nói tự nhiên.
- Tích hợp tùy chọn hình ảnh tùy chỉnh.

## 🔮Thiết lập hệ thống
- **Cấu hình tối thiểu:**
<div align="center">

| Cấu hình           | Diễn giải                             |
| ------------------ | ------------------------------------- |
| Hệ điều hành       | Windows 10                            |
| RAM                | 8GB `(1600 MHz)`                      |
| Dung lượng ổ cứng  | 1GB `(HDD hoặc SSD)`                  |
| CPU Intel          | Core i3 - 2375 `(1.5GHz)`             |
| CPU AMD            | Ryzen 3 - 1200 `(3.1GHz)`             |

</div>


- **Cài đặt Python:**
   - Tải bản cài đặt Python 3.12.1: [Tại đây!!](https://www.python.org/ftp/python/3.12.1/python-3.12.1-amd64.exe).
   - Mở tệp cài đặt đã tải để bắt đầu quá trình cài đặt.
   - Trong trình cài đặt, chọn tùy chọn `Add Python 3.12 to PATH`.
   - Nhấn `Install Now` để bắt đầu quá trình cài đặt.
   - Mở `Command Prompt` và kiểm tra phiên bản Python đã cài đặt:
     ```Python
     python --version
     ```

- **Cài đặt K-Lite Codec Pack:**
   - Tải bản cài đặt K-Lite Codec Pack 18.0.5: [Tại đây!!](https://files2.codecguide.com/K-Lite_Codec_Pack_1805_Full.exe). 
   - Mở tệp cài đặt đã tải để bắt đầu quá trình cài đặt.
   - Sử dụng tổ hợp phím `Win + S`, để mở thanh tìm kiếm trên Windows và gõ:
     ```K-Lite
     K-Lite Codec Pack
     ```

- **Cài đặt FFmpeg:**
   - Tải bản cài đặt FFmpeg 6.1.1: [Tại đây!!](https://bom.so/2Thd6G). 
   - Sau khi tải xong, giải nén thư mục `ffmpeg-6.1.1` bằng cách chọn `Extract Here`.
   - Đổi tên thư mục vừa giải nén thành:
     ```FFmpeg
     ffmpeg
     ```  
   - Di chuyển thư mục `ffmpeg` vào `ổ đĩa C`, nên đường dẫn sẽ là:
     ```FFmpegg
     C:\ffmpeg
     ```  
   - Mở thanh tìm kiếm trên Windows bằng cách nhấn tổ hợp phím `Win + S` và gõ:
     ```FFmpeggg
     View advanced system settings
     ```   
   - Chọn tab `Advanced` và click vào nút `Environment Variables`.
   - Trong phần `User Variables` => chọn `Path` => nhấn `Edit`.
   - Chọn vào nút `New` và thêm đường dẫn:
     ```FFmpegggg
     C:\ffmpeg\bin
     ``` 
   - Nhấn `OK` để lưu thay đổi.

## 🔮Thiết lập môi trường
- [Đang cập nhật lại toàn bộ nội dung]
## 🔮Thông tin tác giả
- [Đang cập nhật lại toàn bộ nội dung]
## 🔮Thông tin giấy phép
- [Đang cập nhật lại toàn bộ nội dung]




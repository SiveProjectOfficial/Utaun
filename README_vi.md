[🇻🇳 Quay lại chọn ngôn ngữ](./README.md)
# Utaun là gì? 

Utaun là một phần mềm Windows tạo ra các ngân hàng giọng hát CV (Phụ âm-Nguyên âm) cho UTAU bằng cách sử dụng độc quyền mô hình hình sin hỗn hợp (tổng hợp giọng nói CSM) hoàn toàn vô tri vô giác.  
Nó hỗ trợ tự động tạo tệp lưu trữ ZIP của ngân hàng giọng hát trong thư mục Tài liệu (Documents), cũng như xuất trực tiếp sang các phần mềm tương thích với UTAU khác nhau.  

# Tính năng  

* Tự động tạo tệp ZIP của ngân hàng giọng hát trong thư mục Tài liệu của bạn hoặc xuất trực tiếp sang phần mềm tương thích khi chạy.  
* Tạo các nguyên âm (A, I, U, E, O, N) thông qua mô hình hình sin hỗn hợp (tổng hợp giọng nói CSM) hoàn toàn vô tri vô giác.  
* Định cấu hình các thư mục phụ âm và âm hữu thanh có trong thư mục Tài liệu của bạn để tạo ngân hàng giọng hát CV.  
* Tự động tạo các hàng m, n, y và w bên trong chương trình.  
* Hỗ trợ các biệt hiệu (alias) bằng Hiragana + biệt hiệu Romaji tiếng Anh (tất cả đều phát âm theo tiếng Nhật).  
* Tự động tạo `oto.ini`, `character.txt` và `readme.txt`.  
* Đồng thời chuyển đổi hình ảnh PNG sang định dạng JPG và BMP (Lưu ý: định dạng JPG được sử dụng cho `character.txt`).  
* Mã hóa của `readme.txt` và `character.txt` có thể được chọn giữa **Shift-JIS (ANSI)** và **UTF-8** (Lưu ý: UTF-8 đảm bảo khả năng tương thích với OpenUTAU và các phần mềm khác).  
* Cho phép thay đổi tần số cơ bản (cao độ giọng nói).  
* Tên ngân hàng giọng hát (tên nhân vật) có thể tùy chỉnh tự do.  
* **Hỗ trợ chế độ Sáng (Light) và Tối (Dark).**  
* **Cho phép chọn điểm đến xuất tệp.**  

# Mục đích sử dụng  

* Khi bạn muốn tạo các ngân hàng giọng hát UTAU sử dụng giọng nói vô tri hoặc nhân tạo.  
* Dành cho việc sản xuất ngân hàng giọng hát nếu bạn cảm thấy khó khăn hoặc bất tiện khi ghi âm bằng chính giọng nói của mình.  
* Nghiên cứu các tài liệu âm thanh dựa trên mô hình hình sin hỗn hợp (tổng hợp giọng nói CSM).  
* Tạo mẫu (prototyping) các ngân hàng giọng hát tùy chỉnh.  
* Giải nén tệp ZIP được tạo để sử dụng trực tiếp làm tài nguyên vocaloid mô phỏng con người.  
* Sử dụng làm tài liệu âm thanh cho các bản remix video (ví dụ: OtoMAD, YTPMV).  

# Cách sử dụng Utaun  

① Tải xuống phiên bản Utaun mới nhất từ **[GitHub Releases](#Releases)**.  
② Nếu bạn đang tải xuống phiên bản thư mục ZIP, **hãy đặt các thư mục "Consonant/Voiced Sound" và `oto.ini` trực tiếp vào bên trong thư mục "Documents" (cũng hỗ trợ OneDrive Documents).** (Lưu ý: Các thư mục này được đặt tự động nếu bạn sử dụng phiên bản cài đặt).  
③ Đặt `Utaun.exe` vào bất kỳ thư mục nào bạn chọn.  
④ Khởi động `Utaun.exe` và làm theo hướng dẫn trên màn hình để tạo ngân hàng giọng hát của bạn.  
⑤ Đối với vị trí lưu dữ liệu, bạn có thể chọn giữa đầu ra ZIP (Tài liệu, v.v.) hoặc xuất thư mục trực tiếp sang UTAU và OpenUTAU.  
*Lưu ý: Tính năng cập nhật tự động sẽ có sẵn trong các phiên bản tương lai.*  

# UI
**UI (Màn hình thao tác - Sáng)**   
 ![Test Image 3](UI/IMG_5542.jpeg)  
**UI (Màn hình cài đặt - Sáng)**  
![Test Image4](UI/IMG_5538.jpeg)
**UI (Màn hình thao tác - Tối)**  
![Test Image5](UI/IMG_5540.jpeg)  
**UI (Màn hình cài đặt - Tối)**  
![Test Image6](UI/IMG_5541.jpeg)  
**UI (Màn hình đang xuất)**  
![Test Image7](UI/IMG_5536.jpeg)  
**UI (Màn hình chi tiết cập nhật)**  
![Test Image8](UI/IMG_5539.jpeg)  
**UI (Màn hình cập nhật)**  
![Test Image9](UI/IMG_5537.jpeg)

# Khả năng tương thích và cách sử dụng ngân hàng giọng hát được tạo  

* **UTAU**  
  Xuất trực tiếp dưới dạng thư mục ngân hàng giọng hát chưa nén vào thư mục `voice` của bạn từ trong ứng dụng và sử dụng ngay lập tức.  
* **OpenUTAU**  
  Xuất trực tiếp dưới dạng thư mục ngân hàng giọng hát chưa nén vào thư mục `Singers` của bạn từ trong ứng dụng và sử dụng ngay lập tức.  
* **UtauTTS**  
  Giải nén tệp ZIP đã xuất và đặt nó vào thư mục `voice` của `utauTTS`.  
* **UtauV**  
  Kéo và thả tệp ZIP vào cửa sổ ứng dụng UtaunV đang chạy.  
* **UTAlet (Phiên bản web)**  
  Kéo và thả tệp ZIP lên màn hình của trang web chính thức.  
*Lưu ý: Để biết hướng dẫn sử dụng cụ thể trong từng phần mềm hoặc môi trường web, vui lòng tham khảo các tệp trợ giúp, hướng dẫn sử dụng hoặc tài liệu chính thức tương ứng của họ.*  

# Yêu cầu hệ thống  

* Windows 10 đến 11 (hỗ trợ 64-bit / 32-bit)  
**(Lưu ý: Phiên bản 32-bit được sử dụng làm nền tảng do các cân nhắc về kích thước tệp, nhưng chương trình vẫn chạy trơn tru trên Windows 64-bit.)**  

# Các tính năng không được hỗ trợ  

* Nguyên âm hữu thanh (あ゙, い゙, ゔ, え゙, お゙)  
* Các biến thể biểu cảm như tiếng thì thầm, tiếng thở hoặc thành phần hơi thổi  
* Âm vòm hóa / ngạc cứng (ví dụ: kya, kyu, kyo / sha, shu, sho)  
* VCV (Nguyên âm liên tục)  
* CVVC  
* Các phát âm đặc biệt khác  

# Điều khoản sử dụng  

Các hành động sau đây bị nghiêm cấm đối với bản thân ứng dụng Utaun (`Utaun.exe`):  
* Sửa đổi  
* Chỉnh sửa  
* Thay đổi  
* Sử dụng thương mại  
* Phân phối lại  
* Biên dịch ngược (disassembly)  

# Nội dung được tạo  

(Ngân hàng giọng hát, tệp `.wav`, `icon.jpg` / `icon.bmp`, `oto.ini`, v.v.)  
Bạn (bên phân phối) hoàn toàn tự do thiết lập các điều khoản sử dụng của riêng mình cho nội dung được tạo.  
Vui lòng viết các điều khoản cấp phép ưa thích của bạn bên trong `readme.txt`.  

Để biết thông tin về các bản cập nhật và chi tiết, vui lòng kiểm tra trang **Releases** trên GitHub.  

# Releases  
[Download Vietnamese Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇻🇳)

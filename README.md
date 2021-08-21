# Việt Hóa Hearts Of Iron 4

## Mục lục  
  1. [**Tài Nguyên**](#tài-nguyên)
  1. [**Lộ Trình Dịch**](#lộ-trình-dịch)
  1. [**Quy Trình Dịch**](#quy-trình-dịch)

## Tài Nguyên  
### [Link](https://drive.google.com/drive/folders/1GcsTJVj2rh-PeA-iKQaxqkkv4UmRlgg7?usp=sharing) bao gồm
  * Visual Studio Code Portable : editor
  * Translate Helper            : phần mềm hỗ trợ dịch 
  * Bộ font việt hóa
  * Khung mod đã chứa font
  * VH_pack.zip : tất cả những thứ trên

## Lộ Trình Dịch  
![Imgur](https://imgur.com/ynADp89.png "flow")
  * Nhóm 1 chịu trách nhiệm dịch những file nhỏ - trung bình
  * Nhóm 2 chịu trách nhiệm dịch những file lớn
  * Nhóm review hoạt động song song với nhóm dịch, gồm 2 thành viên chính là Lê Đức và Lê Thái Sơn

## Quy trình dịch  
  1. **Mod**  
    * Tải mod về và bỏ vào Documents/Paradox Interactive/Hearts of Iron IV/mod
    * Chỉnh lại đường dẫn trong file vanilla_vh.mod trỏ tới đúng thư mục mod (chỉ cần chỉnh lại username ở ...)
    * Những file dịch mới sẽ đặt vào vanilla_vh/localisation/replace
    * ![Imgur](https://imgur.com/IlJcm07.png 'vanilla_vh.mod')
    
  1. **Trello và Github**  
    * Mỗi thành viên cần có tài khoản trello và github để thêm vào workspace  
    * ![Imgur](https://imgur.com/vjiW1Pa.png)
    * [Link trello workspace](https://trello.com/hoi4_viethoa_new/home)
    * HOI4_VIETHOA_NEW workspace sẽ có 5 bảng tương ứng với các nhóm và giai đoạn dịch
    * Mỗi thành viên sẽ kéo các task từ cột "Cần dịch" sang "Đang dịch" và tự thêm name tag của mình vào thẻ. [Hướng dẫn thêm name tag](https://help.trello.com/article/807-adding-a-member-to-a-card) 
    * Khi dịch xong 1 file -> chuyển file sang cột "Đã dịch" để báo cho nhóm review. Sau đó upload file lên github
    * [Link repo github](https://github.com/RandomDW03/HOI4_VANILLA_VIETHOA.new) và [hướng dẫn upload file](https://www.facebook.com/100015171617407/videos/526754478615150/)

  1. **Yêu cầu và lưu ý**  

    * 1 số quy ước chung
    
      * Không dịch tên các state, tên division đặc biệt, tên nước đặc biệt (Mare Nostrum)
      * Dịch vắn tắt tên nước, tên đảng
      * Tên puppet => Lãnh thổ + tên nước
      * Dominion => Tên nước  
      
    * Hạn chế sử dụng google dịch để tránh tình trạng trong ảnh (The long march => Tháng ba dài)
    * ![Imgur](https://imgur.com/U8rU7pf.png)
    * Cẩn thận tránh dịch các biến gây lỗi. Tham khảo thêm 1 số [Formatting characters](https://hoi4.paradoxwikis.com/Localisation#Formatting_characters) để phân biệt formatting character và variable


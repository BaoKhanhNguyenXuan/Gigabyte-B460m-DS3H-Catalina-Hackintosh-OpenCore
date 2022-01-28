# Gigabyte-B460m-DS3H-Catalina-Hackintosh-OpenCore
Trước khi cài macOS hãy sao lưu dữ liệu của ban. Chúng tôi sẽ không chịu trách nhiệm về sự cố xảy ra với dữ liệu và phần cứng của bạn.

Nguồn: [Facebook](https://www.facebook.com/groups/vnohackintosh/permalink/3416705401709687) [Github](https://github.com/niceit/Gigabyte-B460m-DS3H-Catalina-Hackintosh-OpenCore?fbclid=IwAR0JuoS2DEfRU1aZbJfnv8HUT4Y8ozTVLR1G6bnwXIaZNiTyixG-W2eZMuQ)

Chi tiết phần cứng:
- OS: macOS Catalina 10.15.7 ([Downloaded on mac](https://apps.apple.com/us/app/macos-catalina/id1466841314?mt=12))
- CPU: Intel Core i5-10400
- RAM: 32GB (Not important in RAM)
- MainBoard: Gigabyte B460M-DS3H
- GPU: None
- SSD: Kingspec ssd 240GB SATA3 (Bạn có thể sử dụng ổ cứng hdd hoặc ssd của hãng )
- Audio: Realtek ALC887 (Mặc định của M)
- WLAN & Bluetooth: USB wifi + USB bluetooth
- OpenCore Version: 0.6.0
- SMBIOS: iMac

Tạo bộ cài usb: 
- Có thể tra google hoặc tham khảo [ở đây](https://blogchiasekienthuc.com/hackintosh/tao-usb-cai-hackintosh-bang-opencore-bootloader.html)
- Bạn có thể dùng [MountEFI](https://github.com/corpnewt/MountEFI) mình để sẵn hoặc tải bản mới nhất để tạo phân vùng EFI cho usb
- Nếu bạn không muốn tự tạo thư mục EFI hãy copy thư mục EFI(chứa 2 thư mục BOOT và O) vào phân vùng EFI của usb
- Khi tải bộ cài macOS xong  nếu có thông báo như hình hãy nhấn quit
  ![Screenshot](https://raw.githubusercontent.com/BaoKhanhNguyenXuan/Gigabyte-B460m-DS3H-Catalina-Hackintosh-OpenCore/main/image/alert.png)

Cài đặt macOS:
- Máy mình đã cài sẵn win 10 ở ổ ssd 180Gb và có 1 ổ hdd 1TB để chứ dữ liệu. Mình đã mua thêm 1 ổ cứng ssd 240GB để cài macOS
- Bạn có thể tra google cách cài đặt hoặc tham khảo [ở đây](https://blogchiasekienthuc.com/hackintosh/cai-dat-hackintosh-voi-opencore-bootloader.html)
- Nhớ format theo định APFS như hình nhé
  ![Screenshot](https://raw.githubusercontent.com/BaoKhanhNguyenXuan/Gigabyte-B460m-DS3H-Catalina-Hackintosh-OpenCore/main/image/erase.png)
  
- Nếu bạn dùng usb wifi và không nối mạng dây nhớ tải sẵn driver cho macOS vào usb.
- Sau khi cài đặt xong, hãy tạo phân vùng EFI cho ổ cứng cài macOS và copy thư mục EFI ở bước tạo bộ cài usb vào đó luôn. Sau đó bạn có thể rút usb và khi khởi động máy sẽ có màn hình chọn boot vào win hay mac. Như mình cài xong là phần vùng EFI của usb bị mất, nếu không tạo phân vùng EFI cho ổ cứng cài mac thì máy sẽ tự động boot vào win. Như mình đễ sẵn driver wifi và thư mục EFI trong ổ hdd thì cài mac xong vào đấy để lấy bộ cài và cài vào máy.

Kết quả:
- Mình đã cài xong và thu được kết quả như hình.
- Đợt tới mình sẽ cập nhật lên macOS 12.2 Monterey. Sau khi thành công mình sẽ cập nhật hướng dẫn cách cập nhật lên đây.
  ![Screenshot](https://raw.githubusercontent.com/BaoKhanhNguyenXuan/Gigabyte-B460m-DS3H-Catalina-Hackintosh-OpenCore/main/image/imac.png)
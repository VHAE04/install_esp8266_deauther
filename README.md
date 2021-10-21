# Cách cài esp8266_deauther
## Các bước cài:

1. Cài file `arduino-1.8.5-windows.exe` ở trong folder `1_install_arduino`
2. Cắm `modul esp8266` vào máy tính 
    #### Đối với win 10 thì nó sẽ nhận vào port ở cổng COM3
    ###### Hiện lên với chip tương ứng như `ch340` hoặc `csp210x`
    #### Đối với win 7 - 8 thì phải cài thêm driver
    ######  Vào `2_install_driver` rồi cài driver với chip tương ứng
    
3. Vào `3_install_flash` chạy `ESP8266Flasher` để cài firmware 
    
    - Vào tab `config` chọn file firmware ở đây là bản `esp8266_deauther_2.6.1_AVATAR_5W_E14_LAMP.bin`
    - Chuyển sang tab `Operation` chọn `FLASH`
    
4. Rút dậy nguồn ra cắm lại hoặc ấn vào rút `RST` trên mạch để reset

    


## Cách sử dụng

Sau khi reset mở wifi truy cập vào mạng modul

Tên wifi và Pass mặc định (ở đây ta có thể thay thế được)

| AP WIFI | PASSWORD |
| ------ | ------ |
| pwned | deauther |
    
    
    
Truy cập mặc định trên trình duyệt địa chỉ mặc định (có thể thay thế) là `192.168.4.1`
    
![](https://raw.githubusercontent.com/VHAE04/install_esp8266_deauther/master/image_github/1.jpg)

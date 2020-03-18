# Visio-Installation
**Hướng dẫn cài đặt Visio 2019 Professional Reatail (Key trên Azure)**
-- 
**Bước 1:** Tải về công cụ **Office Deployment Tool**
+ Tải về: https://www.microsoft.com/en-us/download/details.aspx?id=49117
+ Sau khi tải về mình tiến hành "Run as administrator" sau khi Run thì sẽ có 2 file là setup.exe và file configuration.xml. Nhưng mình không cần quan tâm file xml này lắm, vì mình sẽ tiến hành tạo 1 file xml khác để config

**Bước 2:** Tạo file configuration
+ Chúng ta có thể tạo bằng cách sử dụng https://config.office.com/ để tạo file config theo ý muốn nhưng mình sẽ cung cấp sẵn file config để tiện cho việc tiến hành
+ Nhưng để cài đặt VisioPro2019Retail mình sẽ tạo sẵn file config để dễ thao tác.
+ **Lưu ý:** Nên chuyển thư mục Visio vào ổ đĩa C cho tiện thao tác
![image](https://user-images.githubusercontent.com/57827985/76886754-d1695f80-68b3-11ea-965c-befcff6096c5.png)

**Bước 3:** Tiến hành cài đặt bằng Command Prompt
+ Sau khi đã chuyển thư mục Visio vào ổ C ta tiến hành configure bằng cmd như sau:

`cd\`

`cd Visio`

`dir`

`setup.exe /configure visio1.xml`



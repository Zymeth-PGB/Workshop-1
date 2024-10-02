+++
title = "SSH từ VSCode tới EC2"
date = 2024
weight = 3
chapter = false
pre = "<b>3. </b>"
+++

1. Sau khi khởi tạo thành công **EC2 Instance** ở bước trước ta tiếp tục thực hiện cấu hình **Security Group** để có thể truy cập bằng **SSH**
![Image](/Workshop-2/images/3/1.png)
![Image](/Workshop-2/images/3/2.png)
![Image](/Workshop-2/images/3/3.png)

2. Mở **Visual Studio Code** và thực hiện cài đặt **Extension** theo các bước sau
![Image](/Workshop-2/images/3/6.png)
![Image](/Workshop-2/images/3/7.png)

   - Khi thấy phần **install** lúc nãy chuyển sang như vậy thì đã cài đặt thành công
![Image](/Workshop-2/images/3/7-1.png)

3. Thực hiện **SSH** từ **Visual Studio Code** tới **EC2 Instance** 
![Image](/Workshop-2/images/3/8.png)
![Image](/Workshop-2/images/3/9.png)
![Image](/Workshop-2/images/3/10.png)

   - Sau đó quay lại **EC2 Instance** và thực hiện như sau
![Image](/Workshop-2/images/3/4.png)
![Image](/Workshop-2/images/3/5.png)

   - Ta copy dòng được đánh dấu trong đây và quay lại **Visual Studio Code**
![Image](/Workshop-2/images/3/11.png)

   - Ở đây ta thấy dòng được đánh dấu có 1 đoạn là **"path/singapore-key.pem"** thì ngay chữ **path** ta sẽ thay thế bằng đường dẫn đến **folder chứa file key pair** của chúng ta
![Image](/Workshop-2/images/3/12.png)

4. Sau khi thực hiện xong thì bạn đã hoàn tất việc **SSH** từ **Visual Studio Code** đến **EC2 Instance**. Chúc bạn thành công 
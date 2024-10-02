+++
title = "Tạo EC2 Instance"
date = 2024
weight = 2
chapter = false
pre = "<b>2. </b>"
+++

#### Tạo Instance
1. Truy cập vào **EC2 Management Console** bằng cách gõ và chọn dịch vụ **EC2** trong thanh tìm kiếm.
![Image](/Workshop-2/images/2/find-ec2.png)

2. Chọn **Launch Instance** để bắt đầu tạo **Instance**.
![Image](/Workshop-2/images/2/launch_instance.png)

3. Tại màn hình tạo **Instance** đặt tên phù hợp với mục đích sử dụng.
![Image](/Workshop-2/images/2/name.png)

4. Chọn hệ điều hành **Ubuntu** với **AMI** là **Ubuntu Server 24.04 (Free Tier Eligible)** và **Architecture** là **64-bit**.
![Image](/Workshop-2/images/2/os.png)
![Image](/Workshop-2/images/2/versionOs.png)

5. **Instance Type** sẽ chọn là **t2.micro**.
![Image](/Workshop-2/images/2/instanceType.png)

6. Tiếp theo ta sẽ tạo mới 1 **key pair** trong trường hợp bạn chưa có **key pair** còn nếu có rồi thì cứ việc sử dụng **key pair** cũ. Khi tạo **key pair** ta sẽ lưu file **.pem** ở thư mục mà chúng ta cần làm việc để thuận tiện cho việc sử dụng ở bước sau.
![Image](/Workshop-2/images/2/createKeypair.png)
![Image](/Workshop-2/images/2/createKeypair1.png)

    **Key pair** sau khi tải về sẽ được lưu ở đây
![Image](/Workshop-2/images/2/saveKeypair.png)

7. Ở phần **Network** ta sẽ chọn **Security Group** có sẵn để sử dụng.
![Image](/Workshop-2/images/2/securityGroup.png)

8. Dung lượng của **Instance** sẽ để mặc định
![Image](/Workshop-2/images/2/memory.png)

9. Ở bên phải ta sẽ xem được tổng thể về **Instance** khi được tạo sẽ có thông số như thế nào. Ta kiểm tra qua một lượt nếu không có vấn đề gì thì ấn **Launch Instance**
![Image](/Workshop-2/images/2/createInstance.png)

10. Kiểm tra trạng thái của **Instance** nếu giống như hình sau thì đã tạo thành công
![Image](/Workshop-2/images/2/status.png)
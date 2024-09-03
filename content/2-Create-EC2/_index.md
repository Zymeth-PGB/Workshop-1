+++
title = "Tạo EC2 Instance"
date = 2024
weight = 2
chapter = false
pre = "<b>2. </b>"
+++

#### Tạo Instance
1. Truy cập vào **EC2 Management Console** bằng cách gõ và chọn dịch vụ **EC2** trong thanh tìm kiếm.
![Image](/2/find-ec2.png?width=40pc)

2. Chọn **Launch Instance** để bắt đầu tạo **Instance**.
![Image](/2/launch_instance.png?width=40pc)

3. Tại màn hình tạo **Instance** đặt tên phù hợp với mục đích sử dụng.
![Image](/2/name.png?width=40pc)

4. Chọn hệ điều hành **Ubuntu** với **AMI** là **Ubuntu Server 24.04 (Free Tier Eligible)** và **Architecture** là **64-bit**.
![Image](/2/os.png?width=40pc)
![Image](/2/versionOs.png?width=40pc)

5. **Instance Type** sẽ chọn là **t2.micro**.
![Image](/2/instanceType.png?width=40pc)

6. Tiếp theo ta sẽ tạo mới 1 **key pair** trong trường hợp bạn chưa có **key pair** còn nếu có rồi thì cứ việc sử dụng **key pair** cũ. Khi tạo **key pair** ta sẽ lưu file **.pem** ở thư mục mà chúng ta cần làm việc để thuận tiện cho việc sử dụng ở bước sau.
![Image](/2/createKeypair.png?width=40pc)
![Image](/2/createKeypair1.png?width=40pc)

    **Key pair** sau khi tải về sẽ được lưu ở đây
![Image](/2/saveKeypair.png?width=40pc)

7. Ở phần **Network** ta sẽ chọn **Security Group** có sẵn để sử dụng.
![Image](/2/securityGroup.png?width=40pc)

8. Dung lượng của **Instance** sẽ để mặc định
![Image](/2/memory.png?width=40pc)

9. Ở bên phải ta sẽ xem được tổng thể về **Instance** khi được tạo sẽ có thông số như thế nào. Ta kiểm tra qua một lượt nếu không có vấn đề gì thì ấn **Launch Instance**
![Image](/2/createInstance.png?width=40pc)

10. Kiểm tra trạng thái của **Instance** nếu giống như hình sau thì đã tạo thành công
![Image](/2/status.png?width=40pc)
+++
title = "Hướng Dẫn SSH Tới EC2 Cho Người Mới Bắt Đầu"
date = 2024
weight = 1
chapter = false
+++

# Tổng quan

Trong phạm vi **Workshop** này, chúng ta sẽ tìm hiểu cách kết nối **SSH** từ **Visual Studio Code** đến **Instance EC2 của AWS**. Việc thực hiện kết nối từ xa mang lại nhiều lợi ích cho người làm việc từ xa hoặc là đối với nhiều người thì việc code trên máy cá nhân mình là thói quen thì khi có thể kết nối tới một máy chủ như thế giúp họ thao tác nhanh hơn cũng như có thể debug và kết hợp nhiều công cụ khác một cách dễ dàng hơn.

#### SSH (Secure Shell)
**SSH (Secure Shell)** là một giao thức mạng được sử dụng để thiết lập kết nối an toàn giữa hai máy tính, thường là giữa máy tính của người dùng và một máy chủ từ xa. **SSH** cho phép người dùng đăng nhập vào máy chủ từ xa và thực hiện các lệnh trong môi trường dòng lệnh, truyền dữ liệu, hoặc quản lý các dịch vụ và ứng dụng một cách an toàn.

- Các đặc điểm chính của **SSH**:
  - Bảo mật: **SSH** mã hóa tất cả dữ liệu truyền giữa hai máy, giúp bảo vệ thông tin khỏi bị nghe lén hoặc tấn công bởi bên thứ ba.
  - Xác thực: **SSH** yêu cầu xác thực người dùng thông qua mật khẩu hoặc khóa **SSH (SSH key)**, giúp ngăn chặn truy cập trái phép.
  - Khả năng chuyển tiếp cổng **(Port Forwarding)**: **SSH** có thể được sử dụng để chuyển tiếp các cổng từ máy khách đến máy chủ hoặc ngược lại, hỗ trợ truy cập các dịch vụ mạng thông qua một đường kết nối bảo mật.

#### AWS EC2 (Elastic Compute Cloud)
**EC2 (Elastic Compute Cloud)** là một dịch vụ của **Amazon Web Services (AWS)** cung cấp khả năng tính toán đám mây linh hoạt và có thể mở rộng. Nói một cách đơn giản, **EC2** cho phép bạn tạo và quản lý các máy chủ ảo (gọi là "**instances**") trong môi trường đám mây **AWS**, mà bạn có thể sử dụng để chạy các ứng dụng, lưu trữ dữ liệu, hoặc thực hiện các tác vụ tính toán khác.

#### Nội dung chính

1. [Cài đặt Visual Studio Code](1-install-vscode/)
2. [Tạo EC2 Instance](2-create-ec2/)
3. [SSH từ VSCode tới EC2](3-remote-ssh-vscode-to-ec2/)
4. [Dọn dẹp tài nguyên](4-clean-up/)
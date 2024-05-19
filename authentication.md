# Authentication

## 1. Đặt Vấn Đề



## Luồng hoạt động của một hệ thống xác thực
Luồng hoạt động cơ bản của một hệ thống xác thực:
- Bước 01: phía Client gửi thông tin như username/password đến Server để xác thực.
- Bước 02: phía Server sẽ xác thực thông tin, từ đó trả về thông báo lại Client, trong trường hợp thành công, nó sẽ gửi một ...
- Bước 03: phía Client sau khi nhận được **dấu hiệu** từ Server, nó sẽ lưu ở Client, và mỗi khi có một yêu cầu đến Server, nó sẽ kèm theo dấu hiệu đó để Server xác thực
- Bước 04: Server xác thực dấu hiệu.




## 1. Refresh Token, Access Token và JWT


Token là gì? Token là một chuỗi các ký tự phục vụ cho mục đính xác thực.

### Access token
Access token được sinh ra sau khi người dùng đăng nhập thành công vào hệ thống, khi này phía máy chủ sẽ gửi về cho người dùng một chuỗi ký tự, nó chính là access token, phía client sau khi nhận được access token sẽ lưu nó lại và sẽ kèm theo nó mỗi khi muốn gửi yêu cầu đến server.



### Refresh token
Refresh token (RT) là một token khác được sinh ra cùng với Access token, RT có hiệu lực lâu hơn AT 

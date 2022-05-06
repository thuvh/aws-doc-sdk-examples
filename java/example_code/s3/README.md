# Hướng dẫn chạy

1. Windows 11 / Windows 10
2. JDK 1.8 (Oracle / OpenJDK)
3. Jetbrain IntelliJ
4. Tài khoản FPT Object Storage [hướng dẫn](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/get-started.html#get-started-setup-credentials)
   1. Đối với Windows
      1. Tạo tệp tin `C:\Users\<yourUserName>\.aws\credentials`
   2. Đối với Linux
      1. Tạo tệp tin `~/.aws/credentials`
   3. Nội dung tệp tin như sau
   ```
   [default]
   aws_access_key_id = YOUR_AWS_ACCESS_KEY_ID
   aws_secret_access_key = YOUR_AWS_SECRET_ACCESS_KEY
   ```
5. Mở porject theo đường dẫn [xem hình](./images/project-directory.png)
6. Cấu hình SDK [hướng dẫn](https://www.jetbrains.com/help/idea/sdk.html#set-up-jdk)
7. Mở tệp [src/main/java/com/mycompany/app/App.java](./src/main/java/com/mycompany/app/App.java) -> chạy để test các bucket
8. Mở tệp [src/main/java/aws/example/s3/PutObject.java](./src/main/java/aws/example/s3/PutObject.java) -> chạy để test push object

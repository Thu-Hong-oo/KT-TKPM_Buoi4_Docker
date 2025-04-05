### Bài 1: Tạo Dockerfile chạy một ứng dụng Node.js đơn giản	
	Yêu cầu:
	Viết Dockerfile để chạy một ứng dụng Node.js hiển thị "Hello, Docker!" trên cổng 3000.
	Sử dụng node:18 làm base image.

![image](https://github.com/user-attachments/assets/42573e71-1510-4f84-9ce0-4d1bb6dada27)
***
### Bài 2: Tạo Dockerfile chạy một ứng dụng Python Flask	
	Yêu cầu:
	Viết Dockerfile để chạy một ứng dụng Flask hiển thị "Hello, Docker Flask!" trên cổng 5000.
	Sử dụng python:3.9 làm base image.
 ![image](https://github.com/user-attachments/assets/53ad0344-b04a-4875-ba05-531243ac7bc1)

***
			
### Bài 3: Tạo Dockerfile chạy một ứng dụng React		
	Yêu cầu:	
	Viết Dockerfile để build và chạy một ứng dụng React.	
	sử dụng node:18-alpine làm base image.	
 ![image](https://github.com/user-attachments/assets/8f02735d-5427-46de-9dca-aa5259fa1be8)

***
### Bài 4: Tạo Dockerfile chạy một trang web tĩnh bằng Nginx	
	Yêu cầu:
	Tạo một file index.html đơn giản và sử dụng nginx:latest để phục vụ trang web.
	
### Bài 5: Tạo Dockerfile cho ứng dụng Go	
	Yêu cầu:
	Viết Dockerfile để build và chạy một ứng dụng Go đơn giản.
	
### Bài 6: Sử dụng Multi-stage Build trong Dockerfile	
	Viết Dockerfile để build một ứng dụng Node.js với hai stage:
	Stage 1: Dùng node:18 để build code.
	Stage 2: Dùng node:18-alpine để chạy ứng dụng đã build.
	
### Bài 7: Sử dụng biến môi trường trong Dockerfile	
	Yêu cầu:
	Viết Dockerfile cho ứng dụng Python đọc biến môi trường APP_ENV và in ra màn hình.
	Sử dụng ENV APP_ENV=development trong Dockerfile.
	
### Bài 8: Tạo Dockerfile cho PostgreSQL tùy chỉnh	
	Yêu cầu:
	Viết Dockerfile để chạy PostgreSQL (postgres:15).
	Thêm file SQL để tự động tạo database khi container chạy lần đầu tiên.
	
### Bài 9: Tạo Dockerfile chạy Redis với cấu hình tùy chỉnh	
	Yêu cầu:
	Viết Dockerfile sử dụng redis:latest.
	Thêm file redis.conf vào container.
	
### Bài 10: Chạy ứng dụng PHP với Apache	
	Yêu cầu:
	Viết Dockerfile để chạy một ứng dụng PHP đơn giản (php:8.2-apache).
	Mount mã nguồn từ máy host vào container.
	

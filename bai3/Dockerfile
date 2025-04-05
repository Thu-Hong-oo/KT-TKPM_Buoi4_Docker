# Sử dụng Node.js 18 Alpine làm base image
FROM node:18-alpine

# Đặt thư mục làm việc trong container
WORKDIR /app

# Sao chép package.json và package-lock.json vào container
COPY package*.json ./

# Cài đặt các dependencies
RUN npm install

# Sao chép toàn bộ mã nguồn ứng dụng vào container
COPY . .

# Build ứng dụng React (tạo build folder)
RUN npm run build

# Cài đặt Nginx để phục vụ các file build
FROM nginx:alpine

# Sao chép folder build từ container đầu tiên vào container Nginx
COPY --from=0 /app/build /usr/share/nginx/html

# Mở cổng 80 để phục vụ ứng dụng React
EXPOSE 80

# Chạy Nginx
CMD ["nginx", "-g", "daemon off;"]

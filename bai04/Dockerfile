# Sử dụng Node.js chính thức
FROM node:18

# Tạo thư mục làm việc
WORKDIR /app

# Copy file cấu hình và cài đặt dependencies
COPY package*.json ./
RUN npm install

# Copy toàn bộ mã nguồn vào container
COPY . .

# Mở cổng cho ứng dụng
EXPOSE 3000

# Lệnh khởi chạy ứng dụng
CMD ["npm", "start"]

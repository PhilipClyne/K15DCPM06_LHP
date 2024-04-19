- Set up trước khi khởi động web:
	+ cài đặt MongoDB extension trên VS code
	+ kết nối connection "mongodb://127.0.0.1:27017/lrisstore" trong MongoDB
- Cài đặt các module/thư viện thêm:
	+ gõ lệnh trên terminal: npm i bcryptjs concurrently cookie-parser cors dotenv Express express-async-handler express-formidable jsonwebtoken mongoose multer nodemon
	+ gõ lệnh: cd frontend
	+ gõ lệnh: npm i slick-carousel  react-slick  react-toastify  react-router  react-router-dom  react-redux  react-icons apexcharts  react-apexcharts  moment  flowbite  axios @reduxjs/toolkit  @paypal/react-paypal-js
- cách khởi động web:
	+ backend: npm run backend
	+ frontend: npm run frontend
- Cách tạo account có quyền admin: 
	+ bấm vào register tạo một account bất kì
	+ vào Mongodb trong VS code, Database lrisstore, collection users, mục Document, thay đổi  "isAdmin": false thành  "isAdmin": true
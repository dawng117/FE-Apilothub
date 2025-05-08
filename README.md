# Dự án VIetnam Is Awesome - TeamFrontEnd
Dự án frontend cho **Vietnam Is Awesome**, được xây dựng bằng **Vue 3**, **Vite** và **Tailwind CSS**.
## Tổng quan dự án
- Đây là dự án đầu tiên trong kỳ thực tập của mình tại **Apilothub**, với vai trò **Frontend Developer**. 
- Dự án hướng đến việc xây dựng một giao diện hiện đại, có cấu trúc rõ ràng, dễ mở rộng và dễ bảo trì, nhằm giới thiệu vẻ đẹp của các điểm đến và các sự kiện kết nối tại Việt Nam.
- Công nghệ sử dụng: Vue 3, Vite, Tailwind CSS, JavaScript.
## Cấu trúc thư mục
```bash
src/
├── assets/         # Tệp tĩnh (hình ảnh, biểu tượng)
├── components/     # Các component Vue tái sử dụng
├── pages/          # Các trang chính tương ứng với route
├── router/         # Cấu hình định tuyến Vue Router
├── store/          # Pinia/Vuex (nếu sử dụng)
├── services/       # Logic gọi API (axios, fetch,...)
├── App.vue         # Component gốc
├── main.js         # Điểm bắt đầu ứng dụng
├── index.css       # Cấu hình Tailwind và style toàn cục
```

## Getting Started
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/FE-Apilothub.git
cd FE-Apilothub
npm install
npm run dev

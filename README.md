# 🏢 Blue Moon Apartment Management System - Frontend

Phần Frontend của hệ thống quản lý chung cư Blue Moon được xây dựng bằng Next.js 14 và TypeScript.

## 🚀 Công nghệ sử dụng

- **Next.js 14** - React Framework
- **TypeScript** - Ngôn ngữ lập trình
- **Tailwind CSS** - Framework CSS
- **Shadcn/ui** - Component library
- **React Context** - State management
- **Axios** - HTTP Client
- **React Query** - Data fetching
- **Chart.js** - Data visualization

## 📦 Cài đặt và chạy dự án

### Yêu cầu hệ thống
- Node.js (v18+)
- npm hoặc yarn

### Các bước cài đặt

1. Clone repository và di chuyển vào thư mục frontend
```bash
cd FE-Next.js
```

2. Cài đặt dependencies
```bash
npm install
```

3. Tạo file môi trường
Tạo file `.env.local` trong thư mục gốc:
```env
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

4. Chạy ứng dụng ở môi trường development
```bash
npm run dev
```

Ứng dụng sẽ chạy tại [http://localhost:3000](http://localhost:3000)

## 📁 Cấu trúc thư mục

```
FE-Next.js/
├── src/
│   ├── app/              # App router và pages
│   ├── components/       # React components
│   │   ├── ui/          # UI components (shadcn/ui)
│   │   ├── panel/       # Panel components
│   │   └── Sidebar/     # Sidebar components
│   ├── context/         # React Context providers
│   ├── lib/             # Utility functions và ta1
```

### ⚠️ Lưu ý quan trọng
- Luôn luôn `git pull` trước khi code
- Xử lý cẩn thận conflict
- Khi cần merge vào main thì sẽ trao đổi với team

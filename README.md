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
│   ├── lib/             # Utility functions và configurations
│   └── middleware/      # Next.js middleware
├── public/              # Static files
├── .gitignore          # Git ignore rules
├── components.json     # Shadcn/ui configuration
├── next.config.ts      # Next.js configuration
├── package.json        # Dependencies và scripts
├── postcss.config.mjs  # PostCSS configuration
├── tailwind.config.ts  # Tailwind CSS configuration
└── tsconfig.json       # TypeScript configuration
```

## 🎨 Components

### Core Components
- `Header.tsx` - Header chính của ứng dụng
- `Footer.tsx` - Footer của ứng dụng
- `Sidebar.tsx` - Sidebar navigation
- `Loader.tsx` - Loading component
- `Message.tsx` - Message/Notification component
- `FormContainer.tsx` - Container cho các form

### Authentication Components
- `PrivateRoute.tsx` - Route protection
- `RoleRoute.tsx` - Role-based access control

### UI Components (shadcn/ui)
- Button
- Card
- Dialog
- Dropdown Menu
- Form
- Input
- Select
- Table
- Tabs
- Toast

### Panel Components
- Dashboard panels
- Statistics panels
- Payment panels
- User management panels

## 🔒 Authentication & Authorization

- JWT-based authentication
- Role-based access control (RBAC)
- Protected routes
- Session management

## 📱 Responsive Design

- Mobile-first approach
- Responsive layouts
- Adaptive components
- Breakpoint-based design

## 🎯 Development Scripts

```bash
npm run dev        # Chạy development server
npm run build      # Build production
npm run start      # Chạy production server
npm run lint       # Kiểm tra lỗi
npm run format     # Format code
```

## 🔧 Cấu hình

### Tailwind CSS
- Custom colors
- Custom breakpoints
- Custom animations
- Dark mode support

### Next.js
- App Router
- API Routes
- Middleware
- Environment variables

### TypeScript
- Strict mode
- Path aliases
- Type definitions
- ESLint configuration

## 🤝 Contributing

### Quy trình đóng góp

1. Clone project
```bash
git clone https://github.com/KyThuatPhanMemQuanlyChungCuBlueMoon/FE-Next.js.git
```

2. Tạo feature branch
```bash
git checkout -b feature/ta1
```

3. Add local repo
```bash
git add .
```

4. Commit changes theo format:
```bash
git commit -m "[type]: message"
```

Trong đó:
- **type**: Loại thay đổi
  - `create`: Tạo mới tính năng/file
  - `add`: Thêm code/tính năng vào file có sẵn
  - `update`: Cập nhật tính năng
  - `fix`: Sửa lỗi
  - `refactor`: Tối ưu code
  - `remove`: Xóa code/tính năng
- **message**: Mô tả ngắn gọn về thay đổi (tiếng Anh hoặc Việt)

Ví dụ:
```bash
git commit -m "[create]: Add login page"
git commit -m "[fix]: Sửa lỗi validate form đăng ký"
git commit -m "[update]: Thêm loading state cho button"
```

5. Push to branch
```bash
git push origin feature/ta1
```

### ⚠️ Lưu ý quan trọng
- Luôn luôn `git pull` trước khi code
- Xử lý cẩn thận conflict
- Khi cần merge vào main thì sẽ trao đổi với team

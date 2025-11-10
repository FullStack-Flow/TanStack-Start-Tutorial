# TanStack Start Basic Example

A comprehensive example application demonstrating the features and capabilities of TanStack Start, a type-safe, client-first, full-stack React framework.

[Full Video Tutorial From YouTube](https://youtu.be/WYbZlIf9_Ok?si=jBtwOK1jWvS-ESZA)

## 🚀 Overview

This project showcases a modern full-stack React application built with TanStack Start, featuring:

- **Type-safe routing** with TanStack Router
- **Server-side rendering (SSR)** capabilities
- **Authentication system** with protected routes
- **Data fetching** with TanStack Query
- **File upload functionality**
- **Error handling** and boundary components
- **Streaming** and **deferred** data loading
- **Infinite scrolling** with pagination
- **Form handling** and validation
- **Modern UI** with Tailwind CSS

## 📋 Prerequisites

- Node.js (version 18 or higher)
- npm or pnpm package manager
- Git

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/FullStack-Flow/TanStack-Start-Tutorial.git
cd TanStack-Start-Tutorial
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

## 🏃‍♂️ Development

Start the development server:

```bash
npm run dev
# or
pnpm dev
```

The application will be available at `http://localhost:3000`

## 📦 Build

Build the application for production:

```bash
npm run build
# or
pnpm build
```

## 🚀 Production

Start the production server:

```bash
npm start
# or
pnpm start
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # UI component library
│   ├── DefaultCatchBoundary.tsx  # Global error boundary
│   ├── NotFound.tsx    # 404 page component
│   ├── auth-header.tsx # Authentication header
│   └── protected.tsx   # Protected route wrapper
├── routes/             # File-based routing
│   ├── __root.tsx      # Root layout and navigation
│   ├── index.tsx       # Home page
│   ├── dashboard.tsx   # Dashboard with nested routes
│   ├── dashboard.*.tsx # Dashboard sub-pages
│   ├── posts/          # Posts-related routes
│   ├── users/          # Users-related routes
│   ├── api/            # API routes
│   └── *.tsx           # Feature-specific routes
├── utils/              # Utility functions and server code
│   ├── auth-*.ts       # Authentication logic
│   ├── *.server.ts     # Server-side utilities
│   └── middleware.ts   # Custom middleware
├── styles/             # Global styles
└── router.tsx          # Router configuration
```

## 🎯 Features Demonstrated

### 🔐 Authentication
- Login system with form validation
- Protected routes requiring authentication
- User context management
- Auth header component

### 📊 Dashboard
- Multi-level navigation
- Protected dashboard area
- Profile and settings pages
- Nested routing structure

### 📝 Posts Management
- Post listing with infinite scroll
- Individual post pages
- Deep nested routing
- Server-side data fetching

### 👥 Users Management
- User listing
- User detail pages
- User editing functionality
- Form handling and validation

### 🔄 Advanced Features
- **File Upload**: Drag-and-drop file upload with progress
- **Streaming**: Real-time data streaming
- **Deferred Loading**: Progressive data loading
- **Parallel Routes**: Multiple routes rendering simultaneously
- **Error Handling**: Comprehensive error boundaries
- **SSR**: Server-side rendering for improved performance

### 🔧 Technical Features
- TypeScript for type safety
- Tailwind CSS for styling
- TanStack Query for data management
- TanStack Router for routing
- Vite for build tooling
- Modern ES modules

## 🔗 API Routes

The application includes several API endpoints:

- `/api/users` - User management
- `/api/users/:id` - Individual user operations

## 🎨 Styling

The project uses Tailwind CSS for styling with:
- Responsive design
- Modern color palette
- Consistent spacing and typography
- Dark mode support (ready)

## 🐛 Error Handling

Comprehensive error handling with:
- Global error boundaries
- Route-specific error components
- 404 page handling
- User-friendly error messages

## 📱 Responsive Design

The application is fully responsive and works across:
- Desktop computers
- Tablets
- Mobile devices

## 🔧 Configuration

Key configuration files:
- `vite.config.ts` - Vite build configuration
- `tsconfig.json` - TypeScript configuration
- `postcss.config.mjs` - PostCSS configuration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions:
- Check the [TanStack documentation](https://tanstack.com/)
- Visit the [TanStack Router docs](https://tanstack.com/router)
- Review the example code in this repository

## 🎉 Acknowledgments

- Built with [TanStack Start](https://tanstack.com/start)
- Powered by [TanStack Router](https://tanstack.com/router)
- Styled with [Tailwind CSS](https://tailwindcss.com)
- Developed with [Vite](https://vitejs.dev)

---

**Happy coding!** 🚀

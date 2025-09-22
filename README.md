# EPUL - Electronic Public Library Management System

A comprehensive library management solution built with React, TypeScript, and Supabase. Features book tracking, ebook support, QR code integration, and user management.

## 🌟 Features

- 📚 **Book Management**: Add, edit, and track physical books
- 📖 **E-book Support**: Upload and manage digital books
- 🔍 **QR Code Integration**: Quick book lookup with QR codes
- 👥 **User Management**: Multi-user system with authentication
- 📊 **Dashboard**: Overview of library statistics
- 📈 **Transaction Tracking**: Borrow/return history
- 🌍 **Multi-language**: English and Kurdish support
- 📱 **Responsive Design**: Works on all devices

## 🚀 Live Demo

[https://diwan1993.github.io/EPUL/](https://diwan1993.github.io/EPUL/)

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Vite
- **Styling**: Tailwind CSS, Framer Motion
- **Backend**: Supabase (PostgreSQL, Auth, Storage)
- **Deployment**: GitHub Pages
- **Icons**: Lucide React

## 📋 Prerequisites

- Node.js 18+
- npm or yarn
- Supabase account

## 🔧 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/diwan1993/EPUL.git
   cd EPUL
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` with your Supabase credentials.

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 🚀 Deployment

The project is automatically deployed to GitHub Pages when you push to the `main` branch.

### Manual Deployment

```bash
npm run deploy
```

## 📁 Project Structure

```
EPUL/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/         # Main application pages
│   ├── services/      # API services (Supabase)
│   ├── contexts/      # React contexts (Auth, Language)
│   ├── types/         # TypeScript type definitions
│   └── utils/         # Utility functions
├── supabase/
│   └── migrations/    # Database schema migrations
├── .github/
│   └── workflows/     # GitHub Actions deployment
└── public/           # Static assets
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Diwan** - [GitHub](https://github.com/diwan1993)

## 🙏 Acknowledgments

- Supabase for the amazing backend-as-a-service
- React community for the excellent framework
- All contributors and users
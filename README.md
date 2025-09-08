# NADA-V2 🏃‍♂️

**National Anti-Doping Analytics Dashboard - Version 2**

A comprehensive anti-doping management system developed for SIH 2024 at NIT Karnataka. This platform provides advanced analytics, case management, and investigative tools for anti-doping agencies.

## 🚀 Overview

NADA-V2 is a multi-module web application designed to combat doping in sports through:
- **Real-time Analytics**: Performance monitoring and anomaly detection
- **Case Management**: Comprehensive investigation tracking system
- **AI-Powered Risk Assessment**: Machine learning models for doping risk evaluation
- **Multi-role Access**: Admin, Analyst, and Investigator interfaces

## 🏗️ Architecture

The application follows a microservices architecture with separate modules:

```
NADA-V2/
├── 🏠 landingPage/     # Landing page and public interface
├── 👨‍💼 admin/          # Admin dashboard (Next.js)
├── 📊 analyst/         # Analyst interface (React)
├── 🔍 invest/          # Investigator portal (Next.js)
├── 🖥️ server/          # Backend API (Node.js/Express)
└── 🤖 model/           # ML models (Python/Flask)
```

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** - Modern React framework with SSR
- **React 18/19** - Component-based UI library
- **Tailwind CSS** - Utility-first CSS framework
- **Material-UI** - React component library
- **Recharts** - Data visualization library
- **Lucide React** - Icon library

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication and authorization
- **Multer** - File upload handling

### Machine Learning
- **Python** - Core language
- **Flask** - Lightweight web framework
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization

## 🚀 Quick Start

### Prerequisites
- Node.js (v18+)
- Python (v3.8+)
- MongoDB
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Awesome-SSP/NADA-V2.git
   cd NADA-V2
   ```

2. **Set up the Backend**
   ```bash
   cd server
   npm install
   npm start
   ```

3. **Set up the Admin Dashboard**
   ```bash
   cd admin
   npm install
   npm run dev
   ```

4. **Set up the Analyst Interface**
   ```bash
   cd analyst
   npm install
   npm start
   ```

5. **Set up the Investigator Portal**
   ```bash
   cd invest
   npm install
   npm run dev
   ```

6. **Set up the ML Model**
   ```bash
   cd model
   pip install -r requirements.txt
   python latest_model.py
   ```

### Default Ports
- **Landing Page**: http://localhost:3000
- **Admin Dashboard**: http://localhost:4000
- **Analyst Interface**: http://localhost:4001
- **Investigator Portal**: http://localhost:3002
- **Backend API**: http://localhost:5000
- **ML Model API**: http://localhost:5001

## 📋 Features

### 🏆 Admin Dashboard
- Real-time analytics and KPIs
- Athlete registration management
- Case overview and statistics
- System-wide monitoring

### 📊 Analyst Interface
- Performance data analysis
- Anomaly detection algorithms
- Risk assessment reports
- Data visualization tools

### 🔍 Investigator Portal
- Case management system
- Evidence documentation
- Report generation
- File upload capabilities

### 🤖 AI/ML Components
- Performance improvement tracking
- Doping risk scoring
- Biomarker analysis
- Predictive modeling

## 🔧 Development

### Environment Variables
Create `.env` files in respective directories:

**Server (.env)**
```env
MONGODB_URI=mongodb://localhost:27017/nada
JWT_SECRET=your_jwt_secret
PORT=5000
```

### Scripts
```bash
# Development
npm run dev          # Start development server
npm start           # Start production server
npm run build       # Build for production

# Testing
npm test            # Run tests
npm run lint        # Run ESLint
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 API Documentation

### Authentication Endpoints
- `POST /api/auth/login` - User login
- `POST /api/auth/register` - User registration
- `GET /api/auth/profile` - Get user profile

### Data Endpoints
- `GET /api/athletes` - Get athlete data
- `POST /api/cases` - Create new case
- `GET /api/analytics` - Get analytics data

## 🚧 Development Status

**Current Status**: Under Active Development

### ✅ Completed
- [x] Basic project structure
- [x] Authentication system
- [x] Admin dashboard UI
- [x] Analyst interface
- [x] ML model integration

### 🚧 In Progress
- [ ] File upload functionality
- [ ] Advanced analytics features
- [ ] Case management workflows
- [ ] Report generation system

### 📋 Planned
- [ ] Mobile application
- [ ] Advanced AI models
- [ ] Real-time notifications
- [ ] Data export features

## 📞 Support

For questions and support:
- **Project Lead**: Saurabh Parmar
- **Institution**: NIT Karnataka
- **Event**: Smart India Hackathon 2024

## 📜 License

This project is developed for Smart India Hackathon 2024. All rights reserved.

---
## Support

For support, you can buy me a coffee

<a href="https://buymeacoffee.com/i.awesomessp" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

**Built with ❤️ for the fight against doping in sports** 🏃‍♂️⚡

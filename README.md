# 🎯 Insider Hub Project

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://sharankumarp.github.io/insider-hub-project)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-green)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A comprehensive full-stack web application designed to enhance team collaboration and employee appreciation within organizations. Built as a **BITS College Final Year Project** by **Sharankumar P**.

## 🌟 Live Demo

**[📖 View Documentation](https://sharankumarp.github.io/insider-hub-project)**

## 📋 Project Overview

Insider Hub is a modern web application that facilitates team appreciation and collaboration through:

- **User Authentication & Authorization** with JWT
- **Appreciation System** for recognizing team members
- **Profile Management** with statistics and rankings
- **Real-time Updates** and notifications
- **Admin Panel** for user management
- **Email Integration** for automated notifications

## 🛠️ Technology Stack

### Frontend
- **React** - UI Library
- **Vite** - Build Tool & Development Server
- **Tailwind CSS** - Utility-First CSS Framework
- **JavaScript** - Programming Language
- **Axios** - HTTP Client with Interceptors

### Backend
- **Node.js** - Runtime Environment
- **Express.js** - Web Application Framework
- **JWT** - JSON Web Token Authentication
- **Database** - Data Storage & Management
- **Email Service** - Automated Notifications
- **Middleware** - Security & Validation Layer

## 🚀 Features

### Core Functionality
- **🔐 Secure Authentication** - SAPID-based login with JWT tokens
- **👥 User Registration** - Admin-approved user onboarding
- **💬 Appreciation Posts** - Send and receive team appreciation
- **👍 Like System** - Engage with appreciation posts
- **🔍 Search & Filter** - Find specific content easily
- **📊 Profile Dashboard** - Personal statistics and rankings
- **📧 Email Notifications** - Automated admin alerts

### Security Features
- **🛡️ Password Encryption** - Bcrypt hashing
- **🔑 JWT Authentication** - Stateless token-based auth
- **👨‍💼 Role-Based Access** - User and admin permissions
- **🔒 Session Management** - Automatic token expiry
- **✅ Input Validation** - Client and server-side validation

## 📱 User Interface

### Landing Page
- **Login Button** → Routes to `/login`
- **Request Access Button** → Routes to `/requestuser`

### Main Dashboard (Post-Login)
- **View Happenings** - Browse all appreciation messages
- **Appreciate** - Send appreciation to team members  
- **Profile** - Manage personal profile and view stats
- **About** - Project information
- **Logout** - Secure session termination

## 🔗 API Endpoints

### Authentication
- `POST /api/auth/login` - User login
- `POST /newUser` - User registration request
- `GET /logoutuser` - Session termination

### Core Features
- `GET /happenings` - Retrieve appreciation posts
- `POST /userappreciate` - Submit appreciation
- `POST /postlike` - Like appreciation post
- `GET /userprofile` - User profile data

## 📖 Documentation Structure

```
📚 Documentation/
├── 🏠 Home (index.html)
├── ⚛️ Frontend Documentation
│   ├── React Application Structure
│   ├── Component Architecture
│   ├── API Integration
│   └── UI/UX Design
├── 🖥️ Backend Documentation
│   ├── Authentication Flow
│   ├── Email Configuration
│   ├── User Access Provisioning
│   ├── Profile Dashboard
│   ├── Appreciation System
│   ├── Like Functionality
│   └── Login/Signup Process
└── 🔄 Frontend ↔ Backend Logic
    ├── API Configuration
    ├── Axios Interceptors
    ├── Authentication Flow
    └── Error Handling
```

## 🎨 Design Features

- **📱 Responsive Design** - Mobile-first approach
- **🎨 Modern UI** - Clean, professional interface
- **🌈 Consistent Theming** - Unified color scheme
- **⚡ Fast Loading** - Optimized performance
- **♿ Accessible** - WCAG compliance
- **🔄 Smooth Animations** - Enhanced user experience

## 🛡️ Security Implementation

### Frontend Security
- **🔒 Protected Routes** - Authentication-based routing
- **🔑 Token Management** - Secure token storage and handling
- **✅ Input Validation** - Client-side validation
- **🚫 XSS Prevention** - Content sanitization

### Backend Security  
- **🔐 JWT Authentication** - Secure token-based auth
- **🛡️ Password Hashing** - Bcrypt encryption
- **🚪 CORS Configuration** - Cross-origin protection
- **📝 Request Logging** - Comprehensive audit trail
- **⚡ Rate Limiting** - API abuse prevention

## 📞 Contact Information

**Developer:** Sharankumar P  
**Email:** [sharanclouddev@gmail.com](mailto:sharanclouddev@gmail.com)  
**Portfolio:** [sharankumarg3.netlify.app](https://sharankumarg3.netlify.app)  
**Institution:** BITS College  
**Project Type:** Final Year Project - 2024  

## 🎓 Academic Context

This project represents a comprehensive demonstration of modern web development practices, including:

- **Full-Stack Development** - Frontend and backend integration
- **Security Implementation** - Authentication and authorization
- **Database Design** - Relational data modeling
- **API Development** - RESTful service architecture
- **UI/UX Design** - User-centered design principles
- **Documentation** - Comprehensive technical documentation

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **BITS College** - Academic support and guidance
- **React Community** - Frontend framework and ecosystem
- **Node.js Community** - Backend runtime and packages
- **Open Source Contributors** - Third-party libraries and tools

---

**🎯 Insider Hub Project** - Enhancing team collaboration through appreciation and recognition.

*Built with ❤️ by [Sharankumar P](https://sharankumarg3.netlify.app)*

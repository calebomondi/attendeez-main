# ATTENDEEZ: Automated Class Attendance Sign In Using QR Codes

![Project Showcase](https://github.com/user-attachments/assets/d87380e2-4a1b-4e4a-a334-8875036a4bed)

## 🎯 Project Overview

ATTENDEEZ is an innovative mobile application designed to streamline and automate the class attendance tracking process using QR code technology. By eliminating manual attendance marking, the app saves time for educators and provides a more efficient, accurate attendance management system.

## ✨ Key Features

- **QR Code-Based Attendance**: Generate unique QR codes for each class session
- **Real-Time Tracking**: Instant attendance recording and verification
- **User-Friendly Interface**: Simple, intuitive design for students and instructors
- **Comprehensive Reporting**: Generate detailed attendance reports and analytics
- **Cross-Platform Support**: Compatible with iOS and Android devices

## 🛠 Technologies Used

- **Frontend**: ReactJs with Vite
- **Backend**: Node.js, Express
- **Database**: supabase (Postegresql)
- **Authentication**: supabase
- **QR Code Generation**: qrcode.react
- **QR Code Scanning**: ZXing Library

## 📦 Prerequisites

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)
- Code editor
- Supabase

## 🚀 Installation & Setup

### Clone the Repository
```bash
git clone <repo_url>
cd cloned_repo
```

### Install Dependencies
```bash
npm install
```

### Add the Necessary Table Schema To Your Supabase
- **Tables** include Students, Teachers, Units, Amattending, ...

### Configure Environment
1. Create a `.env` file in the root directory for the attendeez and attendeez-tutor submodules
2. Add the following configuration:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Run the Application
```bash
npx run dev
```

## 🔐 User Roles

- **Students**: Genarate and Scan QR codes to mark attendance
- **Instructors**: Scans QR codes, view attendance reports
- **Administrators**: Manage user accounts, generate comprehensive reports

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

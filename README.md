# CarePulse - Healthcare Application

*Developed by Phạm Lê Ngọc Sơn*

## Overview

CarePulse is a comprehensive healthcare application designed to bridge the gap between patients and healthcare providers. It offers a modern, secure, and user-friendly platform for accessing medical services, managing health information, and utilizing wellness resources. The application aims to improve healthcare accessibility and patient outcomes through innovative technology.

## Project Structure

The project is built using Next.js 14 with TypeScript and follows a modern web application architecture:

```
healthcare-app/
├── app/                    # Next.js app directory (pages and routes)
│   ├── admin/              # Admin portal
│   ├── api/                # API routes
│   ├── patients/           # Patient management features
│   │   └── [userId]/       # User-specific patient data
│   ├── layout.tsx          # Root layout component
│   └── page.tsx            # Home page
├── components/             # Reusable UI components
│   ├── forms/              # Form components
│   ├── table/              # Table components
│   ├── ui/                 # UI primitives
│   └── *.tsx               # Other standalone components
├── constants/              # Application constants
├── lib/                    # Utility functions and shared logic
├── public/                 # Static assets
├── types/                  # TypeScript type definitions
└── ...                     # Configuration files
```

## Key Features

- **Patient Management**: Register, view, and manage patient information
- **Admin Dashboard**: Healthcare provider portal for managing appointments and medical records
- **Secure Authentication**: Protect sensitive medical data with robust authentication
- **Responsive UI**: Modern interface built with Tailwind CSS that works on all devices
- **Form Validation**: Comprehensive input validation using React Hook Form and Zod
- **Error Handling**: Integrated with Sentry for monitoring and error reporting
- **Accessibility**: Designed with accessibility in mind to serve all users

## Technology Stack

- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS, Radix UI components
- **Forms**: React Hook Form, Zod validation
- **Tables**: TanStack Table
- **Error Tracking**: Sentry
- **Authentication**: Custom implementation with secure protocols
- **API Integration**: RESTful endpoints

## Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/phamngocson/healthcare-app.git
   cd healthcare-app
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Run the development server
   ```
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```
npm run build
npm run start
```

## Usage Guide

### For Patients

1. Register an account or login
2. Complete your medical profile
3. Schedule appointments with healthcare providers
4. Access your medical records and test results
5. Receive reminders for medications and appointments

### For Healthcare Providers

1. Login to the admin portal
2. View and manage patient appointments
3. Update patient records
4. Access medical history and diagnostic information
5. Communicate with patients through the platform

## Deployment

The application can be deployed on platforms such as Vercel, Netlify, or any hosting service that supports Node.js applications.

## Contributing

Contributions to improve CarePulse are welcome. Please feel free to submit a pull request or open an issue to discuss potential improvements.

## License

This project is proprietary and owned by Phạm Lê Ngọc Sơn. All rights reserved.

---

© 2023 Phạm Lê Ngọc Sơn. All Rights Reserved.

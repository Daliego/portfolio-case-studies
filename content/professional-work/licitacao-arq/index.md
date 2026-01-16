---
title: "Licitação ARQ - Landing Page"
date: 2024-01-01
tags: ["full-stack", "typescript", "react", "firebase", "vite", "styled-components", "landing-page", "admin-panel"]
company: "Freelance Client"
description: "A professional landing page for an architecture/construction company with admin functionality, built with React.js and Firebase. This was my first paying job as a developer."
summary: "Full-stack landing page with admin panel for managing content and viewing client submissions, built with React.js, TypeScript, and Firebase."
cover:
  image: "main_image.png"
  alt: "Licitação ARQ Landing Page"
  relative: true
---

##### Project Overview

This is a landing page project that was my first paying job. While it's no longer in active use, I decided to share it here so that people can see a beginner project that was already profitable. It's built with React.js and demonstrates a complete full-stack landing page with admin functionality.

**Summary**: A professional landing page for an architecture/construction company with public-facing content and an admin panel for managing content and viewing client submissions.

##### Project Images

![](main_image.png)

##### Project Links

- **Live Demo:** [https://daliego.github.io/licitacao_landpage_project/](https://daliego.github.io/licitacao_landpage_project/)
- **Repository:** [GitHub](https://github.com/Daliego/licitacao_landpage_project)

##### Technology Stack

**Frontend:**
- React 18.2.0 - UI library
- TypeScript - Type safety
- Vite 5.0.8 - Build tool and dev server
- React Router DOM 6.21.3 - Client-side routing (HashRouter for GitHub Pages)
- Styled Components 6.1.8 - CSS-in-JS styling
- React Hook Form 7.49.3 - Form management
- Yup 1.3.3 - Schema validation
- React Hot Toast 2.4.1 - Toast notifications
- React Icons 5.0.1 - Icon library

**Backend & Services:**
- Firebase 10.8.0 - Backend as a Service
  - Firestore - Database
  - Authentication - User management
  - Storage - File storage
- Formspree - Contact form handling

**Development Tools:**
- ESLint - Code linting
- TypeScript ESLint - TypeScript-specific linting
- Puppeteer - Browser automation (testing)

##### Key Features

**Public Features:**
- Responsive landing page
- Contact form with validation
- FAQ section
- Product/service cards display
- WhatsApp integration
- Social media links

**Admin Features:**
- Protected admin routes
- Login authentication
- Card management (CRUD operations)
- Client submissions viewer
- Image upload for cards

##### Project Structure

The project follows a modular architecture with clear separation of concerns:

- **Modules**: Feature-based organization (adminPages, homePage, loginPage)
- **Shared Components**: Reusable UI components and utilities
- **Services**: API/service layer for Firebase integration
- **Contexts & Hooks**: Authentication and state management
- **Schemas**: Form validation schemas
- **Routes**: Client-side routing configuration

##### Firebase Integration

This project uses Firebase for:
- **Firestore Database** - Stores cards (product/service information) and client submissions
- **Authentication** - Admin login system
- **Storage** - Image storage for cards

##### Routes

- `/` - Home page (landing page)
- `/#/products` - Admin card management (protected)
- `/#/clients` - Admin client viewer (protected)

Note: Uses HashRouter for GitHub Pages compatibility.

##### Styling

The project uses **Styled Components** for styling with:
- Theme provider for consistent theming
- Global styles configuration
- Component-level styled components
- Responsive design patterns

##### Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions, with Firebase environment variables managed through GitHub Secrets.

##### Project Context

This was my first paid project as a developer. While the code may not follow all advanced best practices, it demonstrates a working, profitable application built with React and modern web technologies. The project showcases:

- Full-stack development capabilities
- Integration with Firebase services
- Admin panel functionality
- Responsive design implementation
- Form handling and validation
- Authentication and protected routes

##### Skills & Competencies

- React.js
- TypeScript
- Firebase (Firestore, Authentication, Storage)
- Styled Components
- React Router
- Form Management (React Hook Form)
- Schema Validation (Yup)
- Vite
- GitHub Pages Deployment
- GitHub Actions CI/CD

##### Project Status

**Note**: This project is no longer in active use but is shared here for educational purposes. It represents my first professional paid work as a developer and demonstrates a complete full-stack landing page application.

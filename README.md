# DaisyUI + Supabase Vue Mobile App Template

A mobile application template built with Vue 3, DaisyUI, Capacitor, and Supabase authentication. This template provides a ready-to-use mobile app structure with drawer navigation, authentication flows, and responsive UI components.

## Features

- 🔐 Authentication with Supabase (Sign In, Sign Up, Sign Out)
- 📱 Mobile-first design with Capacitor
- 🎨 UI Components with DaisyUI and TailwindCSS
- 📦 State management with Pinia
- 🗺️ Vue Router with protected routes
- 🔧 TypeScript support
- 📱 Drawer navigation system
- 💨 Hot Module Replacement (HMR) for fast development

## Prerequisites

- Node.js (v18 or later recommended)
- npm or yarn
- iOS development: Xcode (for iOS builds)
- Android development: Android Studio (for Android builds)

## Project Setup

1. Clone the repository
2. Install dependencies:

   ```shell
   npm install
   ```

3. Configure environment variables:

   - Copy .env.example to .env
   - Add your Supabase credentials:

     ```shell
     VITE_SUPABASE_URL=your-supabase-url
     VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
     ```

## Key Components

- DrawerComponent: Main navigation drawer
- NavbarComponent: Top navigation bar
- AuthStore: Supabase authentication management
- Protected Routes: Authentication-based route protection
- Mobile-responsive layouts

## Technologies

- Vue 3
- DaisyUI
- Capacitor
- Supabase
- Pinia
- TailwindCSS
- TypeScript

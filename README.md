<!-- @format -->

# Bowler Website

A comprehensive social networking and tournament management platform for the bowling community. This application connects professional and amateur bowlers, bowling centers, and equipment manufacturers through an intuitive interface.

## 🎯 Features

### For Players

- **Player Profiles** - Showcase bowling statistics, achievements, and performance metrics
- **Tournament Management** - Browse, register, and track bowling tournaments
- **Social Networking** - Follow players, share updates, and engage with the bowling community
- **Analytics Dashboard** - Track performance metrics, game scores, and improvement over time
- **Team Management** - Create and manage bowling teams

### For Administrators

- **User Management** - Manage amateur players, professional players, bowling centers, and manufacturers
- **Content Moderation** - Oversee news feeds and community communications
- **Subscription Management** - Handle premium memberships and transactions
- **Notifications System** - Send updates and announcements to users

### Additional Features

- **News Feed** - Stay updated with posts from bowling centers, manufacturers, and the network
- **Messaging** - Direct communication between users
- **Media Gallery** - Share and view bowling-related photos and videos
- **Payment Integration** - Secure payment processing for tournament registrations and subscriptions

## 🛠️ Tech Stack

- **Frontend Framework**: React 18.3
- **Build Tool**: Vite 6.3
- **Routing**: React Router DOM 7.6
- **Styling**:
  - Tailwind CSS 4.1
  - Bootstrap 5.3
  - Sass
- **UI Components**:
  - Radix UI primitives
  - shadcn/ui components
  - Lucide React icons
- **State Management**: TanStack Query (React Query)
- **Animations**: Framer Motion
- **Charts & Visualization**: Recharts
- **Form Handling**: React Dropzone, React Hot Toast

## 📋 Prerequisites

- Node.js 22.15.0 or higher
- npm or yarn package manager

## 🚀 Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/rahul3507/Bowler-website.git
cd Bowler-website
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## 📜 Available Scripts

- `npm run dev` - Start the development server with hot module replacement
- `npm run build` - Build the application for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## 📁 Project Structure

```
bowler-website/
├── public/              # Static assets
├── src/
│   ├── Admin/          # Admin dashboard components
│   ├── assets/         # Images and static resources
│   ├── components/     # Reusable UI components
│   │   └── ui/        # Base UI components (buttons, cards, inputs, etc.)
│   ├── layouts/       # Layout components
│   ├── lib/           # Utility functions
│   ├── Pages/         # Page components
│   │   ├── Analytics/
│   │   ├── Authentication/
│   │   ├── Dashboard/
│   │   ├── Homepage/
│   │   ├── Messages/
│   │   ├── MyTeams/
│   │   ├── Payment/
│   │   ├── Profile/
│   │   ├── SelectYourRole/
│   │   ├── SplashScreen/
│   │   └── Tournaments/
│   ├── Routers/       # Route configuration
│   ├── index.css      # Global styles
│   ├── main.jsx       # Application entry point
│   └── styles.scss    # Sass stylesheets
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

## 🎨 Key Pages & Components

### User Pages

- **Homepage** - Featured players, bowling centers, manufacturers, and news feed
- **Dashboard** - Personalized user dashboard with quick access to key features
- **Profile** - User profile with bowling statistics, media, privacy, and settings
- **Tournaments** - Tournament listings, details, and registration
- **My Teams** - Team creation and management
- **Analytics** - Performance tracking and statistics visualization
- **Messages** - Direct messaging interface

### Admin Pages

- **Admin Dashboard** - Overview of platform metrics
- **User Management** - Manage amateur players, pro players, bowling centers, and manufacturers
- **Subscriptions** - Manage premium memberships
- **Transactions** - Payment and transaction history
- **Notifications** - System-wide notifications management

## 🔧 Configuration

### Tailwind CSS

The project uses Tailwind CSS with custom color schemes defined in `tailwind.config.js`. Key custom colors include:

- `custom-gray`: #727272
- `custom-red`: #b32021

### Vite Configuration

Build settings and plugin configurations are available in `vite.config.js`.

## 🌐 Deployment

To build for production:

```bash
npm run build
```

The optimized production files will be in the `dist` directory, ready for deployment to any static hosting service (Vercel, Netlify, AWS S3, etc.).

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is proprietary and confidential.

## 👥 Authors

- Rahul - [@rahul3507](https://github.com/rahul3507)

## 🙏 Acknowledgments

- Built with React and Vite
- UI components from Radix UI and shadcn/ui
- Icons from Lucide React and React Icons
- Charts powered by Recharts

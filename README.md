# MOPi Production - Exhibition Design Website

A modern, responsive website for MOPi Production, specializing in exhibition booth design, event production, and custom structures.

## 🌟 Features

### Frontend
- **Modern React Application** built with Vite and TypeScript
- **Responsive Design** with Tailwind CSS
- **Multi-page Website** with smooth navigation
- **Dynamic Logo Management** with database integration
- **Professional Design System** with custom color palette

### Admin Dashboard
- **Complete Content Management System (CMS)**
- **User Management** with role-based access control
- **Media Library** with upload/edit/delete functionality
- **Logo Management** for header and footer logos
- **Portfolio Management** with featured projects
- **Activity Logging** for all admin actions
- **Design System Controls** for colors and typography

### Backend Integration
- **Supabase Backend** for database and authentication
- **Row Level Security (RLS)** for data protection
- **Real-time Updates** across all components
- **Secure File Storage** for media and logos

## 🎨 Design System

### Brand Colors
- **Primary Orange**: #F4A300
- **Secondary Black**: #000000
- **Dark Gray**: #2B2B2B
- **Background White**: #FFFFFF
- **Light Gray**: #F2F2F2

### Typography
- **Headings**: Poppins font family
- **Body Text**: Inter font family
- **Arabic Support**: Included for international use

## 🚀 Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **React Router** for navigation
- **Lucide React** for icons
- **Shadcn/ui** for UI components

### Backend
- **Supabase** for database and authentication
- **PostgreSQL** database with RLS policies
- **Real-time subscriptions** for live updates

### Development Tools
- **ESLint** for code linting
- **TypeScript** for type safety
- **PostCSS** for CSS processing

## 📁 Project Structure

```
mopi_production/
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── ui/             # Shadcn/ui components
│   │   ├── Navigation.tsx  # Main navigation component
│   │   └── LogoComponent.tsx # Dynamic logo component
│   ├── pages/              # Page components
│   │   ├── Index.tsx       # Homepage
│   │   ├── About.tsx       # About page
│   │   ├── Services.tsx    # Services page
│   │   ├── Portfolio.tsx   # Portfolio page
│   │   ├── Contact.tsx     # Contact page
│   │   └── AdminDashboard.tsx # Admin CMS
│   ├── integrations/       # Third-party integrations
│   │   └── supabase/       # Supabase client configuration
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions
│   └── index.css           # Global styles and design system
├── public/
│   ├── images/             # Static images and media
│   └── favicon.ico         # Site favicon
├── supabase/
│   ├── migrations/         # Database migration files
│   └── edge_function/      # Supabase Edge Functions
└── examples/               # Integration examples
    └── third-party-integrations/ # Third-party service examples
```

## 🗄️ Database Schema

### Core Tables
- **content_sections** - Website content management
- **portfolio_projects** - Portfolio project data
- **media_files** - Media library management
- **design_settings** - Design system configuration
- **seo_settings** - SEO metadata

### User Management
- **admin_users** - Admin user profiles
- **user_roles** - Role definitions and permissions
- **user_activity_logs** - Activity tracking
- **user_sessions** - Session management

### Logo Management
- **logo_settings** - Header and footer logo storage

## 🔧 Installation & Setup

### Prerequisites
- Node.js 18+ 
- npm or pnpm
- Supabase account

### Local Development
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### Environment Variables
Create a `.env` file with your Supabase credentials:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🎯 Key Features

### Homepage
- Hero section with dynamic content
- Services overview
- Featured portfolio projects
- Client testimonials
- Contact information

### Admin Dashboard
- **Content Management**: Edit hero, about, and other sections
- **Media Library**: Upload, organize, and manage images
- **Logo Control**: Upload and manage header/footer logos
- **Portfolio Management**: Add, edit, delete, and feature projects
- **User Management**: Create users, assign roles, track activity
- **Design System**: Customize colors and typography
- **Settings**: SEO configuration and general settings

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimized
- Touch-friendly interface
- Fast loading performance

## 🔐 Security Features

- **Row Level Security (RLS)** on all database tables
- **Role-based access control** for admin functions
- **Activity logging** for audit trails
- **Secure file uploads** with validation
- **Authentication required** for admin access

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

The website is optimized for deployment on:
- **Vercel** (recommended)
- **Netlify**
- **AWS Amplify**
- **Any static hosting service**

### Build Command
```bash
npm run build
```

### Output Directory
```
dist/
```

## 📞 Support

For technical support or questions about this project, please refer to the documentation or contact the development team.

## 📄 License

This project is proprietary software developed for MOPi Production.

---

**MOPi Production** - Creating exceptional exhibition experiences and memorable events that elevate your brand presence worldwide.
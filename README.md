# 🛍️ Currency VN - Premium Handcrafted Leather E-commerce Platform

<div align="center">

![Currency VN Logo](public/images/logo.png)

**A sophisticated e-commerce platform for premium handcrafted leather goods**

[![Next.js](https://img.shields.io/badge/Next.js-14.2.17-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.14-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)

[🌐 Live Demo](https://currencyvn.vercel.app) | [📧 Contact](mailto:zaikaman123@gmail.com) | [💼 LinkedIn](https://www.linkedin.com/in/%C4%91inh-ph%C3%BAc-th%E1%BB%8Bnh-2561b5274)

</div>

---

## 🎯 Project Overview

Currency VN is a premium e-commerce platform specializing in handcrafted leather goods. Built with modern web technologies, it showcases Vietnamese craftsmanship through an elegant, minimalist design that reflects the quality and sophistication of traditional leather artistry.

### ✨ Key Features

- **🛒 Complete E-commerce Functionality** - Full shopping cart, checkout, and order management
- **🤖 AI-Powered Customer Support** - Integrated Gemini AI chatbot for real-time assistance
- **🌙 Dark/Light Theme** - Responsive theme switching for optimal user experience
- **📱 Fully Responsive Design** - Seamless experience across all devices
- **🎨 Minimalist UI/UX** - Clean, professional design reflecting luxury craftsmanship
- **📰 Dynamic Content Management** - Rich journal/blog system for storytelling
- **🔍 Advanced Product Filtering** - Smart search and filtering capabilities
- **📧 Automated Email System** - Order confirmations and customer communications
- **⚡ Performance Optimized** - Fast loading with Next.js optimization
- **🎯 SEO Optimized** - Comprehensive meta tags and structured data

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 14.2.17 (App Router)
- **Language**: TypeScript 5.0.0
- **Styling**: TailwindCSS 3.4.14 + Custom CSS
- **UI Components**: Custom React components
- **Icons**: Heroicons, React Icons
- **Fonts**: Montserrat (Vietnamese support)

### Backend & APIs
- **API Routes**: Next.js API Routes
- **AI Integration**: Google Gemini AI
- **Email Service**: Nodemailer
- **Form Handling**: React Hook Form patterns

### Development Tools
- **Package Manager**: npm
- **Linting**: ESLint with Next.js config
- **Code Formatting**: Prettier (implied)
- **Version Control**: Git

### Deployment & Analytics
- **Hosting**: Vercel
- **Analytics**: Vercel Analytics & Speed Insights
- **Performance**: Built-in Next.js optimizations

---

## 📁 Project Structure

```
currency.vn/
├── 📁 public/
│   ├── 🖼️ images/          # Product images, journal photos
│   └── 📄 favicon.ico      # Site favicon
├── 📁 src/
│   ├── 📁 app/             # Next.js 14 App Router
│   │   ├── 🏠 page.tsx     # Homepage
│   │   ├── 🛍️ products/    # Product catalog
│   │   ├── 🛒 cart/        # Shopping cart
│   │   ├── 💳 checkout/    # Checkout process
│   │   ├── 📰 journal/     # Content management
│   │   ├── ℹ️ about/       # About page
│   │   └── 📞 contact/     # Contact information
│   ├── 📁 components/      # Reusable React components
│   │   ├── 🎨 ui/          # UI components
│   │   ├── 🛒 cart/        # Cart-specific components
│   │   ├── 💳 checkout/    # Checkout components
│   │   └── 🔧 layout/      # Layout components
│   ├── 📁 contexts/        # React Context providers
│   ├── 📁 hooks/           # Custom React hooks
│   ├── 📁 lib/             # Utility functions & configs
│   ├── 📁 types/           # TypeScript type definitions
│   └── 📁 data/            # Static data & content
├── 📄 package.json         # Dependencies & scripts
├── 📄 next.config.js       # Next.js configuration
├── 📄 tailwind.config.ts   # TailwindCSS configuration
└── 📄 tsconfig.json        # TypeScript configuration
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/zaikaman/currency.vn.git
   cd currency.vn
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   Configure your environment variables:
   ```env
   GOOGLE_GEMINI_API_KEY=your_gemini_api_key
   NEXT_PUBLIC_ANALYTICS_ID=your_analytics_id
   EMAIL_USER=your_email
   EMAIL_PASS=your_email_password
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

---

## 🎨 Design Philosophy

Currency VN embodies the principles of **minimalist design** and **premium craftsmanship**:

- **Minimalism**: Clean layouts, ample whitespace, and purposeful typography
- **Premium Feel**: Sophisticated color palette and high-quality imagery
- **User-Centric**: Intuitive navigation and seamless user experience
- **Responsive**: Mobile-first approach ensuring accessibility across all devices
- **Performance**: Optimized loading times and smooth interactions

---

## 🌟 Key Achievements

### 🏆 Technical Excellence
- ✅ **100% TypeScript Implementation** - Type-safe development
- ✅ **Modern React Patterns** - Hooks, Context API, and functional components
- ✅ **Responsive Design** - Mobile-first approach
- ✅ **SEO Optimization** - Comprehensive meta tags and structured data
- ✅ **Performance Optimization** - Image optimization, lazy loading
- ✅ **Accessibility** - WCAG guidelines compliance

### 🎯 Business Features
- ✅ **Complete E-commerce Flow** - From product browsing to order completion
- ✅ **AI Customer Support** - Intelligent chatbot integration
- ✅ **Content Management** - Rich storytelling through journal system
- ✅ **Multi-language Support** - Vietnamese localization
- ✅ **Theme Customization** - Dark/light mode switching

### 📊 Performance Metrics
- ⚡ **Fast Loading Times** - Optimized with Next.js
- 📱 **Mobile Responsive** - Seamless cross-device experience
- 🔍 **SEO Optimized** - Search engine friendly
- ♿ **Accessible Design** - Inclusive user experience

---

## 🤖 AI Integration

The platform features an intelligent customer support system powered by **Google Gemini AI**:

- **Real-time Assistance**: Instant responses to customer inquiries
- **Product Knowledge**: Deep understanding of Currency VN's offerings
- **Vietnamese Language Support**: Native language communication
- **Contextual Responses**: Tailored answers based on user context

---

## 📱 Features Showcase

### 🛍️ E-commerce Functionality
- **Product Catalog**: Elegant product grid with filtering and search
- **Shopping Cart**: Dynamic cart management with real-time updates
- **Checkout Process**: Streamlined, user-friendly checkout flow
- **Order Management**: Complete order tracking and confirmation

### 🎨 User Experience
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile
- **Theme Switching**: Dark/light mode for user preference
- **Loading States**: Smooth transitions and loading indicators
- **Error Handling**: Graceful error management with user feedback

### 📰 Content Management
- **Journal System**: Rich storytelling platform for brand narrative
- **Dynamic Routing**: SEO-friendly URLs for all content
- **Image Optimization**: Next.js Image component for optimal performance
- **Reading Experience**: Typography and layout optimized for readability

---

## 🔧 Development Highlights

### 🎯 Modern Development Practices
- **Component-Based Architecture**: Reusable, maintainable React components
- **Custom Hooks**: Encapsulated business logic and state management
- **Context API**: Efficient global state management
- **TypeScript**: Type safety and enhanced developer experience

### 🚀 Performance Optimizations
- **Next.js App Router**: Latest routing paradigm for optimal performance
- **Image Optimization**: Automatic image optimization and lazy loading
- **Code Splitting**: Automatic code splitting for faster page loads
- **Static Generation**: Pre-built pages for lightning-fast delivery

### 🎨 Styling Architecture
- **TailwindCSS**: Utility-first CSS framework
- **Custom Design System**: Consistent spacing, colors, and typography
- **Responsive Design**: Mobile-first, breakpoint-based layouts
- **Dark Mode**: System-preference aware theme switching

---

## 📧 Contact & Connect

<div align="center">

**Đinh Phúc Thịnh**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%C4%91inh-ph%C3%BAc-th%E1%BB%8Bnh-2561b5274)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zaikaman)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zaikaman123@gmail.com)

</div>

---

## 📄 License

This project is developed as a portfolio piece showcasing modern web development capabilities. All rights reserved.

---

## 🙏 Acknowledgments

- **Team**: Developed by a dedicated team of 10 students from Van Lang University
- **Inspiration**: Vietnamese traditional leather craftsmanship
- **Technology**: Built with modern web technologies and best practices
- **Community**: Thanks to the open-source community for the amazing tools and libraries

---

<div align="center">

**⭐ Star this repository if you found it interesting!**

Made with ❤️ by [Đinh Phúc Thịnh](https://github.com/zaikaman)

</div>
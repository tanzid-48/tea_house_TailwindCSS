# Tea House - Tailwind CSS Website

![Tea House Banner](./images/banner.png)

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live-Demo-orange?style=for-the-badge)](https://tanzid-48.github.io/tea_house_TailwindCSS/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/tanzid-48/tea_house_TailwindCSS)

</div>

---

## 📸 Preview

A modern, elegant tea house website built with HTML and Tailwind CSS. Features a clean, responsive design showcasing tea products, company values, customer testimonials, and latest news.

---

## 📋 Project Overview

Tea House is a beautifully designed website for a tea and botanical solutions supplier. Built entirely with HTML and Tailwind CSS utility classes, the site presents a premium tea brand with elegant styling and comprehensive product information.

## ✨ Features

- ✅ **Tailwind CSS Framework** - Utility-first CSS framework for rapid development
- ✅ **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- ✅ **No JavaScript** - Pure HTML and CSS implementation
- ✅ **Hero Section** - Compelling banner with call-to-action
- ✅ **Product Showcase** - Featured tea products with descriptions
- ✅ **About Section** - Company history and values
- ✅ **Client Testimonials** - Customer reviews and feedback
- ✅ **News & Events** - Latest updates and blog posts
- ✅ **Newsletter Subscription** - Email subscription form
- ✅ **Footer Navigation** - Comprehensive quick links and services

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)

- **HTML5** - Semantic markup structure
- **Tailwind CSS** - Utility-first CSS framework
- **CDN Tailwind** - No build process required
- **GitHub Pages** - Hosting and deployment

## 🍵 Featured Products

<div align="center">

| Milk Tea | Black Tea | Lemon Tea | Green Tea |
|:--------:|:---------:|:---------:|:---------:|
| ![Milk Tea](./images/tea-1.png) | ![Black Tea](./images/tea-2.png) | ![Lemon Tea](./images/tea-3.png) | ![Green Tea](./images/tea-4.png) |
| Creamer could be replaced by fresh milk | Creamer could be replaced by fresh milk | Creamer could be replaced by fresh milk | Creamer could be replaced by fresh milk |

**Premium Quality Tea Collection**

</div>

## 🎯 Key Sections

### 1. Hero Section

![Hero Section](./images/banner.png)

**"It's good tea time at The Tea House"**

*Tea and Botanical Solutions Supplier Give Optimum Satisfaction To Your Taste Buds.*

### 2. Featured Products Section

![Featured Products](./images/Group%208.png)

**"Our Featured Products"**

Four signature tea varieties with high-quality product images and descriptions.

### 3. About Section - "Great Tea, Freshly Presented"

<div align="center">

| ![Fresh 1](./images/fresh-1.png) | ![Fresh 2](./images/fresh-2.png) |
|:--------------------------------:|:--------------------------------:|

</div>

**Company Story:**
- **Gong Cha** origin and meaning
- Established in **2006**
- Taiwanese heritage
- Customer appreciation and unique service

**Key Features:**

| Feature | Description |
|---------|-------------|
| 🎨 **Unique Taste** | A Unique and different style from other teapots gives a luxurious and minimalist impression |
| ⭐ **Premium Quality** | Premium Quality that makes tea more elegant and more durable when you use it |

### 4. Client Testimonials - "Meet Our Super Clients"

**Customer Reviews:**

<div align="center">

| Client Name | Position | Review |
|-------------|----------|--------|
| Ilham Yuda | Businessman | "We are providing the best and suitable home insurance services for the people who are interested to treatment" |

**3 Satisfied Clients** | **"Show All" for More Reviews**

</div>

### 5. News & Events Section

<div align="center">

| News 1 | News 2 | News 3 |
|:------:|:------:|:------:|
| ![News 1](./images/news-1.png) | ![News 2](./images/news-2.png) | ![News 3](./images/news-3.png) |
| **Feb 05, 2026** | **Feb 05, 2026** | **Feb 05, 2026** |
| Collecting 8 points for discount | Collecting 8 points for discount | Collecting 8 points for discount |
| [Learn More →](#) | [Learn More →](#) | [Learn More →](#) |

</div>

### 6. Newsletter Section

![Newsletter](./images/cup.png)

**"Ready to get started?"**

Email subscription form with "Get started" button

### 7. Footer Navigation

**Quick Links:**
- Home
- About Us
- Insurance
- Privacy Policy

**Our Service:**
- Life Insurance
- Car Insurance
- Health Insurance
- House Insurance

**Help:**
- FAQs
- Contact Us

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Git installed on your machine
- Basic understanding of HTML and Tailwind CSS

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/tanzid-48/tea_house_TailwindCSS.git

# 2. Navigate to the project directory
cd tea_house_TailwindCSS

# 3. Open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

## 📁 Project Structure

```
tea_house_TailwindCSS/
│
├── images/
│   ├── banner.png
│   ├── Group 8.png
│   ├── tea-1.png
│   ├── tea-2.png
│   ├── tea-3.png
│   ├── tea-4.png
│   ├── fresh-1.png
│   ├── fresh-2.png
│   ├── news-1.png
│   ├── news-2.png
│   ├── news-3.png
│   └── cup.png
│
├── index.html
└── README.md
```

## 🎨 Tailwind CSS Implementation

This project uses **Tailwind CSS CDN** for styling:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

### Tailwind Utilities Used:

<div align="center">

| Category | Utilities |
|----------|-----------|
| **Layout** | Container, Grid, Flexbox |
| **Spacing** | Margin (m-*), Padding (p-*) |
| **Typography** | Font sizes, weights, text colors |
| **Colors** | Background colors, text colors, borders |
| **Responsive** | sm:, md:, lg:, xl: breakpoints |
| **Effects** | Hover states, transitions, shadows |

</div>

### Example Tailwind Classes:

```html
<!-- Responsive Grid Layout -->
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">

<!-- Gradient Background -->
<div class="bg-gradient-to-r from-[#FF8938] to-[#F00]">

<!-- Responsive Text Alignment -->
<h1 class="text-center lg:text-left text-4xl font-bold">

<!-- Spacing Utilities -->
<section class="px-4 py-8 md:px-16 lg:px-32">
```

## 📱 Responsive Design

Built with **mobile-first** approach using Tailwind breakpoints:

<div align="center">

| Breakpoint | Screen Size | Usage |
|------------|-------------|-------|
| Default | < 640px | Mobile phones |
| **sm:** | ≥ 640px | Small tablets |
| **md:** | ≥ 768px | Tablets |
| **lg:** | ≥ 1024px | Laptops |
| **xl:** | ≥ 1280px | Desktops |

</div>

## 🌟 Design Highlights

- **Color Scheme**: Warm orange gradients (#FF8938 to #F00), elegant neutrals
- **Typography**: Clear hierarchy with Tailwind font utilities
- **Spacing**: Consistent padding and margins throughout
- **Card Design**: Clean product and news cards with shadows
- **Gradient Buttons**: Eye-catching call-to-action buttons
- **Image Optimization**: High-quality tea and product images
- **Professional Layout**: Grid-based responsive design system

## 💡 Tailwind CSS Advantages

<div align="center">

| Advantage | Benefit |
|-----------|---------|
| ✅ **Rapid Development** | Pre-built utility classes speed up coding |
| ✅ **Consistent Design** | Built-in design system maintains consistency |
| ✅ **Responsive by Default** | Mobile-first utilities included |
| ✅ **No Custom CSS** | Everything done with utility classes |
| ✅ **Small File Size** | Only used utilities are included |
| ✅ **Easy Customization** | Simple to modify and extend |

</div>

## 🔧 Customization Guide

To customize this website:

### 1. Colors
```html
<!-- Change gradient colors -->
<div class="bg-gradient-to-r from-[#YourColor] to-[#YourColor]">
```

### 2. Content
Update text in `index.html`

### 3. Images
Replace images in `images/` folder

### 4. Layout
Adjust Tailwind grid and flex utilities:
```html
<div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4">
```

### 5. Typography
Change font size and weight:
```html
<h1 class="text-2xl md:text-4xl lg:text-6xl font-bold">
```

## 🌐 Browser Support

<div align="center">

| Browser | Support |
|---------|---------|
| Chrome | ✅ Latest |
| Firefox | ✅ Latest |
| Safari | ✅ Latest |
| Edge | ✅ Latest |
| Opera | ✅ Latest |

</div>

## 🚀 Deployment

Deployed using **GitHub Pages**:

1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select main branch as source
4. Save and wait for deployment
5. Site live at: `https://tanzid-48.github.io/tea_house_TailwindCSS/`

## 💡 Future Enhancements

Potential features to add:

- [ ] JavaScript for interactive elements
- [ ] Shopping cart functionality
- [ ] Product detail pages
- [ ] User authentication
- [ ] Search functionality
- [ ] Dark mode toggle
- [ ] Animation effects with Tailwind
- [ ] Multi-language support
- [ ] Customer account dashboard
- [ ] Payment integration

## 📊 Performance

- ✅ Lightweight and fast loading
- ✅ Optimized images
- ✅ Minimal CSS (Tailwind utilities)
- ✅ No JavaScript dependencies
- ✅ SEO-friendly structure

## 📖 Learning Resources

<div align="center">

[![Tailwind Docs](https://img.shields.io/badge/Tailwind-Documentation-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/docs)
[![Tailwind CDN](https://img.shields.io/badge/Tailwind-CDN-38B2AC?style=for-the-badge)](https://tailwindcss.com/docs/installation/play-cdn)
[![Tailwind UI](https://img.shields.io/badge/Tailwind-UI_Components-38B2AC?style=for-the-badge)](https://tailwindui.com/)

</div>

## 👤 Author

**Tanzid**
- GitHub: [@tanzid-48](https://github.com/tanzid-48)
- Project: [Tea House Tailwind CSS](https://github.com/tanzid-48/tea_house_TailwindCSS)

## 📝 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- **Tailwind CSS** - For the amazing utility-first framework
- Product images and graphics for demonstration
- Inspired by modern tea house websites
- Built following Tailwind CSS best practices
- Responsive design principles

## 📞 Support

For questions or issues, please open an issue in the GitHub repository.

---

<div align="center">

**© 2026 UIDesign.by Tanzid - All rights reserved**

**Made with 🍵 and Tailwind CSS**

⭐ Star this repo if you love tea and clean code!

</div>

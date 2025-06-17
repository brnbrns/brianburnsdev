# brianburns.dev

A clean, modern personal website showcasing professional experience and providing easy access to social profiles and resume.

## 🌐 Live Site

Visit the live site at: [brianburns.dev](https://brianburns.dev)

## ✨ Features

- **Minimalist Design**: Clean, dark-themed interface with subtle hover effects
- **Social Media Integration**: Quick access to LinkedIn, GitHub, and resume
- **Interactive Resume**: Web-based resume matching PDF version exactly
- **PDF Download**: One-click resume download functionality
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Modern Typography**: Custom web fonts for professional appearance
- **Fast Loading**: Lightweight design with optimized assets

## 🛠️ Tech Stack

- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with flexbox, gradients, and animations
- **Font Awesome**: Professional icons for social media and UI elements
- **Google Fonts**: Custom typography with Domine and Lato fonts

## 📁 Project Structure

```plaintext
brianburns.dev/
├── index.html          # Main landing page
├── resume.html         # Interactive web resume
├── resume.pdf          # Downloadable PDF resume
├── css/
│   ├── style.css       # Main stylesheet
│   ├── fa.min.css      # Font Awesome core styles
│   ├── brands.min.css  # Font Awesome brand icons
│   └── solid.min.css   # Font Awesome solid icons
├── webfonts/
│   ├── Domine-VariableFont_wght.ttf
│   ├── Lato-Regular.ttf
│   ├── fa-brands-400.ttf
│   ├── fa-brands-400.woff2
│   ├── fa-solid-900.ttf
│   └── fa-solid-900.woff2
└── README.md
```

## 🎨 Design Features

### Color Palette

- **Background**: `#1d1d1d` (Dark charcoal)
- **Primary Text**: `#ffffff` (White)
- **Accent Color**: `#87ceeb` (Sky blue)
- **Secondary Text**: `#ccc` (Light gray)

### Typography

- **Headers**: Domine (serif font for elegance)
- **Body Text**: Lato (clean readability)
- **Responsive sizing**: Scales appropriately across devices

### Interactive Elements

- **Circular Social Buttons**: Gradient backgrounds with hover animations
- **Smooth Transitions**: 0.3s ease transitions for all interactive elements
- **Hover Effects**: Subtle lift animations and color changes

## 🚀 Getting Started

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/brianburns.dev.git
   cd brianburns.dev
   ```

2. **Serve locally**

   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

### Customization

#### Update Personal Information

- **Social Links**: Edit links in `index.html` (lines 25-35)
- **Resume Content**: Modify `resume.html` with your experience
- **Contact Info**: Update header section in `resume.html`

#### Styling Changes

- **Colors**: Modify CSS custom properties in `css/style.css`
- **Fonts**: Replace font files in `webfonts/` directory
- **Layout**: Adjust flexbox properties and spacing

## 📱 Responsive Design

The site is fully responsive with breakpoints at:

- **Desktop**: > 768px
- **Tablet**: 768px and below
- **Mobile**: 700px and below

### Mobile Optimizations

- Larger touch targets for buttons
- Adjusted typography scaling
- Optimized spacing and layout
- Maintained readability and usability

## 🚀 Deployment

### GitHub Pages

1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)
4. Site will be available at `https://yourusername.github.io/repository-name`

### Custom Domain

1. Add `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

### Other Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **AWS S3/Azure Storage**: Static website hosting
- **Traditional Web Hosting**: Upload files via FTP

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

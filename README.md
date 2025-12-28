# Medha Sharma - Professional Teaching Portfolio

🎓 **Professional Teaching Portfolio Website** for Medha Sharma - CTET Qualified Educator

## 🚀 Live Website
**Coming Soon on Render** - https://medha-sharma-portfolio.onrender.com

## ✨ Features

- ✅ **Fully Responsive Design** (Mobile-First, 320px - 1920px+)
- ✅ **Modern Frontend** (HTML5, CSS3, Vanilla JavaScript)
- ✅ **Express.js Backend** (Node.js server, contact form API)
- ✅ **Professional Sections**:
  - Hero Landing with Profile
  - About Me & Personal Details
  - Core Teaching Competencies
  - Professional Experience Timeline
  - Educational Qualifications
  - Certifications & Achievements
  - Contact Form with Backend Integration
  - Dark/Light Theme Toggle
  - Smooth Animations & Transitions

## 📋 Project Structure

```
medha-sharma-portfolio/
├── server.js              # Express backend (contact form)
├── package.json           # Dependencies
├── render.yaml            # Render deployment config
├── .env.example           # Environment variables template
├── public/
│   ├── index.html        # Main portfolio page
│   ├── 404.html          # 404 error page
│   ├── css/
│   │   └── style.css     # Styling
│   ├── js/
│   │   └── script.js     # JavaScript interactivity
│   └── images/           # Images folder
└── README.md             # This file
```

## 🛠️ Technology Stack

**Frontend:**
- HTML5 (Semantic markup)
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)

**Backend:**
- Node.js
- Express.js
- Nodemailer (email integration)

**Deployment:**
- Render (Free tier)
- GitHub (Version control)
- HTTPS enabled (Let's Encrypt)

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14+)
- npm or yarn
- Git

### Local Development

```bash
# Clone repository
git clone https://github.com/us8024435-debug/medha-sharma-portfolio.git
cd medha-sharma-portfolio

# Install dependencies
npm install

# Create .env file
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev  # or npm start

# Server runs on http://localhost:3000
```

## 🚀 Deployment to Render

### Step 1: GitHub Repository Setup ✅
- Repository created: `us8024435-debug/medha-sharma-portfolio`
- All files committed
- render.yaml configured

### Step 2: Deploy to Render

1. **Connect to Render:**
   - Go to https://render.com
   - Sign in with GitHub
   - Select "medha-sharma-portfolio" repository

2. **Configuration:**
   - Service Type: Web Service
   - Environment: Node
   - Build Command: `npm install`
   - Start Command: `npm start`
   - Port: 3000

3. **Environment Variables in Render Dashboard:**
   ```
   NODE_ENV=production
   PORT=3000
   CONTACT_EMAIL=medha6017@gmail.com
   ```

4. **Deploy:**
   - Click "Deploy"
   - Wait for build to complete
   - Access at: https://medha-sharma-portfolio.onrender.com

### Step 3: Auto-Deployment
- Render automatically deploys on every `git push` to main branch
- No manual deployment needed after initial setup

## 📧 Contact Form Configuration

**Current Setup:** Console logging (for development)

**For Email Integration:**
1. Get Gmail App Password (if using Gmail)
2. Update .env:
   ```
   SMTP_HOST=smtp.gmail.com
   SMTP_PORT=587
   SMTP_USER=your-email@gmail.com
   SMTP_PASS=your-app-password
   ```
3. Uncomment email code in server.js

## 🎨 Customization

### Update Profile Content
Edit `public/index.html` section for:
- Personal details
- Skills
- Experience
- Education
- Certifications

### Styling
Modify `public/css/style.css`:
- Color scheme
- Fonts
- Layouts
- Animations

### Functionality
Update `public/js/script.js` for:
- Form validation
- Theme toggle
- Animations
- Event handlers

## 📱 Responsive Design

- **Mobile** (320px - 767px): Single column, hamburger menu
- **Tablet** (768px - 1023px): 2-column layouts
- **Desktop** (1024px+): Full multi-column showcase

## ♿ Accessibility

- WCAG 2.1 AA Compliant
- Semantic HTML5
- ARIA labels
- Keyboard navigation
- Color contrast ✓
- Skip links ✓

## 📊 Performance

**Target Metrics:**
- Lighthouse Performance: 90+
- Lighthouse Accessibility: 95+
- Lighthouse SEO: 95+
- Page Load Time: <3 seconds

## 🔒 Security

- HTTPS enforced
- Environment variables for secrets
- Input validation on contact form
- Rate limiting on API
- CORS configured

## 📄 CV/Resume

Download resume: [Professional-CV-Resume_20250211_165121_0000.pdf](link-to-pdf)

## 👤 About Medha Sharma

**CTET Qualified Teacher | B.Ed Graduate | Pursuing M.Ed**

- 📍 Location: Sithaura, Bareilly, UP
- 📧 Email: medha6017@gmail.com
- 📱 Phone: +91 8650251651
- 🎓 Certifications: CTET Paper 2, CCC
- 🏢 Experience: 4 months internship at GIC, Bareilly

## 📚 Qualifications

- Master of Education (M.Ed) - Pursuing at Jyoti College, MJPRU
- Bachelor of Education (B.Ed) - Jyoti College
- Bachelor of Commerce - Bareilly College, MJPRU
- CBSE Secondary & Higher Secondary

## 🤝 Contributing

Feel free to fork, create issues, or submit pull requests for improvements!

## 📝 License

MIT License - Free to use and modify

## 🔗 Links

- **GitHub Repo**: https://github.com/us8024435-debug/medha-sharma-portfolio
- **Live Portfolio**: https://medha-sharma-portfolio.onrender.com (coming soon)
- **Render Dashboard**: https://dashboard.render.com

---

**Built with ❤️ for education** | Last Updated: December 28, 2025

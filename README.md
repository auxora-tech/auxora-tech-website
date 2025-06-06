# Auxora Tech - Company Website

[![Website Status](https://img.shields.io/website?url=https%3A//auxoratech.com)](https://auxoratech.com)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-brightgreen)](https://pages.github.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Enterprise lead management solutions for Facebook Lead Ads with seamless CRM integration.

## 🌐 Live Website

**Primary Domain:** [https://auxoratech.com](https://auxoratech.com)  
**GitHub Pages:** [https://auxora-tech.github.io/auxora-tech-website](https://auxora-tech.github.io/auxora-tech-website)

## 📋 About This Repository

This repository contains the official company website for **Auxora Tech**, a technology company specializing in lead management solutions for businesses running Facebook Lead Ads campaigns.

### 🎯 Purpose
- Corporate website and brand presence
- Legal compliance pages (Privacy Policy, Terms of Service)
- Product information and company overview
- Contact information and business details
- Meta App Review compliance documentation

## 🗂️ Repository Structure

```
auxora-tech-website/
├── index.html              # Main homepage
├── privacy/
│   └── index.html         # Privacy Policy (/privacy)
├── terms/
│   └── index.html         # Terms of Service (/terms)
├── assets/                # Images, icons, etc. (future)
├── README.md              # This file
└── CNAME                  # Custom domain configuration
```

## 🚀 Features

### Homepage (`/`)
- **Company Overview:** Mission, vision, and services
- **Product Features:** Lead management capabilities
- **About Section:** Company background and team
- **Contact Information:** Business contact details
- **Professional Design:** Modern, responsive layout

### Privacy Policy (`/privacy`)
- **GDPR Compliance:** European data protection standards
- **CCPA Compliance:** California consumer privacy rights
- **Lead Data Processing:** Facebook Lead Ads data handling
- **CRM Integration:** Third-party service data sharing
- **User Rights:** Access, correction, deletion procedures

### Terms of Service (`/terms`)
- **Service Agreement:** Platform usage terms
- **User Responsibilities:** Account management requirements
- **Data Usage Rights:** Business data ownership
- **Limitation of Liability:** Legal protections
- **Business Integration:** Facebook API compliance

## 🛠️ Technologies

- **Frontend:** Pure HTML5, CSS3, Vanilla JavaScript
- **Hosting:** GitHub Pages
- **Domain:** Custom domain (auxoratech.com)
- **SSL:** Automatic HTTPS via GitHub Pages
- **Responsive:** Mobile-first design approach

### Why No Frameworks?
- ⚡ **Fast Loading:** No build process or heavy dependencies
- 🔧 **Easy Maintenance:** Simple HTML/CSS updates
- 💰 **Cost Effective:** Free hosting with GitHub Pages
- 🌐 **Universal Compatibility:** Works on all browsers
- 📱 **Mobile Optimized:** Responsive design without frameworks

## 🚀 Deployment

### Automatic Deployment
This website is automatically deployed via **GitHub Pages** when changes are pushed to the `main` branch.

```bash
# Deployment Flow
1. Push to main branch
2. GitHub Pages builds automatically
3. Live at auxoratech.com within 1-2 minutes
```

### Manual Deployment (Alternative)
```bash
# Clone repository
git clone https://github.com/auxora-tech/auxora-tech-website.git

# Navigate to directory
cd auxora-tech-website

# Open in browser
open index.html
```

## 📝 Development

### Local Development
```bash
# Method 1: Simple HTTP Server (Python)
python -m http.server 8000

# Method 2: Node.js HTTP Server
npx http-server

# Method 3: Live Server (VS Code Extension)
# Install "Live Server" extension and right-click index.html
```

### Making Changes
1. **Edit HTML files** directly in browser or IDE
2. **Test locally** using any HTTP server
3. **Commit changes** to repository
4. **Automatic deployment** via GitHub Pages

### File Editing
```bash
# Main website content
edit index.html

# Privacy policy updates
edit privacy/index.html

# Terms of service updates
edit terms/index.html

# Commit and push
git add .
git commit -m "Update website content"
git push origin main
```

## 🔗 Important URLs

### Production URLs
- **Homepage:** https://auxoratech.com
- **Privacy Policy:** https://auxoratech.com/privacy
- **Terms of Service:** https://auxoratech.com/terms

### Development URLs
- **GitHub Repository:** https://github.com/auxora-tech/auxora-tech-website
- **GitHub Pages:** https://auxora-tech.github.io/auxora-tech-website

### Related Services
- **Lead Management App:** https://leads.auxoratech.com *(future)*
- **API Documentation:** https://api.auxoratech.com *(future)*

## 📧 Contact Information

### Business Contacts
- **General:** hello@auxoratech.com
- **Support:** support@auxoratech.com
- **Sales:** sales@auxoratech.com
- **Privacy:** privacy@auxoratech.com

### Technical Contacts
- **Webmaster:** webmaster@auxoratech.com
- **Security:** security@auxoratech.com

## 🎯 Meta App Integration

This website serves as the primary domain for **Auxora Tech's Meta App Review** process:

### App Review Configuration
```
App Name: Auxora Lead Management System
App Domain: auxoratech.com
Privacy Policy URL: https://auxoratech.com/privacy
Terms of Service URL: https://auxoratech.com/terms
Contact Email: admin@auxoratech.com
```

### Required Permissions
- `leads_retrieval` - Facebook Lead Ads data access
- `pages_manage_ads` - Page advertising management
- `pages_read_engagement` - Page engagement data
- `pages_show_list` - Page listing access

## 📊 Analytics & Monitoring

### Performance Monitoring
- **Uptime:** Monitored via GitHub Pages status
- **Performance:** Lighthouse audits for speed optimization
- **SEO:** Search engine optimization compliance

### Future Integrations
- Google Analytics (when needed)
- Meta Pixel (for advertising)
- Customer support chat (business growth)

## 🔒 Security & Compliance

### Data Protection
- **HTTPS Enforced:** All traffic encrypted via GitHub Pages
- **No User Data:** Static website with no data collection
- **Privacy Compliant:** GDPR/CCPA compliant privacy policy

### Legal Compliance
- **Terms of Service:** Comprehensive usage terms
- **Privacy Policy:** Complete data protection disclosure
- **Business Verification:** Meta business verification compliant

## 📈 Future Enhancements

### Short Term (1-3 months)
- [ ] Contact form integration
- [ ] Blog section for company updates
- [ ] Customer testimonials
- [ ] Product screenshots and demos

### Long Term (3-12 months)
- [ ] Multi-language support
- [ ] Advanced analytics integration
- [ ] Customer portal integration
- [ ] Knowledge base/documentation

## 🤝 Contributing

### Internal Team
This repository is maintained by the Auxora Tech team. For updates:

1. **Create feature branch** from main
2. **Make changes** and test locally
3. **Submit pull request** for review
4. **Merge to main** for automatic deployment

### External Contributors
For suggestions or bug reports:
- **Email:** webmaster@auxoratech.com
- **Issues:** Use GitHub Issues for bug reports

## 📄 License

This website content is proprietary to Auxora Tech. The codebase structure is available under MIT License for reference.

```
Copyright (c) 2025 Auxora Tech
All rights reserved.
```

## 📚 Documentation

### Technical Documentation
- [GitHub Pages Setup](https://docs.github.com/en/pages)
- [Custom Domain Configuration](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [Meta App Review Process](https://developers.facebook.com/docs/app-review)

### Business Documentation
- [Privacy Policy Details](privacy/index.html)
- [Terms of Service Details](terms/index.html)
- [Company Information](index.html#about)

---

## 🌟 Quick Links

| Resource | URL |
|----------|-----|
| **Live Website** | [auxoratech.com](https://auxoratech.com) |
| **Privacy Policy** | [auxoratech.com/privacy](https://auxoratech.com/privacy) |
| **Terms of Service** | [auxoratech.com/terms](https://auxoratech.com/terms) |
| **GitHub Repository** | [github.com/auxora-tech/auxora-tech-website](https://github.com/auxora-tech/auxora-tech-website) |
| **Lead Management App** | [leads.auxoratech.com](https://leads.auxoratech.com) *(coming soon)* |

---

**Built with ❤️ by the Auxora Tech Team**  
*Empowering businesses with intelligent lead management solutions*

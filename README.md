# NairaGuard - Counterfeit Currency Detector

🛡️ **AI-Powered Nigerian Naira Counterfeit Detection App**

> ⚠️ **DEMO VERSION**: This app currently uses **simulated analysis** for demonstration purposes. Real AI integration (Claude Vision API) is required for actual currency verification. See [AI Integration Guide](AI_INTEGRATION_REQUIRED.md) for details.

## Overview

NairaGuard is a production-ready, single-file web application designed to help Nigerians identify counterfeit currency using advanced image analysis and security feature verification.

## Features

- 📷 **Smart Scanner** - Camera capture and photo upload with HD quality
- 💵 **Note Preview Gallery** - Visual reference for all 8 Naira denominations (₦5-₦1000)
- 🤖 **AI-Powered Analysis** - Denomination detection and security feature verification
- 📚 **Educational Content** - Comprehensive guide on Naira security features
- 💾 **Analysis History** - Saves last 10 scans locally
- 📴 **Offline Support** - Works without internet after first load
- 📱 **Mobile-First** - Fully responsive design

## Quick Start

1. Open `nairaguard-antigravity.html` in any modern web browser
2. Allow camera permissions (optional)
3. Scan or upload a Naira note image
4. View instant analysis results

## Deployment

### Antigravity
Simply copy the entire `nairaguard-antigravity.html` file into Antigravity's editor and deploy.

### Web Server
Upload `nairaguard-antigravity.html` to any web server - no build process required!

## Security Features Checked

- ✓ Watermark
- ✓ Security Thread
- ✓ Iridescent Band
- ✓ Raised Print
- ✓ Serial Numbers
- ✓ Print Quality
- ✓ Gold Foil (higher denominations)

## Technology Stack

- **HTML5** - Semantic markup with Canvas API
- **CSS3** - Modern dark theme with glassmorphism
- **Vanilla JavaScript** - ES6+ with no dependencies
- **Service Worker** - Offline capability
- **LocalStorage** - Data persistence

## Browser Support

- ✅ Chrome/Edge (Chromium)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

## File Structure

```
naita-detect/
└── nairaguard-antigravity.html    # Complete standalone app
```

## Features by Denomination

| Denomination | Color | Security Features |
|--------------|-------|-------------------|
| ₦5 | Purple | Watermark, Security Thread |
| ₦10 | Brown | Watermark, Security Thread |
| ₦20 | Green | + Iridescent Band |
| ₦50 | Blue | + Iridescent Band |
| ₦100 | Red | + Iridescent Band |
| ₦200 | Brown-Green | + Iridescent Band, Gold Foil |
| ₦500 | Blue-Purple | + Iridescent Band, Gold Foil |
| ₦1000 | Blue-Green | + Iridescent Band, Gold Foil |

## Future Enhancements

- Real Claude API integration for AI analysis
- Multi-language support (Hausa, Yoruba, Igbo)
- Batch scanning capability
- Statistics dashboard
- Share/export results

## License

MIT License - Free to use and modify

## Disclaimer

This is an AI-assisted educational tool. For official currency verification, please consult the Central Bank of Nigeria or authorized financial institutions.

---

**Built with ❤️ for Nigeria** 🇳🇬

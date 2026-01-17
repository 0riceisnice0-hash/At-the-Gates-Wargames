# At the Gates Wargames

A static website for a Warhammer collection buying and selling service, built with plain HTML, CSS, and JavaScript for deployment on GitHub Pages.

## About

At the Gates Wargames is a collector-led service for buying and selling Warhammer and tabletop miniatures across Hampshire and the South East of England. This website provides information about our services, fair valuation processes, and contact details for collectors looking to buy or sell their collections.

## Features

- **5 Pages**: Home, About, Services, FAQs, and Contact
- **Mobile-First Responsive Design**: Optimised for all devices
- **SEO Optimised**: Proper heading hierarchy, meta tags, and structured data
- **Structured Data**: Organization, LocalBusiness, and FAQ schemas for enhanced search visibility
- **Dark Collector-Focused Design**: Professional aesthetic inspired by specialist collector sites
- **Form Validation**: JavaScript-powered contact form with client-side validation
- **Fast Performance**: No dependencies, pure HTML/CSS/JS for instant loading

## GitHub Pages Setup

### Option 1: Using Repository Settings (Recommended)

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select the branch you want to deploy (usually `main` or `master`)
5. Click **Save**
6. Your site will be published at: `https://0riceisnice0-hash.github.io/At-the-Gates-Wargames/`

### Option 2: Using GitHub Actions

If you prefer automated deployments with GitHub Actions:

1. Create `.github/workflows/deploy.yml` with appropriate workflow configuration
2. GitHub Pages will automatically build and deploy on each push to the main branch

## Local Development

To run this site locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/0riceisnice0-hash/At-the-Gates-Wargames.git
   cd At-the-Gates-Wargames
   ```

2. Open `index.html` in your web browser, or use a simple HTTP server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have npx)
   npx serve
   ```

3. Navigate to `http://localhost:8000` (or the port shown in your terminal)

## File Structure

```
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── faqs.html          # FAQs page with accordion
├── contact.html        # Contact page with form and map
├── styles.css          # Main stylesheet
├── script.js           # JavaScript for navigation and form validation
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup with proper heading hierarchy
- **CSS3**: Custom properties (CSS variables), Grid, Flexbox, media queries
- **JavaScript (ES6+)**: Form validation, mobile navigation, FAQ accordion
- **Schema.org**: Structured data for SEO (LocalBusiness, Organization, FAQPage)

## SEO Features

- Unique title and meta description on each page
- Single H1 per page with proper heading hierarchy
- Target keywords naturally integrated:
  - buy warhammer collection
  - sell warhammer models
  - second hand warhammer uk
  - warhammer buyers hampshire
  - tabletop miniature buyers
  - wargame collection valuation
- LocalBusiness and Organization structured data
- FAQ schema on FAQs page
- Mobile-responsive design
- Fast load times (no external dependencies)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This is a demonstration website created for portfolio purposes.

## Contact

For inquiries about the service: info@atthegateswargames.co.uk
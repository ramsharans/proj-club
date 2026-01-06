# Finance Club Website

A collection of financial calculators built with pure HTML, CSS, and JavaScript. This website is designed to be hosted on GitHub Pages.

## 🚀 Features

- **Compound Interest Calculator**: Calculate the future value of investments with compound interest
- **EMI Calculator**: Calculate Equated Monthly Installments for loans
- **SIP Calculator**: Plan your Systematic Investment Plan returns
- **ROI Calculator**: Measure Return on Investment for various ventures

## 🌐 Live Demo

Access the website at: `https://[your-username].github.io/proj-club/`

## 📦 Installation & Setup

### Option 1: Local Development

1. Clone this repository:
```bash
git clone https://github.com/[your-username]/proj-club.git
cd proj-club
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

3. Visit `http://localhost:8000` in your browser

### Option 2: GitHub Pages Deployment

1. **Create a GitHub repository:**
   - Go to [GitHub](https://github.com) and create a new repository named `proj-club`
   - Don't initialize with README, .gitignore, or license

2. **Push your code to GitHub:**
```bash
cd /Users/rasingh/Development/proj-club
git init
git add .
git commit -m "Initial commit: Finance Club website"
git branch -M main
git remote add origin https://github.com/[your-username]/proj-club.git
git push -u origin main
```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be published at: `https://[your-username].github.io/proj-club/`

### Option 3: Custom Domain Setup

1. **After enabling GitHub Pages:**
   - In the Pages settings, find "Custom domain"
   - Enter your domain name (e.g., `financeclub.com`)
   - Click "Save"

2. **Configure your domain provider:**
   - Add DNS records at your domain provider (GoDaddy, Namecheap, etc.)
   
   **For Apex Domain (financeclub.com):**
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```
   
   **For Subdomain (www.financeclub.com):**
   ```
   Type: CNAME
   Host: www
   Value: [your-username].github.io
   ```

3. **Wait for DNS propagation** (can take up to 48 hours, usually much faster)

4. **Enable HTTPS:**
   - In GitHub Pages settings, check "Enforce HTTPS"

## 📁 Project Structure

```
proj-club/
├── index.html                 # Homepage
├── compound-interest.html     # Compound Interest Calculator
├── emi-calculator.html        # EMI/Loan Calculator
├── sip-calculator.html        # SIP Calculator
├── roi-calculator.html        # ROI Calculator
├── styles.css                 # Shared stylesheet
└── README.md                  # This file
```

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript (Vanilla)**: Calculator logic and interactivity
- **GitHub Pages**: Hosting

## 🎨 Features

- ✅ Pure HTML/CSS/JavaScript (no frameworks)
- ✅ Fully responsive design
- ✅ Mobile-friendly interface
- ✅ No server required
- ✅ Fast loading times
- ✅ Privacy-focused (all calculations done locally)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

Feel free to fork this project and submit pull requests for:
- New calculator types
- UI/UX improvements
- Bug fixes
- Feature enhancements

## 📄 License

This project is open source and available under the MIT License.

## 👥 About Finance Club

Finance Club is dedicated to providing accessible financial tools and education. Our mission is to help people make informed financial decisions.

## 📞 Support

For issues or questions, please open an issue on GitHub.

---

**Made with ❤️ by Finance Club**

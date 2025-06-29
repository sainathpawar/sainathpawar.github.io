# Sainath Pawar - Personal Portfolio Website

A modern, interactive personal portfolio website showcasing my experience as a Senior Data Scientist and AI innovator.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations, hover effects, and dynamic content
- **Professional Sections**:
  - Hero section with introduction
  - About me with skills showcase
  - Work experience timeline
  - Featured projects gallery
  - Blog/Content section
  - Contact form
- **Social Integration**: Links to GitHub, LinkedIn, YouTube, and Medium
- **Modern UI**: Clean, professional design with blue and white color scheme
- **Accessibility**: Keyboard navigation and screen reader friendly
- **Performance Optimized**: Fast loading with optimized code

## 🚀 Live Website

Visit: [https://sainathpawar.github.io](https://sainathpawar.github.io)

Here’s a clean and professional **Markdown format** you can copy-paste into your existing `README.md` file. You can place it under a relevant section like **Installation** or **Amazon Q Developer CLI Setup**.

### 🚀 Installing Amazon Q Developer CLI on Windows (via WSL)

> **Note**: Amazon Q Developer CLI does **not** support native Windows installation. It requires using **Windows Subsystem for Linux (WSL)**.

#### Step 1: Set up WSL

1. Open **PowerShell as Administrator**.
2. Run the following command to install WSL and the default Ubuntu distribution:

   ```bash
   wsl --install
   ```

   To install a specific distribution:

   ```bash
   wsl --install -d <Distro>
   ```
3. Restart your computer if prompted.
4. Verify installation:

   ```bash
   wsl -l -v
   ```

#### Step 2: Install Amazon Q Developer CLI inside WSL

1. Open the **Ubuntu terminal** (or your installed WSL distribution).
2. Install `unzip`:

   ```bash
   sudo apt install unzip
   ```
3. Download the Amazon Q CLI ZIP:

   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://desktop-release.codewhisperer.us-east-1.amazonaws.com/latest/q-x86_64-linux-musl.zip -o q.zip
   ```
4. Unzip the archive:

   ```bash
   unzip q.zip
   ```
5. Navigate to the directory:

   ```bash
   cd q
   ```
6. Make the installer executable:

   ```bash
   chmod +x install.sh
   ```
7. Run the installer:

   ```bash
   ./install.sh
   ```
8. Restart WSL.

#### Step 3: Verify & Authenticate

1. Open a **new WSL terminal**.
2. Check CLI health:

   ```bash
   q doctor
   ```
3. Log in with your AWS Builder ID or Pro license:

   ```bash
   q login
   ```
4. Follow the prompts in your browser to complete authentication.

✅ You are now ready to use **Amazon Q Developer CLI** inside your WSL environment on Windows.

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## 🛠️ Setup Instructions for GitHub Pages

### Step 1: Create Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it: `sainathpawar.github.io` (replace with your GitHub username)
4. Make it public
5. Initialize with README (optional)

### Step 2: Upload Files
1. Clone the repository or use GitHub's web interface
2. Upload these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`

### Step 3: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 4: Access Your Website
- Your website will be available at: `https://sainathpawar.github.io`
- It may take a few minutes to deploy

## 🎨 Customization

### Colors
The website uses a professional blue and white color scheme:
- Primary Blue: `#2563eb`
- Accent Yellow: `#fbbf24`
- Background: `#ffffff` and `#f8fafc`
- Text: `#1f2937` and `#4b5563`

### Content Updates
To update your information:
1. Edit `index.html` for content changes
2. Modify `styles.css` for design changes
3. Update `script.js` for functionality changes

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu if needed

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px to 1199px
- Mobile: Below 768px

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📈 Performance Features

- Optimized images and assets
- Smooth scrolling and animations
- Debounced scroll events
- Lazy loading for better performance
- Mobile-first responsive design

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- GitHub Pages for hosting

---

**Built with ❤️ by Sainath Pawar**

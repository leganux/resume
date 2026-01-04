# Resume hub Example

A dynamic resume service that generates beautiful, customizable resumes from GitHub-hosted JSON data. Create professional resumes with multiple formats, themes, and language support.

## 🌟 Features

### Resume Formats
- **MIT Format**: Clean, academic-style layout focusing on content
- **Modern Format**: Timeline-based layout with visual elements and cards
- Switch between formats using URL parameters

### Customization
- **Dynamic Theme Switching**: 25+ Bootswatch themes available
  - Cerulean, Cosmo, Cyborg, Darkly, Flatly, and more
  - Change themes on-the-fly without reloading
- **Multi-language Support**
  - Host multiple language versions of your resume
  - Easy language switching through navigation
  - Supports any language variants (en, es, fr, etc.)

### Export Options
- **PDF Download**
  - High-quality PDF generation
  - Maintains selected theme and format
  - Perfect for sharing and printing
- **HTML Download**
  - Standalone HTML file with embedded styles
  - Includes all assets and formatting
  - Great for web hosting

### Technical Features
- **Responsive Design**: Works on all devices and screen sizes
- **GitHub Integration**: Pull resume data from your repository
- **Docker Support**: Easy deployment with Docker
- **Environment Configuration**: Flexible setup options

## 🚀 Getting Started



### Repository Structure

CLONE OR FORK this repository and UPDATE your info.

 Your GitHub repository should contain:

```
your-resume-repo/
├── index.json           # Configuration and settings
├── resume.en.json      # English resume data
├── resume.es.json      # Spanish resume data
└── resume.[lang].json  # Other language variants
```




## 📖 Usage

### Accessing Your Resume

1. Create your resume repository on GitHub
2. Access your resume at:
   ```
   https://resume-hub.com/<github-username>/<repository-name>
   ```

### URL Parameters

- **Format Selection**:
  ```
  /<github-username>/<repository-name>/modern  # Modern timeline format
  /<github-username>/<repository-name>      # Default MIT format
  ```

- **Language Selection**:
  ```
  /<github-username>/<repository-name>?lang=es  # Spanish version
  /<github-username>/<repository-name>?lang=en  # English version
  ```

- **Theme Selection**:
  ```
  /<github-username>/<repository-name>?theme=cyborg   # Dark theme
  /<github-username>/<repository-name>?theme=flatly   # Light theme
  ```

- **Combined Parameters**:
  ```
  /<github-username>/<repository-name>/modern?lang=es&theme=cyborg
  ```

- **Examples**
    https://resume-hub.com/leganux/resume?theme=lux&lang=en
    https://resume-hub.com/leganux/resume/modern?lang=es

### Download Options

- **PDF Download**: Click the PDF button in navigation
  - Maintains current theme and format
  - Perfect for printing and sharing

- **HTML Download**: Click the HTML button in navigation
  - Includes all styles and formatting
  - Self-contained file



1. **New Language**:
   - Add `resume.[lang].json` to your repository
   - Update `index.json` variants


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Bootswatch](https://bootswatch.com/) for the amazing themes
- [Browserless](https://browserless.io/) for PDF generation
- [Express.js](https://expressjs.com/) for the web framework
- [Pug](https://pugjs.org/) for templating

## 📞 Support

- Create an issue for bug reports
- Star the repository if you find it useful
- Fork and contribute to help improve the project

# BlackLine Scanner (Ultimate)

## Overview
**BlackLine Scanner (Ultimate)** is a versatile and user-friendly tool designed for web developers, security researchers, and enthusiasts. It allows users to extract and analyze various web resources, including URLs, scripts, images, sensitive form fields, and cookies. Additionally, it performs basic vulnerability checks to identify common security issues on a webpage.

## Features
- **URL Extraction**: Scans the page for all links, resources, and endpoints.
- **Script Detection**: Identifies both external and inline scripts on the page.
- **Image Collection**: Gathers all image URLs from the page.
- **Sensitive Form Fields Detection**: Identifies input fields such as passwords, emails, and text inputs for security analysis.
- **Cookie Extraction**: Displays cookies present on the page for review.
- **Basic Vulnerability Check**: Highlights common issues such as:
  - Missing `autocomplete` attributes in forms.
  - Presence of inline scripts.
  - Cookies missing the `HttpOnly` flag.

## Installation
No installation is required. The script can be executed directly in the browser console or saved as a bookmarklet.

### How to Use
1. **Copy the Script**:
   - Open the file `Bookmarkscript_By_Dev.txt` and copy its content.

2. **Create a Bookmarklet**:
   - Open your browser's bookmarks manager.
   - Create a new bookmark.
   - In the URL field of the bookmark, paste the copied script.

3. **Run the Scanner**:
   - Navigate to any webpage you want to analyze.
   - Click the bookmarklet to launch the scanner. The results will appear in a panel at the bottom of the page.

### Bookmarklet Code
The script for the BlackLine Scanner can be found in [Bookmarkscript_By_Dev.txt](./Bookmarkscript_By_Dev.txt). Copy its content into the bookmark's URL field to create the bookmarklet.

## Planned Enhancements
- **Advanced Vulnerability Checks**: Include additional scans for common web security issues (e.g., XSS and CSRF vulnerabilities).
- **Improved User Interface**: Enhance the tool's UI/UX for a more seamless experience.
- **Customization Options**: Add features to filter and prioritize specific resource types during scanning.

## Security Disclaimer
This tool is intended for educational and ethical use only. Ensure you have permission before scanning any website, as unauthorized scanning may violate terms of service or local laws.

## License
This project is open-source and distributed under the [MIT License](LICENSE).

## Contributing
Contributions are welcome! If you'd like to report an issue, suggest a feature, or contribute to the project, please open an issue or submit a pull request on GitHub.

## Acknowledgments
- **BlackLine Scanner (Ultimate)** was created to simplify web resource scanning and basic vulnerability checks.
- Special thanks to all contributors and the open-source community for their support and feedback!

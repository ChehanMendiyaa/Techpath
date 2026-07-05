# TechPath – A/L Technology Resource Hub

A web-based educational resource platform designed for Sri Lankan G.C.E. Advanced Level (A/L) Technology students. The platform provides easy access to study materials, allowing students to search, browse, and download academic resources from a centralized location.

## Overview

TechPath was developed as part of the **BAWA** fundraising initiative organized by the Faculty of Technology, University of Ruhuna.

As part of the event, QR codes were printed on BAWA promotional stickers. When scanned, users are directed to this platform, where they can access a collection of educational resources relevant to A/L Technology subjects.

The project was built as a static website to ensure:

- Low hosting costs
- Fast performance
- Easy maintenance
- High accessibility
- No server-side infrastructure requirements

All resources are managed through JavaScript and distributed using Google Drive links.

---

## Features

- 📱 Mobile-responsive design
- ⚡ Fast-loading static architecture
- 🔍 Resource search and filtering
- 📚 Subject-wise resource organization
- ☁️ Google Drive integration
- 🎓 Designed specifically for A/L Technology students
- 🌐 Accessible through QR codes
- 🛠️ Easy resource management
- 🚀 Deployable on any static hosting platform


---

## Available Resources

The platform provides access to:

- Past Papers
- Textbooks
- Teachers' Guides
- Model Papers
- Provincial Papers
- Extra Notes

---

## Subjects

- Engineering Technology
- Science for Technology
- Information & Communication Technology (ICT)
- Bio Systems Technology
- Agricultural Science

---

## Live Website

🌐 **Website:** https://techpath.site

---

## Technology Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Google Drive (Resource Storage)
- GitHub Pages (Hosting)
- Cloudflare DNS

---

## Project Structure

```text
/
├── CNAME
├── README.md
├── PROJECT_1_NOTES.md
├── index.html
├── resources.html
├── subject.html
├── university.html
├── app.js
├── library.js
├── resources.js
├── subject.js
├── university.js
└── styles.css
```

---

## Getting Started

### Run Locally

Clone the repository:

```bash
git clone https://github.com/ChehanMendiyaa/Techpath.git
```

Navigate to the project folder:

```bash
cd Techpath
```

Open `index.html` in your preferred web browser.

---

## Subject Pages

Subject-specific resources are displayed through `subject.html`.

Example:

```text
subject.html?subject=Bio%20Systems%20Technology
```

---

## Managing Resources

All educational resources are stored within `resources.js`.

To add a new resource:

1. Open `resources.js`
2. Copy an existing resource object
3. Update the following fields:
   - Title
   - Type
   - Subject
   - Year
   - Medium
   - Drive URL
4. Upload the file to Google Drive
5. Set sharing permission to **Anyone with the link can view**
6. Paste the sharing link into the `driveUrl` field

### Supported Resource Types

- Past Paper
- Textbook
- Teachers' Guide
- Model Paper

### Supported Subjects

- Engineering Technology
- Science for Technology
- Information & Communication Technology
- Bio Systems Technology
- Agricultural Science

---

## Deployment

This project can be deployed on any static hosting platform, including:

- GitHub Pages
- Netlify
- Cloudflare Pages
- Vercel

No backend services, databases, or server-side processing are required.

---

## Project Highlights

- Developed as a fully static web application
- Designed specifically for Sri Lankan A/L Technology students
- Mobile-first responsive design
- QR-code-based resource distribution
- Cost-effective architecture with zero backend expenses
- Easy content management through JavaScript configuration
- Fast and lightweight user experience

---

## Future Improvements

- Advanced search functionality
- Resource request system
- Resource popularity tracking
- Dark mode support
- Multi-language interface
- Offline resource catalog

---

## Author

**Chehan Mendiya**

BICT Undergraduate  
Faculty of Technology  
University of Ruhuna

---

## Acknowledgements

Special thanks to the Faculty of Technology, University of Ruhuna, and the organizers of the BAWA fundraising initiative for providing the inspiration and opportunity to develop this project.

Special thanks to:

- The Faculty of Technology, University of Ruhuna, for providing the inspiration and opportunity to develop this project through the **BAWA Fundraising Initiative**.
- The Brothers and Sisters in Uni ❤️  who shared educational materials and supported to the resource collection process.
- All individuals who contributed by finding, organizing, verifying, and sharing past papers, textbooks, teachers' guides, model papers, and other learning resources included in this platform.
- Everyone who provided feedback, suggestions, and encouragement throughout the development of the project.

Their contributions have helped make TechPath a valuable educational resource for Sri Lankan G.C.E. Advanced Level (A/L) Technology students.

---

## License

This project is released under the MIT License.

Feel free to use, modify, and distribute this project with proper attribution.

---

⭐ If you find this project useful, consider giving it a star on GitHub.

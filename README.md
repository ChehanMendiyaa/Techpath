# Project 1: TechPath A/L Technology Resource Hub

## Purpose

This is my first project as an undergraduate student at the University of Ruhuna.

I created this website to support a fundraising event called **BAWA**, organized by the Faculty of Technology, University of Ruhuna. As part of the event, we printed stickers featuring the BAWA logo, and each sticker included a QR code. When users scan the QR code, they are redirected to this website, where students can search for and download educational resources.

To minimize hosting and maintenance costs, I developed the platform as a static website. All resources are managed through JavaScript and Google Drive links.

The website is a modern, mobile-responsive platform designed for Sri Lankan G.C.E. Advanced Level (A/L) Technology students.

The site provides access to study resources such as:

* Past Papers
* Textbooks
* Teachers' Guides
* Model Papers
* Extra Notes
* Provincial Papers

All resources are organized and delivered through Google Drive links.

## Current Website Location

**Main Site:**

`techpath.site`

## Subjects Included

* Engineering Technology
* Science for Technology
* Information & Communication Technology (ICT)
* Bio Systems Technology
* Agricultural Science

## Getting Started

Open `index.html` in a web browser, or upload the project folder to GitHub Pages, Netlify, Cloudflare Pages, or any other static hosting platform.

Subject-specific pages use `subject.html`. For example:

`subject.html?subject=Bio%20Systems%20Technology`

## Adding Google Drive Resources

1. Open `resources.js`.
2. Copy an existing resource object.
3. Update the title, type, subject, year, medium, and `driveUrl` fields.
4. In Google Drive, set the file permission to **Anyone with the link can view**, then paste the share link into `driveUrl`.

### Supported Resource Types

* Past Paper
* Textbook
* Teachers' Guide
* Model Paper

### Supported Subjects

* Engineering Technology
* Science for Technology
* Information & Communication Technology
* Bio Systems Technology
* Agricultural Science

No backend or database is required. All searching and filtering are performed directly in the browser.

# Resume Website - Mehidi Akash

## Overview
This project is a personal resume website created as part of **COMP 2600: Technical Communication in Computer Science**. It showcases my resume in a structured and accessible format using **Pelican**, a Python-based static site generator. The website is hosted on **GitHub Pages** for easy access and distribution.

A README file is an essential part of technical documentation. It provides clear instructions and guidance for users, collaborators, and potential employers who want to interact with the project. This README includes detailed instructions on setting up, using, and modifying this project while also addressing technical writing best practices.

## 🌍 Live Website
You can view my resume at:
[https://MHAkaah.github.io/reusme-site](https://MHAkaah.github.io/reusme-site)

## Project Objectives
This project demonstrates:
- **Technical documentation skills** by structuring content using Markdown.
- **Version control and collaboration** using Git and GitHub.
- **Static site generation** with Pelican.
- **Hosting and deployment** through GitHub Pages.
- **Principles of modern technical writing**, as outlined by Andrew Etter.
- **Automation and efficiency** in technical content management.
- **Portability and accessibility**, allowing future modifications or expansions.
- **Integration with CI/CD workflows**, ensuring automated builds and deployments.
- **Scalability** to include additional features such as blog sections or portfolios.
- **Responsive design** support for different screen sizes and devices.

## Features
- **Structured resume in Markdown format** for readability and ease of updating.
- **Automatically generated HTML pages** using Pelican to eliminate manual formatting.
- **Deployment on GitHub Pages** for free hosting and easy access.
- **Version-controlled repository** allowing for tracking changes and collaboration.
- **Customizable themes** to enhance presentation and user experience.
- **SEO-friendly static site** that loads quickly and is indexable by search engines.
- **Lightweight and portable**; can be forked or modified for other projects.
- **Scalability** for future modifications, allowing additional sections or functionality.
- **Scripting and automation** for effortless updates with minimal effort.
- **Efficient site navigation** with automatically generated links and categories.
- **Markdown-based content creation**, making writing and formatting easier.

## Project Structure
```
resume-site/
│── content/           # Markdown files (resume.md, etc.)
│── output/            # Generated static site (HTML, CSS, etc.)
│── themes/            # (Optional) Custom themes
│── pelicanconf.py     # Pelican configuration file
│── publishconf.py     # Production settings
│── README.md          # Project documentation (this file)
```

## 📜 Installation & Setup
To run this project locally, follow these steps:

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/MHAkaah/reusme-site.git
cd reusme-site
```

### **2️⃣ Install Dependencies**
Ensure Python is installed, then run:
```bash
pip install pelican ghp-import
```

### **3️⃣ Generate the Site Locally**
```bash
pelican content
```

### **4️⃣ Preview the Website Locally**
```bash
pelican --listen
```
Now, open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

### **5️⃣ Deploy to GitHub Pages**
```bash
ghp-import output -b gh-pages
git push origin gh-pages
```

## Instructional Guide on Technical Writing Principles
This project aligns with the principles outlined in **Andrew Etter’s *Modern Technical Writing***:
- **Lightweight Markup Language:** The resume is written in Markdown, making it easy to update and format.
- **Version Control:** Git is used to manage changes and track history efficiently.
- **Static Site Generation:** Instead of using traditional word processors, the resume is presented using a structured, automated workflow.
- **Hosting & Deployment:** The project is hosted on GitHub Pages, ensuring accessibility without requiring complex server setup.
- **Separation of Content & Presentation:** Markdown is used for content, while Pelican handles formatting.
- **Scalability & Automation:** By using a static site generator, content updates are automated without the need for manual HTML edits.
- **Continuous Deployment Practices:** Ensuring frequent and effortless updates without manual intervention.
- **Documentation Best Practices:** Clear, concise, and well-structured information to assist users in navigation.
- **Reusability of Content:** Markdown files can be exported into other formats easily.

## FAQ
### **Q1: Why use Pelican for this project?**
Pelican allows for **quick static site generation**, making it ideal for maintaining a professional resume in an organized format. It also supports Markdown, making content creation simple and effective. Unlike traditional word processors, it enables **structured content management** and automatic deployment.

### **Q2: How do I update the resume?**
To update the resume:
1. Edit `content/resume.md`.
2. Run `pelican content` to generate the new HTML output.
3. Deploy the updated content:
   ```bash
   ghp-import output -b gh-pages
   git push origin gh-pages
   ```

### **Q3: How does this project demonstrate Etter’s principles?**
This project follows **modern technical writing principles** by focusing on simplicity, automation, and readability. Markdown enables **easy formatting**, Git ensures **version control**, and Pelican automates **HTML generation**, eliminating the need for manual updates.

### **Q4: What are the advantages of using a static site for a resume?**
- **Fast Load Times:** Static sites are quicker to load compared to dynamic websites.
- **No Server Maintenance:** GitHub Pages handles hosting without requiring a backend.
- **Portable & Reusable:** The resume can be updated and adapted for future projects.
- **Version Controlled:** Any changes made are tracked via Git, making it easier to manage different versions.
- **Security & Reliability:** Unlike dynamic sites, static sites have fewer vulnerabilities and require minimal maintenance.
- **Customization Options:** Allows the use of different themes, color schemes, and layouts for personal branding.

## Setup Process Walkthrough
```
> Where do you want to create your new web site? [.]
> What will be the title of this web site? Mehidi Akash Resume
> Who will be the author of this web site? Mehidi Akash
> What will be the default language of this web site? [English] en
> Do you want to specify a URL prefix? e.g., https://example.com   (Y/n) n
> Do you want to enable article pagination? (Y/n) y
> How many articles per page do you want? [10] 10
> What is your time zone? [America/Edmonton]
> Do you want to generate a tasks.py/Makefile to automate generation and publishing? (Y/n) y
> Do you want to upload your website using GitHub Pages? (y/N) y
> Is this your personal page (username.github.io)? (y/N) n
Done. Your new project is available at C:\Users\mehid
```

## 📜 Assignment Requirements Checklist
✅ **Resume written in Markdown**  
✅ **Static website generated using Pelican**  
✅ **Hosted on a Forge (GitHub Pages)**  
✅ **README file with documentation (1000+ words)**  
✅ **Demonstrates modern technical writing principles**  
✅ **Automation, scalability, and maintainability**  
✅ **Technical accuracy and completeness**  

## 📞 Contact
For any questions, feel free to reach out:
- **Email:** mehidihasanakash118@gmail.com
- **GitHub:** [MHAkaah](https://github.com/MHAkaah)

## Credits
- **Mehidi Akash** - Editor
- **Dac Cam Thai** - Peer Review
- **Saman HM** - Peer Review

---
✅ **Submission Ready!** 🚀

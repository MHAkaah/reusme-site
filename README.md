# Resume Website - Mehidi Akash

This is my personal resume website, built using **Pelican**, a static site generator, and hosted on **GitHub Pages**.

## 🌍 Live Website
[Click here to view my resume](https://MHAkaah.github.io/reusme-site)

## 📜 Project Overview
This project is part of the **COMP 2600** assignment to demonstrate technical communication through documentation, Markdown formatting, and static site generation.

## 🚀 Features
- **Built with Pelican** - A static site generator using Python
- **Resume formatted in Markdown** - Easy to edit and update
- **Hosted on GitHub Pages** - Free and publicly accessible
- **Version controlled with Git** - Allows tracking changes and collaboration

## 📁 Project Structure
```
resume-site/
│── content/           # Markdown files (resume.md, etc.)
│── output/            # Generated static site (HTML, CSS, etc.)
│── themes/            # (Optional) Custom themes
│── pelicanconf.py     # Pelican configuration file
│── publishconf.py     # Production settings
│── README.md          # Project documentation (this file)
```

## 🔧 Installation & Setup
If you want to run the project locally, follow these steps:

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/MHAkaah/reusme-site.git
cd reusme-site
```

### **2️⃣ Install Dependencies**
Ensure you have **Python** installed, then run:
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

## 📜 Assignment Requirements Checklist
✅ **Resume written in Markdown**  
✅ **Static website generated using Pelican**  
✅ **Hosted on a Forge (GitHub Pages)**  
✅ **README file with documentation**  

## 📞 Contact
For any questions, feel free to reach out:
- **Email:** mehidihasanakash118@gmail.com
- **GitHub:** [MHAkaah](https://github.com/MHAkaah)
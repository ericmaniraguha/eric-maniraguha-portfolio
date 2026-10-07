# Eric Maniraguha - Data Engineer Portfolio

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=Apache-Spark&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=Apache-Airflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

A modern, responsive, and beautifully designed static web portfolio built to showcase data engineering experience, projects, academic publications, and certifications.

## 🚀 Features

- **Premium Design:** Sleek dark slate aesthetic (`#0b111e`) with bright cyan accents (`#00bfff`).
- **Dark/Light Mode Switcher:** Built-in theme toggle that dynamically updates variables, shadows, and image blending for an optimal viewing experience in any lighting.
- **Responsive Layout:** fully responsive across all devices (mobile, tablet, and desktop).
- **Comprehensive Sections:**
  - **About/Hero:** Quick summary with integrated CV download and social links.
  - **Experience:** Three categorized timelines for Consulting & Advisory, Technical Industry, and Academic experiences.
  - **Projects:** Highlighted data engineering projects (Databricks, ETL, GIS) with direct links to GitHub repositories and live dashboards.
  - **Publications:** Formatted academic publication record tailored for Data Science/PhD applications.
  - **Education & Certifications:** Comprehensive, scalable list of all degrees and professional certifications.

## 📁 Project Structure

```
portfolio/
├── index.html                                  # Main HTML layout
├── style.css                                   # Styling, layout, animations, and theme variables
├── script.js                                   # Theme toggle logic and scroll animations
├── eric_maniraguha_passport_photo.png          # Hero image
├── eric_maniraguha_data_engineering_2026.pdf   # Downloadable CV
└── README.md                                   # Project documentation
```

## 🛠️ Local Development

Because this is a completely static website with no build step required, running it locally is incredibly fast and easy.

1. **Option 1: Direct File Access**
   Simply double-click the `index.html` file to open it directly in your web browser.

2. **Option 2: Local Server (Recommended for active development)**
   If you have Python installed, you can serve the directory locally:
   ```bash
   python -m http.server
   ```
   Or if you have Node.js installed:
   ```bash
   npx serve
   ```
   Then navigate to `http://localhost:8000` (or the port provided by your server).

## 🌐 Deployment (Netlify)

This portfolio is structurally ready for instant deployment to Netlify via drag-and-drop.

1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag the entire `portfolio` folder into the upload box.
3. Your site will be live instantly! You can then configure a custom domain or rename the site url from your Netlify dashboard.

---
*Developed for Eric Maniraguha | Data Engineering & Database/Analytics Professional*
# eric-maniraguha-portfolio

# 🚀 Serverless Engineering Portfolio & CV Template

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/javilesm/javilesm.github.io)
[![SEO Optimized](https://img.shields.io/badge/SEO-Optimized-success)](#)
[![Analytics](https://img.shields.io/badge/Google_Analytics-GA4-F4B400?logo=google-analytics)](#)

A high-performance, SEO-optimized, and serverless portfolio template designed for hybrid engineering profiles. Originally built as the personal interactive CV for **Jorge Luis Avilés Medina**, this architecture is now open-source and scalable for the developer and engineering community.

---

## 🏗️ System Architecture & Tech Stack

This project leverages a pure **Jamstack** architecture, separating the static frontend from the dynamic backend capabilities to ensure maximum speed, security, and zero-cost scaling.

- **Frontend Hosting:** GitHub Pages (Static HTML/CSS/JS).
- **Serverless Backend:** Vercel Serverless Functions.
- **Email Delivery:** Resend API (Integrated with invisible Honeypot anti-spam logic).
- **Analytics & Tracking:** Google Tag Manager (GTM) + Google Analytics 4 (GA4).
- **Technical SEO:** Fully indexed via `sitemap.xml`, `robots.txt`, dynamic Open Graph (OG) tags, and structured JSON-LD (`@type: "Person"`).

---

## 🛠️ How to Use (Deploy Your Own)

Engineers looking to deploy a highly technical, fast-loading CV can easily fork this repository.

1. **Fork & Clone:** Fork this repository to your GitHub account.
2. **Customize Data:** Edit the `index.html` to inject your own metadata, JSON-LD profile, and experience timeline.
3. **Configure Environment Variables:** If using the contact form, set up a [Resend](https://resend.com/) account and add your `RESEND_API_KEY` in your Vercel project settings.
4. **Deploy:** Push your changes to GitHub Pages for the frontend, and link your repository to Vercel for backend routing.
5. **Analytics (Optional):** Replace the `G-XXXXXXXXXX` Measurement ID in the `<head>` with your own GA4 stream.

---

## 👤 About the Author: Jorge Luis Avilés Medina
### Product Design & Engineering Lead | CAD Automation Specialist

Professional Manufacturing Engineer focused on high-precision mechanical design and workflow optimization. I bridge the gap between traditional industrial engineering and modern software development by implementing automation pipelines for CAD environments and cloud-based 3D geometry processing.

### ⚙️ Core Competencies

- **Design & Engineering:** Autodesk Inventor (API/iLogic), SolidWorks, CATIA V5, GD&T (ASME Y14.5 / ISO 1101), Industrial Metrology. Strict adherence to manufacturing tolerances (e.g., ±0.025 mm / 0.001 in).
- **Programming:** Python (FastAPI, NumPy), VB.NET, VBA, PowerShell.
- **Cloud & DevOps:** Google Cloud Platform (GCP), AWS, Git/GitHub, CI/CD for Engineering Workflows.
- **Manufacturing:** Tooling Design, Reverse Engineering, Injection Molding, Material Science (Polymers & Exotic Alloys).

### 🚀 Key Projects

* **[PointForge3D](https://github.com/javilesm/pointforge3d):** A cloud-native pipeline built on GCP G2 instances (Python/FastAPI) to automatically convert 2D technical references into dense 3D point clouds.
* **[Voxel Engine for CAD](https://github.com/javilesm/cad-voxel-engine):** Procedural geometry generator built within Autodesk Inventor using iLogic and PowerShell, enabling massive data-set handling for 3D assemblies.

### 📈 Professional Experience & Education

- **Current:** Product Design & Engineering Lead at **Perficom**.
- **Past:** Tooling Control Engineer at **VivaAerobus** | Tooling Engineer at **Bombardier Aerospace**.
- **Education:** B.S. in Manufacturing Engineering - **Universidad Tecnológica de San Juan del Río**.

---

## 🌐 Connect & Contact

- **Portfolio:** [javilesm.github.io](https://javilesm.github.io)
- **LinkedIn:** [linkedin.com/in/jorge-aviles-mx](https://linkedin.com/in/jorge-aviles-mx)
- **Email:** jorge.aviles@gmx.com

> *"Precision engineering. Sturdy design. Functional aesthetics. Standardized precision is the foundation of quality engineering."*

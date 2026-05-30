# Labour Relations Dashboard

**Monitor, analyze, and compare workplace relations bodies and compliance across Ireland and Europe.**

---

## 📌 Overview

The **Labour Relations Dashboard** is an open-source project designed to provide a **centralized, real-time, and comparative view** of workplace relations bodies, dispute resolution mechanisms, and compliance frameworks across **Ireland and all European countries**. 

This tool is built for **researchers, policymakers, legal professionals, HR teams, and businesses** who need to:
- Track and compare workplace relations bodies and their functions.
- Monitor compliance requirements and dispute resolution processes.
- Identify trends, gaps, and best practices in labour law enforcement.
- Generate reports for internal use, advocacy, or regulatory compliance.

---

## ✨ Features

### **Core Features (v1.0)**
✅ **Comprehensive Database**
- Curated list of workplace relations bodies in **Ireland and all European countries** (EU27 + UK + EEA).
- Detailed profiles for each body, including **roles, responsibilities, jurisdiction, and contact information**. 

✅ **Interactive Comparison Tool**
- Side-by-side comparison of bodies by **country, function, and legal framework**.
- Filter by **dispute resolution type** (mediation, adjudication, inspection, enforcement).

✅ **Compliance Tracker**
- Track **filing requirements, deadlines, and procedures** for complaints/disputes in each country.
- Customizable alerts for **upcoming deadlines or regulatory changes**. 

✅ **Visual Analytics**
- **Heatmaps** of labour dispute resolution efficiency by country.
- **Trend analysis** of complaint volumes, resolution times, and enforcement actions.

✅ **Report Generator**
- Auto-generate **PDF/CSV reports** for specific countries, bodies, or time periods.
- Exportable **v1 report** (see [Reports](#-reports) section).

✅ **API Access**
- RESTful API for integrating dashboard data into **third-party tools or workflows**.

---

## 🚀 Getting Started

### **Prerequisites**
- Python 3.10+
- Node.js (for frontend)
- PostgreSQL (for database)

### **Installation**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-org/labour-relations-dashboard.git
   cd labour-relations-dashboard
   ```

2. **Set up the backend:**
   ```bash
   cd backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

3. **Set up the frontend:**
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Access the dashboard:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📊 Data Sources

The dashboard aggregates data from:
- Official government websites (e.g., [Workplace Relations Commission Ireland](https://www.workplacerelations.ie));
- European Commission [Labour Law Resources](https://employment-social-affairs.ec.europa.eu/policies-and-activities/rights-work/labour-law_en);
- Eurofound and ILO databases;
- User-submitted updates (via pull requests or the dashboard interface).

---

## 🛠️ Tech Stack

| **Component**       | **Technology**                          |
|----------------------|-----------------------------------------|
| **Frontend**         | React, TypeScript, Tailwind CSS         |
| **Backend**          | Django, Django REST Framework           |
| **Database**         | PostgreSQL                              |
| **Visualization**    | Chart.js, D3.js, Leaflet (for maps)     |
| **Deployment**       | Docker, GitHub Actions, AWS/Heroku       |

---

## 📂 Project Structure

```
labour-relations-dashboard/
├── backend/
│   ├── data/               # Raw and processed datasets
│   ├── api/                # REST API endpoints
│   └── manage.py           # Django management scripts
├── frontend/
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Dashboard pages
│   │   └── styles/         # CSS/SCSS files
│   └── public/             # Static assets
├── docs/
│   ├── reports/           # Generated reports (e.g., v1_report.md)
│   └── roadmap.md          # Future features and milestones
├── README.md               # Project README
└── LICENSE                 # MIT License
```

---

## 📄 Reports

### **v1 Report**
A **fully updated v1 report** is available [here](sandbox/labour-relations-v1-report). This report includes:
- **Executive Summary** of workplace relations bodies in Ireland and Europe.
- **Comparative Analysis** of dispute resolution mechanisms.
- **Compliance Checklist** for filing complaints in each country.
- **Recommendations** for businesses and policymakers.

---

## 🗺️ Roadmap

| **Phase** | **Features**                                                                 | **Status**      | **ETA**       |
|------------|------------------------------------------------------------------------------|-----------------|---------------|
| **v1.0**   | Core database, comparison tool, compliance tracker, basic visualizations    | ✅ Released     | May 2026      |
| **v1.1**   | User accounts, saved searches, email alerts                                | 🚧 In Progress  | June 2026     |
| **v1.2**   | Multi-language support, advanced filtering, API rate limiting               | ⏳ Planned      | July 2026     |
| **v2.0**   | AI-powered insights, predictive analytics, mobile app                       | ⏳ Planned      | Q4 2026       |

---

## 🤝 Contributing

We welcome contributions! Please read our [Contributing Guide](CONTRIBUTING.md) for details on how to:
- Report bugs or request features.
- Submit data updates or corrections.
- Improve the codebase.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For questions or feedback, open an issue or contact us at **team@labour-relations-dashboard.org**.

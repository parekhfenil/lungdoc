# Inland Pulmonary Specialists - Website Content Files

This folder contains all page content for the new website, organized for Framer development.

## Folder Structure

```
website-content/
├── README.md                    # This file
├── pages/                       # Main navigation pages (16 pages)
│   ├── 01-homepage.md
│   ├── 02-asthma.md
│   ├── 03-copd.md
│   ├── 04-pulmonary-fibrosis.md
│   ├── 05-lung-nodule.md
│   ├── 06-pulmonary-hypertension.md
│   ├── 07-ild.md
│   ├── 08-sleep-apnea.md
│   ├── 09-lung-cancer-screening.md
│   ├── 10-about.md
│   ├── 11-staff.md
│   ├── 12-education.md
│   ├── 13-insurance.md
│   ├── 14-tour.md
│   ├── 15-blog.md
│   └── 16-contact.md
│
└── hidden-pages/               # SEO landing pages (not in main nav)
    ├── locations/              # City-specific pages
    ├── conditions/             # Condition + location pages
    ├── services/               # Service-specific pages
    ├── symptoms/               # Symptom-based pages
    └── insurance/              # Insurance-specific pages
```

## Key Information

### Practice Details
- **Name:** Inland Pulmonary Specialists
- **Phone:** (951) 737-5809
- **Text (Preferred):** 951-287-5282
- **Fax:** 951-848-6923

### Locations
1. **Corona Office:** 1157 W Grand Blvd, Corona, CA 92882
2. **Lake Elsinore Office:** 31571 Canyon Estates Dr #219, Lake Elsinore, CA 92532

### Doctors
- Dr. Anoop Maheshwari, M.D. - Pulmonary/Internal Medicine
- Dr. Young H. Lee, M.D. - Pulmonary/Internal Medicine/Critical Care

### Design Notes for Framer
- **Contact CTAs:** Always show text option first (📱 Text Us: 951-287-5282) before call option
- **Schema Markup:** Each page needs JSON-LD structured data (provided in page files)
- **FAQ Sections:** Use accordion/collapsible components with FAQ schema
- **Mobile:** Design mobile-first, text button should be tap-to-text enabled

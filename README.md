# 🏠 Airbnb Performance Dashboard

An interactive business-intelligence dashboard analysing Airbnb listings, hosts, pricing, guest satisfaction and seasonal demand across 10 major cities worldwide (2008–2020).

---

## 📊 Dashboard at a Glance

| Metric | Value |
|---|---|
| Active listings | 279,712 |
| Hosts | 182,024 |
| Cities | 10 |
| Cumulative reviews | 5,000,000+ |
| Time period | 2008 – 2020 |
| Property types | 144 categories |

**Markets covered:** Paris, New York City, Sydney, Rome, Bangkok, Istanbul, Mexico City, Rio de Janeiro, Cape Town, Hong Kong

---

## 🖼️ Dashboard Preview

### Overview — KPIs and listing growth
![Overview page](images/01-overview.png)

### Ratings — market share, pricing and guest ratings by city
![Ratings page](images/02-ratings.png)

### Review — reviewer behaviour, trust and seasonality
![Review page](images/03-reviews.png)

---

## ✨ Key Features

- KPI cards for listings, hosts and reviews
- Historical growth trends (2008–2020)
- Geographic concentration analysis by city
- Pricing architecture across property and room types
- Guest satisfaction and quality metrics
- Trust and verification metrics for hosts
- Review volume and seasonal demand patterns

---

## 🔍 Key Insights

- **Geographic concentration:** Paris, New York and Sydney account for almost half of all listings and 48% of total reviews. Paris leads on both listings and reviews.
- **Pricing:** Hotel rooms average about twice the price of Airbnb options (hotel room $800, entire place $673, shared room $580, private room $462).
- **Guest satisfaction:** Average ratings range from 89.7 (lowest, Hong Kong) to 94.8 (Mexico City).
- **Seasonality:** Paris and Rome dominate review share from April to August (European summer travel); New York rises in November and December (holiday season).
- **Trust:** About 59K profiles (32.6%) are not verified, and 503 (0.3%) are both unverified and have no profile.
- **Growth:** New listings grew steadily through the 2010s before a sharp decline linked to COVID-19.

---

## 🖼️ Report Pages

| Page | Contents |
|---|---|
| **Overview** | KPI cards (listings, cities, hosts, property types, reviews) and new-listing growth by room type, 2008–2020 |
| **Ratings** | Market share by city (superhost vs. non-superhost, cumulative %), average price by room type, average rating by city |
| **Review** | Reviews per reviewer, trust and profile-verification metrics, monthly review share by city |

---

## 📁 Repository Structure

```text
Airbnb-dashboard/
├── README.md             # Project overview (this file)
├── QUICKSTART.md         # 5-minute setup guide
├── INSIGHTS.md           # Business intelligence & key findings
├── DATA_DICTIONARY.md    # Metric and dimension definitions
├── CHANGELOG.md          # Version history and roadmap
├── CONTRIBUTING.md       # Contribution guidelines
├── LICENSE.md            # MIT License
├── .gitignore            # Git ignore configuration
│
├── images/               # Dashboard screenshots used in this README
└── AIRPNB_DASHBOARD.pbix # Power BI report (~195 MB, stored with Git LFS)
```

---

## 📚 Documentation

| File | Description |
|---|---|
| [QUICKSTART.md](QUICKSTART.md) | Setup in 5 minutes, first things to try, common use cases, FAQ, troubleshooting |
| [INSIGHTS.md](INSIGHTS.md) | Strategic findings: geographic concentration, pricing, satisfaction, seasonality, financial implications |
| [DATA_DICTIONARY.md](DATA_DICTIONARY.md) | KPI, geographic, pricing, quality, trust and review metric definitions; refresh cadence; data quality notes |
| [CHANGELOG.md](CHANGELOG.md) | v1.0.0 release notes, v1.1.0 planned enhancements, v2.0.0 ML roadmap, migration notes |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Code of conduct, pull request process, testing, documentation and performance standards |
| [LICENSE.md](LICENSE.md) | MIT License with attribution guide |

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/RUDRAPRAKASHDAS/Airbnb-dashboard.git
   cd Airbnb-dashboard
   ```
2. **Open the dashboard**
   - Install [Git LFS](https://git-lfs.com) first (`git lfs install`) so the large `.pbix` file downloads correctly
   - Open `AIRPNB_DASHBOARD.pbix` in Power BI Desktop
3. **Explore** — use the filters and the three report pages (Overview, Ratings, Review), then read [QUICKSTART.md](QUICKSTART.md) for a guided walkthrough.

---

## 🛠️ Tech Stack

- Microsoft Power BI Desktop
- Airbnb listings and reviews data (10 cities, 2008–2020)

---

## 🗺️ Roadmap

- **v1.0.0** – Initial release ✅
- **v1.1.0** – Planned enhancements
- **v2.0.0** – Machine-learning features

See [CHANGELOG.md](CHANGELOG.md) for details.

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

---

## 📜 License

Distributed under the MIT License. See [LICENSE.md](LICENSE.md) for details.

---

## 🙏 Acknowledgments

- Airbnb listing and review data sources
- Contributors and reviewers of this project

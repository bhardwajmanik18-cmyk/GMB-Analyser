# GMB-Analyser
A free Google Business Profile Scanner &amp; Analyzer that evaluates profile health, generates a score out of 100, identifies optimization gaps, and provides actionable local SEO recommendations through a responsive web app.
# Google Business Profile Scanner & Analyzer

A free web application that helps business owners analyze their Google Business Profile (formerly Google My Business), identify missing information, evaluate profile completeness, and discover opportunities to improve their local SEO.

## 🚀 Project Overview

The Google Business Profile Scanner & Analyzer is designed to make local SEO auditing accessible to everyone. Users can enter a business name, Google Maps profile URL, and publicly visible business information to generate a profile health report with a score out of 100.

The goal is to develop a practical, user-friendly tool that can eventually retrieve supported public business data automatically and provide meaningful optimization recommendations.

## ✨ Key Features

- **Profile Health Score:** Calculate a transparent score out of 100.
- **Business Information Audit:** Check primary category, contact details, location, and business hours.
- **Profile Completeness:** Evaluate business descriptions, services, products, and relevant attributes.
- **Review Analysis:** Assess available rating and review information and review-response practices.
- **Photo Audit:** Evaluate photo coverage, logo, and cover image status.
- **Website Check:** Identify whether a business website is provided.
- **Local SEO Recommendations:** Generate actionable suggestions based on missing or incomplete information.
- **Visual Dashboard:** Display category-wise scores, progress bars, warnings, and improvement priorities.
- **PDF Reports:** Allow users to print or save their audit report as a PDF.
- **Responsive Design:** Support desktop, tablet, and mobile devices.
- **Free Access:** Keep the core auditing experience free to use.

## 🎯 Project Goals

1. Build an accessible free tool for small businesses and local entrepreneurs.
2. Help businesses understand the completeness and quality of their profiles.
3. Provide clear recommendations instead of complicated SEO terminology.
4. Introduce automatic public profile data retrieval where supported.
5. Enable repeat scans and historical score comparisons in future versions.
6. Keep scoring transparent and distinguish profile health from actual Google search rankings.

## 🛠️ Planned Technology

- **Frontend:** HTML, CSS, JavaScript, or React.
- **Hosting:** GitHub Pages or another suitable free-tier static hosting service.
- **Public Business Data:** Google Places API, subject to API availability, billing, and usage policies.
- **Future Database:** Supabase or another suitable database for storing reports, if needed.
- **Future Authentication:** Google OAuth for optional owner-authorized features.

## 📊 Scoring System

The proposed audit score is based on weighted profile-health checks, including:

- Business identity and contact information
- Profile completeness
- Reviews and reputation
- Photos and visual content
- Profile activity and freshness
- Location and discovery information

Each check should have a clear scoring rule. Unknown information should be marked as unavailable rather than incorrectly treated as verified.

**Important:** The score is an independent audit metric. It is not an official Google score and does not guarantee improved rankings, traffic, calls, or customers.

## 🔌 Live Data Integration

The initial version can analyze user-entered information without an API key. Future versions may retrieve supported public business details using the Google Places API.

Private profile performance data, such as certain search impressions or customer interactions, requires appropriate authorization and API access.

The application must not claim to have scanned live data unless that data was successfully retrieved and verified.

## 🔒 Privacy and Security

- Do not request unnecessary personal information.
- Do not expose API keys or secrets in frontend JavaScript.
- Use a secure backend or serverless function for protected API credentials.
- Clearly explain what data is collected and how it is used.
- Follow Google's applicable API terms, attribution, caching, and data-use requirements.

## 🗺️ Development Roadmap

- [x] Create the initial profile audit interface.
- [x] Implement a basic weighted scoring engine.
- [x] Add improvement recommendations.
- [x] Add a printable report.
- [ ] Connect live public business data.
- [ ] Improve scoring using retrieved and verified fields.
- [ ] Add historical scan comparisons.
- [ ] Add optional downloadable branded reports.
- [ ] Explore authorized profile performance analytics.
- [ ] Optimize accessibility, performance, and mobile usability.

## ⚠️ Disclaimer

This is an independent project and is not affiliated with, endorsed by, or officially associated with Google. Google Business Profile is a Google product. Audit results depend on the data available and the information provided by the user.

## 📄 License

This project can be released under the MIT License if the repository owner chooses that license. Add a `LICENSE` file before presenting the project as officially MIT-licensed.

## 🤝 Contributions

Contributions, feature suggestions, bug reports, and improvements are welcome. Please open an issue or submit a pull request to help improve the tool.

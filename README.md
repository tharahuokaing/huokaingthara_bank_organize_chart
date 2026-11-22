# Huokaing Thara Bank — Organizational Chart

An interactive, bilingual (Khmer & English) HTML organizational chart displaying the leadership hierarchy, reporting flow, and role responsibilities for **Huokaing Thara Bank** (`ធនាគារ ហួកាំង ថារ៉ា`).

## Features

* **Multi-Tier Hierarchy Flow:** Visualizes reporting lines using vertical (`.flow-v`) and horizontal (`.flow-h`) CSS connectors across tiers:
  * **Governing Board:** `គណៈគ្រប់គ្រងធនាគារ` (`N/A`)
  * **Director:** `លោក SENG CHHAT (លោក សេង ឆាត)`
  * **Chief Executive Officers (CEOs):** `លោក LEN (លោក ឡែន)`, `លោក DOM (លោក ដំ)`, `លោក NAK (លោក ណាក់)`, and `លោក KUO (លោក គោ)`
  * **Department & Security / Marketing Chiefs:** `អ្នកនាង KIMMUY (គីម មួយ)`, `លោក JAV (លោក ចែវ)`, and `លោក HUOKAING THARA (ហួកាំង ថារ៉ា)`
* **Interactive Detail Modal:** Clicking any leader card opens a modal (`#leader-modal`) showing full bilingual duties and replacement notes.
* **Responsive Layout:** Uses Tailwind CSS utility classes and horizontal scroll support (`.overflow-x-auto`) so the chart remains readable across screen sizes.

## Project Structure

huokaing-thara-bank-org-chart/
├── index.html   # HTML layout, CSS flow connectors, and JavaScript modal logic
├── bank.jpg     # Optional bank logo placed alongside index.html
└── README.md    # Repository documentation
Getting Started
Clone or Download: Download index.html (and optionally bank.jpg) into a project folder.

Open in Browser: Double-click index.html or serve the folder with a local web server (such as the Live Server extension in VS Code).

Publish with GitHub Pages: Push the files to a GitHub repository, go to Settings > Pages, and select your branch to host the chart online.

Customizing Roles & Content
Card Summaries: Edit the text inside each tier card directly in index.html.

Modal Details (leadersData): Inside the <script> tag in index.html, update the leadersData object (title, roleEn, roleKm, dutyKm, and dutyEn) to reflect role updates or add new leaders.

Logo Image: Place bank.jpg in the same folder as index.html to display the header emblem; if missing, a fallback bank icon renders automatically.

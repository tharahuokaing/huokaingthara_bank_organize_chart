# Huokaing Thara Bank — Organizational Chart

An interactive, bilingual (Khmer & English) HTML organizational chart displaying the leadership hierarchy, reporting flow, and role duties for **Huokaing Thara Bank** (`ធនាគារ ហួកាំង ថារ៉ា`).

## Features

* **Top & Middle Hero Banner:** Centers `bank.jpg` at the top of the page above the organizational chart title.
* **Multi-Tier Reporting Flow:** Connects tiers using vertical (`.flow-v`) and horizontal (`.flow-h`) CSS lines:
  * **Tier 1 — Governing Board:** `គណៈគ្រប់គ្រងធនាគារ` (`Bank Management Board`)
  * **Tier 2 — Director:** `លោក SENG CHHAT (លោក សេង ឆាត)`
  * **Tier 3 — CEOs & Vice Presidents:** `លោក LEN (លោក ឡែន)`, `លោក DOM (លោក ដំ)`, `លោក NAK (លោក ណាក់)`, `លោក KUO (លោក គោ)`, `Mr. Huo` (`VP`), and `Mr. B` (`VP`)
  * **Tier 4 — Department & Security / Marketing Chiefs:** `អ្នកនាង KIMMUY (គីម មួយ)`, `លោក JAV (លោក ចែវ)`, and `លោក HUOKAING THARA (ហួកាំង ថារ៉ា)`
* **Interactive Role Modal:** Clicking any card opens `#leader-modal` via `openLeaderModal(key)` to display bilingual titles and responsibilities.
* **Horizontal Scroll Support:** Wraps the chart in `.overflow-x-auto` with a `min-w-[1120px]` container so multi-column cards stay aligned across screen sizes.

## Repository Structure

huokaing-thara-bank-org-chart/
├── index.html   # Page markup, Tailwind/custom styles, and modal script
├── bank.jpg     # Bank logo image used in header, hero banner, and favicon
└── README.md    # Project documentation
Setup & Usage
Add Files: Place index.html, bank.jpg, and README.md in the same folder.

Run Locally: Open index.html in a web browser or use the Live Server extension in VS Code.

Host on GitHub Pages: Push the files to GitHub, open Settings > Pages, and publish from your selected branch.

Customizing the Code
Edit Card Text: Update the text inside each tier <div> in index.html.

Edit Modal Details (leadersData): Inside the <script> tag in index.html, update title, roleEn, roleKm, dutyKm, or dutyEn for any entry (board, seng_chhat, len, dom, nak, kuo, mr_huo, mr_b, kimmuy, jav, huokaing_thara).

Adjust Banner Size: Change w-40 h-40 sm:w-48 sm:h-48 on the hero logo container in index.html to resize bank.jpg.


#### How to Implement:
1. Create a file named `README.md` in the root of your project folder.
2. Paste the Markdown block above and save the file.
3. Commit and push `README.md` along with `index.html` and `bank.jpg` to your GitHub re

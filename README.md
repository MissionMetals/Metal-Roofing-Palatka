# metalroofingpalatka.com — Mission Metals Palatka site

## ⚠️ Temporary phone
(352) 720-9286 / tel:3527209286 is a PLACEHOLDER. Replace every instance (all 3 HTML files + schema "+1-352-720-9286") with the CallRail number:
`grep -rn "555-0100\|5550100" .`

## Upload to GitHub
1. Create repo (e.g. MissionMetals/Metal-Roofing-Palatka), public.
2. Add file → Upload files → drag ALL contents of this folder (index.html, services.html, contact.html, CNAME, robots.txt, sitemap.xml, assets/ folder). Commit to main.
3. Settings → Pages → Deploy from a branch → main / (root) → Save.
4. Settings → Pages → Custom domain should show metalroofingpalatka.com; tick Enforce HTTPS once available.

## Namecheap DNS (Advanced DNS)
- A @ 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
- CNAME www → missionmetals.github.io.
- Then Search Console: Domain property + TXT record, submit sitemap.xml.

## Placeholders
Installer name/license are HTML comments (`{{INSTALLER_NAME}}`, `{{INSTALLER_LICENSE}}`) — fill in when partnered. Replace project photos with real Palatka jobs when available.

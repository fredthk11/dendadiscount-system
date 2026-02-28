# DendaDiscount System

Digital disciplinary record management system for student spotchecks (JDK / university setting).

## Features (Prototype)
- Create new spotcheck sessions
- Add classes/groups
- Scan student IDs via QR code
- Record violations (e.g. rambut panjang, tiada ID, selipar, etc.)
- Batch save violations to session
- Review summary & finalize

## How to Run (Local)
1. Clone or download repo
2. Open `testfile1/start_session.html` in browser
3. Follow flow: Start session → Dashboard → Add kelas → Scan

Live demo: [https://fredthk11.github.io/dendadiscount-system/testfile1/dashboard.html](https://fredthk11.github.io/dendadiscount-system/testfile1/dashboard.html) (once Pages enabled)

## Tech
- Pure HTML + JavaScript + CSS
- Uses html5-qrcode library for QR scanning
- Data stored in browser localStorage (no backend yet)

For full backend (PHP/MySQL), future version planned.

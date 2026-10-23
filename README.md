# IT Help Desk Ticket Management System

A responsive beginner portfolio project that simulates common IT help desk workflows using HTML, CSS, and vanilla JavaScript.

## Features
- Create and edit support tickets
- Automatically generate ticket IDs
- Categorize hardware, software, network/Wi-Fi, account/login, printer, and other issues
- Set priority and assign a technician
- Record troubleshooting notes and resolution / next steps
- Track Open, In Progress, and Resolved status
- Record ticket creation and resolution dates
- Dashboard counts for total, open, in-progress, resolved, and outstanding high-priority tickets
- Search tickets and filter by status or priority
- Export ticket data to CSV for Excel
- Save data in browser local storage
- Responsive desktop and mobile layout

## Run locally
1. Download or clone the repository.
2. Open `index.html` in a modern browser.
3. Create a ticket, assign a technician, add notes, change its status, and try CSV export.

No installation is needed.

## Publish with GitHub Pages
1. Push `index.html` and `README.md` to the `main` branch.
2. Open repository **Settings → Pages**.
3. Under build/deployment, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. Wait for the Pages URL to appear on the same settings page.

## Manual test checklist
- [ ] Create a ticket and confirm a new ID is assigned.
- [ ] Edit a ticket and save changes.
- [ ] Assign a technician and add troubleshooting notes.
- [ ] Add resolution details.
- [ ] Change a ticket to In Progress and then Resolved.
- [ ] Confirm dashboard counts update.
- [ ] Search by requester, ticket ID, issue, or technician.
- [ ] Filter by status and priority.
- [ ] Export a CSV and open it in Excel.
- [ ] Refresh the browser and check that tickets persist.
- [ ] Try the page at mobile width.
- [ ] Reset the sample data.

## Technologies
HTML5, CSS3, JavaScript, browser localStorage, CSV export.

## Portfolio summary
Built a responsive IT Help Desk Ticket Management System using HTML, CSS, and JavaScript. Implemented ticket creation and editing, technician assignment, priority and status tracking, troubleshooting and resolution notes, timestamps, dashboard metrics, search and filtering, CSV export, and browser-based persistence.

## Limitations and security
This is a front-end demo, not a production service desk. It has no authentication, backend, central database, email alerts, audit log, or role-based access control. Data is stored only in the current browser. Do not enter real personal data, passwords, or confidential company information.

## Future improvements
- Build a backend API and database
- Add secure authentication and role-based access
- Add comments / activity history and SLA tracking
- Add automated tests and deployment workflow

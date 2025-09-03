# hhaexchange+

<a href="https://www.hhaexchange.com.co">hhaexchange+</a> is a lightweight React app that demonstrates a practical workflow inspired by home-care operations: logging visit-related expenses (transport, supplies, training), auto-calculating totals, and generating printable receipts caregivers can submit to coordinators. It’s intentionally simple—no backend required—so teams can prototype policy changes or training scenarios quickly. Data is stored in the browser (localStorage) and can be exported via copy/paste or print to PDF using the built-in Receipt view. The UI favors accessibility (labels, keyboard navigation) and clarity (clean headers, inline validation). While **hhaexchange+** is not affiliated with any commercial platform, it mirrors common artifacts in care management—dates, categories, notes, and amounts—so it’s easy to tweak for demos, onboarding exercises, or internal workshops. The codebase is modular: a `Header`, a form for entry, a list with filters and totals, and a printable `Receipt` component. You can drop components into other training apps or expand with authentication, server sync, or reporting later. Use it to teach, to test new policies, or to gather feedback from field staff in minutes.

## Features
- Add, edit, and remove care-related expenses
- Inline validation and friendly error states
- Persistent storage via `localStorage`
- Search & filter by text, category, and date
- Auto totals (per list and per receipt)
- Printable receipt view (save as PDF)
- Responsive, accessible UI with keyboard support

## Technologies Used
- React 18 (hooks + functional components)
- Parcel bundler (zero config, custom folders supported)
- Plain CSS modules per component
- Browser `localStorage` for persistence
- Jest/Testing Library placeholder setup (test file included)

## Author
**Shana Brush** — a pragmatic, people-first engineer who loves mentoring and untangling tricky UX problems.  
- **Email:** shana598brush@outlook.com  
- **Bio:** Shana has 9+ years building React frontends and Node/Express backends for healthcare and education tech. She’s known for clear docs, clean abstractions, and a helpful, collaborative style.  
- **Focus:** Accessibility, data entry flows, and developer experience.  
- **Fun:** Weekend open-source sprints & teaching juniors modern React patterns.

## Getting Started
> You’ll need Node 18+ and npm.

**Clone the Repository:**
```bash
git clone https://github.com/<your-username>/hhaexchange-plus.git

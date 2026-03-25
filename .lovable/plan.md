
## Project 10 Hospital Mobile App — Implementation Plan

### What We're Building
A fully functional **mobile hospital app prototype** displayed inside an iPhone 16 frame in the browser. The app serves two roles — **Doctor/Staff** and **Patient** — with rich, interactive screens across both flows.

---

### Core Changes from Uploaded Code

#### 1. Branding — "SAGAR" → "PROJECT 10"
- Splash screen: **PROJECT 10 HOSPITAL**
- Login screen subtitle, role selection, profile screens, footer watermark
- All `SH-` UHID/ID prefixes → `P10-`

#### 2. Typography — Classic Serif Font System
We'll import and apply:
- **Playfair Display Italic & Bold** — headings, hospital name, section titles
- **Cormorant Garamond Italic & Regular** — doctor names, patient names, elegant labels
- **Libre Baskerville Italic & Regular** — body text, descriptions
- **Georgia / Times New Roman** — fallback serif stack
Applied via Google Fonts import in CSS, replacing the current `Plus Jakarta Sans` across all screens

#### 3. Emoji Replacement → Professional SVG Icons / Illustrations
Replace all emoji with clean, animated SVG icon components:
- 🏥 → Styled hospital cross / medical SVG logo
- 👨‍⚕️ → SVG doctor silhouette / avatar illustration
- 👤 → SVG patient avatar
- 🛏️, ❤️, 🧠, 🦴, etc. → Matching Lucide React icons (already installed)
- Navigation icons: house, calendar, bell, user, activity icons from Lucide
- Department icons: medical specialty SVGs
- SOS button: custom animated pulse SVG
- Stat cards: Lucide icons (Users, BedDouble, AlertTriangle, FileText)
- Vitals: Heart, Activity, Thermometer, Weight, Droplets icons

#### 4. Smooth Professional Animations
- **Splash screen**: Elegant fade-in with staggered entrance for logo + text
- **Screen transitions**: Smooth slide/fade between screens
- **Cards**: Subtle hover scale + shadow lift
- **Bottom nav**: Smooth icon scale on active state
- **Stat cards**: Number count-up animation on mount
- **Status badges**: Gentle pulse for "Critical" status
- **Buttons**: Ripple press effect
- **Loading bar**: Refined shimmer animation

---

### App Screens (All Preserved + Enhanced)

**Auth Flow**
- Splash → Role Selection → Login (Phone/Email/Biometric) → OTP → Dashboard

**Doctor Portal** (5 bottom nav tabs)
- Home Dashboard (stats, OPD summary, charts, quick actions)
- OPD Queue (patient list with status badges)
- Patient Detail (vitals, history, labs tabs)
- Prescription Writer (medicine search + digital signature)
- IPD Inpatients
- Video Consultations
- Analytics/Reports
- Leave Management
- Notifications
- Doctor Profile (settings, theme switcher)

**Patient Portal** (5 bottom nav tabs with SOS center)
- Home Dashboard (quick actions, upcoming appointments)
- Find Doctor by Department → Book Slot
- My Appointments
- Health Records
- Lab Tests
- Pharmacy
- SOS Emergency
- Video Consult
- Vitals Tracker (BP chart)
- Billing & Payments
- Notifications
- Family Members
- Patient Profile (info, health, settings, emergency tabs)

---

### Design Style
- **Color palette**: Deep navy + electric blue gradient (preserved)
- **3 themes**: Light / Semi-Dark / Dark (all functional)
- **iPhone 16 frame** with Dynamic Island + physical buttons
- **Classic serif typography** giving a premium, trustworthy medical feel
- **Clean, minimal cards** with subtle borders and glass-morphism effects
- **Professional medical tone** — no playful emojis, replaced with crisp Lucide icons


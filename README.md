# 🇳🇵 Nepo Super App Prototype

**A mobile-first, multi-service application concept designed for the Nepali community.**

This project is a single-file HTML/JavaScript prototype demonstrating the structure, UI/UX, and core service offerings of a "Super App," which combines multiple functionalities (like ride-hailing, news, shopping, and job boards) into a single, cohesive mobile experience.

-----

## 🚀 Key Features

The app is designed around a clean, mobile-optimized interface (using Tailwind CSS) and includes 10 primary feature modules, plus essential navigation services.

### Core Service Modules (10 Features)

| Icon | Module Name | Description | Database Status |
| :--- | :--- | :--- | :--- |
| \<i class="fas fa-car-side"\>\</i\> | **Nepo Driving** | Real-time ride-hailing requests (The only module with **Live Firebase** integration). | **LIVE/Public DB** |
| \<i class="fas fa-newspaper"\>\</i\> | **Nepo News** | Personalized news feed with local and national updates. | Mock Data |
| \<i class="fas fa-calendar-days"\>\</i\> | **Nepo Calendar** | Nepali date and festival reminders (Bikram Sambat). | Mock Data |
| \<i class="fas fa-hand-holding-medical"\>\</i\> | **Nepo Care** | Booking platform for home nurses, doctors, and caregivers. | Mock Data |
| \<i class="fas fa-tags"\>\</i\> | **Nepo Second-Hand Market** | Local listings for buying and selling used goods. | Mock Data |
| \<i class="fas fa-bag-shopping"\>\</i\> | **Nepo Online Shopping** | Tracking local e-commerce orders and deliveries. | Mock Data |
| \<i class="fas fa-passport"\>\</i\> | **Nepo Visa Check** | Status verification for international visa and immigration applications. | Mock Data |
| \<i class="fas fa-hand-holding-heart"\>\</i\> | **Nepo Donation** | Secure platform for donating to local causes and charities. | Mock Data |
| \<i class="fas fa-house-chimney"\>\</i\> | **Nepo Room Rent** | Listings for rooms, apartments, and commercial rental spaces. | Mock Data |
| \<i class="fas fa-briefcase"\>\</i\> | **Nepo Part-Time Job** | Local job board for part-time and freelance opportunities. | Mock Data |

### Navigation & Utilities

  * **My Wallet:** Overview of balance, top-up, and transaction history.
  * **Explore Local:** Discovery of nearby attractions, events, and community spots.
  * **Profile:** User details, security status, rewards points, and recent activity history.
  * **Weather Forecast:** Detailed 7-day weather outlook.

-----

## 🛠️ Technology Stack

This application is built as a single, fully responsive HTML file, making it extremely easy to deploy and view.

  * **Front-end:** HTML5, JavaScript (ES6+)
  * **Styling:** **Tailwind CSS** (via CDN) for utility-first styling.
  * **Icons:** **Font Awesome** (via CDN).
  * **Database (Live Feature):** **Firebase Firestore** (via CDN) for the real-time "Nepo Driving" feature, allowing multiple users to see new ride requests instantly.
  * **Authentication:** Firebase Anonymous Authentication (for demo purposes).

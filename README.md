# 🏨 Hotel Booking UI

A responsive **hotel booking UI** with secure authentication (login/signup with Google), nested routing, and an owner dashboard.  
Built with **React**, **TailwindCSS**, **React Router**, and **Clerk** for authentication.

---

## ⚡ Features
- 🛏️ Browse and book hotel rooms with an intuitive **Frontend UI**  
- 🧑‍💼 **Hotel Owner Dashboard** to view rooms  
- 🔐 Secure authentication with **Clerk** (login/signup with Google account)  
- 📅 View your bookings   
- 🖼️ Room images upload and gallery view  
- 💻 Fully responsive design for mobile, tablet, and desktop  
- ⚙️ Nested routing and clean project structure for scalable development  

---

## 🚀 Getting Started

Run the development server for the project:

```bash
# Install dependencies
npm install

# Start development server
npm run dev
````

**Notes:**

* You can use `yarn`, `pnpm`, or `bun` instead of `npm`.
* Make sure you have your **Clerk Publishable Key** in `.env` before starting:

---

### 🖥️ Frontend

Open [http://localhost:5173](http://localhost:5173) to view the app locally.
Edit [`src/App.jsx`](src/App.jsx) — the page auto-updates as you edit.

---

## 🧩 Routes Overview

**Public Routes:**

* `/` → Home
* `/rooms` → All Rooms
* `/rooms/:id` → Room Details
* `/my-bookings` → My Bookings

**Owner Routes (nested under `/owner`):**

* `/owner` → Dashboard
* `/owner/add-room` → Add Room
* `/owner/list-room` → List Rooms

---

## ⚙️ Environment Variables

Create a `.env` file in the root folder:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```
---

## 🌐 Live Deployment

The project is deployed via **Vercel**:
🔗 [Hotel Booking UI](https://react10-hotel-booking-ui.vercel.app/)

---

## 🛠️ Tech Stack

* **Frontend:** React, TailwindCSS, React Router
* **Authentication:** Clerk (supports Google login/signup)
* **Routing:** Nested React Router v7
* **Build Tool:** Vite

---

## 📝 Project Structure

```
src/
├─ assets/           # Images, icons, dummy data
├─ components/       # Reusable components (Navbar, Footer, Title, etc.)
├─ pages/            # Page components for routes
│  ├─ Home.jsx
│  ├─ AllRooms.jsx
│  ├─ RoomDetails.jsx
│  ├─ MyBookings.jsx
│  └─ hotelOwner/    # Owner dashboard pages
│     ├─ Layout.jsx
│     ├─ Dashboard.jsx
│     ├─ AddRoom.jsx
│     └─ ListRoom.jsx
├─ App.jsx           # Main app with routes
├─ index.css         # Global CSS
└─ main.jsx          # Entry point with ClerkProvider
.gitignore
eslint.config.js
index.html
package-lock.json
package.json
vercel.json
vite.config.js
```

---

## 🖼️ Screenshot

<img width="1900" height="883" alt="image" src="https://github.com/user-attachments/assets/65dfde0a-173c-4876-ab5e-0b0adf7918b7" />

---

**Rekhta Menahil**

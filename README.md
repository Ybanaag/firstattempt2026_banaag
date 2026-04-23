Banaag
Project Details
Framework: Nuxt JS
Module: Alumni Hub: Document Request
1. Prerequisites

Before running the project, make sure the following tools are installed:

Install Node.js

Download from: https://nodejs.org/

Install the LTS (Long-Term Support) version.

Verify installation:

node -v
npm -v
2. Create the Project
npx nuxi@latest init alumni-hub
cd alumni-hub
npm install
3. Run the Development Server
npm run dev

Open in browser:

http://localhost:3000
4. Project Structure
layouts/
  default.vue

pages/
  index.vue
  alumni/
    dashboard.vue
    request-guide.vue

components/
  AppHeader.vue
  StatusCard.vue

app.vue
5. UI/UX Specifications
Branding
Primary Color: Jesuit Red (#8B0000)
Secondary Color: Royal Blue (#003366)
Design
Mobile-first layout
Rounded corners (2xl)
shadow-sm cards
6. Features
Tab switching in dashboard.vue
(Request History / New Requests)
Biometric Verification button (with success overlay simulation)
Lucide / Nuxt Icons for navigation
<NuxtLink> for seamless page transitions
<NuxtPage /> in app.vue for routing
7. AI Tools Used
ChatGPT – Architecture & code generation
GitHub Copilot – Refinement & fixes
8. Prompt

Pretend you are a Senior Nuxt 3 Developer at Ateneo de Davao University. You are tasked to build a mobile-first Alumni Hub web application for document requests. Follow the given structure and UI/UX specifications. Use Tailwind CSS for styling, Nuxt routing for navigation, and ensure all pages are seamlessly connected. Implement dashboard tabs, biometric verification simulation, and a guided request interface. The design should follow Jesuit Red and Royal Blue branding and use a modern card-based UI.

9. Screenshots

(Insert screenshots here)

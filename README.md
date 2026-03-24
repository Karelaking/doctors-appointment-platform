# Full Stack Doctors Appointment Platform with Next.js, Neon, Tailwind, Vonage, Shadcn UI Tutorial 🔥🔥

This project is a comprehensive platform for managing doctor appointments, built using modern web technologies. It includes features for user authentication, doctor onboarding, appointment scheduling, video calls, and more.

## Project Structure

```
components.json
eslint.config.mjs
jsconfig.json
next.config.mjs
package.json
postcss.config.mjs
proxy.js
README.md
actions/
  admin.js
  appointments.js
  credits.js
  doctor.js
  doctors-listing.js
  onboarding.js
  patient.js
  payout.js
app/
  globals.css
  layout.js
  page.js
  (auth)/
    layout.js
    sign-in/
      [[...sign-in]]/
        page.jsx
    sign-up/
      [[...sign-up]]/
        page.jsx
  (main)/
    layout.jsx
    admin/
      layout.js
      page.jsx
      components/
        pending-doctors.jsx
        pending-payouts.jsx
        verified-doctors.jsx
    appointments/
      page.jsx
    doctor/
      layout.js
      page.jsx
      _components/
        appointments-list.jsx
        availability-settings.jsx
        doctor-earnings.jsx
      verification/
        page.jsx
    doctors/
      layout.js
      page.jsx
      [specialty]/
        page.jsx
        [id]/
          layout.js
          page.jsx
          _components/
            appointment-form.jsx
            doctor-profile.jsx
            slot-picker.jsx
      components/
        doctor-card.jsx
    onboarding/
      layout.js
      page.jsx
    pricing/
      page.jsx
    video-call/
      page.jsx
      video-call-ui.jsx
lingo/
  metadata-dev/
    data.mdb
    lock.mdb
components/
  appointment-card.jsx
  header.jsx
  page-header.jsx
  pricing.jsx
  theme-provider.jsx
  ui/
    alert.jsx
    badge.jsx
    button.jsx
    card.jsx
    dialog.jsx
    input.jsx
    label.jsx
    select.jsx
    separator.jsx
    sonner.jsx
    tabs.jsx
    textarea.jsx
hooks/
  use-fetch.js
lib/
  checkUser.js
  data.js
  prisma.js
  schema.js
  specialities.js
  utils.js
prisma/
  schema.prisma
  migrations/
    migration_lock.toml
    20250515081608_create_modal/
      migration.sql
    20250517054209_credits/
      migration.sql
    20250517064915_vr/
      migration.sql
    20250520101140_update_appointments/
      migration.sql
    20250527063022_payout/
      migration.sql
    20250527071527_update_payout/
      migration.sql
public/
```

## Technologies Used

This project leverages the following technologies and tools:

- **Next.js**: A React framework for building server-side rendered and static web applications. It provides features like file-based routing, API routes, and server-side rendering.
- **Neon**: A serverless Postgres database designed for modern applications. It offers scalability, high availability, and efficient data storage.
- **Tailwind CSS**: A utility-first CSS framework that simplifies styling by providing pre-defined classes for layout, typography, and more.
- **Vonage**: A communication API used for integrating video calls and other real-time communication features.
- **Shadcn UI**: A modern component library for building user interfaces with a focus on accessibility and design consistency.
- **Prisma**: An ORM (Object-Relational Mapping) tool for interacting with the database in a type-safe and efficient manner.
- **ESLint**: A static code analysis tool to identify and fix problems in JavaScript code.
- **PostCSS**: A tool for transforming CSS with JavaScript plugins.
- **Sonner**: A notification library for displaying alerts and messages in the UI.
- **React**: A JavaScript library for building user interfaces, used as the foundation of the project.
- **Node.js**: A runtime environment for executing JavaScript code on the server.

These technologies work together to create a robust, scalable, and user-friendly platform for managing doctor appointments.

## Features

- **Authentication**: Secure user authentication for patients and doctors.
- **Doctor Onboarding**: Streamlined process for doctors to join the platform.
- **Appointment Scheduling**: Easy-to-use interface for booking and managing appointments.
- **Video Calls**: Integrated video call functionality for remote consultations.
- **Admin Dashboard**: Tools for managing doctors, payouts, and platform settings.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/doctors-appointment-platform.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to `http://localhost:3000`.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

For more details, visit the [tutorial](https://www.youtube.com/watch?v=ID1PRFF1dlw).

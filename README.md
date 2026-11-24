# Sahatek

A health platform for Algeria that connects patients, doctors, and labs. It has a web app and a WhatsApp bot that share one database.

## Features

- Appointment booking and reminders
- Prescriptions, with explanations in Arabic and Algerian Darija
- Lab results linked to patient records
- Doctor-to-doctor referrals
- Medical terminology dictionary with French-to-Arabic translation
- Admin dashboard (login, admins, users) with Arabic RTL support

## Tech Stack

- **Backend:** Node.js, Express
- **Database:** Neon (PostgreSQL)
- **File storage:** Supabase Storage
- **Frontend:** HTML/CSS/JS (Arabic and English, RTL)

## Project Structure

```
Sahatek/
├── sahatek/        # Main project folder
└── README.md
```

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/mawidtabib-maker/Sahatek.git
   cd Sahatek/sahatek
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file:
   ```
   DATABASE_URL=your_neon_connection_string
   PORT=3000
   ```
4. Start the server:
   ```bash
   npm start
   ```

## Team

- Supervisor: ياسين بوراس
- Members: شعنبي هاجر، لشخب وسيلة، مساعد بوعدي

## License

To be defined.

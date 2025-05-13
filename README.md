# Volz - Flight Booking Platform

Volz is a modern flight booking platform built with Next.js, TypeScript, and Tailwind CSS. It provides a seamless experience for users to browse and book flights from various airlines.

## Features

- 🛫 **Flight Booking**: Browse and book flights from multiple airlines
- 🏨 **Hotel Packages**: Optional hotel bookings with flight packages
- ✈️ **Airline Management**: Admin panel for managing airlines and offers
- 🎫 **Reservation System**: Track and manage flight reservations
- 📱 **Responsive Design**: Beautiful UI that works on all devices
- 🌙 **Dark Mode**: Modern dark theme for better user experience

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Database**: SQLite with Drizzle ORM
- **Authentication**: NextAuth.js
- **PDF Generation**: React-PDF
- **UI Components**: Custom components with Lucide icons

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- SQLite

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/volz.git
cd volz
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```
Edit `.env.local` with your configuration.

4. Initialize the database:
```bash
npm run db:push
# or
yarn db:push
```

5. Start the development server:
```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`.

## Project Structure

```
src/
├── app/                    # Next.js app router pages
│   ├── admin/             # Admin dashboard pages
│   ├── api/               # API routes
│   └── (routes)/          # Public pages
├── components/            # React components
│   ├── ui/               # Reusable UI components
│   └── modals/           # Modal components
├── db/                    # Database configuration
│   └── schema.ts         # Database schema
├── lib/                   # Utility functions
└── styles/               # Global styles
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run db:push` - Push database schema changes
- `npm run db:studio` - Open Drizzle Studio

## Admin Features

The admin dashboard (`/admin`) provides the following features:

- Manage airlines (add, edit, delete)
- Create and manage flight offers
- View and manage reservations
- Monitor booking statistics

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact:
- Email: info@volz.com
- Website: https://volz.com

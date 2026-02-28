# ✈️ Flight Tracker

A modern, real-time flight tracking application built with Next.js 16, React 19, and TypeScript. Features a beautiful glassmorphic UI with smooth animations and an intuitive search experience.

![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19.2.3-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue?style=flat-square&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.x-38B2AC?style=flat-square&logo=tailwind-css)

## 🌟 Features

- **Real-time Flight Search** - Search flights by flight number with instant results
- **Beautiful UI** - Modern glassmorphic design with smooth animations
- **Flight Timeline** - Visual representation of departure and arrival times
- **Timezone Support** - Displays times in local timezones for departure and arrival
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Fast Performance** - Built with Next.js 16 and React 19 for optimal speed

## 🚀 Demo

Search for flights like:
- `AA 456` - New York to London
- `UA 101` - San Francisco to Tokyo
- `DL 200` - Atlanta to Paris

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js 20.x or higher
- npm, yarn, pnpm, or bun

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd flight-lookup
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📦 Build for Production

```bash
npm run build
npm start
```

## 🏗️ Project Structure

```
flight-lookup/
├── src/
│   ├── app/
│   │   ├── page.tsx          # Main page component
│   │   ├── layout.tsx        # Root layout
│   │   └── globals.css       # Global styles
│   ├── components/
│   │   ├── FlightSearchForm.tsx   # Search form component
│   │   ├── FlightResults.tsx      # Results display component
│   │   └── components.css         # Component styles
│   └── lib/
│       └── api.ts            # Flight data API
├── public/                   # Static assets
├── package.json
└── tsconfig.json
```

## 🎨 Tech Stack

- **Framework:** Next.js 16.1.6 (App Router)
- **UI Library:** React 19.2.3
- **Language:** TypeScript 5.x
- **Styling:** TailwindCSS 4.x + Custom CSS
- **Linting:** ESLint with Next.js config
- **Compiler:** Babel React Compiler

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 🌐 API Integration

Currently uses mock data for demonstration. To integrate with a real flight API:

1. Update `src/lib/api.ts` with your API endpoint
2. Add environment variables in `.env.local`:
```env
NEXT_PUBLIC_FLIGHT_API_KEY=your_api_key
NEXT_PUBLIC_FLIGHT_API_URL=your_api_url
```

## 🎯 Features Breakdown

### Flight Search
- Flexible search supporting various formats (e.g., "AA456", "AA 456")
- Real-time validation and error handling
- Loading states with animated spinner

### Flight Display
- Departure and arrival information
- Flight duration calculation
- Timezone-aware time display
- Airport codes and city names
- Visual timeline with animated elements

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Icons from SVG path elements
- Inspired by modern flight tracking applications

## 📞 Support

For support, please open an issue in the GitHub repository.

---

Made with ❤️ using Next.js and React

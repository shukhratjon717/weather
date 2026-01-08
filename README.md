# Weather App

A **responsive weather application** built with **React + TypeScript**.  
This app allows users to view current weather, search for locations in South Korea, and manage favorite locations.

---

## How to Run the App

1. **Clone the repository:**

```bash
git clone https://github.com/shukhratjon717/weather.git
cd weather
2. Install dependencies:
npm install

3. Start the development server:
npm run dev
============
Features Implemented

Display current weather, minimum & maximum temperatures, and hourly forecasts.

Detect the user's current location on first launch.

Search for locations in South Korea (city, district, neighborhood).

Show a list of matching locations as the user types.

Show a message if weather information is not available for a location.

Add and remove up to 6 favorite locations.

Each favorite card shows location name (editable), current weather, and min/max temperatures.

Clicking a favorite card opens a detail page with full weather data.

Responsive design for desktop and mobile devices.

Technical Decisions

React + TypeScript: Strong typing ensures fewer runtime errors and easier maintenance.

Functional Components: Modular and cleaner code structure.

Feature-Sliced Design (FSD): Organizes code by feature, improving scalability and maintainability.

TanStack Query: Efficient API data fetching and caching for server-side data.

Tailwind CSS: Rapid, responsive, and utility-first styling.

Local JSON for Korean locations: Fast local search without extra API calls.

Tech Stack Used

Frontend: React + TypeScript

State Management & API Fetching: TanStack Query

Styling & UI: Tailwind CSS

Architecture: Feature-Sliced Design (FSD)

API: OpenWeatherMap, Public Data Portal, or any public weather API

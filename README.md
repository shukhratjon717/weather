# Weather App

A responsive weather application built with **React + TypeScript**.  
This app allows users to view current weather, search locations in South Korea, and manage favorite locations.

---

## How to Run the App

1. Clone the repository:

```bash
git clone https://github.com/shukhratjon717/weather.git
cd weather

Install dependencies:

npm install


Start the development server:

npm run dev


==============

Features Implemented

Display current weather, minimum & maximum temperatures, and hourly forecast

Detect user's current location on first launch

Search for locations in South Korea (city, district, neighborhood)

Show a list of matching locations as user types

Show a message if weather information is not available for a location

Add and remove up to 6 favorite locations

Each favorite card shows location name (editable), current weather, min/max temperatures

Clicking a favorite card opens a detail page with all weather data

Responsive design for desktop and mobile devices

Technical Decisions

React + TypeScript: Provides strong typing and maintainable modern React code

Functional Components: Cleaner, modular, and easier-to-read code

Feature-Sliced Design (FSD): Organizes code by feature, improves scalability and maintainability

TanStack Query: Efficient API data fetching and caching for server data

Tailwind CSS: Rapid and responsive styling

JSON for Korean Locations: Allows fast local search without extra API calls

Tech Stack Used

Frontend: React + TypeScript

State Management & API Fetching: TanStack Query

Styling & UI: Tailwind CSS

Architecture: Feature-Sliced Design (FSD)

API: OpenWeatherMap, Public Data Portal, or any public weather API

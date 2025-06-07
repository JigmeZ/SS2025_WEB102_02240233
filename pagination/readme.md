# Pagination Project

This project demonstrates efficient client-side pagination using React and [@tanstack/react-table](https://tanstack.com/table/v8). It generates a large dataset and provides a responsive, filterable, and sortable table UI with pagination controls.

## Features

- Fast client-side pagination for large datasets
- Column sorting and filtering
- Adjustable page size and direct page navigation
- Real-time table state display
- Clean and modular React code structure

## Technologies Used

- React
- TypeScript
- @tanstack/react-table
- Vite

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository or copy the project files.
2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

## Usage

- Use the pagination controls at the bottom of the table to navigate between pages.
- Change the page size using the dropdown.
- Sort columns by clicking on their headers.
- Filter data using the input fields below each column header.

## Project Structure

- `src/main.tsx`: Main React application and table logic.
- `src/makeData.ts`: Generates mock data for the table.
- `index.html`: Entry point for the frontend.

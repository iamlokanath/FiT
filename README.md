# Personal Finance Tracker

A web application for tracking personal finances built with Next.js, MongoDB, and Recharts.

## Features

- Add, edit, and delete transactions
- Categorize transactions
- View monthly expenses in a bar chart
- Track income and expenses
- Responsive design
- Form validation
- Real-time updates

## Prerequisites

- Node.js 14.x or later
- MongoDB Atlas account
- npm or yarn

## Getting Started

1. Clone the repository:

```bash
git clone <repository-url>
cd finance-tracker
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Create a `.env.local` file in the root directory and add your MongoDB connection string:

```
MONGODB_URI=your_mongodb_connection_string
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

4. Run the development server:

```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `/app` - Next.js app router pages and API routes
- `/components` - React components
- `/lib` - Utility functions and database configuration
- `/types` - TypeScript type definitions

## Technologies Used

- Next.js
- React
- MongoDB
- Tailwind CSS
- React Query
- Recharts
- React Hook Form
- Zod
- TypeScript

## Contributing

Feel free to submit issues and enhancement requests!

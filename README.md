# 💎 Cost Manager S&I 💎

A simple yet powerful expense tracking web application built with React and IndexedDB.

## Demo

Check out the live demo: [Cost Manager Demo](https://costmanager-w6qw.onrender.com/)

## Features

- 📝 Add and track your expenses with categories
- 📅 Filter expenses by year or month
- 📊 Visualize spending with interactive charts
- 📱 Responsive design for desktop and mobile
- 🗄️ Local data storage using IndexedDB (no backend required)
- 🔄 Real-time updates when adding or removing expenses

## Tech Stack

- **React** - UI library
- **Vite** - Build tool and development server
- **Material UI** - Component library
- **IndexedDB** - Client-side storage
- **Google Charts** - Data visualization

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cost-manager.git
   cd cost-manager
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

```
src/
├── components/           # UI components
│   ├── AddItem.jsx       # Form to add new expenses
│   ├── TableContents.jsx # Expense table with delete functionality
│   ├── ReportsAndGraphs.jsx # Reporting and visualization
│   └── ReportTable.jsx   # Detailed expense report table
├── App.jsx               # Main application component
├── idb.js               # IndexedDB database configuration
└── main.jsx             # Application entry point
```

## Usage

### Adding Expenses

1. Navigate to the "Add Item" section
2. Enter the expense category, description, price, and date
3. Click "Add Item" to save the expense to your local database

### Managing Expenses

1. View all your expenses in the table
2. Select items and click "Delete Selected Items" to remove them

### Viewing Reports

1. Choose between annual or monthly reports
2. Enter the year (and month if applicable)
3. Click "Show Report" to generate a pie chart and detailed breakdown
4. Click on categories in the report table to view detailed transactions

## Browser Support

The application works on all modern browsers that support IndexedDB:
- Chrome
- Firefox
- Safari
- Edge

## Development

### Building for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

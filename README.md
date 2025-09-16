# Simple CRUD Application

A lightweight Node.js + Express CRUD application with a minimal frontend interface.

## Features

- ✨ Create new items
- 📖 Read/view all items
- ✏️ Update existing items
- 🗑️ Delete items
- 🎨 Clean, responsive UI
- ⚡ Real-time updates

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Data Storage**: In-memory (array)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd crud-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/items` | Get all items |
| GET | `/items/:id` | Get item by ID |
| POST | `/items` | Create new item |
| PUT | `/items/:id` | Update item by ID |
| DELETE | `/items/:id` | Delete item by ID |

## Usage

1. **Add Items**: Type in the input field and click "Add Item" or press Enter
2. **Edit Items**: Click on any item name to edit it inline
3. **Delete Items**: Click the "Delete" button next to any item (with confirmation)

## Project Structure

```
crud-app/
├── server.js          # Express server with CRUD API
├── package.json       # Dependencies and scripts
├── public/
│   └── index.html     # Frontend interface
└── README.md          # Project documentation
```

## Future Enhancements

- [ ] Add data persistence with a database
- [ ] Implement user authentication
- [ ] Add item categories/tags
- [ ] Include item timestamps display
- [ ] Add search and filter functionality
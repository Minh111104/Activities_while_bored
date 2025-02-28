# I'm Bored - Activity Finder 🥱

This is a simple web application that helps users find fun activities to do when they are bored. It fetches random activities from the Bored API and allows users to filter activities based on type and number of participants.

## Features
- Displays a random activity on the home page.
- Allows users to filter activities based on type and participants.
- Uses Express.js for the backend.
- Uses EJS as a templating engine.
- Fetches data using Axios.

## Technologies Used
- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- Axios
- Body-parser
- HTML, CSS

## Installation
### Prerequisites
- Node.js installed

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/im-bored.git
    cd im-bored
    ```

2. Install dependencies:
    ```bash
    npm install
    ```
    
3. Start the server:
    ```bash
    node index.js
    ```
    
4. Open your browser and go to:
    ```bash
    http://localhost:3000
    ```

## Project Structure
```bash
📂 im-bored
├── 📂 public
│   ├── 📂 styles
│   │   ├── main.css
├── 📂 views
│   ├── index.ejs
├── index.js
├── package.json
├── README.md
```

## API Endpoints
- `GET /` - Fetches a random activity.

- `POST /` - Fetches an activity based on user-selected filters.

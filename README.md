# Feedback Form

This project is a simple feedback form built using React. It allows users to leave comments, rate their experience, and edit or delete their feedback.

## Features

- **Add Feedback**: Users can submit their name, comment, and a rating (1-5).
- **Edit Feedback**: Users can edit their previously submitted feedback.
- **Delete Feedback**: Users can delete their feedback.
- **Validation**: Ensures all fields are filled before submission.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mario-World/Build-with-React.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Build-with-React/FeedbackForm
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:5173
   ```

## JSON Server (Optional)

If you want to use `json-server` to simulate a backend:

1. Install `json-server` globally:
   ```bash
   npm install -g json-server
   ```
2. Create a `db.json` file in the project root with the following structure:
   ```json
   {
     "comments": []
   }
   ```
3. Start the server:
   ```bash
   json-server --watch db.json --port 4000
   ```

## Technologies Used

- React
- Vite
- JavaScript
- CSS

## Folder Structure

```
FeedbackForm/
├── public/          # Static assets
├── src/             # Source files
│   ├── App.jsx      # Main component
│   ├── main.jsx     # Entry point
│   ├── App.css      # Component styles
│   └── assets/      # Images and other assets
├── package.json     # Project metadata and dependencies
├── vite.config.js   # Vite configuration
└── README.md        # Project documentation
```

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

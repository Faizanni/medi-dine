# Medi-Dine Project

## Description
Medi-Dine is a web application that allows users to input their maladies, medications, and allergies through a user-friendly interface. The application is designed to run on a local server.

## Project Structure
```
medi-dine
├── public
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── server
│   └── server.js
├── package.json
└── README.md
```

## Getting Started

### Prerequisites
- Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.

### Installation
1. Open a terminal and navigate to the project directory:
   ```
   cd path/to/medi-dine
   ```
2. Run the following command to install the necessary dependencies:
   ```
   npm install
   ```

### Running the Application
1. Start the server by running:
   ```
   node server/server.js
   ```
2. Open a web browser and go to `http://localhost:3000` (or the port specified in `server.js`) to access the application.

## Usage
- Enter your maladies in the first text box.
- Enter your medications in the second text box.
- Enter your allergies in the third text box.
- The application will process the input accordingly.

## License
This project is licensed under the MIT License.
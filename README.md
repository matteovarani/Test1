# Node.js Web Application

A simple Node.js web application built with Express, serving as a starting point for developing more complex web applications.

## Features

- Express server configuration
- Static file serving
- RESTful API endpoints
- Single page application (SPA) support
- Development environment with auto-reload

## Project Structure

```
node-web-app/
│
├── public/               # Static files served by Express
│   ├── css/              # CSS stylesheets
│   │   └── styles.css    # Main stylesheet
│   └── index.html        # Landing page
│
├── .gitignore            # Git ignore file
├── package.json          # Project metadata and dependencies
├── README.md             # Project documentation
└── server.js             # Express server configuration
```

## Prerequisites

- Node.js (v12.x or later)
- npm (v6.x or later)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/node-web-app.git
   cd node-web-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

### Development Mode

Run the application with nodemon for automatic reloading during development:

```bash
npm run dev
```

### Production Mode

Run the application in standard mode:

```bash
npm start
```

The application will be available at: [http://localhost:3000](http://localhost:3000)

## API Endpoints

- `GET /api/status` - Returns the status of the API
  ```json
  {
    "status": "online",
    "message": "API is running"
  }
  ```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License - see the package.json file for details.

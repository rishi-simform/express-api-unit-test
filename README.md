# express-api-unit-test

This project provides a simple setup for building and testing an Express API using Mocha, Chai, and other testing utilities. It also includes coverage reporting using NYC.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rishi-simform/express-api-unit-test.git
   ```

2. Navigate to the project directory:

   ```bash
   cd express-api-unit-test
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

### Running the API

To start the API, use the following command:

```bash
npm start
```

The API will be accessible at `http://localhost:3001` by default.

### Development Mode

If you want to run the API in development mode with nodemon for automatic server restarts, use:

```bash
npm run dev
```

### Running Tests

To execute unit tests, use:

```bash
npm test
```

For watching file changes and rerunning tests, use:

```bash
npm run test:watch
```

### Test Coverage

To generate a coverage report, run:

```bash
npm run coverage
```

The coverage report will be available in the terminal, and detailed information can be found in the `coverage` directory.

## Project Structure

- `server.js`: Entry point for the Express application.
- `src/`: Directory containing the source code for the API.
- `src/tests/`: Directory containing Mocha test files.
- `node_modules/`: Directory containing project dependencies.
- `package.json`: Project configuration file.
- `README.md`: Project documentation.

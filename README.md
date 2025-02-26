# Fake API for Assessment App

This repository contains a fake API built using [json-server](https://github.com/typicode/json-server). It simulates backend endpoints for an assessment app.

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/fake-api-json-server.git
   cd fake-api-json-server
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Server**

   ```bash
   npm start
   ```

   The server will run on http://localhost:3000.

## Endpoints

- **GET /assessments**: Retrieves the list of assessments.
- **POST /assessments**: Creates a new assessment.

## Usage

The React Native app will use these endpoints to:

- Create assessments by sending POST requests to http://localhost:3000/assessments.
- Fetch assessments by sending GET requests to http://localhost:3000/assessments.

## Notes

This API uses an in-memory JSON database (db.json). Changes are not persisted between server restarts. For production, consider connecting to a real database.

## License

This project is licensed under the MIT License.

---

### **Instructions**

1. **Push this repository to GitHub:**
   - Create a new repository on GitHub (e.g., `fake-api-json-server`).
   - Push your local files using Git.

2. **Integrate with Frontend:**
   - In your React Native app, update the API URL to `http://localhost:3000/assessments` (or your network IP if testing on a device).

This setup gives you a complete fake API using json-server that you can use in your take-away assessment. Let me know if you need any further assistance!
# fullstack-dev-takehome

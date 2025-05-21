# Social Networking Platform

A social networking site built using React.js, JavaScript, and MySQL.

## Installation and Setup

### Prerequisites
- React.js and npm should be installed on your machine.
- MySQL Workbench and MySQL Server should be installed on your machine.

### Steps
1. Clone this repository to your local machine.
2. Install the MySQL schema:
   - Open MySQL Workbench.
   - Import the social.sql schema provided in the repository to your MySQL server.
3. Open the `api` folder in your code editor.
   - Navigate to the `connect.js` file.
   - Update the `db` object with your MySQL server credentials (host, user, password, and database).
4. Install dependencies:
   ```bash
   cd api
   npm install yarn
   yarn
   ```
   If `yarn` is not installed, it can be installed with `npm install -g yarn`.
5. Change directory to `client`:
   ```bash
   cd ../client
   npm install yarn
   yarn
   ```
6. Start the backend server:
   ```bash
   cd ../api
   yarn start
   ```
   If you see "api working!", the backend server is ready and ExpressNode is connected.
7. Start the frontend development server:
   ```bash
   cd ../client
   yarn start
   ```
   This will open the development server on your localhost.
   
Once the servers are up and running, you can access the site on your browser by navigating to `http://localhost:3000`.

## Contributing

Contributions are welcome!

## License

Distributed under the MIT License.

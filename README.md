# Getting started

1. Clone the repository <br />
   ```
   git clone https://github.com/bindu-1805/Secrets-app.git
   ```
2. Navigate to the project directory <br />
   ```
   cd Secrets-app
   ```
3. Install the dependencies <br />
   ```
   npm install
   ```
4. Use the sql files in this repository to create a database called 'secrets' and a table called 'users' in postgres.
5. Setup your google oauth credentials
6. Create a .env file in your project's directory and add the following <br />
   ```
   GOOGLE_CLIENT_ID="your_client_id"
   GOOGLE_CLIENT_SECRET="your_client_secret"
   SESSION_SECRET="TOPSECRETWORD"
   PG_USER="postgres"
   PG_HOST="localhost"
   PG_DATABASE="secrets"
   PG_PASSWORD="your_db_password"
   PG_PORT="5432"
   ```
7. Start the development server <br />
   ```
   nodemon index.js
   ```
8. Open your browser to see the result `http://localhost:3000` <br />

BMS Rwanda Online V2

Production-oriented MVP using Express + PostgreSQL.

## Local
Set DATABASE_URL to a PostgreSQL connection string, then:
npm install
npm start
Open http://localhost:3000

Default login:
admin / admin123

## Render deployment
1. Push this folder to a GitHub repository.
2. In Render create a PostgreSQL database.
3. Create a Render Web Service connected to the repository.
4. Build command: npm install
5. Start command: npm start
6. Add environment variables:
   DATABASE_URL = the Render Postgres internal connection string
   SESSION_SECRET = a long random secret
   NODE_ENV = production
7. Deploy.

IMPORTANT: Change the default admin password before real business use.

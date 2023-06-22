## MO Project

Prisma REST API using swagger for MO built using NestJS, Prisma, PostgreSQL and Swagger. 

### Installation

1. Install dependencies: `npm install`
2. Start a PostgreSQL database with docker using: `docker-compose up -d`. 
3. Apply database migrations: `npx prisma migrate dev` 
4. Start the MO:  `npm run start:dev`
5. Access the MO at http://localhost:3000/api

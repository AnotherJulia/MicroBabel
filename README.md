# MicroBabel

MicroBabel is a simple and quick startup container/app for PostgreSQL and Prisma databases.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Docker
- Node.js
- npm

### Installation

1. Setup the package:

```bash
npx @anotherjulia/microbabel my-db
```

2. Install dependencies

```bash
npm install
```

3. Startup the database

```bash
npm run start
```

This will start the Docker containers and the Prisma Client, and start up a Prisma Studio Interface.


# Refer App Backend

## Prerequisites

- **Node.js**: version 20 or higher is required.
- **Docker**: Ensure you have Docker installed to run the database and other services.
- **Make**: To simplify commands, a `Makefile` is provided.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Google-Developers-Groups-Pune/refer-app-backend.git

cd refer-app-backend

cp .env.example .env
```

### 2. Install Node.js Dependencies

Make sure you have Node.js 20 installed.

```bash
npm install
```
#### Install Docker

1. Install **Docker Desktop** from [here](https://www.docker.com/products/docker-desktop/).
2. For windows user use WSL-2 for docker setup

### 3. Start Database server in docker


```bash
make db
```

This will start the required database service in Docker.

### 4. Start the Development Server

To start the development server, use:

```bash
npm run dev
```


After WSL and Docker are set up, you can use `make` commands and run Docker just like on Linux.

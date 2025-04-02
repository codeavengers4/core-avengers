# FraudShield Galaxy

FraudShield Galaxy is a web application built with Vite, React, and ShadCN.

## Prerequisites

Ensure you have the following installed on your system:
- **Node.js** (Latest LTS recommended) [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn**
- **Git** (optional) [Download here](https://git-scm.com/)

## Setup Instructions

### 1. Clone the Repository
```sh
git clone https://github.com/codeavengers4/core-avengers.git
cd fraudshield-galaxy
```

### 2. Install Dependencies
Run:
```sh
npm install
```
or if using Yarn:
```sh
yarn install
```

### 3. Start Development Server
```sh
npm run dev
```
or
```sh
yarn dev
```
Your app should now be running at **`http://localhost:8080`**.

## Troubleshooting
- If `vite` is not recognized, install it manually:
  ```sh
  npm install vite
  ```
  or
  ```sh
  npx insatll vite
  ```
  
- If you face dependency issues, try:
  ```sh
  rm -rf node_modules package-lock.json && npm install
  ```
- Restart your terminal if necessary.

## Build for Production
To generate optimized files:
```sh
npm run build
```
or
```sh
yarn build
```


# Berlin Parking Finder - Root

This is the main project repository which includes submodules for the client and server.

## Getting Started

### Cloning the Repository

To clone this repository with its submodules and to ensure, that they are on the main branch, use the following commands:

```bash
git clone --recurse-submodules https://github.com/evankazadaiev/parkingfinder.git
cd parkingfinder
git submodule foreach 'git checkout main && git pull origin main'
```
### Installing dependencies

```bash
cd client
npm install
cd ../server
npm install
```

### Creating .env
```bash
cd client
touch .env
VITE_APP_API_URL=http://localhost:3000
```
### Running the Client
```bash
cd client
npm run dev
```

### Running the Server
```bash
cd server
npm start
```


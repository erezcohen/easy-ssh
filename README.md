# easy-ssh

A basic fullstack (React + Express) app meant to facilitate the [WeTTY](https://github.com/butlerx/wetty) usage.

This was setup in a couple of hours using simple-react-full-stack as a boilerplate as part of a Hackathon.

The app lets the user enter an IP of a desiered server and once clicking 'connect' he is redirected to a web based terminal.
This is done by spinning up a docker container in the backend running a Wetty server.

(This is of course an incompelte solution that does not include AuthN, cleaning up recourses etc').

## Setup

```bash
# Make sure you have node installed version 16.13 or newer.

# Clone the repository
git clone git@github.com:erezcohen/easy-ssh.git

# Go inside the directory
cd easy-ssh

# Install dependencies
yarn (or npm install)

# Start development server
yarn dev (or npm run dev)

# Build for production
yarn build (or npm run build)

# Start production server
yarn start (or npm start)
```

Note that this does not include the WeTTY setup.

For further info about the app see the original boilerplate at crsandeep/simple-react-full-stack.

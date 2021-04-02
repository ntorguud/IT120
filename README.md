# it120

# Install dependecies for server
npm install

# Install dependecies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server onl;y
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000


You'll need to create a keys_dev.js in the server config folder with:

module.exports = {
    mongoURI: 'YOUR_OWN_MONGO_URI',
    secret0rkey: 'YOUR_OWN_SECRET'

};
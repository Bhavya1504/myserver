# myserver
const http = require('http');

const server = http.createServer((req, res) => {
  console.log('bhavya.'); // Logging my name to the console
  res.end(); // Ending the response
});

server.listen(4000, () => {
  console.log('Server is running on port 4000.');
});

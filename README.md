# Node.js Server Hang

This repository demonstrates a common issue in Node.js where a long-running operation in the request handler blocks the event loop, causing the server to hang and become unresponsive.  The `bug.js` file contains the problematic code, while `bugSolution.js` provides a solution using asynchronous operations.
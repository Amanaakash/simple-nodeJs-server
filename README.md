# Node.js Server

This is a simple Node.js server that serves different endpoints.

## Overview

The server reads HTML templates and data from the file system, replaces placeholders in the templates with actual data, and sends the resulting HTML to the client.

## Setup

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies with `npm install`.
4. Start the server with `node index.js`.

## Endpoints

### Overview Page

The overview page can be accessed at `/` or `/overview`. This endpoint returns an HTML page with product details. The product details are fetched from a JSON file and inserted into HTML templates.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

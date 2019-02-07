# How to use

### Basic setup

1. Download/clone the repo
1. Open index.html in a browser to view it

### Full setup

Some reveal.js features, like external Markdown and speaker notes,
require that presentations run from a local web server. The following
instructions will set up such a server as well as all of the development
tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)
1. Clone this repository
1. Navigate to the folder
1. Install dependencies
   ```sh
   $ npm install
   ```
1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```
1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.

## License

MIT licensed

Copyright (C) 2018 Hakim El Hattab, http://hakim.se

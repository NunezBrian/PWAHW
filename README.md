
# Just Another Text Editor (J.A.T.E)

## Overview

Just Another Text Editor (J.A.T.E) is a Progressive Web Application (PWA) that allows users to write, edit, and save text with JavaScript syntax highlighting. This application supports offline functionality, enabling users to work seamlessly even without an internet connection. The app utilizes IndexedDB for local storage and Workbox for service worker management to ensure a smooth offline experience.


## Features

- **Client-Server Architecture**: Separates frontend (client) and backend (server) logic.
- **Offline Capabilities**: IndexedDB for persistent storage and Workbox for caching static assets.
- **PWA Installation**: Allows users to install the app on their desktop or mobile device.
- **Next-gen JavaScript**: Uses Babel to transpile modern JavaScript for compatibility.
- **Webpack Bundling**: Bundles JavaScript files and manages assets.
- **Service Worker**: Pre-caches static assets and subsequent pages for offline access.


## Installation

1. **Clone the Repository**

\`\`\`bash
git clone https://github.com/NunezBrian/TEXT-EDITOR-PWA.git
cd your-repo
\`\`\`

2. **Install Dependencies**

Install dependencies for both client and server:

\`\`\`bash
# Install root dependencies
npm install

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
\`\`\`

## Usage

1. **Start the Application**

Run the following command from the root directory to start the backend and serve the client:

\`\`\`bash
npm run start
\`\`\`

2. **Build for Production**

To build the application for production, navigate to the \`client\` directory and run:

\`\`\`bash
npm run build
\`\`\`

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Express**: Web framework for Node.js.
- **IndexedDB**: Browser-based database for storing structured data.
- **Workbox**: Libraries and tools for managing service workers.
- **Webpack**: Module bundler for JavaScript applications.

## License

This project is licensed under the MIT License.
# FWXAPI Web Interface

A modern web interface for interacting with FWXAPI, featuring real-time data monitoring, authentication management, and historical data analysis. Built with vanilla JavaScript and modern CSS.

## Features

- **Secure Authentication** (PKCE & Secret-based)
- Real-time data monitoring with configurable refresh rates
- Manual GET/POST requests
- Dataset exploration
- Historical data queries with time range selection
- Tabular/JSON data formatting
- Token lifetime visualization
- Responsive collapsible UI
``
## Installation

1. Clone this repository to your local system:
   ```bash
   git clone https://github.com/MDSonar/ICO.Web-App.git

2. Place the project folder in:
   ```bash
   Project Files > ICOINCS > GENESIS > Websites > AnyGlass

3. Access via :
   ```bash
   https://[local-host]/AnyGlass/[yourFolder]/index.html

4. Project Structure:
   ```bash
   main\
   |--styles\
   |    |--styles.css
   |--scrtipts\
   |    |--scripts.js
   |--index.html

## Configuration Notes
1. Upate API endpoint hostname in scripts.js
   ```bash
   const hostName = 'your-server';
2. Set your OAuth Credentials
   ```bash
   const CLIENT_ID = 'your-client-id';
   const CLIENT_SECRET = 'your-client-secret';
   const REDIRECT_URI = 'your-redirect-uri';


## Security Notes
This implementation user client-side credential for demonstration purpose only. For production use: 
1. Never expose secrets in client-side code
2. Implement proper token storage/rotation
3. User server-side authentication flow

## Software version
`ICONICS GENESIS64 10.97.3 CFR1`

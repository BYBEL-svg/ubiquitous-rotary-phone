# Bybel365 Documentation

## Overview
The Bybel365 website serves as an interactive platform to engage with biblical texts and resources.

## Setup Instructions
1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/BYBEL-svg/bybel365.git
   cd bybel365
   ```
2. **Install Dependencies**: 
   Ensure you have `node` and `npm` installed. Run:
   ```bash
   npm install
   ```
3. **Environment Variables**: 
   Create a `.env` file in the root directory and configure it with your settings. Sample:
   ```bash
   DATABASE_URL=your_db_url
   PORT=your_port
   ```

## Daily Update Procedures
1. **Pull Latest Changes**:  Start your day by pulling the latest updates from the main branch:
   ```bash
   git pull origin main
   ```
2. **Check Issues**: Review the issue tracker for any assigned tasks or bugs to fix.
3. **Daily Builds**: Run the daily builds using:
   ```bash
   npm run build
   ```
4. **Deploy Updates**: Follow the deployment guide stated below.

## Deployment Guide
1. **Build the Project**:
   ```bash
   npm run build
   ```
2. **Deploy to Server**:
   Use the following command to deploy your project:
   ```bash
   npm run deploy
   ```
3. **Monitor Deployment**: Check the logs for any issues:
   ```bash
   npm run logs
   ```

## Support
For any issues, please contact the support via the repository or email support@bybel365.com.

## License
This project is licensed under the MIT License.
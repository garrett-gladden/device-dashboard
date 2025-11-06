# Device Dashboard GitHub Pages

This project hosts the **Teams Call Quality Analytics** dashboard, which provides insights into call quality metrics using mock data. The dashboard is built with React and utilizes Chart.js for visualizing data.

## Project Structure

- **index.html**: The main HTML file containing the dashboard's structure, styles, and scripts.
- **README.md**: This documentation file, providing an overview and instructions for the project.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **CNAME**: Contains the custom domain for the GitHub Pages site.
- **.github/workflows/deploy-gh-pages.yml**: GitHub Actions workflow for automating deployment to GitHub Pages.
- **docs/**: Contains additional documentation and an alternative entry point.
  - **index.html**: An additional HTML file for documentation purposes.
  - **README.md**: Documentation specific to the `docs` directory.

## Setup Instructions

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/device-dashboard-gh-pages.git
   cd device-dashboard-gh-pages
   ```

2. **Install Dependencies**: 
   Ensure you have Node.js and npm installed. Then, run:
   ```bash
   npm install
   ```

3. **Run the Dashboard**: 
   You can use a local server to view the dashboard:
   ```bash
   npx serve .
   ```

4. **Deploy to GitHub Pages**: 
   Push changes to the `main` branch to trigger the GitHub Actions workflow for deployment.

## Usage

Open `index.html` in your browser to view the dashboard. The dashboard displays various metrics related to call quality, including video and audio quality, packet loss, jitter, and latency.

## Contributing

Feel free to submit issues or pull requests to improve the project.
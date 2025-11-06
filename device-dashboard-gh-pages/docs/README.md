# Device Dashboard GitHub Pages

This project hosts the **Teams Call Quality Analytics** dashboard, which provides insights into call quality metrics using mock data. The dashboard is built with React and visualizes various metrics and charts to help analyze call performance.

## Project Structure

- **index.html**: The main HTML file containing the dashboard's structure, styles, and scripts.
- **README.md**: Documentation for the project, including setup instructions and usage.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **CNAME**: Contains the custom domain for the GitHub Pages site.
- **.github/workflows/deploy-gh-pages.yml**: GitHub Actions workflow for automating deployment to GitHub Pages.
- **docs/index.html**: An additional HTML file that may serve as an alternative entry point or documentation.
- **docs/README.md**: Documentation specific to the `docs` directory.

## Setup Instructions

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/device-dashboard-gh-pages.git
   cd device-dashboard-gh-pages
   ```

2. **Install Dependencies**: 
   If you are using a package manager like npm or yarn, install the necessary dependencies (if applicable).

3. **Run the Dashboard**: 
   Open `index.html` in your browser to view the dashboard.

## Usage

- The dashboard displays various metrics related to call quality, including video and audio quality, packet loss, jitter, and latency.
- Use the filters to customize the data displayed on the dashboard.
- The charts provide visual representations of the metrics over time.

## Deployment

The project is automatically deployed to GitHub Pages using GitHub Actions. Any changes pushed to the main branch will trigger a deployment to the GitHub Pages site.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
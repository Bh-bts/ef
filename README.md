# GitHub to Slack Integration for Test Automation Reports
This repository provides a YAML file for automating the integration between GitHub Actions and Slack API, facilitating the transmission of test automation reports to Slack channels. The automation includes sending counts of passed, failed, and skipped tests, along with the success rate.

## Setup Instructions

### Generate the Slack API

Follow these steps to generate the Slack API:

1. Navigate to the Slack API website.
2. Click on "Your Apps" to access your Slack apps dashboard.
3. Create a new app by selecting "Create New App."
4. Choose the "From scratch" option and provide the app name.
5. Select your workspace and click "Create App."
6. Enable "Incoming Webhooks" and add a new webhook to your workspace.
7. Authorize permissions and select the channel for sending messages.
8. After approval, you'll receive the Slack Webhook URL.

### Repository Secrets Setup

To connect the Slack API with your GitHub repository, follow these steps:

1. Go to setting of your repository
2. Select "Secrets and variables" from the side menu of the repository settings.
3. In the "Secrets" section, click on "New repository secret".
4. Add the SLACK_WEBHOOK_URL secrets.
5. Click on "Add secret" to save it.

## Usages
This repository's YAML file automates the transmission of test automation reports to Slack using GitHub Actions. It specifically works with Maven Surefire reports.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve this integration.
# OctoThink
OctoThink is a GitHub App that integrate AIs into issues and pull requests.

## Features
- Command-based AI integration
  - `/question <question>`: Ask a question to the AI
  - `/consult <question>`: Ask multiple AIs to get broader perspectives.
  - `/review `(Pull Request): Ask multiple AIs to review the pull request.
  - `/inlineReview`(Pull Request): Ask multiple AIs to review the pull request with inline comments.
  - and more.

- Event triggers
  - Issue Opened: the AI will automatically add labels to the issue.
  - Issue Closed: the AI will summarize the issue.

## Setup
### 1. Deploy your backend Cloud Run service.
Check out the [backend](https://github.com/HosakaKeigo/OctoThinkBackend). Follow the setup guide in the README.

### 2. Deploy the GitHub App to Firebase Functions.
Check out the [githubApp](https://github.com/HosakaKeigo/OctoThinkFrontend). Follow the setup guide in the README.

## Demo

https://youtu.be/ap8pr5bRXV8
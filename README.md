# Playwright Test Automation Task

## Overview

Login with Github using Playwright

## Setup

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd <directory-name>
```
### Step 2: Install Dependencies

```bash
npm install
npx playwright install
```
### Step 3: Set Up Credentials

You can set your credentials in one of the following ways:

1. **Using environment variables directly:**
   ```bash
   GLITCH_USERNAME=your_github_username GLITCH_PASSWORD=your_github_password npx playwright test
   ```
2. **Using a .env file:**
Create a .env file in the root of the project and add:
   ```bash
   GLITCH_USERNAME=your_github_username GLITCH_PASSWORD=your_github_password npx playwright test
   ```
Then run:
   ```bash
   npx playwright test
   ```

# online-ide-testing

A minimal setup for testing and running applications inside an online IDE environment using the Atlan Automation Engine and the Atlan Application SDK.

## Usage

Follow the steps below to set up your application environment.

### 1. Clone the Automation Engine repository
```bash
  git clone https://github.com/atlanhq/atlan-automation-engine-app.git
```

### 2. Read the Automation Engine documentation

Navigate to the root of your cloned Automation Engine directory and read the README: atlan-automation-engine-app/README.md

This includes required environment variables and other setup details.

### 3. Run the automation engine
```bash
    cd atlan-automation-engine-app
    uv run poe start-deps
    cd automation_engine
    uv run main.py
```

## You’re ready!
Your environment is now set up. Begin building your application with the Atlan Application SDK inside your online IDE. Test your activities inside the automation engine ui(http://localhost:3000) and publish them by raising PR

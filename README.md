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

This includes required environment variables, runtime configuration, and other setup details.

### 3. Create a new application directory

```bash
  mkdir my-application
  cd my-application
```

### 4. Install the Atlan Application SDK

Install using one of the package managers below:

#### Option A — pip

```bash
  pip install atlan-application-sdk
```

#### Option B — uv

```bash
  uv add atlan-application-sdk
```

#### Option C — Poetry

```bash
  poetry add atlan-application-sdk
```

## You’re ready!

Your environment is now set up. Begin building your application with the Atlan Application SDK inside your online IDE.

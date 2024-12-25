# Router-Core

## Step 1: Install Go
Router Core requires Go to be installed on your machine.

1. **Download Go**
   Visit the [official Go downloads page](https://go.dev/dl/) and download the appropriate version for your operating system.

2. **Install Go**
   Follow the installation instructions provided for your platform.

3. **Verify Installation**
   ```bash
   go version
   ```
   Ensure the command outputs the installed Go version.

---

## Step 2: Install Node.js and npm

1. **Download Node.js**
   Visit the [Node.js official website](https://nodejs.org/) and download the LTS version.

2. **Install Node.js**
   Follow the installation instructions for your operating system.

3. **Verify Installation**
   ```bash
   node -v
   npm -v
   ```
   Ensure both Node.js and npm versions are displayed.

---

## Step 3: Install Docker

1. **Download Docker**
   Visit the [Docker website](https://www.docker.com/products/docker-desktop/) and download Docker Desktop for your platform.

2. **Install Docker**
   Follow the installation instructions provided by Docker.

3. **Verify Installation**
   ```bash
   docker --version
   ```
   Ensure the Docker version is displayed.

4. **Enable Docker Daemon**
   Make sure the Docker daemon is running.

---

## Step 4: Install jq
Router Core uses `jq` for parsing JSON files.

1. **Linux**
   ```bash
   sudo apt-get update && sudo apt-get install -y jq
   ```

2. **MacOS**
   ```bash
   brew install jq
   ```

3. **Windows**
   Download the `jq` binary from the [official website](https://stedolan.github.io/jq/) and add it to your PATH.

4. **Verify Installation**
   ```bash
   jq --version
   ```
   Ensure the command outputs the installed `jq` version.

---

## Step 5: Install Make
`make` is required for running build scripts.

1. **Linux**
   ```bash
   sudo apt-get update && sudo apt-get install -y make
   ```

2. **MacOS**
   ```bash
   brew install make
   ```

3. **Windows**
   Install `make` using a package manager like [Chocolatey](https://chocolatey.org/) or [Scoop](https://scoop.sh/).
   ```bash
   choco install make
   ```

4. **Verify Installation**
   ```bash
   make --version
   ```
   Ensure the command outputs the installed `make` version.

---

## Step 6: Clone the Router Core Repository

1. **Install Git** (if not already installed):
   ```bash
   sudo apt-get install git
   ```

2. **Clone the Repository**
   ```bash
   git clone https://github.com/router-protocol/router-core.git
   ```

3. **Navigate to the Repository**
   ```bash
   cd router-core
   ```

---

## Step 7: Install Other Dependencies

Navigate to the project directory and install the necessary Node.js dependencies:
```bash
npm install
```

---

## Final Step: Verify Everything is Set Up

Run the following command to ensure all prerequisites are installed:
```bash
make test
```
This will test the setup and output the results.

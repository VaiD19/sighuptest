# sighuptest

STEP 1 - Install Docker Compose

## Prerequisites

Before installing Docker Compose, ensure you have Docker installed on your system. Docker Compose relies on Docker Engine to function.

## Installation Steps

### 1. Download Docker Compose

The preferred method to install Docker Compose is to download the binary from the official Docker GitHub repository. You can use the following command to download the latest stable release:

```bash
sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```

### 2. Apply Executable Permissions

Once the binary is downloaded, apply executable permissions to the Docker Compose binary:

```bash
sudo chmod +x /usr/local/bin/docker-compose
```

### 3. Verify Installation

To verify that Docker Compose is installed correctly, you can run the following command to check the version:

```bash
docker-compose --version
```

If everything went wright, this command should output the installed version of Docker Compose.

Congratulations! You have successfully installed Docker Compose on your system.

---

It ain't much, but is honest work

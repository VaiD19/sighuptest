# sighuptest

What follows is a simple guide on how to run a basic httpd container with docker compose:

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

---

STEP 2 - Run the sighuptest sample httpd container

Create a New Folder:
First, create a new folder and pull all the files in this repository. You can create a new folder using the mkdir command:

```bash
mkdir sighuptest
```

Navigate into the newly created folder using the cd command

Now, you can use the 
```bash
sudo docker-compose build
```
then the
```bash
sudo docker-compèose up -d
```
commands to build the image and start the container.

It ain't much, but is honest work

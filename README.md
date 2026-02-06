# Orchestra
The central hub for managing and deploying [a-partala](https://github.com/a-partala) microservices ecosystem.

## Overview
Orchestra is a coordination repository that uses Git Submodules to pull together independent services. It provides a unified Docker infrastructure, shared networking, and environment configuration for the entire system.

## Quick Start
```bash
# 1. Clone the repository with all sub-modules
git clone --recursive https://github.com/a-partala/orchestra.git

# 2. Move into the project directory
cd orchestra

# 3. Create a workable .env file from the template
cp .env.example .env

# 4. Spin up the entire ecosystem
docker-compose up --build
```

## Service Map
[Task](https://github.com/a-partala/task-service.git)

[User](https://github.com/a-partala/user-service.git)
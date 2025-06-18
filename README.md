# EvOps :whale:

## Development Notice

- This repository is simply a mirror of https://github.com/evops-sum25/evops.

- All development takes place in our organization:
  https://github.com/evops-sum25.

- Our progress (kanban) board: https://github.com/orgs/evops-sum25/projects/1.

## Quick Start

### How to run the application

- Clone the repository with all submodules.

  ```shell
  git clone --recurse-submodules https://github.com/IU-Capstone-Project-2025/evops.git
  ```

- Set up the [`.env`](/.env.example),
  [`backend/.env`](https://github.com/evops-sum25/evops-backend/blob/main/.env.example),
  and
  [`ml/.env`](https://github.com/evops-sum25/evops-ml/blob/main/.env.example)
  files.

- Run the app with Docker Compose.

  ```shell
  docker compose up --build
  ```

The services will be available on the following URLs:

- Back end: http://0.0.0.0:8080
- Website: http://0.0.0.0:3000

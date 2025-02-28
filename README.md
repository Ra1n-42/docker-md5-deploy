# docker-md5-deploy
is a Bash script that efficiently builds and pushes only the changed Docker images. It calculates checksums for specific directories and files (e.g., ``app``, ``frontend``, ``docker-compose.yml``, ``Dockerfile``) and triggers a rebuild only if changes are detected. This reduces unnecessary builds, speeds up deployment, and optimizes resource usage.

```PHP
Projekt/
├── app/
├── frontend/
├── mysql/
├── docker-compose.yml
├── deploy.sh
└── Dockerfile
``

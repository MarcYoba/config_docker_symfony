# config_docker_symfony
configuration pour conteneuriser une application symfony et le serveur mail

my-project/
├── docker-compose.yml
├── .env
├── web/
│   ├── Dockerfile
│   └── symfony/ (votre projet Symfony)
└── mailhog/
    └── Dockerfile (optionnel)

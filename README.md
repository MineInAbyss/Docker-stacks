<div align="center">

# Mine in Abyss Docker Stacks
</div>

Stacks we deploy on our server using docker-compose.

We manage them using Portainer, via its git import option. Our main stack hosting Portainer as well as other services like Traefik or OAuth is defined in the [ansible-in-abyss](https://github.com/MineInAbyss/ansible-in-abyss/blob/main/roles/containers/templates/compose.yml) repo. (ex. the `oauth@docker` middleware is configured there to protect most of our web services.)

## Environment

Each stack contains a sample environment file. Set it up in a `.env` file or service like Portainer.


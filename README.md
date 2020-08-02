# Docker MERN Stack

This is a project made up of docker containers to create a MERN (Mongoose, Express, React, Node) Stack Environment. The aim is to get going to making a fullstack web application as quick as possible which is why this project is perfect because it already features a frontend, a backend, a database ([MongoDB](https://www.mongodb.com/)) and a CSS Library ([Tailwind](https://tailwindcss.com/)). Future addons to this project will likely include a webserver (Apache and/or Nginx) and several improvements to the existing files.

## How to get started

Make sure you already have [Docker](https://docs.docker.com) installed and working. Then you only need to execute a `docker-compose up -d` inside of the cloned project's directory and wait for your containers to start up. Files for the backend and frontend are respectively found in the similarly named subfolders and you can modify the files as you would in a more traditional setup. Changed the values in the `.env` file as necessary. To restart any container, run a `docker ps -a` followed by a `docker restart <containerName>` or a `docker-compose restart` to restart all of them.

I also recommend [this tool](https://github.com/jesseduffield/lazydocker) if you're going to work a lot with Docker.

# Start server

install docker with docker compose

First run

`cp .env.example .env`

change PORT to your mc prot inside of the created .env

Then do a first start

`docker-compose up` or `docker-compose up -d` for a detached shell

# Add your own files

After the fist start shutdown the server by runing  `docker-compose down`

You can now replace the world dir with your own world.

Start the server again

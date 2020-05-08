# Start server

install docker with docker compose

First run

`cp .env.example .env`

change PORT to your mc port inside of the created .env

Then do a first start

`docker-compose up` or `docker-compose up -d` for a detached shell

# Add your own files

After the fist start shutdown the server by runing  `docker-compose down`

You can now replace the world dir in `./data` with your own world and other files you might need.

Start the server again

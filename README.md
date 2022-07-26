# Reproduce the error

1. Start Docker-compose with this command: `docker compose up`
2. Log in to the xnodejs Docker container: `docker exec -it xnodejs bash`
3. Now inside the xnodejs container start vite: `npm run vite`
4. Start the https server here `https://localhost:7777`
5. See that the client keeps reloading

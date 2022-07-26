# Reproduce the error

1. Start Docker-compose with this command: `docker compose up`
2. Log in to the xnodejs Docker container: `docker exec -it xnodejs bash`
3. Now inside the xnodejs container start vite: `npm run vite`
<<<<<<< HEAD
4. Start the https server here `https://localhost:7777/@vite/client`
6. See that the client keeps reloading
=======

**Apache** (on port 7777)  

4. Now go in your browser to `http://localhost:7777/@vite/client`
5. See that the default HTML page loads instead of the vite client

**Nginx** (on port 8888)  

6. Now go in your browser to `http://localhost:8888/@vite/client`
7. See that the correct JavaScript is loaded
>>>>>>> 1f4e36950b6b2f7cc9ad7187c1c2c0574d235ad1

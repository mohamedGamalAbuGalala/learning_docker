# General learning commands

---

- `docker ps` => Show the running docker images on my pc
- `docker build .` build the current image in this directory
- `docker run -it ${name_of_instance_or_id }` => get in docker image terminal
- `docker run -v /home/galala/Projects/learning_docker:/mnt -it a2a15febcdf3` **mount** the learning_docker folder into /mnt in docker image (mount means that the folder will be synced between docker image and system folder)

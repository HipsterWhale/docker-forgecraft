### Forgecraft

![Forge logo](https://raw.githubusercontent.com/Bahaika/docker-forgecraft/master/forge.png)

#### Usage

Simply start the container with a volume on `/minecraft`. The container will install all the files for minecraft/forge inside this folder and then, you'll be able to customize your installation with ease. You also can add JVM arguments directly to the container whil using the `docker run` command.

```
docker run -d \
  -v /mnt/volumes/minecraft:/minecraft \
  --name=minecraft bahaika/forgecraft
```

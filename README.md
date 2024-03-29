# How to Run Stable Diffusion in Docker

## Prerequisite
- Docker
- Docker-Compose

# Step -1 (Clone)

```
git clone https://github.com/souravsk/stable-diffusion-webui-cpu.git

```

# Step -2 (Build the image)

```
docker-compose build stablediff-cpu

```
# Step -3(Start the docker-compose)

```
docker start -a stablediff-cpu-runner
```
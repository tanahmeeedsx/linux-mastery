# Linux-Mastery — Day 03

## 1. `df -h`

**Purpose:** Check filesystem disk space usage.

```bash
df -h
```

Shows total, used, and available disk space in a human-readable format.

## 2. `lsof`

**Purpose:** Find processes using files or network ports.

```bash
sudo lsof -i :11434
sudo lsof -i :8081
```

- Port `11434`: Found Docker's port forwarding process for Ollama.
- Port `8081`: No matching process was found listening on this port.

## 3. Docker Container Management

### List Running Containers

```bash
docker ps
```

Shows currently running containers.

### List All Containers

```bash
docker ps -a
```

Shows all containers, including stopped containers.

### Stop a Container

```bash
docker stop ollama
```

Stops the container without deleting it.

### Start a Container

```bash
docker start ollama
```

Starts an existing stopped container.

### Restart a Container

```bash
docker restart ollama
```

Stops and starts the container again.

## Key Takeaways

- `df -h` checks filesystem disk space.
- `lsof` helps identify processes using network ports.
- `docker ps` lists running containers.
- `docker ps -a` lists all containers.
- `docker stop`, `docker start`, and `docker restart` manage container states.

**Status:** Completed

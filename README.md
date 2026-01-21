# Komga

A self-hosted application for managing komga.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/komga/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/komga" ~/.local/srv/docker/komga
cd ~/.local/srv/docker/komga
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install komga
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.

# Ansible Execution Environment: Nautobot

[![N|Solid](https://github.com/nautobot/.github/raw/main/profile/nautobot_logo.svg)](https://github.com/nautobot)

## Overview

This project aims to bring the ability to interact with Nautobot through the construct of an Execution Environment.

### 🐍 `Prep your Python environment`

I have included a Poetry file for anyone saavy enough to take advantage. For the uninitiated, Poetry helps replicate Python environments between users with a single file. You'll need to have Poetry installed on your machine, for most users that will be solved with `pip install poetry`.

1. install Python dependencies

```bash
poetry install
```

2. activate environment

```bash
poetry shell
```

## 🐳 `Executing the build`

build the container image with

```bash
ansible-builder build --tag ghcr.io/cdot65/ansible-ee-nautobot:latest
```

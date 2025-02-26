# Docker Kit

This repository provides a Docker environment to test the open-hotel project. While the original project is no longer under active development, this setup allows you to explore and test the implementation.

The environment includes:
- [Client](https://github.com/KZN-Ltd-Sti/open-hotel-client/)
- [Orion Emulator](https://github.com/KZN-Ltd-Sti/open-hotel-orion-emulator)

## Setup

Clone this repository with submodules:

```bash
git clone --recurse-submodules https://github.com/KZN-Ltd-Sti/open-hotel-docker-kit.git
```

Or if you've already cloned the repository:

```bash
git submodule init
git submodule update
```

Build and run:

```bash
docker-compose build
docker-compose up
```

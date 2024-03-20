based on: https://github.com/IfCodingWereNatural/minimal-nvim/tree/lunarvim

# Minimal Lunarvim Config and Docker

This repository contains a fairly minimal Lunarvim,
plus a Dockerfile to run the configuration in a container.

## Getting Started

To get started, clone the repository to your local machine:

```
git clone https://github.com/IfCodingWereNatural/minimal-nvim.git
```

### Prerequisites

You'll need to have Docker installed on your local machine to build and run the container.

### Building the Container

Use `./build.sh` to create the Docker image or just run the following command:

```bash
~$ docker build -t minimal-nvim .
```

This script will build the container and tag it with the name `minimal-nvim`.

### Running the Container

There is a helper script to start up the container.

```bash
~$ ./run.sh
```

This script will run the container and mount the `lvim/` directory as a volume,
so any changes you make to the files in `/root/.config/lvim` while in the
container, will also change the local files.

## LunarVim Configuration

The configuration includes the following plugins (and perhaps more, I dunno, I had chatgpt generate this readme):

- WIP

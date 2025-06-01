# Automata
Automations, automations everywhere.

## Table of Contents
- [Installation](#installation)
- [Requirements](#requirements)
- [Usage](#usage)
- [Resources](#resources)
- [License](#license)

## Installation
Follow the steps below to make use of Automata.

Clone this repository:
```bash
git clone https://github.com/airscripts/automata.git
```

## Requirements
- Docker: https://www.docker.com/

## Usage
In order to use the stuff found in this repository run:
```bash
bash init.sh
```
This will initialize the required stuff for spinning up you n8n instance.

After that just run a simple:
```bash
docker compose up
```

And everything will be available at port 5678 of your localhost.  
From now on, just import the automations in `automations` folder and have fun.

## Resources
- n8n: https://n8n.io/
- Docker: https://www.docker.com/

## License  
This repository is not licensed and is closed source.

## Installation

Clone the project:
```
git clone https://github.com/Nizhenhao-3/Leaphand_retarget.git
```

This repository contains submodules.
After cloning the project, make sure to initialize them with:
```
git submodule update --init --recursive
```

Install [uv](https://docs.astral.sh/uv/getting-started/installation/).

```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Create virtual environment.
```
uv sync
```
Activate virtual enviromeny.
```
source .venv/bin/activate
```

## Run Real time retargeting
```
sudo chmod 777 /dev/serial/by-id/*
python Leap_Hand_real_time_retarget.py
```




<!-- Create virtual environment.
```
uv sync
```

Install the package.
```
uv pip install -e .
``` -->

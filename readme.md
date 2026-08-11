# A site for Botany rules

The goal is a site that makes rules easier to look up and understand for
the board game Botany: A Victorian Expedition

Steps to serve this site locally are below:

## Set up Python

```shell
sudo apt install python3-full;
python3 -m venv ./.venv;
source ./.venv/bin/activate;
pip install --requirement requirements.txt;
```

## Start web server

```shell
zensical serve;
```

Alternatively, use the JetBrains run configuration:\
`zensical-serve`

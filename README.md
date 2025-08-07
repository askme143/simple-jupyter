# Jupyter Notebook with Docker Compose

A quick and easy setup for running Jupyter Notebook in a container environment, managed using Docker Compose.

# How to use

```bash
git clone https://github.com/askme143/simple-jupyter.git
cd simple-jupyter.git
echo "JUPYTER_TOKEN=<yout_token>" > .env
docker compose build
docker compose up -d
```

`/workspace` is the place where you can add your Jupyter notebooks. It is mounted to the local `./workspace` folder.

# License
Apache-2.0
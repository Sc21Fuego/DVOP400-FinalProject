# DVOP400-FinalProject

Personal website for DJ Harrison built as a static multi-page site.

## Run Locally

```bash
python3 server.py
```

Open http://127.0.0.1:80 in your browser.

## Run In Docker, listening on host port 3000

```bash
docker build -t dj-harrison-website .
docker run --rm -p 3000:80 dj-harrison-website
```

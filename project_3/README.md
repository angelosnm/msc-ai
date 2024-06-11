```bash
docker rm -f angelos-notebook
docker run --name angelos-notebook -d -p9999:8888 -v ./:/home/jovyan/msc-ai angelosnm/msc-ai:3
```

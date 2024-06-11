```bash
docker build . -t "angelosnm/msc-ai:3"
docker run --name angelos-notebook -d -p9999:8888 -v ./:/home/jovyan/ angelosnm/msc-ai:3
```

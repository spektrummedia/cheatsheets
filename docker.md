Kill
-----------

- Kill all running containers

```bash
docker stop $(docker ps -a -q)
```
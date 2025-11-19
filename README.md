# docker-electrs


### latest version: `v0.11.0`

[docker hub link](https://hub.docker.com/r/lnliz/electrs/)

usage:
```
$ docker run --volume $HOME/.bitcoin:/home/user/.bitcoin:ro \
             --volume $PWD/db:/home/user/db \
             --env ELECTRS_DB_DIR=/home/user/db \
             --env ELECTRS_ELECTRUM_RPC_ADDR=0.0.0.0:50001 \
             --env ELECTRS_MONITORING_ADDR=0.0.0.0:4224 \
             --rm -i -t lnliz/electrs:v0.11.0
```

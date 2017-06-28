# midithru-connect

```
usage: midithru-connect [-h] [-v] [-n NAME] [-a] [-da] [-c CONNECT]
                        [-d DISCONNECT]

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         shows the current version
  -n NAME, --name NAME  auto connects all clients available by given name
  -a, --all             auto connects all clients available
  -da, --disconnect-all
                        disconnects all clients
  -c CONNECT, --connect CONNECT
                        connects a client to midi through
  -d DISCONNECT, --disconnect DISCONNECT
                        disconnects a client off midi through
```

## Examples

### Connect all

```
$ midithru-connect -a
```

### Connect all FluidSynth clients

```
$ midithru-connect -n fluid
```

### Disconnect all

```
$ midithru-connect -da
```

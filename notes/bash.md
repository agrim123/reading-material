# Bash

## setfacl

> set file access control lists

```bash
$ setfacl -m u:agrim:rw /var/log/mylog.log
```

## Moving hidden files

```bash
$ shopt -s dotglob nullglob
$ mv source destination
```


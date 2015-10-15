# R-3.2 for FreeBSD ports

After installing, Follow the steps below for everything to work perfectly :)

1. Make a symlink for bash:
```
  # ln -s /usr/local/bin/bash /bin/bash
```
2. If you want install rJava download the tar source, create this shell script and run: (bsd make is differ to lnx make)

```bash
  #!/bin/sh
  wget http://mirrors.nics.utk.edu/cran/src/contrib/rJava_0.9-7.tar.gz
  export MAKE=gmake
  R CMD INSTALL rJava_0.9-7.tar.gz
```




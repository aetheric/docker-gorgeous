# Gorgeous

The ruby gem application "gorgeous", packaged in an alpine docker image.

## Usage

To use, either invoke it as you would any docker-based application, or use one of the scripts below to make things a little easier on the keyboard. After that, you should be able to just run `gorgeous --help` and get the help information.

### Linux
(/usr/bin/gorgeous)

```shell
#!/bin/sh
docker run -it --rm -v "$(pwd):/usr/work" aetheric/gorgeous $*

```

### Windows
(c:/scripts/gorgeous.cmd)

```cmd
@ECHO OFF
docker run -it --rm -v "%CD%:/usr/work" aetheric/gorgeous %*
```

If all goes to plan, it's that easy.


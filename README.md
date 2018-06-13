# Mackup using docker

Run:

```terminal
$ docker run -u $(id -u) --rm -e HOME -v $HOME:$HOME -it dmitryrck/mackup bash
```

Then follow the instructions in [lra/mackup](https://github.com/lra/mackup).

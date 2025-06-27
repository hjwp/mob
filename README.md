# How to install this fork instead of the real mob.sh


Install go:

```sh
brew install go
```

Clone this repo and build the binary:

```sh
git clone git@github.com:hjwp/mob.git
cd mob
go build
```


Install it somehow:

```sh
ln -s "$PWD/mob" ~/.local/bin/mob
```

Test it with

```sh
time mob start
```

and it should be order of 4s instead of 8s.


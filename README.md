# tig-docker
tig in a Docker Container

```
sudo docker run -t mcamuzat/tig -v `pwd`:/project
```

you can add the alias `dtig`
```
alias dtig="docker run -t  -v `pwd`:/project mcamuzat/tig"
```

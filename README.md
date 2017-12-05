### docker-git-alpine

A useful simple git container running in alpine Linux, especially for tiny Linux distro, such as RancherOS, which doesn't have a package manager.

### Installation
```
alias git="docker run -ti --rm -v $(pwd):/git dbrosy/docker-git-alpine"
```
### usage
```
git clone https://github.com/dbrosy/rancher-server.git
```
    
### Credits
All Credit to "github.com/BWITS" for this easy solution
I have customised for my needs, feel free to use
  



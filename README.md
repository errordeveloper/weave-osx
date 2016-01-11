## Dependencies

There a couple of small dependencies this script requires

  - `docker-machine` and `docker` (client)
  
Install them with Homebrew: `brew install docker docker-machine jq`

You will also need VirtualBox or VMWare Fusion installed.

You can also obtain [Docker Toolbox](https://www.docker.com/docker-toolbox), which will install VirtualBox for you.

## Installation

```
sudo curl --silent --location git.io/weave --output /usr/local/bin/weave
sudo curl --silent --location git.io/weave-osx --output /usr/local/bin/weave-osx # create the git.io URL once this is published
sudo chmod +x /usr/local/bin/weave
sudo chmod +x /usr/local/bin/weave-osx
```


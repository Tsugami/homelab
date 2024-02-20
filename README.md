# My Lab

## Installation

### Install Helm

```sh
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash
```

### Install Helmfile

1. See last release on https://github.com/helmfile/helmfile/releases

```sh
wget https://github.com/helmfile/helmfile/releases/download/x.x.x/helmfile_x.x.x_linux_amd64.tar.gz
````

```sh
tar -xvf helmfile_x.x.x_linux_amd64.tar.gz
```

```sh
chmod 777 helmfile
```

```sh
mv helmfile /usr/local/bin
```

```sh
helmfile --version
```

### Setup Cloudflared

https://developers.cloudflare.com/cloudflare-one/tutorials/many-cfd-one-tunnel/
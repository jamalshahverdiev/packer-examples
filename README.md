### Download packer and move to the PATH binery folder. Then validate pakcer.json file and execute it to build docker image:
```bash
$ wget https://releases.hashicorp.com/packer/1.4.0/packer_1.4.0_linux_amd64.zip
$ unzip packer_1.4.0_linux_amd64.zip && mv packer /usr/local/bin
$ packer validate packer.json
$ packer build -var 'tag=0.0.1' packer.json
```

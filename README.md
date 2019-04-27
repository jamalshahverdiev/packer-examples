``` bash
   $ wget https://releases.hashicorp.com/packer/1.4.0/packer_1.4.0_linux_amd64.zip
   $ unzip packer_1.4.0_linux_amd64.zip && mv packer /usr/local/bin
   $ packer validate packer.json
   $ packer build -var 'tag=0.0.1' packer.json
```

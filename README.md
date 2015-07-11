# Remote Development Setup
Puphpet-generated configuration for development

Needs added to /etc/hosts (or C:/Windows/System32/etc/hosts)

`192.168.56.101 local.drupalcampdemo www.drupalcampdemo.dev drupalcampdemo.dev`

The site is available at www.drupalcampdemo.dev or drupalcampdemo.dev

Docroot is `/var/www/drupalcampdemo`, and '/var/www/' is mapped to a local shared folder `.\sharedfolder`

SSH login to machine is available with `vagrant` user and private key at `puphpet\files\dot\ssh\id-rsa`
Mind that the key is created on the first `vargant up`
SSH is available at localhost:2222

So start the machine with 'vagrant up' and be a happy user.

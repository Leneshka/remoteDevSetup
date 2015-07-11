# Remote Development Setup
Puphpet-generated configuration for development

Needs added to `/etc/hosts` (or `C:/Windows/System32/etc/hosts`)

`192.168.56.101 local.drupalcampdemo www.drupalcampdemo.dev drupalcampdemo.dev`

The site is available at [www.drupalcampdemo.dev](www.drupalcampdemo.dev) or [drupalcampdemo.dev](drupalcampdemo.dev)

Docroot is `/var/www/drupalcampdemo`, and `/var/www/` is mapped to a local shared folder `.\sharedfolder`

SSH is available at `localhost:2222` with username `vagrant` user and private key at `puphpet\files\dot\ssh\id-rsa`
Mind that the key is created on the first `vargant up`


Also phpcs' standard directory `/usr/share/php/PHP/CodeSniffer/Standards/` is shared and linked with `./codeSnifferStandards`.


So start the machine with `vagrant up` and be a happy user. Use `vagrant halt` when you can't achieve more happiness this way.

Once you've changed `config.yaml`, use `vagrant provision` to reload settings.

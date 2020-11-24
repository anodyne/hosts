# Hosts

User contributed notes on various web host that play well or don't play with with Nova. Send your pull requests, no affiliate links!

## PHP Versions by Host
<http://phpversions.info/shared-hosting/>

## Nova 2

### Hosts that play nice

These guys work well with Nova 2 right out of the box.

- [A Small Orange](https://asmallorange.com/)
- [ArcusTech](https://www.arcustech.com/)
- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)
- [Digital Ocean](https://www.digitalocean.com/) ([One-Click LAMP Stack](https://www.digitalocean.com/features/one-click-apps/))
- [DreamHost](https://www.dreamhost.com/) - [server tweaks needed](https://github.com/anodyne/hosts/wiki/Dreamhost-tweaks)
- [Google Cloud Platform](https://cloud.google.com/)
- [HostGator](http://www.hostgator.com/)
- [Laravel Forge](https://forge.laravel.com/) + [Linode](https://www.linode.com/)
- [Laravel Forge](https://forge.laravel.com/) + [Digital Ocean](https://www.digitalocean.com)
- [Media Temple (dv)](https://mediatemple.net/)
- [Media Temple (grid)](https://mediatemple.net/)
- [Ploi](https://ploi.io) + [Linode](https://www.linode.com/)
- [Ploi](https://ploi.io) + [Digital Ocean](https://www.digitalocean.com)
- [Site5](https://www.site5.com/)

### Hosts that don't play nice

You should probably avoid these. It doesn't mean it's not possible, but will likely require support tickets to enable PHP modules like `mcrypt`, `mbstring`, and so on.

- [Go Daddy](https://godaddy.com) - doesn't meet server requirements
- [NameCheap](https://namecheap.com)
- [Rackspace Cloud](https://www.rackspace.com/cloud/) - issues with out-of-sync file timestamps and permissions
- [1and1.com](https://1and1.com) - please see [issue raised](https://github.com/statamic/hosts/issues/12) for more details.

## Nova 3

### Hosts that play nice

### Hosts that don't play nice

## Standard Dev Environments

Wide-spread dev environments that work well

- [Docker](https://www.docker.com/) - Both versions of Nova come with a full Docker setup
- [MAMP 3](https://www.mamp.info/en/)
- [Laravel Valet](https://laravel.com/docs/master/valet)
- [Laravel Homestead](https://laravel.com/docs/homestead) - Works well for Windows
- [Scotch Box](https://github.com/scotch-io/scotch-box) - 'A Vagrant LAMP Stack That Just Works'

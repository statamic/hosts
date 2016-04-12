# Hosts

User contributed notes on various web host that play well or don't play with with Statamic. Send your pull requests, no affiliate links!

## PHP Versions by Host
<http://phpversions.info/shared-hosting/>

## Hosts that play nice

These guys work well with Statamic right out of the box.

- [ArcusTech](http://arcustech.com)
- [A Small Orange](http://asmallorange.com)
- [DreamHost](https://www.dreamhost.com/) - [server tweaks needed](https://github.com/statamic/hosts/wiki/Dreamhost-tweaks)
- [HostGator](http://www.hostgator.com/)
- [Laravel Forge](https://forge.laravel.com/) + [Linode](http://linode.com)
- [Media Temple (dv)](http://mediatemple.net)
- [Media Temple (grid)](http://mediatemple.net)
- [ServInt](https://www.servint.net/)
- [Site5](http://www.site5.com/)
- [WebFaction](https://www.webfaction.com/)
- [Digital Pacific](http://www.digitalpacific.com.au/hosting/) - Sydney, Australia
- [Panthur](http://www.panthur.com.au/) - Sydney, Australia
- [DigitalOcean](https://www.digitalocean.com/) ([One-Click LAMP Stack](https://www.digitalocean.com/features/one-click-apps/))
- [Metanet](http://www.metanet.ch) - Switzerland
- [OVH](https://www.ovh.com/fr/index.xml) - northeastern France and near Montreal (Quebec, Canada). As of 2016/04/12, It offers PHP 7.0.5 and 5.6.20.

## Hosts that don't play nice

You should probably avoid these. It doesn't mean it's not possible, but will likely require support tickets to enabled PHP modules like `mcrypt`, `mbstring`, and so on.

- [Go Daddy](http://godaddy.com) - doesn't meet server requirements
- [NameCheap](http://namecheap.com)
- [Rackspace Cloud](http://www.rackspace.com/cloud/) - issues with out-of-sync file timestamps and permissions
- [1and1.com](http://1and1.com) - please see [issue raised](https://github.com/statamic/hosts/issues/12) for more details.

## Standard Dev Environments

Wide-spread dev environments that work well (e.g. MAMP)

- [MAMP 3](http://www.mamp.info/en/) (*MAMP 2 works as well*)
- A [Vagrant for Statamic](https://github.com/bradleyflood/vagrant-statamic) setup
- [Scotch Box](https://github.com/scotch-io/scotch-box) - 'A Vagrant LAMP Stack That Just Works'
- Jack's iMac

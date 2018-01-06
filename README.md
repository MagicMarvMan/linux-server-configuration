# Linux Server Configuration
## General
- **IP:** ```18.194.144.83```
- **Web-Application (reachable only under this url, since the OAuth services would not work with a pure IP):** [http://catalog.marvnet.de](http://catalog.marvnet.de) (pointing to my Lightsail instance)

## Installed software
- ufw (_iptables_)
- apache2
- mod_wsgi-py3
- postgresql
- fail2ban

## Configuration changes
I just added the WSGI-Settings to the ```Apache 000-default.conf```, added the ```psql```-Settings to my application and installed ```fail2ban```.

## Third-Party resources
I think, I only used resources from the (#installed-software)[Ubuntu-Sources] and OAuth-Providers (_Facebook_, _Google_ and _GitHub_)
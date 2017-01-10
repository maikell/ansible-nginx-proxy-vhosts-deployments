# ansible-nginx-proxy-vhosts-deployments
Background article can be found @ https://maikel.tiny-host.nl/it/letsencrypt.php

## prepare_proxy_webbackend 
This role deploys the Nginx packages + hardens bits and pieces, also creates a default folder. This is that there's always a landing page. Apart from this, it created the directory structure to request LetEncrypt TLS certificates
An example play book is prepary_proxy_webbackend.yml . 

## manage_vhosts_proxy
This role deploys the Nginx vhost configuration files. An example play book is manage_vhosts.yml

## Notes
If you can add contributions, I would be happy. Both roles are deployed already for months @ the Foundation Contrast Network (https://contrast.network) for >= 60 vhosts

## License
All code is copyrighted with the GNU GPL 2.0 license.


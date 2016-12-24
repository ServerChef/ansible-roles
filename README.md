# Ansible roles for ServerChef
## common
Updates and upgrades all packages, installs basic dependencies like git and curl and handles other common os tasks like setting locale, timezone and DNS servers
Required for: Development, Staging, Production
## apache
Installs apache from upstream (distro default) repos and configures common modules
Required for: Development, Staging, Production
## composer
Installs and configures php-composer for use with other roles
Status: TODO
Required for: Development, Staging, Production
## fail2ban
Installs and configures fail2ban for sshd, nginx, ftp and other common network programs
Status: TODO
Required for: Production
## iptables
Sets up filewall rules
Status: TODO
Required for: Staging, Production
## memcached
Installs and configures memcached
Status: TODO
Required for: Development, Staging, Production
## mysql
Installs and configures mysql (mariadb) and sets up databases
Status: Available
Required for: Development, Staging, Production
## nginx
Installs and configures nginx for default host
Status: Available
Required for: Development, Staging, Production
## php56-fpm
Installs and configures php-fpm from distro upstream
Status: Available
Required for: Development, Staging, Production
## php70-fpm
Installs and configures php7-fpm from php.net repo
Status: Available
Required for: Development, Staging, Production
## sshd
Configures ssh with saner and more secure options
Status: TODO
Required for: Production
## ssmtp
Sets up email forwarder for proper email delivery
Status: TODO
Required for: Staging, Production
## wordpress
Installs wordpress in given location
Required for: Development, Staging, Production
## wordpress-nginx
Configures nginx to use with WordPress
Status: TODO
Required for: Development, Staging, Production
## wordpress-apache
Configures apache to use with apache
Status: TODO
Required for: Development, Staging, Production

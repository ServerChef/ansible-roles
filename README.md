# Ansible roles for ServerChef
## common
Updates and upgrades all packages, installs basic dependencies like git and curl and handles other common os tasks like setting locale, timezone and DNS servers
## apache
Installs apache from upstream (distro default) repos and configures common modules
## composer
Installs and configures php-composer for use with other roles
## fail2ban
Installs and configures fail2ban for sshd, nginx, ftp and other common network programs
## iptables
Sets up filewall rules
## memcached
Installs and configures memcached
## mysql
Installs and configures mysql (mariadb) and sets up databases
## nginx
Installs and configures nginx for default host
## php56-common
Installs and configures php from distro upstream
## php56-fpm
Installs and configures php-fpm from distro upstream
## php70-common
Installs and configures php7 from php.net repo
## php70-fpm
Installs and configures php7-fpm from php.net repo
## sshd
Configures ssh with saner and more secure options
## ssmtp
Sets up email forwarder for proper email delivery
## wordpress
Installs wordpress in given location
## wordpress-nginx
Configures nginx to use with WordPress
## wordpress-apache
Configures apache to use with apache

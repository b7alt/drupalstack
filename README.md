drupalstack
===========

bash script to install a drupal stack based on a debian distro osted on a cloud (digitalocean, rackspace)

NGINX, PHP, APC, MYSQL

http://mybox:80  D7  (already installed with sqlite admin/test)
http://mybox:8080 Drupal Commons
http://mybox:8070 Tb Sirate Starter
http://mybox:8090 Drupal Spark
http://mybox:8060 Drupal8



## Usage

create a vm based on debian wheezy and then:

```
root@mybox:~# git clone http://github.com/b7alt/drupalstack
root@mybox:~# cd drupalstack
root@mybox:~# ./install
```

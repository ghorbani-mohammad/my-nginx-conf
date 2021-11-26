# My Nginx Conf File


This is nginx conf that I use for my server. As you could see I have created ci/cd for this so after each merge on master branch chnages will automatically deployed to my server.


## Features

- keep history of my changes in git repo
- change my config easily on the my code editor (VSCode)
- ci/cd enabled

## Usage Tutorial

Create a new dir like my_conf in 
```sh
/etc/nginx 
```
So the path of new dir will be
```sh
/etc/nginx/my_conf
```
Then clone this repo on that path by
```sh
git clone git@github.com:ghorbani-mohammad/my-nginx-conf.git .
```
Change content of /etc/nginx/nginx.conf to this:

```sh
include /etc/nginx/my_conf/nginx.conf;
```
Done! after each merge on master branch changes are automatically wil get by server and nginx will be reloaded.

## License

MIT


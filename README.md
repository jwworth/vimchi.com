# vimchi.com

This is the source code for the [Vim Chicago](http://vimchi.com/) Meetup group
official website, available here:

http://vimchi.com/

### Installation

Follow these steps:

```
$ git clone https://github.com/jwworth/vimchi.com
$ cd vimchi.com
$ middleman server
```

### Deployment

Setup an Ubuntu server with Nginx. A sample configuration is included in
`config/nginx/vimchi`. Then deploy with:

```
$ cp .env{.example,} # add your deploy target
$ rake deploy
```

### License

vimchi.com is released under the [MIT
License](http://www.opensource.org/licenses/MIT).

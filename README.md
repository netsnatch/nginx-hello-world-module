# ngx_http_limit_req_module for Nginx 1.10.3

## Introduction

This module serves as a learning exercise for me, and hopefully for
others too, when doing [Nginx](http://nginx.org) module development. 

I [stole](http://dominicfallows.com/2011/02/20/hello-world-nginx-module-3/)
the code and added some notes using mostly Evan Miller's
[Nginx Module Development Guide](http://www.evanmiller.org/nginx-modules-guide.html). Also
helpful is the
[translation](http://antoine.bonavita.free.fr/nginx_mod_dev_en.html)
of Vhalery Kholodov's
[Nginx Module Guide](http://www.grid.net.ru/nginx/nginx-modules.html)
done by [Antoine Bonavita](http://antoine.bonavita.free.fr/) that also
mantains a [Nginx Discovery](http://www.nginx-discovery.com/) blog to
document his journey on Nginx module development.

## Installation

   1. Configure Nginx adding this module with:
          
          ./configure (...) --add-module=/path/to/ngx_http_limit_req_module
       
   2. Build Nginx as usual with `make`.
 
## Further reading

 * English: You can go to the [Nginx Planet](http://planet.nginx.org/)
   and get a lot of Nginx related information.
  
 * Russian: The [Habrahabr Nginx Blog](habrahabr.ru/blogs/nginx/) a
   treasure trove of Nginx related discussions. Use google translate
   or Babelfish if you don't read Russian.
 
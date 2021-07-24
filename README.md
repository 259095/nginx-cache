<h1>wiremocknginxpocthingy</h1>

<h2>Cache</h2>

Needs a warm-up; cached files are stored in non-persistent `tmpfs` volume `/etc/nginx/cache`

URLs match directory structure in /usr/share/nginx/json

* http://localhost/api/v1 will return index.json from `/usr/share/nginx/json/api/v1`
* http://localhost/api/v2 will return index.json from `/usr/share/nginx/json/api/v2`

---

<h2>Useful reading</h2>

https://www.nginx.com/blog/nginx-caching-guide/

https://www.nginx.com/blog/nginx-high-performance-caching/#MechanicsofHTTPCaching

https://pollin14.github.io/jekyll/update/2018/07/26/micro-caching-with-nginx-and-memcached.html

https://www.digitalocean.com/community/tutorials/understanding-nginx-http-proxying-load-balancing-buffering-and-caching

https://www.digitalocean.com/community/tutorials/understanding-nginx-server-and-location-block-selection-algorithms

https://github.com/nginxinc/NGINX-Demos/tree/master/nginx-regex-tester
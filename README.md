<h1>Usage</h1>
URLs match directory structure in /usr/share/nginx/json e.g. 
* http://localhost/api/v1 returns index.json from /usr/share/nginx/json/api/v1
* http://localhost/api/v2 returns index.json from /usr/share/nginx/json/api/v2

Cache needs warm-up; files are stored in non-persistent tmpfs volume /etc/nginx/cache

<h1>Performance</h1>
https://pollin14.github.io/jekyll/update/2018/07/26/micro-caching-with-nginx-and-memcached.html

<h1>Guides</h1>
https://www.nginx.com/blog/nginx-high-performance-caching/#MechanicsofHTTPCaching
https://www.nginx.com/blog/nginx-caching-guide/
https://www.digitalocean.com/community/tutorials/understanding-nginx-http-proxying-load-balancing-buffering-and-caching

<h1>Troubleshooting</h1>
https://serverfault.com/questions/911921/debugging-nginx-cache-misses-hitting-high-number-of-miss-despite-high-proxy-val/912897
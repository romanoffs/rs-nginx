# What is this?
This project is based on Alpine Linux, the official nginx image and an nginx module made by Google that provides brotli compression, which also is made by Google.
<br>
Defautl install Curl, Wget, TimeZone
<h4>Nginx Version: 1.17.6</h4>

<h3>Change log</h3>

23.12.2019
- Update Alpine Image to version 3.11
- Update nginx to version 1.17.6
- Add CloudFlareProxy Configuration (see https://gist.github.com/romanoffs/29b981cccff51b0ea564e258e1ed2e85)

18.12.2019
- Update Alpine Image to version 3.10
- Update nginx to version 1.17.4
- Update BROTLI commit to e505dce68acc190cc5a1e780a3b0275e39f160ca

12.03.2018
- Update Alpine Image to version 3.8
- Update nginx to version 1.13.6

# How to use this image
As this project is based on the official [nginx image](https://hub.docker.com/_/nginx/) look for instructions there. In addition to the standard configuration directives, you'll be able to use the brotli module specific ones, see [here for official documentation](https://github.com/google/ngx_brotli#configuration-directives)

<h4>Notice</h4>
Default Time Zone: Europe/Kiev<br>
Nginx Mime Types: /etc/mime.types<br>
Fastcgi Params: /etc/fastcgi_params<br>
CloudFlare Proxy Config: /etc/cloudflare.conf<br>
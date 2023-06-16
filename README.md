RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://yit05.github.io/hesian/index.html$1 [R,L]

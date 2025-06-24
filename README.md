
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Outofsleep.github.io/resturant_project/index.html$1 [R,L]

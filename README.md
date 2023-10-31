Taste `Caddy` with `php-fpm` and `vscode` on `linux`

* Download Caddy
    * https://caddyserver.com/api/download?os=linux&arch=arm64
    * https://caddyserver.com/api/download?os=linux&arch=amd64

* Edit usergroup and username in `myapp.conf` then copy it to `/etc/php/7.x/fpm`
    * Otherwise, always `File not found` showing at the web browser.

* Run Caddy
```sh
./caddy_binary run --config ./Caddyfile
```

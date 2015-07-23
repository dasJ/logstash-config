# Logstash config

These are my private logstash configuration files. They are created for Arch Linux and the software I use. Descriptions are in the files.
As this is my first logstash setup, some of the configuration might be weird. In case you know anything better than me, please open up an issue (or pull request).

Please not that I don't take any responsibility if this breaks anything on your system.

## Installation
Backup your /etc/logstash/conf.d folder if you have anything in it.

    # rm -rf /etc/logstash/*
    # git clone https://github.com/dasJ/logstash-config /etc/logstash
    # systemctl start logstash


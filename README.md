AutoDokkuBackup
===============

AutoDokkuBackup, whose name is inspired by `automysqlbackup`, is a simple tool
for Dokku that allows you to automatically take daily, weekly and monthly
backups of MariaDB and PostgreSQL databases.

Note that it is still in beta. Therefore, you should be careful when using it
in production.

Installation
------------

```sh
sudo curl -L https://raw.githubusercontent.com/ecylmz/autodokkubackup/master/autodokkubackup -o /usr/local/bin/autodokkubackup
sudo chmod +x /usr/local/bin/autodokkubackup
```

License
-------

The GNU General Public License Version 3 (GPLv3) - see
[`LICENSE`](LICENSE) for more details

# symfony-docker-mysql-example
Empty project, could be useful for forking and continuing

Change container names in docker-compose.yml so that they would not be conflicting with other contaienrs on your machine.
Also change in default.conf fastcgi_pass value.

Set container name after @ in this .env line:
DATABASE_URL=mysql://root:notprod@stock_trader_mysql/symfony_db

If gives error that fails to connect to flex.symfony.com (probably it will because tried in another project from this)
get into container. Would be good to fix so that this would not be needed. Or at least add into automatic installation on init 

`make bash`
and run
`composer update symfony/flex --no-plugins --no-scripts
`


# azure-log-analytics-data-collector PHP Client
Azure Log Analytics Data Collector API Client for PHP. The probject was originally started in a repository, [azure-log-analytics-data-collector](https://github.com/yokawasa/azure-log-analytics-data-collector), then moved here as a dedicated repository for PHP client.

## Quickstart
Git clone this repository
```bash
git clone https://github.com/yokawasa/azure-log-analytics-data-collector-php.git
cd azure-log-analytics-data-collector-php
```

Download composer.phar and install client libraries autoload file:
```bash
curl -s https://getcomposer.org/installer | php
php composer.phar install
```

Then move to test dir and configure the following variables in test.php

```bash
$customer_id = '<Customer ID aka WorkspaceID String>';
$shared_key =  '<Primary Key String>';
```

Finally run test.php
```bash
php test.php
```

## Change log

* [Changelog](ChangeLog.md)

## Links

* [Azure Log Analytics Data Collecotr API](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-data-collector-api)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/yokawasa/azure-log-analytics-data-collector-php.

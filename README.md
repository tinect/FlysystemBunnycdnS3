# Flysystem2 Adapter for BunnyCDN Storage with S3

This adapter supports Flysystem with version 2 for BunnyCDN.  

## Installation

```bash
composer require tinect/bunnycdn-s3-flysystem-adapter:^2.0
```

## Usage

```php
use League\Flysystem\Filesystem;
use Tinect\Flysystem\BunnyCDN\BunnyCDNAdapter;

$client = new BunnyCDNAdapter('storageName', 'api-key-or-ftp-passwort', 'storage.bunnycdn.com', 'optionalSubfolder');
$filesystem = new Filesystem($client);
```

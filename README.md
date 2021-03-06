# Switchover Basic Laravel Example

A very basic example that shows how to use Switchover with Laravel (and Blade).

## Installation

```bash
composer install
```


## Configuration

Copy the `env.sample` to `.env` and add your SDK-Key of your environment (e.g. development).

```bash
# .env file

SWITCHOVER_SDK_KEY=<YOUR SDK KEY>
SWITCHOVER_CACHE_TIME=1 # Warning: 0 will cache forever
``` 

## Run

Run the artisan server

```bash
php artisan serve
```

## Usage

By default every new feature toggle is deactived by default. To see the feature in action you have to activate you flag in the enviroment.

## Where to find the SDK Key?

Go to your environment (e.g. development) and copy your SDK-Key:

![Switchover SDK Key](/doc/copy_sdk_key.jpg)
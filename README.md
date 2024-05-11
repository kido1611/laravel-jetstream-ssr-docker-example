# Laravel Jetstream SSR Docker

Run Laravel with Jetstream and InertiaJS(SSR) under Docker, FrankenPHP, and Bun.

See commit logs to check updated code.

## Requirements:

1. PHP
2. Composer
3. Bun
4. Docker

## How To

1. Clone repository
2. Run composer dependencies

```sh
composer install
```

3. Install node dependencies (using bun)

```sh
bun install
```

4. Build asset

```sh
vite run build
```

5. Run container

```sh
docker compose up -d
```

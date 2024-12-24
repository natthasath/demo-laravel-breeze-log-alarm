# 🎉 DEMO Laravel Breeze Log Alaram

Log Alarm is a Laravel package that enhances application logging by providing real-time monitoring, error detection, and instant notifications via Slack and email.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Create Project

```shell
composer create-project laravel/laravel example-app
```

- Install Package

```shell
composer require saasscaleup/laravel-log-alarm
```

- Configure Environment

```shell
cp .env.example .env
```

- Add Service Provider

```
Saasscaleup\LogAlarm\LogAlarmServiceProvider::class,
```

- Publish Config File

```
php artisan vendor:publish --provider="Saasscaleup\LogAlarm\LogAlarmServiceProvider"
```

- Migrate

``` 
php artisan migrate
```

### 🏆 Run

- [http://localhost:8000/](http://localhost:8000/) username : `admin` password : `admin`

```shell
php artisan serve
```

```shell
php artisan tinker
```

```
\Log::error('Log alarm');
\Log::error('Log alarm');
\Log::error('Log alarm');
\Log::error('Log alarm');
\Log::error('Log alarm');
```

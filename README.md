# Docker-PHP

![docker-php](./images/docker-php.png)

## Features

- Customize the configuration file
- Data is stored in the host
- xdebug support
- Contains commonly used php extensions
- React/PHP support(Event-driven, non-blocking I/O with PHP.Similar Node.js)
- swoole support

 
## Software Stack
- [x] MongoDB
- [x] Redis
- [x] MySQL
- [x] PHP 7.1 + PHP-FPM
- [x] Nginx with LuaJit

## Docs

[English](./docs/getting-started.md)
[简体中文](./docs/getting-started.Zh-cn.md)


## How to use it?

>If live behind the [GFW](https://zh.wikipedia.org/zh-hans/%E9%98%B2%E7%81%AB%E9%95%BF%E5%9F%8E) please read this post [Use Ali cloud](http://www.myfreax.com/use-aliyun-mirror-acceleration-on-docker/)


#### Requirements

- [Docker](https://www.docker.com/)

- [Docker-compose](https://github.com/docker/compose/releases)

>Windows and Mac users only need to install Docker

#### Getting started

```bash
git clone https://github.com/huangyanxiong01/docker-php.git
cd docker-php
composer install 
docker-compose up -d
```
Now,you can open http://127.0.0.1:3000/ in browser


#### Configure 

You can find the custom $software configuration file in `./docker/$software/etc/`


#### Data

You can find the  $software data file in `./docker/$software/data/`

#### Log

You can find the  $software log file in `./docker/$software/logs/`

#### More 

Please read [docs](./docs/getting-started.md) 

## TODO

- [ ] Write a php script that integrates with the framework(Such as Laravel,Symfony)
- [ ] Write usage documentation
- [ ] Test on Windows


## Change Log

[ChangeLog.md](ChangeLog.md)

## MIT License

Copyright (c) 2016 Freax

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

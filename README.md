# django_tutorial

ref: [はじめての Django アプリ作成](https://docs.djangoproject.com/ja/2.0/intro/tutorial01/)

Django のチュートリアルやります。

## Usage

```sh
# Instal packages
$ pip install -r requirements.txt

# Set up MySQL container
$ docker run --name mysql -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -d -p 3306:3306 mysql:5.6

# Create database
$ echo 'create database django_tutorial character set utf8' | mysql -h127.0.0.1 -P3306 -uroot
```

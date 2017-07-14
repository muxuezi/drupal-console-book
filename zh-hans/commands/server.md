# server
运行PHP内建的网站服务器

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal server [arguments]
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
address | IP地址:端口号

## commands.generate.doc.gitbook.messages.examples
* 用缺省地址和端口127.0.0.1:8088
```
$ Drupal服务器
```
* 用其他端口的地址
```
$ Drupal服务器127.0.0.1:8089
```
* 运行缺省地址参数，用--root选项来定义Drupal的root
```
$ Drupal --root=/var/www/drupal8.dev server
```
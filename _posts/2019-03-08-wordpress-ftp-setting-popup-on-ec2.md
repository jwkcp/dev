---
layout: post
title: AWS EC2에 워드프레스(wordpress) 설치 후 테마, 플러그인 등 설치, 삭제에 문제가 있을 때
tags: wordpress
comments: true
---

## 문제
EC2에 mysql-server, php-fpm, nginx(혹은 apache 등)을 설치하고 wordpress를 내려받아 설정 후 관리자로 워드프레스 페이지에 로그인하는데까지 성공했는데 테마, 플러그인 등을 삭제하거나 설치하려고 하면 ftp 혹인 sftp 관련 설정이 필요하다면서 팝업이 나타나는 경우가 있다. 

## 원인
웹서버가 워드프레스 파일이 있는 디렉토리에 접근 권한이 없어서 그렇다.

## 해결방법
웹서버를 띄운 사용자를 확인(ps -ef | grep nginx 혹은 ps -ef | grep httpd와 같이)해서 워드프레스가 있는 위치(var/wordpress와 같은)에 소유자를 변경해주면 된다. 예를 들어 -

```
chown -R www-data:www-data /var/wordpress
```


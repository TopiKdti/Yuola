# VLESS Heroku

## 概述

用于在 Heroku 上部署 vless+websocket+tls，部署时自动选择新的 alpine linux 和 xray v2ary。  

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2FTopiKdti%2FYuola)

### 路径

 `/app` 。

### 端口

`端口` 为 `443` 。

### UUID

`UUID` 默认为 `8a53a9e5-da63-4862-aee9-d7a490eb3dd` 可自行设置。 

%rrEventListener(  
%emsp;%emsp;"fetch",event => {  
%emsp;%emsp;%emsp;%emsp;let url=new URL(event.request.url);  


# imoocmall

> Imooc Mall


## 前端运行命令

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```


## mongodb导入全栈商城的goods和users数据

``` bash
> show dbs
admin 0.000GB
config 0.000GB
local 0.000GB
> use dumall
switched to db dumall



db.createCollection('goods')

db.createCollection('users')



root@izuf61quxhnlk8haul3v64z wj]# mongoimport --db dumall --collection goods --file dumall-goods
2018-12-01T22:49:00.049+0800 connected to: localhost
2018-12-01T22:49:00.064+0800 imported 17 documents
[root@izuf61quxhnlk8haul3v64z wj]# mongoimport --db dumall --collection users --file dumall-users
2018-12-01T22:49:16.513+0800 connected to: localhost
2018-12-01T22:49:16.529+0800 imported 1 document
```

## 后台运行命令

# node server\bin\www



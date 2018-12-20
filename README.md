# tieba-api
[![language](https://img.shields.io/badge/language-java-blue.svg)](https://www.java.com)
[![version](https://img.shields.io/badge/version-v0.0.6-orange.svg)](https://mvnrepository.com/artifact/com.github.libsgh/tieba-api/0.0.6)
[![GitHub license](https://img.shields.io/github/license/libsgh/tieba-api.svg)](https://github.com/libsgh/tieba-api/blob/master/LICENSE)


封装了百度贴吧的基本操作，登录，签到，回帖等
## 使用说明
maven项目在pom.xml中引用，非maven项目在[tieba-api](http://mvnrepository.com/artifact/com.github.libsgh/tieba-api/)下载最新版
```
<dependency>
    <groupId>com.github.libsgh</groupId>
    <artifactId>tieba-api</artifactId>
    <version>${lastVersion}</version>
</dependency>
```

## 更新记录
### 2018.12.20
- 解决验证码登录时,STOKEN获取错误的问题

### 2018.11.20
- 添加关注列表、粉丝列表、移除粉丝三个接口

### 2018.11.17
- 修复获取隐藏贴吧接口失效的问题

### 2018.06.26
- 添加取消关注一个贴吧的api

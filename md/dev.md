### dev环境配置

###### 如何获取AccessKey ID和 AccessKey Secret

[获取key](https://help.aliyun.com/knowledge_detail/38738.html)

+ spring cloud 配置非对称加密
````
    keytool -genkeypair -alias paascloud-key-store -keyalg RSA -dname "CN=Web Server,OU=China,O=www.howardliu.cn,L=Beijing,S=Beijing,C=China" -keypass paascloud-keypass -keystore server.jks -storepass paascloud-storepass
````
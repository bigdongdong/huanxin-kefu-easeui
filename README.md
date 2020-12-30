# huanxin-kefu-easeui
# 项目配置

```
  allprojects {
      repositories {
          ...
          maven { url 'https://jitpack.io' }  //添加jitpack仓库
      }
  }
  
  dependencies {
          //非androidx请选择不带'x'的版本
	  implementation 'com.github.bigdongdong:huanxin-kefu-easeui:latest.release' //添加依赖
	  
  }
```

## 学习过程中遇到的错误
#### 1. 执行run-android时显示 Unsupported major.minor version 52.0 错误
在android目录下，用记事本打开`build.gradle`，将`com.android.tools.build:gradle：`后的版本改为2.1.0。

#### 2. 构建完成后在Genymotion模拟器上显示的ip地址错误，连不到本地服务器。
模拟器menu -> Dev Settings -> Debug server host & port for device -> 改成127.0.0.1:8081

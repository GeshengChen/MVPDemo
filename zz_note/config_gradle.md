#### Butterknife gradle
项目
```gradle
classpath 'com.neenbedankt.gradle.plugins:android-apt:1.8'
```
模块
```gradle
apply plugin: 'android-apt'
apt 'com.jakewharton:butterknife-compiler:8.4.0'
compile 'com.jakewharton:butterknife:8.4.0'
```
=========================华丽的分割线==========================================

#### support design 控件
```gradle
compile 'com.android.support:design:24.2.1'
compile 'com.android.support:gridlayout-v7:24.2.1'
compile 'com.android.support:cardview-v7:24.2.1'
compile 'com.android.support:recyclerview-v7:24.2.1'
compile 'com.android.support:palette-v7:24.2.1'
```
=========================华丽的分割线==========================================
#### RxAndroid RxJava
```gradle
compile 'io.reactivex:rxandroid:1.2.1'
compile 'io.reactivex:rxjava:1.2.1'
```

* 使用lambda
在项目
```grdle
classpath 'me.tatarka:gradle-retrolambda:3.3.0'
```
在模块
```gradle
apply plugin: 'me.tatarka.retrolambda'
```
android节点下
```
compileOptions {
    sourceCompatibility JavaVersion.VERSION_1_8
    targetCompatibility JavaVersion.VERSION_1_8
    }
```

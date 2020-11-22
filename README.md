# KdTabLayout
一个Android TabLayout库，基于[FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout)，由原来的对Viewpager的支持更新为对Viewpager2的支持。

##依赖
首先在Project级build.gradle中添加远程仓库：
```groovy
 repositories {
        ...
        maven { url 'https://www.jitpack.io' }
}
```
然后在App级build.gradle中添加：
```groovy
dependencies{
        implementation 'com.github.gitlzq:KdTabLayout:1.3.2@aar'
}
```

##用法
```java
//关联ViewPager,用于不想在ViewPager适配器中设置titles数据的情况
public void setViewPager(ViewPager2 vp, String[] titles)

//关联ViewPager
public void setViewPager(ViewPager2 vp) 
```
  
## 感谢
* [FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout)

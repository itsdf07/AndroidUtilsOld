## AndroidUtils是用来干嘛的？
我认为每位Android开发者都希望能有一套属于自己的代码，这份代码肯定蕴含着程序员的心血、汗水与泪水。

所以这个即将成为我个人在代码生涯中的财富。
## 对于AndroidUtils有什么规划？
工具工具，既然是工具，那肯定是多方面的工具，那么就肯定是一个个独立的工具模块，而工具多了，就需要有一个工具箱，实现手提这样一个工具箱，就可以仗工具箱走IT路的理想！

## 对于AndroidUtils，里面会有什么工具？
* [alog](https://github.com/itsdf07/ALogUtils.git)
* [utils]()
* [okhttp3](https://github.com/itsdf07/AndroidHttpUtils.git)

## 对于module baseutils的使用
* 项目的build.gradle增加工具库的目标地址
```javascript
    repositories {
        jcenter()
        maven {
            url 'https://bintray.com/itsdf07/maven/'
        }
    }
```
* 需要依赖该工具库的Module中的'build.gradle'中添加'compile'依赖
```javascript
    dependencies {
        compile 'com.itsdf07:baseutils:1.0.1'
    }
```


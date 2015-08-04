## Android学习CheckList

总结的Android学习的一些Checklist，对于共性的知识，比如: Clean Code, Git使用等 未列举，但是却是项目中的基石。不正之处欢迎补充！

### 开发技能

#### Activity, Fragment 生命周期及用法

1. 生命周期简述，Activity与Fragment的联系与区别
2. 如何在Activity中打开一个Fragment
3. DialogFragment 弹窗式Fragment
4. 与Fragment相关组件， DataPicker, TimePicker

#### Android数据存储

1. SharedPreferences
2. Sqlite数据读取，有ORM的library可以使用
3. ContentProvider读取数据

#### Android中的资源

1. 如何绘制不同点击状态下的按钮，圆角矩形，圆形背景等；9 patch图片制作及原理
2. drawable资源，不同文件夹的意义，添加icon有什么注意事项
3. 学会使用Material Design的 Theme, Theme之间的继承
4. Style, 字体尺寸，颜色，样式。如何抽取出来，如何使用

#### Android Support Library

1. AppComptLibrary: com.android.support:appcompat
2. Android Design library: com.android.support:design
3. 更多关注：Android recycleview, cardview
4. 这些库的作用以及哪些常用的控件
5. Material Design: ActionBar用法

### 常用的库

1. ButterKnife
2. Retrofit
3. Eventbus
4. Picasso
5. ...

### others

1. 开发中的一些best practice. BaseAdapter 抽取出CardView
2. 使用ButterKnife， 初始化按钮，注册事件等


### 测试技能

#### Robolectric框架的使用

1. 项目中如何集成 Robolectric
2. 点击按钮，打开Intent(带有参数)， 如何测试
3. 点击按钮，弹框AlertDialog, 测试弹窗内容，测试弹框按钮点击后行为
4. 界面中文字，颜色，内容的测试
5. SharedPreference等数据的更改，如何测试

#### 功能测试

1. Google Espresso测试及集成
2. Appium/Calabash测试及应用

### 构建技能

1. Android中的Flavor
2. Android应用的签名以及proguard(混淆)
3. Android Gradle常见命令，build, assembel, test, install...
4. Lint error是什么，如何修复


### CI 技能

1. Jenkins安装及使用
2. 构建Android project， 单元测试/功能测试 pipeline


##参考文章

[Android Developer Training](http://developer.android.com/training/index.html)

[Google Material Design](http://www.google.com/design/spec/material-design/introduction.html)

[Android Design Support Library](http://android-developers.blogspot.hk/2015/05/android-design-support-library.html)



 



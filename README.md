dview-colors
![Release](https://jitpack.io/v/dora4/dview-colors.svg)
--------------------------------

#### 卡片

![Dora视图_五彩缤纷的危险-](https://github.com/user-attachments/assets/9dad007c-04ec-4c3b-b75e-23dfedb19f84)
##### 卡名：Dora视图 五彩缤纷的危险
###### 卡片类型：陷阱
###### 属性：陷阱
###### 效果：我方场地上名字带有「Dora视图」的怪兽作为攻击对象时，若攻击怪兽的守备力低于被攻击怪兽的守备力，则破坏攻击怪兽，并给予对方被攻击怪兽守备力的伤害。

#### Gradle依赖配置

```groovy
// 添加以下代码到项目根目录下的build.gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
// 添加以下代码到app模块的build.gradle
dependencies {
    implementation 'com.github.dora4:dview-colors:1.1'
}
```

#### 参考文献

https://www.w3.org/TR/css-color-3/#svg-color

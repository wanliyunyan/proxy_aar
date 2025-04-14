# proxy.aar (JitPack)

一个通过 JitPack 发布的 AAR 包。

## 使用方式

在你的项目中添加：

```groovy
allprojects {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
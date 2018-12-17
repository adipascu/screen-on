# Android Screen On

Use this library to keep the screen on and prevent the phone from going into sleep while the app is in the foreground.
This is useful for app development. The library is self bootstrapping, it requires no extra code in your app (besides the gradle dependency).

## Instalation steps (using jitpack)
- Add the JitPack repository to your build file, using your root build.gradle at the end of repositories:
```groovy
allprojects {
  repositories {
    /* ... */
    maven { url 'https://jitpack.io' }
  }
}
```
- Add the dependency
```groovy
dependencies {
  debugImplementation 'com.github.adi1133:screen-on:1.0'
}
```


For more information regarding the instalation check out [this link](https://jitpack.io/#adi1133/screen-on/1.0) 

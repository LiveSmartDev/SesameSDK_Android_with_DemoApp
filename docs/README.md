# SesameSDK_Android

this repository provides use old sesame sdk files that is copied from [here](https://github.com/CANDY-HOUSE/SesameSDK_Android_with_DemoApp/tree/5c3a51d3ea625e4338230c994b8b775bad9b17e4/SesameSDK_Android/).

## how to use

add repository

```
allprojects {
    repositories {
        maven {
            url = uri("https://livesmartdev.github.io/SesameSDK_Android_with_DemoApp/")
        }
    }
}
```

add dependency

```
dependencies {
    implementation 'co.candyhouse.jp:sesame:2.0.7@aar'
}
```
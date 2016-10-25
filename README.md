# ReadMoreTextView
 
[![](https://jitpack.io/v/czy1121/readmoretextview.svg)](https://jitpack.io/#czy1121/readmoretextview)

点击展开收缩的文本

![readmoretextview](screenshot.png)

## Gradle

``` groovy
repositories { 
    maven { url "https://jitpack.io" }
}
```  
    
``` groovy
dependencies {
    compile 'com.github.czy1121:readmoretextview:1.0.0'
}
```
    
## Usage
    
**XML**

``` xml
<com.github.czy1121.view.ReadMoreTextView
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:layout_gravity="top"
    android:layout_marginTop="10dp"
    android:layout_marginRight="10dp"
    android:layout_weight="1"
    android:maxLines="3"
    android:text="微信小程序设计的基本原则是微信设计中心针对在微信类上线的小程序页面总结的设计指南及建议。以下设计原则都是基于对用户的尊重的基础上的，旨在微信生态类建立有号、高效、一致的用户体验的同时，最大程度顺应和支持各业务需求设计，实现用户与程序的共赢。"
    app:rmtLessColor="@color/colorPrimary"
    app:rmtLessText="显示摘要"
    app:rmtMoreColor="@color/colorAccent"
    app:rmtMoreText="...显示更多"/>
``` 

**属性**

``` xml 
<declare-styleable name="ReadMoreTextView">
    <attr name="rmtMoreText" format="string"/>
    <attr name="rmtMoreColor" format="color"/>
    <attr name="rmtLessText" format="string"/>
    <attr name="rmtLessColor" format="color"/>
</declare-styleable>
```
 

## License

```
Copyright 2016 czy1121

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
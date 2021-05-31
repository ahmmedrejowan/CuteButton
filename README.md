# CuteButton
[![platform](https://img.shields.io/badge/platform-Android-yellow.svg)](https://www.android.com)
 [![API](https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=21) [![JitPack](https://img.shields.io/jitpack/v/github/ahmmedrejowan/CuteButton)](https://jitpack.io/#ahmmedrejowan/CuteButton) [![GitHub license](https://img.shields.io/github/license/ahmmedrejowan/CuteButton)](https://github.com/ahmmedrejowan/CuteButton/blob/master/LICENSE)  
 
[![GitHub issues](https://img.shields.io/github/issues/ahmmedrejowan/CuteButton)](https://github.com/ahmmedrejowan/CuteButton/issues) [![GitHub forks](https://img.shields.io/github/forks/ahmmedrejowan/CuteButton)](https://github.com/ahmmedrejowan/CuteButton/network) [![GitHub stars](https://img.shields.io/github/stars/ahmmedrejowan/CuteButton)](https://github.com/ahmmedrejowan/CuteButton/stargazers) [![GitHub contributors](https://img.shields.io/github/contributors/ahmmedrejowan/CuteButton)](https://github.com/ahmmedrejowan/CuteButton/graphs/contributors)

![CuteButton](https://github.com/ahmmedrejowan/CuteButton/blob/master/demo/CuteButton.png)

**A Material Design Custom Button Library for Android**

## Purpose
**CuteButton** is a `Custom Material Design Android Library` which could be an alternative for Deault `Button` Library. 
It has everything as the Default Button library, but with a lots customizations.

## What's New
This is the Initial Relase. Changes will be added later. Check on `Releases Tab` for Info.

## Features 
CuteButton comes with tons of new features and options:
- Background Color - Normal, Focused, Disabled
- Border - Color, Width, Radius
- Icon - Drawable Icon, Icon Size, Icon Padding, Icon Position
- Text - Normal Color, Disabled Color
- Ripple Effect on Clicks
 and also all the features of normal `Button` like padding, margin etc.

## Screenshot
Here are some buttons created with `CuteButton`

<img src="https://github.com/ahmmedrejowan/CuteButton/blob/master/demo/1622416945510.jpg" width="500px" alt="CuteButton"/>

## Prerequisites

Add this in your root `build.gradle` file (**not** your module `build.gradle` file):

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```
<br/>

## Dependencies

Add this to your module's `build.gradle` file (make sure the version matches the JitPack badge above):

```gradle
dependencies {
	...
	implementation 'com.github.ahmmedrejowan:CuteButton:1.0'
}
```

## Usage

#### XML
Include namespace to the root Layout/View:

```

xmlns:app="http://schemas.android.com/apk/res-auto"

```

CuteButton
```

<com.rejowan.cutebutton.CuteButton
    android:id="@+id/cuteButton"
    android:layout_width="190dp"
    android:layout_height="55dp"
    android:layout_margin="5dp"
    app:cb_bgColor="#0097A7"
    app:cb_bgColorFocus="#006064"
    app:cb_borderRadius="40dp"
    app:cb_icon="@drawable/ic_arrow"
    app:cb_iconPadding="5dp"
    app:cb_iconSize="25dp"
    app:cb_text="Download"
    app:cb_textColor="#fff"
    app:cb_textSize="20sp" />

```

Java

```
CuteButton cuteButton = findViewById(R.id.cuteButton);
cuteButton.setText("Hi, This is Cute Button");
cuteButton.setBackgroundColor(Color.BLUE);
cuteButton.setDisableColor(Color.BLACK);
cuteButton.setFocusColor(Color.CYAN);
cuteButton.setTextStyle(CuteButton.TEXT_STYLE_BOLD);
cuteButton.setBorderWidth(2);
cuteButton.setBorderWidth(1);
cuteButton.setRadius(10);
cuteButton.setIcon(R.drawable.ic_baseline_save_24);
cuteButton.setIconSize(25);
cuteButton.setIconPadding(10);
cuteButton.setIconPosition(CuteButton.POSITION_START);

```

## Contribute

Please fork this repository and contribute back using [pull requests](https://github.com/ahmmedrejowan/CuteButton/pulls).

Any contributions, large or small, major features, bug fixes, are welcomed and appreciated
but will be thoroughly reviewed .

Let me know which features you want in the future in `Request Feature` tab. 

If this project helps you a little bit, then give a to Star ⭐ the Repo. 

<br/>


## Credits

Created with Love by **K M Rejowan Ahmmed** (@ahmmedrejowan)

Reach me @
* [Github](https://github.com/ahmmedrejowan) 
* [LinkedIn](https://www.linkedin.com/in/ahmmedrejowan)
* [Twitter](https://twitter.com/ahmmedrejowan)
* [Facebook](https://facebook.com/ahmmedrejowan)
* [StackOverFlow](https://stackoverflow.com/users/9932194/k-m-rejowan-ahmmed)





## Licences 
* [Apache Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

```
Copyright 2021 K M Rejowan Ahmmed (ahmmedrejowan)

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

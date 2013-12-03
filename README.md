android-flatUiColors
====================

Android Colors for Flat UI Design

Colors: [flatuicolors.com](http://www.flatuicolors.com/)
Page: http://fbrinker.github.io/android-flatUiColors/

1. Overview
2. Installation
3. Usage

##1. Overview

![Editor Screenshot](https://raw.github.com/fbrinker/android-flatUiColors/master/screenshot.png)

##2. Installation
To adopt the colors, just copy the [colorsFlatUi.xml](../master/res/values/colorsFlatUi.xml) into your *res/values/* directory or paste the content of the [colorsFlatUi.xml](../master/res/values/colorsFlatUi.xml) into your *colors.xml* file.

##3. Usage
Now, you can use the colors in your xml layouts:
```xml
@color/flatui_midnight_blue
```

or in java like this:
```java
Color midnightBlue = getApplicationContext().getResources().getColor(R.id.flatui_midnight_blue)
MyTextView.setTextColor(midnightBlue);
```

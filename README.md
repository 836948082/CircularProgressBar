#CircularProgressBar

This is an Android project allowing to realize a circular ProgressBar in the simplest way possible.

![](https://github.com/836948082/CircularProgressBar/blob/master/image/image.gif)

USAGE
-----

To make a circular ProgressBar add CircularProgressBar in your layout XML and add CircularProgressBar library in your project or you can also grab it via Gradle:

```groovy
compile 'com.mikhaellopez:circularprogressbar:1.1.1'
```

XML
-----

```xml
<com.mikhaellopez.circularprogressbar.CircularProgressBar
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:cpb_background_progressbar_color="#FFCDD2"
    app:cpb_background_progressbar_width="5dp"
    app:cpb_progressbar_color="#F44336"
    app:cpb_progressbar_width="10dp" />
```

You must use the following properties in your XML to change your CircularProgressBar.


#####Properties:

* `app:cpb_progress`                      (integer)   -> default 0
* `app:cpb_progressbar_color`             (color)     -> default BLACK
* `app:cpb_background_progressbar_color`  (color)     -> default GRAY
* `app:cpb_progressbar_width`             (dimension) -> default 7dp
* `app:cpb_background_progressbar_width`  (dimension) -> default 3dp

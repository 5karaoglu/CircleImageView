
# CircleImageView

Simple circle shaped ImageView with border attribute.


## Deployment

Add it in your root build.gradle at the end of repositories:

```bash
  allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

Add the dependency

```bash
  dependencies {
	        implementation 'com.github.5karaoglu:CircleImageView:1.0.0'
	}
```

Example:

```bash
  <com.besirkaraoglu.circleimageview.CircleImageView
        android:id="@+id/iv"
        app:border_color="@color/black"
        app:border_size="3dp"
        app:src="@drawable/ic_launcher_background" />
```


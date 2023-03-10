## ImageView

### About

The application uses an ```ImageView``` to show a full bleed image.

```xml
<?xml version="1.0" encoding="utf-8"?>
<ImageView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:contentDescription="@string/description"
    android:scaleType="centerCrop"
    android:src="@drawable/rocks"
    tools:context=".MainActivity" />
```

### Resource

Image used - [rocks](https://user-images.githubusercontent.com/122201501/224284655-34606539-fb94-435a-a0c8-2574ab761f10.jpg)

### Screenshots

| Device      | Virtual | OS        | API | Orientation                                                                                                         |
|-------------|---------|-----------|-----|---------------------------------------------------------------------------------------------------------------------|
| Pixel 6 Pro | Yes     | Android Q | 29  | [Portrait](https://user-images.githubusercontent.com/122201501/224284328-fdb3c572-a561-4998-a67f-a6a5dfa3e122.png)  |
| Pixel 6 Pro | Yes     | Android Q | 29  | [Landscape](https://user-images.githubusercontent.com/122201501/224283404-647fb93b-1d58-4ed6-ad3a-8a06ef11a5f6.png) |

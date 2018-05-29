# StackImageView
StackImageView Provides horizontally overlapping of circular images with lots of customization.
## Gradle
Add following line of code into your top level build.gradle file :
```
repositories {
        google()
        jcenter()
    }
```
Add following line of code into your app level build.gradle file :
```
dependencies {
    ...
    compile 'com.kartikp.stackimageview:stackimageview:0.0.5'
}
```
## Usage
For display images in circular shape with horizontally overlapping, use **StackImageView** in your layout XML file.
### XML
```
<com.kartikp.stackimageview.StackImageView
        android:id="@+id/stackImageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        app:countTextViewBg="#000080"
        app:countTextViewBorderColor="#3CB371"
        app:countTextViewBorderWidth="2dp"
        app:countTextViewColor="#FF8C00"
        app:countTextViewDimen="65dp"
        app:countTextViewImageDimen="20dp"
        app:countTextViewImageInsteadOfText="true"
        app:countTextViewImageSource="@drawable/ic_star_icon"
        app:countTextViewPosition="after"
        app:countTextViewSize="18sp"
        app:gapBetweenViews="-10dp"
        app:maxVisibleProfileImage="5"
        app:profileImageBorderColor="#DC143C"
        app:profileImageBorderWidth="2dp"
        app:profileImageDimen="65dp"
        app:profileImageLoaderColor="#FF7F50"
        app:profileImageLoaderDimen="20dp"
        app:profileImageLoaderVisible="true"
        app:profileImageLoadingFailedBgColor="#2F4F4F"
        app:profileImagePlaceHolder="@drawable/ic_star_icon"
        app:profileImagePlaceHolderDimen="20dp"
        app:profileImagePlaceHolderVisible="true"/>
```
You must use following proprties in your XML to customize **StackImageView** as per your requirements.
> Properties :
```
- app:maxVisibleProfileImage="5"(integer)-> default 5
```

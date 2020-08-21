## Adding Dependency

Gradle is the only supported build configuration, so just add the dependency to your project `build.gradle` file:

```groovy
dependencies {
  implementation 'com.airbnb.android:lottie:$lottieVersion'
}
```
The latest Lottie version is:
![lottieVersion](https://maven-badges.herokuapp.com/maven-central/com.airbnb.android/lottie/badge.svg)

Lottie 2.8.0 and above only supports projects that have been migrated to [androidx](https://developer.android.com/jetpack/androidx/). For more information, read Google's [migration guide](https://developer.android.com/jetpack/androidx/migrate).

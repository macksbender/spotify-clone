

![screenshot](https://github.com/macksbender/spotify-clone/blob/master/logo.png)

# Spotify clone. App based on MVVM architecture.

```groovy
dependencies {
    implementation fileTree(dir: "libs", include: ["*.jar"])
    implementation "org.jetbrains.kotlin:kotlin-stdlib:$kotlin_version"
    implementation 'androidx.core:core-ktx:1.3.1'
    implementation 'androidx.appcompat:appcompat:1.2.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.1'
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.3.0'

    // Material Design
    implementation 'com.google.android.material:material:1.3.0-alpha02'

    // Architectural Components
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0"

    // Lifecycle
    implementation "androidx.lifecycle:lifecycle-extensions:2.2.0"
    implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.2.0"
    implementation "androidx.lifecycle:lifecycle-runtime:2.2.0"
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.2.0"

    // Coroutines
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.3.9'
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.9'

    // Coroutine Lifecycle Scopes
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0"
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.2.0"

    // Navigation Component
    implementation "androidx.navigation:navigation-fragment-ktx:2.3.0"
    implementation "androidx.navigation:navigation-ui-ktx:2.3.0"

    // Glide
    implementation 'com.github.bumptech.glide:glide:4.11.0'
    kapt 'com.github.bumptech.glide:compiler:4.11.0'

    // Activity KTX for viewModels()
    implementation "androidx.activity:activity-ktx:1.1.0"

    //Dagger - Hilt
    implementation "com.google.dagger:hilt-android:2.28-alpha"
    kapt "com.google.dagger:hilt-android-compiler:2.28-alpha"
    implementation "androidx.hilt:hilt-lifecycle-viewmodel:1.0.0-alpha02"
    kapt "androidx.hilt:hilt-compiler:1.0.0-alpha02"

    // Timber
    implementation 'com.jakewharton.timber:timber:4.7.1'

    // Firebase Firestore
    implementation 'com.google.firebase:firebase-firestore:21.6.0'

    // Firebase Storage KTX
    implementation 'com.google.firebase:firebase-storage-ktx:19.2.0'

    // Firebase Coroutines
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.1.1'

    // ExoPlayer
    api "com.google.android.exoplayer:exoplayer-core:2.11.8"
    api "com.google.android.exoplayer:exoplayer-ui:2.11.8"
    api "com.google.android.exoplayer:extension-mediasession:2.11.8"
}
```

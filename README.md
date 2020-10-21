# Android-Dependencies
Collection of different dependencies for android components and libraries

**Retrofit**

implementation "com.squareup.retrofit2:retrofit:2.6.0"  
implementation 'com.squareup.retrofit2:converter-gson:2.6.3'  

implementation "com.squareup.retrofit2:converter-moshi:2.6.0"

**Moshi**

implementation "com.squareup.moshi:moshi:1.8.0"  
implementation "com.squareup.moshi:moshi-kotlin:1.8.0"

**Coroutines**

implementation "org.jetbrains.kotlinx:kotlinx-coroutines-core:1.1.0"    
implementation "org.jetbrains.kotlinx:kotlinx-coroutines-android:1.1.0"

**Room Database**

implementation "androidx.room:room-runtime:2.2.5"  
kapt "androidx.room:room-compiler:2.2.5"

**CameraX Database**   
def camerax_version = "1.0.0-beta07"   
// CameraX core library using camera2 implementation     
  implementation "androidx.camera:camera-camera2:$camerax_version"    
// CameraX Lifecycle Library. 
  implementation "androidx.camera:camera-lifecycle:$camerax_version"   
// CameraX View class  
  implementation "androidx.camera:camera-view:1.0.0-alpha14"    
  
**Jetpack Navigation**   

  implementation "androidx.navigation:navigation-fragment-ktx:2.3.1"   
  implementation "androidx.navigation:navigation-ui-ktx:2.3.1"  
  
**ViewModel and LiveData (arch components)**

  implementation "androidx.lifecycle:lifecycle-extensions:2.2.0"  
  implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0" 
  
**RecyclerView**

  implementation 'androidx.recyclerview:recyclerview:1.0.0'  
  
**Glide** 

  implementation 'com.github.bumptech.glide:glide:4.10.0'  






# dependencies

// .collectAsStateWithLifecycle
implementation("androidx.lifecycle:lifecycle-runtime-compose:2.6.0")

//Coil
implementation("io.coil-kt:coil-compose:2.4.0")

//Constraints 
implementation("androidx.constraintlayout:constraintlayout-compose:1.1.0-alpha11")

//Shared Preferences
implementation("androidx.preference:preference-ktx:1.2.1")

//Room
implementation("androidx.room:room-runtime:2.5.2")
annotationProcessor("androidx.room:room-compiler:2.5.2")
ksp("androidx.room:room-compiler:2.5.2")
//support for coroutines
implementation("androidx.room:room-ktx:2.5.2")

//Navigation
implementation("androidx.navigation:navigation-compose:2.4.0-alpha04")

//Icons
implementation("androidx.compose.material:material-icons-extended")

//Coroutines
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.2")
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.2")

//Retrofit + gson
implementation("com.squareup.retrofit2:retrofit:2.8.1")
implementation("com.squareup.retrofit2:converter-gson:2.8.1")

//ViewModel
implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.1")

//ksp
id("com.google.devtools.ksp") version "1.8.10-1.0.9"
kotlin {
    sourceSets.main {
        kotlin.srcDir("build/generated/ksp/main/kotlin")
    }
    sourceSets.test {
        kotlin.srcDir("build/generated/ksp/test/kotlin")
    }
}

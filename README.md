# Global Theme JPC

A reusable **Jetpack Compose UI Theme Library** for Android that helps maintain
**consistent theming, colors, and state-based UI** across apps.

Built as an **Android Library (AAR)** using **Jetpack Compose**.

---

## ✨ Features

- Jetpack Compose–based theming
- Centralized **Color**, and **Theme**
- Easy integration into any Compose app
- Designed for reuse inside teams / organizations
- Clean separation of **UI**, **Theme**, and **DataStore logic**



## 📦 Installation (for Users)

### Step 1: Add JitPack repository
### In settings.gradle.kts
```kotlin
dependencyResolutionManagement {
      repositories {
        google()
        mavenCentral()
        maven("https://jitpack.io")
    }
}
```

### Step 2: Add dependency

### In app -> build.gradle.kts:
```kotlin
dependencies {
    implementation("com.github.harshitdev20:Global_Theme_JPC:v1.0.1")
}
```

### Optional 
(Use this only if you cannot use JitPack (offline / internal builds))
```kotlin
dependencies {
   implementation(files("libs/jpc_library-release.aar"))
}
```

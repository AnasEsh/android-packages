# android-packages
public repo used as a single source for android maven repos

# Usage
add the following to dependency resulution repos:
```kotlin
  maven {
            url = uri("https://maven.pkg.github.com/AnasEsh/android-packages")
            credentials{
                username="AnasEsh"
                password = "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"
            }
        }
```


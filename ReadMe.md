# BrandMessenger:

Development branch of **khoros-android** repo corresponds to release **3.0.3** on Jitpack ( in case of releasing latest version, update development branch from master and make appropriate changes)


Dependency to be added for Khoros messaging and core:

    com.github.lithiumtech.brand-messenger-android-sdk:ui:3.0.3
    com.github.lithiumtech.brand-messenger-android-sdk:core:3.0.3


**Auth token to access lib**
You need to generate Auth token on Jitpack and copy that in gradle.properties file
authToken='YOUR_AUTH_TOKEN'

Also, add this in your project's gradle file

    allprojects {
        repositories {
            maven {
                url 'https://jitpack.io'
                credentials { username authToken }
            }
        }
    }

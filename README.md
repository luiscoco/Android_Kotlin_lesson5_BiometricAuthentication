# Learn how to use Biometric (FaceRecognition or FingerPrint) for Authentication

For a detailed explanation see this youtube video: https://www.youtube.com/watch?v=BcmPW3ji_MA

## 1. Create a new Android Compose application

We run Android and we press **New Project** button 

![image](https://github.com/luiscoco/Android_Kotlin_lesson5_BiometricAuthentication/assets/32194879/c8b1427b-541f-41e8-ae8d-a3563682c9fa)

Then we select the **Empty Activity** template

![image](https://github.com/luiscoco/Android_Kotlin_lesson5_BiometricAuthentication/assets/32194879/32f7e67d-6398-47a5-8a2a-b2547227a0be)

This is the code for the new application

![image](https://github.com/luiscoco/Android_Kotlin_lesson5_BiometricAuthentication/assets/32194879/cd0a2d13-8f1a-44fc-be26-f6bfa0d40bd5)

## 2. Add dependencies

We add the following dependencies in the **build.gradle.kts**(app) file

```kotlin
implementation ("androidx.biometric:biometric:1.1.0")
implementation ("androidx.appcompat:appcompat:1.4.1")
```

![image](https://github.com/luiscoco/Android_Kotlin_lesson5_BiometricAuthentication/assets/32194879/f2cfd9f4-9f7e-4c25-874b-41a0ca855cde)


## 3. 

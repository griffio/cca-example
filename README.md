cca-example
===========

chrome apps

cca run android --device     

cca is gradle sensitive 

the platforms/android/build.gradle may need to be updated

if (gradle.gradleVersion >= "2.1") {
    dependencies {
        classpath 'com.android.tools.build:gradle:0.14.0+'
    }
} else {
    dependencies {
        classpath 'com.android.tools.build:gradle:0.12.0+'
    }
}

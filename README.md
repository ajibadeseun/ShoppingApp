# ShoppingApp
This app serves as a template to build a beautiful and catchy app UI appearance conforming to material design guidelines

# Screenshots
<img src="https://github.com/ajibadeseun/ShoppingApp/blob/master/Screenshot_20180303-145427.png" width="400" height="700"/>


<img src="https://github.com/ajibadeseun/ShoppingApp/blob/master/Screenshot_20180303-145433.png" width="400" height="700"/>


#Gradle

The gradle.build(Module:app) file must like the following:

apply plugin: 'com.android.application'

android {

    compileSdkVersion 25
    buildToolsVersion "25.0.2"
    defaultConfig {
        applicationId "io.material.demo.codelab.buildingbeautifulapps"
        minSdkVersion 15
        targetSdkVersion 25
        versionCode 1
        versionName "1.0"
        vectorDrawables.useSupportLibrary true

    }
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
        }
    }
}

dependencies {

    compile fileTree(dir: 'libs', include: ['*.jar'])
    compile 'com.android.support:appcompat-v7:25.3.1'
    compile 'com.android.support:cardview-v7:25.3.1'
    compile 'com.android.support:design:25.3.1'
    compile 'com.android.support:recyclerview-v7:25.3.1'
    compile 'com.android.volley:volley:1.0.0'
    compile 'com.google.code.gson:gson:2.2.4'
}


#Link to Apk

https://drive.google.com/open?id=1EGyxwfLfb4p8fI3LBqpZ5RGCW0D-a4nE


#Acknowledgement

ShoppingApp is licensed under the Apache License, Version 2.0 (the "License"),you may not use this file except in compliance with the License.You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0. Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

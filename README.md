![GitHub release (latest by date)](https://img.shields.io/github/v/release/colin-yeoh/fileuploader?color=green)

# FileUploader   
Helper class for uploading file using okHttp multipart form and kotlin flow pattern.


### Usage
Step 1. Add the JitPack repository to your build file. Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.colin-yeoh:fileuploader:{{ latest_release }}'
	}

Step 3. Use it in your fragment / activity

[Sample usage in fragment](https://github.com/colin-yeoh/fileuploader/blob/main/app/src/main/java/com/cyapp/fileuploaderexample/FirstFragment.kt)

### License

Copyright 2019 Square, Inc.
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
  
http://www.apache.org/licenses/LICENSE-2.0
    
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, 

WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. 
See the License for the specific language governing permissions and 
limitations under the License.

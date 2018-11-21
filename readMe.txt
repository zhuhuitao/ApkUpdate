Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.zhuhuitao:ApkUpdate:v1.0.1'
	}


  UpdateManage updateManage = new UpdateManage(this, "url", "name");
        updateManage.showDownloadDialog();
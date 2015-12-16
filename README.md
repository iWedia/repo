# ANDROID4TV Java Library Repository
Android Java library (`android4tv-framework-x.x.x.jar`) contains classes and interfaces that needs to be imported by the applications, in order to use ANDROID4TV framework capabilities on the platform.
## Add to Project:
		1. In main build.gradle add:
                       allprojects {
                            repositories {
                                maven {
                                   url 'https://github.com/iWedia/repo/raw/master/';
                                }
                            }
                       }
		2. Add Dependecy where is needed:
                       dependencies {
                            compile group:'com.iwedia.dtv', name:'android4tv-framework', version:'x.x.x'
                       }


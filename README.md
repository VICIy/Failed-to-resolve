# Failed-to-resolve
There  is a problem when inserting thirdparty library :Failed to reslove~~I am crying!~~

solution:
add jcenter{url "http://jcenter.bintray.com/"} in your Application's 'build.gradle' like following:


buildscript {
    repositories {
        jcenter{url "http://jcenter.bintray.com/"}
    }
}


allprojects {
    repositories {
        jcenter{url "http://jcenter.bintray.com/"}
    }
}

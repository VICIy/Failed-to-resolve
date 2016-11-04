# Failed-to-resolve
There  is a problem when inserting thirdparty library :Failed to reslove~~I am crying!~~

add jcenter{url "http://jcenter.bintray.com/"} like following:


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

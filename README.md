How to use
========

```maven repo
https://raw.githubusercontent.com/opensz/mvn-repo/master/
http://mvn.servicezon.com/maven2/    (nginx proxy pass, only support org.szopen)
http://mvn.servicezon.com:8081/nexus/content/groups/public/   (nginx porxy pass, support org.szopen and maven central)
```

Simply add the repository to your build.gradle file:

```groovy
repositories {
    maven {
        url 'https://raw.githubusercontent.com/opensz/mvn-repo/master/'
    }
    mavenCentral()
}
```

License:
--------
The licenses are provided by the individual libary owner. This "mvn-repo" utilizes these libaries and
won´t provide any support, responsibility or licenses itself.

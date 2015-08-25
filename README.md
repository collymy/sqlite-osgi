# sqlite-osgi

Provides a Gradle build file that uses the [bnd-platform](https://github.com/stempler/bnd-platform) plugin to create an OSGi bundle containing the [SQLite JDBC driver from Xerial](https://bitbucket.org/xerial/sqlite-jdbc).

Build with:

```
gradle updateSiteZip
```

The build will fail but it will still have built the bundle in ./build/plugins

## Note well

Prior to launching the build, edit the *build.gradle* file to make sure **eclipseHome** variable points to the path of your Eclipse local installation directory.

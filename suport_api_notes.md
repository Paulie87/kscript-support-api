Developer Info
--------------


```bash
## to install to local maven repo
gradle install

## to run the tests 
gradle test

```

Release Checklist
-----------------

1. Update version in
* `build.gradle`
* `kscript and`
* `kscript-support-api/README`
* `kscript/README`


1. Push and create github release tag

2. 
```
gradle install
```

4. Create new version on jcenter

* Upload jar, sources.jar and pom for new version from `~/.m2/repository/de/mpicbg/scicomp/kscript` to:
> https://bintray.com/holgerbrandl/mpicbg-scicomp/kscript

5. Check for release status on
https://jcenter.bintray.com/de/mpicbg/scicomp/

6. Bump versions for new release cycle
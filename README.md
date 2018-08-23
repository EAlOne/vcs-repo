# vcs-repo

This repository contains artifacts from different projects to be able to use them in other projects by connecting 
a remote Maven repository.

## How it use
If you want use this repository as remote Maven repository you should be add some configuration in your *build.gradle* 
script:
 ```groovy
buildscript {
	repositories {
        ...
        // For use gradle plugin
        maven {
            url 'https://github.com/EAlOne/vcs-repo/raw/master'
        }
	}
}

// For dependencies
maven {
    url 'https://github.com/EAlOne/vcs-repo/raw/master'
}

```
## Content

#### [version-info](https://github.com/EAlOne/version-info)
* version-info-1.1.0
* version-info-1.0.0


## License
Each project has its own license. For more information visit page of the project you are interested in.

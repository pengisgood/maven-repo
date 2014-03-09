# maven-repo

## Use github as dependency repository

### Usage:

1. add these line to your 'build.gradle'

```
repositories {
    mavenRepo urls: 'https://github.com/pengisgood/maven-repo/raw/master/'
}
dependencies {
    compile 'org.makedream:FirstArtifact:0.0.1-SNAPSHOT'
}
```
# Purpose #

This makes it easier to work for with
[the Eclipse Bundlor tool](https://www.eclipse.org/virgo/documentation/bundlor-documentation-1.1.2.RELEASE/docs/user-guide/htmlsingle/user-guide.html)
for Gradle and OSGi containers (including Adobe CQ/AEM).

[ ![Download](https://api.bintray.com/packages/twcable/aem/gradle-plugin-bundlor/images/download.svg) ](https://bintray.com/twcable/aem/gradle-plugin-bundlor/_latestVersion)

# Usage #

`apply plugin: 'bundlor'`

Applying the plugin adds a method to the project called `osgiWrapJar`

## Methods ##

* `osgiWrapJar` - .

# Installation #

```
buildscript {
    repositories {
        jcenter()
        maven {
            url "http://dl.bintray.com/twcable/aem"
        }
    }

    dependencies {
        classpath "com.twcable.gradle:cq-gradle-plugin-bundlor:<version>"
    }
}
```

Built against **Gradle 2.8**

# API #

https://twcable.github.io/gradle-plugin-bundlor/docs/groovydoc/

# LICENSE

Copyright 2015 Time Warner Cable, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance
with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on
an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for
the specific language governing permissions and limitations under the License.

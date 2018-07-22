# VMF-Text-Gradle-Plugin

Get this plugin from here: https://plugins.gradle.org/plugin/eu.mihosoft.vmftext

Just add the plugin id to use this plugin:

```gradle
plugins {
  id "eu.mihosoft.vmftext" version "0.1.0" // use latest version
}
```

and configure VMF-Text:

```gradle
vmfText {
    version    = '0.1.1' // use desired VMF version
    vmfVersion = '0.1'   //
}
```

Grails Security Bridge
======================

The Grails Security Bridge plugin provides a decoupled, cross-plugin security interface for Grails applications. It allows you to keep the majority of authentication logic in one plugin, while other plugins can reference a public API interface to retrieve the information needed.

Documentation
-------------

Full documentation is available at: https://wondrify.github.io/grails-security-bridge/

To build the documentation locally:

```bash
./gradlew :grails-security-bridge-docs:asciidoctor
```

Then open `grails-security-bridge-docs/build/docs/index.html` in your browser.

Installation
------------

### Grails 7

```groovy
dependencies {
    implementation 'cloud.wondrify:grails-security-bridge:7.0.0'
}
```

### Grails 6.x and Earlier

```groovy
dependencies {
    implementation 'com.bertramlabs.plugins:grails-security-bridge:6.x.x'
}
```

License
-------

Apache License 2.0

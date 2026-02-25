# Grails Security Bridge Documentation

This directory contains the AsciiDoc documentation for the Grails Security Bridge plugin.

## Building Documentation

To build the documentation locally:

```bash
./gradlew :grails-security-bridge-docs:asciidoctor
```

The generated HTML documentation will be available in `grails-security-bridge-docs/build/docs/`.

## Viewing Documentation

After building, open `grails-security-bridge-docs/build/docs/index.html` in your browser.

## Publishing

Documentation is automatically published to GitHub Pages when changes are pushed to the `master` or `main` branch via the `.github/workflows/publish-docs.yml` workflow.

The published documentation is available at: https://wondrify.github.io/grails-security-bridge/

## Structure

- `src/docs/asciidoc/index.adoc` - Main documentation page with installation, configuration, and usage

## Editing Documentation

Documentation is written in AsciiDoc format. Key conventions:

- Use `[source,groovy]` for Groovy code examples
- Use `[source,java]` for Java code examples
- Keep examples practical and complete
- Use the `:project-version:` attribute for version references

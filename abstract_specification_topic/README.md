= Bounding Box Abstract Specification Topic

== Content

Guidance on authoring OGC documents in Metanorma asciidoc is at https://www.metanorma.org/author/ogc/topics/markup

== Building

Run `docker run -v "$(pwd)":/metanorma -v ${HOME}/.fontist/fonts/:/config/fonts  metanorma/mn  metanorma compile --agree-to-terms -t ogc -x xml,html,doc,pdf document.adoc`.


Note that the document was compiled using version 1.2.9.2 of the metanorma/mn docker image.

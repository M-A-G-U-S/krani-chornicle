The English translation of Raoul Renier's ["_Kráni Krónika_"](./germane_documents/02_-_Raoul_Renier_-_Krani-Kronika.pdf), a M.A.G.U.S role playing game novella, taking place in the world of Ynev.

Available formats:
+ AsciiDoc ( -> [`krani-chronicle.adoc`](./krani-chronicle.adoc))
+ HTML ( -> https://m-a-g-u-s.github.io/krani-chornicle/)
+ DocBook ( -> [`docs/krani-chronicle.xml`](./docs/krani-chronicle.xml))

[`germane_documents`](./germane_documents/) contains files related to this novella (however remotely).

[`asciidoctor`](https://docs.asciidoctor.org/asciidoctor/latest/cli/man1/asciidoctor/) commands to generate HTML and DocBook:

+ `asciidoctor -b docbook -D docs/ krani-chronicle.adoc` 
+ `asciidoctor -b html -o docs/index.html krani-chronicle.adoc`

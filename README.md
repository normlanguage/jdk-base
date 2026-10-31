# jdk-base

This repository retains the historical `jdk.base` v1 release. New applications use the `java.base` module supplied by Norm. New `jdk.base` versions are no longer published.

The [migration example](examples/java-base/Main.norm) uses `norm:java.base` directly and verifies calendar arithmetic, exact decimals, rounding, enums and the Locale type. Run it with `norm examples/java-base/Main.norm`.

Public Java types have one owner. Their aliases and selected members are defined by the [official java.base declaration](https://github.com/normlanguage/Norm/blob/main/norm/stdlib/java/base/module.norm). In current releases, `java.base.util.Locale` exposes the type; the old wrapper's Locale factory and accessor methods are outside that selected surface.

The [v1 tag](https://github.com/normlanguage/jdk-base/tree/v1) and its immutable release remain available for historical consumers. The registry ownership entry remains available for resolving that release.

[License](LICENSE)

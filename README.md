# json-smart-v2

[the new WIKI is here](https://github.com/netplex/json-smart/wiki)

== Changelog: ==

*V 2.2*
* rename asm to accessors-smart due to conflict name with asm.ow2.org lib.
* fix OSGI error
* add support for BigDecimal
* improve JSONObject.getAsNumber() helper
* add a Field Remaper

*V 2.1*
  * net.minidev.json.mapper renamed to net.minidev.json.writer
  * Add ACCEPT_TAILLING_SPACE Parssing Flag.
  * Mapper classes now non static.
  * Reader mapper are now available in net.minidev.json.reader.JsonReader class
  * Writer mapper are now available in net.minidev.json.writer.JsonWriter class

*V 2.0*
  * Fix Double Identification [issue 44](http://code.google.com/p/json-smart/issues/detail?id=44)
  * Fix Collection Interface Serialisation
  * Fix security Exception in ASM code
  * Project moved to GitHub
  * Fix [issue 42](http://code.google.com/p/json-smart/issues/detail?id=42)

*V 2.0-RC3*
  * Add custom data binding inside the ASM layer.
  * Add Date support
  * Add \x escape sequence support [issue 39](http://code.google.com/p/json-smart/issues/detail?id=39)
  * fix issue [issue 37](http://code.google.com/p/json-smart/issues/detail?id=37)

*V 2.0-RC2*
  * Fix critical [issue 23](http://code.google.com/p/json-smart/issues/detail?id=23)
  * Improve Javadoc in JSONStyle [issue 24](http://code.google.com/p/json-smart/issues/detail?id=23)

*V 2.0-RC1*
  * speed improvement in POJO manipulation
  * add JSONStyle.LT_COMPRESS predefined generate strct json, but ignoring / escapement.

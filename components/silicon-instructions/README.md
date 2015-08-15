# Usage

Highlights an array of instructions.  Glows.  Is somewhat efficient.  Uses [highlight.js](https://highlightjs.org/).

Example:

````html
<silicon-instructions instructions="[[instructions]]"></silicon-instructions>
````

Works well with [silicon-disassembler](http://github.com/m4b/silicon-disassembler).

See [documentation](http://m4b.github.io/silicon-instructions) for more information and a demo.

# TODO

* fix UI `<iron-list>` re-used state bug where multiple elements are highlighted (but not selected)
* Allow memory on/off option?
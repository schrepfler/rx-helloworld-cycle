Rx Helloworld Cycle
====

Rationale
----

The Rx Helloworld Web Component is intended to show a simple bosonic based toolchain which will generate a 
Cycle.js based web component. Code is currently not fully ES6.

Usage
----
`npm install`
`grunt demo`

Open http://127.0.0.1/8020

Development
----

The web component builds on top of the [Bosonic] toolset.
The rx-helloworld-cycle.html [src/rx-betslip.html] is the main defining point of the component. Its segmented in three sections:
* style
* template
* script
Once they get filled, the bosonic transpiler will take the code from the given sections and generate rx-helloworld-cycle.css and
rx-helloworld-cycle.js.

[Web Component]:http://webcomponents.org/
[Bosonic]:http://bosonic.github.io/

Principles
-----

Thoughts
-----

TODO
-----

Rx Betslip
====

Rationale
----

The Rx Betlip is intended to be a tested and reusable [Web Component] following the latest web standard and aspiring to
provide a stable and maintainable UI Javascript component used to build and place betslips.

Development
----

The rx-betslip web component builds on top of the [Bosonic] toolset.
The rx-betslip.html [src/rx-betslip.html] is the main point of entry to your component. Its segmented in three sections:
* style
* template
* script
Once they get filled, the bosonic transpiler will take the code from the given sections and generate rx-betslip.css and
rx-helloworld-cycle.js.

Principles
----
When building this web component we will try to adhere to the following principles:
* Accessibility
* Performance
* Re-usability
* Responsiveness
* Namespacing
* Docs & testing


[Web Component]:http://webcomponents.org/
[Bosonic]:http://bosonic.github.io/

Thoughts
-----
Mutation observers? http://addyosmani.com/blog/mutation-observers/
# Learning Vue

## Philosophy

1. Reactivity - being able to react appropriately to incoming changes to the DOM.
1. String Interpolation - strings are replaced with values.
1. Load HTML first before scripts.
1. Execution order is important.

## Mechanics

1. ``{{someId}}`` - DoubleStash.
1. ``:value`` - Syntantic sugar for ``v-bind:value``.
1. ``v-model`` - two way data binding.
1. ``@click.prevent`` - Syntactic sugar for ``v-on:click.prevent``.
1. ``v-if / v-else``, ``v-show``, and ``v-cloak`` for conditionally displaying elements on screen.
1. **Hook** - an interface that can be used to provide additional/overriding code to be executed under certain conditions or in response to specific events.
1. ``v-for="(a, index) in items"`` for looping through a data set.
1. ``:key`` for patching arrays in place for performance improvements.
1. ``:style`` for binding styles. Element style is base style, ``v-bind:style`` overrides.
1. ``:class`` for bindiing classes.
1. ``<transition> and <transition-group tag="tagnametoreplace">`` used for grouping transitional elements for CSS.
1. ``.<name>-leave-to, <name>-enter and <name>-enter-active and <name>-leave-active`` for grouping CSS transitions.
1. For those CSS transition elements that are not parsed correctly, use ``is="transition-group"`` attribute in element.

## Components

1. For reusability, encapsulation, portability, organization, and readility.
1. W3C standard states that custom component name must include a hypen.
1. Props are passed into components as an array.
1. Slots take in element data inbetween the component tags. Slots can contain names for default values.
1. To raise events, use ``this.$emit('<function name>', parameter(s))`` to route the event to parent (root).
1. Module bundler - vue-cli - webpack, rollup or parcel. Hot reloading is supported.

## Resources

1. [Vue JS](https://vuejs.org/v2/guide/)
1. [JSDelivr](https://www.jsdelivr.com/)
1. [Vue Devtools](https://github.com/vuejs/vue-devtools)
1. [Awesome Vue](https://github.com/vuejs/awesome-vue)
1. [Vue Curated](https://curated.vuejs.org)

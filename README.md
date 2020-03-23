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

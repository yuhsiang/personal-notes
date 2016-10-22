# How to adapt to change...
## Vue.js
## sacrificial-architecture
## Modularisation
* simple implementation detail
* increase performance
* reduce code and modulize
   manage state of your implementation
   make things easy to test
* nobody likes spinning (icon for loading)
   use webpack & browsify
   
## LIFT Principles
* manage your code in good manner
* [L]ocate the code very quickly
  export the code and the function is in the bottom
* [I]dentify
* [F]lat
* [T]-dry [try to stick dry]
   don't implemnt wide and implent big
   
## HMR [Hot Module Replacement]
change -> compile -> HMR Server -> bundle -> HMR runtime -> code
 \_> its basically just webpack
 
## Exploring Vue.js
is a progressive framework for building user interfaces. 
* View layer
* Components with reactivity
* Extendable via plugins
* Lightweight
* Simplicity
* Testable

## Vie.js work?
* Reactive data-binding system for a Data-driven view
* DOM in sync with data
* Object.defineProperty
* Component System helps with small abstraction layer
* Component loosely modeled after the Web Components spec
* implements the Slot API and the special attribute

## Vue.js & Vuex with Sacrificial Architecture!
Keep Actions
Keep State
[Mutation] Easily remove and add Module

## Vue.js 2.0
### Virtual DOM


## What is Reactivity?
settger and getter dependencies -> watcher -> [notify] -> Directive -> [update] -> DOM



### Reference
[sacrificial-architecture-1](https://medium.com/@TheStrazz86/sacrificial-architecture-in-web-development-3926c0593fc8#.pbstt7uvf)

[sacrificial-architecture-2](http://martinfowler.com/bliki/SacrificialArchitecture.html)

[Vue.js](https://vuejs.org/guide/)

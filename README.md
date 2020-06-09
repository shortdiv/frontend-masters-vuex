# Vuex Workshop course materials

Materials for the State Management with Vuex Course

Author: Divya Tagtachian

Here are the [Vue chrome devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en)

## Code
All code is available on this repo, exercises are saved in submodules so be sure to run the following commands to pick those up: 

```
git clone --recurse-submodules https://github.com/shortdiv/frontend-masters-vuex.git
```

### Troubleshooting
If things seem outdated, try updating submodules with this command: 
```
git submodule update --init --recursive
```

## Slides:
- [Vuex 1: Introduction to State Management](https://slides.com/shortdiv/vuex-1)
- [Vuex 2: Vuex; The Good Parts—State, Getters, Actions, Mutations](https://slides.com/shortdiv/vuex-2)
- [Vuex 3: Getting Vuex State into SFCs](https://slides.com/shortdiv/vuex-3)
- [Vuex 4: Composing Vuex Actions](https://slides.com/shortdiv/vuex-4)
- [Vuex 5: Vuex Modules](https://slides.com/shortdiv/vuex-5)
- [Vuex 6: Vuex Plugins](https://slides.com/shortdiv/vuex-6)
- [Vuex 7: Vuex + Vue Router](https://slides.com/shortdiv/vuex-7/)

Bonus Content! 
- [Vue 3 aka you might not need Vuex](https://slides.com/shortdiv/vue-3-aka-you-might-not-need-vuex/edit)
- [Vue 3](https://noti.st/shortdiv/mqzBEX/at-vues-end#sdD4BHq)

## Exercises:

### State Management Basics (Codepen)
- Exercise 1: 
Convert the dispense method to using state and actions in a vuex store
https://codepen.io/shortdiv/pen/zYGoVwe
- Exercise 2: 
Convert the restock method to using state and actions in a vuex store
https://codepen.io/shortdiv/pen/rNVjzoe

### Vuex; the Good Parts (Codepen)
- Exercise 1: 
Let's create isRestocking state in Vuex that gets toggled on fetchInventory https://codepen.io/shortdiv/pen/xxGrMLV
- Exercise 2: Switch out the language so it's handled in Vuex https://codepen.io/shortdiv/pen/MWwJXEJ

### Vuex in SFCs (Local Editor)
- Exercise 1: Let's move our vuex store into a separate file
`vuex-sfc[step-0]`
- Exercise 2: Destructure context so it uses the methods commit and dispatch `vuex-sfc[step-1]`
- Exercise 3: Update so that the remaining action and getters are using helpers `vuex-sfc [step-2]`

### Composing Actions (Local Editor)
- Exercise 1: In the `fetchFromInventory` action, dispatch a call to check the machine state action `vuex-compose-actions[step-0]`
- Exercise 2: Create a fail condition, where the machine shows a message when dispensing while stock is < 0 `vuex-compose-actions[step-1]`

### Vuex Modules (Local Editor)
- Exercise 1: Let's move our store, getters, actions and mutations into separate vuex modules `vuex-modules[step-0]`
- Exercise 2: Let's namespace our vuex module and update the actions, and getters in the component appropriately `vuex-modules[step-1]`

### Vuex Modules Cont'd - Static vs Dynamic (Local Editor)
- Exercise 3: In the `operatorView` component, extrapolate the store and dynamically load it so that servicing the primary machine doesn't update the other machines `vuex-static-vs-dynamic-modules[step-0]`
- Exercise 4: Similarly, in the `vendingMachineItem` component, extrapolate the store and dynamically load it `vuex-static-vs-dynamic-modules[step-1]`
- Exercise 5: In the `vendingMachineItem` component, create a unique id for every module, this way, the module for every item isn't shared `vuex-static-vs-dynamic-modules[step-2]`

### Vuex Plugins
- Exercise 1: Let's create our first Vuex Plugin `persistState` `vuex-plugin[master]`
- Exercise 2: Let's modify to use subscribeAction in our Vuex Plugin `persistState` `vuex-plugin[middle-state]`
- Exercise 3: Modify to use subscribeAction (before/after) that listen for action change and register the frequency change `vuex-plugin[end-state]`

### Vuex + Vue Router

### Normalize Vuex State (Local Editor)
- Exercise 1: Let's create a model of Machine in Vuex ORM `vuex-normalize-state[step-0]`
- Exercise 2: Let's create a location model in Vuex ORM `vuex-normalize-state[step-1]`
- Exercise 3: Let's create some helper queries in Vuex ORM `vuex-normalize-state[step-2]`


- [Vuex Workshop Codepen Collection](https://codepen.io/collection/DzPMVV)

## Vue CLI Resources

- [Vue-CLI](https://github.com/vuejs/vue-cli)

## Vuex Resources

- [Vuex docs](https://vuex.vuejs.org/en/)
- [Understanding Vue 3 Closures](https://www.youtube.com/watch?v=KJP1E-Y-xyo)

## VS Code Extensions
https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-extensionpack

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)
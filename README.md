# Vuex Basics - Todo Manager App

Demo application to show Vuex State Management by creating a Todo Manager application. First Project for Vuex Getting Started from the very basics.

## Vuex
- State Management & Pattern Library
- Used most commonly with the Vue framework
- Very similar to Redux, Flux etc
- Centralized store for all components

## Why Use Vuex
- Components need to share state in many cases
- Vuex provides a single source of truth for data/state
- No need to pass events up and props down through multiple components
- Global state is "reactive"

## Vuex Terms
- State: App level state/data (posts, token, todos etc)
- Getters: Get pieces of state or computed values from state
- Actions: Called from components to commit a mutation
- Mutations: Mutate the state (Update data etc)
- Modules: Each module can have its own state, getters, actions and mutations (posts module, auth module, etc) 

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See
[Configuration Reference](https://cli.vuejs.org/config/).


## Reference
See [Here](https://www.youtube.com/watch?v=5lVQgZzLMHc)

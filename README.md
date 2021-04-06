# Reproduction of Bug

https://github.com/vitejs/vite/issues/2889

install, run yarn dev and see this error in the console

```node
Uncaught ReferenceError: isRef is not defined
    at Object.isRef (index.esm.js:1)
    at useToggle (index.esm.js:815)
    at setup (App.vue:18)
    at callWithErrorHandling (runtime-core.esm-bundler.js:154)
    at setupStatefulComponent (runtime-core.esm-bundler.js:6542)
    at setupComponent (runtime-core.esm-bundler.js:6503)
    at mountComponent (runtime-core.esm-bundler.js:4206)
    at processComponent (runtime-core.esm-bundler.js:4182)
    at patch (runtime-core.esm-bundler.js:3791)
    at render2 (runtime-core.esm-bundler.js:4883)
```

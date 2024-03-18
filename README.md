# Arch

- Using bun
- Using Solid.js: no runtime, compiler
  - [Web component buider](https://github.com/solidjs/solid/tree/main/packages/solid-element#readme) (preserves reactivity)
- Styles inline b/c no style frameworks work to build custom elements
  - [CSS reset](https://github.com/sindresorhus/modern-normalize/blob/main/modern-normalize.css) adapted with [`:host` as suggested here](https://www.colorglare.com/css-resets-and-global-styles-in-web-components-c71fcea86dbd).
  - No portals, or styles break

# API

- Event handlers / event emitters
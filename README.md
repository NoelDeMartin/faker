# Faker (fork)

This is a fork of [@faker-js/faker](https://github.com/faker-js/faker) with a `"sideEffects": true` declaration in the package.json, nothing else is changed.

This is done in order to make the library tree-shakable, as discussed in [#1791](https://github.com/faker-js/faker/issues/1791). It is a temporary workaround, and it probably won't be necessary once the issue is resolved in the main library. Use it at your own discretion, as this naive fix may break some existing functionality.

You can install it the same way you'd install the main library, but using `@noeldemartin/faker` instead:

```sh
npm install @noeldemartin/faker
```

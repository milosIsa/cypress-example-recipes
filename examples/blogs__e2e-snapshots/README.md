# End-to-end snapshots

Adding snapshot support to Cypress via 3rd party module [@cypress/snapshot](https://github.com/cypress-io/snapshot) and testing TodoMVC application.

## Blog Post

## Lessons

- Adding `.snapshot()` command by requiring 3rd party module [cypress/support/commands.js](cypress/support/commands.js)
- Capturing and saving snapshots of primitive values [cypress/integration/unit-spec.js](cypress/integration/unit-spec.js)
- Testing central data Vuex store using snapshots [cypress/integration/store-spec.js](cypress/integration/store-spec.js)
- Making assertions against a DOM element using `cy.get('todo-list').snapshot()`  [cypress/integration/ui-spec.js](cypress/integration/ui-spec.js)

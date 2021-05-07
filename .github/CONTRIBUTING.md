# Contribution Guidelines

## General Guidelines

1. Respect the formats and categories described below.
2. Make sure your item is **awesome**.

   - > Only has awesome items. Awesome lists are curations of the best, not everything. _— [Awesome Guidelines](https://github.com/sindresorhus/awesome/blob/master/pull_request_template.md#requirements-for-your-awesome-list)_

3. The item _must_ be added to the bottom of the list.
4. After your pull request, this list must still be elligible for [Awesome](https://github.com/sindresorhus/awesome).

## Formats, naming conventions and descriptions

- Every item _must_ have the following format : `[Item Name](link) - Description.`, except for the adapter category, which doesn't have descriptions.
- Every item and description _must_ be in English.
- Every mention of Inertia.js _must_ use the exact format `Inertia.js`, except for resource names.
  - `✖` InertiaJS
  - `✖` Inertia
  - `✔` Inertia.js
- Descriptions _should not_ start with "The", "A", or similar.
  - `✔` Vue.js adapter.
  - `✖` A Vue.js adapter.
- Descriptions _must_ start with an uppercase character and ends with a period.
- Descriptions _must_ be **short** and **explicit**.
- Descriptions _must_ describe the resource, not be a slogan.

  - `✔` Showcase of products built with Inertia.js.
  - `✖` The best Inertia.js products.

## Categories

### Useful Links

This category must contain must-known resources related to Inertia.js, preferably only official ones.

### Adapters

This category must contain only Inertia.js adapters that comply to the [Inertia.js protocol](https://inertiajs.com/the-protocol).

[Client-side](README.md#client-side) and [server-side](README.md#server-side) adapters must be added to the bottom of their respective sub-categories.

### Resources

This category contains other resources directly related to Inertia.js, such as [presets](README.md#presets) or [articles](README.md#articles). A sub-category can be added if too many related resources are added in the [Other](README.md#other) sub-category.

The [articles](README.md#articles) sub-category's items _must not_ have a description.

## Pull request and commits

You can name your pull request and commits however you want, but for clarity, [conventional commits](http://conventionalcommits.org/) are welcome. Pull request will be squashed upon merge.

Here are the keywords used in this list:

- `add` — For adding a resource to the list.
  - `add(adapters): Vue.js adapter`
- `remove` — For removing a resource to the list.
  - `remove(item-name): outdated resource`
- `update` — For updating a resource to the list.
  - `update(item-name): fix typographical error in description`
- `chore` — For anything else.

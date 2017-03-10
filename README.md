
# Storefront.js

Included here are all the basic tools and building blocks to make an isomorphic
`React.js` storefront powered by the Fox Commerce API Platform.

The tools here fall into a few categories:

- [UI](ui): core interface elements, used to build up more complex components.
- [Components](components): the building blocks for rich storefront experiences.
  - Smart Containers: API & data handling components, usually paired with a presenter.
  - Presenters: Stateless presentation components.
- [Utilities](utils): helpers and tools to make it all happen. Should include
  server and build tooling code as much as possible.
- [Example](examples): the simplest possible storefront implementation.


# Roadmap

Based on [this doc](https://github.com/FoxComm/highlander/blob/feature/new-storefront-for-great-good/demo/peacock/reuse_strategy.md)

### Phase 1: The Basics

Goal: MVP removing elements into this framework repo.

Basically just moving elements from our existing storefronts to this new repo,
doing some minimal optimization and abstraction, but not tackling the more
complex items like a robust inheritance mechanism. We can just do dumb overrides by
changing the `import` statements from `npm` to local path, basically whatever is
required to get it up and running for now.


### Phase 2: Living Styleguide

Goal: Make it possible to spin up multiple storefronts easily.

We need good documentation and a clear way to develop and maintain components
in isolation, so we implement a demo of all components. Example from my time at
littleBits [can be found here](http://ui.littlebits.cc/).


### Phase 3: Open it Up

Goal: Allow 3rd party developers to use and extend our core framework.

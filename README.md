## React Navigation 5

Routing and navigation for your React Native apps.

Documentation can be found at [reactnavigation.org](https://reactnavigation.org/).

## Package Versions

| Name                                                                     |                                                                               Latest Version                                                                                |
| ------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [@react-navigation/core](/packages/core)                                 |                 [![badge](https://img.shields.io/npm/v/@react-navigation/core.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/core)                 |
| [@react-navigation/native](/packages/native)                             |               [![badge](https://img.shields.io/npm/v/@react-navigation/native.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/native)               |
| [@react-navigation/routers](/packages/routers)                           |              [![badge](https://img.shields.io/npm/v/@react-navigation/routers.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/routers)              |
| [@react-navigation/stack](/packages/stack)                               |                [![badge](https://img.shields.io/npm/v/@react-navigation/stack.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/stack)                |
| [@react-navigation/drawer](/packages/drawer)                             |               [![badge](https://img.shields.io/npm/v/@react-navigation/drawer.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/drawer)               |
| [@react-navigation/material-top-tabs](/packages/material-top-tabs)       |    [![badge](https://img.shields.io/npm/v/@react-navigation/material-top-tabs.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/material-top-tabs)    |
| [@react-navigation/material-bottom-tabs](/packages/material-bottom-tabs) | [![badge](https://img.shields.io/npm/v/@react-navigation/material-bottom-tabs.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/material-bottom-tabs) |
| [@react-navigation/bottom-tabs](/packages/bottom-tabs)                   |          [![badge](https://img.shields.io/npm/v/@react-navigation/bottom-tabs.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/bottom-tabs)          |
| [@react-navigation/devtools](/packages/devtools)                         |             [![badge](https://img.shields.io/npm/v/@react-navigation/devtools.svg?style=flat-square)](https://www.npmjs.com/package/@react-navigation/devtools)             |

## Contributing

Please read through our [contribution guide](CONTRIBUTING.md) to get started!

## Installing from a Fork

Since we use a monorepo, it is not possible to install a package from the repository URL.

If you need to install a forked version from Git, you can use [`gitpkg`](https://github.com/ramasilveyra/gitpkg).

First install `gitpkg`:

```
yarn global add gitpkg
```

Then follow these steps to publish a forked package:

1. Fork this repository to your account and clone the forked repository to your local machine.
2. Open a terminal and change the directory to the location of the cloned repository.
3. Run `yarn` to install any dependencies.
4. If you want to make any changes, go ahead and do so. Then commit the changes afterwards.
5. Now change the directory to the package directory that you want to use. For example: `cd packages/stack`.
6. Run `gitpkg publish` to publish the package to your repository. Refer to [`gitpkg`](https://github.com/ramasilveyra/gitpkg) documentation for more details.

After publishing, you should see something like this:

```
Package uploaded to git@git.server:<user>/<repo>.git with the name <name>
```

You can now install the dependency in your project:

```
yarn add <user>/<repo>.git#<name>
```

Remember to replace `<user>`, `<repo>`, and `<name>` with the right values.

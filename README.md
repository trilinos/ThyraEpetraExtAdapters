# ThyraEpetraAdapters

This repository is a **deprecated subpackage** from the Trilinos project and is no longer being supported. This subpackage was last supported in the [Trilinos version 16.2.0 release branch](https://github.com/trilinos/Trilinos/tree/trilinos-release-16-2-branch).

Please see: https://github.com/trilinos/Trilinos


## How to add a deprecated subpackage to an unsupported version of Trilinos

Although this subpackage is **unsupported** in Trilinos versions greather than 16.2.0, if you want to use this deprecated package with a newer version of Trilinos, you can do the following:

1. Clone the Trilinos repository

```shell
git clone https://github.com/trilinos/Trilinos.git
```

2. Clone this deprecated subpackage repository to the `packages` directory in Trilinos

```
cd Trilinos
git clone https://github.com/trilinos/ThyraEpetraAdapters.git packages/thyra/adapters/epetraext
```

3. Proceed to configure, build, and use Trilinos with the deprecated subpackage as previously known.


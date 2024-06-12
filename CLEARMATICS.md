# AirSwap CLI - Clearmatics fork

## How to add a new network

1. Follow the steps from the
   [documentation](https://github.com/clearmatics/airswap-protocols/blob/autonity/CLEARMATICS.md)
   of [clearmatics/airswap-protocols](https://github.com/clearmatics/airswap-protocols/)
1. Update the version of the `@airswap/libraries` dependency in `package.json`
   and bump the module version
1. Install dependencies with `yarn`
1. Commit changes and create a new package with `yarn dist`
1. Create a new release on GitHub and upload the package from the `dist`
   directory

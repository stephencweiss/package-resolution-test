A sample project to demonstrate overrides and selective resoltuions with `npm` and `yarn`.

Steps:

1. Install dependencies with package manager of choice
1. Check the version for `loose-envify` to confirm they're pinned
1. Remove the key to `package.json` for `override` or `resolutions` for `npm` and `yarn` respectively
1. Re-run the install process and check the `lock` file to confirm that versions changed.

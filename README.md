## Justin's TS BoilerPlate

run `npm start` on a terminal one to start the lite server

run `tsc -w FILE.ts` on terminal two to watch changes for a single file

run `tsc -w` to watch all ts files in project

start a new package.json: `npm init`

start a new tsconfig file: `tsc --init`

## Table of Contents

- [Usage](#usage)
- [More](#more)
- [Support](#support)
- [Contributing](#contributing)

## Usage

- Configured tsconfig.json
  - Exclude
    - configured to ignore excluded.ts to have it setup it for the user, can be removed. other settings could be wild card if desired. "_.dev.ts or \*\*/_.dev.ts"
    - Node_modules is added as well, not required it is excluded by default, but here as well for placement to see you can do this for when its added
  - Include
    - Not configured, when set you need to include everything you want to do. by default it includes all, can be done by file or folder
  - Files
    - Not included, added like Include, but files

## More

more information coming soon...

## Support

Please [open an issue](https://github.com/haney2121/TS-BoilerPlate/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/haney2121/TS-BoilerPlate/compare).
